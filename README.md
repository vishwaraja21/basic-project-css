## home
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Home</title>
        <link rel="stylesheet" href="main.css">
    </head> 
    <body>
        <header class="top-header">
            <h1 >ROOPTECH</h1>
            
            <nav>
                <ul id="bar">
                    <li><a href="#" >Home</a></li>
                    <li><a href="product.html">Product</a></li>
                    <li><a href="people.html">people</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
            </nav>
    
            <div class="search-button">
            
                <input  type="text" placeholder="Enter to search">
                <button class="button">search</button>
            
            </div>
        
        </header>

     <div class="content">
        <main>
            <h1>"Driving progress through precision <br>
                engineering and boundless creativity"</h1>
            <div class="buttons">
                <button class="btn btn-login">Log In</button>
                <button class="btn btn-signup">Sign Up</button>
            </div>
        </main>
    </div>
    
        <footer>DESIGNED AND DEVELOPED BY Vishwaraja R (212221220060) </footer> 
    </body>
</html>
```

##home.css
```
 
  *{
    text-decoration: none;
    font-family:sans-serif;
    /* background: linear-gradient(to top,rgba(0,0,0,5)),url(background.jpg); */
    background-position: center;
  }
  .top-header{
    padding-right: 15px;
    padding-left: 15px;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  li{
    list-style: none;
    display: inline-block;
    justify-content: space-between;
    color: white;
    margin: 20px;
  }
  /* div{
    justify-content: flex-end;

  } */
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #1d1a1a;
    color: #fff;
}
  h1{
    color: beige;
  }
  a{
    color: white;
  }
.content{
    color: white;
}
.search-button input {
    padding: 5px;
    border: none;
    border-radius: 5px 0 0 5px;
}
.search-button button{
    padding: 5px 10px;
    background-color: #00ffff;
    border: none;
    border-radius: 0 5px 5px 0;
    cursor: pointer;

}
.content {
    text-align: center;
    padding: 100px 20px;
}
.buttons {
    margin-top: 30px;
}
.btn-login {
    background-color: #ff0000;
    color: #fff;
}
.btn-signup {
    background-color: #00ff00;
    color: #fff;
}


