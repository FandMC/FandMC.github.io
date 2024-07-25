<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FandMC 服务器</title>
    <meta name="description" content="FandMC 是一个 Minecraft 服务器，旨在提供极致生电体验的服务器软件。">
    <link rel="icon" href="favicon.ico">
    <link rel="stylesheet" href="css.css">
</head>
<body>
    <div id="__next">
        <nav class="fixed top-0 left-0 right-0 z-50 transition-shadow">
            <div class="max-w-7xl flex flex-row items-center mx-auto px-4 py-2 gap-2">
                <a href="https://github.com/FandMC/FandServer" class="inline-block h-min w-min rounded-full p-2 transition-colors hover:bg-gray-800/20 dark:hover:bg-gray-400/20 leading-0" aria-label="GitHub" target="_blank">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 496 512" class="h-6 w-6 fill-gray-700 dark:fill-gray-300">
                        <path d="M165.9 397.4c0 2-2.3 3.6-5.2 3.6-3.3.3-5.6-1.3-5.6-3.6 0-2 2.3-3.6 5.2-3.6 3-.3 5.6 1.3 5.6 3.6m-31.1-4.5c-.7 2 1.3 4.3 4.3 4.9 2.6 1 5.6 0 6.2-2s-1.3-4.3-4.3-5.2c-2.6-.7-5.5.3-6.2 2.3m44.2-1.7c-2.9.7-4.9 2.6-4.6 4.9.3 2 2.9 3.3 5.9 2.6 2.9-.7 4.9-2.6 4.6-4.6-.3-1.9-3-3.2-5.9-2.9M244.8 8C106.1 8 0 113.3 0 252c0 110.9 69.8 205.8 169.5 239.2 12.8 2.3 17.3-5.6 17.3-12.1 0-6.2-.3-40.4-.3-61.4 0 0-70 15-84.7-29.8 0 0-11.4-29.1-27.8-36.6 0 0-22.9-15.7 1.6-15.4 0 0 24.9 2 38.6 25.8 21.9 38.6 58.6 27.5 72.9 20.9 2.3-16 8.8-27.1 16-33.7-55.9-6.2-112.3-14.3-112.3-110.5 0-27.5 7.6-41.3 23.6-58.9-2.6-6.5-11.1-33.3 2.6-67.9 20.9-6.5 69 27 69 27 20-5.6 41.5-8.5 62.8-8.5s42.8 2.9 62.8 8.5c0 0 48.1-33.6 69-27 13.7 34.7 5.2 61.4 2.6 67.9 16 17.7 25.8 31.5 25.8 58.9 0 96.5-58.9 104.2-114.8 110.5 9.2 7.9 17 22.9 17 46.4 0 33.7-.3 75.4-.3 83.6 0 6.5 4.6 14.4 17.3 12.1C428.2 457.8 496 362.9 496 252 496 113.3 383.5 8 244.8 8M97.2 352.9c-1.3 1-1 3.3.7 5.2 1.6 1.6 3.9 2.3 5.2 1 1.3-1 1-3.3-.7-5.2-1.6-1.6-3.9-2.3-5.2-1m-10.8-8.1c-.7 1.3.3 2.9 2.3 3.9 1.6 1 3.6.7 4.3-.7.7-1.3-.3-2.9-2.3-3.9-2-.6-3.6-.3-4.3.7m32.4 35.6c-1.6 1.3-1 4.3 1.3 6.2 2.3 2.3 5.2 2.6 6.5 1 1.3-1.3.7-4.3-1.3-6.2-2.2-2.3-5.2-2.6-6.5-1m-11.4-14.7c-1.6 1-1.6 3.6 0 5.9s4.3 3.3 5.6 2.3c1.6-1.3 1.6-3.9 0-6.2-1.4-2.3-4-3.3-5.6-2"></path>
                    </svg>
                </a>
                <div class="flex-grow"></div>
                <div class="color-gray-200 hover:text-green-600 dark:hover:text-green-400 text-sm transition-colors px-2.5 inline-block h-full">
                    <span class="flex flex-row items-center gap-1" role="button">语言 <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="w-4 h-4 fill-gray-700 dark:fill-gray-300" viewBox="0 0 20 20">
                        <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 0 1 1.414 0L10 10.586l3.293-3.293a1 1 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0l-4-4a1 1 0 0 1 0-1.414" clip-rule="evenodd"></path>
                    </svg></span>
                    <div class="language-dropdown-content hidden">
                        <a href="#" onclick="setLanguage('zh-CN')">简体中文（中国大陆）</a>
                        <a href="#" onclick="setLanguage('en-US')">English (US)</a>
                    </div>
                </div>
            </div>
        </nav>
        <main class="flex-1">
            <header class="max-w-7xl flex flex-row mx-auto px-4 pt-32 pb-26 lg:pt-48 lg:pb-46">
                <div class="flex-1">
                    <h1 class="font-medium leading-normal lg:text-5xl lg:leading-normal text-4xl">纯净<br><span class="text-green-500">专为生电设计</span></h1>
                    <p class="text-xl mt-4">FandMC 改变了 Minecraft 的生态系统，提供快速、安全和稳定的软件，作为精简独立运行的轻型快速生电模板支持。</p>
                    <div class="flex flex-row gap-4 mt-8">
                        <a role="button" class="font-medium px-6 py-1.5 rounded-md hover:shadow-md transition text-md bg-green-600 hover:bg-green-500 text-white" href="https://github.com/FandMC/FandServer/releases">下载</a>
                        <a role="button" class="font-medium px-6 py-1.5 rounded-md hover:shadow-md transition text-md border-1 border-gray-400 dark:border-gray-600 hover:bg-gray-100 dark:hover:bg-gray-800" href="http://fandmc.top">文档</a>
                    </div>
                </div>
                <div class="flex-1 lg:flex hidden justify-end">
                    <div class="max-h-82 w-120 h-283 rounded-lg bg-gray-800">
                        <div class="w-full bg-gray-900 rounded-t-lg flex p-2 gap-2">
                            <div class="w-2.5 h-2.5 bg-red-500 rounded-full"></div>
                            <div class="w-2.5 h-2.5 bg-yellow-500 rounded-full"></div>
                            <div class="w-2.5 h-2.5 bg-green-500 rounded-full"></div>
                        </div>
                        <div class="max-h-74 p-4 font-mono text-xs text-white overflow-y-hidden flex flex-col-reverse">
                            <div id="log"></div>
                            <div>Loading libraries, please wait...</div>
                            <div class="prompt">$ <span class="command">java -jar fand.jar</span></div>
                        </div>
                    </div>
                </div>
            </header>
            <section id="software" class="w-full pt-12 pb-8 bg-green-100 dark:bg-background-dark-80">
                <div class="max-w-7xl mx-auto">
                    <h2 class="font-semibold text-xl md:text-2xl px-6 lg:px-4 mb-4">你的服务器值得更大惊喜。<span class="text-green-500">更多光彩。</span></h2>
                    <div class="grid md:grid-cols-3 md:-ml-4 gap-2 px-2 xl:gap-4">
                        <a href="https://github.com/FandMC/FandServer">
                            <article class="rounded-xl transition-all h-full p-4 md:p-8 hover:shadow-lg hover:bg-green-200 hover:dark:bg-gray-800">
                                <div class="flex flex-row items-center gap-4">
                                    <div class="rounded-lg w-12 h-12 bg-gray-800 p-3">
                                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 256 256">
                                            <path fill="#fff" d="M224 39.5a8.1 8.1 0 0 0-7.5-7.5C140.2 27.5 79.1 50.5 53 93.6a87.3 87.3 0 0 0-12.8 49.1c.6 15.9 5.2 32.1 13.8 48L154.3 90.3a8.1 8.1 0 0 1 11.4 11.4L65.3 202c15.9 8.6 32.1 13.2 48 13.8h3.3a87 87 0 0 0 45.8-12.8c43.1-26.1 66.1-87.2 61.6-163.5"></path>
                                            <path fill="#fff" d="M57.1 196.1c-1.1-1.8-2.1-3.6-3.1-5.4l-19.7 19.6a8.1 8.1 0 0 0 0 11.4 8.2 8.2 0 0 0 11.4 0L65.3 202l-5.4-3.1a9.3 9.3 0 0 1-2.8-2.8"></path>
                                        </svg>
                                    </div>
                                    <h3 class="font-medium flex-1">FandMC</h3>
                                </div>
                                <p class="text-gray-800 dark:text-gray-200 mt-4">FandMC 是一个 Minecraft 服务器，旨在提供极致生电体验的服务器软件。</p>
                            </article>
                        </a>
                    </div>
                </div>
            </section>
            <section id="facts" class="flex flex-col max-w-7xl mx-auto px-4 py-8 gap-8 md:gap-12 md:py-16">
                <div class="flex flex-col gap-6 md:flex-row md:gap-8 xl:gap-24 items-center">
                    <div class="w-full flex-1 rounded-xl bg-gray-900 aspect-video relative overflow-clip">
                        <img alt="Screenshot" loading="lazy" decoding="async" data-nimg="fill" class="object-cover" src="screenshot.png" sizes="(min-width: 80rem) 40rem, (min-width: 768px) 40vw, 100vw">
                    </div>
                    <div class="flex-1">
                        <h2 class="font-semibold text-2xl md:text-4xl break-all">为 <span class="rounded-md bg-gray-400/40 animate-pulse h-6 w-auto w-30 h-6 inline-block">588+</span> 位玩家提供支持</h2>
                        <p class="md:mt-6 md:text-xl text-gray-900 dark:text-gray-100 mt-3">FandMC 的软件在设计之初就考虑到了实用性和性能，可以处理任何需要处理的事物。</p>
                    </div>
                </div>
            </section>
        </main>
        <footer class="bg-background-dark-80 py-12 mt-8 Footer_footer__tM8eX">
            <div class="max-w-7xl m-auto px-4">
                <div class="grid gap-10 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 text-sm text-white">
                    <div>
                        <span class="font-semibold">入门</span>
                        <ul class="mt-4 leading-5 text-gray-400 space-y-2">
                            <li><a href="https://github.com/FandMC/FandServer/releases">下载</a></li>
                            <li><a href="http://fandmc.top" target="_blank">文档</a></li>
                        </ul>
                    </div>
                    <div>
                        <span class="font-semibold">社区</span>
                        <ul class="mt-4 leading-5 text-gray-400 space-y-2">
                            <li><a href="https://github.com/FandMC/FandServer" target="_blank" rel="noreferrer">GitHub</a></li>
                            <li><a href="http://qm.qq.com/cgi-bin/qm/qr?_wv=1027&k=QHppZv41_pMbojSt2HuESA-n1lWaQoEU&authKey=CJywB2ahZYrSxAmeCkJ7SfI%2FBIjQ4y69at%2BkTPfqiqj0VMYe0Af63XzsCw3zXgyW&noverify=0&group_code=495796642" target="_blank" rel="noreferrer">QQ 群</a></li>
                        </ul>
                    </div>
                </div>
                <div class="flex flex-row items-center gap-2 border-t border-gray-600/50 mt-8 pt-10">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 128 128" class="h-12 cursor-pointer" alt="FandMC">
                        <g>
                            <mask id="logo_svg__b" fill="#fff">
                                <use xlink:href="#logo_svg__a"></use>
                            </mask>
                            <g mask="url(#logo_svg__b)">
                                <path fill-rule="evenodd" d="M67.867 104.601c10.43-2.51 19.09-10.13 23.87-18.75 2.93-5.28 5.6-10.72 6.29-23.32.64-11.43-1.05-29.89-6.07-36.6-6.46 0-13.89 1.04-23.48 3.52-8.78 2.28-19.17 8.5-25.83 14.69-13.45 12.49-20.18 41.13.58 58.75 12.11 2.94 17.52 3.42 24.64 1.71" style="fill:#40794f"></path>
                                <path d="M67.399 102.657a31.7 31.7 0 0 0 7.016-2.613 35.7 35.7 0 0 0 6.246-4.08 38.4 38.4 0 0 0 5.263-5.184 37.5 37.5 0 0 0 4.064-5.899q1.302-2.346 2.057-3.972a37 37 0 0 0 1.768-4.568q.846-2.72 1.38-5.921.596-3.585.837-7.998.243-4.333.026-9.403-.229-5.356-.922-10.279-.752-5.339-1.937-9.293-1.258-4.2-2.841-6.318l1.601-1.198v2q-4.793 0-10.274.809-5.742.846-12.705 2.647-3.066.797-6.51 2.286a65 65 0 0 0-6.701 3.389q-3.3 1.905-6.333 4.11a59 59 0 0 0-5.425 4.434q-2.377 2.207-4.42 5.081a40 40 0 0 0-3.632 6.27 42.6 42.6 0 0 0-2.577 7.127 41.2 41.2 0 0 0-1.277 7.649 37.7 37.7 0 0 0 .252 7.844 34.4 34.4 0 0 0 1.996 7.734 33.5 33.5 0 0 0 3.968 7.349q2.6 3.648 6.202 6.706l-1.294 1.525.472-1.943q4.666 1.132 7.851 1.725 3.397.63 6.014.822 2.607.19 4.977-.019 2.28-.2 4.859-.82zm.935 3.889q-2.866.689-5.442.915a35 35 0 0 1-5.62.024q-2.838-.207-6.453-.88-3.291-.612-8.064-1.77l-.46-.112-.362-.307q-3.983-3.38-6.872-7.435a37.5 37.5 0 0 1-4.439-8.223 38.4 38.4 0 0 1-2.229-8.63 41.7 41.7 0 0 1-.28-8.676q.297-4.215 1.4-8.39a46.6 46.6 0 0 1 2.818-7.795 44 44 0 0 1 3.998-6.897q2.28-3.21 4.956-5.694a63 63 0 0 1 5.797-4.738q3.203-2.33 6.685-4.34a69 69 0 0 1 7.112-3.596q3.729-1.612 7.097-2.487 7.17-1.854 13.123-2.732 5.771-.852 10.858-.852h1.002l.6.802q2.009 2.685 3.47 7.567 1.271 4.244 2.066 9.882.72 5.115.958 10.667.225 5.266-.029 9.791-.254 4.633-.886 8.436-.577 3.473-1.506 6.455a41 41 0 0 1-1.96 5.063q-.815 1.756-2.186 4.227a41.5 41.5 0 0 1-4.495 6.528 42.4 42.4 0 0 1-5.81 5.722 39.7 39.7 0 0 1-6.947 4.535 35.7 35.7 0 0 1-7.9 2.94z" style="fill:#40794f;opacity:1"></path>
                                <path d="M39.33 17.524a.496.496 0 0 1-.361.48.5.5 0 0 1-.09.018A48.6 48.6 0 0 0 28.09 20.24a44 44 0 0 0-6.073 2.512l-.45-.893a45 45 0 0 1 6.21-2.569 49.6 49.6 0 0 1 11.053-2.265.5.5 0 0 1 .5.5M10.747 25.902q.241 1.619.65 4.699.302 2.26.462 3.383.265 1.86.524 3.374l-.986.168q-.261-1.527-.528-3.4-.16-1.128-.462-3.394a326 326 0 0 0-.65-4.683q-.4-2.694-.85-5.05A111 111 0 0 0 5.862 8.911a.497.497 0 0 1 .286-.61.5.5 0 0 1 .67.313 112 112 0 0 1 3.07 12.197q.455 2.377.859 5.091M40.123 43.014a.5.5 0 0 1-.432.495q-9.804 1.557-21.192 4.549A277 277 0 0 0 4.115 52.25l-.306-.952a278 278 0 0 1 14.436-4.208q11.442-3.006 21.299-4.57a.498.498 0 0 1 .579.494" style="fill:#fff;opacity:1" transform="translate(40.31 44.252)"></path>
                                <path d="M38.538 0q0 .166-.099.298l.002.001q-8.097 10.846-12.817 17.392-5.97 8.28-9.544 13.8-7.001 10.807-10.906 19.45a82 82 0 0 0-2.523 6.226q-.625 1.752-1.44 4.416a61 61 0 0 1-.74 2.305l-.942-.336q.229-.64.725-2.262.823-2.685 1.455-4.459a83 83 0 0 1 2.554-6.302q3.936-8.712 10.977-19.58 3.588-5.542 9.573-13.843 4.719-6.543 12.802-17.373a.498.498 0 0 1 .839-.01.5.5 0 0 1 .084.277" style="fill:#fff;opacity:1" transform="translate(40.31 44.252)"></path>
                            </g>
                        </g>
                        <defs>
                            <path id="logo_svg__a" d="M0 0h128v128H0z"></path>
                        </defs>
                    </svg>
                    <div class="flex-1"></div>
                    <span class="text-gray-300 text-sm" style="text-align:right">
                        © 2024 FandMC 版权所有。
                    </span>
                </div>
            </div>
        </footer>
    </div>
    <script>
        function getCurrentTime() {
            const now = new Date();
            return now.toLocaleTimeString('zh-CN', { hour12: false });
        }

        function updateTerminalLog() {
            const log = document.getElementById('log');
            log.innerHTML = `
                <div>[${getCurrentTime()} INFO]: Starting minecraft server version 1.20.6</div>
                <div>[${getCurrentTime()} INFO]: Preparing level "world"</div>
                <div>[${getCurrentTime()} INFO]: Preparing start region for dimension minecraft:overworld</div>
                <div>[${getCurrentTime()} INFO]: Time elapsed: 363 ms</div>
                <div>[${getCurrentTime()} INFO]: Preparing start region for dimension minecraft:the_nether</div>
                <div>[${getCurrentTime()} INFO]: Time elapsed: 147 ms</div>
                <div>[${getCurrentTime()} INFO]: Preparing start region for dimension minecraft:the_end</div>
                <div>[${getCurrentTime()} INFO]: Time elapsed: 366 ms</div>
                <div>[${getCurrentTime()} INFO]: Running delayed init tasks</div>
                <div>[${getCurrentTime()} INFO]: Done (2.274s)! For help, type "help"</div>
            `;
        }

        function setLanguage(language) {
            if (language === 'zh-CN') {
                document.getElementById("hero-text").innerHTML = `
                    <h1>纯净</h1>
                    <p>专为生电设计</p>
                    <p>FandMC 改变了 Minecraft 的生态系统，提供快速、安全和稳定的软件，作为精简独立运行的轻型快速生电模板支持。</p>
                    <div class="hero-buttons">
                        <a href="https://github.com/FandMC/FandServer/releases">下载</a>
                        <a href="http://fandmc.top">文档</a>
                    </div>
                `;
                document.querySelector("#section-content1 h2").textContent = "你的服务器值得更大惊喜。";
                document.querySelector("#section-content1 p").textContent = "FandMC 是一个 Minecraft 服务器，旨在提供极致生电体验的服务器软件。";
                document.querySelector("#section-content2 h2").textContent = "为 588+ 位玩家提供支持";
                document.querySelector("#section-content2 p").textContent = "FandMC 的软件在设计之初就考虑到了实用性和性能，可以处理任何需要处理的事物。";
            } else if (language === 'en-US') {
                document.getElementById("hero-text").innerHTML = `
                    <h1>Pure</h1>
                    <p>Designed for Survival</p>
                    <p>FandMC changes the Minecraft ecosystem, providing fast, secure, and stable software as a light and independent quick survival template support.</p>
                    <div class="hero-buttons">
                        <a href="https://github.com/FandMC/FandServer/releases">Download</a>
                        <a href="http://fandmc.top">Documentation</a>
                    </div>
                `;
                document.querySelector("#section-content1 h2").textContent = "Your server deserves greater surprises.";
                document.querySelector("#section-content1 p").textContent = "FandMC is a Minecraft server aimed at providing the ultimate survival experience.";
                document.querySelector("#section-content2 h2").textContent = "Supporting 588+ players";
                document.querySelector("#section-content2 p").textContent = "FandMC's software is designed with utility and performance in mind, it can handle whatever you throw at it.";
            }
        }

        document.getElementById("language-select").addEventListener("click", function(event) {
            event.preventDefault();
            const dropdown = document.querySelector(".language-dropdown-content");
            dropdown.classList.toggle("hidden");
        });

        window.onclick = function(event) {
            if (!event.target.matches('#language-select')) {
                const dropdowns = document.getElementsByClassName("language-dropdown-content");
                for (let i = 0; i < dropdowns.length; i++) {
                    const openDropdown = dropdowns[i];
                    if (!openDropdown.classList.contains("hidden")) {
                        openDropdown.classList.add("hidden");
                    }
                }
            }
        };

        updateTerminalLog();
    </script>
</body>
</html>
