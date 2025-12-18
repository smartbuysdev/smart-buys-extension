<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Smart Buys - Shopping Companion</title>
    
    <style>
        /* This resets the page to look clean on all browsers */
        * { box-sizing: border-box; }
        
        body { 
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; 
            margin: 0;
            padding: 0;
            background-color: #f9f9f9; /* Light grey background looks more pro */
            color: #333;
            display: flex;
            align-items: center;
            justify-content: center;
            min-height: 100vh; /* Centers everything vertically on the screen */
        }

        .container { 
            background: white;
            max-width: 600px; 
            width: 90%;
            padding: 50px; 
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1); /* Adds a subtle shadow card effect */
            text-align: center;
        }

        h1 { 
            font-size: 2.5rem; 
            color: #2c3e50; 
            margin-bottom: 20px;
        }

        p { 
            font-size: 1.2rem; 
            line-height: 1.6; 
            color: #555;
            margin-bottom: 30px;
        }

        .btn {
            display: inline-block;
            background-color: #007bff;
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 8px;
            font-weight: bold;
            font-size: 1.1rem;
            transition: background-color 0.2s;
        }

        .btn:hover { 
            background-color: #0056b3; 
        }

        .footer {
            margin-top: 40px; 
            font-size: 0.9rem; 
            color: #888;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Smart Buys</h1>
        
        <p>
            Smart Buys automatically finds cheaper, high-quality alternatives 
            on eBay while you shop on Amazon.
        </p>
        
        <a href="https://chrome.google.com/webstore/detail/obachdidi..." class="btn">
            Download for Chrome
        </a>
        
        <div class="footer">
            Contact: smartbuys.dev@gmail.com
        </div>
    </div>

</body>
</html>
