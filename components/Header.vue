<template>
    <header>
        <div class = "container">

            <nav>
                <ul>
                    <img src = "ColinLogo.jpg" width = "50px" alt = "My Logo" class = "logo">
                    <li><a href = "#">HOME</a></li>
                    <li><a href = "#">RESUME</a></li>
                    <li><a href = "#">CONTACT INFO</a></li>
                    <li><a href = "#s">CREATIVE PROJECTS</a></li>
                </ul>

            </nav>
        </div>
    </header>
    
</template>

<style>
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

    nav {
        padding-top: none;
    }

    nav ul {
       display: flex;
       flex-direction: row;
       justify-content: space-between;
       margin: auto;
       padding: 10px;
       list-style: none;
    }

    nav li {
        display: inline-block;
        padding-top: 10px;
        
    }

</style>