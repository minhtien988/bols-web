<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Ủng hộ BOLOS bằng Ethereum</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: #121212;
            color: #eee;
            text-align: center;
            padding: 20px;
            max-width: 600px;
            margin: auto;
        }
        h1 {
            color: #00d8ff;
            margin-bottom: 10px;
        }
        p {
            font-size: 1.1rem;
            margin: 10px 0 30px 0;
            line-height: 1.5;
        }
        .status {
            background: #1f1f1f;
            border-radius: 12px;
            padding: 15px 20px;
            margin-bottom: 30px;
            text-align: left;
            font-size: 1rem;
            line-height: 1.4;
            box-shadow: 0 0 15px #00d8ff77;
        }
        .game-image {
            width: 100%;
            max-width: 350px;
            border-radius: 15px;
            box-shadow: 0 0 15px #00d8ffaa;
            margin-bottom: 20px;
        }
        .gallery {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-bottom: 30px;
        }
        .gallery img {
            width: 150px;
            border-radius: 12px;
            box-shadow: 0 0 10px #00d8ffaa;
        }
        .wallet {
            background: #222;
            padding: 15px 20px;
            border-radius: 12px;
            font-family: monospace;
            word-break: break-all;
            user-select: all;
            margin-bottom: 20px;
            font-size: 1.1rem;
        }
        .qr-code {
            margin: 0 auto 30px auto;
            width: 200px;
            height: 200px;
            box-shadow: 0 0 12px #00d8ffbb;
            border-radius: 15px;
        }
        footer {
            font-size: 0.9rem;
            color: #666;
            margin-top: 50px;
        }
        a {
            color: #00d8ff;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <h1>Ủng hộ trò chơi BOLOS</h1>
    <p>
        Xin chào! Đây là dự án game BOLOS do mình phát triển.<br />
        Nếu bạn thích game, hãy ủng hộ mình bằng Ethereum để mình có thể phát triển tiếp nhé! 🙏
    </p>

    <div class="status">
        <strong>Trạng thái phát triển game BOLOS:</strong>
        <ul>
            <li>BOLOS hiện đang trong giai đoạn phát triển thử nghiệm alpha, mọi tính năng cơ bản đã hoàn thành, nhưng vẫn cần nhiều phản hồi từ người chơi để hoàn thiện.</li>
            <li>Đã có hơn 100 người chơi trải nghiệm bản thử nghiệm và gửi về nhiều ý kiến quý giá.</li>
            <li>Đội ngũ phát triển đang tập trung tối ưu hiệu năng và thêm các chế độ chơi mới trong các bản cập nhật sắp tới.</li>
            <li>Mục tiêu của BOLOS là tạo ra một trải nghiệm game giải trí hấp dẫn, dễ chơi nhưng đầy thử thách và mang tính cạnh tranh cao.</li>
            <li>Người chơi có thể theo dõi tiến độ phát triển và tham gia cộng đồng để góp ý và nhận quà đặc biệt trong tương lai.</li>
        </ul>
    </div>

    <img class="game-image" src="https://cdn.pixabay.com/photo/2014/04/03/10/00/pixel-309014_1280.png" alt="Hình minh họa trò chơi BOLOS" />

    <div class="gallery">
        <img src="https://cdn.pixabay.com/photo/2016/04/01/11/02/video-game-1309547_1280.png" alt="Game screenshot 1" />
        <img src="https://cdn.pixabay.com/photo/2016/04/01/11/01/video-game-1309534_1280.png" alt="Game screenshot 2" />
    </div>

    <div class="wallet">Địa chỉ ví Ethereum:<br />0xbA996eaD8a528B67b0A119dD3543F6365BD6cCED</div>
    
    <img
        class="qr-code"
        src="https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=ethereum:0xbA996eaD8a528B67b0A119dD3543F6365BD6cCED"
        alt="Mã QR ví Ethereum"
    />
    
    <footer>
        Cảm ơn bạn đã quan tâm và ủng hộ!<br />
        <a href="https://ethereum.org/" target="_blank" rel="noopener noreferrer">Tìm hiểu thêm về Ethereum</a>
    </footer>
</body>
</html>
