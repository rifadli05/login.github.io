# login.github.io
Login
<!DOCTYPE html>

<html>

<head>

  <meta charset="utf-8" />

  <meta http-equiv="X-UA-Compatible" content="IE=edge" />

  <title>Login</title>

  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <link rel="stylesheet" href="LoginStyle.css">

</head>

<body>

  <div id="LOGIN">

    <div id="Username">

      <div id="Password">

        <h2>LOGIN</h2>

        <div class="underline-title"></div>

      </div>

      <form method="post" class="form">

        <label for="user-Username" style="padding-top:13px">

            &nbsp;Username

          </label>

        <input id="user-email" class="form-content" type="email" name="email" autocomplete="on" required />

        <div class="form-border"></div>

        <label for="user-password" style="padding-top:22px">&nbsp;Password

          </label>

        <input id="user-password" class="form-content" type="password" name="password" required />

        <div class="form-border"></div>

        <a href="#">

          <legend id="forgot-pass">Forgot password?</legend>

        </a>

        <input id="submit-btn" type="submit" name="submit" value="LOGIN" />

      </form>

    </div>

  </div>

</body>

</html>

