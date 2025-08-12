# Sorry-
I love you so much cutu 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For My Love Shagaf 💖</title>
<style>
    body {
        margin: 0;
        font-family: 'Poppins', sans-serif;
        background: linear-gradient(135deg, #ff9a9e, #fad0c4);
        height: 100vh;
        display: flex;
        align-items: center;
        justify-content: center;
        text-align: center;
    }
    .container {
        background: rgba(255, 255, 255, 0.2);
        padding: 30px;
        border-radius: 20px;
        box-shadow: 0 0 40px rgba(255, 182, 193, 0.8);
        backdrop-filter: blur(10px);
        max-width: 500px;
        width: 90%;
    }
    h1 {
        font-size: 2.5rem;
        color: white;
        text-shadow: 2px 2px 5px rgba(255, 0, 90, 0.8);
        animation: glow 2s infinite alternate;
    }
    @keyframes glow {
        from { text-shadow: 0 0 10px #ff4d79; }
        to { text-shadow: 0 0 25px #ff1a66; }
    }
    input {
        padding: 10px;
        border-radius: 10px;
        border: none;
        outline: none;
        width: 80%;
        margin-top: 15px;
        font-size: 1rem;
    }
    button {
        margin-top: 15px;
        padding: 10px 20px;
        border: none;
        border-radius: 10px;
        background: #ff4d79;
        color: white;
        font-size: 1rem;
        cursor: pointer;
        transition: 0.3s;
    }
    button:hover {
        background: #ff1a66;
    }
    p {
        font-size: 1.2rem;
        color: white;
    }
</style>
</head>
<body>

<div class="container" id="page1">
    <h1>For the love of my life Shagaf 💖</h1>
    <p>Every heartbeat of mine whispers your name, and every breath carries my love for you...</p>
    <input type="password" id="password1" placeholder="Enter Password">
    <button onclick="goInside()">Go Inside 💌</button>
</div>

<div class="container" id="page2" style="display: none;">
    <h1>My Dearest Shagaf 💖</h1>
    <p>
        I am truly sorry, my love.  
        Not just with words, but with my heart
        poz ho skae to mujhe maaf kar dena cutu 
        mai genuinely sorry mangna chahta hun aapse
        Shagaf aap merko bhot jyada pasand ho aur mai         hamesha se hi bhot jyada pagal deewana hun aapke piche
        Please meri cutu,meri kuchu puchu,meri princess,meei duniya,meri jaan ho sake to maaf kar dena 
        i love you shaggi❤️💖💞💝💘💕❣️❤️‍🩹💓💕
    </p>
    <input type="password" id="password2" placeholder="Enter Password">
    <button onclick="goBack()">Back to Love 💞</button>
</div>

<script>
function goInside() {
    let pass = document.getElementById("password1").value.trim().toLowerCase();
    if (pass === "i love you fahad") {
        document.getElementById("page1").style.display = "none";
        document.getElementById("page2").style.display = "block";
    } else {
        alert("Wrong Password! 💔");
    }
}

function goBack() {
    let pass = document.getElementById("password2").value.trim().toLowerCase();
    if (pass === "i love you fahad") {
        document.getElementById("page2").style.display = "none";
        document.getElementById("page1").style.display = "block";
    } else {
        alert("Wrong Password! 💔");
    }
}
</script>

</body>
</html>
