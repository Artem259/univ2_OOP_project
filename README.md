Status: Completed.\
(lab3 + project)
-
***Матричний калькулятор***

**Звіт**
1. **Які конкретні задачі планували вирішувати за допомогою цієї бібліотеки?**\
Частину, пов'язану безпосередньо з математичними (матричними) розрахунками.
2. **Чому було обрано саме цю бібліотеку, а не аналоги?**\
Найбільш популярна серед подібних. Напочатку розглядалася можливість використання Armadillo, але ця ідея досить швидко була відкинута через недостатню універсальність та брак деяких математичних операцій, які б довелося реалізовувати самостійно.
3. **Наскільки просто та зрозуміло було отримати, встановити, налаштувати та почати використовувати цю бібліотеку?**\
Отримання та "інсталяція" досить примітивні, адже виконуються без використання додаткових утиліт, простим завантаженням бібліотеки або клонування репозиторію. Налаштування не потрібне. Початок використання ("Hello, world"), відповідно, також не становив особливих труднощів.
4. **Наскільки зрозумілою та корисною була документація бібліотеки?**\
Документація досить зрозуміла (отримання сигнатур методів), але інколи було досить важко знайти потрібний метод серед купи однакових імен з різних класів, доводилось використовувати інтуїтивний пошук і метод вгадування.
5. **Наскільки було зрозуміло, як саме використовувати бібліотеку, які класи/методи/функції використовувати для вирішення поставлених задач?**\
Класи для роботи з матрицями зрозумілі, легко знаходиться пояснення серед початкових гайдів. Але іноді доводилося робити неочевидні маніпуляції с перетвореннями об'єктів (спосіб отримання рангу матриці).
6. **Наскільки зручно було використовувати бібліотеку, чи не треба було писати багато надлишкового коду?**\
Бібліотека дозволила вирішити усі поставлені задачі внутрішніми методами, без дописування власного надлишкового коду.
7. **Наскільки зрозумілою була поведінка класів/методів/функцій з бібліотеки?**\
Поведінка зрозуміла, якщо потрібні класи/методи вже вдалося відшукати серед купи подібних.
8. **Наскільки зрозумілою була взаємодія між різними класами/методами/функціями цієї бібліотеки, а також взаємодія між бібліотекою та власним кодом?**\
Досить зрозуміла. Є реалізовані можливості взаємодії зі стандартними типами даних, а також потоками.
9. **Чи виникали якісь проблеми з використанням бібліотеки? Чи вдалось їх вирішити, як саме?**\
Єдина проблема була з отриманням рангу матриці (описано у п.5), яку вдалося вирішити за першим же посиланням на StackOverflow.
10. **Що хорошого можна сказати про цю бібліотеку, які були позитивні аспекти використання бібліотеки?**\
Як вже сказано у п.6, усе що потребувалось від бібліотеки, було успішно реалізовано досить швидко і без суттєвих проблем.
11. **Що поганого можна сказати про цю бібліотеку, які були негативні аспекти використання бібліотеки?**\
Складна ієрархія документації, купа подібних класів, які перевантажують документацію і заважають зосередитись на пошуку конкретних класів/методів.
12. **Якби довелось вирішувати аналогічну задачу, але вже враховуючи досвід використання в цій лабораторній роботі, що варто було б робити так само, а що змінити? Можливо, використати інші бібліотеки, чи використати інші можливості цієї бібліотеки, чи інакше організувати код, чи ще щось?**\
Зробив би усе так само.

**Використані ресурси**
1. Офіційна документація: https://eigen.tuxfamily.org/dox/
2. https://stackoverflow.com/questions/31041921/how-to-get-rank-of-a-matrix-in-eigen-library
