<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Instagram</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        * {
            box-sizing: border-box;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
        }

        body {
            background-color: #fafafa;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .login-container {
            width: 350px;
        }

        .login-box {
            background: #fff;
            border: 1px solid #dbdbdb;
            padding: 40px 30px;
            text-align: center;
        }

        .logo {
            font-family: 'Billabong', cursive;
            font-size: 48px;
            margin-bottom: 30px;
        }

        input {
            width: 100%;
            padding: 10px;
            margin-bottom: 8px;
            border: 1px solid #dbdbdb;
            border-radius: 3px;
            background: #fafafa;
        }

        button {
            width: 100%;
            padding: 8px;
            background-color: #4cb5f9;
            border: none;
            border-radius: 5px;
            color: white;
            font-weight: 600;
            cursor: pointer;
            margin-top: 10px;
        }

        button:hover {
            background-color: #3797ef;
        }

        .divider {
            display: flex;
            align-items: center;
            margin: 20px 0;
            color: #8e8e8e;
            font-size: 13px;
        }

        .divider::before,
        .divider::after {
            content: "";
            flex: 1;
            height: 1px;
            background: #dbdbdb;
        }

        .divider span {
            margin: 0 18px;
        }

        .facebook-login {
            color: #385185;
            font-weight: 600;
            font-size: 14px;
            cursor: pointer;
        }

        .forgot {
            margin-top: 15px;
            font-size: 12px;
            color: #00376b;
            cursor: pointer;
        }

        .signup-box {
            background: #fff;
            border: 1px solid #dbdbdb;
            padding: 20px;
            text-align: center;
            margin-top: 10px;
            font-size: 14px;
        }

        .signup-box span {
            color: #0095f6;
            font-weight: 600;
            cursor: pointer;
        }
    </style>
</head>
<body>

<div class="login-container">

    <div class="login-box">
        <div class="logo">Instagram</div>

        <form>
            <input type="text" placeholder="Phone number, username, or email">
            <input type="password" placeholder="Password">
            <button type="submit">Log In</button>
        </form>

        <div class="divider">
            <span>OR</span>
        </div>

        <div class="facebook-login">
            Log in with Facebook
        </div>

        <div class="forgot">
            Forgot password?
        </div>
    </div>

    <div class="signup-box">
        Don’t have an account? <span>Sign up</span>
    </div>

</div>

</body>
</html>
