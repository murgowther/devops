# Задание 1:
Dockerfile\
![alt text](imgs/1.png)\
Build\
![alt text](imgs/2.png)\
![alt text](imgs/3.png)\
Result\
![alt text](imgs/4.png)\
# Задание 2:\
![alt text](imgs/5.png)\
![alt text](imgs/6.png)\
# Задание 3:\
Переименую контейнер в "custom-nginx-t2"\
![alt text](imgs/7.png)\
Контейнер остановился, потому как мы подключились к его стандартному выводу и отправили сигнал SIGINT на выключение\
![alt text](imgs/8.png)\
![alt text](imgs/9.png)\
![alt text](imgs/10.png)\
Данное поведение вызвано тем, что порт с которого раннее происходило перенаправление изменился, поэтому port-forwarding ничего не выводит, ведь при запуске мы указывали перенаправление с 80 порта на 8080\
Удалим его не выключая\
![alt text](imgs/11.png)\
# Задание 4:\
![alt text](imgs/12.png)\
![alt text](imgs/13.png)\ 
# Задание 5:\
![alt text](imgs/14.png)\
![alt text](imgs/15.png)\
![alt text](imgs/16.png)\
Или обновим docker-compose до версии 2\
![alt text](imgs/17.png)\
Но тогда используется только предпочтительный для v2 docker.yaml\
![alt text](imgs/18.png)
 
 
 
