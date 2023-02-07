<script>
export default {
    name: 'BlogRightbar',
}
</script>

<template>
    <!-- Right sidebar -->
    <aside class="cf ck rs">

        <div class="ir">

            <!-- Newsletter widget -->
            <div class="im ib iz lf lp ld lv fr fs sj">
                <div class="ov tt">
                    <div class="tz ii tr">
                        <img class="iv iw se lf tk" src="../assets/images/avatar-01.jpg" width="24" height="24" alt="Avatar 01">
                        <img class="iv iw se lf tk" src="../assets/images/avatar-02.jpg" width="24" height="24" alt="Avatar 02">
                        <img class="iv iw se lf tk" src="../assets/images/avatar-03.jpg" width="24" height="24" alt="Avatar 03">
                        <img class="iv iw se lf tk" src="../assets/images/avatar-04.jpg" width="24" height="24" alt="Avatar 04">
                        <img class="iv iw se lf tk" src="../assets/images/avatar-05.jpg" width="24" height="24" alt="Avatar 05">
                    </div>
                </div>
                <div class="ov ts">
                    <div class="og oz tt">Never miss an update!</div>
                    <p class="ob uf lb">Subscribe and join 100K+ developers.</p>
                </div>
                <form>
                    <div class="to">
                        <label class="p" for="newsletter">Your email…</label>
                        <input id="newsletter" type="email" class="i ot nv" placeholder="Your email…">
                    </div>
                    <button class="n nv  ua su fa" type="submit">Subscribe</button>
                </form>
            </div>

            <!-- Sponsor widget -->
            <div class="im ib iz lf lp ld lv fr fs sj">
                <div class="tq rw is to">
                    <svg xmlns="http://www.w3.org/2000/svg" width="28" height="20">
                        <path fill="#38BDF8" fill-rule="evenodd"
                            d="M.73 6.173a9.92 9.92 0 0 1 3.527-4.488A9.294 9.294 0 0 1 9.58 0h.737v4.67l.14-.226a9.68 9.68 0 0 1 4.3-3.683A9.205 9.205 0 0 1 20.29.192a9.461 9.461 0 0 1 4.904 2.737 10.143 10.143 0 0 1 2.622 5.12c.37 1.94.18 3.95-.545 5.778a9.92 9.92 0 0 1-3.528 4.488A9.294 9.294 0 0 1 18.42 20h-.737v-4.67a10.459 10.459 0 0 1-.14.226 9.68 9.68 0 0 1-4.3 3.683 9.205 9.205 0 0 1-5.534.569 9.461 9.461 0 0 1-4.904-2.737 10.143 10.143 0 0 1-2.622-5.12C-.186 10.01.004 8 .73 6.173ZM8.841 10V1.573a7.89 7.89 0 0 0-3.766 1.391A8.394 8.394 0 0 0 2.09 6.762a8.808 8.808 0 0 0-.462 4.889 8.583 8.583 0 0 0 2.219 4.332 8.006 8.006 0 0 0 4.15 2.316 7.789 7.789 0 0 0 4.683-.482 8.18 8.18 0 0 0 3.528-2.95 4.958 4.958 0 0 1-2.209.518c-2.849 0-5.158-2.411-5.158-5.385Zm10.316 8.427a7.89 7.89 0 0 0 3.766-1.391 8.393 8.393 0 0 0 2.985-3.798 8.807 8.807 0 0 0 .462-4.889 8.583 8.583 0 0 0-2.219-4.332 8.006 8.006 0 0 0-4.15-2.316 7.789 7.789 0 0 0-4.683.482 8.179 8.179 0 0 0-3.528 2.95A4.958 4.958 0 0 1 14 4.615c2.849 0 5.158 2.411 5.158 5.385v8.427Z">
                        </path>
                    </svg>
                    <span class="ow uo ly">*Sponsor</span>
                </div>
                <div class="og oz tt">Build The Site You Want!</div>
                <p class="ob uf lb">Your website should be an asset, not an engineering challenge.</p>
            </div>

            <!-- E-Book widget -->
            <div class="im ib iz lf lp ld lv fr fs sj">
                <div class="og oz ov ta">Free E-Book</div>
                <div class="ov">
                    <img class="tz im uq rf" src="../assets/images/book.png" width="148" height="190" alt="Book">
                </div>
            </div>

        </div>

    </aside>

</template>

