Задачата е да разгледа как работи този Docker Compose - по специфично как Logstash си взима данните:

https://github.com/docker/awesome-compose/tree/master/elasticsearch-logstash-kibana
и в този Compose да добави Angular аппликейшън хостнат с NGINX:

Примерно:
https://github.com/bbachi/angular-nginx-docker

Бонус точки:

Кратко показване/обяснение как търсим и филтрираме логовете в Кибана - може и със сампъл данните
Когато nginx работи като reverse proxy, зад него може да има повече програми: искаме да можем да отворим еластик на localhost/elastic и Angular App-a на localhost/angular
Nginx има access_log и error_log, които се пишат във файлове -> чрез Docker Compose - да се направи така че логовете на Nginx се четат от LogStash
 
awesome-compose/elasticsearch-logstash-kibana at master · docker/awesome-compose

За въпроси използвай github Issues.

Текста на задачата трябва да се преведе на английски.
