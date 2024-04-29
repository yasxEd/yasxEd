<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Social Card Design</title>
    <style>
        /* Styles for the social card */
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f4f4f4;
        }

        .card {
            width: 300px;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            background-color: white;
            text-align: center;
        }

        .card img {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 10px;
        }

        .card h2 {
            margin: 10px 0;
            font-size: 24px;
            color: #333;
        }

        .card p {
            margin: 10px 0;
            font-size: 14px;
            color: #666;
        }

        .card .social-links {
            margin-top: 10px;
        }

        .card .social-links a {
            margin: 0 5px;
            display: inline-block;
            width: 30px;
            height: 30px;
            line-height: 30px;
            text-align: center;
            border-radius: 50%;
            background-color: #ddd;
            color: #333;
            text-decoration: none;
        }

        /* Customize the background color of each social media icon */
        .card .social-links a:hover {
            background-color: #ccc;
        }
    </style>
</head>

<body>
    <div class="card">
        <img src="https://placekitten.com/100/100" alt="Profile Picture">
        <h2>John Doe</h2>
        <p>Web Developer and Designer</p>
        <div class="social-links">
            <a href="https://twitter.com/yourprofile" target="_blank">T</a>
            <a href="https://facebook.com/yourprofile" target="_blank">F</a>
            <a href="https://www.instagram.com/yourprofile" target="_blank">I</a>
            <a href="https://www.linkedin.com/in/yourprofile" target="_blank">L</a>
        </div>
    </div>
</body>

</html>
