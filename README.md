

# Основы Linux
### Создание директории devops_test в домашнем каталоге:
```bash
nurzhan@nrzank:~$ mkdir ~/devops_test
nurzhan@nrzank:~$ ls -l
total 4
drwxr-xr-x 2 nurzhan nurzhan 4096 Sep 19 16:12 devops_test
```
### Создание пустого файла readme.txt в созданной директории:
nurzhan@nrzank:~$ ls -l
total 4
drwxr-xr-x 2 nurzhan nurzhan 4096 Sep 19 16:12 devops_test
nurzhan@nrzank:~$ cd devops_test/
nurzhan@nrzank:~/devops_test$ touch readme.txt

### Показ текущего пути в терминале:
nurzhan@nrzank:~/devops_test$ pwd
/home/nurzhan/devops_test




# Основы Git
### Создание нового локального репозитория:
nurzhan@nrzank:~/devops_test$ git init

### Создание файла test.txt и добавление в него текста:
nurzhan@nrzank:~/devops_test$ echo "Hello DevOps" > test.txt

### Добавление изменений и коммит с сообщением:
nurzhan@nrzank:~/devops_test$ git add test.txt
nurzhan@nrzank:~/devops_test$ git commit -m 'initial commit'
initial commit
 1 file changed, 1 insertion(+)
 create mode 100644 test.txt

### Показ истории коммитов:
nurzhan@nrzank:~/devops_test$ git log
commit e228cdc441529914e553072514f6d6985d18c0f6 (HEAD -> master)
Author: nrzank <asapnrz@gmail.com>
Date:   Thu Sep 19 16:17:01 2024 +0500

    initial commit

    
# Основы сетевых технологий
### Что такое IP-адрес и для чего он используется?
IP-адрес — это уникальный числовой идентификатор устройства в сети, который используется для его идентификации и обеспечения связи между устройствами через интернет или локальные сети. IP-адрес позволяет передавать данные между устройствами.

### Основные отличия между протоколами TCP и UDP:
- **TCP (Transmission Control Protocol)**: Протокол с установлением соединения, обеспечивающий надежную передачу данных. Гарантирует доставку пакетов в том порядке, в котором они были отправлены. Используется для приложений, где важна точность и целостность данных (например, веб-серверы, почтовые серверы).
- **UDP (User Datagram Protocol)**: Протокол без установления соединения, не гарантирует доставку данных и их порядок. Используется для приложений, где важна скорость передачи (например, стриминг, онлайн-игры).



### Скрипт на Python:
nurzhan@nrzank:~/devops_test$ python3
Python 3.10.12 (main, Jun 11 2023, 05:26:28) [GCC 11.4.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> for i in range(1, 11):
...     print(i)
...
1
2
3
4
5
6
7
8
9
10
>>>

# Логическое мышление
### Задача с лампочками и выключателями:
1. Включить первый выключатель и оставить его включённым на некоторое время.
2. Затем выключить первый и включить второй.
3. Пройти в комнату с лампочками:
   - Лампочка, которая горячая и выключена — управляется первым выключателем.
   - Лампочка, которая включена — управляется вторым выключателем.
   - Лампочка, которая выключена и холодная — управляется третьим выключателем.
