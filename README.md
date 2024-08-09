<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trang Web Cá Nhân</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        header {
            background-color: #e0f7fa;
            padding: 20px;
            text-align: center;
        }
        .logo {
            width: 100px;
            height: auto;
        }
        nav {
            margin: 10px 0;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #00796b;
            font-weight: bold;
        }
        .container {
            width: 80%;
            margin: auto;
        }
        .section {
            padding: 20px;
            background-color: #ffffff;
            margin-bottom: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .footer {
            background-color: #00796b;
            color: #ffffff;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .login-form, .register-form {
            max-width: 300px;
            margin: auto;
        }
        .login-form input, .register-form input {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #00796b;
            border-radius: 4px;
        }
        .login-form button, .register-form button {
            width: 100%;
            padding: 10px;
            background-color: #00796b;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        .login-form button:hover, .register-form button:hover {
            background-color: #004d40;
        }
        .advertisement {
            background-color: #ffebee;
            padding: 20px;
            border-radius: 8px;
            text-align: center;
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <header>
        <img src="logo.png" alt="Logo" class="logo">
        <nav>
            <a href="#about">Giới thiệu</a>
            <a href="#login">Đăng nhập</a>
            <a href="#register">Đăng ký</a>
            <a href="#advertisement">Quảng cáo</a>
        </nav>
    </header>

    <div class="container">
        <section id="about" class="section">
            <h2>Giới thiệu bản thân</h2>
            <p>Chào mừng bạn đến với trang web cá nhân của tôi! Tôi là một người yêu thích học tiếng Anh và hiện tại tôi đang tìm kiếm cơ hội để phát triển bản thân hơn nữa trong lĩnh vực này.</p>
        </section>

        <section id="login" class="section">
            <h2>Đăng nhập</h2>
            <form class="login-form">
                <input type="text" placeholder="Tên người dùng" required>
                <input type="password" placeholder="Mật khẩu" required>
                <button type="submit">Đăng nhập</button>
            </form>
        </section>

        <section id="register" class="section">
            <h2>Đăng ký</h2>
            <form class="register-form">
                <input type="text" placeholder="Tên người dùng" required>
                <input type="email" placeholder="Email" required>
                <input type="password" placeholder="Mật khẩu" required>
                <button type="submit">Đăng ký</button>
            </form>
        </section>

        <section id="advertisement" class="section">
            <div class="advertisement">
                <h2>Quảng cáo</h2>
                <p>Đây là khu vực dành cho quảng cáo. Bạn có thể thêm các thông tin quảng cáo hoặc thông báo quan trọng ở đây.</p>
            </div>
        </section>
    </div>

    <footer class="footer">
        <p>&copy; 2024 Trang Web Cá Nhân. Tất cả các quyền được bảo lưu.</p>
    </footer>
</body>
</html>
