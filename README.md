# <style>
    .custom-social-connect {
        font-family: Arial, sans-serif;
        text-align: center;
        padding: 40px 15px;
        background-color: #fcfcfd; /* Màu nền nhạt */
    }

    .custom-social-connect .social-header h2 {
        font-size: 32px;
        font-weight: bold;
        color: #2b303a;
        margin-bottom: 10px;
    }

    /* Hiệu ứng chữ chuyển màu cho "Mọi Nền Tảng" */
    .custom-social-connect .gradient-text {
        background: linear-gradient(90deg, #6a11cb 0%, #2575fc 100%);
        background: linear-gradient(to right, #4a00e0, #8e2de2);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
    }

    .custom-social-connect .social-header p {
        color: #888;
        font-size: 15px;
        max-width: 600px;
        margin: 0 auto 30px auto;
        line-height: 1.5;
    }

    .custom-social-cards {
        display: flex;
        justify-content: center;
        gap: 20px;
        flex-wrap: wrap;
    }

    .custom-social-card {
        background-color: #2b3240; /* Màu nền thẻ tối */
        border-radius: 16px;
        padding: 30px 20px;
        width: 280px;
        box-sizing: border-box;
        box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    .social-icon-wrapper {
        width: 60px;
        height: 60px;
        border-radius: 12px;
        display: flex;
        align-items: center;
        justify-content: center;
        margin-bottom: 15px;
    }

    .social-icon-wrapper img {
        width: 40px;
        height: 40px;
        border-radius: 8px;
    }

    .custom-social-card h3 {
        color: #ffffff;
        font-size: 20px;
        margin: 0 0 5px 0;
    }

    .custom-social-card p.sub-title {
        color: #a0a5b1;
        font-size: 14px;
        margin: 0 0 20px 0;
    }

    .qr-box {
        background-color: #ffffff;
        padding: 10px;
        border-radius: 12px;
        width: 150px;
        height: 150px;
        margin-bottom: 20px;
    }

    .qr-box img {
        width: 100%;
        height: 100%;
        object-fit: cover;
    }

    .social-btn {
        width: 100%;
        padding: 12px 0;
        border-radius: 8px;
        text-decoration: none;
        font-weight: bold;
        font-size: 14px;
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 8px;
        transition: opacity 0.3s ease;
    }

    .social-btn:hover {
        opacity: 0.85;
    }

    /* Các nút có màu riêng biệt */
    .btn-facebook {
        background-color: #1877F2;
        color: #ffffff;
    }
    .btn-tiktok {
        background-color: #ffffff;
        color: #000000;
    }
    .btn-zalo {
        background-color: #0088FF;
        color: #ffffff;
    }
</style>

<div class="custom-social-connect">
    <div class="social-header">
        <h2>Kết Nối Với Chúng Tôi Trên <span class="gradient-text">Mọi Nền Tảng</span></h2>
        <p>Hãy chọn kênh truyền thông yêu thích của bạn hoặc sử dụng máy ảnh điện thoại quét mã QR để theo dõi tin tức mới nhất!</p>
    </div>

    <div class="custom-social-cards">
        <!-- Thẻ Facebook -->
        <div class="custom-social-card">
            <div class="social-icon-wrapper">
                <!-- Thay thế link ảnh icon Facebook của bạn -->
                <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Facebook_Logo_%282019%29.png" alt="Facebook">
            </div>
            <h3>Facebook</h3>
            <p class="sub-title">Fanpage Chính Thức</p>
            <div class="qr-box">
                <!-- Thay thế link ảnh QR Facebook của bạn -->
                <img src="https://storage3.me-qr.com/qr/408083953.png" alt="QR Facebook">
            </div>
            <a href="https://www.facebook.com/southchimex" class="social-btn btn-facebook">Truy Cập Fanpage ↗</a>
        </div>

        <!-- Thẻ TikTok -->
        <div class="custom-social-card">
            <div class="social-icon-wrapper">
                <!-- Thay thế link ảnh icon TikTok của bạn -->
                <img src="https://upload.wikimedia.org/wikipedia/commons/e/e8/Tiktok_logo.png?utm_source=commons.wikimedia.org&utm_campaign=index&utm_content=original" alt="TikTok">
            </div>
            <h3>TikTok</h3>
            <p class="sub-title">Kênh Tin Tức</p>
            <div class="qr-box">
                <!-- Thay thế link ảnh QR TikTok của bạn -->
                <img src="https://storage3.me-qr.com/qr/408091687.png" alt="QR TikTok">
            </div>
            <a href="https://www.tiktok.com/@ctycpxnk.hoachatmiennam" class="social-btn btn-tiktok">Xem Kênh TikTok ↗</a>
        </div>

        <!-- Thẻ Zalo -->
        <div class="custom-social-card">
            <div class="social-icon-wrapper">
                <!-- Thay thế link ảnh icon Zalo của bạn -->
                <img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Icon_of_Zalo.svg?utm_source=commons.wikimedia.org&utm_campaign=index&utm_content=original" alt="Zalo">
            </div>
            <h3>Zalo</h3>
            <p class="sub-title">Kết nối tức thời</p>
            <div class="qr-box">
                <!-- Thay thế link ảnh QR Zalo của bạn -->
                <img src="https://storage3.me-qr.com/qr/408099841.png" alt="QR Zalo">
            </div>
            <a href="https://zalo.me/g/ay9vau9tbscx8pdfg1e9" class="social-btn btn-zalo">Nhắn Tin Zalo ↗</a>
        </div>
    </div>
</div>
