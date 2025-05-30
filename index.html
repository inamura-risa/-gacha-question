<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <title>事業推進グループへようこそ！</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            text-align: center;
            margin: 0;
            padding: 20px;
            background-color: #f0f0f0;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
        }
        h1 {
            color: #333;
            font-size: 32px;
            margin-bottom: 30px;
        }
        .gacha-machine {
            width: 300px;
            margin: 0 auto;
            position: relative;
            cursor: pointer;
            height: auto;
            padding-bottom: 20px;
        }
        .arrow {
            position: relative;
            display: block;
            margin: 20px auto;
            font-size: 60px;
            font-weight: bold;
            color: #ff6b6b;
            animation: bounce 1s infinite;
            width: fit-content;
            transform: translateX(-50px);
        }
        @keyframes bounce {
            0%, 100% {
                transform: translateX(-50px) translateY(0);
            }
            50% {
                transform: translateX(-50px) translateY(-10px);
            }
        }
        .machine-body {
            width: 250px;
            height: 350px;
            position: relative;
        }
        .top-dome {
            width: 250px;
            height: 40px;
            background-color: #ff6b6b;
            border-radius: 20px 20px 0 0;
            position: absolute;
            top: 0;
        }
        .glass-container {
            width: 250px;
            height: 250px;
            background-color: #e6f7ff;
            position: absolute;
            top: 40px;
            border-radius: 125px 125px 0 0;
        }
        .base {
            width: 250px;
            height: 100px;
            background-color: #ff6b6b;
            position: absolute;
            bottom: 0;
        }
        .dispenser {
            width: 80px;
            height: 40px;
            background-color: #ddd;
            position: absolute;
            bottom: 30px;
            left: 85px;
            border-radius: 10px;
        }
        .dispenser-hole {
            width: 60px;
            height: 30px;
            background-color: #8b0000;
            position: absolute;
            bottom: 10px;
            left: 95px;
            border-radius: 15px 15px 0 0;
        }
        .capsule {
            width: 40px;
            height: 40px;
            position: absolute;
            border-radius: 20px;
            overflow: hidden;
        }
        .question-display {
            font-size: 24px;
            margin-top: 30px;
            padding: 20px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            min-height: 100px;
        }
        @keyframes rotate {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.8);
            z-index: 1000;
            opacity: 0;
            transition: opacity 0.3s ease-in-out;
        }
        .modal-content {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%) scale(0.7);
            background-color: white;
            padding: 40px;
            border-radius: 20px;
            width: 80%;
            max-width: 600px;
            text-align: center;
            transition: transform 0.3s ease-in-out;
        }
        .modal.show {
            display: block;
            opacity: 1;
        }
        .modal.show .modal-content {
            transform: translate(-50%, -50%) scale(1);
        }
        .modal-question {
            font-size: 32px;
            margin-bottom: 30px;
            color: #333;
            line-height: 1.4;
        }
        .back-button {
            background-color: #ff6b6b;
            color: white;
            border: none;
            padding: 15px 30px;
            font-size: 18px;
            border-radius: 10px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        .back-button:hover {
            background-color: #ff5252;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>事業推進グループへ ようこそ！</h1>
        <div class="gacha-machine">
            <div class="machine-body">
                <div class="top-dome"></div>
                <div class="glass-container" id="capsules-container"></div>
                <div class="base">
                    <div class="dispenser"></div>
                    <div class="dispenser-hole"></div>
                </div>
            </div>
        </div>
        <div class="arrow">↑</div>
        <div class="question-display" id="question">
            ガチャを回して質問に答えよう！
        </div>
    </div>

    <div class="modal" id="questionModal">
        <div class="modal-content">
            <div class="modal-question" id="modalQuestion"></div>
            <button class="back-button" onclick="closeModal()">もう一度ガチャを回す</button>
        </div>
    </div>

    <script>
        const questions = [
            "好きな食べ物は何ですか？",
            "休日は何をして過ごしますか？",
            "最近ハマっていることは？",
            "今までで一番印象に残っている旅行先は？",
            "学生時代の思い出を教えてください",
            "今一番行きたい場所はどこですか？",
            "特技は何ですか？",
            "最近見た面白い映画やドラマは？",
            "今チャレンジしてみたいことは？",
            "好きな季節とその理由は？",
            "仕事で大切にしていることは？",
            "将来の夢を教えてください",
            "趣味は何ですか？",
            "最近うれしかったことは？",
            "事業推進グループで挑戦したいことは？"
        ];

        const colorPairs = [
            ['#ff0000', '#0000ff'],
            ['#00ff00', '#ff0000'],
            ['#ffff00', '#0000ff'],
            ['#ff0000', '#00ff00'],
            ['#ffff00', '#00ff00']
        ];

        function createCapsules() {
            const container = document.getElementById('capsules-container');
            for (let i = 0; i < 12; i++) {
                const capsule = document.createElement('div');
                capsule.className = 'capsule';
                const colorPair = colorPairs[Math.floor(Math.random() * colorPairs.length)];
                
                capsule.style.left = Math.random() * 200 + 'px';
                capsule.style.top = Math.random() * 200 + 'px';
                capsule.style.transform = `rotate(${Math.random() * 360}deg)`;
                
                capsule.style.background = `linear-gradient(90deg, 
                    ${colorPair[0]} 0%, 
                    ${colorPair[0]} 50%, 
                    ${colorPair[1]} 50%, 
                    ${colorPair[1]} 100%)`;
                
                container.appendChild(capsule);
            }
        }

        function turnGacha() {
            const container = document.getElementById('capsules-container');
            container.style.animation = 'rotate 1s linear';
            
            document.querySelector('.arrow').style.display = 'none';
            
            setTimeout(() => {
                const randomIndex = Math.floor(Math.random() * questions.length);
                const question = questions[randomIndex];
                document.getElementById('question').textContent = question;
                document.getElementById('modalQuestion').textContent = question;
                container.style.animation = '';
                
                showModal();
            }, 1000);
        }

        function showModal() {
            const modal = document.getElementById('questionModal');
            modal.style.display = 'block';
            setTimeout(() => {
                modal.classList.add('show');
            }, 10);
        }

        function closeModal() {
            const modal = document.getElementById('questionModal');
            modal.classList.remove('show');
            setTimeout(() => {
                modal.style.display = 'none';
                document.querySelector('.arrow').style.display = 'block';
            }, 300);
        }

        // 初期化
        createCapsules();
        document.querySelector('.gacha-machine').addEventListener('click', turnGacha);
    </script>
</body>
</html>
