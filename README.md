
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8"/>
    <meta name="viewport" content="width=device-width, initial-scale=1"/>
    <title>Campus Notices</title>
    <link rel="stylesheet" href="style.css"/>

    <style>
        .container {
            display: flex;
            background-color: DodgerBlue;
            padding: 10px;
        }

        .container section {
            background-color: #f1f1f1;
            margin: 10px;
            padding: 20px;
            font-size: 20px;
            flex: 1;
        }
    </style>
</head>

<body>CCC

    <header>
        <h1>Don Mariano Marcos Memorial State University</h1>
    </header>

    <nav>
        <a href="#home">HOME</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact Us</a>
        <a href="#register">Register</a>
    </nav>

    <main>
        <section id="home">
            <h3>Campus Notices</h3>

            <div class="container">

                <section id="register">
                    <h3 style="text-align: center; margin-top: 0;">Login Form</h3>

                    <form>
                        <label for="username">Username:</label>
                        <input type="text" id="username" name="username" required>

                        <br><br>

                        <label for="password">Password:</label>
                        <input type="password" id="password" name="password" required>

                        <br><br>

                        <p style="text-align: center;">
                            <button type="reset">Cancel</button>
                            <button type="submit">Login</button>
                        </p>
                    </form>
                </section>

                <section>
                    <img src="/Users/mac18/Downloads/dmmmsupogi.png" alt="DMMMSU Campus" width="200">
                </section>

            </div>
        </section>

        <section id="about">
            <h2>About Us</h2>
            <p>Don Mariano Marcos Memorial State University provides quality education to students.</p>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <p>College of Computer Science</p>
        </section>
    </main>

    <footer>
        <p>College of Computer Science</p>
    </footer>

</body>
</html>

