<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Досье: Секретные материалы</title>
    <style>
        /* Оформление сайта (CSS) */
        body {
            font-family: 'Courier New', Courier, monospace;
            background-color: #0b0f19;
            color: #00ff66;
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }
        .card {
            background-color: #111827;
            border: 2px solid #00ff66;
            border-radius: 10px;
            padding: 30px;
            max-width: 500px;
            width: 100%;
            box-shadow: 0 0 20px rgba(0, 255, 102, 0.2);
        }
        h1 {
            text-align: center;
            color: #ff3333;
            text-transform: uppercase;
            letter-spacing: 2px;
            margin-bottom: 25px;
            border-bottom: 1px dashed #ff3333;
            padding-bottom: 10px;
        }
        .photo-placeholder {
            width: 150px;
            height: 150px;
            border: 2px dashed #00ff66;
            margin: 0 auto 20px auto;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            font-size: 12px;
            color: #888;
        }
        .info-group {
            margin-bottom: 15px;
            font-size: 16px;
            line-height: 1.5;
        }
        .label {
            color: #8892b0;
            font-weight: bold;
        }
        .status-danger {
            color: #ff3333;
            font-weight: bold;
            animation: blink 1.5s infinite;
        }
        @keyframes blink {
            50% { opacity: 0; }
        }
    </style>
</head>
<body>

    <div class="card">
        <h1>[ СЕКРЕТНОЕ ДОСЬЕ ]</h1>
        
        <!-- МЕСТО ДЛЯ ФОТО: Можете заменить текст внутри -->
        <div class="photo-placeholder">
            [ ФОТО В РОЗЫСКЕ ]
        </div>

        <!-- ЛИЧНЫЕ ДАННЫЕ: Меняйте текст после двоеточий -->
        <div class="info-group">
            <span class="label">ФИО Объекта:</span> 
            <span>Иванов Иван Иванович</span>
        </div>

        <div class="info-group">
            <span class="label">Кодовое имя:</span> 
            <span>«Неуловимый Крот»</span>
        </div>

        <div class="info-group">
            <span class="label">Особые приметы:</span> 
            <span>Пьет чай без сахара, программирует во сне, не моргает.</span>
        </div>

        <div class="info-group">
            <span class="label">Тайная деятельность:</span> 
            <span>Подозревается в несанкционированном поедании чужих конфет в офисе и взломе микроволновок.</span>
        </div>

        <div class="info-group">
            <span class="label">Текущий статус:</span> 
            <span class="status-danger">В МЕЖДУНАРОДНОМ РОЗЫСКЕ</span>
        </div>
    </div>

</body>
</html>
