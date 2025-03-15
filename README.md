<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>StoryHub</title>
    <style>
    body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #0f0f2d; /* Change this color to whatever you like */
            color: white; /* This ensures the text is visible on a dark background */
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1rem;
            text-align: center;
        }
          header img {
            width: 50px;
            height: 50px;
        }
        nav ul {
            list-style: none;
            padding: 0;
            text-align: center;
        }
        nav ul li {
            display: inline;
            margin: 0 1rem;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        section {
            padding: 2rem;
            margin: 1rem 0;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            color: #333; /* This ensures the text is visible on a light background */
        }
        .book-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px;
            margin: 20px 0;
        }
        .book {
            background-color: white;
            color: black;
            padding: 10px;
            border-radius: 10px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .book img {
            width: 100%;
            border-radius: 10px;
        }
        .friends-list {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }
        .friend {
            background-color: #eee;
            padding: 10px;
            border-radius: 5px;
            display: flex;
            align-items: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .friend img {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            margin-right: 10px;
        }
        .friend.pink { background-color: pink; }
        .friend.light-blue { background-color: lightblue; }
        .friend.blue { background-color: blue; color: white; }
        .friend.light-green { background-color: lightgreen; }
        .home-section {
            background-color: darkblue;
            color: white;
            text-align: center;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .home-section img {
            width: 150px;
            border-radius: 10px;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 1rem;
            text-align: center;
        }
        .feedback-section {
            background-color: #1E3A5B;
            color: #fff;
            text-align: center;
            padding: 20px;
            border-radius: 5px;
        }
        .feedback-section textarea {
            width: 100%;
            height: 100px;
            border: none;
            border-radius: 5px;
            padding: 10px;
            margin: 10px 0;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .feedback-section .contact-info {
            color: #ddd;
            margin-top: 10px;
        }
        button {
            background-color: #333;
            color: #fff;
            border: none;
            border-radius: 5px;
            padding: 10px 20px;
            cursor: pointer;
            margin-top: 10px;
        }
        button:hover {
            background-color: #555;
        }
        a {
            color: #fff;
            text-decoration: none;
        }
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #c0c0c0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1rem;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 1rem;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        section {
            padding: 2rem;
            margin: 1rem 0;
            background-color: #fff;
            border-radius: 5px;
        }
        .book-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px;
            margin: 20px 0;
        }
        .book {
            background-color: white;
            color: black;
            padding: 10px;
            border-radius: 10px;
            text-align: center;
        }
        .book img {
            width: 100%;
            border-radius: 10px;
        }
        .friends-list {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }
        .friend {
            background-color: #eee;
            padding: 10px;
            border-radius: 5px;
            display: flex;
            align-items: center;
        }
        .friend img {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            margin-right: 10px;
        }
        .friend.pink { background-color: pink; }
        .friend.light-blue { background-color: lightblue; }
        .friend.blue { background-color: blue; color: white; }
        .friend.light-green { background-color: lightgreen; }
        .home-section {
            background-color: darkblue;
            color: white;
            text-align: center;
            padding: 20px;
        }
        .home-section img {
            width: 150px;
            border-radius: 10px;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 1rem;
            text-align: center;
        }
        .feedback-section {
            background-color:#ffffff;
            color: #000000;
            text-align: center;
            padding: 20px;
        }
        .feedback-section textarea {
            width: 100%;
            height: 100px;
            border: none;
            border-radius: 5px;
            padding: 10px;
            margin: 10px 0;
        }
        .feedback-section .contact-info {
            color: #808080;
            margin-top: 10px;
        }
         body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1rem;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
            text-align: center;
        }
        nav ul li {
            display: inline;
            margin: 0 1rem;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        section {
            padding: 2rem;
            margin: 1rem 0;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .button {
            display: inline-block;
            padding: 10px 20px;
            font-size: 16px;
            color: white;
            background-color: #333;
            border: none;
            border-radius: 5px;
            text-align: center;
            text-decoration: none;
            cursor: pointer;
            transition: background-color 0.3s;
            margin: 10px 5px;
        }
        .button:hover {
            background-color: #555;
        }
        .explore-section {
            background-color: #1E3A5B;
            color: white;
            padding: 20px;
            text-align: center;
            border-radius: 5px;
        }
        .explore-section h2 {
            margin-top: 0;
        }
          /* General Body Styling */
body {
    background-color: #0d0d2b; /* Dark blue background */
    color: white; /* White text */
    font-family: Arial, sans-serif;
    text-align: center;
    margin: 0;
    padding: 0;
}

/* Container Styling */
.container {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 20px;
    background-color: #1a1a3d; /* Darker blue for the container */
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    max-width: 800px;
    margin: 50px auto;
}

/* Header Styling */
.header {
    display: flex;
    justify-content: space-between;
    width: 100%;
    padding: 10px 20px;
    background-color: #333; /* Dark gray for the header */
    border-radius: 5px;
    margin-bottom: 20px;
}

.header div {
    display: flex;
    align-items: center;
}

.header img {
    width: 20px;
    height: 20px;
    margin-right: 10px;
}

.header h2 {
    font-size: 24px;
    font-weight: bold;
    margin: 0;
}

.header span {
    font-size: 18px;
    cursor: pointer;
    color: #87ceeb; /* Light blue for the "HOME" text */
}

/* Books Styling */
.books {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 20px;
    margin-bottom: 20px;
}

.book {
    width: 150px;
    height: 200px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    transition: transform 0.3s ease;
}

.book:hover {
    transform: scale(1.05);
}

/* Footer Styling */
.footer {
    margin: 20px 0;
    padding: 10px;
    background-color: #333; /* Dark gray for the footer */
    border-radius: 5px;
    width: 100%;
}

.footer span {
    font-size: 18px;
    cursor: pointer;
    color: #87ceeb; /* Light blue for the "SETTINGS" text */
}

/* Button Styling */
.button {
    display: block;
    width: 200px;
    margin: 10px auto;
    padding: 15px;
    border: none;
    border-radius: 5px;
    font-size: 18px;
    font-weight: bold;
    font-family: 'Comic Sans MS', cursive, sans-serif;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

.button:hover {
    opacity: 0.9;
}

.home {
    background-color: #d3d3d3; /* Light gray */
    color: black;
}

.profile-settings {
    background-color: #add8e6; /* Light blue */
    color: black;
}

.language {
    background-color: #87ceeb; /* Sky blue */
    color: black;
}

.data-saver {
    background-color: #ffb6c1; /* Light pink */
    color: black;
}

.notification {
    background-color: #dda0dd; /* Light purple */
    color: black;
}

.privacy-policy {
    background-color: #ffffe0; /* Light yellow */
    color: black;
}

.add-account {
    background-color: #87cefa; /* Light sky blue */
    color: black;
}
/* Stories Section Styling */
#stories {
    background-color: #1a1a3d; /* Dark blue background */
    padding: 40px 20px;
    text-align: center;
    border-radius: 10px;
    margin: 20px auto;
    max-width: 1200px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

#stories h2 {
    font-size: 28px;
    font-weight: bold;
    margin-bottom: 30px;
    color: #87ceeb; /* Light blue for the heading */
}

/* Book Grid Styling */
.book-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    margin-bottom: 30px;
}

.book {
    background-color: #333; /* Dark gray for book cards */
    border-radius: 10px;
    padding: 15px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.book:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
}

.book img {
    width: 100%;
    height: 250px;
    border-radius: 10px;
    object-fit: cover;
    margin-bottom: 10px;
}

.book p {
    font-size: 16px;
    font-weight: bold;
    color: white;
    margin: 0;
}

/* Button Styling */
#stories button {
    display: inline-block;
    margin: 10px;
    padding: 12px 24px;
    font-size: 16px;
    font-weight: bold;
    color: white;
    background-color: #87ceeb; /* Light blue for buttons */
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s ease, transform 0.3s ease;
}

#stories button:hover {
    background-color: #6ca6c1; /* Slightly darker blue on hover */
    transform: scale(1.05);
}

