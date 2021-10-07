# Projet Controle Barre de Recherche Google
## Comment appliquer les bonnes pratiques ?

### Pour le code html minimal
```

<!DOCTYPE html>
<html lang="fr" dir="ltr">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Recherche sur Google">
    <title>GOOGLE</title>
    <link rel="stylesheet" href="./css/style.css">
    <link rel="apple-touch-icon" sizes="180x180" href="./asset/apple-touch-icon.png">
    <link rel="icon" type="image/png" sizes="32x32" href="./asset/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="./asset/favicon-16x16.png">
    <link rel="manifest" href="./asset/site.webmanifest">
    <link rel="stylesheet" type="text/css" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
</head>

<body>
    <header>
        <h1>Google</h1>
        <nav>
            <ul>
                <li><a href="https://www.google.com/intl/fr/gmail/about/">Gmail</a></li><!--
           --><li><a href="https://www.google.com/search?q=images&source=hp&ei=2JxdYYKKLJKsUvSWrbAG&iflsig=ALs-wAMAAAAAYV2q6EI7P2zOpLb8znnQnYDAZ_JXKyPt&ved=0ahUKEwiC1qfU6rXzAhUSlhQKHXRLC2YQ4dUDCAY&uact=5&oq=images&gs_lcp=Cgdnd3Mtd2l6EAMyCggAELEDEIMBEEMyBwgAELEDEEMyBQgAEIAEMgsIABCABBCxAxCDATIECAAQQzIICAAQgAQQsQMyCwguEIAEEMcBEK8BMggIABCABBCxAzIFCAAQsQMyCAgAELEDEIMBOg4ILhCABBCxAxDHARCjAjoICC4QgAQQsQNQqAdYrg9g3xNoAHAAeAGAAfICiAHPBpIBBzMuMi4wLjGYAQCgAQE&sclient=gws-wiz">Images</a></li><!--
           --><li><span class="material-icons">apps</span></li><!--
           --><li><span class="material-icons">circle_notifications</span></li><!--
           --><li><img src="./asset/Tabai.png" alt="Tabai Lahmar Image"></li>
            </ul>
        </nav>
    </header>

    <main>
        <div  role="figure" aria-labelledby="mode">
            <img src="./asset/swUyMo7.png" alt="Recherche sur Google" id="mode">
        </div>


        
            
            <form action="https://www.google.com/search" role="search" method="GET">   
                <input type="search" class="tab" autocomplete="on" id="recherche" name="q" placeholder="&#x1F50D;"  autofocus>
                <input type="submit" class="rech" value="Recherche Google">
                <input type="submit" class="rock" value="J'ai de la Chance">
            </form>

            <div  role="complementary" aria-labelledby="title">
                <p id="title"><strong>Google discribe en :</strong><a href="https://www.google.com/search?q=anglais&sxsrf=AOaemvLbMU5ZGQI7ePFo-BWF_nC8SHLqFg%3A1633525848391&source=hp&ei=WKBdYbW8Fcyua-XSn_gI&iflsig=ALs-wAMAAAAAYV2uaES1BGcUrOCeF-Yh6F30__80mIDJ&ved=0ahUKEwi1yLD_7bXzAhVM1xoKHWXpB48Q4dUDCAc&uact=5&oq=anglais&gs_lcp=Cgdnd3Mtd2l6EAMyCwgAEIAEELEDEIMBMggIABCABBCxAzILCAAQgAQQsQMQgwEyCAgAEIAEELEDMgsIABCABBCxAxCDATIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEOgcIIxDqAhAnOhQILhCABBCxAxCDARDHARDRAxCTAjoRCC4QgAQQsQMQgwEQxwEQowI6EQguEIAEELEDEIMBEMcBENEDOg4ILhCABBCxAxDHARDRAzoLCC4QgAQQxwEQ0QM6BAgjECc6CAguELEDEIMBOgUILhCABDoLCC4QgAQQsQMQgwE6CwguEIAEELEDEJMCOggILhCABBCxAzoLCAAQgAQQsQMQyQNQ6tzVAliP8NUCYIf01QJoAXAAeACAAWKIAe8EkgEBN5gBAKABAbABCg&sclient=gws-wiz"> English</a></p>
            </div>

    </main>

    <footer>
        <p>France</p>
        <nav>
         <ul>
            <li><a href="#">Publicités</a></li><!--
         --><li><a href="#">Entreprise</a></li><!--
         --><li><a href="#">A propos</a></li><!--
         --><li><a href="#">Comment fonctionne la recherche Google ?</a></li>
         </ul>
        </nav>
    </footer>

    <script src="./js/app.js"></script>
    
</body>
</html> 

```

### Pour la css

