<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>CÔNG TY TNHH TƯ VẤN THIẾT KẾ VÀ XÂY DỰNG TRUNG NGUYỄN | xaydungtrungnguyen.com</title>
    <meta name="description" content="CÔNG TY TNHH TƯ VẤN THIẾT KẾ VÀ XÂY DỰNG TRUNG NGUYỄN - Chuyên tư vấn thiết kế kiến trúc, nội thất, thi công phần thô, hoàn thiện và xây nhà trọn gói uy tín tại Đà Nẵng. Hotline: 0908.561.719.">
    <meta name="keywords" content="xây dựng trung nguyễn, xaydungtrungnguyen.com, thiết kế xây dựng đà nẵng, thi công trọn gói đà nẵng, thi công phần thô đà nẵng">

    <!-- Meta Open Graph & Thumbnail Logo khi chia sẻ đường link website -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://xaydungtrungnguyen.com/">
    <meta property="og:site_name" content="Xây Dựng Trung Nguyễn">
    <meta property="og:title" content="CÔNG TY TNHH TƯ VẤN THIẾT KẾ VÀ XÂY DỰNG TRUNG NGUYỄN">
    <meta property="og:description" content="Tư vấn thiết kế kiến trúc - Thi công phần thô - Hoàn thiện & Xây nhà trọn gói chuyên nghiệp tại Đà Nẵng. Địa chỉ: 83 Hói Kiểng 18, Phường Ngũ Hành Sơn, TP Đà Nẵng. Hotline: 0908.561.719.">
    <meta property="og:image" content="https://placehold.co/1200x630/0F2A47/C89B3C?text=XAY+DUNG+TRUNG+NGUYEN%0Axaydungtrungnguyen.com+%7C+0908.561.719">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY TNHH TƯ VẤN THIẾT KẾ VÀ XÂY DỰNG TRUNG NGUYỄN">
    <meta name="twitter:description" content="Thiết kế kiến trúc, nội thất & thi công xây dựng uy tín tại Đà Nẵng. Hotline: 0908.561.719">
    <meta name="twitter:image" content="https://placehold.co/1200x630/0F2A47/C89B3C?text=XAY+DUNG+TRUNG+NGUYEN%0Axaydungtrungnguyen.com+%7C+0908.561.719">

    <!-- Favicon đồng bộ logo công ty (SVG gọn nhẹ) -->
    <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='12' fill='%230F2A47'/%3E%3Cpath d='M14 48V24l18-12 18 12v24h-8V28.5L32 22l-10 6.5V48h-8z' fill='%23C89B3C'/%3E%3Cpath d='M27 48V34h10v14h-10z' fill='%23FFFFFF'/%3E%3C/svg%3E">

    <!-- Font Inter chuẩn hiện đại & dễ đọc -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        /* Cấu hình bảng màu đồng bộ theo Logo Trung Nguyễn (Navy Kiến Trúc & Vàng Đồng) */
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
                    },
                    colors: {
                        tnNavy: {
                            DEFAULT: '#0F2A47',
                            dark: '#091B30',
                            light: '#1B3F66',
                        },
                        tnGold: {
                            DEFAULT: '#C89B3C',
                            dark: '#A67C23',
                            light: '#E3BC65',
                            soft: '#FAF5E8',
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Quy tắc chuẩn chống tràn viền & lệch phải tuyệt đối trên mọi màn hình */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100%;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            color: #1E293B;
            background-color: #FFFFFF;
            scroll-behavior: smooth;
        }

        /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình */
        .tn-container {
            width: 94%;
            max-width: 94%;
            margin-left: auto;
            margin-right: auto;
        }
        @media (min-width: 1024px) {
            .tn-container {
                width: 95%;
                max-width: 95%;
            }
        }

        /* Định dạng thanh menu máy tính: chữ nhỏ gọn, viết liền không xuống dòng từng danh mục */
        .desktop-nav-list {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: flex-end;
            gap: 2px 6px;
        }
        .desktop-nav-item {
            position: relative;
            flex-shrink: 0;
        }
        .desktop-nav-link {
            display: inline-flex;
            align-items: center;
            gap: 4px;
            white-space: nowrap;
            font-size: 12px;
            font-weight: 600;
            color: #0F2A47;
            padding: 8px 8px;
            border-radius: 6px;
            transition: color 0.2s ease, background-color 0.2s ease;
            text-transform: uppercase;
            letter-spacing: 0.01em;
        }
        @media (min-width: 1280px) {
            .desktop-nav-link {
                font-size: 12.5px;
                padding: 8px 10px;
            }
        }
        .desktop-nav-link:hover,
        .desktop-nav-item:hover > .desktop-nav-link {
            color: #C89B3C;
            background-color: #F8FAFC;
        }

        /* Dropdown menu chuẩn Flatsome */
        .desktop-dropdown {
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 235px;
            background: #FFFFFF;
            border: 1px solid #E2E8F0;
            border-top: 2px solid #C89B3C;
            border-radius: 0 0 10px 10px;
            box-shadow: 0 12px 28px rgba(15, 42, 71, 0.12);
            opacity: 0;
            visibility: hidden;
            transform: translateY(8px);
            transition: all 0.22s ease;
            z-index: 60;
            padding: 6px 0;
        }
        .desktop-nav-item:hover .desktop-dropdown {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }
        .desktop-dropdown a {
            display: block;
            padding: 8px 14px;
            font-size: 13px;
            font-weight: 500;
            color: #334155;
            white-space: nowrap;
            transition: all 0.18s ease;
        }
        .desktop-dropdown a:hover {
            background-color: #FAF5E8;
            color: #0F2A47;
            padding-left: 18px;
        }

        /* Slider 2 banner kích thước bằng nhau tuyệt đối, chữ nằm trọn và cách xa viền */
        .banner-viewport {
            position: relative;
            width: 100%;
            overflow: hidden;
            background-color: #0F2A47;
        }
        .banner-track {
            display: flex;
            width: 100%;
            transition: transform 0.65s cubic-bezier(0.4, 0, 0.2, 1);
            align-items: stretch;
        }
        .banner-slide {
            flex: 0 0 100%;
            width: 100%;
            min-width: 100%;
            display: flex;
            align-items: center;
            position: relative;
            overflow: hidden;
            /* Chiều cao đồng nhất cho cả 2 slide trên từng thiết bị */
            min-height: 360px;
        }
        @media (min-width: 640px) {
            .banner-slide {
                min-height: 410px;
            }
        }
        @media (min-width: 1024px) {
            .banner-slide {
                min-height: 470px;
            }
        }

        /* Hiệu ứng nút danh mục trang chủ nhỏ gọn */
        .cat-tab-btn {
            white-space: nowrap;
            font-size: 12px;
            font-weight: 600;
            padding: 7px 14px;
            border-radius: 8px;
            border: 1px solid #E2E8F0;
            background-color: #FFFFFF;
            color: #334155;
            transition: all 0.2s ease;
            cursor: pointer;
        }
        @media (min-width: 768px) {
            .cat-tab-btn {
                font-size: 12.5px;
                padding: 8px 16px;
            }
        }
        .cat-tab-btn:hover {
            border-color: #C89B3C;
            color: #0F2A47;
        }
        .cat-tab-btn.active {
            background-color: #0F2A47;
            border-color: #0F2A47;
            color: #FFFFFF;
        }

        /* Card ảnh Flatsome mượt mà, tỷ lệ đồng đều */
        .project-img-box {
            aspect-ratio: 4 / 3;
            overflow: hidden;
            background-color: #E2E8F0;
            border-radius: 10px 10px 0 0;
        }
        .project-img-box img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.45s ease;
            display: block;
        }
        .project-card:hover .project-img-box img {
            transform: scale(1.06);
        }

        /* Tiêu đề section kiểu Flatsome */
        .flatsome-heading {
            position: relative;
            display: inline-block;
            padding-bottom: 10px;
        }
        .flatsome-heading::after {
            content: "";
            position: absolute;
            left: 50%;
            bottom: 0;
            transform: translateX(-50%);
            width: 64px;
            height: 3px;
            background-color: #C89B3C;
            border-radius: 99px;
        }
        .flatsome-heading-left::after {
            left: 0;
            transform: none;
        }

        /* Hiệu ứng nhịp nhẹ cho cụm nút liên hệ nổi */
        @keyframes softPulse {
            0%, 100% { box-shadow: 0 0 0 0 rgba(200, 155, 60, 0.45); }
            50% { box-shadow: 0 0 0 9px rgba(200, 155, 60, 0); }
        }
        .pulse-hotline {
            animation: softPulse 2.2s infinite;
        }

        /* Ẩn thanh cuộn phụ nhưng vẫn vuốt được trên điện thoại */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
