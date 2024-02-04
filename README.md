<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix Login Page</title>
    <style>
        body {
            background-color: #353535;
            color: #fff;
            font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
        }
        .container {
            width: 400px;
            margin: 0 auto;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 5px;
            background-color: rgba(0, 0, 0, 0.7);
        }
        .form-group {
            margin-bottom: 15px;
        }
        .form-group label {
            display: block;
            margin-bottom: 5px;
            font-size: 12px;
            text-transform: uppercase;
        }
        .form-group input {
            width: 100%;
            padding: 5px;
            border: none;
            border-radius: 3px;
            background-color: #454545;
            color: #fff;
        }
        .form-group button {
            width: 100%;
            padding: 5px;
            background-color: #e50914;
            border: none;
            border-radius: 3px;
            color: #fff;
            cursor: pointer;
        }
        .form-group button:hover {
            background-color: #cf0611;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Sign In</h2>
        <form>
            <div class="form-group">
                <label for="email">Email or phone number</label>
                <input type="email" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="password">Password</label>
                <input type="password" id="password" name="password" required>
            </div>
            <div class="form-group">
                <button type="submit">Sign In</button>
            </div>
        </form>
        <div class="form-group">
            <a href="#" style="color: #fff; text-decoration: none;">Need help?</a>
        </div>
    </div>
</body>
</html>
