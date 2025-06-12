# About Me Page:-

```
<!DOCTYPE html>
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
                rgba (0,0,0,0.1);
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
                        <a href ="blog home.html"> Home  </a> /* Would only work after adding both codes with the name */
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
            <table >
                <tr>
                    <td> <img src='fix2.jpg' height='380', width='280' border='1'> </td>
                    <td></td>
                    <td></td>
                    <td></td>
                    <td> /* You can add your info here!! */ </td>
                </tr>
            </table>
        </main>

        <footer>
            <p> Now that you have scrolled here, wanna give me a like? </p>
        </footer>
    </body>
</html>
```
