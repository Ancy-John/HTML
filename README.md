# HTML
Code of html web development
******************************************************************************************************************************************
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <mata name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AIRLINE MANANGEMENT|EMIRATES</title>
    <link rel="stylesheet" href="style1.css">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>

</head>
<body>
    <header class="header">
        <nav class="navbar">
            <a href="#">Home</a>
            <a href="#">About</a>
            <a href="#">Service</a> 
            <a href="#">Contact</a>
            <button class="Login">Login</button>
        </nav>
        <form action="#" class="search-bar">
            <input type="text" placeholder="Search...">
            <button type="submit"><box-icon name='search'><i class='bx bx-search-alt-2'></i></box-icon></button>
        </form>
    </header>
    

    <div class="background"></div>
    <div class="container">
        <div class="content">
            <h2 class="logo">EMIRATES<i class='bx bxs-plane-alt'></i></h2>

            <div class="text-sci">
                <h2>Welcome!<br><span>EMIRATES|FLY BETTER</span></h2>

                <p>Get a wonderful experience with Emirates. Feel the summer <i class='bx bxs-plane-take-off'></i></p>

                <div class="social-icons">
                    <a href="#"><i class='bx bxl-linkedin' ></i></a>
                    <a href="#"><i class='bx bxl-instagram' ></i></a>
                    <a href="#"><i class='bx bxl-facebook' ></i></a>
                    <a href="#"><i class='bx bxl-twitter' ></i></a>
                    
                    
                    
                </div>
            </div>
        </div>
        
        <div class="logreg-box">
            <div class="form-box login">
                <form action="#">
                    <h2>Login</h2>

                    <div class="input-box">
                        <span class="icon"><i class='bx bxs-envelope'></i></span>
                        <input type="email" required>
                        <label>Email</label>
                    </div>

                    <div class="input-box">
                        <span class="icon"><i class='bx bxs-lock-alt'></i></span>
                        <input type="password" required>
                        <label>Password</label>
                    </div>

                    <div class="remember-forgot">
                        <label><input type="checkbox">Remember me</label>
                        <a href="#">Forgot password?</a>
                    </div>

                    <button type="submit"
                    class="btn">Sign In</button>

                    <div class="login-register">
                        <p>Don't have an account? <a href="#"
                        class="register-link">Sign Up</a></p>
                    </div>
                </form>
            </div>
            <div class="form-box register">
                <form action="#">
                    <h2>Register</h2>

                    <div class="input-box">
                        <span class="icon"><i class='bx bxs-user'></i></span>
                        <input type="text" required>
                        <label>Name</label>
                    </div>

                    <div class="input-box">
                        <span class="icon"><i class='bx bxs-envelope'></i></span>
                        <input type="email" required>
                        <label>Email</label>
                    </div>

                    <div class="input-box">
                        <span class="icon"><i class='bx bxs-lock-alt'></i></span>
                        <input type="password" required>
                        <label>Password</label>
                    </div>

                    <div class="remember-forgot">
                        <label><input type="checkbox">I agree to term and conditions</label>
                        <a href="#"></a>
                    </div>

                    <button type="submit"
                    class="btn">Sign Up</button>

                    <div class="login-register">
                        <p>Already have an account? <a href="#"
                        class="login-link">Sign In</a></p>
                    </div>
                </form>
            </div>
        </div>
    </div>



    <script src="script.js"></script>
    <script type="module" src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.esm.js"></script>
<script nomodule src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.js">
</script> 
</body>

</html>
