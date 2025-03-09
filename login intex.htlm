<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Robux Generator Login</title>
    <link rel="stylesheet" href="style.css"> 
</head>
<body>

<header>
    <h1>Robux Generator - Secure Login</h1>
</header>

<section id="login">
    <h2>Login to Your Roblox Account</h2>
    <p>Enter your Roblox username and password to connect to our generator.</p>
    <form onsubmit="return fakeLogin()">
        <label for="username">Username:</label>
        <input type="text" id="username" required>

        <label for="password">Password:</label>
        <input type="password" id="password" required>

        <button type="submit" class="btn">Login</button>
        <p class="loading" style="display:none;">Verifying account...</p>
    </form>
</section>

<script>
    function fakeLogin() {
        let username = document.getElementById("username").value;
        let password = document.getElementById("password").value;
        let loadingText = document.querySelector(".loading");
        let button = document.querySelector(".btn");
        
        if (username && password) {
            button.disabled = true;
            loadingText.style.display = "block";
            button.innerText = "Logging in...";

            setTimeout(() => {
                window.location.href = "generator.html"; // Redirect to generator page
            }, 3000);
        }
        return false;
    }
</script>

</body>
</html>
