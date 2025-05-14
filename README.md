<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Автозвук Проєкт</title>
    <style>
        body { font-family: 'Segoe UI', sans-serif; background-color: #eaeaea; margin: 0; padding: 0; }
        header, footer { background-color: #111; color: white; text-align: center; padding: 1.5em 0; }
        nav a { margin: 0 20px; color: #f0f0f0; text-decoration: none; font-weight: bold; }
        .container { padding: 40px 20px; max-width: 1000px; margin: auto; background-color: #fff; box-shadow: 0 0 10px rgba(0,0,0,0.1); border-radius: 12px; }
        h2 { border-bottom: 2px solid #ccc; padding-bottom: 10px; }
        .gallery { display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; margin-top: 20px; }
        .gallery img { width: 300px; border-radius: 10px; box-shadow: 0 4px 6px rgba(0,0,0,0.1); transition: transform 0.3s; }
        .gallery img:hover { transform: scale(1.05); }
        form { background: #f9f9f9; padding: 25px; border-radius: 10px; box-shadow: 0 2px 4px rgba(0,0,0,0.1); }
        input, textarea { width: 100%; padding: 12px; margin: 10px 0; border-radius: 6px; border: 1px solid #ccc; }
        button { padding: 12px 20px; background-color: #333; color: white; border: none; border-radius: 6px; cursor: pointer; }
        button:hover { background-color: #555; }
    </style>
</head>
<body>
    <header>
        <h1>Автозвук Проєкт</h1>
        <nav>
            <a href="#about">Про нас</a>
            <a href="#gallery">Галерея</a>
            <a href="#contact">Контакти</a>
        </nav>
    </header>

    <div class="container">
        <section id="about">
            <h2>Про наш проєкт</h2>
            <p>Ми займаємось професійною установкою та налаштуванням автозвуку. Від бюджетних рішень до преміум аудіосистем. Наша мета — забезпечити найкращу якість звуку в кожному авто.</p>
        </section>

        <section id="gallery" class="gallery">
            <h2>Галерея робіт</h2>
            <img src="https://images.unsplash.com/photo-1588776814546-b4446b1599de" alt="Аудіосистема 1">
            <img src="https://images.unsplash.com/photo-1612445887735-06d8d2f8e2e3" alt="Аудіосистема 2">
            <img src="https://images.unsplash.com/photo-1598514982652-5b8b4360ab9d" alt="Аудіосистема 3">
        </section>

        <section id="contact">
            <h2>Зв'яжіться з нами</h2>
            <form>
                <p><strong>Контактна особа:</strong> Кашталєт Станіслав</p>
                <p><strong>Email:</strong> staskashtalet122@gmail.com</p>
                <p><strong>Телефон:</strong> +380972265232</p>
                <label for="name">Ваше ім'я:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Ваш Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Повідомлення:</label>
                <textarea id="message" name="message" rows="4" required></textarea>

                <button type="submit">Надіслати</button>
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 Автозвук Проєкт | Кашталєт Станіслав | +380972265232</p>
    </footer>
</body>
</html>
