<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Мой сайт</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <h1>Добро пожаловать на мой сайт!</h1>
  <div id="observations">
    <h2>Наблюдения 1.1</h2>
    <p>Результаты наблюдений: нету</p>
    <button onclick="alert('Скоро будут результаты наблюдений!')">Посмотреть</button>
  </div>
</body>
</html>

body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f4f4f4;
}

h1 {
  color: #333;
  text-align: center;
  margin-top: 20px;
}

#observations {
  padding: 20px;
  margin: 20px;
  background-color: #fff;
  border: 1px solid #ccc;
  border-radius: 5px;
}

button {
  padding: 10px 20px;
  margin-top: 10px;
  background-color: #007BFF;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

button:hover {
  background-color: #0056b3;
}

