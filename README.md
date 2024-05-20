# my-website


body {
    font-family: Arial, sans-serif;
    background: url('images/background.jpg') no-repeat center center fixed;
    background-size: cover;
    margin: 0;
    padding: 0;
}

.background {
    background-color: rgba(255, 255, 255, 0.8);
    padding: 20px;
}

header {
    text-align: center;
    background-color: #333;
    color: white;
    padding: 10px 0;
}

header nav ul {
    list-style: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 10px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
}

main {
    padding: 20px;
}

marquee {
    background-color: yellow;
    color: red;
    padding: 10px;
    margin: 20px 0;
}


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="background">
        <header>
            <h1>About Us</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="page2.html">Page 2</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="https://www.example.com">External Link</a></li>
                </ul>
            </nav>
        </header>
        <main>
            <section>
                <h2>Our Story</h2>
                <p>This page contains information about us.</p>
            </section>
        </main>
    </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="background">
        <header>
            <h1>Welcome to My Website</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="page2.html">Page 2</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="https://www.example.com">External Link</a></li>
                </ul>
            </nav>
        </header>
        <main>
            <section>
                <h2>Introduction</h2>
                <p>This is the main page of the website. You will find various examples of HTML elements here.</p>
                <img src="images/example.jpg" alt="Example Image">
                <marquee>This text is scrolling across the screen!</marquee>
            </section>
            <section>
                <h2>Table Example</h2>
                <table border="1">
                    <tr>
                        <th>Header 1</th>
                        <th>Header 2</th>
                        <th>Header 3</th>
                    </tr>
                    <tr>
                        <td>Data 1</td>
                        <td>Data 2</td>
                        <td>Data 3</td>
                    </tr>
                    <tr>
                        <td>Data A</td>
                        <td>Data B</td>
                        <td>Data C</td>
                    </tr>
                </table>
            </section>
            <section>
                <h2>List Example</h2>
                <ul>
                    <li>Item 1</li>
                    <li>Item 2</li>
                    <li>Item 3</li>
                </ul>
            </section>
            <section>
                <h2>HTML5 Features</h2>
                <article>
                    <h3>Video Example</h3>
                    <iframe width="560" height="315" src="(https://www.youtube.com/watch?v=sjkrrmBnpGE)" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                </article>
            </section>
        </main>
    </div>
</body>
</html>

