---
layout: default
title: StudyHelper
---



---


<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>StudyHelper - Learn Smart, Study Better</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #e0c3fc 0%, #8ec5fc 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .container {
            text-align: center;
            background: rgba(255, 255, 255, 0.95);
            padding: 60px 50px;
            border-radius: 25px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            max-width: 500px;
            width: 100%;
            backdrop-filter: blur(10px);
        }

        h1 {
            font-size: 3.5em;
            color: #667eea;
            margin-bottom: 10px;
            font-weight: 800;
            letter-spacing: -1px;
        }

        .tagline {
            font-size: 1.1em;
            color: #999;
            margin-bottom: 50px;
            font-weight: 300;
        }

        .choose-text {
            font-size: 1.3em;
            color: #555;
            margin-bottom: 30px;
            font-weight: 600;
            letter-spacing: 0.5px;
        }

        .button-group {
            display: flex;
            gap: 15px;
            flex-wrap: wrap;
            justify-content: center;
        }

        .btn {
            padding: 18px 40px;
            font-size: 1.1em;
            font-weight: 600;
            border: none;
            border-radius: 15px;
            cursor: pointer;
            transition: all 0.3s ease;
            text-decoration: none;
            display: inline-block;
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.15);
            letter-spacing: 0.5px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
        }

        .btn:hover {
            transform: translateY(-4px);
            box-shadow: 0 12px 35px rgba(102, 126, 234, 0.4);
        }

        .btn:active {
            transform: translateY(-2px);
        }

        .emoji {
            font-size: 1.3em;
            margin-right: 8px;
        }

        @media (max-width: 600px) {
            .container {
                padding: 40px 30px;
                border-radius: 20px;
            }

            h1 {
                font-size: 2.8em;
            }

            .choose-text {
                font-size: 1.1em;
            }

            .btn {
                padding: 15px 30px;
                font-size: 1em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>StudyHelper</h1>
        <p class="tagline">Your One Way Stop for ICSE Notes, Soutions And More!</p>
        
        <p class="choose-text">📚 Choose Your Class</p>
        
        <div class="button-group">
            <a href="class10.html" class="btn">
                <span class="emoji">✨</span>Class 10
            </a>
			<p class="tagline">More Classes Coming Soon!</p>
        </div>
    </div>
</body>
</html>



