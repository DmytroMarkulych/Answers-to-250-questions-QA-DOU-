### 1. Що таке тестування?

Тестування - процес порівняння Актуального результату з Фактичним результатом

### 2. Навіщо тестувати ПЗ?

Потрібно для того щоб забезпечити необхідну якість програмного забезпечення і знизити ризик помилок у програмі “багів”.

### 3. Які є етапи тестування?

#### 1-й Аналіз вимог 
Умови і критерії роботи системи, як правило, визначаються замовником або менеджером проєкту в процесі спілкування з клієнтом, або аналізом стандартів та нормативної документації. Ці вимоги можуть бути як функціональними, так і не функціональними.
Тестувальник працює над статичним тестуванням вимог: досліджує їх повноту, логічність, однозначність і визначеність, також знаходить слабкі місця в тестовому покритті і виявляє можливі ризики. Виникають обставини, коли наявні вимоги не тестуються, але використовуються на етапі дизайну і розробки. І вже готовий продукт направляється у відділ QA. Тоді кількість знайдених дефектів, вартість та масштаб їх виправлення можуть значно зрости.
 
#### 2-й. Процес дизайну 
Один з найважливіших складових етапів, тому що користувачеві доведеться постійно взаємодіяти з системою. Продукт повинен бути інтуїтивно зрозумілий у використанні, мати приємний інтерфейс, а також бути оптимізованим (користувач робить мінімальні дії для досягнення результату). На даному етапі тестувальник перевіряє існуючі прототипи ПЗ на відповідність вимогам замовника, коректності відображення візуальних елементів і зручності використання.

#### 3-й. Розробка 
Під час процесу розробки системи необхідно провести модульне, інтеграційне та системне тестування. 
Для початку тестуються окремі компоненти програми. Це дозволяє виявити, в якій саме частині коду є помилка і досить швидко усунути її. Ще модульне тестування допомагає відстежити, чи не призвела зміна коду до появи нових помилок в уже перевірених місцях продукту. Також це допомагає краще зрозуміти роль кожного модуля системи. Усі знайдені дефекти, як правило, виправляються в коді без формального їх опису (внесення звітів в баг-трекер).Інтеграційне тестування дозволяє перевірити, як компоненти коду об'єднуються і взаємодіють один з одним. Також воно визначає зв'язки між модулями, обладнанням або різними системами.
І, нарешті, переходимо до системного тестування. На цій стадії мається на увазі перевірка всіх компонентів і модулів в цілому. Це необхідно для зменшення ймовірності дефектів, пов'язаних з особливостями поведінки системи в різних середовищах. В ході цих перевірок виявляються такі баги, як: нераціональне використання ресурсів системи, несумісність з оточенням, збій або неправильне функціонування функціоналу та інше.
 
#### 4-й. Процес тестування та дебаггінгу
Дебаггінг (налагодження) – це процес, під час якого знаходять і усувають помилки програми.
На даному етапі тестувальники перевіряють систему на наявність дефектів незалежно від того, чи відбувалось це раніше. Проводиться повне тестування інтерфейсу та функціоналу продукту. Всі виявлені помилки повинні бути задокументовані в баг-трекері. Також слід провести регресійне тестування, щоб дослідити систему на предмет дефектів, які могли з'явитися після усунення інших багів.
По завершенню процесу налагодження потрібно надати оцінку якості продукту, наскільки відповідають вимоги замовника реальній роботі системи.

#### 5-й. Експлуатація та підтримка
Після того, як продукт надходить у реліз, залишається необхідність у тестуванні, так як буде відбуватися оновлення ПЗ, будуть з'являтися нові баги, які були випущені або баги, пов'язані з експлуатацією кінцевого користувача. В такому випадку потрібне втручання відділу QA.
У разі виявлення користувачами тих чи інших пост-релізних багів, інформація про них передається у вигляді звітів про помилки команді розробки, яка, в залежності від серйозності проблеми, або негайно випускає виправлення (т.зв. hot-fix), або відкладає його до наступної версії програми.
Всі зміни, що вносяться до програмного забезпечення, необхідно ретельно протестувати. ПЗ повинне продовжувати виконувати спочатку закладені в ньому бізнес-функції і не порушувати працездатність інших функцій і всієї системи в цілому.

### 4. Які типи тестування можете назвати?

