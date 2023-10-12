# SymphoStaff
CRM для автоматизации бизнес-процессов камерных и симфонических оркестров

(PHP, MySQL, Vue3 + Quasar)
### Структура и основные возможности:


- автоматизация кадрового делопроизводства
    
    [Backend](https://github.com/symphograph/SymStaffApi) [Frontend](https://github.com/symphograph/symstaff)
    - Сохранение информации о сотрудниках

      ![721817410.png](img%2F721817410.png)

    - генерация рабочего графика

        ![721818098.png](img%2F721818098.png)
        
    - интерфейс сохранения данных о посещаемости

       ![721816078.png](img%2F721816078.png) 

    - генерация табели рабочего времени

        ![tabel.png](img%2Ftabel.png)
    
    - формирование метрик

        ![metrics.png](img%2Fmetrics.png)
    - генерация документов
    - расчет отпусков
- сайт организации
  ![site.png](img%2Fsite.png)
  [Backend](https://github.com/symphograph/SymStaffApi) [Frontend](https://github.com/symphograph/symstaff)
    
  - админ-панель сайта позволяет редактировать
      - состав оркестра на момент выбранной даты
        ![staff.png](img%2Fstaff.png)
      - новостную ленту
        ![entry.png](img%2Fentry.png)
      - анонсы концертов
        ![announce.png](img%2Fannounce.png)
      - схемы концертных залов
        ![hallEditor.png](img%2FhallEditor.png)
      - записи концертов
      - фотоальбомы
      - информацию об организации
      - документы организации
  - пользователи сайта могут
      - просматривать контент
      - бронировать билеты
      - оплачивать покупку билетов
      - отправлять сообщения


### Зависимости:
- [Symphograph/authServer](https://github.com/symphograph/authServer)

  Обеспечивает взаимодействие между сервисами


- [Symphograph/Bicycle](https://github.com/symphograph/bicycle)

  Библиотека с обширным набором классов для упрощения разработки

