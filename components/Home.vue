<template>
    <div>
        <h1><b><center>Colin J. Emmanuel</center></b></h1>
        <h2><b><center>From Dar es Salaam to New York City</center></b></h2>
		<!--<p> Follow me on Instagram </p> -->
        
		<!--<a href="https://www.instagram.com/ej_.colin/" target="_blank">
			here's the link </a>-->
        <img id="homepic" width = "400" src="/Mypic.png" alt="a picture of Colin"/>
        <p id ="mainpagetext">Colin is a freshman at Columbia University in the City of New York. 
            He plans to major in Computer Science. 
            He is obsessed with technology and is constantly looking for 
            better opportunities to develop and improve his knowledge in tech. 
            He is currently participating in 
            Columbia’s Jumpstarting Aspiring Developers and Entrepreneurs (JADE) program 
            as part of the 2023 Cohort. He hopes by the end of it, he will be able to 
            launch his own personal website.</p>

        <p id="takemetoJADE">Check out <a href="https://www.cc-seas.columbia.edu/jade" 
            target="_blank">JADE</a> </p>
        
    </div>
</template>

<style>
    
    body {
        font-family: 'Work Sans' , sans-serif;
        font-weight: 300;
        background-image: url(../static/Multicolor.png) 
    }

    #mainpagetext {
        font-family: 'Times New Roman', Times, serif;
    }
    
    #homepic {
        margin: auto;
        display: block;
        margin-left: auto;
        margin-right: auto;
        width: 250px;
        border-radius: 50%;
    }

    #mainpagetext {
        text-align: justify;
        font-family: Arial;
        margin-left: 75px;
        margin-right: 75px;
    }

    #takemetoJADE {
        text-align: justify;
        font-family: Arial;
        margin-left: 75px;
        margin-right: 75px;
    }

    h2 {
        margin-top: -20px;
        color: #61B2DA;
    }

    
</style>