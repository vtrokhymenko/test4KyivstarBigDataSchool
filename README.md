# test4KyivstarBigDataSchool

Крок 1. Розбираємося в тому, коли і що потрібно буде зробити.
Ви маєте повні 24 години, тобто час до 10:00 ранку 8 жовтня, щоб встигнути завантажити завдання, розв'язати вказану проблему та завантажити у форму результат і код.
 
Крок 2. Завдання.
Завантажити завдання

Крок 3. Перевіряємо, що було завантажено і навіщо.
Архів містить 5 файлів: train.txt, test.txt, Base1.txt, Base2.txt, PetrenkoPetro_test.txt. 
 
Навіщо вони потрібні? Ці файли допоможуть вирішити аналітичну задачу - визначення рівня доходу абонента. Зазвичай така інформація використовується для того, щоб зробити контекстну пропозицію або рекламу більш точними. І для цього:

➤ Файл train.txt містить інформацію про 6 229 абонентів:
ID – ідентифікатор абонента.
Стовпчик TARGET визначає до якої групи за рівнем доходу належить абонент та приймає значення 0, 1, 2, 3.
Це, як Ви розумієте, навчальна вибірка.
 
➤ Файл test.txt містить інформацію про 3 038 абонентів. Це тестовий набір даних.
 
➤ В файлах Base1.txt і Base2.txt зібрані дані по абонентам для навчання і тестування.
 
Зокрема, файл Base2.txt містить ID та захешовані факторні змінні T1, T2, T3, T4, а у файлі Base1.txt по абонентам зібрані помісячно числові неперервні дані за півроку, де:
ID – ідентифікатор абонента.
MONTH – кількість місяців від дати зрізу до розрахункової дати.
V1, V2, ..., V42 - числові неперервні змінні, що містять деякі дані про дії абонента в мережі.
➤ А для чого потрібен файл PetrenkoPetro_test.txt? Це файл зі зразком рішення. Тобто, ми будемо чекати від Вас рішення саме в такому форматі, Вам необхідно лише кожного абонента віднести до однієї або іншої групи.

Проте новий файл Ви маєте назвати своїм ім'ям та прізвищем. 

Крок 4. У чому ж завдання?
На навчальній вибірці на підставі даних про активності абонента в мережі потрібно побудувати модель, що визначить до якої групи за рівнем доходу належить цей абонент. 

Потім застосуйте модель на тестовому наборі даних і кожне спостереження віднесіть до відповідної групи за рівнем доходу. Значення групи повинні бути внесені в стовпець TARGET файлу PetrenkoPetro_test.txt. 
 
В результаті Ви маєте створити файл, який містить усього два стовпці:
ID – ідентифікатор абонента з тестового набору даних (тестової вибірки).
TARGET – відповідна група за рівнем доходу. 
Подивіться знову на зразок PetrenkoPetro_test.txt.

Слід зазначити, що для оцінки якості моделі ми будемо використовувати Accuracy. Але ще потрібно оцінити Ваш підхід та стиль, тож для цього попросимо надіслати код програми, за допомогою якого були отримані результати.
 
Крок 5.1. Оформлення рішення – результати.
Зберігаємо передбачені групи для тестової вибірки у файл MoyePrizvyshcheMoyeImya_test.txt в такому саме форматі, як у файлі PetrenkoPetro_test.txt, де MoyePrizvyshcheMoyeImya = Ваше прізвище і Ваше ім'я.

Ми хочемо, щоб Ви назвали свій файл унікально, про всяк випадок :)

Крок 5.2. Оформлення рішення – код.
Зберігаємо код програми в файл MoyePrizvyshcheMoyeImyaPROGRAM.? Залежно від мови програмування, природньо, у файлі буде відповідне розширення: .R, або .py або .txt або ще яке-небудь.

Наприклад:
MoyePrizvyshcheMoyeImyaPROGRAM.R,
MoyePrizvyshcheMoyeImyaPROGRAM.py,
MoyePrizvyshcheMoyeImyaPROGRAM.txt і т.д.
 
Крок 6. Завантажуємо рішення.
Переходимо за посиланням та для Вашої ідентифікації вводимо свою електрону адресу та натискаємо кнопку «Підтвердити». Після успішного підтвердження у Вас з’являється можливість завантажити обидва файли з результатами – MoyePrizvyshcheMoyeImya_test.txt і MoyePrizvyshcheMoyeImyaPROGRAM.? Для цього натискаємо на кнопку «Вибрати файли» та не забуваємо натиснути кнопку «Відправити».
 
Крок 7. Очікування результатів.
Якщо Ви бачите повідомлення «Дякуємо ...» – значить все відмінно. Тепер можна буде відпочивати і чекати від нас листа.
 