</head>
<body class="bg-white text-slate-800 antialiased">

    <!-- ===================================================================== -->
    <!-- UX BUILDER SECTION: TOP BAR THÔNG TIN NHANH                           -->
    <!-- ===================================================================== -->
    <div class="bg-tnNavy text-slate-200 text-xs py-2 border-b border-tnNavy-light">
        <div class="tn-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
                <span class="inline-flex items-center gap-1.5">
                    <svg class="w-3.5 h-3.5 text-tnGold shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                    <span class="truncate max-w-[260px] sm:max-w-none">83 Hói Kiểng 18, Phường Ngũ Hành Sơn, TP Đà Nẵng</span>
                </span>
                <span class="hidden md:inline text-slate-500">|</span>
                <span class="hidden md:inline-flex items-center gap-1.5">
                    <svg class="w-3.5 h-3.5 text-tnGold shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9"/></svg>
                    <span>xaydungtrungnguyen.com</span>
                </span>
            </div>
            <div class="flex items-center gap-3">
                <a href="tel:0908561719" class="inline-flex items-center gap-1.5 font-semibold text-tnGold-light hover:text-white transition">
                    <svg class="w-3.5 h-3.5" fill="currentColor" viewBox="0 0 20 20"><path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.773a11.037 11.037 0 006.105 6.105l.774-1.548a1 1 0 011.059-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z"/></svg>
                    <span>0908.561.719</span>
                </a>
            </div>
        </div>
    </div>

    <!-- ===================================================================== -->
    <!-- UX BUILDER SECTION: HEADER & MENU ĐIỀU HƯỚNG (KHÔNG ĐỂ NÚT GỌI NGAY)  -->
    <!-- ===================================================================== -->
    <header id="main-header" class="sticky top-0 z-50 bg-white/95 backdrop-blur-md border-b border-slate-200 shadow-sm">
        <div class="tn-container flex items-center justify-between gap-3 py-2.5">
            <!-- Logo công ty chuyên nghiệp, thiết kế gọn nhỏ cân đối -->
            <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group" aria-label="Xây Dựng Trung Nguyễn">
                <svg class="w-9 h-9 sm:w-10 sm:h-10 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <rect width="64" height="64" rx="12" fill="#0F2A47"/>
                    <rect x="3" y="3" width="58" height="58" rx="9.5" stroke="#C89B3C" stroke-opacity="0.45" stroke-width="1.5"/>
                    <!-- Khối kiến trúc mái & cột tạo hình chữ T-N cách điệu -->
                    <path d="M13 47V24.5L32 12L51 24.5V47H44V28.2L32 20.3L20 28.2V47H13Z" fill="#C89B3C"/>
                    <path d="M24 47V32H40V36.5H34.5V47H29.5V36.5H24V47Z" fill="#FFFFFF"/>
                    <rect x="13" y="49.5" width="38" height="2.8" rx="1.4" fill="#C89B3C"/>
                </svg>
                <div class="leading-tight">
                    <div class="text-sm sm:text-[15px] font-extrabold tracking-tight text-tnNavy group-hover:text-tnGold transition whitespace-nowrap">
                        TRUNG NGUYỄN
                    </div>
                    <div class="text-[9.5px] sm:text-[10px] font-semibold uppercase tracking-wider text-tnGold-dark whitespace-nowrap">
                        Thiết Kế &amp; Xây Dựng
                    </div>
                </div>
            </a>

            <!-- Menu điều hướng trên máy tính: chữ nhỏ gọn, viết liền từng danh mục không xuống dòng -->
            <nav class="hidden lg:block flex-1 min-w-0" aria-label="Danh mục chính">
                <ul class="desktop-nav-list">
                    <li class="desktop-nav-item">
                        <a href="#trang-chu" class="desktop-nav-link">Trang chủ</a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#gioi-thieu" class="desktop-nav-link">Giới thiệu</a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#cong-trinh-thuc-te" class="desktop-nav-link">
                            <span>Công trình thực tế</span>
                            <svg class="w-3 h-3 opacity-70" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                        </a>
                        <div class="desktop-dropdown">
                            <a href="#cong-trinh-thuc-te" onclick="filterConstruction('khach-san-can-ho')">Khách sạn – Căn hộ – Phòng trọ</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterConstruction('biet-thu')">Biệt thự</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterConstruction('nha-pho')">Nhà phố</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterConstruction('van-phong')">Văn phòng</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#linh-vuc-hoat-dong" class="desktop-nav-link">
                            <span>Lĩnh vực hoạt động</span>
                            <svg class="w-3 h-3 opacity-70" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                        </a>
                        <div class="desktop-dropdown">
                            <a href="#linh-vuc-hoat-dong">Thiết kế Kiến trúc – Nội thất</a>
                            <a href="#linh-vuc-hoat-dong">Thi công phần thô</a>
                            <a href="#linh-vuc-hoat-dong">Thi công hoàn thiện</a>
                            <a href="#linh-vuc-hoat-dong">Thi công nội thất</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#du-an-da-nang" class="desktop-nav-link">
                            <span>Dự án Đà Nẵng</span>
                            <svg class="w-3 h-3 opacity-70" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                        </a>
                        <div class="desktop-dropdown">
                            <a href="#du-an-da-nang" onclick="filterDaNang('all')">Tất cả dự án Đà Nẵng</a>
                            <a href="#du-an-da-nang" onclick="filterDaNang('nha-pho')">Mẫu thiết kế nhà phố</a>
                            <a href="#du-an-da-nang" onclick="filterDaNang('biet-thu')">Mẫu biệt thự cao cấp</a>
                            <a href="#du-an-da-nang" onclick="filterDaNang('noi-that')">Mẫu thiết kế nội thất</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#bao-gia" class="desktop-nav-link">
                            <span>Báo giá</span>
                            <svg class="w-3 h-3 opacity-70" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                        </a>
                        <div class="desktop-dropdown">
                            <a href="#bao-gia">Báo giá thiết kế kiến trúc</a>
                            <a href="#bao-gia">Báo giá thi công phần thô</a>
                            <a href="#bao-gia">Báo giá thi công hoàn thiện</a>
                            <a href="#bao-gia">Báo giá thi công trọn gói</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#tin-tuc" class="desktop-nav-link">Tin tức</a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#lien-he" class="desktop-nav-link">Liên hệ</a>
                    </li>
                </ul>
            </nav>

            <!-- Nút mở menu trên điện thoại (gọn gàng, dễ bấm) -->
            <button id="mobile-menu-btn" type="button" class="lg:hidden inline-flex items-center justify-center p-2.5 rounded-lg border border-slate-200 text-tnNavy hover:bg-slate-50 transition" aria-label="Mở danh mục">
                <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16M4 18h16"/></svg>
            </button>
        </div>

        <!-- Menu trượt xuống dành riêng cho Điện thoại & Tablet -->
        <div id="mobile-menu" class="hidden lg:hidden border-t border-slate-200 bg-white shadow-lg">
            <div class="tn-container py-3 flex flex-col gap-1 text-sm font-medium text-tnNavy">
                <a href="#trang-chu" class="mobile-nav-link py-2.5 px-3 rounded-lg hover:bg-tnGold-soft">Trang chủ</a>
                <a href="#gioi-thieu" class="mobile-nav-link py-2.5 px-3 rounded-lg hover:bg-tnGold-soft">Giới thiệu</a>
                <a href="#linh-vuc-hoat-dong" class="mobile-nav-link py-2.5 px-3 rounded-lg hover:bg-tnGold-soft">Lĩnh vực hoạt động</a>
                <a href="#cong-trinh-thuc-te" class="mobile-nav-link py-2.5 px-3 rounded-lg hover:bg-tnGold-soft">Công trình thực tế</a>
                <a href="#du-an-da-nang" class="mobile-nav-link py-2.5 px-3 rounded-lg hover:bg-tnGold-soft">Dự án tại Đà Nẵng</a>
                <a href="#bao-gia" class="mobile-nav-link py-2.5 px-3 rounded-lg hover:bg-tnGold-soft">Yêu cầu &amp; Báo giá</a>
                <a href="#doi-tac" class="mobile-nav-link py-2.5 px-3 rounded-lg hover:bg-tnGold-soft">Đối tác tiêu biểu</a>
                <a href="#tin-tuc" class="mobile-nav-link py-2.5 px-3 rounded-lg hover:bg-tnGold-soft">Tin tức xây dựng</a>
                <a href="#lien-he" class="mobile-nav-link py-2.5 px-3 rounded-lg hover:bg-tnGold-soft">Liên hệ &amp; Bản đồ</a>
            </div>
        </div>
    </header>

    <main id="trang-chu" class="w-full overflow-x-hidden">

        <!-- ===================================================================== -->
        <!-- UX BUILDER SECTION: SLIDER 2 BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU     -->
        <!-- Chữ & ảnh nằm gọn bên trong, cách xa viền ảnh trên cả Mobile & PC     -->
        <!-- ===================================================================== -->
        <section class="w-full bg-tnNavy">
            <div class="banner-viewport" id="hero-slider">
                <div class="banner-track" id="banner-track">

                    <!-- BANNER 1 -->
                    <div class="banner-slide">
                        <!-- Ảnh nền công trình thực tế (Drive) phủ lớp tối dịu giúp chữ sắc nét -->
                        <img src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w1400"
                             onerror="handleImgError(this, '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz', 'Thi+Cong+Trung+Nguyen')"
                             alt="Thiết kế và thi công xây dựng trọn gói Trung Nguyễn"
                             class="absolute inset-0 w-full h-full object-cover object-center opacity-35">
                        <div class="absolute inset-0 bg-gradient-to-r from-tnNavy-dark/95 via-tnNavy/85 to-tnNavy/65"></div>

                        <!-- Khung nội dung cách xa viền 4 phía (padding lớn) đảm bảo không mất chữ -->
                        <div class="relative z-10 w-full px-10 py-10 sm:px-16 sm:py-12 lg:px-24 lg:py-14">
                            <div class="tn-container grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
                                <div class="lg:col-span-7 text-left space-y-3 sm:space-y-4">
                                    <p class="text-[11px] sm:text-xs font-bold uppercase tracking-[0.18em] text-tnGold-light">
                                        CÔNG TY TNHH TƯ VẤN THIẾT KẾ VÀ XÂY DỰNG TRUNG NGUYỄN
                                    </p>
                                    <h1 class="text-xl sm:text-3xl lg:text-4xl font-extrabold text-white leading-snug">
                                        Kiến Tạo Không Gian Sống Bền Vững &amp; Chuẩn Mực Tại Đà Nẵng
                                    </h1>
                                    <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed max-w-2xl">
                                        Chuyên tư vấn thiết kế kiến trúc, thi công phần thô, hoàn thiện và xây nhà trọn gói. Cam kết đúng tiến độ, chuẩn kỹ thuật kết cấu và minh bạch chi phí từng hạng mục.
                                    </p>
                                    <div class="pt-2 flex flex-wrap items-center gap-3">
                                        <a href="#bao-gia" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-tnGold hover:bg-tnGold-dark text-tnNavy-dark font-bold text-xs sm:text-sm transition shadow-md">
                                            Nhận Báo Giá Miễn Phí
                                        </a>
                                        <a href="#cong-trinh-thuc-te" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg border border-white/40 hover:bg-white/10 text-white font-semibold text-xs sm:text-sm transition">
                                            Xem Công Trình Thực Tế
                                        </a>
                                    </div>
                                </div>
                                <div class="hidden lg:block lg:col-span-5">
                                    <div class="rounded-xl overflow-hidden border-2 border-tnGold/40 shadow-2xl aspect-[16/10] bg-tnNavy-light">
                                        <img src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w1000"
                                             onerror="handleImgError(this, '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR', 'Cong+Trinh+Thuc+Te')"
                                             alt="Thi công công trình thực tế tại Đà Nẵng"
                                             class="w-full h-full object-cover">
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- BANNER 2 -->
                    <div class="banner-slide">
                        <img src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w1400"
                             onerror="handleImgError(this, '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT', 'Du+An+Da+Nang')"
                             alt="Dự án nhà phố biệt thự căn hộ tại Đà Nẵng"
                             class="absolute inset-0 w-full h-full object-cover object-center opacity-35">
                        <div class="absolute inset-0 bg-gradient-to-r from-tnNavy-dark/95 via-tnNavy/85 to-tnNavy/65"></div>

                        <!-- Khung nội dung giống hệt Banner 1 để 2 banner bằng nhau tuyệt đối -->
                        <div class="relative z-10 w-full px-10 py-10 sm:px-16 sm:py-12 lg:px-24 lg:py-14">
                            <div class="tn-container grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
                                <div class="lg:col-span-7 text-left space-y-3 sm:space-y-4">
                                    <p class="text-[11px] sm:text-xs font-bold uppercase tracking-[0.18em] text-tnGold-light">
                                        XAYDUNGTRUNGNGUYEN.COM — ĐỒNG HÀNH CÙNG CHỦ ĐẦU TƯ
                                    </p>
                                    <h2 class="text-xl sm:text-3xl lg:text-4xl font-extrabold text-white leading-snug">
                                        Thi Công Nhà Phố, Biệt Thự, Căn Hộ &amp; Khách Sạn Chuyên Nghiệp
                                    </h2>
                                    <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed max-w-2xl">
                                        Đội ngũ kỹ sư giám sát trực tiếp tại công trình, vật tư chính hãng rõ nguồn gốc và chính sách bảo hành kết cấu dài hạn giúp gia chủ an tâm trọn vẹn.
                                    </p>
                                    <div class="pt-2 flex flex-wrap items-center gap-3">
                                        <a href="#du-an-da-nang" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-tnGold hover:bg-tnGold-dark text-tnNavy-dark font-bold text-xs sm:text-sm transition shadow-md">
                                            Khám Phá Dự Án Đà Nẵng
                                        </a>
                                        <a href="#lien-he" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg border border-white/40 hover:bg-white/10 text-white font-semibold text-xs sm:text-sm transition">
                                            Liên Hệ Tư Vấn: 0908.561.719
                                        </a>
                                    </div>
                                </div>
                                <div class="hidden lg:block lg:col-span-5">
                                    <div class="rounded-xl overflow-hidden border-2 border-tnGold/40 shadow-2xl aspect-[16/10] bg-tnNavy-light">
                                        <img src="https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff=w1000"
                                             onerror="handleImgError(this, '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff', 'Thiet+Ke+Da+Nang')"
                                             alt="Dự án tiêu biểu tại Đà Nẵng - Trung Nguyễn"
                                             class="w-full h-full object-cover">
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                </div>

                <!-- Nút điều khiển trái / phải đặt sát mép gọn gàng, không che chữ -->
                <button type="button" id="banner-prev" class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-white/15 hover:bg-tnGold text-white hover:text-tnNavy-dark flex items-center justify-center transition backdrop-blur-sm" aria-label="Banner trước">
                    <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M15 19l-7-7 7-7"/></svg>
                </button>
                <button type="button" id="banner-next" class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-white/15 hover:bg-tnGold text-white hover:text-tnNavy-dark flex items-center justify-center transition backdrop-blur-sm" aria-label="Banner tiếp theo">
                    <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7"/></svg>
                </button>

                <!-- Chấm chỉ báo vị trí banner -->
                <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button type="button" class="banner-dot w-7 h-2 rounded-full bg-tnGold transition-all" data-index="0" aria-label="Xem banner 1"></button>
                    <button type="button" class="banner-dot w-2.5 h-2 rounded-full bg-white/45 hover:bg-white transition-all" data-index="1" aria-label="Xem banner 2"></button>
                </div>
            </div>
        </section>

        <!-- ===================================================================== -->
        <!-- UX BUILDER SECTION: DỊCH VỤ TIÊU BIỂU / LĨNH VỰC HOẠT ĐỘNG           -->
        <!-- Đồng bộ danh mục theo mẫu tintruongthinh.com                          -->
        <!-- ===================================================================== -->
        <section id="linh-vuc-hoat-dong" class="py-10 sm:py-14 bg-slate-50">
            <div class="tn-container">
                <div class="text-center mb-8">
                    <h2 class="flatsome-heading text-xl sm:text-2xl lg:text-[26px] font-extrabold text-tnNavy uppercase tracking-tight">
                        Dịch Vụ Tiêu Biểu
                    </h2>
                    <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
                        Giải pháp toàn diện từ khâu tư vấn thiết kế kiến trúc đến thi công xây dựng và hoàn thiện nội thất.
                    </p>
                </div>

                <!-- 2 cột trên điện thoại, 4 cột trên máy tính -->
                <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                    <div class="bg-white rounded-xl p-4 sm:p-6 border border-slate-200 hover:border-tnGold hover:shadow-md transition text-center flex flex-col items-center">
                        <div class="w-12 h-12 rounded-xl bg-tnNavy text-tnGold flex items-center justify-center mb-3.5">
                            <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"/></svg>
                        </div>
                        <h3 class="text-xs sm:text-sm lg:text-[15px] font-bold text-tnNavy uppercase leading-snug mb-1.5">
                            Thiết Kế Kiến Trúc – Nội Thất
                        </h3>
                        <p class="text-[11.5px] sm:text-xs text-slate-600 leading-relaxed">
                            Thiết kế mặt bằng công năng khoa học, phối cảnh 3D chuẩn thẩm mỹ, tối ưu phong thủy và ngân sách.
                        </p>
                    </div>

                    <div class="bg-white rounded-xl p-4 sm:p-6 border border-slate-200 hover:border-tnGold hover:shadow-md transition text-center flex flex-col items-center">
                        <div class="w-12 h-12 rounded-xl bg-tnNavy text-tnGold flex items-center justify-center mb-3.5">
                            <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4"/></svg>
                        </div>
                        <h3 class="text-xs sm:text-sm lg:text-[15px] font-bold text-tnNavy uppercase leading-snug mb-1.5">
                            Thi Công Phần Thô
                        </h3>
                        <p class="text-[11.5px] sm:text-xs text-slate-600 leading-relaxed">
                            Thi công móng, khung bê tông cốt thép, tường bao và hệ thống điện nước âm tường chuẩn quy chuẩn kỹ thuật.
                        </p>
                    </div>

                    <div class="bg-white rounded-xl p-4 sm:p-6 border border-slate-200 hover:border-tnGold hover:shadow-md transition text-center flex flex-col items-center">
                        <div class="w-12 h-12 rounded-xl bg-tnNavy text-tnGold flex items-center justify-center mb-3.5">
                            <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"/></svg>
                        </div>
                        <h3 class="text-xs sm:text-sm lg:text-[15px] font-bold text-tnNavy uppercase leading-snug mb-1.5">
                            Thi Công Hoàn Thiện &amp; Trọn Gói
                        </h3>
                        <p class="text-[11.5px] sm:text-xs text-slate-600 leading-relaxed">
                            Xây nhà chìa khóa trao tay, kiểm soát vật liệu hoàn thiện sắc nét, không phát sinh chi phí ngoài hợp đồng.
                        </p>
                    </div>

                    <div class="bg-white rounded-xl p-4 sm:p-6 border border-slate-200 hover:border-tnGold hover:shadow-md transition text-center flex flex-col items-center">
                        <div class="w-12 h-12 rounded-xl bg-tnNavy text-tnGold flex items-center justify-center mb-3.5">
                            <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M4 5a1 1 0 011-1h14a1 1 0 011 1v2a1 1 0 01-1 1H5a1 1 0 01-1-1V5zM4 13a1 1 0 011-1h6a1 1 0 011 1v6a1 1 0 01-1 1H5a1 1 0 01-1-1v-6zM16 13a1 1 0 011-1h2a1 1 0 011 1v6a1 1 0 01-1 1h-2a1 1 0 01-1-1v-6z"/></svg>
                        </div>
                        <h3 class="text-xs sm:text-sm lg:text-[15px] font-bold text-tnNavy uppercase leading-snug mb-1.5">
                            Thi Công Nội Thất
                        </h3>
                        <p class="text-[11.5px] sm:text-xs text-slate-600 leading-relaxed">
                            Sản xuất và lắp đặt nội thất gỗ công nghiệp, gỗ tự nhiên tinh tế cho nhà phố, biệt thự, căn hộ và văn phòng.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- ===================================================================== -->
        <!-- UX BUILDER SECTION: GIỚI THIỆU CÔNG TY & THẾ MẠNH CỐT LÕI             -->
        <!-- ===================================================================== -->
        <section id="gioi-thieu" class="py-10 sm:py-14 bg-white">
            <div class="tn-container">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                    <div class="lg:col-span-6 space-y-4">
                        <h2 class="flatsome-heading flatsome-heading-left text-xl sm:text-2xl font-extrabold text-tnNavy uppercase leading-snug">
                            CÔNG TY TNHH TƯ VẤN THIẾT KẾ VÀ XÂY DỰNG TRUNG NGUYỄN
                        </h2>
                        <p class="text-sm text-slate-600 leading-relaxed">
                            <strong class="text-tnNavy">Xây Dựng Trung Nguyễn</strong> là đơn vị chuyên Tư vấn Thiết kế – Thi công Xây dựng – Hoàn thiện Nội thất cho các công trình Nhà phố, Biệt thự, Khách sạn, Căn hộ cho thuê và Văn phòng tại khu vực Đà Nẵng và Miền Trung.
                        </p>
                        <p class="text-sm text-slate-600 leading-relaxed">
                            Đặt chữ <strong class="text-tnNavy">“TÂM”</strong> và chữ <strong class="text-tnNavy">“TÍN”</strong> lên hàng đầu, mỗi công trình bàn giao đều được kiểm soát nghiêm ngặt theo 4 tiêu chuẩn cốt lõi: <strong class="text-tnGold-dark">An Toàn – Chất Lượng – Tiến Độ – Hài Lòng</strong>. Chúng tôi đồng hành từ bản vẽ ý tưởng, thủ tục xin phép xây dựng đến khi trao chìa khóa tổ ấm hoàn thiện.
                        </p>
                        <div class="grid grid-cols-3 gap-3 pt-2">
                            <div class="bg-slate-50 border border-slate-200 rounded-xl p-3.5 text-center">
                                <div class="text-xl sm:text-2xl font-extrabold text-tnNavy">100%</div>
                                <div class="text-[11px] sm:text-xs font-medium text-slate-600 mt-0.5">Trực tiếp thi công</div>
                            </div>
                            <div class="bg-slate-50 border border-slate-200 rounded-xl p-3.5 text-center">
                                <div class="text-xl sm:text-2xl font-extrabold text-tnGold-dark">5 Năm</div>
                                <div class="text-[11px] sm:text-xs font-medium text-slate-600 mt-0.5">Bảo hành kết cấu</div>
                            </div>
                            <div class="bg-slate-50 border border-slate-200 rounded-xl p-3.5 text-center">
                                <div class="text-xl sm:text-2xl font-extrabold text-tnNavy">24/7</div>
                                <div class="text-[11px] sm:text-xs font-medium text-slate-600 mt-0.5">Hỗ trợ chủ đầu tư</div>
                            </div>
                        </div>
                    </div>

                    <div class="lg:col-span-6">
                        <div class="grid grid-cols-2 gap-3 sm:gap-4">
                            <div class="rounded-xl overflow-hidden shadow-md aspect-[4/3] bg-slate-100">
                                <img src="https://lh3.googleusercontent.com/d/1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv=w800"
                                     onerror="handleImgError(this, '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv', 'Thi+Cong+Trung+Nguyen')"
                                     alt="Thi công công trình Xây Dựng Trung Nguyễn"
                                     class="w-full h-full object-cover">
                            </div>
                            <div class="rounded-xl overflow-hidden shadow-md aspect-[4/3] bg-slate-100">
                                <img src="https://lh3.googleusercontent.com/d/1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_=w800"
                                     onerror="handleImgError(this, '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_', 'Giam+Sat+Cong+Trinh')"
                                     alt="Giám sát thi công thực tế tại công trường"
                                     class="w-full h-full object-cover">
                            </div>
                            <div class="col-span-2 rounded-xl overflow-hidden shadow-md aspect-[16/8] bg-slate-100">
                                <img src="https://lh3.googleusercontent.com/d/1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO=w1000"
                                     onerror="handleImgError(this, '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO', 'Hoan+Thien+Cong+Trinh')"
                                     alt="Công trình hoàn thiện chuẩn kỹ thuật Trung Nguyễn"
                                     class="w-full h-full object-cover">
                            </div>
                        </div>
                    </div>
                </div>

                <!-- 6 Thế mạnh của Xây Dựng Trung Nguyễn -->
                <div class="mt-12 pt-10 border-t border-slate-200">
                    <div class="text-center mb-7">
                        <h3 class="flatsome-heading text-lg sm:text-xl font-extrabold text-tnNavy uppercase">
                            Thế Mạnh Của Chúng Tôi
                        </h3>
                    </div>
                    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
                        <div class="p-5 rounded-xl bg-slate-50 border border-slate-200">
                            <h4 class="font-bold text-sm text-tnNavy mb-1.5 flex items-center gap-2">
                                <span class="w-6 h-6 rounded-full bg-tnGold text-tnNavy-dark text-xs font-extrabold flex items-center justify-center shrink-0">1</span>
                                Đội ngũ kiến trúc sư, kỹ sư giàu kinh nghiệm
                            </h4>
                            <p class="text-xs text-slate-600 leading-relaxed">Kiến trúc sư sáng tạo kết hợp đội ngũ kỹ sư hiện trường và thợ tay nghề cao đảm bảo từng chi tiết sắc sảo.</p>
                        </div>
                        <div class="p-5 rounded-xl bg-slate-50 border border-slate-200">
                            <h4 class="font-bold text-sm text-tnNavy mb-1.5 flex items-center gap-2">
                                <span class="w-6 h-6 rounded-full bg-tnGold text-tnNavy-dark text-xs font-extrabold flex items-center justify-center shrink-0">2</span>
                                Cập nhật xu hướng kiến trúc hiện đại
                            </h4>
                            <p class="text-xs text-slate-600 leading-relaxed">Ứng dụng giải pháp không gian mở, thông gió tự nhiên và vật liệu xây dựng bền bỉ phù hợp khí hậu miền Trung.</p>
                        </div>
                        <div class="p-5 rounded-xl bg-slate-50 border border-slate-200">
                            <h4 class="font-bold text-sm text-tnNavy mb-1.5 flex items-center gap-2">
                                <span class="w-6 h-6 rounded-full bg-tnGold text-tnNavy-dark text-xs font-extrabold flex items-center justify-center shrink-0">3</span>
                                Giám sát tiến độ chuẩn xác từng ngày
                            </h4>
                            <p class="text-xs text-slate-600 leading-relaxed">Báo cáo hình ảnh thi công thường xuyên giúp chủ đầu tư dễ dàng theo dõi tiến độ dù ở bất cứ đâu.</p>
                        </div>
                        <div class="p-5 rounded-xl bg-slate-50 border border-slate-200">
                            <h4 class="font-bold text-sm text-tnNavy mb-1.5 flex items-center gap-2">
                                <span class="w-6 h-6 rounded-full bg-tnGold text-tnNavy-dark text-xs font-extrabold flex items-center justify-center shrink-0">4</span>
                                Bảo hành công trình nhanh chóng, dài lâu
                            </h4>
                            <p class="text-xs text-slate-600 leading-relaxed">Chế độ hậu mãi rõ ràng, hỗ trợ kiểm tra bảo dưỡng kịp thời để khách hàng an tâm sử dụng dài lâu.</p>
                        </div>
                        <div class="p-5 rounded-xl bg-slate-50 border border-slate-200">
                            <h4 class="font-bold text-sm text-tnNavy mb-1.5 flex items-center gap-2">
                                <span class="w-6 h-6 rounded-full bg-tnGold text-tnNavy-dark text-xs font-extrabold flex items-center justify-center shrink-0">5</span>
                                Báo giá minh bạch, chi phí hợp lý
                            </h4>
                            <p class="text-xs text-slate-600 leading-relaxed">Dự toán chi tiết từng hạng mục vật tư, tối ưu chi phí đầu tư mà vẫn giữ trọn chất lượng kết cấu công trình.</p>
                        </div>
                        <div class="p-5 rounded-xl bg-slate-50 border border-slate-200">
                            <h4 class="font-bold text-sm text-tnNavy mb-1.5 flex items-center gap-2">
                                <span class="w-6 h-6 rounded-full bg-tnGold text-tnNavy-dark text-xs font-extrabold flex items-center justify-center shrink-0">6</span>
                                Tư vấn khảo sát miễn phí 24/7
                            </h4>
                            <p class="text-xs text-slate-600 leading-relaxed">Luôn sẵn sàng khảo sát thực địa, tư vấn phương án thiết kế và lên khái toán sơ bộ miễn phí cho khách hàng.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- ===================================================================== -->
        <!-- UX BUILDER SECTION: CÔNG TRÌNH THỰC TẾ & SẢN PHẨM THI CÔNG (9 ẢNH)    -->
        <!-- Chia 2 cột trên điện thoại, tên đầy đủ không tràn, không nhãn dán     -->
        <!-- ===================================================================== -->
        <section id="cong-trinh-thuc-te" class="py-10 sm:py-14 bg-slate-50 border-t border-slate-200">
            <div class="tn-container">
                <div class="text-center mb-6">
                    <h2 class="flatsome-heading text-xl sm:text-2xl lg:text-[26px] font-extrabold text-tnNavy uppercase">
                        Công Trình Thực Tế &amp; Hạng Mục Thi Công
                    </h2>
                    <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
                        Hình ảnh thi công thực tế tại công trường do đội ngũ kỹ sư Công ty Xây Dựng Trung Nguyễn trực tiếp triển khai.
                    </p>
                </div>

                <!-- Danh mục lọc sản phẩm / công trình chuẩn mẫu tintruongthinh.com, chữ nhỏ gọn -->
                <div class="flex flex-wrap items-center justify-center gap-2 mb-7" id="construction-tabs">
                    <button type="button" class="cat-tab-btn active" onclick="filterConstruction('all', this)">Tất cả</button>
                    <button type="button" class="cat-tab-btn" onclick="filterConstruction('nha-pho', this)">Nhà phố</button>
                    <button type="button" class="cat-tab-btn" onclick="filterConstruction('biet-thu', this)">Biệt thự</button>
                    <button type="button" class="cat-tab-btn" onclick="filterConstruction('khach-san-can-ho', this)">Khách sạn – Căn hộ – Phòng trọ</button>
                    <button type="button" class="cat-tab-btn" onclick="filterConstruction('van-phong', this)">Văn phòng</button>
                </div>

                <!-- Lưới sản phẩm: 2 cột trên điện thoại, 3-4 cột trên máy tính -->
                <div id="construction-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
                    <!-- Nội dung được render từ dữ liệu 9 ảnh thực tế Google Drive bên dưới -->
                </div>
            </div>
        </section>

        <!-- ===================================================================== -->
        <!-- UX BUILDER SECTION: CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (10 ẢNH DRIVE)    -->
        <!-- Chia 2 cột trên điện thoại, hiển thị trọn vẹn tên dự án               -->
        <!-- ===================================================================== -->
        <section id="du-an-da-nang" class="py-10 sm:py-14 bg-white border-t border-slate-200">
            <div class="tn-container">
                <div class="text-center mb-6">
                    <h2 class="flatsome-heading text-xl sm:text-2xl lg:text-[26px] font-extrabold text-tnNavy uppercase">
                        Các Dự Án Tiêu Biểu Tại Đà Nẵng
                    </h2>
                    <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
                        Tuyển tập các công trình thiết kế kiến trúc, thi công xây dựng và hoàn thiện nội thất nổi bật tại các quận Ngũ Hành Sơn, Hòa Xuân, Hải Châu, Sơn Trà – TP Đà Nẵng.
                    </p>
                </div>

                <!-- Thanh danh mục dự án Đà Nẵng gọn đẹp trên cả PC & Mobile -->
                <div class="flex flex-wrap items-center justify-center gap-2 mb-7" id="danang-tabs">
                    <button type="button" class="cat-tab-btn active" onclick="filterDaNang('all', this)">Tất cả dự án</button>
                    <button type="button" class="cat-tab-btn" onclick="filterDaNang('nha-pho', this)">Nhà phố Đà Nẵng</button>
                    <button type="button" class="cat-tab-btn" onclick="filterDaNang('biet-thu', this)">Biệt thự hiện đại</button>
                    <button type="button" class="cat-tab-btn" onclick="filterDaNang('can-ho', this)">Căn hộ – Khách sạn</button>
                    <button type="button" class="cat-tab-btn" onclick="filterDaNang('noi-that', this)">Thiết kế nội thất</button>
                </div>

                <!-- Lưới 10 dự án Đà Nẵng: 2 cột trên điện thoại, 5 cột trên màn hình lớn -->
                <div id="danang-grid" class="grid grid-cols-2 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
                    <!-- Nội dung được render từ dữ liệu 10 ảnh dự án Đà Nẵng bên dưới -->
                </div>
            </div>
        </section>

        <!-- ===================================================================== -->
        <!-- UX BUILDER SECTION: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ           -->
        <!-- Thiết kế đồng bộ mẫu tintruongthinh.com                               -->
        <!-- ===================================================================== -->
        <section id="bao-gia" class="py-10 sm:py-14 bg-tnNavy text-white">
            <div class="tn-container">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-start">
                    <!-- Cột thông tin bảng giá tham khảo -->
                    <div class="lg:col-span-5 space-y-5">
                        <div>
                            <h2 class="flatsome-heading flatsome-heading-left text-xl sm:text-2xl font-extrabold text-white uppercase">
                                Yêu Cầu Tư Vấn &amp; Báo Giá
                            </h2>
                            <p class="mt-3 text-xs sm:text-sm text-slate-300 leading-relaxed">
                                Quý khách vui lòng điền thông tin công trình dự kiến. Đội ngũ kỹ sư Xây Dựng Trung Nguyễn sẽ liên hệ tư vấn phương án tối ưu và gửi bảng dự toán chi tiết trong vòng 30 phút.
                            </p>
                        </div>

                        <div class="space-y-2.5 text-xs sm:text-sm">
                            <div class="flex items-center justify-between p-3.5 rounded-xl bg-white/10 border border-white/15">
                                <span class="font-semibold text-white">Thiết kế kiến trúc – nội thất</span>
                                <span class="font-bold text-tnGold-light whitespace-nowrap">Theo m² sàn</span>
                            </div>
                            <div class="flex items-center justify-between p-3.5 rounded-xl bg-white/10 border border-white/15">
                                <span class="font-semibold text-white">Thi công phần thô &amp; nhân công</span>
                                <span class="font-bold text-tnGold-light whitespace-nowrap">Báo giá chi tiết</span>
                            </div>
                            <div class="flex items-center justify-between p-3.5 rounded-xl bg-white/10 border border-white/15">
                                <span class="font-semibold text-white">Thi công hoàn thiện trọn gói</span>
                                <span class="font-bold text-tnGold-light whitespace-nowrap">Chìa khóa trao tay</span>
                            </div>
                            <div class="flex items-center justify-between p-3.5 rounded-xl bg-white/10 border border-white/15">
                                <span class="font-semibold text-white">Cải tạo, sửa chữa nhà ở &amp; văn phòng</span>
                                <span class="font-bold text-tnGold-light whitespace-nowrap">Khảo sát miễn phí</span>
                            </div>
                        </div>

                        <div class="pt-1 flex flex-wrap items-center gap-4 text-xs sm:text-sm text-slate-200">
                            <a href="tel:0908561719" class="inline-flex items-center gap-2 font-bold text-tnGold-light hover:text-white transition">
                                <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 20 20"><path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.773a11.037 11.037 0 006.105 6.105l.774-1.548a1 1 0 011.059-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z"/></svg>
                                Hotline / Zalo: 0908.561.719
                            </a>
                        </div>
                    </div>

                    <!-- Cột biểu mẫu đăng ký báo giá -->
                    <div class="lg:col-span-7">
                        <form id="quote-form" class="bg-white text-slate-800 rounded-2xl p-5 sm:p-7 shadow-xl space-y-4">
                            <h3 class="text-base sm:text-lg font-extrabold text-tnNavy uppercase">
                                Miễn Phí Tư Vấn &amp; Lập Khái Toán
                            </h3>
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label for="q-name" class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên *</label>
                                    <input id="q-name" type="text" required placeholder="Nhập họ tên của bạn"
                                           class="w-full rounded-lg border border-slate-300 px-3.5 py-2.5 text-sm focus:border-tnGold focus:ring-2 focus:ring-tnGold/25 outline-none">
                                </div>
                                <div>
                                    <label for="q-phone" class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                    <input id="q-phone" type="tel" required placeholder="Ví dụ: 0908 561 719"
                                           class="w-full rounded-lg border border-slate-300 px-3.5 py-2.5 text-sm focus:border-tnGold focus:ring-2 focus:ring-tnGold/25 outline-none">
                                </div>
                                <div>
                                    <label for="q-type" class="block text-xs font-semibold text-slate-700 mb-1">Loại công trình</label>
                                    <select id="q-type" class="w-full rounded-lg border border-slate-300 px-3.5 py-2.5 text-sm bg-white focus:border-tnGold focus:ring-2 focus:ring-tnGold/25 outline-none">
                                        <option value="Nhà phố">Nhà phố</option>
                                        <option value="Biệt thự">Biệt thự</option>
                                        <option value="Khách sạn – Căn hộ cho thuê – Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                                        <option value="Văn phòng">Văn phòng</option>
                                        <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                                    </select>
                                </div>
                                <div>
                                    <label for="q-budget" class="block text-xs font-semibold text-slate-700 mb-1">Mức đầu tư dự kiến</label>
                                    <select id="q-budget" class="w-full rounded-lg border border-slate-300 px-3.5 py-2.5 text-sm bg-white focus:border-tnGold focus:ring-2 focus:ring-tnGold/25 outline-none">
                                        <option value="Chưa xác định">Chưa xác định</option>
                                        <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                                        <option value="500 triệu - 1 tỷ">500 triệu – 1 tỷ</option>
                                        <option value="1 tỷ - 2 tỷ">1 tỷ – 2 tỷ</option>
                                        <option value="2 tỷ - 3 tỷ">2 tỷ – 3 tỷ</option>
                                        <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                    </select>
                                </div>
                                <div>
                                    <label for="q-service" class="block text-xs font-semibold text-slate-700 mb-1">Hạng mục yêu cầu</label>
                                    <select id="q-service" class="w-full rounded-lg border border-slate-300 px-3.5 py-2.5 text-sm bg-white focus:border-tnGold focus:ring-2 focus:ring-tnGold/25 outline-none">
                                        <option value="Thi công trọn gói">Báo giá thi công trọn gói</option>
                                        <option value="Thi công phần thô">Báo giá thi công phần thô</option>
                                        <option value="Thi công hoàn thiện">Báo giá thi công hoàn thiện</option>
                                        <option value="Thiết kế kiến trúc – nội thất">Báo giá thiết kế kiến trúc – nội thất</option>
                                    </select>
                                </div>
                                <div>
                                    <label for="q-email" class="block text-xs font-semibold text-slate-700 mb-1">Email (không bắt buộc)</label>
                                    <input id="q-email" type="email" placeholder="email@example.com"
                                           class="w-full rounded-lg border border-slate-300 px-3.5 py-2.5 text-sm focus:border-tnGold focus:ring-2 focus:ring-tnGold/25 outline-none">
                                </div>
                            </div>
                            <div>
                                <label for="q-note" class="block text-xs font-semibold text-slate-700 mb-1">Thông tin khu đất &amp; yêu cầu chi tiết</label>
                                <textarea id="q-note" rows="3" placeholder="Ví dụ: Diện tích 5x20m tại Ngũ Hành Sơn, dự kiến xây 3 tầng..."
                                          class="w-full rounded-lg border border-slate-300 px-3.5 py-2.5 text-sm focus:border-tnGold focus:ring-2 focus:ring-tnGold/25 outline-none"></textarea>
                            </div>
                            <button type="submit" class="w-full py-3 px-6 rounded-xl bg-tnGold hover:bg-tnGold-dark text-tnNavy-dark font-extrabold text-sm uppercase tracking-wide transition shadow-md">
                                Gửi Yêu Cầu Báo Giá Ngay
                            </button>
                            <!-- Thông báo phản hồi trực tiếp (không dùng alert) -->
                            <div id="quote-feedback" class="hidden rounded-xl p-3.5 text-xs sm:text-sm font-medium bg-emerald-50 text-emerald-800 border border-emerald-200"></div>
                        </form>
                    </div>
                </div>
            </div>
        </section>

        <!-- ===================================================================== -->
        <!-- UX BUILDER SECTION: DANH MỤC CÁC BÀI VIẾT / TIN TỨC XÂY DỰNG          -->
        <!-- ===================================================================== -->
        <section id="tin-tuc" class="py-10 sm:py-14 bg-slate-50 border-t border-slate-200">
            <div class="tn-container">
                <div class="text-center mb-8">
                    <h2 class="flatsome-heading text-xl sm:text-2xl lg:text-[26px] font-extrabold text-tnNavy uppercase">
                        Tin Tức &amp; Kinh Nghiệm Xây Dựng
                    </h2>
                    <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
                        Chia sẻ kiến thức kỹ thuật thi công, xu hướng thiết kế nhà đẹp và kinh nghiệm tối ưu chi phí xây nhà tại Đà Nẵng.
                    </p>
                </div>

                <!-- 2 cột trên điện thoại, 4 cột trên máy tính -->
                <div id="articles-grid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                    <!-- Render danh mục bài viết từ JavaScript -->
                </div>
            </div>
        </section>

        <!-- ===================================================================== -->
        <!-- UX BUILDER SECTION: DANH MỤC CÁC ĐỐI TÁC & NHÀ CUNG CẤP VẬT TƯ        -->
        <!-- ===================================================================== -->
        <section id="doi-tac" class="py-10 sm:py-12 bg-white border-t border-slate-200">
            <div class="tn-container">
                <div class="text-center mb-7">
                    <h2 class="flatsome-heading text-xl sm:text-2xl font-extrabold text-tnNavy uppercase">
                        Đối Tác &amp; Nhà Cung Cấp Vật Tư
                    </h2>
                    <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
                        Hợp tác cùng các thương hiệu vật liệu xây dựng chính hãng, đảm bảo độ bền kết cấu và tính thẩm mỹ lâu dài.
                    </p>
                </div>

                <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-3">
                    <div class="rounded-xl border border-slate-200 bg-slate-50 hover:border-tnGold hover:bg-white transition p-3.5 flex flex-col items-center justify-center text-center min-h-[78px]">
                        <span class="text-xs sm:text-sm font-extrabold text-tnNavy tracking-tight">HÒA PHÁT</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Thép xây dựng</span>
                    </div>
                    <div class="rounded-xl border border-slate-200 bg-slate-50 hover:border-tnGold hover:bg-white transition p-3.5 flex flex-col items-center justify-center text-center min-h-[78px]">
                        <span class="text-xs sm:text-sm font-extrabold text-tnNavy tracking-tight">VIỆT NHẬT</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Thép kết cấu</span>
                    </div>
                    <div class="rounded-xl border border-slate-200 bg-slate-50 hover:border-tnGold hover:bg-white transition p-3.5 flex flex-col items-center justify-center text-center min-h-[78px]">
                        <span class="text-xs sm:text-sm font-extrabold text-tnNavy tracking-tight">SÔNG GIANH</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Xi măng PCB40</span>
                    </div>
                    <div class="rounded-xl border border-slate-200 bg-slate-50 hover:border-tnGold hover:bg-white transition p-3.5 flex flex-col items-center justify-center text-center min-h-[78px]">
                        <span class="text-xs sm:text-sm font-extrabold text-tnNavy tracking-tight">DULUX</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Sơn nội ngoại thất</span>
                    </div>
                    <div class="rounded-xl border border-slate-200 bg-slate-50 hover:border-tnGold hover:bg-white transition p-3.5 flex flex-col items-center justify-center text-center min-h-[78px]">
                        <span class="text-xs sm:text-sm font-extrabold text-tnNavy tracking-tight">JOTUN</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Sơn chống thấm</span>
                    </div>
                    <div class="rounded-xl border border-slate-200 bg-slate-50 hover:border-tnGold hover:bg-white transition p-3.5 flex flex-col items-center justify-center text-center min-h-[78px]">
                        <span class="text-xs sm:text-sm font-extrabold text-tnNavy tracking-tight">BÌNH MINH</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Ống nhựa cấp thoát</span>
                    </div>
                    <div class="rounded-xl border border-slate-200 bg-slate-50 hover:border-tnGold hover:bg-white transition p-3.5 flex flex-col items-center justify-center text-center min-h-[78px]">
                        <span class="text-xs sm:text-sm font-extrabold text-tnNavy tracking-tight">CADIVI</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Dây cáp điện</span>
                    </div>
                    <div class="rounded-xl border border-slate-200 bg-slate-50 hover:border-tnGold hover:bg-white transition p-3.5 flex flex-col items-center justify-center text-center min-h-[78px]">
                        <span class="text-xs sm:text-sm font-extrabold text-tnNavy tracking-tight">INAX</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Thiết bị vệ sinh</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- ===================================================================== -->
        <!-- UX BUILDER SECTION: BẢN ĐỒ GOOGLE MAP & FANPAGE FACEBOOK TRANG CHỦ    -->
        <!-- ===================================================================== -->
        <section id="lien-he" class="py-10 sm:py-14 bg-slate-50 border-t border-slate-200">
            <div class="tn-container">
                <div class="text-center mb-8">
                    <h2 class="flatsome-heading text-xl sm:text-2xl lg:text-[26px] font-extrabold text-tnNavy uppercase">
                        Bản Đồ Chỉ Đường &amp; Fanpage Chính Thức
                    </h2>
                    <p class="mt-3 text-xs sm:text-sm text-slate-600">
                        Văn phòng giao dịch: 83 Hói Kiểng 18, Phường Ngũ Hành Sơn, TP Đà Nẵng — Hotline: 0908.561.719
                    </p>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                    <!-- Cột Google Maps trực tiếp ngoài trang chủ -->
                    <div class="lg:col-span-7 bg-white rounded-2xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
                        <div class="px-5 py-3.5 border-b border-slate-200 flex flex-wrap items-center justify-between gap-2">
                            <div class="flex items-center gap-2">
                                <svg class="w-5 h-5 text-tnGold-dark shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                                <span class="text-sm font-bold text-tnNavy">Google Map: 83 Hói Kiểng 18, Phường Ngũ Hành Sơn, TP Đà Nẵng</span>
                            </div>
                            <a href="https://www.google.com/maps/search/?api=1&query=83+H%C3%B3i+Ki%E1%BB%83ng+18,+Ng%C5%A9+H%C3%A0nh+S%C6%A1n,+%C4%90%C3%A0+N%E1%BA%B5ng"
                               target="_blank" rel="noopener noreferrer"
                               class="text-xs font-semibold text-tnGold-dark hover:underline whitespace-nowrap">
                                Mở trên Google Maps &rarr;
                            </a>
                        </div>
                        <div class="w-full flex-1 min-h-[340px] sm:min-h-[380px] bg-slate-100">
                            <iframe
                                title="Bản đồ Công ty TNHH Tư Vấn Thiết Kế và Xây Dựng Trung Nguyễn"
                                src="https://maps.google.com/maps?q=83%20H%C3%B3i%20Ki%E1%BB%83ng%2018,%20Ng%C5%A9%20H%C3%A0nh%20S%C6%A1n,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                                class="w-full h-full min-h-[340px] sm:min-h-[380px] border-0"
                                loading="lazy"
                                referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                        </div>
                    </div>

                    <!-- Cột Fanpage Facebook hiển thị trực tiếp ngoài trang chủ -->
                    <div class="lg:col-span-5 bg-white rounded-2xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
                        <div class="px-5 py-3.5 border-b border-slate-200 flex items-center justify-between gap-2">
                            <div class="flex items-center gap-2">
                                <svg class="w-5 h-5 text-[#1877F2] shrink-0" fill="currentColor" viewBox="0 0 24 24"><path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"/></svg>
                                <span class="text-sm font-bold text-tnNavy">Fanpage Xây Dựng Trung Nguyễn</span>
                            </div>
                            <a href="https://www.facebook.com/profile.php?id=100093851405007"
                               target="_blank" rel="noopener noreferrer"
                               class="text-xs font-semibold text-[#1877F2] hover:underline whitespace-nowrap">
                                Truy cập Trang &rarr;
                            </a>
                        </div>

                        <!-- Khung nhúng Facebook Page + Thẻ giới thiệu dự phòng luôn đẹp -->
                        <div class="p-4 flex-1 flex flex-col justify-between gap-4">
                            <div class="w-full rounded-xl overflow-hidden border border-slate-200 bg-slate-50">
                                <iframe
                                    title="Fanpage Facebook Xây Dựng Trung Nguyễn"
                                    src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D100093851405007&tabs=timeline&width=500&height=260&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true"
                                    class="w-full h-[260px] border-0 overflow-hidden"
                                    scrolling="no"
                                    frameborder="0"
                                    allowfullscreen="true"
                                    allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                                </iframe>
                            </div>

                            <!-- Thẻ truy cập nhanh Fanpage luôn hiển thị rõ ràng -->
                            <div class="rounded-xl bg-tnNavy text-white p-4 flex flex-col sm:flex-row items-start sm:items-center justify-between gap-3">
                                <div class="space-y-0.5">
                                    <div class="text-xs sm:text-sm font-bold text-white">CÔNG TY TNHH TƯ VẤN THIẾT KẾ &amp; XÂY DỰNG TRUNG NGUYỄN</div>
                                    <div class="text-[11px] text-slate-300">Theo dõi tiến độ thi công &amp; mẫu nhà mới cập nhật mỗi tuần trên Facebook.</div>
                                </div>
                                <a href="https://www.facebook.com/profile.php?id=100093851405007"
                                   target="_blank" rel="noopener noreferrer"
                                   class="shrink-0 inline-flex items-center gap-1.5 px-4 py-2 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold transition">
                                    <span>Xem Fanpage</span>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- ===================================================================== -->
    <!-- UX BUILDER SECTION: FOOTER CHUẨN FLATSOME                             -->
    <!-- ===================================================================== -->
    <footer class="bg-tnNavy-dark text-slate-300 pt-12 pb-6 border-t-4 border-tnGold">
        <div class="tn-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8 pb-8 border-b border-white/10">
                <!-- Cột 1: Thông tin doanh nghiệp -->
                <div class="lg:col-span-5 space-y-3">
                    <div class="flex items-center gap-2.5">
                        <svg class="w-9 h-9 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <rect width="64" height="64" rx="12" fill="#1B3F66"/>
                            <path d="M13 47V24.5L32 12L51 24.5V47H44V28.2L32 20.3L20 28.2V47H13Z" fill="#C89B3C"/>
                            <path d="M24 47V32H40V36.5H34.5V47H29.5V36.5H24V47Z" fill="#FFFFFF"/>
                            <rect x="13" y="49.5" width="38" height="2.8" rx="1.4" fill="#C89B3C"/>
                        </svg>
                        <div>
                            <div class="text-sm font-extrabold text-white uppercase">CÔNG TY TNHH TƯ VẤN THIẾT KẾ VÀ XÂY DỰNG TRUNG NGUYỄN</div>
                            <div class="text-[11px] text-tnGold-light font-semibold">xaydungtrungnguyen.com</div>
                        </div>
                    </div>
                    <ul class="space-y-2 text-xs sm:text-sm text-slate-300 pt-1">
                        <li><strong class="text-white">Trụ sở:</strong> 83 Hói Kiểng 18, Phường Ngũ Hành Sơn, TP Đà Nẵng</li>
                        <li><strong class="text-white">Mã số thuế:</strong> 0402259757</li>
                        <li><strong class="text-white">Hotline / Zalo:</strong> <a href="tel:0908561719" class="text-tnGold-light font-bold hover:underline">0908.561.719</a></li>
                        <li><strong class="text-white">Website:</strong> <a href="https://xaydungtrungnguyen.com" class="hover:text-tnGold-light">xaydungtrungnguyen.com</a></li>
                        <li><strong class="text-white">Fanpage:</strong> <a href="https://www.facebook.com/profile.php?id=100093851405007" target="_blank" rel="noopener noreferrer" class="hover:text-tnGold-light underline">Facebook Xây Dựng Trung Nguyễn</a></li>
                    </ul>
                </div>

                <!-- Cột 2: Lĩnh vực hoạt động -->
                <div class="lg:col-span-3 space-y-3">
                    <h4 class="text-sm font-bold text-white uppercase tracking-wide border-l-2 border-tnGold pl-2.5">
                        Lĩnh Vực Hoạt Động
                    </h4>
                    <ul class="space-y-2 text-xs sm:text-sm">
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-tnGold-light transition">Thiết kế kiến trúc – nội thất</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-tnGold-light transition">Thi công phần thô chuẩn kỹ thuật</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-tnGold-light transition">Thi công hoàn thiện chìa khóa trao tay</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-tnGold-light transition">Thi công nội thất nhà phố, biệt thự</a></li>
                        <li><a href="#bao-gia" class="hover:text-tnGold-light transition">Cải tạo, sửa chữa công trình</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục công trình & Báo giá -->
                <div class="lg:col-span-4 space-y-3">
                    <h4 class="text-sm font-bold text-white uppercase tracking-wide border-l-2 border-tnGold pl-2.5">
                        Danh Mục Công Trình &amp; Báo Giá
                    </h4>
                    <div class="grid grid-cols-2 gap-2 text-xs sm:text-sm">
                        <a href="#cong-trinh-thuc-te" class="hover:text-tnGold-light transition">Nhà phố hiện đại</a>
                        <a href="#cong-trinh-thuc-te" class="hover:text-tnGold-light transition">Biệt thự cao cấp</a>
                        <a href="#cong-trinh-thuc-te" class="hover:text-tnGold-light transition">Khách sạn – Căn hộ</a>
                        <a href="#cong-trinh-thuc-te" class="hover:text-tnGold-light transition">Thi công văn phòng</a>
                        <a href="#du-an-da-nang" class="hover:text-tnGold-light transition">Dự án Đà Nẵng</a>
                        <a href="#bao-gia" class="hover:text-tnGold-light transition">Báo giá trọn gói</a>
                        <a href="#tin-tuc" class="hover:text-tnGold-light transition">Kinh nghiệm xây nhà</a>
                        <a href="#lien-he" class="hover:text-tnGold-light transition">Bản đồ &amp; Liên hệ</a>
                    </div>
                </div>
            </div>

            <div class="pt-5 text-center text-xs text-slate-400">
                Copyright &copy; 2026 <strong class="text-slate-200">CÔNG TY TNHH TƯ VẤN THIẾT KẾ VÀ XÂY DỰNG TRUNG NGUYỄN</strong> (xaydungtrungnguyen.com). All rights reserved.
            </div>
        </div>
    </footer>

    <!-- ===================================================================== -->
    <!-- CỤM NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE (PC & MOBILE)        -->
    <!-- ===================================================================== -->
    <div class="fixed right-3 bottom-4 sm:right-5 sm:bottom-6 z-40 flex flex-col items-end gap-2.5">
        <!-- Nút Facebook -->
        <a href="https://www.facebook.com/profile.php?id=100093851405007"
           target="_blank" rel="noopener noreferrer"
           class="group flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white rounded-full p-2.5 sm:px-3.5 sm:py-2.5 shadow-lg transition"
           aria-label="Liên hệ Facebook Xây Dựng Trung Nguyễn">
            <svg class="w-5 h-5 shrink-0" fill="currentColor" viewBox="0 0 24 24"><path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"/></svg>
            <span class="hidden sm:inline text-xs font-bold pr-1">Facebook</span>
        </a>

        <!-- Nút Zalo -->
        <a href="https://zalo.me/0908561719"
           target="_blank" rel="noopener noreferrer"
           class="group flex items-center gap-2 bg-[#0068FF] hover:bg-blue-600 text-white rounded-full p-2.5 sm:px-3.5 sm:py-2.5 shadow-lg transition"
           aria-label="Nhắn tin Zalo 0908.561.719">
            <span class="w-5 h-5 rounded-full bg-white text-[#0068FF] font-extrabold text-[10px] flex items-center justify-center shrink-0">Zalo</span>
            <span class="hidden sm:inline text-xs font-bold pr-1">Chat Zalo</span>
        </a>

        <!-- Nút Hotline -->
        <a href="tel:0908561719"
           class="pulse-hotline group flex items-center gap-2 bg-tnGold hover:bg-tnGold-dark text-tnNavy-dark rounded-full p-2.5 sm:px-4 sm:py-2.5 shadow-xl transition"
           aria-label="Gọi Hotline 0908.561.719">
            <svg class="w-5 h-5 shrink-0" fill="currentColor" viewBox="0 0 20 20"><path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.773a11.037 11.037 0 006.105 6.105l.774-1.548a1 1 0 011.059-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z"/></svg>
            <span class="hidden sm:inline text-xs font-extrabold tracking-tight">0908.561.719</span>
        </a>
    </div>

    <!-- ===================================================================== -->
    <!-- MODAL XEM CHI TIẾT ẢNH CÔNG TRÌNH / DỰ ÁN / BÀI VIẾT                  -->
    <!-- ===================================================================== -->
    <div id="detail-modal" class="fixed inset-0 z-50 hidden bg-slate-900/75 backdrop-blur-sm flex items-center justify-center p-3 sm:p-6">
        <div class="bg-white rounded-2xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200">
            <div class="sticky top-0 bg-white px-5 py-3.5 border-b border-slate-200 flex items-center justify-between gap-3 z-10">
                <h3 id="modal-title" class="text-sm sm:text-base font-extrabold text-tnNavy"></h3>
                <button type="button" onclick="closeDetailModal()" class="w-8 h-8 rounded-full bg-slate-100 hover:bg-slate-200 text-slate-700 flex items-center justify-center font-bold" aria-label="Đóng">
                    &times;
                </button>
            </div>
            <div class="p-5 space-y-4">
                <div class="rounded-xl overflow-hidden bg-slate-100 aspect-[16/10]">
                    <img id="modal-img" src="" alt="" class="w-full h-full object-cover">
                </div>
                <div id="modal-meta" class="text-xs font-semibold text-tnGold-dark uppercase"></div>
                <p id="modal-desc" class="text-sm text-slate-600 leading-relaxed"></p>
                <div class="pt-2 flex flex-wrap gap-3">
                    <a href="#bao-gia" onclick="closeDetailModal()" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-tnNavy hover:bg-tnNavy-light text-white text-xs sm:text-sm font-bold transition">
                        Nhận Báo Giá Công Trình Tương Tự
                    </a>
                    <a href="tel:0908561719" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-tnGold hover:bg-tnGold-dark text-tnNavy-dark text-xs sm:text-sm font-bold transition">
                        Gọi Kỹ Sư: 0908.561.719
                    </a>
                </div>
            </div>
        </div>
    </div>

    <!-- ===================================================================== -->
    <!-- JAVASCRIPT: DỮ LIỆU ẢNH GOOGLE DRIVE, SLIDER, BỘ LỌC & FORM BÁO GIÁ   -->
    <!-- ===================================================================== -->
    <script>
        /* Hàm lấy URL ảnh Google Drive tối ưu và tự động dự phòng nếu lỗi mạng */
        function getDriveImageUrl(fileId) {
            return `https://lh3.googleusercontent.com/d/${fileId}=w1000`;
        }

        function handleImgError(imgEl, fileId, fallbackText) {
            if (!imgEl.dataset.fallbackStep) {
                imgEl.dataset.fallbackStep = '1';
                imgEl.src = `https://drive.google.com/thumbnail?id=${fileId}&sz=w1000`;
            } else if (imgEl.dataset.fallbackStep === '1') {
                imgEl.dataset.fallbackStep = '2';
                imgEl.src = `https://placehold.co/800x600/0F2A47/C89B3C?text=${fallbackText}`;
            }
        }

        /* -------------------------------------------------------------------
         * DỮ LIỆU 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG (NHÓM 1 - GOOGLE DRIVE)
         * Phân loại chuẩn danh mục mẫu tintruongthinh.com
         * ------------------------------------------------------------------- */
        const constructionProjects = [
            {
                id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                title: 'Thi Công Phần Thô & Kết Cấu Móng Nhà Phố 3 Tầng',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố • Thi công phần thô',
                location: 'Quận Ngũ Hành Sơn, Đà Nẵng',
                desc: 'Thi công ép cọc, gia công lắp dựng cốt thép móng băng và đổ bê tông tươi đúng mác thiết kế, nghiệm thu chuẩn quy trình kỹ thuật bởi kỹ sư Xây Dựng Trung Nguyễn.'
            },
            {
                id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                title: 'Thi Công Khung Bê Tông Cốt Thép Nhà Phố Hiện Đại',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố • Thi công phần thô',
                location: 'Khu đô thị Hòa Quý, Đà Nẵng',
                desc: 'Công tác lắp dựng cốp pha dầm sàn, kiểm tra độ võng và cao độ chuẩn xác trước khi đổ bê tông, đảm bảo độ bền vững tuyệt đối cho công trình.'
            },
            {
                id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                title: 'Thi Công Xây Tường Bao & Ngăn Phòng Chuẩn Kỹ Thuật',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố • Thi công xây trát',
                location: 'Khu đô thị Nam Hòa Xuân, Đà Nẵng',
                desc: 'Xây tường gạch đúng mạch vữa, đóng lưới chống nứt vị trí tiếp giáp cột bê tông và đi hệ thống ống điện nước âm tường khoa học.'
            },
            {
                id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                title: 'Thi Công Hoàn Thiện Mặt Tiền Biệt Thự Phố Sang Trọng',
                category: 'biet-thu',
                categoryLabel: 'Biệt thự • Thi công hoàn thiện',
                location: 'Quận Sơn Trà, Đà Nẵng',
                desc: 'Hoàn thiện trát phẳng ngoại thất, chống thấm hai lớp chuyên dụng và ốp đá tự nhiên tạo điểm nhấn kiến trúc bền đẹp theo thời gian.'
            },
            {
                id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
                title: 'Thi Công Căn Hộ Cho Thuê & Khách Sạn Mini 5 Tầng',
                category: 'khach-san-can-ho',
                categoryLabel: 'Khách sạn – Căn hộ – Phòng trọ',
                location: 'Khu vực An Thượng, Ngũ Hành Sơn',
                desc: 'Thi công trọn gói tòa nhà căn hộ dịch vụ tích hợp thang máy, hệ thống PCCC và bố trí phòng ốc thông thoáng tối ưu hiệu suất khai thác.'
            },
            {
                id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
                title: 'Thi Công Cải Tạo & Hoàn Thiện Không Gian Văn Phòng',
                category: 'van-phong',
                categoryLabel: 'Văn phòng • Hoàn thiện trọn gói',
                location: 'Quận Hải Châu, Đà Nẵng',
                desc: 'Triển khai thi công trần thạch cao, hệ thống chiếu sáng tiêu chuẩn, vách kính cường lực và sàn hoàn thiện cho văn phòng làm việc hiện đại.'
            },
            {
                id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                title: 'Thi Công Trọn Gói Biệt Thự 2 Mặt Tiền Mái Nhật',
                category: 'biet-thu',
                categoryLabel: 'Biệt thự • Xây nhà trọn gói',
                location: 'Quận Cẩm Lệ, Đà Nẵng',
                desc: 'Thiết kế và thi công chìa khóa trao tay công trình biệt thự sân vườn rộng rãi, hệ mái chống nóng tốt và hoàn thiện nội ngoại thất đồng bộ.'
            },
            {
                id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
                title: 'Thi Công Hoàn Thiện Căn Hộ Dịch Vụ Cao Cấp',
                category: 'khach-san-can-ho',
                categoryLabel: 'Khách sạn – Căn hộ – Phòng trọ',
                location: 'Phường Mỹ An, Đà Nẵng',
                desc: 'Hoàn thiện ốp lát gạch khổ lớn, lắp đặt thiết bị vệ sinh chính hãng và hệ tủ bếp gọn đẹp, bàn giao sạch sẽ đúng tiến độ cam kết.'
            },
            {
                id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
                title: 'Thi Công Nội Thất & Bàn Giao Nhà Phố Chìa Khóa Trao Tay',
                category: 'van-phong',
                categoryLabel: 'Nhà phố & Văn phòng • Nội thất',
                location: 'TP Đà Nẵng',
                desc: 'Lắp đặt hoàn chỉnh hệ thống cửa nhôm kính, cầu thang gỗ kính và nội thất phòng khách – bếp – làm việc theo đúng bản vẽ 3D đã duyệt.'
            }
        ];

        /* -------------------------------------------------------------------
         * DỮ LIỆU 10 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (NHÓM 2 - GOOGLE DRIVE)
         * ------------------------------------------------------------------- */
        const danangProjects = [
            {
                id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                title: 'Nhà Phố Hiện Đại 3 Tầng – Hòa Quý, Ngũ Hành Sơn',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố Đà Nẵng',
                desc: 'Công trình nhà phố diện tích 5x20m với mặt tiền tối giản, kết hợp mảng xanh ban công và giếng trời lấy sáng tự nhiên cho toàn bộ các tầng.'
            },
            {
                id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
                title: 'Biệt Thự Phố 2 Mặt Tiền – Nam Hòa Xuân, Đà Nẵng',
                category: 'biet-thu',
                categoryLabel: 'Biệt thự hiện đại',
                desc: 'Thiết kế kiến trúc đương đại tận dụng lợi thế hai mặt thoáng, không gian phòng khách thông tầng sang trọng và gara ô tô tiện nghi.'
            },
            {
                id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
                title: 'Tòa Căn Hộ Dịch Vụ Cao Cấp – Khu An Thượng, Đà Nẵng',
                category: 'can-ho',
                categoryLabel: 'Căn hộ – Khách sạn',
                desc: 'Dự án căn hộ cho thuê 6 tầng thiết kế tối ưu diện tích phòng khép kín, hành lang rộng thoáng và vật liệu hoàn thiện bền bỉ gần biển.'
            },
            {
                id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
                title: 'Nhà Phố Kết Hợp Kinh Doanh – Khu Nam Việt Á',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố Đà Nẵng',
                desc: 'Giải pháp không gian tầng trệt thông suốt phục vụ kinh doanh kết hợp khu sinh hoạt gia đình ấm cúng, riêng tư ở các tầng trên.'
            },
            {
                id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
                title: 'Thiết Kế & Thi Công Nội Thất Nhà Phố – Quận Hải Châu',
                category: 'noi-that',
                categoryLabel: 'Thiết kế nội thất',
                desc: 'Phong cách nội thất hiện đại sử dụng tông gỗ ấm kết hợp ánh sáng dịu nhẹ, tối ưu công năng tủ âm tường và khu bếp mở liền kề phòng khách.'
            },
            {
                id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
                title: 'Khách Sạn Boutique Mini – Quận Sơn Trà, Đà Nẵng',
                category: 'can-ho',
                categoryLabel: 'Căn hộ – Khách sạn',
                desc: 'Công trình lưu trú gần biển Mỹ Khê được Xây Dựng Trung Nguyễn tư vấn thiết kế và thi công trọn gói với kiến trúc ấn tượng, chuẩn thẩm mỹ.'
            },
            {
                id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
                title: 'Biệt Thự Sân Vườn Nghỉ Dưỡng – Ngũ Hành Sơn',
                category: 'biet-thu',
                categoryLabel: 'Biệt thự hiện đại',
                desc: 'Không gian biệt thự hài hòa cùng thiên nhiên, hệ cửa kính lớn mở tầm nhìn ra sân vườn xanh mát, đảm bảo thông gió tự nhiên quanh năm.'
            },
            {
                id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
                title: 'Nhà Phố 4 Tầng Mặt Tiền Đẹp – Khu Phước Lý, Đà Nẵng',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố Đà Nẵng',
                desc: 'Thiết kế hình khối mạnh mẽ với hệ lam chắn nắng hướng Tây, giúp giảm nhiệt hiệu quả và tạo nét kiến trúc nổi bật cho khu phố.'
            },
            {
                id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
                title: 'Hoàn Thiện Nội Thất Căn Hộ – Trung Tâm TP Đà Nẵng',
                category: 'noi-that',
                categoryLabel: 'Thiết kế nội thất',
                desc: 'Thi công hoàn thiện nội thất đồng bộ từ phòng khách, phòng ngủ master đến phòng bếp với chất liệu chống ẩm cao cấp.'
            },
            {
                id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
                title: 'Nhà Ở Gia Đình Trọn Gói – Phường Hòa Hải, Đà Nẵng',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố Đà Nẵng',
                desc: 'Công trình nhà ở gia đình 2 tầng 1 tum thi công chìa khóa trao tay, bàn giao đúng tiến độ với chi phí hợp lý và chất lượng kết cấu vững chắc.'
            }
        ];

        /* -------------------------------------------------------------------
         * DỮ LIỆU DANH MỤC BÀI VIẾT TRANG CHỦ
         * ------------------------------------------------------------------- */
        const articlesList = [
            {
                title: 'Hướng dẫn bảo dưỡng bê tông móng và sàn đúng tiêu chuẩn kỹ thuật',
                date: 'Kinh nghiệm thi công',
                imageId: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                excerpt: 'Bảo dưỡng bê tông đúng thời điểm giúp hạn chế nứt chân chim, tăng cường độ chịu lực và tuổi thọ lâu dài cho toàn bộ kết cấu ngôi nhà.',
                content: 'Sau khi đổ bê tông móng, cột và sàn từ 4 đến 6 giờ, cần tiến hành che phủ giữ ẩm và tưới nước bảo dưỡng liên tục tối thiểu 7 ngày đầu. Việc duy trì độ ẩm ổn định giúp quá trình thủy hóa xi măng diễn ra trọn vẹn, tránh hiện tượng co ngót nứt bề mặt đặc biệt trong thời tiết nắng gió tại Đà Nẵng.'
            },
            {
                title: '03 lưu ý quan trọng chủ đầu tư cần biết trước khi xây nhà trọn gói',
                date: 'Tư vấn xây nhà',
                imageId: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                excerpt: 'Chuẩn bị hồ sơ thiết kế đầy đủ, kiểm tra bảng chủng loại vật tư chi tiết và lựa chọn nhà thầu thi công trực tiếp giúp hạn chế phát sinh.',
                content: 'Để quá trình xây nhà diễn ra suôn sẻ, gia chủ nên chốt rõ nhu cầu công năng ngay từ giai đoạn thiết kế 2D/3D, thống nhất bảng vật liệu phần thô và hoàn thiện có ghi rõ thương hiệu trong hợp đồng, đồng thời lên kế hoạch tài chính dự phòng hợp lý trước khi khởi công.'
            },
            {
                title: 'Cách tính diện tích xây dựng và dự trù chi phí nhà phố tại Đà Nẵng',
                date: 'Báo giá & Dự toán',
                imageId: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
                excerpt: 'Nắm rõ hệ số tính diện tích móng, tầng trệt, các tầng lầu và mái giúp chủ đầu tư chủ động lập ngân sách xây dựng chính xác.',
                content: 'Diện tích xây dựng thường được tính gồm phần móng (30% - 50% diện tích sàn tùy loại móng băng hay móng cọc), 100% diện tích các tầng có mái che, 50% - 70% sân thượng có giàn lam và 30% - 50% phần mái. Liên hệ Xây Dựng Trung Nguyễn 0908.561.719 để nhận bảng dự toán bóc tách miễn phí.'
            },
            {
                title: 'Giải pháp chống thấm và thông gió hiệu quả cho nhà phố miền Trung',
                date: 'Kỹ thuật kiến trúc',
                imageId: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
                excerpt: 'Khí hậu nắng nóng mùa hè và mưa bão cuối năm đòi hỏi thiết kế giếng trời hợp lý cùng quy trình chống thấm tường, sân thượng bài bản.',
                content: 'Các vị trí trọng yếu như sân thượng, ban công, nhà vệ sinh và tường tiếp giáp nhà hàng xóm cần được xử lý chống thấm tối thiểu 2 lớp bằng vật liệu đàn hồi cao, kết hợp bố trí giếng trời thông gió đối lưu giúp ngôi nhà luôn mát mẻ và khô ráo.'
            }
        ];

        /* -------------------------------------------------------------------
         * RENDER LƯỚI CÔNG TRÌNH THỰC TẾ (KHÔNG NHÃN DÁN, 2 CỘT TRÊN MOBILE)
         * ------------------------------------------------------------------- */
        function renderConstruction(category = 'all') {
            const grid = document.getElementById('construction-grid');
            const filtered = category === 'all'
                ? constructionProjects
                : constructionProjects.filter(item => item.category === category);

            grid.innerHTML = filtered.map((item) => `
                <article onclick="openDetailModal('${item.title.replace(/'/g, "\\'")}', '${item.categoryLabel} — ${item.location}', '${item.desc.replace(/'/g, "\\'")}', '${item.id}')"
                         class="project-card bg-white rounded-xl border border-slate-200 hover:border-tnGold hover:shadow-md transition cursor-pointer flex flex-col overflow-hidden">
                    <div class="project-img-box">
                        <img src="${getDriveImageUrl(item.id)}"
                             onerror="handleImgError(this, '${item.id}', 'Cong+Trinh+Trung+Nguyen')"
                             alt="${item.title}"
                             loading="lazy">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between gap-1.5">
                        <h3 class="text-[12.5px] sm:text-sm font-bold text-tnNavy leading-snug break-words">
                            ${item.title}
                        </h3>
                        <p class="text-[11px] sm:text-xs text-slate-500 leading-snug">
                            ${item.location}
                        </p>
                    </div>
                </article>
            `).join('');
        }

        function filterConstruction(category, btnEl) {
            renderConstruction(category);
            const tabs = document.querySelectorAll('#construction-tabs .cat-tab-btn');
            tabs.forEach(btn => btn.classList.remove('active'));
            if (btnEl) {
                btnEl.classList.add('active');
            } else {
                const mapIndex = { 'all': 0, 'nha-pho': 1, 'biet-thu': 2, 'khach-san-can-ho': 3, 'van-phong': 4 };
                if (tabs[mapIndex[category]]) tabs[mapIndex[category]].classList.add('active');
            }
        }

        /* -------------------------------------------------------------------
         * RENDER LƯỚI 10 DỰ ÁN TẠI ĐÀ NẴNG (KHÔNG NHÃN DÁN, 2 CỘT TRÊN MOBILE)
         * ------------------------------------------------------------------- */
        function renderDaNang(category = 'all') {
            const grid = document.getElementById('danang-grid');
            const filtered = category === 'all'
                ? danangProjects
                : danangProjects.filter(item => item.category === category);

            grid.innerHTML = filtered.map((item) => `
                <article onclick="openDetailModal('${item.title.replace(/'/g, "\\'")}', '${item.categoryLabel} • TP Đà Nẵng', '${item.desc.replace(/'/g, "\\'")}', '${item.id}')"
                         class="project-card bg-white rounded-xl border border-slate-200 hover:border-tnGold hover:shadow-md transition cursor-pointer flex flex-col overflow-hidden">
                    <div class="project-img-box">
                        <img src="${getDriveImageUrl(item.id)}"
                             onerror="handleImgError(this, '${item.id}', 'Du+An+Da+Nang')"
                             alt="${item.title}"
                             loading="lazy">
                    </div>
                    <div class="p-3 sm:p-3.5 flex-1 flex flex-col justify-between gap-1">
                        <h3 class="text-[12.5px] sm:text-[13.5px] font-bold text-tnNavy leading-snug break-words">
                            ${item.title}
                        </h3>
                        <p class="text-[11px] text-tnGold-dark font-medium">
                            ${item.categoryLabel}
                        </p>
                    </div>
                </article>
            `).join('');
        }

        function filterDaNang(category, btnEl) {
            renderDaNang(category);
            const tabs = document.querySelectorAll('#danang-tabs .cat-tab-btn');
            tabs.forEach(btn => btn.classList.remove('active'));
            if (btnEl) {
                btnEl.classList.add('active');
            } else {
                const mapIndex = { 'all': 0, 'nha-pho': 1, 'biet-thu': 2, 'can-ho': 3, 'noi-that': 4 };
                if (tabs[mapIndex[category]]) tabs[mapIndex[category]].classList.add('active');
            }
        }

        /* -------------------------------------------------------------------
         * RENDER DANH MỤC BÀI VIẾT TRANG CHỦ
         * ------------------------------------------------------------------- */
        function renderArticles() {
            const grid = document.getElementById('articles-grid');
            grid.innerHTML = articlesList.map((art) => `
                <article onclick="openDetailModal('${art.title.replace(/'/g, "\\'")}', '${art.date}', '${art.content.replace(/'/g, "\\'")}', '${art.imageId}')"
                         class="project-card bg-white rounded-xl border border-slate-200 hover:border-tnGold hover:shadow-md transition cursor-pointer flex flex-col overflow-hidden">
                    <div class="project-img-box">
                        <img src="${getDriveImageUrl(art.imageId)}"
                             onerror="handleImgError(this, '${art.imageId}', 'Tin+Tuc+Xay+Dung')"
                             alt="${art.title}"
                             loading="lazy">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between gap-2">
                        <div>
                            <div class="text-[10.5px] sm:text-[11px] font-semibold text-tnGold-dark uppercase mb-1">${art.date}</div>
                            <h3 class="text-[12.5px] sm:text-sm font-bold text-tnNavy leading-snug break-words mb-1.5">
                                ${art.title}
                            </h3>
                            <p class="text-[11.5px] sm:text-xs text-slate-600 leading-relaxed hidden sm:block">
                                ${art.excerpt}
                            </p>
                        </div>
                        <span class="text-[11.5px] sm:text-xs font-bold text-tnNavy hover:text-tnGold-dark">Xem chi tiết &rarr;</span>
                    </div>
                </article>
            `).join('');
        }

        /* -------------------------------------------------------------------
         * MODAL XEM CHI TIẾT CÔNG TRÌNH / BÀI VIẾT
         * ------------------------------------------------------------------- */
        function openDetailModal(title, meta, desc, imageId) {
            const modal = document.getElementById('detail-modal');
            const img = document.getElementById('modal-img');
            document.getElementById('modal-title').textContent = title;
            document.getElementById('modal-meta').textContent = meta;
            document.getElementById('modal-desc').textContent = desc;
            delete img.dataset.fallbackStep;
            img.src = getDriveImageUrl(imageId);
            img.alt = title;
            img.onerror = function() { handleImgError(img, imageId, 'Xay+Dung+Trung+Nguyen'); };
            modal.classList.remove('hidden');
            document.body.style.overflow = 'hidden';
        }

        function closeDetailModal() {
            const modal = document.getElementById('detail-modal');
            modal.classList.add('hidden');
            document.body.style.overflow = '';
        }

        /* Đóng modal khi bấm nền tối bên ngoài hoặc phím ESC */
        document.getElementById('detail-modal').addEventListener('click', function(e) {
            if (e.target === this) closeDetailModal();
        });
        document.addEventListener('keydown', function(e) {
            if (e.key === 'Escape') closeDetailModal();
        });

        /* -------------------------------------------------------------------
         * SLIDER 2 BANNER TỰ TRƯỢT + HỖ TRỢ VUỐT CẢM ỨNG TRÊN ĐIỆN THOẠI
         * ------------------------------------------------------------------- */
        let currentBanner = 0;
        const totalBanners = 2;
        const bannerTrack = document.getElementById('banner-track');
        const bannerDots = document.querySelectorAll('.banner-dot');
        let bannerTimer = null;

        function updateBannerSlide(index) {
            currentBanner = (index + totalBanners) % totalBanners;
            bannerTrack.style.transform = `translateX(-${currentBanner * 100}%)`;
            bannerDots.forEach((dot, idx) => {
                if (idx === currentBanner) {
                    dot.classList.add('w-7', 'bg-tnGold');
                    dot.classList.remove('w-2.5', 'bg-white/45');
                } else {
                    dot.classList.remove('w-7', 'bg-tnGold');
                    dot.classList.add('w-2.5', 'bg-white/45');
                }
            });
        }

        function startBannerAutoSlide() {
            stopBannerAutoSlide();
            bannerTimer = setInterval(() => {
                updateBannerSlide(currentBanner + 1);
            }, 5200);
        }

        function stopBannerAutoSlide() {
            if (bannerTimer) clearInterval(bannerTimer);
        }

        document.getElementById('banner-prev').addEventListener('click', () => {
            updateBannerSlide(currentBanner - 1);
            startBannerAutoSlide();
        });
        document.getElementById('banner-next').addEventListener('click', () => {
            updateBannerSlide(currentBanner + 1);
            startBannerAutoSlide();
        });
        bannerDots.forEach(dot => {
            dot.addEventListener('click', () => {
                updateBannerSlide(parseInt(dot.dataset.index, 10));
                startBannerAutoSlide();
            });
        });

        /* Hỗ trợ vuốt trái / phải banner trên điện thoại */
        let touchStartX = 0;
        const heroSlider = document.getElementById('hero-slider');
        heroSlider.addEventListener('touchstart', (e) => {
            touchStartX = e.changedTouches[0].screenX;
        }, { passive: true });
        heroSlider.addEventListener('touchend', (e) => {
            const touchEndX = e.changedTouches[0].screenX;
            if (touchStartX - touchEndX > 45) {
                updateBannerSlide(currentBanner + 1);
                startBannerAutoSlide();
            } else if (touchEndX - touchStartX > 45) {
                updateBannerSlide(currentBanner - 1);
                startBannerAutoSlide();
            }
        }, { passive: true });

        /* -------------------------------------------------------------------
         * MENU ĐIỆN THOẠI & XỬ LÝ FORM YÊU CẦU BÁO GIÁ
         * ------------------------------------------------------------------- */
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');
        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
        document.querySelectorAll('.mobile-nav-link').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });

        document.getElementById('quote-form').addEventListener('submit', function(e) {
            e.preventDefault();
            try {
                const name = document.getElementById('q-name').value.trim();
                const phone = document.getElementById('q-phone').value.trim();
                const type = document.getElementById('q-type').value;
                const service = document.getElementById('q-service').value;
                const feedback = document.getElementById('quote-feedback');

                feedback.textContent = `Cảm ơn anh/chị ${name}! Yêu cầu "${service} - ${type}" đã được ghi nhận. Kỹ sư Xây Dựng Trung Nguyễn sẽ liên hệ số ${phone} trong thời gian sớm nhất (Hotline hỗ trợ nhanh: 0908.561.719).`;
                feedback.classList.remove('hidden');
                this.reset();
            } catch (err) {
                console.error('Lỗi gửi biểu mẫu:', err);
            }
        });

        /* Khởi tạo dữ liệu trang chủ */
        window.addEventListener('DOMContentLoaded', () => {
            renderConstruction('all');
            renderDaNang('all');
            renderArticles();
            updateBannerSlide(0);
            startBannerAutoSlide();
        });
    </script>
</body>
</html>
