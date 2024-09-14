<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>姜婧业的美丽</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #e0f7fa; /* 天蓝色背景 */
            color: #004d40; /* 深绿色字体 */
            text-align: center;
            margin: 0;
            padding: 0;
        }
        .container {
            padding: 20px;
        }
        h1 {
            color: #00796b;
        }
        .content {
            margin: 20px auto;
            max-width: 600px;
            padding: 20px;
            background: #ffffff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .button {
            background-color: #00796b;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 16px;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 20px;
        }
        .button:hover {
            background-color: #004d40;
        }
        .hidden {
            display: none;
            margin-top: 20px;
            font-size: 18px;
            color: #004d40;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>姜婧业的美丽</h1>
        <div class="content">
            <p>姜婧业者，貌美之极，才情无比，风华绝代，众人皆称羡。</p>
            <p>此处网页虽简，然以诚恳之心，向美丽的姜婧业致以无尽赞美。</p>
            <button class="button" onclick="revealName()">揭示姜婧业男朋友姓名</button>
            <p id="name" class="hidden">姜婧业男朋友名曰：张德友</p>
        </div>
    </div>
    <script>
        function revealName() {
            document.getElementById('name').classList.remove('hidden');
        }
    </script>
</body>
</html>