footer {
    background-color: #ff0000;
    color: #fff;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
h1 {
    font-size: 36px;
    margin-bottom: 30px;
}
.btn {
    padding: 10px 20px;
    margin: 0 10px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
}
.product {
    border: 1px solid #333;
    border-radius: 10px;
    padding: 15px;
    text-align: center;
}
.product h2 {
    color: #ff0000;
    margin-top: 0;
}

```

##contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home</title>
    <link rel="stylesheet" href="contact.css">
</head>
<body>
    <header class="top-header">
            <h1 >ROOPTECH</h1>
            
            <nav>
                <ul id="bar">
                    <li><a href="home.html" >Home</a></li>
                    <li><a href="product.html">Product</a></li>
                    <li><a href="people.html">people</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
            </nav>
    
            <div class="search-button">
            
                <input  type="text" placeholder="Enter to search">
                <button class="button">search</button>
            
            </div>
        
        </header>
        <main>
            <div class="contact-form">
                <h2>Contact Us</h2>
                <input type="text" placeholder="Your Name">
                <input type="email" placeholder="Your Email">
                <button>Submit</button>
            </div>
            <div class="contact-info">
                <h2>Contact Information</h2>
                <p><span>Address:</span> 3RD Floor, Tower 12, FCA Building No.18,ROOP DEVELOP CITY Phase-I SECUNDERABAD HR IN 1888546</p>
                <p><span>Email:</span> rooptech.official@gmail.com</p>
                <p><span>Phone:</span> 1234567890</p>
            </div>
        </main>
    </main>
    <footer>DESIGNED AND DEVELOPED BY Vishwaraja R (212221220060) </footer> 
    
</body>
</html>

```
##contact.css
```
 
  *{
    text-decoration: none;
    font-family:sans-serif;
    /* background: linear-gradient(to top,rgba(0,0,0,5)),url(background.jpg); */
    background-position: center;
  }
  .top-header{
    padding-right: 15px;
    padding-left: 15px;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  li{
    list-style: none;
    display: inline-block;
    justify-content: space-between;
    color: white;
    margin: 20px;
  }
  /* div{
    justify-content: flex-end;

  } */
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #1d1a1a;
    color: #fff;
}
  h1{
    color: beige;
  }
  a{
    color: white;
  }
.content{
    color: white;
}
.search-button input {
    padding: 5px;
    border: none;
    border-radius: 5px 0 0 5px;
}
.search-button button{
    padding: 5px 10px;
    background-color: #ff0000;
    border: none;
    border-radius: 0 5px 5px 0;
    cursor: pointer;

}
.content {
    text-align: center;
    padding: 100px 20px;
}
.buttons {
    margin-top: 30px;
}
.btn-login {
    background-color: #ff0000;
    color: #fff;
}
.btn-signup {
    background-color: #00ff00;
    color: #fff;
}


footer {
    background-color: #ff0000;
    color: #fff;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
h1 {
    font-size: 36px;
    margin-bottom: 30px;
}
.btn {
    padding: 10px 20px;
    margin: 0 10px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
}
.product {
    border: 1px solid #333;
    border-radius: 10px;
    padding: 15px;
    text-align: center;
}
.product h2 {
    color: #ff0000;
    margin-top: 0;
}
main {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    gap: 20px;
    padding: 20px;
}

```
##people.css
```
 
  *{
    text-decoration: none;
    font-family:sans-serif;
    /* background: linear-gradient(to top,rgba(0,0,0,5)),url(background.jpg); */
    background-position: center;
  }
  .top-header{
    padding-right: 15px;
    padding-left: 15px;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  li{
    list-style: none;
    display: inline-block;
    justify-content: space-between;
    color: white;
    margin: 20px;
  }
  /* div{
    justify-content: flex-end;

  } */
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #1d1a1a;
    color: #fff;
}
  h1{
    color: beige;
  }
  a{
    color: white;
  }
.content{
    color: white;
}
.search-button input {
    padding: 5px;
    border: none;
    border-radius: 5px 0 0 5px;
}
.search-button button{
    padding: 5px 10px;
    background-color: #ff0000;
    border: none;
    border-radius: 0 5px 5px 0;
    cursor: pointer;

}
.content {
    text-align: center;
    padding: 100px 20px;
}
.buttons {
    margin-top: 30px;
}
.btn-login {
    background-color: #ff0000;
    color: #fff;
}
.btn-signup {
    background-color: #00ff00;
    color: #fff;
}


footer {
    background-color: #ff0000;
    color: #fff;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
h1 {
    font-size: 36px;
    margin-bottom: 30px;
}
.btn {
    padding: 10px 20px;
    margin: 0 10px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
}
.product {
    border: 1px solid #333;
    border-radius: 10px;
    padding: 15px;
    text-align: center;
}
.product h2 {
    color: #ff0000;
    margin-top: 0;
}

main {
    padding: 20px;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    min-height: 70vh;
}
.person {
    text-align: center;
    margin: 20px;
}
.person img {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    /* object-fit: cover; */
}
.person h3 {
    margin: 10px 0 5px;
}
.person p {
    margin: 0;
    color: #ff0000;
}
```
##people.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home</title>
    <link rel="stylesheet" href="people.css">
</head>
<body>
    <header class="top-header">
        <h1 >ROOPTECH</h1>
        
        <nav>
            <ul id="bar">
                <li><a href="home.html" >Home</a></li>
                <li><a href="product.html">Product</a></li>
                <li><a href="people.html">people</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>

        <div class="search-button">
        
            <input  type="text" placeholder="Enter to search">
            <button class="button">search</button>
        
        </div>
    
    </header>
    
    <main>
        <div class="person">
            <img src="images/bill gate.png" alt="Roop Sagar">
            <h3>BILL GATE</h3>
            <p> Co-founder of Microsoft</p>
        </div>
        <div class="person">
            <img src="images/elon.png" alt="Ratan Tata">
            <h3>ELON MUSK</h3>
            <p>CEO of SpaceX and Tesla</p>
        </div>
        <div class="person">
            <img src="images/sundar.png" alt="Steve Jobs">
            <h3>SUNDAR PICHAI</h3>
            <p>Director of google</p>
        </div>
        <div class="person">
            <img src="images/tata owner.png" alt="Sundar">
            <h3>RATAN TATA</h3>
            <p>CEO,CO-founder</p>
        </div>
        
    </main>
    <footer>DESIGNED AND DEVELOPED BY Vishwaraja R (212221220060) </footer> 
    
</body>
</html>
```
##product.css
```
 
  *{
    text-decoration: none;
    font-family:sans-serif;
    /* background: linear-gradient(to top,rgba(0,0,0,5)),url(background.jpg); */
    background-position: center;
  }
  .top-header{
    padding-right: 15px;
    padding-left: 15px;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  li{
    list-style: none;
    display: inline-block;
    justify-content: space-between;
    color: white;
    margin: 20px;
  }
  /* div{
    justify-content: flex-end;

  } */
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #1d1a1a;
    color: #fff;
}
  h1{
    color: beige;
  }
  a{
    color: white;
  }
.content{
    color: white;
}
.search-button input {
    padding: 5px;
    border: none;
    border-radius: 5px 0 0 5px;
}
.search-button button{
    padding: 5px 10px;
    background-color: #ff0000;
    border: none;
    border-radius: 0 5px 5px 0;
    cursor: pointer;

}
.content {
    text-align: center;
    padding: 100px 20px;
}
.buttons {
    margin-top: 30px;
}
.btn-login {
    background-color: #ff0000;
    color: #fff;
}
.btn-signup {
    background-color: #00ff00;
    color: #fff;
}


footer {
    background-color: #ff0000;
    color: #fff;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
h1 {
    font-size: 36px;
    margin-bottom: 30px;
}
.btn {
    padding: 10px 20px;
    margin: 0 10px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
}
.product {
    border: 1px solid #333;
    border-radius: 10px;
    padding: 15px;
    text-align: center;
}
.product h2 {
    color: #ff0000;
    margin-top: 0;
}
main {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    gap: 20px;
    padding: 20px;
}

```
##product.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home</title>
    <link rel="stylesheet" href="product.css">
</head>
<body>
    <header class="top-header">
            <h1 >ROOPTECH</h1>
            
            <nav>
                <ul id="bar">
                    <li><a href="home.html" >Home</a></li>
                    <li><a href="#">Product</a></li>
                    <li><a href="people.html">people</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
            </nav>
    
            <div class="search-button">
            
                <input  type="text" placeholder="Enter to search">
                <button class="button">search</button>
            
            </div>
        
        </header>
    <main>
        <div class="product">
            <h2>C++</h2>
            <p>Efficiency Redefined: Harnessing the Power of C++ for Next-Level Development</p>
        </div>
        <div class="product">
            <h2>C</h2>
            <p>Crafting Performance: Where Precision Meets C Programming</p>
        </div>
        <div class="product">
            <h2>JAVASCRIPT</h2>
            <p>Scripting Success: Unleashing the Power of JavaScript</p>
        </div>
        <div class="product">
            <h2>PHP</h2>
            <p>PHP is a server side scripting language that is embedded in HTML.</p>
        </div>
        <div class="product">
            <h2>PYTHON</h2>
            <p>Unlocking Innovation: Python Paving the Way to Progress.</p>
        </div>
        <div class="product">
            <h2>SQL</h2>
            <p>SQL is a standard language for accessing and manipulating databases.</p>
        </div>
        <div class="product">
            <h2>SHELL</h2>
            <p>Shell can be accessed by users using a command line interface.</p>
        </div>
        <div class="product">
            <h2>RUBY</h2>
            <p>Ruby: Where Simplicity Meets Power in Programming</p>
        </div>
        <div class="product">
            <h2>TYPESCRIPT</h2>
            <p>Empower Your Code: Embrace the Future with TypeScript</p>
        </div>
        <div class="product">
            <h2>F#</h2>
            <p>F# is an Open-source programming language with a lot of features.</p>
        </div>
    </main>
    <footer>DESIGNED AND DEVELOPED BY Vishwaraja R (212221220060) </footer> 
    
</body>
</html>
```
