**Описание проекта**

Вы работаете в стартапе, который продаёт продукты питания. Нужно разобраться, как ведут себя пользователи вашего мобильного приложения. Дизайнеры захотели поменять шрифты во всём приложении. Договорились принять решение по результатам A/A/B-теста. Пользователей разбили на 3 группы: 2 контрольные со старыми шрифтами и одну экспериментальную — с новыми. Необходимо выяснить, какой шрифт лучше.     

Для выполнения данной задачи необходимо выполнить следующее:
*  провести предобработку данных; 
* изучить и проверить данные;
* сделать воронку событийу, чтобы узнать, как пользователи доходят до покупки;
* провести и изучить результаты А/А/В теста.

**Описание данных**     
Каждая запись в логе — это действие пользователя, или событие.    
`EventName` — название события;     
`DeviceIDHash` — уникальный идентификатор пользователя;       
`EventTimestamp` — время события;      
`ExpId` — номер эксперимента: 246 и 247 — контрольные группы, а 248 — экспериментальная.

**Выполненные действия**    
В процессе выполнения и анализа А/А/В теста были выполнены следующие действия:

- удалены старые данные в логе;
- построена воронка событий;
- проведен z- test.

**Основной вывод** - изменение шрифта не привело к каким-либо статически значимым изменениям в поведении пользователей. Введение фичи не оправдало себя.

Также, к важным наблюдениям можно отнести следующие:

- до последнего этапа показ экрана об успешной оплате дошли 48% от общего числа имеющихся пользователей, а именно - 3539;
- больше всего пользователей были утеряны после этапа показ главного экрана: 2893 или 39% от общего количества пользователей не дошли до следующего этапа показ экрана предложений.

**Статус проекта**    
Проект завершен.
