<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Styled Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header id="main-header">
        <h1>Welcome to My Page</h1>
        <p>This is a styled HTML page.</p>
    </header>

    <div class="container">
        <section class="content">
            <h2>About Us</h2>
            <p>We are a company dedicated to providing amazing services.</p>
            <img src="placeholder.jpg" alt="Company Logo">
        </section>

        <section class="content">
            <h2>Our Services</h2>
            <ul>
                <li>Service 1</li>
                <li>Service 2</li>
                <li>Service 3</li>
            </ul>
        </section>
    </div>

    <footer id="main-footer">
        <p>&copy; 2024 My Company</p>
    </footer>
</body>
</html>
```css
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

#main-header {
    background-color: #355e3b;
    color: white;
    padding: 20px;
    text-align: center;
    border-bottom: 3px solid #2a4d2e;
}

.container {
    max-width: 1000px;
    margin: 20px auto;
    padding: 0 20px;
}

.content {
    background-color: white;
    padding: 20px;
    margin-bottom: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    border: 1px solid #e0e0e0;
}

.content h2 {
    color: #355e3b;
    margin-bottom: 10px;
    font-size: 24px;
}

.content ul {
    list-style-type: disc;
    padding-left: 20px;
}

.content li{
    margin-bottom: 5px;
}

.content img {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
    margin-top: 15px;
    border: 1px solid #ccc;
    padding: 5px;
    background-color: #f0f0f0;
}

#main-footer {
    background-color: #355e3b;
    color: white;
    text-align: center;
    padding: 10px;
    margin-top: 20px;
    border-top: 3px solid #2a4d2e;
}
