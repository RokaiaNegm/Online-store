<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Online Fashion Store</title>
    <link rel="stylesheet"  href="style.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.6.0/css/fontawesome.min.css">
</head>
<body>
    <header>
        <div class="top-bar">
            <p> 🎁 FREE SHIPPING ON ORDERS OVER 700 $</p>
        </div>
        <nav class="navbar">
            <div class="logo">AURORA</a> </div>
            
            <ul class="nav-links" id="MenueItems">
                <li><a href="Home">Home</a></li>
                <li><a href="Products">Products</a></li>
                <li><a href="Shop">Shop</a></li>
            </ul>
            <div class="search-bar">
                <input type="text" placeholder="Search: dresses, sets, ...">
            </div>
            <div class="icons">
                <a href="Login"><img src="user.png" width="35" height="35"></a>
                <a href="Favorites"><img src="love.png" width="32" height="35"></a>
                <a href="shopping-bag.png"><img src="shopping-bag.png" width="35" height="35"></a>
                <a href="menue"><img src="menu-bar.png" width="38" height="39" class="menue" onclick="menuetoggle()"></a>
            </div>
        </nav>
    <div class="hero-section">
        <div class="sentence">
            <h3> Elevate Your Style  </h3>
            <p> Embrace the Elegance Discover Fashion That Defines You! </p>
            <a href=""class="btn" > Shop &#8594;  </a>
        </div> 
    </div>
    </header>

    <!---------featured categories-->
    <div class="COLLECTIONS">FEATURED PRODUCTS </div>
    <div class="categories" >
    
      <div class="photos">
      <div class="imo" ><img src="Images/K (1).jpeg" > <img src="Images/B&W (4).jpeg" > <img src="Images/U (1).jpeg" ></div>
      </div>
    </div>

    <!-----------Best Sellers-->    
    <div class="title">BEST SELLERS</div> 
    <div class="best-seller" >
        <div class="col"><img src="Images/BR (2).jpeg" >
        <h4>SEREN Coat</h4>
        <div class="rating">
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            
        </div>
        <p>USD 1775,00</p>
        </div>

        <div class="col"><img src="Images/N (3).jpeg" >
            <h4>Shaped Blazer-Tan Check</h4>
            <div class="rating">
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
            </div>
            <p>USD 2249,00</p>
            </div>
        
        <div class="col"><img src="Images/Wrap (2).jpeg" >
            <h4>Tie Front Roll Dress</h4>
            <div class="rating">
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
            </div>
            <p>USD 1960,10</p>
            </div>

        <div class="col"><img src="Images/P&W (3).jpeg" >
                <h4>FIDELIA PINK SLIM FIT THREE PIECE SET</h4>
                <div class="rating">
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                </div>
                <p>USD 2859,07</p>
                </div>
    </div>

    <!------footer------>
    <footer class="footer">
    <div class="footer-container"> 
        <div class="footer-section">
            <h3>Download Our App</h3>
            <p>Download App for Android and iOS mobile phone.</p>
            <div class="app-buttons">
                <img src="play store.jpg" alt="Google Play">
                <img src="app-store.jpg" alt="App Store">
            </div>

        <div class="footer-section"><img src="logo.jpeg"  > 
            <p >
                Hijab wear blends modesty with modern style, allowing individuals
                to showcase their personality and values while embracing creativity and tradition,
                making every outfit a statement of self-expression and elegance.
            </p>
        </div>
        <div class="footer-section">
            <h3>Follow Us</h3>
            <ul>
                <li><a href="facebook.png">Facebook</a></li>
                <li><a href="twitter.png">Twitter</a></li>
                <li><a href="instagram.png">Instagram</a></li>
             
            </ul>
        </div>
        
        </div>    
    </footer>





 <!------js for toggle------>   
    

    
    
</body>
</html>









*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
    flex-direction: row;

}

/* Top Bar */
.top-bar {
    background: black;
    color: white;
    text-align: center;
    padding: 10px 0;
    font-size: 14px;
}

