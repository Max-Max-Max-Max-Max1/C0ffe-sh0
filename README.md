<html>
    <head>
        <title>Cafe</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <header>
            <img src="https://static.vecteezy.com/system/resources/previews/000/334/460/original/coffee-place-logo-vector.jpg" width="75px" height="75px">
        </header>
        <nav>
            <a class="nav-link" href="index.html">Десерти</a>
            <a class="nav-link" href="index1.html">Кава</a>
            <a class="nav-link" href="#contact">Контакти</a>
        </nav>
        <main>
            <h1>Меню Десертів</h1>
            <section class="info">
                <article>
                    <h2>Чизкейк з полуниці</h2>
                    <img src="https://th.bing.com/th/id/R.aa1eb5c4d5303d76d370fc551d7c149c?rik=xh1CTCdYRelOUw&pid=ImgRaw&r"width="400px" height="300px"/>
                </article>
                <article>
                    <h2>Торт з ягод</h2>
                    <img src="https://th.bing.com/th/id/OIP.SFmZoeTYOla0uWFetnZIogHaFs?r=0&rs=1&pid=ImgDetMain" width="400px" height="300px"/>
                    <p class="price">400 ₴</p>
                    <br>
                    <a class="article-but" href="#contact">Детальніше</a>
                </article>
                <article>
                    <h2>Тирамісу</h2>
                    <img src="https://th.bing.com/th/id/R.c6b183f69f36efdd906973f05d421ede?rik=lvUAcn9KzVzxgw&pid=ImgRaw&r=0" width="400px" height="300px"/>
            
                    <p class="price">200 ₴</p>
                    <br>
                    <a class="article-but" href="#contact">Детальніше</a>
                </article>
            </section>
            <img src="https://thumbs.dreamstime.com/b/desserts-text-made-sweets-isolated-white-background-314107446.jpg" width="800" height="200"/ class="img-footer">
        </main>
        <footer>
            <a href="" id="contact"><img src="https://img.icons8.com/m_outlined/512/FFFFFF/instagram-new--v2.png" width="80px" height="80px"></a>
            <a href="" id="contact"><img src="https://img.icons8.com/sf-ultralight-filled/512/FFFFFF/telegram.png" width="80px" height="80px"></a>
            <p><b>Напиши - отримай <br/> промокод!</b></p> 
        </footer>
    </body>
</html>


body {
    font-family: sans-serif;
    background-color: rgb(248, 131, 131);
    color: rgb(198, 41, 43);
    margin: 0;
    text-align: center;
.nav-link:hover,
.article-but:hover,
.price:hover,
article h2:hover {
  color: #0e0a079d; 
  transform: translateY(-3px);
  transition: all 0.3s ease;
}

}



nav {
    display: flex;
    justify-content: center;
    

    
}

.nav-link{
    text-decoration: none;
    margin-left: 35px;
    background-color: rgb(222, 185, 136);
    border-radius: 12px;
    padding: 9px;
    color: rgb(198, 41, 43);
    font-weight: 600;
}

.article-but{
    background-color: rgb(222, 185, 136);
    border-radius: 12px;
    padding: 9px;
    color: rgb(198, 41, 43);
    font-weight: 600;
    text-decoration: none;
    margin-bottom: 36px;
}
.price{
    font-weight: 700;
}



p {
    font-size: 20px;
}

main img{
    border-left: 10px double rgb(198, 41, 43);
}
.nav-link::before {
    content: "☕ ";
}

.article-but::before {
    content: "➤ ";
}

.price::after {
    content: " ₴";
}

article h2::before {
    content: "🍰 ";
}

.img-footer {
    margin-top: 125px;
}




.img footer{
    margin-top: 125px;
}



