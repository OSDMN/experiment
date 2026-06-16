
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>家庭亲社会行为实验</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background: #f0f4f8;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
        }
        .container {
            text-align: center;
            background: white;
            padding: 40px 60px;
            border-radius: 12px;
            box-shadow: 0 4px 20px rgba(0,0,0,0.1);
        }
        h1 {
            color: #2c3e50;
            margin-bottom: 0.5em;
        }
        p {
            color: #555;
            font-size: 18px;
            margin-bottom: 2em;
        }
        .key-hint {
            display: inline-block;
            background: #3498db;
            color: white;
            padding: 10px 30px;
            border-radius: 30px;
            font-size: 22px;
            animation: pulse 1.5s infinite;
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>家庭亲社会行为实验</h1>
        <p>感谢您的参与！<br>请认真阅读指导语并完成全部任务。</p>
        <div class="key-hint">按任意键开始</div>
        <p style="margin-top: 20px; font-size: 14px; color: #888;">（或点击页面任意位置）</p>
    </div>

    <script>
        function startExperiment() {
            window.location.href = 'experiment.html';
        }
        document.addEventListener('keydown', startExperiment, { once: true });
        document.addEventListener('click', startExperiment, { once: true });
    </script>
</body>
</html>
