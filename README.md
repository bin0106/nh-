<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chúc Mừng 8/3</title>
    <style>
        body {
            text-align: center;
            background-color: pink;
            font-family: Arial, sans-serif;
            overflow: hidden;
        }
        h1 {
            font-size: 50px;
            color: white;
            text-shadow: 2px 2px 5px red;
            animation: glow 1s infinite alternate;
        }
        @keyframes glow {
            from { text-shadow: 2px 2px 5px red; }
            to { text-shadow: 4px 4px 10px yellow; }
        }
        .heart {
            position: absolute;
            font-size: 30px;
            animation: float 4s linear infinite;
        }
        @keyframes float {
            from { transform: translateY(100vh); }
            to { transform: translateY(-10vh); }
        }
    </style>
</head>
<body>

    <h1>💖 Chúc NHư Ngày 8/3 💖</h1>
    <P> chúc bà ngày 8 tháng 3 zui zẻ với mọi điều hạnh phúc nha, cho phép tui làm quen với như nha </p>
    <script>
        function createHeart() {
            const heart = document.createElement("div");
            heart.innerHTML = "💗";
            heart.classList.add("heart");
            document.body.appendChild(heart);

            heart.style.left = Math.random() * 100 + "vw";
            heart.style.animationDuration = Math.random() * 3 + 2 + "s";

            setTimeout(() => {
                heart.remove();
            }, 5000);
        }
        setInterval(createHeart, 300);
    </script>

</body>
</html>
Đã gửi
Viết cho
