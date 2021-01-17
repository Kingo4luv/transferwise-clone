<template>
    <div  class="hero w-full bg-no-repeat bg-cover relative pb-10" style="background-image: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTQ0MCIgaGVpZ2h0PSI3NTAiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiPjxkZWZzPjxwYXRoIGlkPSJhIiBkPSJNMCAwaDE0NDB2NzUwSDB6Ii8+PGxpbmVhckdyYWRpZW50IHgxPSI0NC4yNDglIiB5MT0iNzUuMTU2JSIgeDI9IjYxLjkxOSUiIHkyPSItLjMxMiUiIGlkPSJiIj48c3RvcCBzdG9wLWNvbG9yPSIjNTY0M0U1IiBvZmZzZXQ9IjAlIi8+PHN0b3Agc3RvcC1jb2xvcj0iIzU2NDNFNSIgc3RvcC1vcGFjaXR5PSIuMSIgb2Zmc2V0PSIxMDAlIi8+PC9saW5lYXJHcmFkaWVudD48bGluZWFyR3JhZGllbnQgeDE9IjQ0LjI1MSUiIHkxPSI3NS4xNTYlIiB4Mj0iNjEuOTEyJSIgeTI9Ii0uMzEyJSIgaWQ9ImQiPjxzdG9wIHN0b3AtY29sb3I9IiM1NjQzRTUiIG9mZnNldD0iMCUiLz48c3RvcCBzdG9wLWNvbG9yPSIjNTY0M0U1IiBzdG9wLW9wYWNpdHk9Ii4xIiBvZmZzZXQ9IjEwMCUiLz48L2xpbmVhckdyYWRpZW50PjxsaW5lYXJHcmFkaWVudCB4MT0iNTYuMjYlIiB5MT0iMjMuODM4JSIgeDI9IjM4LjM2NSUiIHkyPSIxMDAuMzEyJSIgaWQ9ImUiPjxzdG9wIHN0b3AtY29sb3I9IiMzNjUwODAiIHN0b3Atb3BhY2l0eT0iLjEiIG9mZnNldD0iMCUiLz48c3RvcCBzdG9wLWNvbG9yPSIjMzY1MDgwIiBvZmZzZXQ9IjEwMCUiLz48L2xpbmVhckdyYWRpZW50PjxsaW5lYXJHcmFkaWVudCB4MT0iNTYuMjYlIiB5MT0iMjMuODM4JSIgeDI9IjM4LjM2NSUiIHkyPSIxMDAuMzEyJSIgaWQ9ImYiPjxzdG9wIHN0b3AtY29sb3I9IiMzNjUwODAiIHN0b3Atb3BhY2l0eT0iLjMiIG9mZnNldD0iMCUiLz48c3RvcCBzdG9wLWNvbG9yPSIjNTY0M0U1IiBvZmZzZXQ9IjEwMCUiLz48L2xpbmVhckdyYWRpZW50PjwvZGVmcz48ZyBmaWxsPSJub25lIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiPjxtYXNrIGlkPSJjIiBmaWxsPSIjZmZmIj48dXNlIHhsaW5rOmhyZWY9IiNhIi8+PC9tYXNrPjx1c2UgZmlsbD0iIzM3NTE3RSIgeGxpbms6aHJlZj0iI2EiLz48cGF0aCBmaWxsLW9wYWNpdHk9Ii45IiBmaWxsPSJ1cmwoI2IpIiBmaWxsLXJ1bGU9Im5vbnplcm8iIG9wYWNpdHk9Ii4zOTYiIG1hc2s9InVybCgjYykiIGQ9Ik04NzQgMTYzOS44OTJMMTU0Mi4yMTQgNjNoMzA2LjY2MmwtNjY4LjIxMyAxNTc2Ljg5MnoiLz48cGF0aCBmaWxsLW9wYWNpdHk9Ii41IiBmaWxsPSJ1cmwoI2QpIiBmaWxsLXJ1bGU9Im5vbnplcm8iIG9wYWNpdHk9Ii41NTIiIG1hc2s9InVybCgjYykiIGQ9Ik0tOTgwIDQ0MDguODkyTDcyNS45NiAzODJoNzgyLjkxNmwtMTcwNS45NiA0MDI2Ljg5MnoiLz48cGF0aCBmaWxsPSJ1cmwoI2UpIiBmaWxsLXJ1bGU9Im5vbnplcm8iIG9wYWNpdHk9Ii4wNCIgbWFzaz0idXJsKCNjKSIgZD0iTTE1NTQuOTc4IDc0SDExMzBsOTI2LjAyMi0yMTg2SDI0ODF6Ii8+PHBhdGggZmlsbD0idXJsKCNmKSIgZmlsbC1ydWxlPSJub256ZXJvIiBtYXNrPSJ1cmwoI2MpIiBkPSJNLTcxNSAxNjQwTDIxMS4wMjItNTQ2SDYzNmwtOTI2LjAyMiAyMTg2eiIvPjwvZz48L3N2Zz4=)">
        <div class="container w-full lg:max-w-6xl mx-auto py-3 px-4">
            <div class="hidden lg:block">
                <nav  class="text-white flex justify-between items-center text-sm">
                    <div class="logo">
                        <img class="bg-no-repeat bg-transparent bg-center w-32" src="data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiIHN0YW5kYWxvbmU9Im5vIj8+PHN2ZyB2aWV3Qm94PSIwIDAgMTUwIDI2IiB2ZXJzaW9uPSIxLjEiIHhtbDpzcGFjZT0icHJlc2VydmUiICAgIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHhtbG5zOnNrZXRjaD0iaHR0cDovL3d3dy5ib2hlbWlhbmNvZGluZy5jb20vc2tldGNoL25zIj4gICAgICAgIDx0aXRsZT5Mb2dvPC90aXRsZT4gICAgPGRlc2M+Q3JlYXRlZCB3aXRoIFNrZXRjaC48L2Rlc2M+ICAgIDxkZWZzPjwvZGVmcz4gICAgPGcgaWQ9IkZsb3ciIHN0cm9rZT0ibm9uZSIgc3Ryb2tlLXdpZHRoPSIxIiBmaWxsPSJub25lIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIHNrZXRjaDp0eXBlPSJNU1BhZ2UiPiAgICAgICAgPGcgaWQ9IjQtRCIgc2tldGNoOnR5cGU9Ik1TQXJ0Ym9hcmRHcm91cCIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTEzMC4wMDAwMDAsIC0xNy4wMDAwMDApIj4gICAgICAgICAgICA8ZyBpZD0iSGVhZGVyIiBza2V0Y2g6dHlwZT0iTVNMYXllckdyb3VwIj4gICAgICAgICAgICAgICAgPGcgaWQ9IkxvZ28iIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEzMC4wMDAwMDAsIDE3LjAwMDAwMCkiIHNrZXRjaDp0eXBlPSJNU1NoYXBlR3JvdXAiPiAgICAgICAgICAgICAgICAgICAgPHBhdGggZD0iTTIuNzgzMjYyNzEsMC40NTcyMTk1MTIgTDYuMDY1NDY2MSw1Ljk1MzM2NTg1IEwwLjMxMjA3NjI3MSwxMS40NDA2MzQxIEwxMC4yNTkxMTAyLDExLjQ0MDYzNDEgTDExLjE5NDA2NzgsOS4yNDE0MTQ2MyBMNS43MDU3MjAzNCw5LjI0MTQxNDYzIEw5LjAyNjY5NDkyLDUuOTM4NzgwNDkgTDcuMDg2ODY0NDEsMi42NTU4MDQ4OCBMMTYuMTM3MDc2MywyLjY1NTgwNDg4IEw4LjE5MjE2MTAyLDIxLjQyMzM2NTkgTDEwLjkxNDQwNjgsMjEuNDIzMzY1OSBMMTkuNzk4MDkzMiwwLjQ1NzIxOTUxMiBMMi43ODMyNjI3MSwwLjQ1NzIxOTUxMiIgaWQ9IkZpbGwtMSIgZmlsbD0iIzAwQzZGRiI+PC9wYXRoPiAgICAgICAgICAgICAgICAgICAgPHBhdGggZD0iTTEyMy40OTg5NDEsMTMuMzEzOTAyNCBMMTI1Ljc2NzM3MywxMy4zMTM5MDI0IEwxMjUuNzY3MzczLDI1LjMxOTU2MSBMMTIzLjQ5ODk0MSwyNS4zMTk1NjEgTDEyMy40OTg5NDEsMTMuMzEzOTAyNCBaIiBpZD0iRmlsbC0yIiBmaWxsPSIjRkZGRkZGIj48L3BhdGg+ICAgICAgICAgICAgICAgICAgICA8cGF0aCBkPSJNMTIzLjM5NTk3NSw5LjI1NTM2NTg1IEwxMjUuODcwOTc1LDkuMjU1MzY1ODUgTDEyNS44NzA5NzUsMTEuNjkwNDg3OCBMMTIzLjM5NTk3NSwxMS42OTA0ODc4IEwxMjMuMzk1OTc1LDkuMjU1MzY1ODUgWiIgaWQ9IkZpbGwtMyIgZmlsbD0iI0ZGRkZGRiI+PC9wYXRoPiAgICAgICAgICAgICAgICAgICAgPHBhdGggZD0iTTExOS42MTM1NTksOS4yNTYgTDExNi43OTM0MzIsMjEuNzM0NzMxNyBMMTE2LjY5MTEwMiwyMS43MzQ3MzE3IEwxMTMuNzY4NjQ0LDEzLjMxNTE3MDcgTDExMS43Mzk4MzEsMTMuMzE1MTcwNyBMMTA4LjQwNDIzNywyMS43MzQ3MzE3IEwxMDguMzAxMjcxLDIxLjczNDczMTcgTDEwNi4wNjY1MjUsOS4yNTYgTDEwMy42MjUyMTIsOS4yNTYgTDEwNi42ODQzMjIsMjUuMzE5NTYxIEwxMDguOTU0MDI1LDI1LjMxOTU2MSBMMTEyLjU2NDgzMSwxNi40MjU2NTg1IEwxMTIuNjY3MTYxLDE2LjQyNTY1ODUgTDExNS43OTc0NTgsMjUuMzE5NTYxIEwxMTguMDY1ODksMjUuMzE5NTYxIEwxMjEuOTUxMjcxLDkuMjU2IEwxMTkuNjEzNTU5LDkuMjU2IiBpZD0iRmlsbC00IiBmaWxsPSIjRkZGRkZGIj48L3BhdGg+ICAgICAgICAgICAgICAgICAgICA8cGF0aCBkPSJNODguMDQ5MzY0NCwyMy41NjE3MDczIEM4NS44NDg5NDA3LDIzLjU2MTcwNzMgODQuMzM2MjI4OCwyMS44MzYxOTUxIDg0LjMzNjIyODgsMTkuMzMzODUzNyBDODQuMzM2MjI4OCwxNy4wMDA4MjkzIDg1LjY0MjM3MjksMTUuMDA0NTM2NiA4Ny43NzQ3ODgxLDE1LjAwNDUzNjYgQzkwLjIxNjEwMTcsMTUuMDA0NTM2NiA5MC44Njk0OTE1LDE3LjAzNDQzOSA5MC45MzgxMzU2LDE4LjI4NjI0MzkgTDg2LjcxNzc5NjYsMTguMjg2MjQzOSBMODUuOTI3NzU0MiwyMC4xMTI1ODU0IEw5My4yNDE1MjU0LDIwLjExMjU4NTQgQzkzLjI3NTIxMTksMTkuNjM4MjQzOSA5My4yNzUyMTE5LDE5LjUwMzgwNDkgOTMuMjc1MjExOSwxOS4yNjY2MzQxIEM5My4yNzUyMTE5LDE1LjgxNjg3OCA5MS41MjIyNDU4LDEzLjA3OCA4Ny43Mzk4MzA1LDEzLjA3OCBDODQuNDczNTE2OSwxMy4wNzggODEuOTY0MTk0OSwxNS43MTQ3ODA1IDgxLjk2NDE5NDksMTkuMzMzODUzNyBDODEuOTY0MTk0OSwyMy4wNTQzOTAyIDg0LjM2OTkxNTMsMjUuNTIyNDg3OCA4Ny44MDg0NzQ2LDI1LjUyMjQ4NzggQzg5Ljg3MjI0NTgsMjUuNTIyNDg3OCA5MS42OTM4NTU5LDI0Ljc3OTI2ODMgOTIuNzk0NzAzNCwyMy40NjAyNDM5IEw5MS40MTkyNzk3LDIyLjE0MDU4NTQgQzkwLjUyNTYzNTYsMjMuMDU0MzkwMiA4OS4zNTYxNDQxLDIzLjU2MTcwNzMgODguMDQ5MzY0NCwyMy41NjE3MDczIiBpZD0iRmlsbC01IiBmaWxsPSIjRkZGRkZGIj48L3BhdGg+ICAgICAgICAgICAgICAgICAgICA8cGF0aCBkPSJNNzkuMDc1NDIzNywxMy4wNzczNjU5IEM3OS4wNzU0MjM3LDExLjU4OTY1ODUgNzkuNzk3NDU3NiwxMC43NDM3MDczIDgxLjE3Mjg4MTQsMTAuNzQzNzA3MyBDODEuNjg4OTgzMSwxMC43NDM3MDczIDgyLjUxMzk4MzEsMTAuODc5NDE0NiA4My4xNjczNzI5LDExLjExNjU4NTQgTDgzLjg4ODc3MTIsOS40NTg5MjY4MyBDODIuOTk1MTI3MSw5LjAxOTQ2MzQxIDgxLjkyOTIzNzMsOC44NTAxNDYzNCA4MS4xMDQyMzczLDguODUwMTQ2MzQgQzc4LjgwMDIxMTksOC44NTAxNDYzNCA3Ni44MDYzNTU5LDkuOTk5ODUzNjYgNzYuODA2MzU1OSwxMy4wNzczNjU5IEw3Ni44MDYzNTU5LDEzLjQ0OTYwOTggTDc1LjI5MzY0NDEsMTMuNDQ5NjA5OCBMNzUuMjkzNjQ0MSwxNS4zNDM4MDQ5IEw3Ni44MDYzNTU5LDE1LjM0MzgwNDkgTDc2LjgwNjM1NTksMjUuMzE5NTYxIEw3OS4wNzU0MjM3LDI1LjMxOTU2MSBMNzkuMDc1NDIzNywxNS4zNDM4MDQ5IEw4MS4zNzg4MTM2LDE1LjM0MzgwNDkgTDgyLjE3MDEyNzEsMTMuNDQ5NjA5OCBMNzkuMDc1NDIzNywxMy40NDk2MDk4IEw3OS4wNzU0MjM3LDEzLjA3NzM2NTkiIGlkPSJGaWxsLTYiIGZpbGw9IiNGRkZGRkYiPjwvcGF0aD4gICAgICAgICAgICAgICAgICAgIDxwYXRoIGQ9Ik01OC42MTY5NDkyLDEzLjA3NzM2NTkgQzU3LjEwNDIzNzMsMTMuMDc3MzY1OSA1NS43Mjg4MTM2LDEzLjY1MzE3MDcgNTUuMDQxMTAxNywxNC44MzY0ODc4IEw1NC45Mzg3NzEyLDE0LjgzNjQ4NzggTDU0LjkzODc3MTIsMTMuMzE0NTM2NiBMNTIuNzM3NzExOSwxMy4zMTQ1MzY2IEw1Mi43Mzc3MTE5LDI1LjMxOTU2MSBMNTUuMDA2Nzc5NywyNS4zMTk1NjEgTDU1LjAwNjc3OTcsMTguODI3ODA0OSBDNTUuMDA2Nzc5NywxNi40NTk5MDI0IDU2LjIxMDU5MzIsMTUuMDM4NzgwNSA1OC4xMDIxMTg2LDE1LjAzODc4MDUgQzU5Ljg4ODc3MTIsMTUuMDM4NzgwNSA2MC45NTUyOTY2LDE1Ljk4NTU2MSA2MC45NTUyOTY2LDE4LjE4MzUxMjIgTDYwLjk1NTI5NjYsMjUuMzE5NTYxIEw2My4yMjQzNjQ0LDI1LjMxOTU2MSBMNjMuMjI0MzY0NCwxNy43NzgyOTI3IEM2My4yMjQzNjQ0LDE0LjczNTAyNDQgNjEuNDM3MDc2MywxMy4wNzczNjU5IDU4LjYxNjk0OTIsMTMuMDc3MzY1OSIgaWQ9IkZpbGwtNyIgZmlsbD0iI0ZGRkZGRiI+PC9wYXRoPiAgICAgICAgICAgICAgICAgICAgPHBhdGggZD0iTTQ3Ljg1NTA4NDcsMjAuNjg3MTIyIEM0Ny44NTUwODQ3LDIyLjQ3ODU4NTQgNDYuMzc2Njk0OSwyMy42Mjg5MjY4IDQ0LjMxMzU1OTMsMjMuNjI4OTI2OCBDNDMuMDc2MDU5MywyMy42Mjg5MjY4IDQyLjAxMDE2OTUsMjMuMDU0MzkwMiA0Mi4wMTAxNjk1LDIxLjYzMzI2ODMgQzQyLjAxMDE2OTUsMjAuMzE1NTEyMiA0My4xMTAzODE0LDE5LjQzNTk1MTIgNDQuNzk1MzM5LDE5LjQzNTk1MTIgQzQ2LjMwODA1MDgsMTkuNDM1OTUxMiA0Ny4zMDUyOTY2LDE5LjcwNjA5NzYgNDcuODU1MDg0NywyMC4xMTE5NTEyIEw0Ny44NTUwODQ3LDIwLjY4NzEyMiBMNDcuODU1MDg0NywyMC42ODcxMjIgWiBNNDQuNjU3NDE1MywxMy4wNzczNjU5IEM0My4zMTY5NDkyLDEzLjA3NzM2NTkgNDIuMDQ0NDkxNSwxMy4yNzk2NTg1IDQxLjA4MjIwMzQsMTMuNjUxOTAyNCBMNDEuNDYwMzgxNCwxNS40Nzk1MTIyIEM0Mi41NjA1OTMyLDE1LjE0MDg3OCA0My40NTQyMzczLDE1LjAwNTE3MDcgNDQuMzQ4NTE2OSwxNS4wMDUxNzA3IEM0Ni4yNzM3Mjg4LDE1LjAwNTE3MDcgNDcuODU1MDg0NywxNS44ODQ3MzE3IDQ3Ljg1NTA4NDcsMTcuODQ2MTQ2MyBMNDcuODU1MDg0NywxOC4xODQxNDYzIEM0Ny4yMzY2NTI1LDE3Ljk0ODI0MzkgNDYuMjczNzI4OCwxNy42NDMyMTk1IDQ0Ljg2Mzk4MzEsMTcuNjQzMjE5NSBDNDEuNzY5Mjc5NywxNy42NDMyMTk1IDM5Ljc0MTEwMTcsMTkuMTk4NzgwNSAzOS43NDExMDE3LDIxLjczNTM2NTkgQzM5Ljc0MTEwMTcsMjQuMzczNDE0NiA0MS43MzQ5NTc2LDI1LjU1NjczMTcgNDMuOTY5NzAzNCwyNS41NTY3MzE3IEM0NS44MjY5MDY4LDI1LjU1NjczMTcgNDcuMDk4NzI4OCwyNC44MTM1MTIyIDQ3Ljc1Mjc1NDIsMjMuOTMzMzE3MSBMNDcuODU1MDg0NywyMy45MzMzMTcxIEw0Ny44NTUwODQ3LDI1LjMyMDgyOTMgTDUwLjA1NjE0NDEsMjUuMzIwODI5MyBMNTAuMDU2MTQ0MSwxNy44MTI1MzY2IEM1MC4wNTYxNDQxLDE0LjUzMjczMTcgNDcuOTI0MzY0NCwxMy4wNzczNjU5IDQ0LjY1NzQxNTMsMTMuMDc3MzY1OSBMNDQuNjU3NDE1MywxMy4wNzczNjU5IFoiIGlkPSJGaWxsLTgiIGZpbGw9IiNGRkZGRkYiPjwvcGF0aD4gICAgICAgICAgICAgICAgICAgIDxwYXRoIGQ9Ik0xOS43OTgwOTMyLDkuMjU2IEwxOS43OTgwOTMyLDExLjQyMDk3NTYgTDI0Ljg4NjY1MjUsMTEuNDIwOTc1NiBMMjQuODg2NjUyNSwyNS4zMTk1NjEgTDI3LjI5NDI3OTcsMjUuMzE5NTYxIEwyNy4yOTQyNzk3LDExLjQyMDk3NTYgTDMyLjM4MjgzOSwxMS40MjA5NzU2IEwzMi4zODI4MzksOS4yNTYgTDE5Ljc5ODA5MzIsOS4yNTYiIGlkPSJGaWxsLTkiIGZpbGw9IiNGRkZGRkYiPjwvcGF0aD4gICAgICAgICAgICAgICAgICAgIDxwYXRoIGQ9Ik0zOS44NDQwNjc4LDEzLjU1MTA3MzIgQzM5LjEyMjAzMzksMTMuMjQ2NjgyOSAzOC4zMzEzNTU5LDEzLjIxMzA3MzIgMzcuODgzODk4MywxMy4yMTMwNzMyIEMzNi42MTE0NDA3LDEzLjIxMzA3MzIgMzUuMzc0NTc2MywxMy43MjAzOTAyIDM0LjcyMDU1MDgsMTQuNjMyMjkyNyBMMzQuNjE3NTg0NywxNC42MzIyOTI3IEwzNC42MTc1ODQ3LDEzLjMxNDUzNjYgTDMyLjQxNzE2MSwxMy4zMTQ1MzY2IEwzMi40MTcxNjEsMjUuMzIwMTk1MSBMMzQuNjg2ODY0NCwyNS4zMjAxOTUxIEwzNC42ODY4NjQ0LDE4Ljc1OTMxNzEgQzM0LjY4Njg2NDQsMTYuMjIyNzMxNyAzNS45MjQzNjQ0LDE1LjIwODA5NzYgMzcuNzQ2NjEwMiwxNS4yMDgwOTc2IEMzOC4zNjU2NzgsMTUuMjA4MDk3NiAzOC43NzgxNzgsMTUuMjc1OTUxMiAzOS4zMjg2MDE3LDE1LjQxMTAyNDQgTDM5Ljg0NDA2NzgsMTMuNTUxMDczMiIgaWQ9IkZpbGwtMTAiIGZpbGw9IiNGRkZGRkYiPjwvcGF0aD4gICAgICAgICAgICAgICAgICAgIDxwYXRoIGQ9Ik0xMDMuMDA2MTQ0LDEzLjU4NDY4MjkgQzEwMi4yODQxMSwxMy4yODA5MjY4IDEwMS40OTM0MzIsMTMuMjEyNDM5IDEwMS4wNDU5NzUsMTMuMjEyNDM5IEM5OS43NzQxNTI1LDEzLjIxMjQzOSA5OC4zOTg3Mjg4LDEzLjcxOTc1NjEgOTcuNzQ2NjEwMiwxNC42MzM1NjEgTDk3LjY0MTczNzMsMTQuNjMzNTYxIEw5Ny42NDE3MzczLDEzLjMxMzkwMjQgTDk1LjQ0MTk0OTIsMTMuMzEzOTAyNCBMOTUuNDQxOTQ5MiwyNS4zMTk1NjEgTDk3LjcxMTY1MjUsMjUuMzE5NTYxIEw5Ny43MTE2NTI1LDE4Ljc1OTMxNzEgQzk3LjcxMTY1MjUsMTYuMjIyNzMxNyA5OS4wODY0NDA3LDE1LjIwODczMTcgMTAwLjkwODY4NiwxNS4yMDg3MzE3IEMxMDEuNTI3NzU0LDE1LjIwODczMTcgMTAxLjk0MDI1NCwxNS4yNzUzMTcxIDEwMi40OTA2NzgsMTUuNDExMDI0NCBMMTAzLjAwNjE0NCwxMy41ODQ2ODI5IiBpZD0iRmlsbC0xMSIgZmlsbD0iI0ZGRkZGRiI+PC9wYXRoPiAgICAgICAgICAgICAgICAgICAgPHBhdGggZD0iTTE0NC4zNTcyMDMsMjMuNTYxNzA3MyBDMTQyLjE1NjE0NCwyMy41NjE3MDczIDE0MC42NDQwNjgsMjEuODM2MTk1MSAxNDAuNjQ0MDY4LDE5LjMzMzg1MzcgQzE0MC42NDQwNjgsMTcuMDAwODI5MyAxNDEuOTUwODQ3LDE1LjAwNDUzNjYgMTQ0LjA4MTk5MiwxNS4wMDQ1MzY2IEMxNDYuNTIzOTQxLDE1LjAwNDUzNjYgMTQ3LjE3NjY5NSwxNy4wMzQ0MzkgMTQ3LjI0NTk3NSwxOC4yODYyNDM5IEwxNDMuMDI1LDE4LjI4NjI0MzkgTDE0Mi4yMzQzMjIsMjAuMTEyNTg1NCBMMTQ5LjU0OTM2NCwyMC4xMTI1ODU0IEMxNDkuNTgzMDUxLDE5LjYzODI0MzkgMTQ5LjU4MzA1MSwxOS41MDM4MDQ5IDE0OS41ODMwNTEsMTkuMjY2NjM0MSBDMTQ5LjU4MzA1MSwxNS44MTY4NzggMTQ3LjgzMDA4NSwxMy4wNzggMTQ0LjA0NzY2OSwxMy4wNzggQzE0MC43ODEzNTYsMTMuMDc4IDEzOC4yNzEzOTgsMTUuNzE0NzgwNSAxMzguMjcxMzk4LDE5LjMzMzg1MzcgQzEzOC4yNzEzOTgsMjMuMDU0MzkwMiAxNDAuNjc3NzU0LDI1LjUyMjQ4NzggMTQ0LjExNjMxNCwyNS41MjI0ODc4IEMxNDYuMTgwMDg1LDI1LjUyMjQ4NzggMTQ4LjAwMjMzMSwyNC43NzkyNjgzIDE0OS4xMDI1NDIsMjMuNDYwMjQzOSBMMTQ3LjcyNjQ4MywyMi4xNDA1ODU0IEMxNDYuODMyODM5LDIzLjA1NDM5MDIgMTQ1LjY2Mzk4MywyMy41NjE3MDczIDE0NC4zNTcyMDMsMjMuNTYxNzA3MyIgaWQ9IkZpbGwtMTIiIGZpbGw9IiNGRkZGRkYiPjwvcGF0aD4gICAgICAgICAgICAgICAgICAgIDxwYXRoIGQ9Ik03MC4xNzEzOTgzLDE4LjM4ODM0MTUgQzY4LjQxNzc5NjYsMTguMTUxMTcwNyA2Ny4zODYyMjg4LDE3LjgxMjUzNjYgNjcuMzg2MjI4OCwxNi42NjI4MjkzIEM2Ny4zODYyMjg4LDE1LjYxNDU4NTQgNjguNDE3Nzk2NiwxNC45NzIxOTUxIDY5LjY5MDI1NDIsMTQuOTcyMTk1MSBDNzAuNzIxMTg2NCwxNC45NzIxOTUxIDcyLjAyNzk2NjEsMTUuMzc4NjgyOSA3Mi44NTIzMzA1LDE1Ljk4NzQ2MzQgTDczLjk1MzE3OCwxNC4zNjM0MTQ2IEM3Mi45MjIyNDU4LDEzLjUxNzQ2MzQgNzEuMjcxNjEwMiwxMy4wNzg2MzQxIDY5LjcyMzk0MDcsMTMuMDc4NjM0MSBDNjcuMDc2Njk0OSwxMy4wNzg2MzQxIDY1LjExNjUyNTQsMTQuNjY4NDM5IDY1LjExNjUyNTQsMTYuNzY0MjkyNyBDNjUuMTE2NTI1NCwxOS4xNjY0MzkgNjYuNjY0MTk0OSwxOS45NDM5MDI0IDY5LjI3Nzc1NDIsMjAuMzQ5N
                        zU2MSBDNzAuNzU2MTQ0MSwyMC41ODYyOTI3IDcyLjAyNzk2NjEsMjAuNzU1NjA5OCA3Mi4wMjc5NjYxLDIyLjAwNjc4MDUgQzcyLjAyNzk2NjEsMjMuMDU1MDI0NCA3MC45OTU3NjI3LDIzLjYzMDE5NTEgNjkuNjIxNjEwMiwyMy42MzAxOTUxIEM2OC4yODA1MDg1LDIzLjYzMDE5NTEgNjcuMDc2Njk0OSwyMy4yNTc5NTEyIDY1LjkwNzIwMzQsMjIuMzQ0NzgwNSBMNjQuOTEwNTkzMiwyNC4xMzY4NzggQzY1Ljc2OTkxNTMsMjQuOTE0OTc1NiA2Ny41NTg0NzQ2LDI1LjUyMzc1NjEgNjkuNTUyMzMwNSwyNS41MjM3NTYxIEM3Mi4zMDMxNzgsMjUuNTIzNzU2MSA3NC4yOTcwMzM5LDIzLjkzNDU4NTQgNzQuMjk3MDMzOSwyMS44MDM4NTM3IEM3NC4yOTcwMzM5LDE5LjIzMzY1ODUgNzIuMjM0NTMzOSwxOC42NTkxMjIgNzAuMTcxMzk4MywxOC4zODgzNDE1IiBpZD0iRmlsbC0xMyIgZmlsbD0iI0ZGRkZGRiI+PC9wYXRoPiAgICAgICAgICAgICAgICAgICAgPHBhdGggZD0iTTEzMi45NjAzODEsMTguMzkyMTQ2MyBDMTMxLjIwNjc4LDE4LjE1NDk3NTYgMTMwLjE3NTIxMiwxNy44MTYzNDE1IDEzMC4xNzUyMTIsMTYuNjY2NjM0MSBDMTMwLjE3NTIxMiwxNS42MTgzOTAyIDEzMS4yMDY3OCwxNC45NzYgMTMyLjQ3OTg3MywxNC45NzYgQzEzMy41MTAxNjksMTQuOTc2IDEzNC44MTc1ODUsMTUuMzgyNDg3OCAxMzUuNjQxOTQ5LDE1Ljk5MTI2ODMgTDEzNi43NDI3OTcsMTQuMzY2NTg1NCBDMTM1LjcxMTIyOSwxMy41MjEyNjgzIDEzNC4wNjEyMjksMTMuMDgyNDM5IDEzMi41MTM1NTksMTMuMDgyNDM5IEMxMjkuODY2MzE0LDEzLjA4MjQzOSAxMjcuOTA2NzgsMTQuNjcxNjA5OCAxMjcuOTA2NzgsMTYuNzY4MDk3NiBDMTI3LjkwNjc4LDE5LjE2OTYwOTggMTI5LjQ1MzgxNCwxOS45NDcwNzMyIDEzMi4wNjYxMDIsMjAuMzUyOTI2OCBDMTMzLjU0NTEyNywyMC41OTAwOTc2IDEzNC44MTc1ODUsMjAuNzU4NzgwNSAxMzQuODE3NTg1LDIyLjAwOTk1MTIgQzEzNC44MTc1ODUsMjMuMDU4MTk1MSAxMzMuNzg2MDE3LDIzLjYzNCAxMzIuNDEwNTkzLDIzLjYzNCBDMTMxLjA2OTQ5MiwyMy42MzQgMTI5Ljg2NjMxNCwyMy4yNjE3NTYxIDEyOC42OTY4MjIsMjIuMzQ3OTUxMiBMMTI3LjcwMDg0NywyNC4xNDEzMTcxIEMxMjguNTU5NTM0LDI0LjkxODc4MDUgMTMwLjM0NjgyMiwyNS41Mjc1NjEgMTMyLjM0MTk0OSwyNS41Mjc1NjEgQzEzNS4wOTIxNjEsMjUuNTI3NTYxIDEzNy4wODYwMTcsMjMuOTM3NzU2MSAxMzcuMDg2MDE3LDIxLjgwNzY1ODUgQzEzNy4wODYwMTcsMTkuMjM3NDYzNCAxMzUuMDIzNTE3LDE4LjY2MjI5MjcgMTMyLjk2MDM4MSwxOC4zOTIxNDYzIiBpZD0iRmlsbC0xNCIgZmlsbD0iI0ZGRkZGRiI+PC9wYXRoPiAgICAgICAgICAgICAgICA8L2c+ICAgICAgICAgICAgPC9nPiAgICAgICAgPC9nPiAgICA8L2c+PC9zdmc+">
                    </div>
                    <div class="hidden lg:block">
                        <ul class="flex items-center space-x-4">
                            <li @click="openDrop" @mouseover="openDrop" @mouseleave="closeDrop" class="flex hover:text-accent cursor-pointer relative" tabindex="-1">
                               <button class=" flex" type="button">
                                   <span> Money Transfer </span>
                                    <span aria-hidden="true" role="presentation"><svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" focusable="false" class="h-5 w-5 transition ease-in-out duration-150 text-current" viewBox="0 0 24 24"><path class="heroicon-ui" d="M15.3 9.3a1 1 0 0 1 1.4 1.4l-4 4a1 1 0 0 1-1.4 0l-4-4a1 1 0 0 1 1.4-1.4l3.3 3.29 3.3-3.3z"/></svg></span>
                                        <transition
                                        enter-active-class="transform transition ease-in-out duration-300 "
                                        enter-class=" opacity-0 translate-y-4 translate-y-0 scale-95"
                                        enter-to-class="opacity-100 translate-y-0 scale-100"
                                        leave-active-class="transform transition ease-in-out duration-300"
                                        leave-from-class="opacity-100 translate-y-0 scale-100"
                                        leave-to-class="opacity-0 translate-y-4 translate-y-0 scale-95"
                                        >
                                        <div v-show="showDrop" class="absolute top-0 right-0" style="width:430px">
                                            <div class="relative bg-white mt-10" style="box-shadow:0px 20px 66px 0 rgba(34,48,73,.2); border-radius:3px">
                                                <span class="absolute top-0 right-0 bg-white h-3 w-3 transform rotate-45 -mt-1 mr-3"></span>
                                                <div class="p-10 border-b border-gray-300" tabindex="0">
                                                    <img class="" src="https://daw291njkc3ao.cloudfront.net/conversion/navigation/send-money.svg" alt="">
                                                    <div class="flex space-x-2 items-center mt-3">
                                                        <strong class="text-primary tracking-wider text-sm">Send money</strong>
                                                        <svg width="10" height="10" fill="currentColor" class="text-primary"><path fill-rule="evenodd" d="M7.913 5L3.235.064 2.087 1.275 5.616 5l-3.53 3.725 1.149 1.211z"></path></svg>
                                                    </div>
                                                    <p class="text-secondary mt-3 tracking-wider text-left">
                                                        Make a one-off payment. You'll get the real exchange rate with the low fee we're known for.
                                                    </p>
                                                </div>
                                                <div class="p-10 bg-gray-100 rounded-b">
                                                    <div class="flex space-x-2 items-center mt-3" tabindex="0">
                                                        <p class="text-primary font-semibold tracking-wider text-xs">Send large amount</p>
                                                        <svg width="10" height="10" fill="currentColor" class="text-primary"><path fill-rule="evenodd" d="M7.913 5L3.235.064 2.087 1.275 5.616 5l-3.53 3.725 1.149 1.211z"></path></svg>
                                                    </div>
                                                    <div class="flex space-x-2 items-center mt-3" tabindex="0">
                                                        <p class="text-primary font-semibold tracking-wider text-xs">About TransferWise</p>
                                                        <svg width="10" height="10" fill="currentColor" class="text-primary"><path fill-rule="evenodd" d="M7.913 5L3.235.064 2.087 1.275 5.616 5l-3.53 3.725 1.149 1.211z"></path></svg>
                                                    </div>
                                                    <div class="flex space-x-2 items-center mt-3" tabindex="0">
                                                        <p class="text-primary font-semibold tracking-wider text-xs">Track your transfer</p>
                                                        <svg width="10" height="10" fill="currentColor" class="text-primary"><path fill-rule="evenodd" d="M7.913 5L3.235.064 2.087 1.275 5.616 5l-3.53 3.725 1.149 1.211z"></path></svg>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </transition>
                               </button>
                            </li>
                            <li class="flex hover:text-accent cursor-pointer"> <span class="bg-positive mr-1 rounded-full px-2 leading-5 text-white font-medium" style="font-size: 8px">New</span> <span>Multi-currency-account</span> <span><svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="h-5 w-5 transition ease-in-out duration-150 text-current" viewBox="0 0 24 24"><path class="heroicon-ui" d="M15.3 9.3a1 1 0 0 1 1.4 1.4l-4 4a1 1 0 0 1-1.4 0l-4-4a1 1 0 0 1 1.4-1.4l3.3 3.29 3.3-3.3z"/></svg></span></li>
                            <li class="flex hover:text-accent cursor-pointer">Business <span><svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="h-5 w-5 transition ease-in-out duration-150 text-current" viewBox="0 0 24 24"><path class="heroicon-ui" d="M15.3 9.3a1 1 0 0 1 1.4 1.4l-4 4a1 1 0 0 1-1.4 0l-4-4a1 1 0 0 1 1.4-1.4l3.3 3.29 3.3-3.3z"/></svg></span></li>
                            <li class="flex hover:text-accent cursor-pointer">Help</li>
                            <li class="flex item-center hover:text-accent cursor-pointer"> <span class="mr-1"><svg width="16" height="16" fill="currentColor" class="text-current" focusable="false"><path fill-rule="evenodd" clip-rule="evenodd" d="M16 8A8 8 0 100 8a8 8 0 0016 0zm-11.483.8c.09 2.045.515 3.863 1.149 5.161A6.407 6.407 0 011.65 8.8h2.867zm1.602 0c.081 1.703.416 3.174.872 4.215.264.604.537.992.759 1.206.137.133.22.169.25.178.03-.01.113-.045.25-.178.222-.214.495-.602.76-1.206.455-1.041.79-2.512.871-4.215H6.12zm3.762-1.6H6.12c.081-1.703.416-3.174.872-4.216.264-.603.537-.99.759-1.205.137-.133.22-.169.25-.178.03.01.113.045.25.178.222.215.495.602.76 1.205.455 1.042.79 2.513.871 4.216zm1.602 1.6c-.089 2.045-.515 3.863-1.149 5.161A6.407 6.407 0 0014.351 8.8h-2.868zm2.868-1.6h-2.868c-.089-2.045-.515-3.863-1.149-5.16a6.407 6.407 0 014.017 5.16zm-9.834 0H1.65a6.407 6.407 0 014.016-5.16c-.634 1.297-1.06 3.115-1.149 5.16z"></path></svg></span> EN <span><svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="h-5 w-5 transition ease-in-out duration-150 text-current" viewBox="0 0 24 24"><path class="heroicon-ui" d="M15.3 9.3a1 1 0 0 1 1.4 1.4l-4 4a1 1 0 0 1-1.4 0l-4-4a1 1 0 0 1 1.4-1.4l3.3 3.29 3.3-3.3z"/></svg></span></li>
                            <li class="flex hover:text-accent cursor-pointer">Log in</li>
                            <li class="border border-accent px-4 rounded py-1 leading-6 text-accent hover:text-white hover:bg-accent cursor-pointer">Register</li>
                        </ul>
                    </div>
                </nav>
            </div>
            <div class="block lg:hidden">
                <nav  class="text-white flex justify-between items-center text-sm">
                    <div class="logo flex space-x-2 items-center">
                        <button @click="toggleShow" class="focus:outline-none">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="w-5 h-6 text-accent" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                            </svg>
                        </button>
                        <a href="#" class="text-lg tracking-wide">TransferWise</a>
                    </div>
                    <div class="">
                        <ul class="flex items-center space-x-4">
                            <li class="border border-accent px-4 rounded py-1 leading-6 text-accent hover:text-white hover:bg-accent cursor-pointer">Register</li>
                        </ul>
                    </div>
                </nav>
            </div>
            <transition
                enter-active-class="transform transition ease-in-out duration-700"
                enter-class="-translate-x-full"
                enter-to-class="-translate-x-0"
                leave-active-class="transform transition ease-in-out duration-700"
                leave-from-class="-translate-x-0"
                leave-to-class="-translate-x-full"
                >
                <div v-show="show" class="block lg:hidden fixed top-0 left-0 w-full h-screen min-h-screen z-50">
                    <div class="bg-primary text-white w-full h-full flex flex-col justify-between px-4">
                        <div>
                            <div class="header py-4 space-x-2 flex border-b border-fader-background">
                                <button @click="toggleShow" class="focus:outline-none">
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="w-5 h-5 text-accent font-medium" viewBox="0 0 20 20">
                                        <path fill-rule="evenodd" d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z" clip-rule="evenodd" />
                                    </svg>
                                </button>
                                <a href="#" class="text-lg tracking-wide">TransferWise</a>
                            </div>
                            <ul class="text-sm font-medium">
                                <li class="flex justify-between items-center py-5 border-b border-fader-background relative">
                                    <span>Money Transfer</span> 
                                    <span><svg xmlns="http://www.w3.org/2000/svg" class="w-4 h-4 text-accent" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" /></svg></span> 
                                </li>
                                <li class="flex justify-between py-5 border-b border-fader-background"><div><span class="mr-2">Multi-currency-account</span> <span class="bg-positive rounded-full py-1 px-2 text-white" style="font-size: 10px">New</span></div><span><svg xmlns="http://www.w3.org/2000/svg" class="w-4 h-4 text-accent" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" /></svg></span></li>
                                <li class="flex justify-between py-5 border-b border-fader-background"><span>Business</span> <span><svg xmlns="http://www.w3.org/2000/svg" class="w-4 h-4 text-accent" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" /></svg></span></li>
                                <li class="flex justify-between py-5 border-b border-fader-background"><span>Help</span> <span><svg xmlns="http://www.w3.org/2000/svg" class="w-4 h-4 text-accent" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" /></svg></span></li>
                                <li class="flex justify-between py-5 border-b border-fader-background"><div class="flex space-x-2 items-center"><span><svg width="16" height="16" fill="currentColor" focusable="false"><path fill-rule="evenodd" clip-rule="evenodd" d="M16 8A8 8 0 100 8a8 8 0 0016 0zm-11.483.8c.09 2.045.515 3.863 1.149 5.161A6.407 6.407 0 011.65 8.8h2.867zm1.602 0c.081 1.703.416 3.174.872 4.215.264.604.537.992.759 1.206.137.133.22.169.25.178.03-.01.113-.045.25-.178.222-.214.495-.602.76-1.206.455-1.041.79-2.512.871-4.215H6.12zm3.762-1.6H6.12c.081-1.703.416-3.174.872-4.216.264-.603.537-.99.759-1.205.137-.133.22-.169.25-.178.03.01.113.045.25.178.222.215.495.602.76 1.205.455 1.042.79 2.513.871 4.216zm1.602 1.6c-.089 2.045-.515 3.863-1.149 5.161A6.407 6.407 0 0014.351 8.8h-2.868zm2.868-1.6h-2.868c-.089-2.045-.515-3.863-1.149-5.16a6.407 6.407 0 014.017 5.16zm-9.834 0H1.65a6.407 6.407 0 014.016-5.16c-.634 1.297-1.06 3.115-1.149 5.16z"></path></svg></span> <span>EN</span> </div><span><svg xmlns="http://www.w3.org/2000/svg" class="w-4 h-4 text-accent" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" /></svg></span></li>
                            </ul>
                        </div>
                        <div class="py-6 space-y-3">
                            <button class="mt-6 w-full px-6 py-3 rounded text-accent hover:text-white bg-transparent hover:bg-accent border border-accent">Log in</button>
                            <button class="mt-6 w-full px-6 py-3 rounded text-white bg-accent">Register</button>
                        </div>
                    </div>
                </div>
            </transition>
            <div class="converter-container w-full flex flex-col  sm:flex-row flex-no-wrap sm:flex-wrap py-12 mt-4 sm:mt-16 text-white">
                <div class="w-full lg:w-1/2 ">
                    <div class="w-full px-16 lg:pl-0 lg:pr-28">
                        <h1 class="text-2xl lg:text-4xl font-semibold tracking-wide lg:tracking-wider text-center lg:text-left">
                            The cheap, fast way to send money abroad<span class="text-accent">.</span>
                        </h1>
                        <p class="hidden lg:block mt-12 text-text-hero font-light">Join over 9 million people who get the real exchange rate with TransferWise. We’re <span class="text-accent underline">on average 8x cheaper</span> than leading UK high street banks.</p>
                        <div class="mt-12 hidden lg:block">
                            <button class="flex items-center border border-accent px-4 rounded py-2 leading-6 text-accent hover:text-white hover:bg-accent space-x-4">
                                <span>
                                    <svg class="tw-play-icon text-current transition-all delay-75 " fill="currentColor" width="30" height="30" xmlns="http://www.w3.org/2000/svg"><path d="M15 0c8.284 0 15 6.624 15 14.796v.408C30 23.376 23.284 30 15 30 6.716 30 0 23.376 0 15.204v-.408C0 6.624 6.716 0 15 0zm4.655 14.796l-7.241-5.612v11.224l7.241-5.612z" fill-rule="nonzero"></path></svg>
                                </span>
                                <span class="font-medium">See how we send money</span>
                            </button>
                        </div>
                    </div>
                    <div class="hidden lg:block w-full">
                        <div class="flex w-full items-center mt-20">
                            <div class="w-1/2">
                                <div class="w-16 h-20">
                                    <span>
                                        <svg id="el_H8G--UHWO" class="tw-trust-element__image" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 84 50"><path d="M14.3 43.5h46.9v-21H0v21h7.1V50l7.2-6.5z" id="el_o50-IfnOhY"></path><g id="el_ZKUtuKmlJ2_an_27_VJB_eK" data-animator-group="true" data-animator-type="2"><path d="M70.1 38.5H7.2v-24h77.2v24h-7.1V45l-7.2-6.5z" id="el_ZKUtuKmlJ2"></path></g><g id="el_cKmWEw9KDj_an_Al496FKhj" data-animator-group="true" data-animator-type="2"><path d="M24 25.5h-3.2l-1-3-1 3h-3.2l2.6 1.9-1 3.1 2.6-1.9 2.6 1.9-1-3.1 2.6-1.9z" id="el_cKmWEw9KDj"></path></g><g id="el_FrN2weN1HV_an_VyY4hnoQje" data-animator-group="true" data-animator-type="2"><path id="el_FrN2weN1HV" d="M37 25.5h-3.2l-1-3-1 3h-3.2l2.6 1.9-1 3.1 2.6-1.9 2.6 1.9-1-3.1z"></path></g><g id="el_QxWDtUDnYN_an_fi3jS4kw1" data-animator-group="true" data-animator-type="2"><path id="el_QxWDtUDnYN" d="M50 25.5h-3.2l-1-3-1 3h-3.2l2.6 1.9-1 3.1 2.6-1.9 2.6 1.9-1-3.1 2.6-1.9z"></path></g><g id="el_0LSJko48lh_an_2TS1w_u6J" data-animator-group="true" data-animator-type="2"><path id="el_0LSJko48lh" d="M63 25.5h-3.2l-1-3-1 3h-3.2l2.6 1.9-1 3.1 2.6-1.9 2.6 1.9-1-3.1 2.6-1.9z"></path></g><g id="el_Yv2r1TIYxk_an_GdS0Y6cG7" data-animator-group="true" data-animator-type="2"><path id="el_Yv2r1TIYxk" d="M76 25.5h-3.2l-1-3-1 3h-3.2l2.6 1.9-1 3.1 2.6-1.9 2.6 1.9-1-3.1 2.6-1.9z"></path></g></svg>
                                    </span>
                                </div>
                                <div class="">
                                    <h4 class="text-lg font-medium">Over 9 million customers</h4>
                                    <div class="flex items-center">
                                        <h4 class="text-sm text-accent font-medium">Read on Trustpilot</h4>
                                        <span class="ml-2">
                                            <svg class="text-accent" width="10" height="10" fill="currentColor"><path fill-rule="evenodd" d="M7.913 5L3.235.064 2.087 1.275 5.616 5l-3.53 3.725 1.149 1.211z"></path></svg>
                                        </span>
                                    </div>
                                </div>
                            </div>
                            <div class="w-1/2 flex flex-col">
                                <div class="">
                                    <div class="block w-16 h-20">
                                        <svg viewBox="0 0 49 48" fill="none" xmlns="http://www.w3.org/2000/svg" class="tw-trust-element__image"><path d="M39.586 46.567H.269v.998h39.317v-.998z" fill="url(#paint0_linear)"></path><path fill-rule="evenodd" clip-rule="evenodd" d="M33.818 12.68H23.36l.582-1.383H34.4l-.582 1.383z" fill="#7CD9F5"></path><path d="M34.456 7.282H5.4a.927.927 0 00-.927.927v38.186c0 .512.415.927.927.927h29.056a.927.927 0 00.927-.927V8.21a.927.927 0 00-.928-.927z" fill="#DBF4FE"></path><path fill-rule="evenodd" clip-rule="evenodd" d="M29.546 37.992H9l.59-1.375h20.546l-.59 1.375zM29.546 30.992H9l.59-1.375h20.546l-.59 1.375zM29.546 23.992H9l.59-1.375h20.546l-.59 1.375zM19.466 16.383H9L9.59 15h10.457l-.581 1.383z" fill="#7CD9F5"></path><path fill-rule="evenodd" clip-rule="evenodd" d="M28.482 17H17l1.539-3H30l-1.518 3z" fill="#7CD9F5"></path><path d="M45.157 39.373l2.3-1.673L36.735 22.96l-2.3 1.673 10.722 14.741z" fill="#253655"></path><path d="M47.836 40.352a2.184 2.184 0 00.48-3.04l-7.426-9.948-3.512 2.562 7.417 9.955a2.184 2.184 0 003.04.471z" fill="#485CC7"></path><path d="M34.884 26.537l3.514-2.556-.939-1.29-3.514 2.556.939 1.29z" fill="#253655"></path><path opacity=".7" d="M28.405 23.947c5.611 0 10.16-4.549 10.16-10.16 0-5.61-4.549-10.16-10.16-10.16-5.61 0-10.159 4.55-10.159 10.16 0 5.611 4.549 10.16 10.16 10.16z" fill="#fff"></path><path d="M18.254 20.514a12.186 12.186 0 103.473-16.886 12.194 12.194 0 00-3.473 16.886zm2.255-1.485a9.492 9.492 0 1113.153 2.71 9.5 9.5 0 01-13.153-2.71z" fill="#fff"></path><path d="M17.547 21.024a13.043 13.043 0 1021.78-14.357 13.043 13.043 0 00-21.78 14.357zm2.404-1.572a10.159 10.159 0 1114.072 2.892 10.167 10.167 0 01-14.072-2.947v.056z" fill="#253655"></path><defs><linearGradient id="paint0_linear" x1=".269" y1="47.07" x2="39.586" y2="47.07" gradientUnits="userSpaceOnUse"><stop stop-opacity="0"></stop><stop offset=".07" stop-opacity=".16"></stop><stop offset=".5" stop-opacity=".3"></stop><stop offset=".93" stop-opacity=".16"></stop><stop offset="1" stop-opacity="0"></stop></linearGradient></defs>
                                        </svg>
                                    </div>
                                    <div class="">
                                        <h4 class="text-lg tracking-wide font-medium">FCA regulated</h4>
                                        <div class="flex items-center">
                                            <h4 class="text-sm text-accent font-medium">Learn More</h4>
                                            <span class="ml-2">
                                                <svg class="text-accent" width="10" height="10" fill="currentColor"><path fill-rule="evenodd" d="M7.913 5L3.235.064 2.087 1.275 5.616 5l-3.53 3.725 1.149 1.211z"></path></svg>
                                            </span>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w-full lg:w-1/2 mt-4 lg:mt-0">
                    <div class="container px-0 lg:pl-32 w-full">
                        <ContainerInput country="us" currency="USD" title="You send"/>
                         <div class="w-full h-36 px-6">
                             <div class="border-l-2 border-converter-border w-full h-full relative">
                                 <div class="absolute right-0 top-0 w-full h-28 mt-4 mr-3 flex flex-col justify-between text-sm">
                                    <div class="flex space-x-3 items-center">
                                         <span class="w-6 h-6 bg-converter-border rounded-full text-white flex items-center justify-center text-lg font-light"> - </span>
                                         <p class="font-medium text-xs lg:text-base">5.53 USD</p>
                                         <button class="focus:outline-none bg-converter-button border border-transparent hover:bg-converter-border rounded cursor-pointer flex justify-between items-center px-2 py-1">
                                            <span class="text-xs">Low cost transfer</span>
                                            <span>
                                                <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="h-4 w-4 transition ease-in-out duration-150 text-accent" viewBox="0 0 24 24"><path class="heroicon-ui" d="M15.3 9.3a1 1 0 0 1 1.4 1.4l-4 4a1 1 0 0 1-1.4 0l-4-4a1 1 0 0 1 1.4-1.4l3.3 3.29 3.3-3.3z"/></svg>
                                            </span>
                                         </button>
                                         <p class="text-text-accent font-light">fee</p>
                                    </div>
                                    <div class="flex items-center space-x-3 font-light">
                                         <span class="w-6 h-6 bg-converter-border rounded-full text-white flex items-center justify-center text-lg"> = </span>
                                         <p class="text-text-accent font-light text-sm lg:text-sm">995.53 USD</p>
                                         <p class="text-text-accent font-light text-xs lg:text-sm">Amount we convert</p>
                                    </div>
                                    <div class="flex items-center space-x-3">
                                         <span class="w-6 h-6 bg-converter-border rounded-full text-white flex items-center justify-center"> x </span>
                                         <p class="text-accent font-medium text-sm lg:text-sm">527.932</p>
                                         <p class="text-text-accent font-light text-xs lg:text-sm">Guaranteed rate (2hrs)</p>
                                    </div>
                                 </div>
                             </div>
                         </div>
                        <ContainerInput country="ng" currency="NGN" title="Recipient get"/>
                        <div class="mt-8 w-full">
                            <button class="w-full bg-positive rounded py-4 hover:bg-control-positive-hover text-sm font-medium">Get started</button>
                        </div>
                    </div>
                </div>
            </div>
            <div class="block lg:hidden mb-6">
                <div class="flex flex-col space-y-4 justify-center items-center">
                    <img src="../assets/apple-store.svg" alt="apple store" class="w-2/4">
                    <img src="../assets/android-store.svg" alt="apple store" class="w-3/5">
                </div>
                <p class="text-text-hero font-light text-center px-2 text-sm mt-10 tracking-wide leading-6">Join over 9 million people who get the real exchange rate with TransferWise. We’re <span class="text-accent underline">on average 8x cheaper</span> than leading UK high street banks.</p>
                <div class="flex flex-col w-full justify-center items-center mt-10">
                    <div class="w-full flex flex-col justify-center items-center">
                        <div class="w-16 justify-center items-center">
                            <span>
                                <svg id="el_H8G--UHWO" class="tw-trust-element__image"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 84 50"><path d="M14.3 43.5h46.9v-21H0v21h7.1V50l7.2-6.5z" id="el_o50-IfnOhY"></path><g id="el_ZKUtuKmlJ2_an_27_VJB_eK" data-animator-group="true" data-animator-type="2"><path d="M70.1 38.5H7.2v-24h77.2v24h-7.1V45l-7.2-6.5z" id="el_ZKUtuKmlJ2"></path></g><g id="el_cKmWEw9KDj_an_Al496FKhj" data-animator-group="true" data-animator-type="2"><path d="M24 25.5h-3.2l-1-3-1 3h-3.2l2.6 1.9-1 3.1 2.6-1.9 2.6 1.9-1-3.1 2.6-1.9z" id="el_cKmWEw9KDj"></path></g><g id="el_FrN2weN1HV_an_VyY4hnoQje" data-animator-group="true" data-animator-type="2"><path id="el_FrN2weN1HV" d="M37 25.5h-3.2l-1-3-1 3h-3.2l2.6 1.9-1 3.1 2.6-1.9 2.6 1.9-1-3.1z"></path></g><g id="el_QxWDtUDnYN_an_fi3jS4kw1" data-animator-group="true" data-animator-type="2"><path id="el_QxWDtUDnYN" d="M50 25.5h-3.2l-1-3-1 3h-3.2l2.6 1.9-1 3.1 2.6-1.9 2.6 1.9-1-3.1 2.6-1.9z"></path></g><g id="el_0LSJko48lh_an_2TS1w_u6J" data-animator-group="true" data-animator-type="2"><path id="el_0LSJko48lh" d="M63 25.5h-3.2l-1-3-1 3h-3.2l2.6 1.9-1 3.1 2.6-1.9 2.6 1.9-1-3.1 2.6-1.9z"></path></g><g id="el_Yv2r1TIYxk_an_GdS0Y6cG7" data-animator-group="true" data-animator-type="2"><path id="el_Yv2r1TIYxk" d="M76 25.5h-3.2l-1-3-1 3h-3.2l2.6 1.9-1 3.1 2.6-1.9 2.6 1.9-1-3.1 2.6-1.9z"></path></g></svg>
                            </span>
                        </div>
                        <div class="mt-3 w-full text-center">
                            <h4 class="text-white">Over 9 million customers</h4>
                            <div class="flex items-center justify-center">
                                <h4 class="text-sm text-accent font-medium text-center">Read on Trustpilot</h4>
                                <span class="ml-2">
                                    <svg class="text-accent" width="10" height="10" fill="currentColor" ><path fill-rule="evenodd" d="M7.913 5L3.235.064 2.087 1.275 5.616 5l-3.53 3.725 1.149 1.211z"></path></svg>
                                </span>
                            </div>
                        </div>
                    </div>
                    <div class="w-full flex flex-col justify-center items-center mt-6">
                        <div class="w-16 justify-center items-center">
                            <span>
                                <svg viewBox="0 0 49 48" fill="none" xmlns="http://www.w3.org/2000/svg" class="tw-trust-element__image"><path d="M39.586 46.567H.269v.998h39.317v-.998z" fill="url(#paint0_linear)"></path><path fill-rule="evenodd" clip-rule="evenodd" d="M33.818 12.68H23.36l.582-1.383H34.4l-.582 1.383z" fill="#7CD9F5"></path><path d="M34.456 7.282H5.4a.927.927 0 00-.927.927v38.186c0 .512.415.927.927.927h29.056a.927.927 0 00.927-.927V8.21a.927.927 0 00-.928-.927z" fill="#DBF4FE"></path><path fill-rule="evenodd" clip-rule="evenodd" d="M29.546 37.992H9l.59-1.375h20.546l-.59 1.375zM29.546 30.992H9l.59-1.375h20.546l-.59 1.375zM29.546 23.992H9l.59-1.375h20.546l-.59 1.375zM19.466 16.383H9L9.59 15h10.457l-.581 1.383z" fill="#7CD9F5"></path><path fill-rule="evenodd" clip-rule="evenodd" d="M28.482 17H17l1.539-3H30l-1.518 3z" fill="#7CD9F5"></path><path d="M45.157 39.373l2.3-1.673L36.735 22.96l-2.3 1.673 10.722 14.741z" fill="#253655"></path><path d="M47.836 40.352a2.184 2.184 0 00.48-3.04l-7.426-9.948-3.512 2.562 7.417 9.955a2.184 2.184 0 003.04.471z" fill="#485CC7"></path><path d="M34.884 26.537l3.514-2.556-.939-1.29-3.514 2.556.939 1.29z" fill="#253655"></path><path opacity=".7" d="M28.405 23.947c5.611 0 10.16-4.549 10.16-10.16 0-5.61-4.549-10.16-10.16-10.16-5.61 0-10.159 4.55-10.159 10.16 0 5.611 4.549 10.16 10.16 10.16z" fill="#fff"></path><path d="M18.254 20.514a12.186 12.186 0 103.473-16.886 12.194 12.194 0 00-3.473 16.886zm2.255-1.485a9.492 9.492 0 1113.153 2.71 9.5 9.5 0 01-13.153-2.71z" fill="#fff"></path><path d="M17.547 21.024a13.043 13.043 0 1021.78-14.357 13.043 13.043 0 00-21.78 14.357zm2.404-1.572a10.159 10.159 0 1114.072 2.892 10.167 10.167 0 01-14.072-2.947v.056z" fill="#253655"></path><defs><linearGradient id="paint0_linear" x1=".269" y1="47.07" x2="39.586" y2="47.07" gradientUnits="userSpaceOnUse"><stop stop-opacity="0"></stop><stop offset=".07" stop-opacity=".16"></stop><stop offset=".5" stop-opacity=".3"></stop><stop offset=".93" stop-opacity=".16"></stop><stop offset="1" stop-opacity="0"></stop></linearGradient></defs>
                                </svg>
                            </span>
                        </div>
                        <div class="mt-4">
                            <h4 class="tracking-wide text-white">FCA regulated</h4>
                            <div class="flex items-center w-full justify-center">
                                <h4 class="text-sm text-accent text-center font-medium">Learn More</h4>
                                <span class="ml-2">
                                    <svg class="text-accent" width="10" height="10" fill="currentColor"><path fill-rule="evenodd" d="M7.913 5L3.235.064 2.087 1.275 5.616 5l-3.53 3.725 1.149 1.211z"></path></svg>
                                </span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import ContainerInput from './ConverterInput'
export default {
    components:{
        ContainerInput
    },

    data(){
        return{
            show: false,
            showDrop: false,
        }
    },

    methods:{
        toggleShow(){
            this.show = !this.show
        },
        openDrop(){
            this.showDrop = true
        },
        closeDrop(){
            this.showDrop = false
        }
    }
    
}


</script>

<style>
.tw-trust-element #el_ZKUtuKmlJ2 {
    fill: #dbf4fe;
}

.tw-trust-element #el_H8G--UHWO * {
    -webkit-animation-duration: 3s;
    animation-duration: 3s;
    -webkit-animation-iteration-count: 1;
    animation-iteration-count: 1;
    -webkit-animation-play-state: running;
    animation-play-state: running;
    -webkit-animation-timing-function: cubic-bezier(0,0,1,1);
    animation-timing-function: cubic-bezier(0,0,1,1);
}
    
</style>