#### За об’єктом тестування виділяють наступні види тестування ПЗ:
- функціональне тестування (functional testing);
- дослідницьке тестування (exploratory testing);
- тестування продуктивності (performance testing);
- навантажувальне тестування (load testing);
- димне тестування (smoke testing);
- стрес-тестування (stress testing);
- тестування стабільності (stability / endurance / soak testing);
- тестування зручності використання (usability testing);
- тестування інтерфейсу користувача (ui testing);
- тестування безпеки (security testing);
- тестування локалізації (localization testing);
- тестування сумісності (compatibility testing).
#### У залежності від переслідуваних цілей, види тестування можна умовно розділити на наступні типи:
- функціональне тестування (functional);
- нефункціональне тестування (non-functional);
- тестування пов’язане зі змінами.
#### За знанням системи:
- тестування чорної скриньки (black box);
- тестування білої скриньки (white box);
- тестування сірої скриньки (gray box).
#### За ступенем автоматизації:
- ручне тестування (manual testing);
- автоматизоване тестування (automated testing);
- напівавтоматизоване тестування (semiautomated testing).
#### За ступенем ізольованості компонентів:
- компонентне (модульне) тестування (component / unit testing);
- інтеграційне тестування (integration testing);
- системне тестування (system / end-to-end testing).
#### За часом проведення тестування:
- Альфа-тестування (alpha testing):
- тестування нової функціональності (new feature testing);
- регресійне тестування (regression testing);
- тестування при здачі (acceptance testing);
- Бета-тестування (beta testing).
#### За ознакою позитивності сценаріїв:
- позитивне тестування (positive testing);
- негативне тестування (negative testing).
#### За ступенем підготовленості до тестування:
- тестування за документацією (formal testing);
- Ad Hoc Testing (інтуїтивне) тестування (ad hoc testing).
#### Більше детальної інформації по видах тестування:
https://qagroup.com.ua/publications/vydy-testuvannya-ta-vidminnosti-mizh-nymy/

### 5.Які рівні тестування знаєте?
В основному існує чотири рівні тестування при тестуванні програмного забезпечення:
- #### Модульне тестування (Unit test) : #### перевіряє, чи компоненти програмного забезпечення відповідають функціональним можливостям чи ні.
- #### Тестування інтеграції (Integration Test): #### перевіряє потік даних від одного модуля до інших модулів.
- #### Системне тестування(System Test) : #### оцінює як функціональні, так і нефункціональні потреби в тестуванні.
- #### Випробування на приймання (Acceptance Test) : #### перевіряє, чи відповідають вимогам специфікації або контракту відповідно до її поставки.

### 6.Які техніки тест-дизайну знаєте?
#### Тест дизайн  – #### це етап процесу тестування ПЗ, на якому проектуються та створюються тестові випадки (тест кейси), відповідно до визначених раніше критеріїв якості та цілей тестування. Просто кажучи, завдання тест зводиться до того, щоб використовуючи різні стратегії та техніки тест дизайну, створити набір тестових випадків, що забезпечує оптимальну перевірку програми, що тестується.
#### Основні техніки тест дизайну:####
 #### Еквівалентний поділ (Equivalence Partitioning - EP) ####
Метод еквівалентного поділу дозволяє мінімізувати число тестів, не створюючи сценарій для кожного можливого значення, а вибравши лише одне значення з цілого класу і прийнявши за аксіому, що для всіх значень цієї групи результат буде аналогічним.
Наприклад, ми тестуємо функціональність програми, що дозволяє купувати авіа- та залізничні квитки онлайн. Вартість квитка залежатиме від віку пасажира, оскільки діти, студенти та пенсіонери належать до пільгових категорій. У нас є чотири вікові групи: молодше 15 років, від 15 до 25 років, старше 25 і молодше 60 років і люди старше 60. При цьому в полі для введення віку міститься всього два символи, тому вказати вік понад 99 років технічно неможливо.
QA-фахівцеві не потрібно писати 99 тестів для кожного віку, вистачить п'яти: по одному для кожної вікової групи (скажімо, 10, 18, 35 та 75 років) та один для випадку, якщо вік людини перевищує 99 років. Так, останній тест на практиці нездійсненний (оскільки в полі віку неможливо ввести більше двох знаків), та все ж не слід забувати про цю перевірку.

