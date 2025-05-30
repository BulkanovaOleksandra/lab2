# lab2-lab3
flex css, grid css, no-flex-grid css

**Лабораторна робота №2 **

Верстка веб-сторінок за допомогою CSS 
А) Flexbox CSS: 
Переваги: гнучкість при управлінні елементами (особливо для вирівнювання та розподілу простору). 
Простота при роботі з вертикальними та горизонтальними вирівнюваннями. 
Легко адаптується до різних розмірів екрану за допомогою медіа-запитів. 
Недоліки: менше контролю над розміщенням елементів по сітці в порівнянні з Grid. 
Не завжди зручний для розкладки складних елементів на багатьох рівнях. 

Б) Grid CSS: 
Переваги: кращий контроль над складними макетами і розміщенням елементів у двовимірній сітці (по колонках та рядках). 
Прекрасно підходить для створення розкладок, де потрібно чітко визначити, які елементи мають займати певні області. 
Недоліки: може бути надмірно складним для простих версток. 
Деякі браузери можуть мати обмежену підтримку деяких властивостей Grid.

В) Без використання Flexbox CSS та Grid CSS (float): 
Переваги: підходить для класичних версток і простих макетів. 
Хороша сумісність з усіма браузерами, навіть зі старими версіями. 
Недоліки: важче керувати вирівнюванням та розподілом елементів. 
Не такий гнучкий, як Flexbox чи Grid, для адаптивних дизайнів. 
Може призводити до проблем з очищенням контейнерів і розміщенням елементів, якщо не використовуються додаткові стратегії.

Висновок: у процесі виконання лабораторної роботи були створені три варіанти головної веб-сторінки з використанням Flexbox, Grid та традиційного методу через float. Flexbox і Grid забезпечили гнучкість і легкість в адаптивності, тоді як використання float обмежене в складних макетах. Всі варіанти були успішно опубліковані на GitHub Pages, що продемонструвало їх коректне відображення на різних пристроях і розмірах екранів. 


**Лабораторна робота №3**

У процесі виконання лабораторної роботи було створено адаптивну веб-сторінку з використанням HTML і CSS. Для покращення сумісності в поштових клієнтах були застосовані інлайн-стилі, що відповідає сучасним рекомендаціям для email-розсилок. Сторінка була опублікована через GitHub Pages, що дозволило створити стабільне та доступне посилання для перевірки відображення.Після тестування у різних поштових сервісах (Gmail, Outlook, Ukr.net) на комп’ютерах та мобільних пристроях встановлено:
1. Сторінка відкривається однаково та коректно у всіх перевірених поштових клієнтах.
2. Адаптивність сторінки працює належним чином: на малих екранах усі секції шикуються у вертикальну послідовність відповідно до заданого медіазапиту.
3. Стилі збережені повністю, без "обрізання" або спотворення елементів інтерфейсу.
4. Візуальна структура та кольори залишилися такими, як було задумано.
**Аналіз:**
Переваги використання інлайн-стилів:
1. Висока сумісність із різними поштовими клієнтами та браузерами.
2. Гарантія, що стилі не будуть видалені або змінені системами безпеки поштових серверів

Недоліки інлайн-стилів:
1. Код стає довшим та менш структурованим, що ускладнює підтримку й редагування у майбутньому.
2. Щодо таблицевої верстки (альтернативний підхід для email): таблиці мають ще вищу сумісність із найстарішими версіями поштових клієнтів, але вони ускладнюють реалізацію адаптивності без додаткового коду та роблять підтримку коду громіздкою.
**Висновок:** обраний підхід із інлайн-стилями та використанням сучасних CSS-технологій (Grid + медіазапити) виправдав себе, оскільки забезпечив і якісне відображення сторінки, і хорошу адаптивність, і високу сумісність із популярними поштовими клієнтами.
