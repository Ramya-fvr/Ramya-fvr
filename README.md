<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Historical Places in India</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#taj-mahal">Taj Mahal</a></li>
                <li><a href="#red-fort">Red Fort</a></li>
                <li><a href="#qutub-minar">Qutub Minar</a></li>
                <li><a href="#hampi">Hampi</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="taj-mahal">
            <h2>Taj Mahal</h2>
            <img src="taj-mahal.jpg" alt="Taj Mahal">
            <p>The Taj Mahal is a white marble mausoleum located in Agra, Uttar Pradesh. It was built by Mughal Emperor Shah Jahan in memory of his wife Mumtaz Mahal.</p>
        </section>
        <section id="red-fort">
            <h2>Red Fort</h2>
            <img src="red-fort.jpg" alt="Red Fort">
            <p>The Red Fort is a historic fort located in Delhi. It was built by Mughal Emperor Shah Jahan in 1648 and served as the imperial palace of the Mughal Empire.</p>
        </section>
        <section id="qutub-minar">
            <h2>Qutub Minar</h2>
            <img src="qutub-minar.jpg" alt="Qutub Minar">
            <p>The Qutub Minar is a minaret located in Delhi. It was built by Qutb-ud-din Aibak in 1192 and is the tallest minaret in India.</p>
        </section>
        <section id="hampi">
            <h2>Hampi</h2>
            <img src="hampi.jpg" alt="Hampi">
            <p>Hampi is a UNESCO World Heritage Site located in Karnataka. It was the capital of the Vijayanagara Empire in the 14th century.</p>
        </section>
    </main>
    <footer>
        <p>Designed and Developed by [Your Name]</p>
    </footer>
</body>
</html>
```

CSS (in style.css file):

```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1em;
    text-align: center;
    position: fixed;
    top: 0;
    width: 100%;
}

header nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: space-between;
}

header nav ul li {
    margin-right: 20px;
}

header nav a {
    color: #fff;
    text-decoration: none;
}

main {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 20px;
    padding: 5em 2em 2em 2em;
}

section {
    background-color: #f7f7f7;
    padding: 1em;
    border: 1px solid #ddd;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h2 {
    margin-top: 0;
}

img {
    width: 100%;
    height: 150px;
    object-fit: cover;
    margin-bottom: 10px;
}

footer {
    background-color: #333;
    color: #fff;
    padding: 1em;
    text-align: center;
    position: fixed;
    bottom: 0;
    width: 100%;
}

@media (max-width: 768px) {
    main {
        grid-template-columns: 1fr;
    }
    section {
        margin-bottom: 20px;
    }
}

