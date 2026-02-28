# Yoshi<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Port - Yoshi</title>

<!-- Ícones -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<style>
body {
    margin: 0;
    height: 100vh;
    background: linear-gradient(-45deg, #000000, #111111, #1a1a1a, #000000);
    background-size: 400% 400%;
    animation: gradientBG 10s ease infinite;
    display: flex;
    justify-content: center;
    align-items: center;
    font-family: Arial, sans-serif;
}

@keyframes gradientBG {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
}

.container {
    text-align: center;
    color: white;
    animation: fadeIn 1.5s ease-out;
    backdrop-filter: blur(10px);
    padding: 30px;
    border-radius: 20px;
}

@keyframes fadeIn {
    from {
        opacity: 0;
        transform: translateY(40px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

h1 {
    margin: 0 0 5px;
    font-size: 40px;
    letter-spacing: 3px;
}

p {
    font-size: 18px;
    opacity: 0.8;
    margin-bottom: 25px;
}

.social {
    width: 260px;
    margin: 10px auto;
    padding: 12px;
    border-radius: 12px;
    border: 1px solid white;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 10px;
    transition: 0.3s;
    text-decoration: none;
    color: white;
}

.social:hover {
    background: white;
    color: black;
    transform: scale(1.05);
    box-shadow: 0 0 15px white;
}

.social:active {
    transform: scale(0.95);
}

@media (max-width: 480px) {
    h1 {
        font-size: 30px;
    }

    .social {
        width: 220px;
        font-size: 14px;
    }
}
</style>
</head>

<body>

<div class="container">

    <h1>Yoshi</h1>
    <p>Editor</p>

    <!-- TikTok -->
    <a href="https://tiktok.com/@iamerise" target="_blank" rel="noopener noreferrer" class="social">
        <i class="fa-brands fa-tiktok"></i>
        TIKTOK
    </a>

    <!-- Instagram -->
    <a href="https://www.instagram.com/yoshiwq1?igsh=MW1ocThlMzlhYnRrbA==" target="_blank" rel="noopener noreferrer" class="social">
        <i class="fa-brands fa-instagram"></i>
        INSTAGRAM
    </a>

</div>

</body>
</html>
