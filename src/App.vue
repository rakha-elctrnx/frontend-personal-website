<template>
  <div class="n_ k">
    <div class="np tq">
      <BlogSidebar />
      <!-- Main content -->
      <main class="ro ih oe">
        <div class="nv ni nj k tq rm">
          <BlogHeader />
          <router-view />
          <BlogFooter />
        </div>
      </main>
    </div>
  </div>
</template>

<script>
import BlogSidebar from '@/components/BlogSidebar.vue'
import BlogHeader from '@/components/BlogHeader.vue'
import BlogFooter from '@/components/BlogFooter.vue'

export default {
  name: 'AppView',
  components: {
    BlogSidebar,
    BlogHeader,
    BlogFooter
  },
  mounted() {
    console.log(`the component is now mounted.`)
    if (localStorage.getItem('dark-mode') === 'false' || !('dark-mode' in localStorage)) {
            document.querySelector('html').classList.remove('dark');
        } else {
            document.querySelector('html').classList.add('dark');
        }
        
    const lightSwitches = document.querySelectorAll('.light-switch');
    if (lightSwitches.length > 0) {
      lightSwitches.forEach((lightSwitch, i) => {
        if (localStorage.getItem('dark-mode') === 'true') {
          // eslint-disable-next-line no-param-reassign
          lightSwitch.checked = true;
        }
        lightSwitch.addEventListener('change', () => {
          const { checked } = lightSwitch;
          lightSwitches.forEach((el, n) => {
            if (n !== i) {
              // eslint-disable-next-line no-param-reassign
              el.checked = checked;
            }
          });
          if (lightSwitch.checked) {
            document.documentElement.classList.add('dark');
            localStorage.setItem('dark-mode', true);
          } else {
            document.documentElement.classList.remove('dark');
            localStorage.setItem('dark-mode', false);
          }
        });
      });
    }
    
  },
};
</script>

<style src="./assets/tailwind.css"></style>
<style src="./assets/main.css"></style>