#### Аналіз граничних значень (Boundary Value Analysis - BVA) ####
Якщо взяти приклад вище, як значення для позитивного тестування виберемо мінімальну і максимальну межі (1 і 99), і значення більше і менше меж (0 і 100). Аналіз Граничний значень може бути застосований до полів, записів, файлів та інших параметрів, що мають обмеження. Щоб переконатися в правильності поведінки програми при різних вхідних даних, в ідеалі слід протестувати всі можливі значення кожного елемента цих даних.
Щоб зменшити кількість значень, що тестуються, проводиться:
1. Розбиття множини всіх значень вхідної змінної на підмножини (класи еквівалентності)
2. Тестування одного будь-якого значення з кожного класу
Якщо тест проходить успішно для одного значення класу еквівалентності, він повинен проходити успішно для всіх інших. І навпаки, якщо тест не проходить для одного значення, він не повинен проходити для решти. Таким чином, метод класів еквівалентності можна поділити на три етапи:
1. Тестування дозволених значень
2. Тестування граничних значень
3. Тестування заборонених значень.

#### Причина/Слідство (Cause/Effect - CE). ####
 Це введення комбінацій умов (причин) для отримання відповіді від системи (слідство). Наприклад, ви перевіряєте можливість додавати клієнта, використовуючи певну екранну форму. Для цього вам необхідно буде ввести кілька полів, таких як "Ім'я", "Адреса", "Номер Телефону", а потім натиснути кнопку "Додати" - ця "Причина". Після натискання кнопки «Додати» система додає клієнта в базу даних і показує його номер на екрані — це «Слідство».
 
#### Передбачення помилки (Error Guessing — EG) ####
 Це коли тест аналітик використовує свої знання системи та здатність до інтерпретації специфікації щодо того, щоб «передбачити» за яких вхідних умов система може видати помилку. Наприклад, специфікація каже: "користувач повинен ввести код". Тест аналітик буде думати: «Що, якщо я не введу код?», «Що, якщо я введу неправильний код? ", і так далі. Це і є передбачання помилки. 
 
#### Вичерпне тестування (Exhaustive Testing - ET). ####
Використовується вкрай поодиноких випадках. У межах цієї техніки ви повинні перевірити всі можливі комбінації вхідних значень, і в результаті це має знайти всі проблеми. Насправді застосування цього методу неможливо, через велику кількість вхідних значень.

#### Попарне тестування (Pairwise testing). ####
 Метод класів еквівалентності застосовується тестування кожного вхідного параметра окремо. Нехай наша програма приймає на вхід десять параметрів. Дефекти, що виникають за певного поєднання всіх десяти параметрів, досить рідкісні. Взаємний вплив параметрів, про який користувач не знає, - це дефект інтерфейсу (інтерфейс інтуїтивно не зрозумілий). Найчастіше зустрічатимуться ситуації, у яких один параметр впливає одне із тих, що залишилися, тобто. найчастішими будуть дефекти, що виникають при певному поєднанні двох параметрів. Таким чином, можна спростити собі завдання та протестувати всі можливі значення для кожної з пар параметрів. Такий підхід називається попарним тестуванням (pairwise testing).


9.Що таке Regression і Confirmation тестування, яка між ними різниця?
10.Як часто варто проводити регресійне тестування продукту?
11.Які бувають види інтеграційного тестування?
12.Що таке Configuration testing?
13.Що таке Exploratory testing?
14.Які існують UI-стандарти?
15.Що таке Black/Grey/White Box Testing?
16.Що таке Performance Testing?
17.Що таке Smoke та Sanity тестування і яка між ними різниця?
18.Що таке Traceability Matrix?
19.Що таке Sanity Testing?
20.Що таке End-to-End тест?
21.Що таке тестування безпеки?
22.Що таке випробування на основі ризиків?
23.Що таке динамічне тестування?
24.Що таке «парадокс пестициду»?
25.Опишіть основні фази STLC? Дайте визначення Entry та Exit Criteria.
26.Що таке Bug, Error, Failure, Fault?
27.Які є атрибути баг-репорту? Які основні поля для заповнення?
28.Яка різниця між пріоритетом і серйозністю?
29.Наведіть приклади серйозного, але не пріоритетного багу.
30.У чому різниця між валідацією та верифікацією?
31.Навіщо потрібна тестова документація? Які її види?
32.Що таке тест-план? Які елементи він має?
33.Яку обов’язкову інформацію має містити тест-план? Як правильно його використовувати, підтримувати та чи взагалі він потрібний для більшості проєктів?
34.Яка різниця між чеклістом і тест-кейсами?
35.Наведіть приклад хорошого тест-кейсу.
