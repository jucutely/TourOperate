<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Туроператор — авторский лендинг</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: #f8faff;
            color: #1a1a2e;
            line-height: 1.6;
        }

        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 0 24px;
        }

        header {
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            color: #fff;
            padding: 60px 0 50px;
            text-align: center;
            border-bottom: 6px solid #2196F3;
        }

        header h1 {
            font-size: 42px;
            font-weight: 700;
            letter-spacing: 1px;
        }

        header h1 span {
            color: #4fc3f7;
        }

        header p {
            font-size: 18px;
            opacity: 0.9;
            margin-top: 10px;
        }

        .author {
            margin-top: 16px;
            font-size: 16px;
            background: rgba(255, 255, 255, 0.08);
            display: inline-block;
            padding: 6px 24px;
            border-radius: 40px;
            backdrop-filter: blur(4px);
        }

        .description {
            background: #fff;
            padding: 40px 0;
            text-align: center;
            border-bottom: 1px solid #e9ecf3;
        }

        .description h2 {
            font-size: 28px;
            font-weight: 600;
            color: #0f2027;
        }

        .description p {
            max-width: 700px;
            margin: 12px auto 0;
            color: #3e4a5e;
            font-size: 17px;
        }

        .apps {
            padding: 50px 0;
            background: #f8faff;
        }

        .apps-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            justify-content: center;
        }

        .app-card {
            background: #ffffff;
            border-radius: 28px;
            padding: 32px 28px 28px;
            width: 100%;
            max-width: 380px;
            box-shadow: 0 8px 30px rgba(0, 0, 0, 0.06);
            transition: transform 0.25s ease, box-shadow 0.3s ease;
            border: 1px solid #eef2f9;
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
        }

        .app-card:hover {
            transform: translateY(-6px);
            box-shadow: 0 18px 45px rgba(0, 0, 0, 0.08);
        }

        .app-icon {
            font-size: 48px;
            margin-bottom: 8px;
        }

        .app-card h3 {
            font-size: 24px;
            font-weight: 700;
            margin: 8px 0 4px;
            color: #0f2027;
        }

        .app-card .badge {
            font-size: 14px;
            font-weight: 600;
            background: #eef3fc;
            color: #1e3b5c;
            padding: 4px 16px;
            border-radius: 40px;
            display: inline-block;
            margin-bottom: 12px;
        }

        .app-card p {
            color: #3e4a5e;
            font-size: 15px;
            margin-bottom: 18px;
            flex: 1;
        }

        .btn-download {
            display: inline-block;
            background: #1a2b3c;
            color: #fff;
            padding: 12px 32px;
            border-radius: 60px;
            font-weight: 600;
            font-size: 16px;
            text-decoration: none;
            transition: background 0.2s ease, transform 0.2s ease;
            width: 100%;
        }

        .btn-download:hover {
            background: #2196F3;
            transform: scale(1.02);
        }

        .btn-download.android {
            background: #0f2027;
        }

        .btn-download.android:hover {
            background: #1b4a5a;
        }

        .btn-download.desktop {
            background: #1a2b3c;
        }

        .btn-download.desktop:hover {
            background: #2c4b66;
        }

        .file-info {
            font-size: 14px;
            color: #7a879b;
            margin-top: 10px;
        }

        footer {
            background: #0f2027;
            color: #b0c7d6;
            padding: 30px 0;
            text-align: center;
            border-top: 4px solid #2196F3;
        }

        footer p {
            font-size: 15px;
            margin: 4px 0;
        }

        footer .copy {
            color: #7c97ad;
        }

        @media (max-width: 600px) {
            header h1 {
                font-size: 28px;
            }
            .app-card {
                max-width: 100%;
            }
            .btn-download {
                width: 100%;
                text-align: center;
            }
        }
    </style>
</head>
<body>

    <header>
        <div class="container">
            <h1>🌍 <span>Туроператор</span></h1>
            <p>Автоматизированная система подбора и бронирования туров</p>
            <div class="author">👤 Якимюк Карина Руслановна · ИС-151</div>
        </div>
    </header>

    <section class="description">
        <div class="container">
            <h2>📱 Мобильное приложение + 💻 Десктопный модуль</h2>
            <p>
                Выбирайте страну, отель, питание, даты и получайте расчёт стоимости.
                Всё в одном месте — для Android и Windows.
            </p>
        </div>
    </section>

    <section class="apps">
        <div class="container">
            <div class="apps-grid">

                <!-- Android -->
                <div class="app-card">
                    <div class="app-icon">📱</div>
                    <h3>Android</h3>
                    <span class="badge">APK</span>
                    <p>
                        Мобильное приложение для подбора тура, выбора дат, 
                        расчёта стоимости и оформления заявок.
                    </p>
                    <a href="https://disk.yandex.ru/d/rb09JAdv_197NQ" class="btn-download android" target="_blank">
                        ⬇ Скачать APK
                    </a>
                    <span class="file-info">Версия 1.0 · 15 МБ</span>
                </div>

                <!-- Windows -->
                <div class="app-card">
                    <div class="app-icon">💻</div>
                    <h3>Windows</h3>
                    <span class="badge">Python</span>
                    <p>
                        Десктопный модуль с полным функционалом: подбор тура,
                        календарь вылетов, админ-панель и отчёты.
                    </p>
                    <a href="https://disk.yandex.ru/d/M1MRAgcylJoAtg" class="btn-download desktop" target="_blank">
                        ⬇ Скачать EXE
                    </a>
                    <span class="file-info">Версия 1.0 · 25 МБ</span>
                </div>

            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>© 2026 — Авторский лендинг</p>
            <p class="copy">Якимюк Карина Руслановна · ИС-151</p>
        </div>
    </footer>

</body>
</html>
