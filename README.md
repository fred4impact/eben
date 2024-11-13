```

/* Global styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

/* Header styling */
header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    background-color: #2c6e63;
    color: #fbe5b6;
    padding: 20px;
}
 .carousel img {
      width: 100%; 
      height: auto; 
      display: block;
    }

.site-name {
    font-size: 30px;
    font-weight: bold;
}

.social-icons {
    display: flex;
}

.social-icons a {
    margin-left: 10px;
}

.social-icons img {
    width: 30px;
    height: 30px;
}

/* Navbar styling */
nav {
    background-color: #f38218;
}

nav ul {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    list-style: none;
    padding: 10px 0;
}

nav ul li {
    margin: 5px 0;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
    padding: 10px 20px;
    display: block;
    transition: background-color 0.3s ease;
}

nav ul li a:hover,
nav ul li a.active {
    background-color: #2c6e63;
    color: #fbe5b6;
}

/* Main content styling */
main {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    padding: 20px;
    background-color: #fbe5b6;
}

.sidebar {
    flex: 1 1 300px;
    padding: 20px;
    background-color: #fbe5b6;
}

.sidebar img {
    width: 100%;
    height: auto;
    display: block;
    margin-bottom: 20px;
}

.main-content {
    flex: 2 1 600px;
   /* background-color: #fff; */
    padding: 20px;
    margin:8px ;
    border-radius: 5px;
    /*box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);*/
}

.textbody p {
    margin-bottom: 15px;
}

/* Footer styling */
footer {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    padding: 20px;
    background-color: #2c6e63;
    color: white;
}

.footer-links,
.map {
    flex: 1 1 300px;
    margin-bottom: 20px;
}

.footer-links ul {
    list-style: none;
}

.footer-links li {
    margin-bottom: 10px;
}

.footer-links a {
    color: white;
    text-decoration: none;
}

.map iframe {
    width: 100%;
    height: 200px;
    border: none;
}


/* Responsive styles */
@media (max-width: 768px) {
    header {
        flex-direction: column;
        align-items: center;
        text-align: center;
    }

    .social-icons {
        margin-top: 10px;
    }

    nav ul {
        flex-direction: column;
        align-items: center;
    }

    main {
        flex-direction: column;
    }

    .footer-links,
    .map {
        flex: 1 1 100%;
    }



/* now */
 

    footer {
        flex-direction: column; /* Stack footer items vertically */
        text-align: center;
    }

    .map iframe {
        height: 150px; /* Adjust map height for smaller screens */
    }


}



/* tablets */

@media (max-width: 480px) {
    header {
        padding: 15px;
    }

    .site-name {
        font-size: 30px;
    }

    nav ul li a {
        font-size: 18px;
        padding: 8px 15px;
    }

  .carousel img {
    
        max-height: 200px; /* Limits the height for better display on small screens */
  
}


    .form {
        padding: 15px;
    }

    .button {
        font-size: 14px;
    }
}

```

