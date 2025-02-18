<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Profile</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        h1 {
            text-align: left;
        }
        p {
            text-align: left;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            align-items: center;
        }
        .skills, .image {
            flex: 1;
            min-width: 250px;
            text-align: center;
        }
        img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <h1>Hi, nice to meet you! :)</h1>
    <p>My name is Guilherme. I currently work as a UX Designer and Web Designer. Recently, I started watching some videos about programming and decided to study it further. Now, here I am, coding like crazy every day because I truly fell in love with this world.</p>
    <h2>Languages and Tools</h2>
    <div class="container">
        <div class="skills">
            <a href="https://skillicons.dev">
                <img src="https://skillicons.dev/icons?i=py,html,css,flask,figma,git,github" alt="Skills">
            </a>
        </div>
        <div class="image">
            <img src="https://i.imgur.com/leZOdBP.gif" alt="Coding GIF">
        </div>
    </div>
</body>
</html>
