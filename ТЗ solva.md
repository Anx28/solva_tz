[\[Ссылка на гугл док\]](https://docs.google.com/document/d/1xDFeSP6kBv10O6c2GWdOIM8vTK48EU-pcLb3me0vbsQ/edit?usp=sharing) 

# Linux

● Создание директории devops\_test в домашнем каталоге.   
`mkdir ~/devops_test`  
● Создание пустого файла readme.txt в созданной директории.   
`touch ~/devops_test/readme.txt `  
● Показать текущий путь в терминале.   
`pwd`

![image](https://github.com/user-attachments/assets/16acd82a-1438-4320-bd5e-e788f1e7f7b8)


#  GIt

Задание: Выполните следующие действия с использованием Git:  
● Создайте новый локальный репозиторий.  
● Создайте файл test.txt, добавьте в него текст “Hello DevOps”.  
● Закоммитьте изменения с сообщением “Initial commit”.  
● Покажите историю коммитов

```  
git init  
echo 'Hello Devops' > test.txt  
git add test.txt  
git commit -m 'Initial commit'
git log  
```  
![image](https://github.com/user-attachments/assets/635d7d26-28c1-495c-bab8-f559f8673c92)


# Сети

\* ip \-  уникальный идентификатор устройства

● Назовите основные отличия между протоколами TCP и UDP.  \-   
tcp \- гарантированная доставка пакетов  
UDP \- нет гарантированной доставка, быстрее

Напишите скрипт на Bash или Python, который выводит числа от 1 до 10
```
#!/bin/bash  
echo {1..10}
```

Python
```
for x in range(1, 10 + 1):  
   print(x)
```

# Логическая задача

Включу два выключателя (1,2), через некоторое время отключу один (2).   
Итог.  
Включенная лампа \- переключатель один  
Теплая лампа \- переключатель два  
Холодная лампа \- переключатель три