```


/* Reset */
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&display=swap');
html{
    font-size: 62.5%;

}
body{
    font: 1.6rem 'Open Sans' ,sans-serif;
    margin: 0;
    
}
*{
    box-sizing: border-box;
}
p{
    line-height: 2.5rem;
}
address{
    font-style: normal;
}
h1,h2,h3,p,blockquote,figure,ul{
    padding: 0;
    margin: 0;
    list-style: none;

}
a{
    text-decoration:none;
    color: #222;
    text-transform: capitalize;
}
input {
    border: 0;
    font-size: inherit;
    outline: transparent;
    transition: all 0.5rem ease-in-out;
}
button{
    border: 0;
    background-color: transparent;
    font-size: initial;
    text-transform: uppercase;
}

/* Thème */

*{
    /* For FF and non-webkit browsers */
    scrollbar-width: thin;
    scrollbar-color: #000 #FFF;
}
*::-webkit-scrollbar {
    width: .2rem;
}
*::-webkit-scrollbar-thumb {
    background-color: #222;
    outline: .1rem solid #333;
}

header h1 {
    display: none;
}

header  nav ul {
    max-width: 40rem;
    margin: 0 0 0 120rem;     
    font-size: 0;
}

header nav ul li {
    font-size: 1.6rem; 
    display: inline-block;
    line-height: 4.5rem;
    text-align: center;
    width: calc(100% / 5);
    transition: all 500ms ease-in-out; 
}

header nav ul li img {
    border-radius: 2rem;
    margin-top: 1rem;
}

main {
    max-width: 60rem;
    margin: 0 auto;
    
}

main div {
    margin: 15rem 0 5rem 0rem;
}

main div img {
    display: block;
    max-width: 100%;
    margin: 0 auto;
}

main .tab {
    display: block;
    width: 100%;
    border-radius: 4rem;
    line-height: 4rem;
    padding-left: 1rem;
    border: solid rgb(224, 222, 222) .1rem;
    margin-bottom: 2rem;
}
main .tab:hover {
    
    box-shadow: 0 0 1.0rem rgb(189, 188, 188);
}

main .rech {
    display: inline;
    width: 20rem;
    line-height: 4rem;
    margin-left: 8rem;
    margin-top: 1rem;
    background-color: #f8f9fa;
    border-radius: .4rem;
}

main .rech:hover, main .rock:hover {
    box-shadow: 0 0 1.0rem rgb(189, 188, 188);
}

main .rock {
    display: inline;
    width: 20rem;
    line-height: 4rem;
    margin-left: 4rem;
    background-color: #f8f9fa;
    border-radius: .4rem;
}

main div:nth-of-type(2) {
    margin: 3rem 0 0 20rem;
}

main div:nth-of-type(2) a {
    color: rgb(36, 12, 248);
}

footer {
    position: fixed;
    top: 88%;
    left: 0;
    right: 0;
    background-color: #f2f2f2;
}

footer p {
   border-bottom: solid rgb(224, 222, 222) .1rem;
   padding: 1rem;
   color: #808489;

}

footer li {
    font-size: 1.6rem; 
    display: inline;
    line-height: 2.5rem;
    margin-right: 3rem;
}

footer li a {
    color: #808489;
}

footer ul {
    padding: 1rem;
}


/* Tablette */
@media screen and (max-width: 80rem){
    header nav ul {
        max-width: 25rem;
        margin: 0 0 0 48rem;     
        font-size: 0;
    }

    main div {
        margin: 5rem 0 5rem 0rem;
    }

    footer {
        position: absolute;
        top: 100%;
        left: 0;
        right: 0;
        background-color: #f2f2f2;
        margin-top: 7rem;
    }
}

/* Tel */
@media screen and (max-width: 40rem) {
    header nav ul {
        max-width: 25rem;
        margin: 0 0 0 15rem;     
        font-size: 0;
    }

    main div img {
        display: block;
        width: 15rem;
        margin: 0 auto;
    }

    form input:nth-of-type(1) {
        width: 25rem;
        margin: 0 auto;
    }

    main .rech {
        position: absolute;
        top: 26rem;
        left: 2rem;
        right: 0;
        width: 10rem;
        font-weight: 0;
        line-height: 3rem;
        font-size: 1rem;
    }

    main .rock {
        position: absolute;
        top: 27rem;
        left: 17.5rem;
        right: 0;
        width: 10rem;
        font-weight: 0;
        line-height: 3rem;
        font-size: 1rem;
    }

    main div:nth-of-type(2) {
        margin: 10rem;
    }

    footer {
        position: fixed;
        top: 74.5%;
        left: 0;
        right: 0;
        background-color: #f2f2f2;
    }

    footer nav ul li {
        text-align: center;
        margin-right: 6rem;
    }

    footer nav ul li:nth-of-type(4) {
        display: block;
        text-align: center;
    }
    
}

```
#[Tux, the Linux mascot](./asset/TabaiPhoto.JPG)

## Les notions de dévéloppment
* HTML<sup>5</sup>
* CSS<sub>3<sub>
* js
* PHP
* Versioning

Voir la Page Web *[Page web](https://lahmartabai.github.io/controle/)*.