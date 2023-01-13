<template>
    <header>
        <div class = "container">

            <nav>
                <ul>
                    <img src = "ColinLogo.jpg" width = "50px" alt = "My Logo" class = "logo">
                    <li><a href = "#">Home</a></li>
                    <li><a href = "#">Projects</a></li>
                    <li><a href = "#">Contact Info</a></li>
                    <li><a href = "#">Creative Projects</a></li>
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

    nav ul{
       display: flex;
       flex-direction: row;
       justify-content: space-between;
       margin: auto;
    }

</style>