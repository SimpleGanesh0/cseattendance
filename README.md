<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Attendance Management System</title>

    <style>
        /* General Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', sans-serif;
        }

        body {
            background: linear-gradient(135deg, #007bff, #00c6ff);
            color: #fff;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            text-align: center;
            position: relative;
        }

        h1 {
            font-size: 48px;
            margin-bottom: 20px;
        }

        p {
            font-size: 18px;
            margin-bottom: 30px;
            max-width: 500px;
        }

        .buttons {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
            justify-content: center;
        }

        a.button {
            background-color: #fff;
            color: #007bff;
            padding: 12px 24px;
            text-decoration: none;
            border-radius: 8px;
            font-weight: bold;
            transition: all 0.3s ease;
        }

        a.button:hover {
            background-color: #f0f0f0;
            transform: scale(1.05);
        }

        /* Footer */
        footer {
            position: absolute;
            bottom: 15px;
            text-align: center;
            font-size: 14px;
            color: #f0f0f0;
            width: 100%;
        }
    </style>
</head>
<body>

    <h1>Attendance Management System</h1>
    <p>Welcome! Please log in to manage attendance.</p>

    <div class="buttons">
        <a href="login.html" class="button">Login</a>
    </div>

    <footer>
        © Project group 5
    </footer>

</body>
</html>
