# Aider Roadmap

| Цель | Что нужно для изучения и Задания | Как поймем что цель достигнута? | Примерная дата окончания изучения 
|-|-|-|-
| Linux | Пройти курс https://www.youtube.com/watch?list=PLg5SS_4L6LYuE4z-3BgLYGkZrs-cF4Tep и сделать все задания https://github.com/eabykov/devops-linux | Может устанавливать программы, знает основные команды и может их применять, что такое ядро linux, знает основные папки есть в `/`, вопросы https://github.com/bregman-arie/devops-exercises/tree/master/topics/linux | 01.03.2023
| Linux скрипты | Сделать скрипты для всех заданий https://github.com/eabykov/devops-linux | Умеет задавать переменные и использовать их, может применять условный оператор IF и использовать CASE, умеет использовать циклы, вопросы https://github.com/bregman-arie/devops-exercises/tree/master/topics/shell | 01.03.2023
| Git | Пройти курс https://www.youtube.com/watch?list=PLg5SS_4L6LYstwxTEOU05E0URTHnbtA0l до 15 урока и создать свой репозиторий на github с несколькими ветками и тегами | Знает что такое commit и как его делать, умеет делать branch и tag, знает что такое merge и как исправлять конфликты, знает как откатиться на предидущий commit, как склонировать репозиторий локально и как загрузить свои изменения в github, вопросы https://github.com/bregman-arie/devops-exercises/tree/master/topics/git | 01.03.2023
| Docker | Пройти курс https://github.com/eabykov/devops-docker и посмотреть урок https://www.youtube.com/watch?v=uZQtRyF6Eg | Понимает зачем нужен docker, умеет создавать свой образ и пушить его в dockerhub, умеет запускать несколько образов вместе используя compose, вопросы https://habr.com/ru/company/southbridge/blog/528206/ | 15.03.2023
| CI/CD | В курсе https://www.youtube.com/watch?list=PLg5SS_4L6LYstwxTEOU05E0URTHnbtA0l 15й и 16й уроки и https://youtu.be/tE3u1LquFcg на скорости 1.25 | Понимает зачем нужен ci/cd, как собрать docker образ через ci/cd и запушить его в registry, из каких шагов состоит идеальный пайплайн, вопросы https://github.com/bregman-arie/devops-exercises/tree/master/topics/cicd | 01.04.2023
| Ansible | Пройти курс https://www.youtube.com/watch?list=PLg5SS_4L6LYufspdPupdynbMQTBnZd31N до 20 | Понимает зачем нужен Ansible, что такое идемпотентность, что такое playbook, умеет писать свои роли, вопросы https://github.com/bregman-arie/devops-exercises/tree/master/topics/ansible | 01.05.2023
| Terraform | Пройти курс https://www.youtube.com/watch?list=PLg5SS_4L6LYujWDTYb-Zbofdl44Jxb2l8 до 17 | Понимает зачем нужен Terraform, знает как создавать ресурсы (например виртуальную машину), где хранится состояние (информация) о том что сделал terraform, вопросы https://habr.com/ru/company/southbridge/blog/528206/ | 01.05.2023
| Сети, сетевые технологии | Прочесть статью https://habr.com/ru/post/326574/ , https://ru.wikipedia.org/wiki/Маска_подсети и https://habr.com/ru/post/711578/ | Понимает что такое 'пакет', знает уровни TCP/IP, что такое DNS, что такое HTTP протокол и REST, что такое IP и маска подсети, как на linux посмотреть сетевые интерфейсы, сниффинг трафика, что такое Nginx (как выглядит конфиг) и балансировка, вопросы https://github.com/bregman-arie/devops-exercises#network | 01.05.2023
| Kubernetes | Пройти курс https://www.youtube.com/watch?list=PLg5SS_4L6LYvN1RqaVesof8KAf-02fJSi и https://github.com/eabykov/kubernetes запускать локально через Docker Desktop и поставить linkerd | Понимает зачем нужен Kubernetes, как устанавливать приложения через helm, вопросы https://github.com/bregman-arie/devops-exercises/tree/master/topics/kubernetes | 01.06.2023
| Мониторинг | Prometheus + Grafana + metric-server, ELK стек (логи), Трейсинг | Понимает как создавать алерты (оповещения), может настроить мониторинг Kubernetes и приложений в нем, вопросы https://github.com/bregman-arie/devops-exercises#monitoring | 01.06.2023
