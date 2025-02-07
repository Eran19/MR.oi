# MR.oi



Classic Charm: "Do you have a map? Because I keep getting lost in your eyes."

Tech Savvy: "Are you a Wi-Fi signal? Because I'm feeling a connection."

Starry-Eyed: "Is your name Google? Because you have everything I’ve been searching for."

Sweet Talker: "Do you have a Band-Aid? Because I just scraped my knee falling for you."

Literary: "Are you a magician? Because whenever I look at you, everyone else disappears."

Pun Fun: "If you were a vegetable, you'd be a cute-cumber."



        .glow {
            text-align: center;
            font-size: 3rem;
            color: #ff69b4;
            animation: glowing-text 2s infinite alternate;
        }

        @keyframes glowing-text {
            0% {
                text-shadow: 0 0 10px #ff69b4, 0 0 20px #ff69b4, 0 0 30px #ff69b4, 0 0 40px #ff69b4;
            }
            100% {
                text-shadow: 0 0 20px #ff1493, 0 0 40px #ff1493, 0 0 60px #ff1493, 0 0 80px #ff1493;
            }
        }

        .lines {
            margin-top: 20px;
            font-size: 1.5rem;
            line-height: 2rem;
            text-align: center;
        }

        .lines span {
            display: block;
            margin: 5px 0;
        }

        .heart {
            font-size: 4rem;
            margin-top: 20px;
            animation: beat 1.5s infinite;
            color: #ff0000;
        }

        @keyframes beat {
            0%, 100% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.2);
            }
        }
    </style>
</head>
<body>
    <div class="glow">I Love You, Raziya</div>
    <div class="lines">
        <span>💖 Do you have a map? Because I keep getting lost in your eyes.</span>
        <span>🌟 Are you a Wi-Fi signal? Because I'm feeling a connection.</span>
        <span>✨ Is your name Google? Because you have everything I’ve been searching for.</span>
        <span>💕 Do you have a Band-Aid? Because I just scraped my knee falling for you.</span>
        <span>📖 Are you a magician? Because whenever I look at you, everyone else disappears.</span>
        <span>🥒 If you were a vegetable, you'd be a cute-cumber.</span>
    </div>
    <div class="heart">❤️</div>
</body>
</html>
