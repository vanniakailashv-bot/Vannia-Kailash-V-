<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio | Link in Bio</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f4f7f6;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 40px 20px;
            margin: 0;
        }
        .container {
            max-width: 400px;
            width: 100%;
            text-align: center;
        }
        .profile-img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 4px solid #fff;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
            object-fit: cover;
        }
        h1 { font-size: 1.5rem; margin: 15px 0 5px; color: #333; }
        p { color: #666; font-size: 0.9rem; margin-bottom: 30px; }
        
        .link-card {
            background: white;
            display: block;
            padding: 15px;
            margin-bottom: 15px;
            text-decoration: none;
            color: #333;
            font-weight: 600;
            border-radius: 12px;
            transition: transform 0.2s, box-shadow 0.2s;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
        }
        .link-card:hover {
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            background-color: #007bff;
            color: white;
        }
    </style>
</head>
<body>

    <div class="container">
        <img src="https://via.placeholder.com/150" alt="Profile Photo" class="profile-img">
        
        <h1>Your Name</h1>
        <p>Short bio about what you do (e.g., Designer, Creator, Entrepreneur)</p>

        <a href="https://wa.me/yournumber" class="link-card">💬 Chat on WhatsApp</a>
        <a href="https://instagram.com/yourusername" class="link-card">📸 Follow on Instagram</a>
        <a href="https://linkedin.com/in/yourusername" class="link-card">💼 Connect on LinkedIn</a>
        <a href="mailto:yourname@email.com" class="link-card">📧 Email Me</a>
    </div>

</body>
</html>
