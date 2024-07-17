#  CSS_project
# Design a Website like the one given below using CSS.
# AIM
 Design a Website like the one given below using CSS.
# PROGRAM:
# ROOP.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RoopTech</title>
    <link rel="stylesheet" href="css/roop.css">
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">ROOPTECH</div>
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Products</a></li>
                    <li><a href="#">People</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
            </nav>
            <div class="search">
                <input type="text" placeholder="Enter to Search">
                <button>Search</button>
            </div>
        </div>
    </header>
    <main>
        <div class="hero">
            <h1>"Driving progress through<br> precision engineering and<br> boundless creativity."</h1>
            <div class="buttons">
                <button class="login">Log In</button>
                <button class="signup">Sign Up</button>
            </div>
        </div>
    </main>
    <footer>
        <p>DESIGNED AND DEVELOPED BY POOJA V (212221040122)</p>
    </footer>
</body>
</html>
```
# ROOP.CSS
```
/* styles.css */

body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #000;
    color: #fff;
    background-size: cover;
}

.container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
}

.logo {
    font-size: 24px;
    font-weight: bold;
    color: #00f3ff;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    display: flex;
    gap: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
}

.search {
    display: flex;
    align-items: center;
}

.search input {
    padding: 5px;
    border: none;
    border-radius: 5px 0 0 5px;
}

.search button {
    padding: 6px 10px;
    border: none;
    border-radius: 0 5px 5px 0;
    background-color: #00f3ff;
    color: #000;
    cursor: pointer;
}

.hero {
    text-align: center;
    padding: 100px 20px;
    
}

.hero h1 {
    font-size: 36px;
    margin-bottom: 40px;
}

.buttons {
    display: flex;
    justify-content: center;
    gap: 20px;
}

button {
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    font-size: 16px;
    cursor: pointer;
}

.login {
    background-color: #f00;
    color: #fff;
}

.signup {
    background-color: #0f0;
    color: #fff;
}

footer {
    text-align: center;
    padding: 10px 0;
    background-color: #f00;
    color: #fff;
    position: fixed;
    width: 100%;
    bottom: 0;
}
```
# OUTPUT
![Screenshot (148)](https://github.com/user-attachments/assets/9396f12b-2c1f-4304-8cc6-b6dec4225e04)
# RESULT
   Thus the program was executes successfully.
