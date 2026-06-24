<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Туроператор</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: Arial, sans-serif;
            background: #E3F2FD;
            color: #333;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 40px 20px;
        }
        .container {
            max-width: 900px;
            width: 100%;
            background: white;
            border-radius: 24px;
            padding: 40px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.1);
        }
        h1 {
            text-align: center;
            font-size: 32px;
            color: #0D47A1;
            margin-bottom: 8px;
        }
        .subtitle {
            text-align: center;
            color: #555;
            font-size: 16px;
            margin-bottom: 30px;
        }
        .apps {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 24px;
            margin: 20px 0;
        }
        .app-card {
            background: #F0F7FF;
            border-radius: 16px;
            padding: 24px;
            text-align: center;
            border: 2px solid #BBDEFB;
            transition: 0.3s;
        }
        .app-card:hover {
            border-color: #1976D2;
            transform: translateY(-4px);
            box-shadow: 0 8px 24px rgba(25, 118, 210, 0.15);
        }
        .app-card .icon { font-size: 48px; margin-bottom: 12px; }
        .app-card h3 { font-size: 20px; color: #0D47A1; margin-bottom: 8px; }
        .app-card .platform { color: #1976D2; font-weight: 600; font-size: 14px; margin-bottom: 8px; }
        .app-card p { color: #555; font-size: 14px; margin-bottom: 16px; line-height: 1.5; }
        .btn {
            display: inline-block;
            padding: 12px 32px;
            background: #1976D2;
            color: white;
            text-decoration: none;
            border-radius: 30px;
            font-weight: bold;
            transition: 0.3s;
            border: none;
            cursor: pointer;
        }
        .btn:hover { background: #0D47A1; transform: scale(1.02); }
        .footer {
            text-align: center;
            margin-top: 30px;
            color: #888;
            font-size: 14px;
            border-top: 1px solid #E3F2FD;
            padding-top: 20px;
        }
        .footer .name {
            color: #0D47A1;
            font-weight: 600;
        }
        @media (max-width: 600px) {
            .apps { grid-template-columns: 1fr; }
            .container { padding: 20px; }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🌍 Туроператор</h1>
        <p class="subtitle">Автоматизированная система подбора и бронирования туров</p>

        <div class="apps">
            <!-- APK -->
            <div class="app-card">
                <div class="icon">📱</div>
                <h3>Мобильное приложение</h3>
                <div class="platform">Android — APK</div>
                <p>
                    Приложение для подбора тура, выбора дат,<br>
                    расчёта стоимости и оформления заявок.<br>
                    <strong>Версия 1.0</strong>
                </p>
                <a href="https://disk.yandex.ru/d/rb09JAdv_197NQ" class="btn" target="_blank">
                    ⬇️ Скачать APK
                </a>
            </div>

            <!-- EXE -->
            <div class="app-card">
                <div class="icon">💻</div>
                <h3>Desktop приложение</h3>
                <div class="platform">Windows — EXE</div>
                <p>
                    Десктопный модуль с полным функционалом.<br>
                    Не требует установки Python.<br>
                    <strong>Версия 1.0</strong>
                </p>
                <a href="https://disk.yandex.ru/d/M1MRAgcylJoAtg" class="btn" target="_blank">
                    ⬇️ Скачать EXE
                </a>
            </div>
        </div>

        <div class="footer">
            © 2026 — Авторский лендинг<br>
            <span class="name">Перелыгина Юлия Александровна</span> · ИС-151
        </div>
    </div>
</body>
</html>
