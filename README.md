# My-Love
<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Love ❤️</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #ffe6f2;
            color: #d63384;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ff99cc;
            padding: 20px;
            font-size: 24px;
            font-weight: bold;
            color: white;
        }
        .container {
            margin: 20px auto;
            max-width: 600px;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .btn {
            display: inline-block;
            background-color: #ff66a3;
            color: white;
            padding: 10px 20px;
            margin: 10px;
            border-radius: 5px;
            text-decoration: none;
            transition: 0.3s;
        }
        .btn:hover {
            background-color: #ff3385;
        }
        img {
            width: 100%;
            border-radius: 10px;
            margin-top: 10px;
        }
    </style>
</head>
<body>

    <header>❤️ Love Story ❤️</header>

    <div class="container">
        <h2>เรารักกันมาแล้วกี่วัน?</h2>
        <p id="loveDays"></p>

        <h2>ความทรงจำของเรา</h2>
        <img src="https://source.unsplash.com/400x300/?love,couple" alt="Love Image">
        
        <h2>ถึงที่รัก 💖</h2>
        <p>ขอบคุณที่อยู่เคียงข้างกันเสมอ รักมากๆ นะ! 😘</p>

        <a href="#" class="btn">ดูรูปภาพเพิ่มเติม</a>
    </div>

    <script>
        // คำนวณจำนวนวันที่รักกัน
        const startDate = new Date("2022-01-01"); // เปลี่ยนเป็นวันที่คบกัน
        const today = new Date();
        const timeDiff = today - startDate;
        const days = Math.floor(timeDiff / (1000 * 60 * 60 * 24));
        document.getElementById("loveDays").innerText = `เรารักกันมาแล้ว ${days} วัน 💕`;
    </script>

</body>
</html>
</html>
