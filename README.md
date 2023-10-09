Library project
<!DOCTYPE HTML>
<html>
    <head>
        <meta charset="viewport">
        <title>Moldays interactive webpage</title>
    </head>
    <header>
        <nav class="nav">
        <ul class="nav_items">
            <li class="nav_item">
                <a href="#" class="nav_link">Home</a>
                <a href="#"class="nav_link">Contact Page</a>
                <a href="#"class="nav_link">Service</a>
                <a href="#"class="nav_link">Portfolio</a>
                <a href="#"class="nav_link">About me</a>
            </li>
        </ul>
    </header>
</nav>
<div class="container">
    <div class="content">
        <p>Hi. Am Molday Ouma Fidel</p>
        <h1>Website Developer<span>Freelancer</span>Data Administrator</h1>
        <button type="button">Learn More</button>
    </div>
</div>
    <body>
        <style>
            *{
                margin: 0;
                padding: 0;
                box-sizing: border-box;
                font-family: 'Courier New', Courier, monospace;
            }
            a{
                text-decoration: none;
            }
            
            header{
                position: fixed;
                padding:  0 30px;
                margin-top: 9px;
                display: flex;
                list-style: none;
                margin: 20px 0px;
                width: 100%;
                height: 80px;
                z-index: 100;
            }
            .nav{
                max-width: 1100px;
                width: 100%;
                margin: 0 auto;
            }
            .nav,
            .nav_item{
                display: flex;
                height: 100%;
                align-items: center;
                justify-content: space-between;
                font-size: 17px;
            }
            .nav_item{
                column-gap: 25px;
            }
            .nav_link{
                color: #fff;
            }
            .nav_link:hover{
                color: #d9d9;
            }
            body{
                background-color: blueviolet;
            }.container{
                width: 100vw;
                height: 100vh;
                padding: 0 8%;
                position: relative;
            }
            .content{
                top: 50%;
                position: absolute;
                transform: translateY(-50%);
                color: #fff;
            }
            .content h1{
                font-size: 64px;
                font-weight: 600;
            }
            .content h1 span{
                color: #ff3753;
            }
            .content button{
                background: transparent;
                border: 2px solid #fff;
                outline: none;
                padding: 12px 25px;
                color: #fff;
            }
        </style>
    </body>
</html>
