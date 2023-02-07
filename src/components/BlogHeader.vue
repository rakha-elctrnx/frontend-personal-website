<script>
export default {
    name: 'BlogHeader',
}
</script>

<template>
    <!-- Header -->
    <header>
        <div class="tq rw r_ no ac">
            <div class="ro tq rx ie">
                <!-- Search form -->
                <form class="nv nq">
                    <div class="tq rg">
                        <div class="nv">
                            <label class="t_ ob p" for="search">Search</label>
                            <div class="m tq rw">
                                <input id="search" type="search" class="i ot nv of">
                                <div class="v y w tq rw rk">
                                    <svg class="nm nu rs j" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
                                        <path class="sm"
                                            d="M7 14c-3.86 0-7-3.14-7-7s3.14-7 7-7 7 3.14 7 7-3.14 7-7 7zM7 2C4.243 2 2 4.243 2 7s2.243 5 5 5 5-2.243 5-5-2.243-5-5-5zm8.707 12.293a.999.999 0 11-1.414 1.414L11.9 13.314a8.019 8.019 0 001.414-1.414l2.393 2.393z">
                                        </path>
                                    </svg>
                                </div>
                            </div>
                        </div>
                    </div>
                </form>

                <!-- Light switch -->
                <div class="tq rm rk z">
                    <input type="checkbox" name="light-switch" id="light-switch" class="light-switch p">
                    <label class="m rc s_" for="light-switch">
                        <svg class="la" width="16" height="16" xmlns="http://www.w3.org/2000/svg">
                            <path class="sg"
                                d="M7 0h2v2H7zM12.88 1.637l1.414 1.415-1.415 1.413-1.413-1.414zM14 7h2v2h-2zM12.95 14.433l-1.414-1.413 1.413-1.415 1.415 1.414zM7 14h2v2H7zM2.98 14.364l-1.413-1.415 1.414-1.414 1.414 1.415zM0 7h2v2H0zM3.05 1.706 4.463 3.12 3.05 4.535 1.636 3.12z">
                            </path>
                            <path class="sm" d="M8 4C5.8 4 4 5.8 4 8s1.8 4 4 4 4-1.8 4-4-1.8-4-4-4Z"></path>
                        </svg>
                        <svg class="nt lu" width="16" height="16" xmlns="http://www.w3.org/2000/svg">
                            <path class="sm"
                                d="M6.2 1C3.2 1.8 1 4.6 1 7.9 1 11.8 4.2 15 8.1 15c3.3 0 6-2.2 6.9-5.2C9.7 11.2 4.8 6.3 6.2 1Z">
                            </path>
                            <path class="sy"
                                d="M12.5 5a.625.625 0 0 1-.625-.625 1.252 1.252 0 0 0-1.25-1.25.625.625 0 1 1 0-1.25 1.252 1.252 0 0 0 1.25-1.25.625.625 0 1 1 1.25 0c.001.69.56 1.249 1.25 1.25a.625.625 0 1 1 0 1.25c-.69.001-1.249.56-1.25 1.25A.625.625 0 0 1 12.5 5Z">
                            </path>
                        </svg>
                        <span class="p">Switch to light / dark version</span>
                    </label>
                </div>

                <!-- Button -->
                <div>
                    <a class="n ua su fa" href="subscribe.html">Login</a>
                </div>

            </div>

        </div>
    </header>
</template>

