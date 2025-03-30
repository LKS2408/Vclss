# Vclass
Trang học trực tuyến
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vclass - Học trực tuyến</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f4f4f4;
        }
        .navbar {
            background-color: #007bff;
            padding: 15px;
        }
        .navbar a {
            color: white;
            text-decoration: none;
            padding: 15px;
            font-size: 18px;
            display: inline-block;
        }
        .navbar a:hover {
            background-color: #0056b3;
            border-radius: 5px;
        }
        .logo {
            width: 120px;
            margin: 20px auto;
        }
        .container {
            padding: 20px;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            background-color: #28a745;
            color: white;
            border: none;
            cursor: pointer;
            margin-top: 10px;
        }
        button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>

    <!-- Thanh menu điều hướng -->
    <div class="navbar">
        <a href="#">Trang chủ</a>
        <a href="#">Khóa học</a>
        <a href="#">Giáo viên</a>
        <a href="#">Liên hệ</a>
    </div>

    <!-- Logo -->
    <img src="https://via.placeholder.com/120" alt="Logo Vclass" class="logo">

    <!-- Nội dung chính -->
    <div class="container">
        <h1>Chào mừng đến với Vclass!</h1>
        <p>Học tập mọi lúc, mọi nơi với các khóa học chất lượng.</p>
        <button onclick="showMessage()">Bắt đầu học</button>
    </div>

    <script>
        function showMessage() {
            alert("Chào bạn! Hãy bắt đầu hành trình học tập nào!");
        }
    </script>

</body>
</html>