#stories button:active {
    transform: scale(0.95);
}
/* Feedback Section Styling */
#feedback {
    background-color: #1a1a3d; /* Dark blue background */
    padding: 40px 20px;
    text-align: center;
    border-radius: 10px;
    margin: 20px auto;
    max-width: 800px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

#feedback h2 {
    font-size: 28px;
    font-weight: bold;
    margin-bottom: 20px;
    color: #87ceeb; /* Light blue for the heading */
}

#feedback a {
    display: inline-block;
    margin-bottom: 20px;
    padding: 10px 20px;
    font-size: 16px;
    font-weight: bold;
    color: white;
    background-color: #87ceeb; /* Light blue for the button */
    border: none;
    border-radius: 5px;
    text-decoration: none;
    transition: background-color 0.3s ease, transform 0.3s ease;
}

#feedback a:hover {
    background-color: #6ca6c1; /* Slightly darker blue on hover */
    transform: scale(1.05);
}

#feedback textarea {
    width: 100%;
    max-width: 600px;
    height: 150px;
    padding: 15px;
    font-size: 16px;
    font-family: Arial, sans-serif;
    border: 2px solid #87ceeb; /* Light blue border */
    border-radius: 10px;
    background-color: #333; /* Dark gray background */
    color: white;
    resize: none; /* Disable resizing */
    margin-bottom: 20px;
    transition: border-color 0.3s ease;
}

