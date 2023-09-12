# Linux


<details> 
<summary>  Установка системы Linux на виртуалку. 
</summary>

* Программы необходимые для установки

1. ### VirtualBox - [Скачать](https://www.virtualbox.org/wiki/Downloads) 
###

2. ### Образ системы Linux [Скачать](https://ubuntu.com/download/desktop) ![Скрин](Dop_Materiali/Linux-Obrz.jpg)
###
3. ### Запускаем программу VirtualBox, далее нажимаем создать (зелённая надпись сверху), после этого нажимаем режим эксперта. ![Скрин](Dop_Materiali/Linux_ust_1.jpg)
###
4. ### Настраиваем имя образа, путь где будет установлен и храниться и сам образ который мы скачали, ну и систему которую хотим установить.![Скрин](Dop_Materiali/Linux_ust_2.jpg)
###
5. ### Далее в следущей вкладке, настраиваем имя пользователя на вход в систему. ![Скрин](Dop_Materiali/Linux_ust_3.jpg) 
###
6. ### Вследующей вкладке, выделяем ресурсы под систему (это не постоянное выделение, а в момент, когда будем запускать и рабоать в системе)![Скрин](Dop_Materiali/Linux_ust_4.jpg)
###
7. ### В следующей вкладке (Жёский диск, просто выделяем места под систему, примерно если не жало выделить 50гигов) Затем нажать готов, пойдёт установка системы.
8. ### После установки, в программе VirtualBox уже нажимаем запуск системы.![Скрин](Dop_Materiali/Linux_ust_5.jpg)
###
9. ### После того как поработали в системе, закрываем на крестик, и выбираем выключение по середине.![Скрин](Dop_Materiali/Linux_ust_6.jpg)

</details>

<details> 
<summary>  Непосредственная работа в системе Linux.
</summary>

* Вся работа в системе Linux практически осуществляеться через терминал.
* Запустив терминал, зачастую многие команды требуют пароль root или по другому администратора.
    * Для этого в терминале необходимо прописать комаду su, далее запросит пароль администратора, его ввести (пароль не видно что вводим), после этого покажет что мы уже не пользователь а администратор (root)
    ![Скрин](Dop_Materiali/Linux_ust_7.jpg)
* Запуск через терминал своего рода командора(работа с файлами.). В терминале прописываем команду mc ![Скрин](Dop_Materiali/Linux_ust_8.jpg)
* Расшифровка
    * segars - имя пользователя
    * Linux-Znatia - имя компа
    * :~$ каталог в котром мы находимся.
    * ![Скрин](Dop_Materiali/Linux_osn_1.jpg)

</details>

<details> 
<summary>  Команды в терминале. 
</summary>

* Для любой команды, можно запросить подсказку, если мы забыли или не знаем что она может и как её применить.
    * К примеру ls --help получим описания, для чего и что мы можем сделать
    * или man ls тоже своего рода справка по команде
* su - запуск режима администратора
* mc - запуск тотол командора
* Ctrl+L - очистка терминала
* Ctrl+О - свернуть тотол командер (mc)
* Ctrl+Shift+(+) - увеличевает текст в терминале.
* команда cd / (имя каталога куда хотим попасть)
* команда cd - выйдем в корней каталог
* команда exit выйдем из программы или из режима администратора (root)
* команда ip a - покажет адрес айпи
* команда ls -al покажет все файлы в каталоге
* команда cd /dev - устройства
* команда cd /proc - процессы состояния системы ОС
* команда cd /sys - информация о системе
* команда cd /run - временные файлы
* команда pwd - выдаст нам полный путь каталога в котором мы находимся, затем для удобства его скопировать и применить если потребуеться.
* Продолжить с 30 минуты

</details>




