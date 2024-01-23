# Домашнее задание к занятию «ELK» - Михалёв Сергей

---

### Задание 1. Elasticsearch 

Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный. 

*Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name*.

**Результат:**

- Скриншот с командой и результатом ее выполнения
  
  <img src="images/Task_1.png" alt="Task_1" width="500" height="auto">

---

### Задание 2. Kibana

Установите и запустите Kibana.

*Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty*.

**Результат:**

- Скриншот интерфейса Kibana
  
  <img src="images/Task_2.png" alt="Task_2" width="500" height="auto">

---

### Задание 3. Logstash

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.*

**Результат:**

- Скриншот настройки Logstash
  
  <img src="images/Task_3_1.png" alt="Task_3_1" width="500" height="auto">

- Скриншот интерфейса Kibana
  
  <img src="images/Task_3.png" alt="Task_3" width="750" height="auto">

---

### Задание 4. Filebeat. 

Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.*

**Результат:**

- Скриншот настройки Logstash
  
  <img src="images/Task_4_1.png" alt="Task_4_1" width="500" height="auto">

- Скриншот интерфейса Kibana
  
  <img src="images/Task_4.png" alt="Task_4" width="750" height="auto">


## Дополнительные задания (со звёздочкой*)
Эти задания дополнительные, то есть не обязательные к выполнению, и никак не повлияют на получение вами зачёта по этому домашнему заданию. Вы можете их выполнить, если хотите глубже шире разобраться в материале.


