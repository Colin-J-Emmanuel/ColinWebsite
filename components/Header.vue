<template>
    <header>
        <div class = "container">
            <nav>
                <ul>
                    <img src = "ColinLogo.jpg" width = "50px" alt = "My Logo" class = "logo">
                    <li><a href = "#"><b>Home</b></a></li>
                    <li><a href = "https://drive.google.com/drive/folders/15_j5mvxBJ3Ie_-OZOxP_ZrdSW5tPKWyc"><b>Resume</b></a></li>
                    <li><a href = "#"><b>Contact Info</b></a></li>
                    <li><a href = "https://www.instagram.com/youthstorytime/"><b>Creative Projects</b></a></li>
                </ul>
            </nav>
        </div>
    </header>   
</template>

<style>
    /* container class refers to the entire header portion of the website */
    .container {
            margin: 0px;
            margin-left: 12px;
            margin-right: 12px;
        }

    header {
        background: #59E80D;
    }

    header::after {
        content: '';
        display: table;
        clear: both;
    }

    nav ul {
       display: flex;
       flex-direction: row;
       justify-content: space-between;
       margin: auto;
       padding: 10px;
       list-style: none;
    }

    /* The nav headers which originally were imported as list items */
    nav li {
        display: inline-block;
        padding-top: 10px;
        position: relative; /* makes sure the top element on nav headers doesn't extend
        to the entire width of the screen */
    }

     /* Modifies the tab headers on the nav bar */
     nav a {
        text-decoration: none;
        color: #444;
        font-size: 15px;
        text-transform: uppercase;
    }

    nav a:hover {
        color: #000;
    }

    nav a::before {
        content: '';
        display: block;
        height: 5px;
        width: 100%;
        background-color: #444;

        position: absolute;
        top: 0;
        width: 0%;

        transition: all ease-in-out 1000ms;
    }

    nav a:hover::before {
        width: 100%;

    }

</style>