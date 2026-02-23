<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Site</title>
    <style>
        body {
            font-family: 'Fira Code', monospace, Arial, sans-serif;
            max-width: 700px;
            margin: 50px auto;
            padding: 0 20px;
            line-height: 1.6;
            color: #e0e0e0;
            background: linear-gradient(135deg, #1e1e2f, #2b2b3c, #3a3a50);
            background-attachment: fixed;
            text-align: center; /* center everything by default */
        }
        h1 {
            border-bottom: 2px solid #8ec6c5;
            padding-bottom: 10px;
            color: #8ec6c5;
        }
        h2 {
            color: #a0d2db;
        }
        a {
            color: #ffd580;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .section {
            background: rgba(40, 40, 50, 0.85);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.5);
            margin-bottom: 30px;
            border-left: 4px solid #8ec6c5;
            text-align: left; /* keep section content left-aligned */
        }
        ul {
            list-style: none;
            padding-left: 0;
        }
        li::before {
            content: "💻 ";
        }
        li {
            margin-bottom: 10px;
        }

        /* Profile image */
        .profile-pic {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 4px solid #8ec6c5;
            margin-bottom: 20px;
        }

        /* Waving hand animation */
        .wave-hand {
            display: inline-block;
            animation: wave 1.5s infinite;
            transform-origin: 70% 70%;
        }
        @keyframes wave {
            0% { transform: rotate(0deg); }
            15% { transform: rotate(14deg); }
            30% { transform: rotate(-8deg); }
            45% { transform: rotate(14deg); }
            60% { transform: rotate(-4deg); }
            75% { transform: rotate(10deg); }
            100% { transform: rotate(0deg); }
        }
    </style>
</head>
<body>
    <!-- Profile Picture -->
    <img src=<img width="1024" height="1024" alt="Boniface1818_profile_compressed" src="https://github.com/user-attachments/assets/8a7d7bd9-5ed8-4b47-9d83-86f619092bda" />
 alt="Boniface Kagunda" class="profile-pic">

    <h1>Welcome! I'm Boniface Kagunda <span class="wave-hand">👋</span></h1>

    <div class="section">
        <h2>About Me 🎵</h2>
        <p>I'm a student currently learning Programming and Web Development.
           I enjoy coding, solving problems, and exploring new technologies.</p>
    </div>

    <div class="section">
        <h2>Learning Goals 🎯</h2>
        <ul>
            <li>🐍 Master Python basics</li>
            <li>🌐 Build a simple website</li>
            <li>💾 Practice Git and GitHub daily</li>
            <li>🎵 Explore music production</li>
        </ul>
    </div>

    <div class="section">
        <h2>What I'm Learning 📚</h2>
        <ul>
            <li>Git and GitHub</li>
            <li>Python, JavaScript</li>
        </ul>
    </div>

    <div class="section">
        <h2>Links 🔗</h2>
        <ul>
            <li><a href="https://github.com/Boniface1818" target="_blank">My GitHub Profile</a></li>
        </ul>
    </div>
</body>
</html>
