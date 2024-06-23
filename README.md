## Live as much as I know!
<img src="https://github.com/injae-kim/injae-kim/assets/34854527/70215679-4007-4ce7-be37-43b9d3a2cd4d" width=350>
<img src="https://github.com/injae-kim/injae-kim/assets/34854527/a4087de9-3642-4533-aef7-4428ec4511b2" width=300>

- [How LINE OpenChat Server Handles x100 Extream Traffic Spikes](https://engineering.linecorp.com/ko/blog/how-line-openchat-server-handles-extreme-traffic-spikes), LINE&Yahoo Japan tech-verse 2022
- [LINE OpenSource Sprint 2023](https://youtu.be/jYT98fxN6Ak?si=LSmXIHclJGQEmjLx&t=306) - Armeria MVP

I'm `LINE OpenChat` backend engineer and open source contributor(my hobby) on `LINE/armeria`, `spring-framework`, `spring-batch`, `reactor-core`..

Also participated in [2 start-up](https://injae-kim.github.io/experience/2020/09/06/sheco-startup.html) as founding member for 3 years.

## Open Source Contributions
- [LINE/armeria](https://github.com/line/armeria/pulls?q=is%3Apr+author%3Ainjae-kim) (15+ new feature)
  - Add `AsyncLoader` to load and update value periodically [#5590](https://github.com/line/armeria/pull/5590)
  - Add `CompositeHttpHeaders` that wraps `HttpHeaders` without expensive copy operations [#5340](https://github.com/line/armeria/pull/5340)
  - Add `StreamMessage(reactive-streams, async)` <-> `InputStream, OutputStream(sync)` converter [#4703](https://github.com/line/armeria/pull/4703)
  - Add `SurroundingPublisher` that can add head or tail item on `Publisher(reactive-streams)` [#4727](https://github.com/line/armeria/pull/4727)
- [spring-framework](https://github.com/spring-projects/spring-framework/pulls?q=is%3Apr+author%3Ainjae-kim+)
  - Support sending large `STOMP messages` as fragmented frames on `WebSocketStompClient` [#31970](https://github.com/spring-projects/spring-framework/pull/31970)
  - Fix `DefaultDataBuffer#getNativeBuffer()` to set correct limit [#32009](https://github.com/spring-projects/spring-framework/pull/32009)
  - `WebClient` and `RestClient`'s `defaultRequest(..)` is not invoked early enough [#32053](https://github.com/spring-projects/spring-framework/issues/32053)
- [spring-batch](https://github.com/spring-projects/spring-batch/pulls?q=is%3Apr+author%3Ainjae-kim+)
  - Fix `FlowBuilder.next().end()` infinite loop [#4475](https://github.com/spring-projects/spring-batch/pull/4475)
  - Support full `regular expression` on `PatterMatcher.match()` [#4492](https://github.com/spring-projects/spring-batch/pull/4492)
  - Fix `SystemCommandTasklet` to propagate error when exit status is failed [#4566](https://github.com/spring-projects/spring-batch/pull/4566)
- [reactor-core](https://github.com/reactor/reactor-core/pulls?q=is%3Apr+author%3Ainjae-kim+)
  - Add `AutoCloseable` shourtcut on `Flux#using`, `Mono#using` [#3704](https://github.com/reactor/reactor-core/pull/3704)
  - Throw wrapped `TimeoutException` on `Mono.block*` and `Flux.block*` [#3733](https://github.com/reactor/reactor-core/pull/3733)
  - `expandDeep` uses unbounded queue which results in OutOfMemoryException [#3411](https://github.com/reactor/reactor-core/issues/3411)
- [netty](https://github.com/netty/netty/pulls?q=is%3Apr+author%3Ainjae-kim+)
  - Make `ScheduledEventExecutor` task scheduler pluggable [#13552](https://github.com/netty/netty/pull/13552)
- [resilience4j](https://github.com/resilience4j/resilience4j/pulls?q=is%3Apr+author%3Ainjae-kim+)
  - Add `startedTime` configuration on `RateLimiter` [#2100](https://github.com/resilience4j/resilience4j/pull/2100)
- [apache-pekko](https://github.com/apache/incubator-pekko/pulls?q=is%3Apr+author%3Ainjae-kim+)
  - Add `AutoCloseable` shortcut on `mapWithResource` [#1053](https://github.com/apache/incubator-pekko/pull/1053)
- [angular](https://github.com/angular/angular/pulls?q=is%3Apr+author%3Ainjae-kim+)
  - fix(core): Fix decimal pipe floating point formatting bug [#53730](https://github.com/angular/angular/pull/53730)
- [![OpenSource Mentoring](https://img.shields.io/badge/GDG-OpenSource_Mentoring-blue.svg?logo=data:image/svg%2bxml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz4KPHN2ZyB3aWR0aD0iMjU2cHgiIGhlaWdodD0iMTI1cHgiIHZpZXdCb3g9IjAgMCAyNTYgMTI1IiB2ZXJzaW9uPSIxLjEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHByZXNlcnZlQXNwZWN0UmF0aW89InhNaWRZTWlkIj4KICAgIDxnPgogICAgICAgIDxwYXRoIGQ9Ik0xODQuMzE0ODEsNjcuNzA0NDU4NyBDMTk3Ljc4MzgxLDU5Ljk2ODQ1ODcgMjExLjIxNjgxLDUyLjE2OTQ1ODcgMjI0LjczMTgxLDQ0LjUxMzQ1ODcgQzIzNy41NTk4MSwzNy4yNDU0NTg3IDI1Mi42NTI4MSw0My45NDg0NTg3IDI1NS41NjA4MSw1OC4wOTI0NTg3IEMyNTcuMjQzODEsNjYuMjc0NDU4NyAyNTMuNTkwODEsNzUuMTEzNDU4NyAyNDYuMjAzODEsNzkuNDE4NDU4NyBDMjIxLjk4NTgxLDkzLjUzMTQ1ODcgMTk3LjczMjgxLDEwNy41ODg0NTkgMTczLjM1ODgxLDEyMS40MzA0NTkgQzE2NS44MTQ4MSwxMjUuNzE0NDU5IDE1OC4wNDM4MSwxMjQuOTI2NDU5IDE1MS4xNjg4MSwxMTkuNjc2NDU5IEMxNDQuMTg0ODEsMTE0LjM0NjQ1OSAxNDEuOTgzODEsMTA2Ljk5NDQ1OSAxNDMuNjIxODEsOTguNDM3NDU4NyBDMTQ1LjQ5MTgxLDkxLjkyMzQ1ODcgMTQ5Ljc3MTgxLDg3LjU2ODQ1ODcgMTU1LjYwODgxLDg0LjMxMDQ1ODcgQzE2NS4yNTk4MSw3OC45MjQ0NTg3IDE3NC43NTM4MSw3My4yNTQ0NTg3IDE4NC4zMTQ4MSw2Ny43MDQ0NTg3IiBmaWxsPSIjRkFCQzA1Ij48L3BhdGg+CiAgICAgICAgPHBhdGggZD0iTTE5NC4yMDM0MSw2Mi4wNzg5NTg3IEMxODAuNzY4NDEsNTQuMjgyOTU4NyAxNjcuMjk5NDEsNDYuNTQ3OTU4NyAxNTMuOTExNDEsMzguNjcyOTU4NyBDMTQxLjIwMjQxLDMxLjE5Njk1ODcgMTM5LjQ2MjQxLDE0Ljc3NDk1ODcgMTUwLjI1NjQxLDUuMTgyOTU4NzEgQzE1Ni41MDA0MSwtMC4zNjQwNDEyODYgMTY1Ljk4MTQxLC0xLjYyMTA0MTI5IDE3My40MDM0MSwyLjYyMzk1ODcxIEMxOTcuNzM1NDEsMTYuNTQwOTU4NyAyMjIuMDM1NDEsMzAuNTE2OTU4NyAyNDYuMjA5NDEsNDQuNzAzOTU4NyBDMjUzLjY5MTQxLDQ5LjA5NDk1ODcgMjU2Ljg5MzQxLDU2LjIxOTk1ODcgMjU1Ljc4NjQxLDY0Ljc5ODk1ODcgQzI1NC42NjE0MSw3My41MTA5NTg3IDI0OS4zOTU0MSw3OS4wOTI5NTg3IDI0MS4xNjY0MSw4MS45NTM5NTg3IEMyMzQuNTg5NDEsODMuNTkxOTU4NyAyMjguNjc4NDEsODIuMDYxOTU4NyAyMjIuOTM4NDEsNzguNjM1OTU4NyBDMjEzLjQ0NzQxLDcyLjk3MDk1ODcgMjAzLjc5MDQxLDY3LjU4Mjk1ODcgMTk0LjIwMzQxLDYyLjA3ODk1ODciIGZpbGw9IiMxMDlENTgiPjwvcGF0aD4KICAgICAgICA8cGF0aCBkPSJNNzEuNzUxODEwMiw1Ni41NjI4NTg3IEM2My4xMzA4MTAyLDYxLjQ2MDg1ODcgNTQuNTA0ODEwMiw2Ni4zNDk4NTg3IDQ1Ljg5MjgxMDIsNzEuMjYyODU4NyBDNDAuODU0ODEwMiw3NC4xMzY4NTg3IDM1Ljg3MjgxMDIsNzcuMTA4ODU4NyAzMC44MDg4MTAyLDc5LjkzNDg1ODcgQzIwLjYwNTgxMDIsODUuNjI5ODU4NyA4LjQ4MzgxMDE3LDgyLjI5MTg1ODcgMi42OTg4MTAxNyw3Mi4yNjA4NTg3IEMtMi44MjIxODk4Myw2Mi42ODg4NTg3IDAuMzUwODEwMTcsNTAuMjc4ODU4NyAxMC4xNzY4MTAyLDQ0LjU0Mjg1ODcgQzM0LjIwMTgxMDIsMzAuNTE5ODU4NyA1OC4yODg4MTAyLDE2LjU5ODg1ODcgODIuNDYyODEwMiwyLjgzMzg1ODcxIEM4OS44NzY4MTAyLC0xLjM4ODE0MTI5IDk3LjU2ODgxMDIsLTAuODU3MTQxMjg2IDEwNC40MjQ4MSw0LjE4OTg1ODcxIEMxMTEuNjYwODEsOS41MTY4NTg3MSAxMTQuMDI5ODEsMTcuMDEyODU4NyAxMTIuNDA0ODEsMjUuODAwODU4NyBDMTExLjM5NjgxLDI3LjkyNjg1ODcgMTEwLjc5NDgxLDMwLjQxOTg1ODcgMTA5LjI4NTgxLDMyLjA5NDg1ODcgQzEwNi44MzA4MSwzNC44MTk4NTg3IDEwNC4wNDA4MSwzNy40Mjg4NTg3IDEwMC45MzQ4MSwzOS4zNDQ4NTg3IEM5MS4zMjI4MTAyLDQ1LjI3MTg1ODcgODEuNDk1ODEwMiw1MC44NDk4NTg3IDcxLjc1MTgxMDIsNTYuNTYyODU4NyIgZmlsbD0iI0U5NDQzNiI+PC9wYXRoPgogICAgICAgIDxwYXRoIGQ9Ik02MS44NjcwMTAyLDYyLjA1Njk1ODcgQzcwLjQyMDAxMDIsNjcuMDcyOTU4NyA3OC45NjcwMTAyLDcyLjA5OTk1ODcgODcuNTI4MDEwMiw3Ny4xMDE5NTg3IEM5Mi41MzUwMTAyLDgwLjAyNzk1ODcgOTcuNjAwMDEwMiw4Mi44NTY5NTg3IDEwMi41NzkwMSw4NS44Mjc5NTg3IEMxMTIuNjEzMDEsOTEuODE3OTU4NyAxMTUuNzg0MDEsMTAzLjk4Mzk1OSAxMDkuOTg5MDEsMTE0LjAwODk1OSBDMTA0LjQ1OTAxLDEyMy41NzY5NTkgOTIuMTI2MDEwMiwxMjcuMDM0OTU5IDgyLjI0NTAxMDIsMTIxLjM5MTk1OSBDNTguMDg4MDEwMiwxMDcuNTk2OTU5IDMzLjk4OTAxMDIsOTMuNjk4OTU4NyA5Ljk4MTAxMDE3LDc5LjY0NTk1ODcgQzIuNjE4MDEwMTcsNzUuMzM1OTU4NyAtMC43Njc5ODk4Myw2OC40MDg5NTg3IDAuMTc1MDEwMTcsNTkuOTQ3OTU4NyBDMS4xNzAwMTAxNyw1MS4wMTY5NTg3IDYuNDc3MDEwMTcsNDUuMjE3OTU4NyAxNC45MDAwMTAyLDQyLjIzMDk1ODcgQzE3LjI0NTAxMDIsNDIuMDQxOTU4NyAxOS43MDUwMTAyLDQxLjMxNTk1ODcgMjEuOTExMDEwMiw0MS43ODU5NTg3IEMyNS40OTgwMTAyLDQyLjU0OTk1ODcgMjkuMTUzMDEwMiw0My42NjA5NTg3IDMyLjM2NTAxMDIsNDUuMzkyOTU4NyBDNDIuMzA0MDEwMiw1MC43NTI5NTg3IDUyLjA0ODAxMDIsNTYuNDc0OTU4NyA2MS44NjcwMTAyLDYyLjA1Njk1ODciIGZpbGw9IiM0Mzg1RjMiPjwvcGF0aD4KICAgIDwvZz4KPC9zdmc+)](https://medium.com/opensource-contributors) [OpenSource Mentoring](https://medium.com/opensource-contributors) leader at GDG songdo
  - Help 70+ developers to open first PR on open-source they want (Next.js, react, angular, flutter, spring, k8s, ..)
  - [Make 100+ PRs together](https://chip-bream-9d5.notion.site/PR-459f46f1dbe048ffbb7ef04fd9dcc6a6), 30+ PRs are merged now :)

## My Interests
- Large/Burst traffic handling and distributed system architecture
- Open Source Contribution
- Documentation, visualization, communication
- Band (🎷Saxophone player)

## Contact
- injae.kim.dev@gmail.com
  - ☕ I like coffee chat! feel free to mail me when you want 🙂
- [About me](https://injae-kim.github.io/experience/2020/09/06/sheco-startup.html) blog
- [Linked.in](https://www.linkedin.com/in/injae-kim-dev)
- [![GDG Songdo](https://img.shields.io/badge/Google_Developer_Groups-Songdo-blue.svg?logo=data:image/svg%2bxml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz4KPHN2ZyB3aWR0aD0iMjU2cHgiIGhlaWdodD0iMTI1cHgiIHZpZXdCb3g9IjAgMCAyNTYgMTI1IiB2ZXJzaW9uPSIxLjEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHByZXNlcnZlQXNwZWN0UmF0aW89InhNaWRZTWlkIj4KICAgIDxnPgogICAgICAgIDxwYXRoIGQ9Ik0xODQuMzE0ODEsNjcuNzA0NDU4NyBDMTk3Ljc4MzgxLDU5Ljk2ODQ1ODcgMjExLjIxNjgxLDUyLjE2OTQ1ODcgMjI0LjczMTgxLDQ0LjUxMzQ1ODcgQzIzNy41NTk4MSwzNy4yNDU0NTg3IDI1Mi42NTI4MSw0My45NDg0NTg3IDI1NS41NjA4MSw1OC4wOTI0NTg3IEMyNTcuMjQzODEsNjYuMjc0NDU4NyAyNTMuNTkwODEsNzUuMTEzNDU4NyAyNDYuMjAzODEsNzkuNDE4NDU4NyBDMjIxLjk4NTgxLDkzLjUzMTQ1ODcgMTk3LjczMjgxLDEwNy41ODg0NTkgMTczLjM1ODgxLDEyMS40MzA0NTkgQzE2NS44MTQ4MSwxMjUuNzE0NDU5IDE1OC4wNDM4MSwxMjQuOTI2NDU5IDE1MS4xNjg4MSwxMTkuNjc2NDU5IEMxNDQuMTg0ODEsMTE0LjM0NjQ1OSAxNDEuOTgzODEsMTA2Ljk5NDQ1OSAxNDMuNjIxODEsOTguNDM3NDU4NyBDMTQ1LjQ5MTgxLDkxLjkyMzQ1ODcgMTQ5Ljc3MTgxLDg3LjU2ODQ1ODcgMTU1LjYwODgxLDg0LjMxMDQ1ODcgQzE2NS4yNTk4MSw3OC45MjQ0NTg3IDE3NC43NTM4MSw3My4yNTQ0NTg3IDE4NC4zMTQ4MSw2Ny43MDQ0NTg3IiBmaWxsPSIjRkFCQzA1Ij48L3BhdGg+CiAgICAgICAgPHBhdGggZD0iTTE5NC4yMDM0MSw2Mi4wNzg5NTg3IEMxODAuNzY4NDEsNTQuMjgyOTU4NyAxNjcuMjk5NDEsNDYuNTQ3OTU4NyAxNTMuOTExNDEsMzguNjcyOTU4NyBDMTQxLjIwMjQxLDMxLjE5Njk1ODcgMTM5LjQ2MjQxLDE0Ljc3NDk1ODcgMTUwLjI1NjQxLDUuMTgyOTU4NzEgQzE1Ni41MDA0MSwtMC4zNjQwNDEyODYgMTY1Ljk4MTQxLC0xLjYyMTA0MTI5IDE3My40MDM0MSwyLjYyMzk1ODcxIEMxOTcuNzM1NDEsMTYuNTQwOTU4NyAyMjIuMDM1NDEsMzAuNTE2OTU4NyAyNDYuMjA5NDEsNDQuNzAzOTU4NyBDMjUzLjY5MTQxLDQ5LjA5NDk1ODcgMjU2Ljg5MzQxLDU2LjIxOTk1ODcgMjU1Ljc4NjQxLDY0Ljc5ODk1ODcgQzI1NC42NjE0MSw3My41MTA5NTg3IDI0OS4zOTU0MSw3OS4wOTI5NTg3IDI0MS4xNjY0MSw4MS45NTM5NTg3IEMyMzQuNTg5NDEsODMuNTkxOTU4NyAyMjguNjc4NDEsODIuMDYxOTU4NyAyMjIuOTM4NDEsNzguNjM1OTU4NyBDMjEzLjQ0NzQxLDcyLjk3MDk1ODcgMjAzLjc5MDQxLDY3LjU4Mjk1ODcgMTk0LjIwMzQxLDYyLjA3ODk1ODciIGZpbGw9IiMxMDlENTgiPjwvcGF0aD4KICAgICAgICA8cGF0aCBkPSJNNzEuNzUxODEwMiw1Ni41NjI4NTg3IEM2My4xMzA4MTAyLDYxLjQ2MDg1ODcgNTQuNTA0ODEwMiw2Ni4zNDk4NTg3IDQ1Ljg5MjgxMDIsNzEuMjYyODU4NyBDNDAuODU0ODEwMiw3NC4xMzY4NTg3IDM1Ljg3MjgxMDIsNzcuMTA4ODU4NyAzMC44MDg4MTAyLDc5LjkzNDg1ODcgQzIwLjYwNTgxMDIsODUuNjI5ODU4NyA4LjQ4MzgxMDE3LDgyLjI5MTg1ODcgMi42OTg4MTAxNyw3Mi4yNjA4NTg3IEMtMi44MjIxODk4Myw2Mi42ODg4NTg3IDAuMzUwODEwMTcsNTAuMjc4ODU4NyAxMC4xNzY4MTAyLDQ0LjU0Mjg1ODcgQzM0LjIwMTgxMDIsMzAuNTE5ODU4NyA1OC4yODg4MTAyLDE2LjU5ODg1ODcgODIuNDYyODEwMiwyLjgzMzg1ODcxIEM4OS44NzY4MTAyLC0xLjM4ODE0MTI5IDk3LjU2ODgxMDIsLTAuODU3MTQxMjg2IDEwNC40MjQ4MSw0LjE4OTg1ODcxIEMxMTEuNjYwODEsOS41MTY4NTg3MSAxMTQuMDI5ODEsMTcuMDEyODU4NyAxMTIuNDA0ODEsMjUuODAwODU4NyBDMTExLjM5NjgxLDI3LjkyNjg1ODcgMTEwLjc5NDgxLDMwLjQxOTg1ODcgMTA5LjI4NTgxLDMyLjA5NDg1ODcgQzEwNi44MzA4MSwzNC44MTk4NTg3IDEwNC4wNDA4MSwzNy40Mjg4NTg3IDEwMC45MzQ4MSwzOS4zNDQ4NTg3IEM5MS4zMjI4MTAyLDQ1LjI3MTg1ODcgODEuNDk1ODEwMiw1MC44NDk4NTg3IDcxLjc1MTgxMDIsNTYuNTYyODU4NyIgZmlsbD0iI0U5NDQzNiI+PC9wYXRoPgogICAgICAgIDxwYXRoIGQ9Ik02MS44NjcwMTAyLDYyLjA1Njk1ODcgQzcwLjQyMDAxMDIsNjcuMDcyOTU4NyA3OC45NjcwMTAyLDcyLjA5OTk1ODcgODcuNTI4MDEwMiw3Ny4xMDE5NTg3IEM5Mi41MzUwMTAyLDgwLjAyNzk1ODcgOTcuNjAwMDEwMiw4Mi44NTY5NTg3IDEwMi41NzkwMSw4NS44Mjc5NTg3IEMxMTIuNjEzMDEsOTEuODE3OTU4NyAxMTUuNzg0MDEsMTAzLjk4Mzk1OSAxMDkuOTg5MDEsMTE0LjAwODk1OSBDMTA0LjQ1OTAxLDEyMy41NzY5NTkgOTIuMTI2MDEwMiwxMjcuMDM0OTU5IDgyLjI0NTAxMDIsMTIxLjM5MTk1OSBDNTguMDg4MDEwMiwxMDcuNTk2OTU5IDMzLjk4OTAxMDIsOTMuNjk4OTU4NyA5Ljk4MTAxMDE3LDc5LjY0NTk1ODcgQzIuNjE4MDEwMTcsNzUuMzM1OTU4NyAtMC43Njc5ODk4Myw2OC40MDg5NTg3IDAuMTc1MDEwMTcsNTkuOTQ3OTU4NyBDMS4xNzAwMTAxNyw1MS4wMTY5NTg3IDYuNDc3MDEwMTcsNDUuMjE3OTU4NyAxNC45MDAwMTAyLDQyLjIzMDk1ODcgQzE3LjI0NTAxMDIsNDIuMDQxOTU4NyAxOS43MDUwMTAyLDQxLjMxNTk1ODcgMjEuOTExMDEwMiw0MS43ODU5NTg3IEMyNS40OTgwMTAyLDQyLjU0OTk1ODcgMjkuMTUzMDEwMiw0My42NjA5NTg3IDMyLjM2NTAxMDIsNDUuMzkyOTU4NyBDNDIuMzA0MDEwMiw1MC43NTI5NTg3IDUyLjA0ODAxMDIsNTYuNDc0OTU4NyA2MS44NjcwMTAyLDYyLjA1Njk1ODciIGZpbGw9IiM0Mzg1RjMiPjwvcGF0aD4KICAgIDwvZz4KPC9zdmc+)](https://danielkim88.notion.site/danielkim88/GDG-Incheon-Songdo-with-Flutter-Songdo-3d00a1dbf75949cdaf8ce12665c75750) organizer
