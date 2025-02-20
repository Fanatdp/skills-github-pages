<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Innovative Solution - Каталог</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #444;
            color: white;
            padding: 15px;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
        }
        .category {
            background: white;
            margin: 20px;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
        }
        .product {
            display: flex;
            align-items: center;
            margin-top: 10px;
        }
        .product img {
            width: 150px;
            height: auto;
            margin-right: 15px;
            border-radius: 5px;
        }
        button {
            background-color: #28a745;
            color: white;
            border: none;
            padding: 10px 15px;
            cursor: pointer;
            border-radius: 5px;
            transition: 0.3s;
        }
        button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>
    <header>
        <h1>Innovative Solution</h1>
        <nav>
            <ul>
                <li><a href="#catalog">Каталог</a></li>
                <li><a href="#calculator">Калькулятор</a></li>
                <li><a href="#contacts">Контакти</a></li>
                <li><a href="#admin">Адмін-панель</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="catalog">
        <h2 style="text-align:center;">Каталог продукції</h2>
        
        <div class="category">
            <h3>Вікна</h3>
            <div class="product">
                <img src="A_high-quality_modern_PVC_window_with_double-glaze.png" alt="Металопластикове вікно">
                <div>
                    <h4>Металопластикове вікно</h4>
                    <p>Енергоефективне вікно з подвійним склопакетом, забезпечує відмінну тепло- та шумоізоляцію.</p>
                    <button>Детальніше</button>
                </div>
            </div>
        </div>
        
        <div class="category">
            <h3>Двері</h3>
            <div class="product">
                <img src="A_modern,_secure_steel_entry_door_with_a_dark_wood.png" alt="Вхідні двері">
                <div>
                    <h4>Вхідні двері</h4>
                    <p>Надійні металеві двері з темним дерев'яним покриттям, забезпечують високий рівень безпеки.</p>
                    <button>Детальніше</button>
                </div>
            </div>
        </div>
        
        <div class="category">
            <h3>Скло та дзеркала</h3>
            <div class="product">
                <img src="A_high-quality_tempered_glass_panel_with_polished_.png" alt="Загартоване скло">
                <div>
                    <h4>Загартоване скло</h4>
                    <p>Міцне скло для безпеки та дизайнерських рішень, стійке до ударів та перепадів температур.</p>
                    <button>Детальніше</button>
                </div>
            </div>
        </div>
    </section>
    
    <section id="calculator">
        <h2 style="text-align:center;">Калькулятор вартості</h2>
        <form style="text-align:center;">
            <label for="size">Розмір (см):</label>
            <input type="number" id="size" name="size">
            <label for="material">Матеріал:</label>
            <select id="material" name="material">
                <option value="wood">Дерево</option>
                <option value="metal">Метал</option>
                <option value="plastic">Пластик</option>
            </select>
            <button type="submit">Розрахувати</button>
        </form>
    </section>
    
    <section id="admin">
        <h2 style="text-align:center;">Адмін-панель</h2>
        <p style="text-align:center;">Тут можна управляти замовленнями та клієнтами. Додавати та редагувати товари може лише адміністратор.</p>
        <h3 style="text-align:center;">Авторизація</h3>
        <form style="text-align:center;">
            <label for="username">Логін:</label>
            <input type="text" id="username" name="username">
            <label for="password">Пароль:</label>
            <input type="password" id="password" name="password">
            <button type="submit">Увійти</button>
        </form>
    </section>
    
    <section id="contacts">
        <h2 style="text-align:center;">Контакти</h2>
        <p style="text-align:center;">Телефон: +38 095 770 70 71</p>
        <p style="text-align:center;">Email: budulakoleg@gmail.com </p>
    </section>
</body>
</html>
