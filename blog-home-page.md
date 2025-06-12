# Blog Home Page:-

```
<!DOCTYPE HTML>
<html>
    <head>
        <title>
            Hey! It's my diary!
        </title>

        <style>
            body {
                font-family: "Times New Roman", sans-serif;
                margin: 0;
                padding: 0;
                background-color: #f8f8f8;
                /* light background for the entire page */
            }

            header{
                background-color: #6160d3;
                /* blue ish header colors */
                color: #ffffff;
                text-align: center;
                padding: 1em 0;
            }

            header nav ul{
                list-style: none;
                padding: 0;
            }

            header nav ul li{
                display: inline;
                margin: 0 15px;
            }

            header nav ul li a{
                color: #ffffff;
                text-decoration: none;
                font-weight: bold;
            }

            main {
                margin: 20px;
                background-color: #ffffff;
                /* white background for the main content */
                padding: 20px;
                border-radius: 8px;
                box-shadow: 0 4px 8px;
                rgb (0,0,0,0.1);
            }

            article{
                margin-bottom: 40px;
                padding-bottom: 20px;
                border-bottom: 1px solid #eeeeee;
            }

            article h2{
                color: #333333;
                margin-bottom: 10px
            }

            article p{
                color: #666666;
                line-height: 1.6;
            }

            footer{
                background-color: #6160d3;
                color: #ffffff;
                text-align: center;
                padding: 1em 0;
            }
        </style>
    </head>

    <body>
        <header>
            <h1> Latest Blog <h1>
            <nav>
                <ul>
                    <li>
                        <a href ='blog home.html'> Home  </a>
                    </li>
                    <li>
                        <a href ="blog about me.html"> About Me </a>
                    </li>
                    <li>
                        <a href ="#"> Socials </a>
                    </li>
                </ul>
            </nav>
        </header>

        <main>
            <article>
                <table>
                <tr>
                    <td></td>
                    <td> <br> <img src='image.png' height='100' width='100'> </td> 
                    <td></td>
                    <td></td>
                    <td> <h2> /*title for current blog*/ </h2> </td>
                </tr>
            </table>
                <p>/*add your blog content here!*/ </p>
            </article>

            <article>
                <h2> /*title for previous blog*/</h2>
                <p>/*add your blog content here!*/</p>
            </article>

            <article>
                <h2> /*title for previous blog*/ </h2>
                <p> /*add your blog content here!*/ </p>
        </main>

        <footer>
            <p> Now that you have scrolled here, wanna give me a like? </p>
        </footer>
    </body>
</html>
