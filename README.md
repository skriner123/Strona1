<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мій сайт з трьома стовпцями</title>
    <style>
        .container {
            display: flex;
            justify-content: space-around;
            margin-top: 20px;
        }
        .column {
            width: 30%; /* Ширина кожного стовпця */
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            position: relative; /* Для абсолютного позиціонування підстовпців */
        }
        .sub-column {
            margin-top: 10px;
            padding: 5px;
            border: 1px solid #aaa;
            border-radius: 5px;
        }
        .bottom-text {
            text-align: center;
            margin-top: 20px;
        }
        .extra-columns {
            display: flex;
            justify-content: space-around;
            margin-top: 20px;
        }
        .extra-column {
            width: 22%; /* Ширина для нових стовпців */
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .additional-columns {
            display: flex;
            justify-content: space-around;
            margin-top: 20px;
        }
        .additional-column {
            width: 22%; /* Ширина для нових стовпців */
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <h1>Kolia Burak</h1>
    <div class="container">
        <div class="column">
            <h2>1</h2>
            <p>Текст для першого стовпця.</p>
            <div class="sub-column">
                <h3>Підстовпець 1</h3>
                <p>Текст для підстовпця 1.1.</p>
            </div>
            <div class="sub-column">
                <h3>Підстовпець 2</h3>
                <p>asd.</p>
            </div>
        </div>
        <div class="column">
            <h2>2</h2>
            <p>asd.</p>
            <div class="sub-column">
                <h3>2</h3>
                <p>fds.</p>
            </div>
            <div class="sub-column">
                <h3>2</h3>
                <p>fds.</p>
            </div>
        </div>
        <div class="column">
            <h2>3</h2>
            <p>Текст для третього стовпця.</p>
            <div class="sub-column">
                <h3>3</h3>
                <p>fds.</p>
            </div>
            <div class="sub-column">
                <h3>3</h3>
                <p>fds.</p>
            </div>
        </div>
    </div>
    
    <div class="bottom-text">
        <p>ewq</p>
        <p>eqw</p>
        <p>eqw</p>
    </div>

    <div class="extra-columns">
        <div class="extra-column">
            <h2>1</h2>
            <p>Перше речення в додатковому стовпці 1.</p>
            <p>Друге речення в додатковому стовпці 1.</p>
        </div>
        <div class="extra-column">
            <h2>2</h2>
            <p>Перше речення в додатковому стовпці 2.</p>
            <p>Друге речення в додатковому стовпці 2.</p>
        </div>
        <div class="extra-column">
            <h2>3</h2>
            <p>Перше речення в додатковому стовпці 3.</p>
            <p>Друге речення в додатковому стовпці 3.</p>
        </div>
        <div class="extra-column">
            <h2>4</h2>
            <p>Перше речення в додатковому стовпці 4.</p>
            <p>Друге речення в додатковому стовпці 4.</p>
        </div>
    </div>

    <div class="additional-columns">
        <div class="additional-column">
            <h2>5</h2>
            <p>Перше речення .</p>
            <p>Друге речення .</p>
            <p>Третє речення .</p>
        </div>
        <div class="additional-column">
            <h2>6</h2>
            <p>Перше речення в .</p>
            <p>Друге речення в .</p>
            <p>Третє речення в .</p>
        </div>
    </div>
</body>
</html>
