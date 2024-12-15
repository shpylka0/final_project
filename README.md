# Перевірка надійності паролів

Цей проєкт дозволяє перевірити надійність пароля за кількома критеріями, включаючи його довжину, наявність великих і малих літер, цифр, спеціальних символів, а також перевірку на те, чи є пароль поширеним або зламаним (через API Have I Been Pwned).

## Функціональність

1. **Перевірка надійності пароля:**
   - Перевіряється довжина пароля (не менше 8 символів).
   - Перевірка на наявність великих і малих літер.
   - Перевірка на наявність цифр і спеціальних символів.
   - Перевірка, чи є пароль у списку найбільш поширених паролів.

2. **Перевірка на зламані паролі:**
   - Перевіряється, чи є пароль у відкритих базах зламаних паролів через API **Have I Been Pwned**.

3. **Колірний вивід:**
   - Використовується бібліотека `colorama` для кольорового виведення результатів перевірки.

4. **Запис історії перевірок:**
   - Результати перевірки зберігаються в локальному файлі `password_checks.json`.
   - 
## Як запустити проєкт


1. Клонувати репозиторій:
 - git clone https://github.com/shpylka0/final_project.git
2. Встановити необхідні бібліотеки:
 - pip install -r requirements.txt
4. Запустити проєкт:
 - python password_checker.py

# Як переглянути історію паролів


1. Запустіть файл read_history.py:
 - python read_history.py