/* Navbar */
.navbar {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 15px 5%;
    background: #a89171;
    box-shadow: 0 1px 10px rgba(0, 0, 0, 0.1);
}

.logo {
    font-size: 24px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    font-weight: bold;
    padding: 0 0 0 0;
    margin-right: 70;
    margin-right: 90;
    top: 0;
}

.nav-links {
    list-style: none;
    display: flex;
    gap: 20px;
}

.nav-links li {
    display: inline;
}

.nav-links a {
    text-decoration: none;
    color: black;
    font-weight: 600;
}

.search-bar input {
    padding: 8px;
    width: 250px;
    border: 1px solid #ccc;
    border-radius: 20px;
    outline: none;
}

.icons a {
    margin-left: 15px;
    text-decoration: none;
    color: black;
    font-weight: bold;
}
.hero-section {
    width: 100vw;
    height: 100vh;
    background-image: url('background.jpeg'); 
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
}
.sentence {
    position: absolute;
    top: 60%;
    left: 50%;
    transform: translateY(-50%);
    color: white;
    max-width: 400px;
}
.sentence h3{
    display: flex;
    flex-wrap: wrap;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-size: 2.5rem;
    font-weight: bold;
}
.sentence p{
    flex-basis: 50%;
    min-width: 300;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-size: 1.2rem;
    margin: 10px 0;
}
.btn {
    display: inline-block;
    padding: 10px 20px;
    background-color: #532506; /* Change to match your theme */
    color: white;
    text-decoration: none;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-weight: bold;
    border-radius: 5px;
    margin-top: 10px;
    transition: 0.3s ease;
    
}

.btn:hover {
    background-color: #301502; 
}

.COLLECTIONS {
    align-items: center;
    padding-left: 40%;
    padding-top: 2%;
    font-size: 1.7rem;
    font-weight: bold;
    color: #271702;
}
.categories {
    margin: 65px 0;
    display: inline-flex;
    padding-left: 10%;
}
.imo{
    flex-basis: 40%;
    min-width: 250px;
    margin-bottom: 10px;
}
.imo img{
    width: 30%;
}


  /* Best seller section  */
.title {
    align-items: center;
    position: relative;
    left: 40%;
    top: 205%;
    font-size: 1.7rem;
    font-weight: bold;
    color: #140d02;
} 
.best-seller {
    display: flex; 
    justify-content: space-between;   
    flex-wrap: wrap; 
    padding: 10px;
    max-width: 90%;
    margin: 0 auto;
}



.col{
    flex-basis: 25%;
    flex: 1;
    padding: 10px;
    min-width: 200px;
    margin-bottom: 50px;
    transition: transform 0.5s;
}
.col img{
    width: 100%;
}
.col:hover{
    transform: translate(-5px);
}
 
/* .......footer.*/

.footer {
    background-color: #140d08;
    color: white;
    padding: 40px 0;
    text-align: center;
}

.footer-container {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    max-width: 1100px;
    margin: auto;
    flex-wrap: wrap;
}
.footer-section {
    flex: 1;
    padding: 10px;
    min-width: 200px;
}
.footer-section p {
    font-size: 14px;
    color: #ccc;
}

.footer-section img {
    max-width: 150px;
    margin: 10px 0;
}

.app-buttons img {
    width: 120px;
    margin: 5px;
    cursor: pointer;
}
.footer-section h3 {
    font-size: 18px;
    margin-bottom: 10px;
}

@media only screen and (max-width:800px) {
    nav ul{
        position: absolute;
        top: 70px;
        left: 0;
        background-color: #333;
    }
    nav ul li{
        display: block;
        margin-right: 50px;
        margin-top:10px ;
        margin: bottom 10px; 
    }
    nav ul li a{
        color: #fff;

    .menue{
        display: block;
        cursor: pointer;

    }
    }
}

![image](https://github.com/user-attachments/assets/0a2ad455-ddba-44b7-ae02-d3ece1a338ed)
![image](https://github.com/user-attachments/assets/5ba0b536-e8f4-4a72-9f34-4b3e43d7a07a)


