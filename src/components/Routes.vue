<template>
    <div class="w-full bg-no-repeat bg-cover py-20" style="background-image: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz4KPHN2ZyB3aWR0aD0iMTQ0MHB4IiBoZWlnaHQ9IjEzODZweCIgdmlld0JveD0iMCAwIDE0NDAgMTM4NiIgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIj4KICAgIDwhLS0gR2VuZXJhdG9yOiBTa2V0Y2ggNTQuMSAoNzY0OTApIC0gaHR0cHM6Ly9za2V0Y2hhcHAuY29tIC0tPgogICAgPHRpdGxlPlRydXN0ZWQgYWxsIG92ZSB0aGUgd29ybGQ8L3RpdGxlPgogICAgPGRlc2M+Q3JlYXRlZCB3aXRoIFNrZXRjaC48L2Rlc2M+CiAgICA8ZGVmcz4KICAgICAgICA8cmVjdCBpZD0icGF0aC0xIiB4PSIwIiB5PSIwIiB3aWR0aD0iMTQ0MCIgaGVpZ2h0PSIxMzg2Ij48L3JlY3Q+CiAgICAgICAgPGxpbmVhckdyYWRpZW50IHgxPSI2Mi4wMTk2Mzg3JSIgeTE9Ii0wLjMxMzMxMTY4OCUiIHgyPSI0NC4xOTg1NzMyJSIgeTI9Ijc1LjE1NjY1NTglIiBpZD0ibGluZWFyR3JhZGllbnQtMyI+CiAgICAgICAgICAgIDxzdG9wIHN0b3AtY29sb3I9IiM1NzRBRTIiIG9mZnNldD0iMCUiPjwvc3RvcD4KICAgICAgICAgICAgPHN0b3Agc3RvcC1jb2xvcj0iIzU3NEFFMiIgc3RvcC1vcGFjaXR5PSIwLjU5IiBvZmZzZXQ9IjU3JSI+PC9zdG9wPgogICAgICAgICAgICA8c3RvcCBzdG9wLWNvbG9yPSIjNTc0QUUyIiBzdG9wLW9wYWNpdHk9IjAuMjQiIG9mZnNldD0iODclIj48L3N0b3A+CiAgICAgICAgICAgIDxzdG9wIHN0b3AtY29sb3I9IiM1NzRBRTIiIHN0b3Atb3BhY2l0eT0iMC4xIiBvZmZzZXQ9IjEwMCUiPjwvc3RvcD4KICAgICAgICA8L2xpbmVhckdyYWRpZW50PgogICAgICAgIDxsaW5lYXJHcmFkaWVudCB4MT0iNjIuMDE5NjM4NyUiIHkxPSItMC4zMTMzMTE2ODglIiB4Mj0iNDQuMTk4NTczMiUiIHkyPSI3NS4xNTY2NTU4JSIgaWQ9ImxpbmVhckdyYWRpZW50LTQiPgogICAgICAgICAgICA8c3RvcCBzdG9wLWNvbG9yPSIjNTc0QUUyIiBvZmZzZXQ9IjAlIj48L3N0b3A+CiAgICAgICAgICAgIDxzdG9wIHN0b3AtY29sb3I9IiM1NzRBRTIiIHN0b3Atb3BhY2l0eT0iMC41OSIgb2Zmc2V0PSI1NyUiPjwvc3RvcD4KICAgICAgICAgICAgPHN0b3Agc3RvcC1jb2xvcj0iIzU3NEFFMiIgc3RvcC1vcGFjaXR5PSIwLjI0IiBvZmZzZXQ9Ijg3JSI+PC9zdG9wPgogICAgICAgICAgICA8c3RvcCBzdG9wLWNvbG9yPSIjNTc0QUUyIiBzdG9wLW9wYWNpdHk9IjAuMSIgb2Zmc2V0PSIxMDAlIj48L3N0b3A+CiAgICAgICAgPC9saW5lYXJHcmFkaWVudD4KICAgICAgICA8bGluZWFyR3JhZGllbnQgeDE9IjU2LjI1OTA1OTQlIiB5MT0iMjMuODM3MDc3OSUiIHgyPSIzOC4zNjU3MjczJSIgeTI9IjEwMC4zMTMzMTIlIiBpZD0ibGluZWFyR3JhZGllbnQtNSI+CiAgICAgICAgICAgIDxzdG9wIHN0b3AtY29sb3I9IiMzNzUxN0UiIHN0b3Atb3BhY2l0eT0iMC4xIiBvZmZzZXQ9IjAlIj48L3N0b3A+CiAgICAgICAgICAgIDxzdG9wIHN0b3AtY29sb3I9IiMzNzUxN0UiIHN0b3Atb3BhY2l0eT0iMC4zNSIgb2Zmc2V0PSIyNCUiPjwvc3RvcD4KICAgICAgICAgICAgPHN0b3Agc3RvcC1jb2xvcj0iIzM3NTE3RSIgc3RvcC1vcGFjaXR5PSIwLjk3IiBvZmZzZXQ9Ijc0JSI+PC9zdG9wPgogICAgICAgICAgICA8c3RvcCBzdG9wLWNvbG9yPSIjMzc1MTdFIiBvZmZzZXQ9IjEwMCUiPjwvc3RvcD4KICAgICAgICA8L2xpbmVhckdyYWRpZW50PgogICAgICAgIDxsaW5lYXJHcmFkaWVudCB4MT0iNTYuMjU5MDU5NCUiIHkxPSIyMy44MzcwNzc5JSIgeDI9IjM4LjM2NTcyNzMlIiB5Mj0iMTAwLjMxMzMxMiUiIGlkPSJsaW5lYXJHcmFkaWVudC02Ij4KICAgICAgICAgICAgPHN0b3Agc3RvcC1jb2xvcj0iIzM3NTE3RSIgc3RvcC1vcGFjaXR5PSIwLjEiIG9mZnNldD0iMCUiPjwvc3RvcD4KICAgICAgICAgICAgPHN0b3Agc3RvcC1jb2xvcj0iIzM3NTE3RSIgc3RvcC1vcGFjaXR5PSIwLjM1IiBvZmZzZXQ9IjI0JSI+PC9zdG9wPgogICAgICAgICAgICA8c3RvcCBzdG9wLWNvbG9yPSIjMzc1MTdFIiBzdG9wLW9wYWNpdHk9IjAuOTciIG9mZnNldD0iNzQlIj48L3N0b3A+CiAgICAgICAgICAgIDxzdG9wIHN0b3AtY29sb3I9IiMzNzUxN0UiIG9mZnNldD0iMTAwJSI+PC9zdG9wPgogICAgICAgIDwvbGluZWFyR3JhZGllbnQ+CiAgICAgICAgPGxpbmVhckdyYWRpZW50IHgxPSI1MCUiIHkxPSIzLjY4MjcxMzE1JSIgeDI9IjUwJSIgeTI9Ijc3LjA4MDk2NTklIiBpZD0ibGluZWFyR3JhZGllbnQtNyI+CiAgICAgICAgICAgIDxzdG9wIHN0b3AtY29sb3I9IiMyRjQ0NjgiIHN0b3Atb3BhY2l0eT0iMC4wNzMxNDMxMTU5IiBvZmZzZXQ9IjAlIj48L3N0b3A+CiAgICAgICAgICAgIDxzdG9wIHN0b3AtY29sb3I9IiMyRjQ0NjgiIG9mZnNldD0iMTAwJSI+PC9zdG9wPgogICAgICAgIDwvbGluZWFyR3JhZGllbnQ+CiAgICA8L2RlZnM+CiAgICA8ZyBpZD0iRGVzaWduIiBzdHJva2U9Im5vbmUiIHN0cm9rZS13aWR0aD0iMSIgZmlsbD0ibm9uZSIgZmlsbC1ydWxlPSJldmVub2RkIj4KICAgICAgICA8ZyBpZD0iVHJ1c3RlZC1hbGwtb3ZlLXRoZS13b3JsZCI+CiAgICAgICAgICAgIDxnIGlkPSJDVEEiPgogICAgICAgICAgICAgICAgPG1hc2sgaWQ9Im1hc2stMiIgZmlsbD0id2hpdGUiPgogICAgICAgICAgICAgICAgICAgIDx1c2UgeGxpbms6aHJlZj0iI3BhdGgtMSI+PC91c2U+CiAgICAgICAgICAgICAgICA8L21hc2s+CiAgICAgICAgICAgICAgICA8dXNlIGlkPSJCYWNrZ3JvdW5kLShkYXJrLW5hdnkpIiBmaWxsPSIjMkY0NDY4IiB4bGluazpocmVmPSIjcGF0aC0xIj48L3VzZT4KICAgICAgICAgICAgICAgIDxwb2x5Z29uIGlkPSJTaGFwZSIgZmlsbD0idXJsKCNsaW5lYXJHcmFkaWVudC0zKSIgZmlsbC1ydWxlPSJub256ZXJvIiBvcGFjaXR5PSIwLjQiIG1hc2s9InVybCgjbWFzay0yKSIgcG9pbnRzPSIxMjg0LjQyMDI2IDEwMzQuMTc1MTggMTA2OCAxMDM0LjE3NTE4IDE1MzkuNTc5NzQgLTc0IDE3NTYgLTc0Ij48L3BvbHlnb24+CiAgICAgICAgICAgICAgICA8cG9seWdvbiBpZD0iU2hhcGUtQ29weS0yIiBmaWxsPSJ1cmwoI2xpbmVhckdyYWRpZW50LTQpIiBmaWxsLXJ1bGU9Im5vbnplcm8iIG9wYWNpdHk9IjAuMyIgbWFzaz0idXJsKCNtYXNrLTIpIiBwb2ludHM9Ii0yODEuNDA1MzU4IDEzNjcgLTU4Ny4yMzYxNzkgMTM2NyA3OS4xNjkxNzkzIC0xOTkgMzg1IC0xOTkiPjwvcG9seWdvbj4KICAgICAgICAgICAgICAgIDxwb2x5Z29uIGlkPSJTaGFwZS1Db3B5LTkiIGZpbGw9InVybCgjbGluZWFyR3JhZGllbnQtNSkiIGZpbGwtcnVsZT0ibm9uemVybyIgbWFzaz0idXJsKCNtYXNrLTIpIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxMzc1LjAwMDAwMCwgMTA3Ni42NDE3OTApIHNjYWxlKC0xLCAtMSkgdHJhbnNsYXRlKC0xMzc1LjAwMDAwMCwgLTEwNzYuNjQxNzkwKSAiIHBvaW50cz0iMTI0Ny40MjAyNiAxNjMzLjI4MzU4IDEwMzEgMTYzMy4yODM1OCAxNTAyLjU3OTc0IDUyMCAxNzE5IDUyMCI+PC9wb2x5Z29uPgogICAgICAgICAgICAgICAgPHBvbHlnb24gaWQ9IlNoYXBlLUNvcHktMTAiIGZpbGw9InVybCgjbGluZWFyR3JhZGllbnQtNikiIGZpbGwtcnVsZT0ibm9uemVybyIgbWFzaz0idXJsKCNtYXNrLTIpIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgyODYuNTAwMDAwLCAyNzMuNzA2MTEzKSBzY2FsZSgtMSwgLTEpIHRyYW5zbGF0ZSgtMjg2LjUwMDAwMCwgLTI3My43MDYxMTMpICIgcG9pbnRzPSIxNjUuNzgxMzc4IDgwMC40MTIyMjUgLTM5IDgwMC40MTIyMjUgNDA3LjIxODYyMiAtMjUzIDYxMiAtMjUzIj48L3BvbHlnb24+CiAgICAgICAgICAgIDwvZz4KICAgICAgICAgICAgPHJlY3QgaWQ9InNoYWRvdyIgZmlsbD0idXJsKCNsaW5lYXJHcmFkaWVudC03KSIgeD0iMTQ1IiB5PSIxMjIxIiB3aWR0aD0iMTE1MSIgaGVpZ2h0PSI1NSI+PC9yZWN0PgogICAgICAgIDwvZz4KICAgIDwvZz4KPC9zdmc+) ">
        <div class="w-full lg:w-5/6 xl:w-4/6 mx-auto">
            <div class="w-full lg:w-3/5 mx-auto">
                <h3 class="font-bold text-white text-2xl lg:text-4xl text-center tracking-wider px-10 lg:px-0">Trusted all over the world</h3>
                <p class="text-sm text-text-hero leading-5 text-center tracking-wider mt-2 px-10 lg:px-20 text-">We move over $6 billion every month, and save people and businesses $3 million in hidden fees every day.</p>
            </div>
            <div class="mt-8 px-4">
                <img src="https://mypatricia.co/images/map-base.svg" alt="">
            </div>
            <div class="w-full flex flex-col md:flex-row flex-wrap justify-center items-center mt-4 lg:mt-28 space-y-5 lg:space-y-0">
                <div class="w-full md:w-2/4 lg:w-1/4 px-2 text-center">
                    <h2 class="text-xl md:text-4xl text-white font-bold">14 offices</h2>
                    <p class="text-sm lg:text-base text-white font-light">around the world</p>
                </div>
                <div class="w-full md:w-2/4 lg:w-1/4 px-2 text-center">
                    <h2 class="text-xl md:text-4xl text-white font-bold">$6 billion</h2>
                    <p class="text-sm lg:text-base text-white font-light">sent every month</p>
                </div>
                <div class="w-full md:w-2/4 lg:w-1/4 px-2 text-center">
                    <h2 class="text-xl md:text-4xl text-white font-bold">9 million</h2>
                    <p class="text-sm lg:text-base text-white font-light">customers</p>
                </div>
                <div class="w-full md:w-2/4 lg:w-1/4 px-2 text-center">
                    <h2 class="text-xl md:text-4xl text-white font-bold">$1.5 billion</h2>
                    <p class="text-sm lg:text-base text-white font-light">saved by customers every year</p>
                </div>
            </div>
            <div class="mt-4 w-full">
                <div class="w-full px-4 md:px-32 mx-auto text-center">
                    <p class="text-sm text-text-hero tracking-wider font-light">We’re available around the world, and we add new currencies all the time. If you think we should add a specific currency, let us know. Be the first to know when we add more by <span class="text-accent underline">signing up to our mailing list.</span></p>
                </div>

                <div class="w-full flex flex-col md:flex-row flex-wrap mt-6">
                    <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                        <div class="py-3 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                            <country-flag country="eu" size='normal'/>
                            <span class="">Europe</span>
                        </div>
                    </div>
                    <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                        <div class="py-3 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                            <country-flag country="gb" size='normal'/>
                            <span class="">United Kingdom</span>
                        </div>
                    </div>
                    <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                        <div class="py-3 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                            <country-flag country="in" size='normal'/>
                            <span class="">India</span>
                        </div>
                    </div>
                    <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                        <div class="py-3 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                            <country-flag country="us" size='normal'/>
                            <span class="">United state</span>
                        </div>
                    </div>
                    <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                        <div class="py-3 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                            <country-flag country="br" size='normal'/>
                            <span class="">Brazil</span>
                        </div>
                    </div>
                    <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                        <div class="py-3 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                            <country-flag country="au" size='normal'/>
                            <span class="">Australia</span>
                        </div>
                    </div>
                    <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2 hidden lg:block">
                        <div class="py-3 bg-primary flex items-center space-x-3 px-2 rounded text-white font-medium hover:text-accent">
                            <country-flag country="ca" size='normal'/>
                            <span class="">Canada</span>
                        </div>
                    </div>
                    <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2 hidden lg:block">
                        <div class="py-3 bg-primary flex items-center space-x-3 px-2 rounded text-white font-medium hover:text-accent">
                            <country-flag country="th" size='normal'/>
                            <span class="">Thailand</span>
                        </div>
                    </div>

                    <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2 hidden lg:block opacity-20">
                        <div class="py-6 bg-primary flex items-center space-x-3 px-2  rounded text-white font-medium hover:text-accent">
                            
                        </div>
                    </div>
                    <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2 hidden lg:block opacity-20">
                        <div class="py-6 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                            
                        </div>
                    </div>
                    <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2 hidden lg:block opacity-20">
                        <div class="py-6 bg-primary flex items-center space-x-3 px-2 rounded text-white font-medium hover:text-accent">
                            
                        </div>
                    </div>
                    <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2 hidden lg:block opacity-20">
                        <div class="py-6 bg-primary flex items-center space-x-3 px-2 rounded text-white font-medium hover:text-accent">
                            
                        </div>
                    </div>
                </div>

                <div @click="toggleShow" class="flex justify-center items-center mt-4 lg:-mt-8 bg-transparent lg:bg-fader-background bg-opacity-90 lg:bg-opacity-70 px-3 relative">
                    <button class="w-full sm:w-auto px-6 py-3 rounded text-accent hover:text-white bg-transparent text-sm font-medium hover:bg-accent border border-accent">See all route we cover</button>
                </div>
            </div>
        </div>
        <div v-show="show" class="w-full overflow-y-auto fixed top-0 left-0 h-full z-50 bg-no-repeat bg-cover py-12" style="background-image: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz4KPHN2ZyB3aWR0aD0iMTQ0MHB4IiBoZWlnaHQ9IjEzODZweCIgdmlld0JveD0iMCAwIDE0NDAgMTM4NiIgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIj4KICAgIDwhLS0gR2VuZXJhdG9yOiBTa2V0Y2ggNTQuMSAoNzY0OTApIC0gaHR0cHM6Ly9za2V0Y2hhcHAuY29tIC0tPgogICAgPHRpdGxlPlRydXN0ZWQgYWxsIG92ZSB0aGUgd29ybGQ8L3RpdGxlPgogICAgPGRlc2M+Q3JlYXRlZCB3aXRoIFNrZXRjaC48L2Rlc2M+CiAgICA8ZGVmcz4KICAgICAgICA8cmVjdCBpZD0icGF0aC0xIiB4PSIwIiB5PSIwIiB3aWR0aD0iMTQ0MCIgaGVpZ2h0PSIxMzg2Ij48L3JlY3Q+CiAgICAgICAgPGxpbmVhckdyYWRpZW50IHgxPSI2Mi4wMTk2Mzg3JSIgeTE9Ii0wLjMxMzMxMTY4OCUiIHgyPSI0NC4xOTg1NzMyJSIgeTI9Ijc1LjE1NjY1NTglIiBpZD0ibGluZWFyR3JhZGllbnQtMyI+CiAgICAgICAgICAgIDxzdG9wIHN0b3AtY29sb3I9IiM1NzRBRTIiIG9mZnNldD0iMCUiPjwvc3RvcD4KICAgICAgICAgICAgPHN0b3Agc3RvcC1jb2xvcj0iIzU3NEFFMiIgc3RvcC1vcGFjaXR5PSIwLjU5IiBvZmZzZXQ9IjU3JSI+PC9zdG9wPgogICAgICAgICAgICA8c3RvcCBzdG9wLWNvbG9yPSIjNTc0QUUyIiBzdG9wLW9wYWNpdHk9IjAuMjQiIG9mZnNldD0iODclIj48L3N0b3A+CiAgICAgICAgICAgIDxzdG9wIHN0b3AtY29sb3I9IiM1NzRBRTIiIHN0b3Atb3BhY2l0eT0iMC4xIiBvZmZzZXQ9IjEwMCUiPjwvc3RvcD4KICAgICAgICA8L2xpbmVhckdyYWRpZW50PgogICAgICAgIDxsaW5lYXJHcmFkaWVudCB4MT0iNjIuMDE5NjM4NyUiIHkxPSItMC4zMTMzMTE2ODglIiB4Mj0iNDQuMTk4NTczMiUiIHkyPSI3NS4xNTY2NTU4JSIgaWQ9ImxpbmVhckdyYWRpZW50LTQiPgogICAgICAgICAgICA8c3RvcCBzdG9wLWNvbG9yPSIjNTc0QUUyIiBvZmZzZXQ9IjAlIj48L3N0b3A+CiAgICAgICAgICAgIDxzdG9wIHN0b3AtY29sb3I9IiM1NzRBRTIiIHN0b3Atb3BhY2l0eT0iMC41OSIgb2Zmc2V0PSI1NyUiPjwvc3RvcD4KICAgICAgICAgICAgPHN0b3Agc3RvcC1jb2xvcj0iIzU3NEFFMiIgc3RvcC1vcGFjaXR5PSIwLjI0IiBvZmZzZXQ9Ijg3JSI+PC9zdG9wPgogICAgICAgICAgICA8c3RvcCBzdG9wLWNvbG9yPSIjNTc0QUUyIiBzdG9wLW9wYWNpdHk9IjAuMSIgb2Zmc2V0PSIxMDAlIj48L3N0b3A+CiAgICAgICAgPC9saW5lYXJHcmFkaWVudD4KICAgICAgICA8bGluZWFyR3JhZGllbnQgeDE9IjU2LjI1OTA1OTQlIiB5MT0iMjMuODM3MDc3OSUiIHgyPSIzOC4zNjU3MjczJSIgeTI9IjEwMC4zMTMzMTIlIiBpZD0ibGluZWFyR3JhZGllbnQtNSI+CiAgICAgICAgICAgIDxzdG9wIHN0b3AtY29sb3I9IiMzNzUxN0UiIHN0b3Atb3BhY2l0eT0iMC4xIiBvZmZzZXQ9IjAlIj48L3N0b3A+CiAgICAgICAgICAgIDxzdG9wIHN0b3AtY29sb3I9IiMzNzUxN0UiIHN0b3Atb3BhY2l0eT0iMC4zNSIgb2Zmc2V0PSIyNCUiPjwvc3RvcD4KICAgICAgICAgICAgPHN0b3Agc3RvcC1jb2xvcj0iIzM3NTE3RSIgc3RvcC1vcGFjaXR5PSIwLjk3IiBvZmZzZXQ9Ijc0JSI+PC9zdG9wPgogICAgICAgICAgICA8c3RvcCBzdG9wLWNvbG9yPSIjMzc1MTdFIiBvZmZzZXQ9IjEwMCUiPjwvc3RvcD4KICAgICAgICA8L2xpbmVhckdyYWRpZW50PgogICAgICAgIDxsaW5lYXJHcmFkaWVudCB4MT0iNTYuMjU5MDU5NCUiIHkxPSIyMy44MzcwNzc5JSIgeDI9IjM4LjM2NTcyNzMlIiB5Mj0iMTAwLjMxMzMxMiUiIGlkPSJsaW5lYXJHcmFkaWVudC02Ij4KICAgICAgICAgICAgPHN0b3Agc3RvcC1jb2xvcj0iIzM3NTE3RSIgc3RvcC1vcGFjaXR5PSIwLjEiIG9mZnNldD0iMCUiPjwvc3RvcD4KICAgICAgICAgICAgPHN0b3Agc3RvcC1jb2xvcj0iIzM3NTE3RSIgc3RvcC1vcGFjaXR5PSIwLjM1IiBvZmZzZXQ9IjI0JSI+PC9zdG9wPgogICAgICAgICAgICA8c3RvcCBzdG9wLWNvbG9yPSIjMzc1MTdFIiBzdG9wLW9wYWNpdHk9IjAuOTciIG9mZnNldD0iNzQlIj48L3N0b3A+CiAgICAgICAgICAgIDxzdG9wIHN0b3AtY29sb3I9IiMzNzUxN0UiIG9mZnNldD0iMTAwJSI+PC9zdG9wPgogICAgICAgIDwvbGluZWFyR3JhZGllbnQ+CiAgICAgICAgPGxpbmVhckdyYWRpZW50IHgxPSI1MCUiIHkxPSIzLjY4MjcxMzE1JSIgeDI9IjUwJSIgeTI9Ijc3LjA4MDk2NTklIiBpZD0ibGluZWFyR3JhZGllbnQtNyI+CiAgICAgICAgICAgIDxzdG9wIHN0b3AtY29sb3I9IiMyRjQ0NjgiIHN0b3Atb3BhY2l0eT0iMC4wNzMxNDMxMTU5IiBvZmZzZXQ9IjAlIj48L3N0b3A+CiAgICAgICAgICAgIDxzdG9wIHN0b3AtY29sb3I9IiMyRjQ0NjgiIG9mZnNldD0iMTAwJSI+PC9zdG9wPgogICAgICAgIDwvbGluZWFyR3JhZGllbnQ+CiAgICA8L2RlZnM+CiAgICA8ZyBpZD0iRGVzaWduIiBzdHJva2U9Im5vbmUiIHN0cm9rZS13aWR0aD0iMSIgZmlsbD0ibm9uZSIgZmlsbC1ydWxlPSJldmVub2RkIj4KICAgICAgICA8ZyBpZD0iVHJ1c3RlZC1hbGwtb3ZlLXRoZS13b3JsZCI+CiAgICAgICAgICAgIDxnIGlkPSJDVEEiPgogICAgICAgICAgICAgICAgPG1hc2sgaWQ9Im1hc2stMiIgZmlsbD0id2hpdGUiPgogICAgICAgICAgICAgICAgICAgIDx1c2UgeGxpbms6aHJlZj0iI3BhdGgtMSI+PC91c2U+CiAgICAgICAgICAgICAgICA8L21hc2s+CiAgICAgICAgICAgICAgICA8dXNlIGlkPSJCYWNrZ3JvdW5kLShkYXJrLW5hdnkpIiBmaWxsPSIjMkY0NDY4IiB4bGluazpocmVmPSIjcGF0aC0xIj48L3VzZT4KICAgICAgICAgICAgICAgIDxwb2x5Z29uIGlkPSJTaGFwZSIgZmlsbD0idXJsKCNsaW5lYXJHcmFkaWVudC0zKSIgZmlsbC1ydWxlPSJub256ZXJvIiBvcGFjaXR5PSIwLjQiIG1hc2s9InVybCgjbWFzay0yKSIgcG9pbnRzPSIxMjg0LjQyMDI2IDEwMzQuMTc1MTggMTA2OCAxMDM0LjE3NTE4IDE1MzkuNTc5NzQgLTc0IDE3NTYgLTc0Ij48L3BvbHlnb24+CiAgICAgICAgICAgICAgICA8cG9seWdvbiBpZD0iU2hhcGUtQ29weS0yIiBmaWxsPSJ1cmwoI2xpbmVhckdyYWRpZW50LTQpIiBmaWxsLXJ1bGU9Im5vbnplcm8iIG9wYWNpdHk9IjAuMyIgbWFzaz0idXJsKCNtYXNrLTIpIiBwb2ludHM9Ii0yODEuNDA1MzU4IDEzNjcgLTU4Ny4yMzYxNzkgMTM2NyA3OS4xNjkxNzkzIC0xOTkgMzg1IC0xOTkiPjwvcG9seWdvbj4KICAgICAgICAgICAgICAgIDxwb2x5Z29uIGlkPSJTaGFwZS1Db3B5LTkiIGZpbGw9InVybCgjbGluZWFyR3JhZGllbnQtNSkiIGZpbGwtcnVsZT0ibm9uemVybyIgbWFzaz0idXJsKCNtYXNrLTIpIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxMzc1LjAwMDAwMCwgMTA3Ni42NDE3OTApIHNjYWxlKC0xLCAtMSkgdHJhbnNsYXRlKC0xMzc1LjAwMDAwMCwgLTEwNzYuNjQxNzkwKSAiIHBvaW50cz0iMTI0Ny40MjAyNiAxNjMzLjI4MzU4IDEwMzEgMTYzMy4yODM1OCAxNTAyLjU3OTc0IDUyMCAxNzE5IDUyMCI+PC9wb2x5Z29uPgogICAgICAgICAgICAgICAgPHBvbHlnb24gaWQ9IlNoYXBlLUNvcHktMTAiIGZpbGw9InVybCgjbGluZWFyR3JhZGllbnQtNikiIGZpbGwtcnVsZT0ibm9uemVybyIgbWFzaz0idXJsKCNtYXNrLTIpIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgyODYuNTAwMDAwLCAyNzMuNzA2MTEzKSBzY2FsZSgtMSwgLTEpIHRyYW5zbGF0ZSgtMjg2LjUwMDAwMCwgLTI3My43MDYxMTMpICIgcG9pbnRzPSIxNjUuNzgxMzc4IDgwMC40MTIyMjUgLTM5IDgwMC40MTIyMjUgNDA3LjIxODYyMiAtMjUzIDYxMiAtMjUzIj48L3BvbHlnb24+CiAgICAgICAgICAgIDwvZz4KICAgICAgICAgICAgPHJlY3QgaWQ9InNoYWRvdyIgZmlsbD0idXJsKCNsaW5lYXJHcmFkaWVudC03KSIgeD0iMTQ1IiB5PSIxMjIxIiB3aWR0aD0iMTE1MSIgaGVpZ2h0PSI1NSI+PC9yZWN0PgogICAgICAgIDwvZz4KICAgIDwvZz4KPC9zdmc+)">
            <div class="absolute top-0 right-0 mt-6 mr-6">
                <button @click="toggleShow" class="focus:outline-none">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="w-7 h-7 text-accent font-medium" viewBox="0 0 20 20">
                        <path fill-rule="evenodd" d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z" clip-rule="evenodd" />
                    </svg>
                </button>
            </div>
            <div class="w-full max-w-6xl mx-auto px-2 lg:px-6 text-white text-center">
                    <h2 class="text-2xl lg:text-4xl font-bold ">Europe</h2>
                    <div class="w-full flex flex-col md:flex-row flex-wrap mt-6">
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                                <country-flag country="eu" size='normal'/>
                                <span class="">Europe</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                                <country-flag country="gb" size='normal'/>
                                <span class="">United Kingdom</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                                <country-flag country="in" size='normal'/>
                                <span class="">India</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                                <country-flag country="us" size='normal'/>
                                <span class="">United state</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                                <country-flag country="br" size='normal'/>
                                <span class="">Brazil</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                                <country-flag country="au" size='normal'/>
                                <span class="">Australia</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-2 rounded text-white font-medium hover:text-accent">
                                <country-flag country="ca" size='normal'/>
                                <span class="">Canada</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-2 rounded text-white font-medium hover:text-accent">
                                <country-flag country="th" size='normal'/>
                                <span class="">Thailand</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                                <country-flag country="ng" size='normal'/>
                                <span class="">Nigeia</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                                <country-flag country="ke" size='normal'/>
                                <span class="">Kenya</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-2 rounded text-white font-medium hover:text-accent">
                                <country-flag country="gh" size='normal'/>
                                <span class="">Ghana</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-2 rounded text-white font-medium hover:text-accent">
                                <country-flag country="mr" size='normal'/>
                                <span class="">Morocco</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                                <country-flag country="za" size='normal'/>
                                <span class="">South Africa</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                                <country-flag country="ug" size='normal'/>
                                <span class="">Uganda</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                                <country-flag country="ng" size='normal'/>
                                <span class="">Nigeia</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                                <country-flag country="ke" size='normal'/>
                                <span class="">Kenya</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-2 rounded text-white font-medium hover:text-accent">
                                <country-flag country="gh" size='normal'/>
                                <span class="">Ghana</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-2 rounded text-white font-medium hover:text-accent">
                                <country-flag country="mr" size='normal'/>
                                <span class="">Morocco</span>
                            </div>
                        </div>
                    </div>

                    <h2 class="text-2xl lg:text-4xl  font-bold mt-12">America</h2>
                    <div class="w-full flex flex-col md:flex-row flex-wrap mt-6">
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                                <country-flag country="us" size='normal'/>
                                <span class="">USA</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                                <country-flag country="ar" size='normal'/>
                                <span class="">Argentina</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-2 rounded text-white font-medium hover:text-accent">
                                <country-flag country="ca" size='normal'/>
                                <span class="">Canada</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 p-2 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-2 rounded text-white font-medium hover:text-accent">
                                <country-flag country="th" size='normal'/>
                                <span class="">Thailand</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                                <country-flag country="br" size='normal'/>
                                <span class="">Brazil</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                                <country-flag country="mx" size='normal'/>
                                <span class="">Mexico</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                                <country-flag country="ng" size='normal'/>
                                <span class="">Nigeia</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                                <country-flag country="ke" size='normal'/>
                                <span class="">Kenya</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-2 rounded text-white font-medium hover:text-accent">
                                <country-flag country="gh" size='normal'/>
                                <span class="">Ghana</span>
                            </div>
                        </div>
                    </div>

                    <h2 class="text-2xl lg:text-4xl  font-bold mt-12">Africa</h2>
                    <div class="w-full flex flex-col md:flex-row flex-wrap mt-6">
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                                <country-flag country="ng" size='normal'/>
                                <span class="">Nigeia</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                                <country-flag country="ke" size='normal'/>
                                <span class="">Kenya</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-2 rounded text-white font-medium hover:text-accent">
                                <country-flag country="gh" size='normal'/>
                                <span class="">Ghana</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-2 rounded text-white font-medium hover:text-accent">
                                <country-flag country="mr" size='normal'/>
                                <span class="">Morocco</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                                <country-flag country="za" size='normal'/>
                                <span class="">South Africa</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                                <country-flag country="ug" size='normal'/>
                                <span class="">Uganda</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                                <country-flag country="ng" size='normal'/>
                                <span class="">Nigeia</span>
                            </div>
                        </div>
                        <div class="w-full md:w-1/3 lg:w-1/4 px-3 py-2">
                            <div class="py-3 bg-primary flex items-center space-x-3 px-4 rounded text-white font-medium hover:text-accent">
                                <country-flag country="ke" size='normal'/>
                                <span class="">Kenya</span>
                            </div>
                        </div>
                    </div>

                    <div class="mt-12 w-full">
                        <button @click="toggleShow" class="mt-6 lg:mt-10 px-6 py-3 font-medium rounded text-accent hover:text-white bg-transparent hover:bg-accent border border-accent">Got it</button>
                    </div>
            </div>
        </div>
    </div>
</template>

<script>
import CountryFlag from 'vue-country-flag'
export default {
    components: {
        CountryFlag
    },
    data(){
        return {
            show: false
        }
    },
    methods:{
        toggleShow(){
            this.show = !this.show
        }
    }
}
</script>