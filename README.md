<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Gaming Zone</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial,sans-serif;
}

body{
    background:#111;
    color:white;
}

header{
    background:#000;
    padding:20px;
    text-align:center;
}

header h1{
    color:#00ff88;
}

nav{
    margin-top:10px;
}

nav a{
    color:white;
    text-decoration:none;
    margin:0 15px;
}

.hero{
    text-align:center;
    padding:80px 20px;
}

.hero h2{
    font-size:40px;
    color:#00ff88;
}

.hero p{
    margin-top:10px;
}

.btn{
    display:inline-block;
    margin-top:20px;
    background:#00ff88;
    color:black;
    padding:12px 25px;
    text-decoration:none;
    border-radius:5px;
    font-weight:bold;
}

.games{
    padding:50px 20px;
    text-align:center;
}

.games h2{
    margin-bottom:30px;
}

.card-container{
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
    gap:20px;
}

.card{
    background:#222;
    width:250px;
    padding:20px;
    border-radius:10px;
}

.card h3{
    color:#00ff88;
    margin-bottom:10px;
}

footer{
    background:#000;
    text-align:center;
    padding:20px;
    margin-top:40px;
}
</style>

</head>
<body>

<header>
    <h1>Gaming Zone</h1>

    <nav>
        <a href="#">Home</a>
        <a href="#">Games</a>
        <a href="#">News</a>
        <a href="#">Contact</a>
    </nav>
</header>

<section class="hero">
    <h2>Welcome To Gaming Zone</h2>
    <p>Latest Gaming News, BGMI Tips & Tournament Updates</p>
    <a href="#" class="btn">Explore Now</a>
</section>

<section class="games">
    <h2>Featured Games</h2>

    <div class="card-container">

        <div class="card">
            <h3>BGMI</h3>
            <p>Battle Royale action with intense gameplay.</p>
        </div>

        <div class="card">
            <h3>Free Fire MAX</h3>
            <p>Fast-paced survival game with amazing graphics.</p>
        </div>

        <div class="card">
            <h3>Call Of Duty</h3>
            <p>Multiplayer shooting experience for gamers.</p>
        </div>

    </div>
</section>

<footer>
    <p>© 2026 Gaming Zone | Created By Shalini Singh</p>
</footer>

</body>
</html>