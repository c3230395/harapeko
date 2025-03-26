<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Music Log</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            background-color: #f8f9fa;
            color: #333;
        }
        .navbar {
            background-color: #ffcc00;
        }
        .album-cover {
            width: 100px;
            height: 100px;
            object-fit: cover;
            border-radius: 8px;
        }
        .card {
            border: none;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-light">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">🎵 Music Log</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item"><a class="nav-link active" href="#">ホーム</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">マイログ</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">設定</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">ランキング</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">おすすめ</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <div class="container mt-5">
        <h2 class="mb-4">あなたの今月の音楽</h2>
        <button class="btn btn-primary mb-3">新しい曲を追加</button>
        <div class="row">
            <div class="col-md-3">
                <div class="card">
                    <img src="https://via.placeholder.com/100" class="album-cover card-img-top" alt="Album Cover">
                    <div class="card-body">
                        <h5 class="card-title">アルバム名</h5>
                        <p class="card-text">アーティスト名</p>
                        <button class="btn btn-outline-primary">詳細を見る</button>
                    </div>
                </div>
            </div>
            <div class="col-md-3">
                <div class="card">
                    <img src="https://via.placeholder.com/100" class="album-cover card-img-top" alt="Album Cover">
                    <div class="card-body">
                        <h5 class="card-title">アルバム名</h5>
                        <p class="card-text">アーティスト名</p>
                        <button class="btn btn-outline-primary">詳細を見る</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