#feedback textarea:focus {
    border-color: #6ca6c1; /* Slightly darker blue on focus */
    outline: none;
}

#feedback .contact-info {
    font-size: 18px;
    font-weight: bold;
    color: #87ceeb; /* Light blue for the text */
    margin: 0;
}
/* Footer Styling */
footer {
    background-color: #333; /* Dark gray background */
    color: white;
    padding: 20px;
    text-align: center;
    border-top: 2px solid #87ceeb; /* Light blue border at the top */
    margin-top: 40px;
}

.footer-content {
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 10px;
}

.footer-content p {
    margin: 0;
    font-size: 14px;
    color: #87ceeb; /* Light blue text for the copyright */
}

.footer-links {
    display: flex;
    gap: 20px;
    margin-top: 10px;
}

.footer-links a {
    color: white;
    text-decoration: none;
    font-size: 14px;
    transition: color 0.3s ease;
}

.footer-links a:hover {
    color: #87ceeb; /* Light blue on hover */
}
 body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }

        .container {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f4f4f4;
        }
          h2 {
            color: #000000; /* Green color */
        }

        .form-container {
            background-color: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            width: 300px;
            text-align: center;
        }

        .form-container h2 {
            margin-bottom: 20px;
        }

        input {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        button {
            width: 100%;
            padding: 10px;
            background-color: #4CAF50;
            border: none;
            border-radius: 4px;
            color: white;
            font-size: 16px;
        }

        button:hover {
            background-color: #45a049;
        }

        .footer {
            margin-top: 20px;
        }

        .footer a {
            text-decoration: none;
            color: #4CAF50;
        }
        
    </style>
</head>
<body>
    <header>
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRbxXw5wLyepRjVtpP4cPShXD4G9EBCkFmSQSDjfSNx0NGv62Q3yNQ-4DGCZ_8TSynX5H4&usqp=CAU" alt="Logo">
        <h1>The StoryHub</h1>
        <nav>
            <ul>
                <li><a href="#login">Login</a></li>
                <li><a href="#signup">Sign-Up</a></li>
                <li><a href="#explore">Explore</a></li>
                <li><a href="#home">Home</a></li>
            </ul>
        </nav>
    </header>
    <body>
<div class="container">
        <div class="form-container">
            <h2>Login</h2>
            <form action="/submit-login" method="POST">
                <input type="email" name="email" placeholder="Email" required><br>
                <input type="password" name="password" placeholder="Password" required><br>
                <button type="submit">Login</button>
            </form>

            <div class="forgot-password">
                <a href="#">Forgot Password?</a>
            </div>

            <div class="footer">
                <p>Don't have an account? <a href="#">Sign Up</a></p>
            </div>
        </div>
    </div>
    </body>
    <div class="container">
        <div class="form-container">
            <h2>Sign Up</h2>
            <form action="/submit-signup" method="POST">
                <input type="text" name="fullname" placeholder="Full Name" required><br>
                <input type="email" name="email" placeholder="Email" required><br>
                <input type="password" name="password" placeholder="Password" required><br>
                <input type="password" name="confirm_password" placeholder="Confirm Password" required><br>
                <button type="submit">Sign Up</button>
            </form>

            <div class="footer">
                <p>Already have an account? <a href="#">Login</a></p>
            </div>
        </div>
    </div>
   <section id="explore" class="explore-section" style="background-color: #f0f8ff; color: #333;">
        <h2>Explore!</h2>
        <a href="#" class="button" style="background-color: lightblue;">Search Stories</a><BR>
        <a href="#" class="button" style="background-color: purple;">Your Stories</a><BR>
        <a href="#" class="button" style="background-color: pink;">Share to Your Friends</a><BR>
        <a href="#" class="button" style="background-color: lightgreen;">Add Stories</a><BR>
        <a href="#" class="button" style="background-color: blue;">Download</a><BR>
        <a href="#" class="button" style="background-color: lightblue;">Feedback</a><BR>
        <button class="button" style="background-color: #333;">Go to Home Page</button>
    </section>
    <section id="SEARCH STORIES" class=" search-section" style="background-color: #f0f8ff; color: #333;">
     
    <div class="container">
        <div class="header">
            <div>
       <h2 style="color: #ffffff;">SEARCH STORIES</h2>

            </div>
            <div>
                <span>HOME</span>
            </div>
        </div>
        <div class="books">
            <img src="data:image/jpeg;base64,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" alt="The Emperor's New Clothes" class="book">
            <img src="data:image/jpeg;base64,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" alt="Reading Under Tree" class="book">
            <img src="data:image/jpeg;base64,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" alt="101 Panchatantra Stories" class="book">
            <img src="data:image/jpeg;base64,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" alt="Jungle Book" class="book">
        </div>
        <div class="footer">
            <span>SETTINGS</span>
        </div>
    </div>
    </section>
 <h2>YOUR STORIES</h2>
        <div class="home-section">
            <button>HOME</button>
            <div class="book-grid">
                <div class="book">
                    <img src="https://offshootbooks.com/cdn/shop/products/91vTgugLZRL.jpg?v=1652863218" alt="The Fool">
                    
                </div>
                <div class="book">
                    <img src="https://5.imimg.com/data5/SELLER/Default/2021/2/SA/IQ/HS/49559104/img-20210211-121925.jpg" alt="The Story School">
                   
                </div>
                <div class="book">
                    <img src="data:image/jpeg;base64,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" alt="When Do Hippos Play?">
                   
                </div>
                <div class="book">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSMd11zJesnrQWuInQJVgnUmKG5AkGWE7-XOg&s" alt="Cinderella">
                  
                </div>
            </div>
            <button>Download or Share</button>
        </div>
    </section>
    <section id="share-friends">
        <h2>Share to Your Friends</h2>
        <div class="friends-list">
            <div class="friend pink">
                <img src="https://img.freepik.com/premium-vector/icon-human-icon_1076610-59590.jpg" alt="Prapti Pandya">
                <p>PRAPTI PANDYA</p>
            </div>
            <div class="friend light-blue">
                <img src="https://img.freepik.com/premium-vector/icon-human-icon_1076610-59590.jpg" alt="Roshni Aahir">
                <p>ROSHNI AAHIR</p>
            </div>
            <div class="friend blue">
                <img src="https://img.freepik.com/premium-vector/icon-human-icon_1076610-59590.jpg" alt="Neha Patel">
                <p>NEHA PATEL</p>
            </div>
            <div class="friend light-green">
                <img src="https://img.freepik.com/premium-vector/icon-human-icon_1076610-59590.jpg" alt="Hita Desai">
                <p>HITA DESAI</p>
            </div>
            <div class="friend pink">
                <img src="https://img.freepik.com/premium-vector/icon-human-icon_1076610-59590.jpg" alt="Anni Jain">
                <p>ANNI JAIN</p>
            </div>
            <div class="friend blue">
                <img src="https://img.freepik.com/premium-vector/icon-human-icon_1076610-59590.jpg" alt="Arzoo Parmar">
                <p>ARZOO PARMAR</p>
            </div>
            <button>ADD OTHER FRIENDS</button>
        </div>
    </section>
    <section id="stories">
        <h2>Add More Stories and Share with Friends</h2>
        <div class="book-grid">
            <div class="book">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSMd11zJesnrQWuInQJVgnUmKG5AkGWE7-XOg&s" alt="Cinderella">
             
            </div>
            <div class="book">
                <img src="https://5.imimg.com/data5/SELLER/Default/2021/2/SA/IQ/HS/49559104/img-20210211-121925.jpg"alt="Jungle Book">
                
            </div>
            <div class="book">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS_mF28-QwIISUcKjiwlSNYTIILb5zwVCbD-A&s" alt="Pick a Story: A Pirate + Alien Jungle Adventure">
              
            </div>
            <div class="book">
                <img src="https://m.media-amazon.com/images/I/81hLqXpebIL._AC_UF1000,1000_QL80_.jpg" alt="Good Company">
               
            </div>
        </div>
        <button>DOWNLOAD MORE STORIES</button>
        <button>HOME</button>
    </section>
    <section id="settings">
     <div class="container">
        <div class="title">SETTINGS</div>
        <button class="button home">HOME</button>
        <button class="button profile-settings">PROFILE SETTINGS</button>
        <button class="button language">LANGUAGE</button>
        <button class="button data-saver">DATA SAVER</button>
        <button class="button notification">NOTIFICATION</button>
        <button class="button privacy-policy">PRIVACY AND POLICY</button>
        <button class="button add-account">ADD OTHER ACCOUNT</button>
    </div>
    </section>
    <section id="feedback" class="feedback-section">
        <h2>FEEDBACK</h2>
        <a href="#">HOME</a>
        <textarea placeholder="WRITE YOUR REVIEW AND SUGGESTION"></textarea>
        <p class="contact-info">THANK YOU FOR REVIEW</p>
</section>
</body>

  <footer>
    <div class="footer-content">
        <p>&copy; 2023 Story App. All rights reserved.</p>
        <div class="footer-links">
            <a href="#">Privacy Policy</a>
            <a href="#">Terms of Service</a>
            <a href="#">Contact Us</a>
        </div>
    </div>
</footer>
</footer>
</html>
