# NZK-MALCOLM
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pour Toi ❤️</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background: #000;
            color: white;
            font-family: 'Helvetica Neue', sans-serif;
            overflow-x: hidden;
        }
        .section {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 20px;
        }
        h1 { font-size: 2.5rem; margin-bottom: 20px; color: #ff3e6c; }
        p { font-size: 1.2rem; max-width: 600px; line-height: 1.6; }
        .heart { font-size: 50px; animation: beat 1s infinite; }
        @keyframes beat {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.2); }
        }
        .scroll-hint {
            position: absolute;
            bottom: 20px;
            font-size: 0.8rem;
            opacity: 0.6;
        }
        .highlight { color: #ff3e6c; font-weight: bold; }
    </style>
</head>
<body>

    <div class="section">
        <div class="heart">❤️</div>
        <h1>Aujourd'hui est un jour spécial...</h1>
        <p>Prends un moment pour toi. <br> Fais défiler vers le bas.</p>
        <div class="scroll-hint">Scrolle doucement ↓</div>
    </div>

    <div class="section" style="background: #111;">
        <h1>Parce que c'est TON jour</h1>
        <p>Je voulais te dire à quel point tu comptes pour moi. <br> Chaque moment passé à tes côtés est un <span class="highlight">cadeau</span>.</p>
    </div>

    <div class="section" style="background: #1a1a1a;">
        <h1>Joyeux Anniversaire ! 🎂</h1>
        <p>Que cette année soit remplie de rires, de succès et de beaucoup d'amour. Je serai toujours là pour te soutenir.</p>
        <div style="font-size: 40px; margin-top: 30px;">🥂 ✨ 🎁</div>
    </div>

</body>
</html>
