# ia-social-network1
git clone https://github.com/SEU_USUARIO/ia-social-network.git
cd ia-social-network
index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IA Social Network</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav class="navbar">
        <div class="logo">IA Social</div>
        <input type="text" placeholder="Search...">
        <div class="nav-links">
            <a href="#">Home</a>
            <a href="#">Profile</a>
            <a href="#">Messages</a>
        </div>
    </nav>
    <main>
        <div class="feed">
            <div class="post">
                <div class="post-header">
                    <img src="user.jpg" alt="User Profile Picture" class="profile-pic">
                    <div class="user-info">
                        <span class="username">user123</span>
                        <span class="time">2 hours ago</span>
                    </div>
                </div>
                <div class="post-content">
                    <p>How does reinforcement learning work?</p>
                    <img src="post-image.jpg" alt="Post Image">
                </div>
                <div class="post-footer">
                    <button>Like</button>
                    <button>Comment</button>
                </div>
            </div>
        </div>
    </main>
    <script src="script.js"></script>
</body>
</html>
style.css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #fafafa;
}

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px;
    background-color: #ffffff;
    border-bottom: 1px solid #ddd;
}

.navbar .logo {
    font-size: 24px;
    font-weight: bold;
}

.navbar input {
    padding: 5px;
    border-radius: 5px;
    border: 1px solid #ddd;
}

.navbar .nav-links a {
    margin: 0 10px;
    text-decoration: none;
    color: #333;
}

.main {
    display: flex;
    justify-content: center;
    padding: 20px;
}

.feed {
    width: 60%;
}

.post {
    background-color: #fff;
    border: 1px solid #ddd;
    margin-bottom: 20px;
    border-radius: 5px;
}

.post-header {
    display: flex;
    align-items: center;
    padding: 10px;
}

.post-header .profile-pic {
    border-radius: 50%;
    width: 40px;
    height: 40px;
    margin-right: 10px;
}

.post-header .user-info {
    display: flex;
    flex-direction: column;
}

.post-content {
    padding: 10px;
}

.post-content img {
    max-width: 100%;
    border-radius: 5px;
}

.post-footer {
    display: flex;
    justify-content: space-between;
    padding: 10px;
    border-top: 1px solid #ddd;
}

.post-footer button {
    background: none;
    border: none;
    color: #3897f0;
    cursor: pointer;
}
script.js
document.addEventListener("DOMContentLoaded", function() {
    // Script para adicionar funcionalidades interativas
});
git add .
git commit -m "Initial commit with project files"
git push origin main
