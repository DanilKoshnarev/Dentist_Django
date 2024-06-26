# Dentist Clinic

В цьому проекті ми працюємо над створенням веб-сайту для стоматологічної клініки.

## Учасники проекту

1. Уляна Шамільова (Team Lead)
   
   - GitHub профіль: [UlyanaShamilova](https://github.com/UlyanaShamilova)
   
   - Figma проект: [Figma Project](https://www.figma.com/design/v8zsIeGGLNxgXN4j9VlyQQ/Untitled?node-id=0-1&t=M0h7vMHDwMcdirco-1)
   
   - FigJam проект: [FigJam Project](https://www.figma.com/board/uzB60e2o9Mh5KEZgq40tmA/Untitled?node-id=0-1&t=5ciEY9J7BZFZBO1C-1)
   
3. Павло Устич (Full Stack Developer)
   
   - GitHub профіль: [pavel-ustych-v](https://github.com/pavel-ustych-v)
   
   - Figma проект: [Figma Project](https://www.figma.com/design/iOp7LH5dnMdAzAsNeNc1YB/Dentists---project?t=BL1WdQzrCKhPzmMH-1)
   
    - FigJam проект: [FigJam Project](https://www.figma.com/board/rGsSmSDPyRF65GE1lg5KHn/Untitled?t=BL1WdQzrCKhPzmMH-1)
   
5. Назар Зозуля (Full Stack Developer)
   
   - GitHub профіль: [Nazar-Zozulya](https://github.com/Nazar-Zozulya)
   
   - Figma проект: [Figma Project](https://www.figma.com/design/U7j60sky15Ah4svZ5OkjAv/%D0%97%D0%B4%D0%BE%D1%80%D0%BE%D0%B2%D0%B0-%D0%BF%D0%BE%D1%81%D0%BC%D1%96%D1%88%D0%BA%D0%B0?node-id=0-1&t=YX774ACYa85vNaU1-1)
   
   - FigJam проект: [FigJam Project](https://www.figma.com/board/t4iufr1JmRpZwJla7kyWBI/%D0%97%D0%B4%D0%BE%D1%80%D0%BE%D0%B2%D0%B0-%D0%BF%D0%BE%D1%81%D0%BC%D1%96%D1%88%D0%BA%D0%B0-FigJam?node-id=0-1&t=Bjx14rXO9EI0TqFE-1)
   
7. Данило Кошнарьов (Full Stack Developer)
   
   - GitHub профіль: [DanilKoshnarev](https://github.com/DanilKoshnarev)
   
   - Figma проект: [Figma Project](https://www.figma.com/design/YpxoSvDuPoPzSRsXEfas5p/Untitled?node-id=0-1&t=10FxvHjbiRjT482v-1)
   
   - FigJam проект: [FigJam Project](https://www.figma.com/board/qk3eLvORSrN1Bz74wG4CIR/Untitled?node-id=0-1&t=EuJST6NJS6qIhpZS-1)

## Технології

- HTML/CSS - мови розмітки, які використовуються для створення та стилізації веб-сторінки;
- Python/Django - мовиапрограмування та її фреймворк, які використовуються для написання логіки веб-сайту;
- Ajax - використовується для асинхронної взаємодії з сервером для оновлення частини веб-сторінки без повного перезавантаження;
- SQLite3/MySQL - бази даних, які використовуються для зберігання даних користувача(логін, пароль) на сервері;
- Bootstrap - фреймворк для зручної та швидкої розробки інтерфейсу;
- Figma - інструмент для створення дизайну веб-сторінки без логіки.

## Сторінки

- Головна
- Послуги
- Контакти
- Інформація
- Сторінки авторизації та реєстрації

## Моделі, використані у проекті
![image](https://github.com/UlyanaShamilova/Dentist_Django/assets/110716865/b92d5924-d599-4742-a9f6-1a80509c24df)

Ця модель використовується для представлення категорії послуг. Наприклад, категорії включають такі елементи, як "Ортодонтичні послуги", "Хірургічні втручання" тощо.
Модель має 1 поле: назва категорії.

![image](https://github.com/UlyanaShamilova/Dentist_Django/assets/110716865/91267b5a-f5c6-4b19-9522-f636eb155245)

Ця модель використовується для представлення конкретної послуги, що надається клінікою. Наприклад, послуги включають такі елементи, як "Пломбування", "Видалення зуба" тощо.
Кожна послуга має три поля: назва послуги, ціна послуги, та категорію, до якої вона відноситься.

## Функції, використані у проекті

Функція реєстрації користувача, яка перевіряє введення вірних даних:

![image](https://github.com/UlyanaShamilova/Dentist_Django/assets/110716865/f58cc1b3-f573-4561-8ad8-c0dbbbf699ad)

Функція авторизації користувача на сайті:

![image](https://github.com/UlyanaShamilova/Dentist_Django/assets/110716865/c5110151-6f81-4a3d-a6a0-3f6344710ecd)

Функція виходу з акаунту на сайті:

![image](https://github.com/UlyanaShamilova/Dentist_Django/assets/110716865/84a8909a-8122-4470-88ba-88d50ffb8cb7)

Функція, яка відправляє повідомлення з проблемою клієнта на пошту клініки:

![image](https://github.com/UlyanaShamilova/Dentist_Django/assets/110716865/0a6e936a-5f95-46dc-81c7-dc38bbeecfdc)

У цій функції ми отримуємо дані з моделей, і виводимо їх на сайт:

![image](https://github.com/UlyanaShamilova/Dentist_Django/assets/110716865/49d7f55e-a03a-490d-b4bc-c776d7397a55)

## Використання ajax у проекті

Тут ми отримуємо дані користувача з форми реєстрації, яку він заповнює, і перевіряємо на наявність помилок, не оновлюючи сторінки:

![image](https://github.com/UlyanaShamilova/Dentist_Django/assets/110716865/8ee59af1-7081-4299-ac9f-77af9f779e42)

Тут ми отримуємо дані користувача з форми реєстрації, яку він заповнює, і перевіряємо на наявність помилок, не оновлюючи сторінки:

![image](https://github.com/UlyanaShamilova/Dentist_Django/assets/110716865/a058c769-2a46-4967-8271-4ba113c6f32f)
