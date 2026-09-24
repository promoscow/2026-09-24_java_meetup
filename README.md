## Материалы к докладу "Дрессируем потоки. Добиваемся дешёвой конкурентности на JVM"

### Ссылки доклада:

#### Давайте знакомиться:

Профиль на Хабре:
https://habr.com/ru/users/xpendence/

Канал в Telegram:
https://t.me/xpendence

Личный сайт:
https://chernyshoff.ru/

#### Внешние ресурсы:

The State of Spring 2024:
https://images.sw.broadcom.com/Web/CAInc2/%7B0084ba0d-6d1e-4c87-a4f2-106ec62fb83a%7D_Tanzu_State_of_Spring_2024.pdf

The C10K problem:
https://www.kegel.com/c10k.html

Melvin Conway:
https://en.wikipedia.org/wiki/Melvin_Conway

JEP 444: Virtual Threads:
https://openjdk.org/jeps/444

JEP 491: Synchronize Virtual Threads without Pinning
https://openjdk.org/jeps/491

#### Тестовый проект:
Client:
https://github.com/promoscow/coroutines-concept-client

IO:
https://github.com/promoscow/coroutines-concept-io

Server Web (Tomcat):
https://github.com/promoscow/coroutines-concept-server-web

Server WebFlux (Netty):
https://github.com/promoscow/coroutines-concept-server-webflux

### Grafana snapshots:

#### Spring MVC

Server JVM: https://snapshots.raintank.io/dashboard/snapshot/ihGrZ1AYdTagGGpROKfDB9vQVIQzn6jc

IO JVM: https://snapshots.raintank.io/dashboard/snapshot/kIXE79NeToGFNuUFHeNBriT0UaYgkQsw

Server threads: https://snapshots.raintank.io/dashboard/snapshot/Mi225WOqkiVrOjCE872eLbTEk1iIJdur

#### Spring WebFlux

Server JVM: https://snapshots.raintank.io/dashboard/snapshot/GzW8TUAOEhda6n2GeR9BWkU5HKgOxkIy

IO JVM: https://snapshots.raintank.io/dashboard/snapshot/0KUE8zPnLoofg0XOJ0pYWvigu7h9Lp8p

Server threads: https://snapshots.raintank.io/dashboard/snapshot/ykrpDaHlldJOWsRq8P9WNnnxuQY3hpe8

#### Spring WebFlux + blocking I/O

Server JVM: https://snapshots.raintank.io/dashboard/snapshot/ljux6wfjUnGuygasrTbrDGhzLIEwj5ln

Server threads: https://snapshots.raintank.io/dashboard/snapshot/wElTFs3DJFSvySP6g1Bf2UYoevaPl93w

#### Spring MVC + Virtual Threads

Server JVM: https://snapshots.raintank.io/dashboard/snapshot/mysdujhLcpHI4n8dpOWdXaxBLGRAbJF0

IO JVM: https://snapshots.raintank.io/dashboard/snapshot/m9flNaR6IZ4qvzD8VtaAyvebAL7k83Ja

Server threads: https://snapshots.raintank.io/dashboard/snapshot/WpaFiIdntM52arOWa96GC6DNslrYEMXd

#### Spring WebFlux + Coroutines

Server JVM: https://snapshots.raintank.io/dashboard/snapshot/r0QNhfXyjk0xBzGllzVlQWEaazvAZijG

IO JVM: https://snapshots.raintank.io/dashboard/snapshot/jUt3PT3OxxNbSBnP7pirH0gsAsbfLevi

Server threads: https://snapshots.raintank.io/dashboard/snapshot/SnPrrbSDmoFKpxPZB8loVGx4F5Zy4MKd
