<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/reset.css">
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="css/font.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
    <title>Document</title>
</head>
<body>

    <header>
        <div class="header-block">
            <a href="">
                <img class="lol" src="logo/apple-logo.svg" alt="">
            </a>
            <nav class="navigation">
                <ul class="ul-el">
                <li> <a href="">isa</a> </li>
                <li><a href="">esa</a></li>   
                <li><a href="">asa</a></li>  
                <li><a href="">usa</a></li>
                </ul>
            </nav>
            <div class="burger">
                <i class="fa-solid fa-bars"></i>
            </div>
        </div>
        
    </header>
    <section>
        <!-- <h2 class="title">is ar aris is imitom rom ar aris es is ubralod is aris</h2>

        <div class="icons">
            <i class="fa-solid fa-laptop"></i>
            <i class="fa-brands fa-youtube"></i>
        </div> -->

        <div class="container">
            <div class="box">
            <img class="isa" src="logo/apple-logo.svg" alt="">
            <h2>sisiaidsaidisad</h2>
        </div>
            <div class="box">
                <div class="wraper-new">
                    <div class="block">                <h3>isaisaidas</h3>
                    </div>
                    <div class="block">                <p>ragaca</p>
                    </div>
                    <div class="block">                <p>lorem ipsum</p>
                    </div>
                </div>
                
            </div>
            <div class="box"> <p class="esa">isadiasd</p></div>
            
            <div class="box"></div>
            
            <div class="box"></div>

        </div>
    </section>
</body>
</html>


reset:

/* http://meyerweb.com/eric/tools/css/reset/ 
   v2.0 | 20110126
   License: none (public domain)
*/

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;
	border-spacing: 0;
}

a{
    text-decoration: none;
}


style:

/* .title{
   font-family: Chokokutai;
    
} */

/* .fa-laptop{
    color: yellowgreen;
    font-size: 30px;
    transition: all 3s;
} */

/* .fa-youtube{
    color: violet;
    font-size: 30px;
}

.fa-laptop:hover{
    color: cadetblue;
} */

.header-block{
    display: flex;
    /* justify-content: left; */
    align-items: center;
    /* margin-right: 50px; */

}

.ul-el{
    display: flex;
    width: 250px;
    justify-content: space-between;
    margin-left: 50px;
}

.burger{
    display: none;
    margin-right: 30px;
}

.lol {
    height: 100px;
}

@media(max-width: 1024px){
    .navigation{
        display: none;
    }
    .burger{
        display: block;
    }
    .container{
        /* flex-direction: column; */
        /* align-items: center; */
        flex-wrap: wrap;
        justify-content: center;
    }
    .box{
        width: 48%;
    }
}



.container{
    max-width: 1170px;
    width: 90%;
    margin: 0 auto;
    background-color: lightcoral;
    display: flex;
    gap: 30px 25px;
}

.box{
    width: 250px;
    height: 400px;
    background-color: teal;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}

@media(max-width: 480px){
    .box{
        width: 100%;
    }
}

.isa{
    width: 50px;
}

.wraper-new{
    display: flex;
}

.esa{
    border: 2px solid;
}

.block{
    border: 2px solid;
    text-align: center;
    border-radius: 20px;
    border-radius: 300px;
    display: flex;
}


<!-- font-awesome burger baristvis -->
