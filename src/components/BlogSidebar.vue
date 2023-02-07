<script>
export default {
    name: 'BlogSidebar',
}
</script>

<template>
    <!-- Side navigation -->
    <div class="g b nd ca rs nr id f ik iz lf">
        <div class="ni tq rm r_ ft aq">
            <div class="ri"></div>
            <div class="ri ro tq rw">
                <nav class="nv">
                    <ul class="rz">
                        <li class="sz">
                            <router-link active-class="exact-active-link" class="active-link" to="/">
                                <span class="p">Home</span>
                                <svg class="sv" xmlns="http://www.w3.org/2000/svg" width="21" height="19">
                                    <path fill-opacity=".16" d="M4 7v11h13V7l-6.5-5z"></path>
                                    <path
                                        d="m10.433 3.242-8.837 6.56L.404 8.198l10.02-7.44L20.59 8.194l-1.18 1.614-8.977-6.565ZM16 17V9h2v10H3V9h2v8h11Z">
                                    </path>
                                </svg>
                            </router-link>
                        </li>
                        <li class="sz">
                            <router-link active-class="exact-active-link" class="active-link" to="/about">
                                <span class="p">About</span>
                                <svg class="sv" xmlns="http://www.w3.org/2000/svg" width="20" height="20">
                                    <path fill-opacity=".16"
                                        d="M10 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8Z"></path>
                                    <path
                                        d="M9 5h2v2H9V5Zm0 4h2v6H9V9Zm1-9C4.48 0 0 4.48 0 10s4.48 10 10 10 10-4.48 10-10S15.52 0 10 0Zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8Z">
                                    </path>
                                </svg>
                            </router-link>
                        </li>
                        <li class="sz">
                            <router-link active-class="exact-active-link" class="active-link" to="/subscribe">
                                <span class="p">Subscribe</span>
                                <svg class="sv" xmlns="http://www.w3.org/2000/svg" width="21" height="21">
                                    <path fill-opacity=".16" d="m13.4 18-3-7.4-7.4-3L19 2z"></path>
                                    <path
                                        d="M13.331 15.169 17.37 3.63 5.831 7.669l5.337 2.163 2.163 5.337Zm-3.699-3.801L.17 7.53 20.63.37l-7.161 20.461-3.837-9.463Z">
                                    </path>
                                </svg>
                            </router-link>
                        </li>
                    </ul>
                </nav>
            </div>
        </div>
    </div>
</template>
