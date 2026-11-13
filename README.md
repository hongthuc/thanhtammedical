<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Thanh Tâm Medical - Dịch Vụ Y Tế Tại Nhà & Thiết Bị Y Tế Đà Nẵng</title>
    <meta name="description" content="Thanh Tâm Medical (thanhtammedical.com) - Dịch vụ y tế tại nhà Đà Nẵng, cho thuê bình oxy, máy tạo oxy, máy thở, giường bệnh nhân, xe cấp cứu 24/7. Địa chỉ: 64 Trần Cao Vân, Phường Thanh Khê, Tp.Đà Nẵng. Hotline: 0932.552.313">
    
    <!-- Open Graph Thumbnail là ảnh Logo trang web khi gửi link chia sẻ -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://thanhtammedical.com/">
    <meta property="og:title" content="Thanh Tâm Medical - Dịch Vụ Y Tế Tại Nhà & Thiết Bị Y Tế Đà Nẵng">
    <meta property="og:description" content="Cung cấp dịch vụ điều dưỡng tại nhà, bác sĩ gia đình, thuê bình oxy, máy thở, xe cấp cứu chuyển viện 24/7 và thiết bị y tế chính hãng tại 64 Trần Cao Vân, Đà Nẵng.">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1WHFD2AqrulRIbWAiX3zw90FEpWxVS6Y9=w800">
    <meta property="og:image:alt" content="Logo Thanh Tâm Medical">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1WHFD2AqrulRIbWAiX3zw90FEpWxVS6Y9=w800">
    <link rel="icon" href="https://lh3.googleusercontent.com/d/1WHFD2AqrulRIbWAiX3zw90FEpWxVS6Y9=w200" type="image/png">

    <!-- Tailwind CSS & Font Awesome & Google Fonts -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        medical: {
                            50: '#f0f9ff',
                            100: '#e0f2fe',
                            200: '#bae6fd',
                            500: '#0284c7',
                            600: '#0072bc', /* Màu xanh chủ đạo theo logo y tế */
                            700: '#035388',
                            800: '#07426b',
                            teal: '#0d9488',
                            accent: '#e11d48'
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Reset chống tràn viền và chống lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
            scroll-behavior: smooth;
        }

        /* Khung Container chuẩn Flatsome: 95% chiều ngang trên máy tính, 100% gọn gàng trên điện thoại */
        .container-flatsome {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 1024px) {
            .container-flatsome {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Tối ưu tên danh mục trên máy tính: viết liền trên 1 hàng, chữ nhỏ gọn, tuyệt đối không gãy chữ trong từng danh mục */
        .desktop-cat-list {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: center;
            gap: 4px 6px;
        }
        .desktop-cat-item {
            white-space: nowrap !important;
            display: inline-flex;
            align-items: center;
            font-size: 12.5px;
            font-weight: 600;
            line-height: 1.2;
            padding: 6px 10px;
            border-radius: 6px;
            transition: all 0.2s ease;
        }
        @media (min-width: 1280px) {
            .desktop-cat-item {
                font-size: 13px;
                padding: 7px 11px;
            }
        }

        /* Chữ danh mục ở trang chủ nhỏ gọn, không tràn, viết liền trên 1 dòng */
        .home-cat-pill {
            white-space: nowrap !important;
            font-size: 12px;
            line-height: 1.25;
            padding: 7px 12px;
            border-radius: 8px;
            transition: all 0.2s ease;
        }

        /* Tên sản phẩm đầy đủ, tự xuống dòng mượt, không bị cắt mất chữ (không dùng ellipsis) và không tràn khung */
        .product-title-full {
            white-space: normal;
            word-break: break-word;
            overflow-wrap: break-word;
            line-height: 1.38;
        }

        /* Kích thước cố định bằng nhau cho 2 Banner Máy Tính và 2 Banner Điện Thoại */
        .desktop-banner-slide {
            height: 350px;
            width: 100%;
        }
        .mobile-banner-slide {
            height: 220px;
            width: 100%;
        }

        /* Tiêu đề Section kiểu Flatsome (Divider Line) */
        .flatsome-section-title {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #e2e8f0;
            margin-bottom: 18px;
            padding-bottom: 8px;
        }
        .flatsome-section-title h2 {
            position: relative;
            font-weight: 700;
            color: #0072bc;
            text-transform: uppercase;
            letter-spacing: 0.02em;
        }
        .flatsome-section-title h2::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 0;
            width: 100%;
            height: 3px;
            background-color: #0072bc;
        }

        /* Hiệu ứng rung nhẹ cho nút liên hệ nổi */
        @keyframes pulse-ring {
            0% { box-shadow: 0 0 0 0 rgba(0, 114, 188, 0.5); }
            70% { box-shadow: 0 0 0 10px rgba(0, 114, 188, 0); }
            100% { box-shadow: 0 0 0 0 rgba(0, 114, 188, 0); }
        }
        .contact-float-btn {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body>

    <!-- ==========================================
         1. TOP BAR (UX BUILDER TOP BAR)
         ========================================== -->
    <div class="bg-medical-700 text-white text-xs py-1.5 border-b border-medical-800">
        <div class="container-flatsome flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-3 overflow-hidden">
                <span class="inline-flex items-center gap-1.5 font-medium truncate">
                    <i class="fa-solid fa-hospital-user text-sky-300"></i>
                    <span>THANH TÂM MEDICAL - DỊCH VỤ Y TẾ TẠI NHÀ & THIẾT BỊ Y TẾ ĐÀ NẴNG</span>
                </span>
            </div>
            <div class="hidden md:flex items-center gap-4 text-[11.5px] text-sky-100">
                <span><i class="fa-solid fa-location-dot mr-1 text-sky-300"></i>64 Trần Cao Vân, Phường Thanh Khê, Tp.Đà Nẵng</span>
                <span>|</span>
                <span><i class="fa-solid fa-clock mr-1 text-sky-300"></i>Phục vụ 24/7 Cả Lễ & Chủ Nhật</span>
                <span>|</span>
                <a href="https://www.facebook.com/dichvuytetainhataidanang" target="_blank" rel="noopener noreferrer" class="hover:text-white underline">
                    <i class="fa-brands fa-facebook mr-1"></i>Fanpage Thanh Tâm Medical
                </a>
            </div>
        </div>
    </div>

    <!-- ==========================================
         2. HEADER CHÍNH (LOGO GỌN NHỎ - KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN)
         ========================================== -->
    <header class="bg-white shadow-sm sticky top-0 z-40 border-b border-slate-200">
        <div class="container-flatsome py-2.5">
            <div class="flex items-center justify-between gap-3">
                
                <!-- Nút mở Menu danh mục trên điện thoại -->
                <button id="mobileMenuBtn" type="button" aria-label="Mở danh mục" class="lg:hidden inline-flex items-center justify-center w-9 h-9 rounded-lg bg-slate-100 text-medical-700 hover:bg-medical-50 shrink-0">
                    <i class="fa-solid fa-bars text-base"></i>
                </button>

                <!-- Logo Thanh Tâm Medical: chỉnh gọn nhỏ lại theo đúng yêu cầu -->
                <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group">
                    <div class="w-10 h-10 md:w-11 md:h-11 rounded-lg bg-white border border-sky-100 p-0.5 flex items-center justify-center overflow-hidden shadow-xs shrink-0">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1WHFD2AqrulRIbWAiX3zw90FEpWxVS6Y9=w400" 
                            data-drive-id="1WHFD2AqrulRIbWAiX3zw90FEpWxVS6Y9"
                            alt="Logo Thanh Tâm Medical" 
                            class="w-full h-full object-contain"
                            onerror="handleDriveImageError(this, 'LOGO')"
                        >
                    </div>
                    <div class="leading-tight">
                        <span class="block text-sm md:text-base font-extrabold text-medical-600 tracking-tight">THANH TÂM MEDICAL</span>
                        <span class="block text-[10.5px] md:text-[11px] text-slate-500 font-medium">thanhtammedical.com</span>
                    </div>
                </a>

                <!-- Thanh tìm kiếm sản phẩm & dịch vụ y tế (Hiển thị trên máy tính) -->
                <div class="hidden md:flex flex-1 max-w-md mx-4">
                    <div class="relative w-full">
                        <input 
                            id="searchInputDesktop"
                            type="text" 
                            placeholder="Tìm bình oxy, máy thở, giường bệnh, dịch vụ điều dưỡng..." 
                            class="w-full pl-3.5 pr-9 py-1.5 text-xs bg-slate-50 border border-slate-300 rounded-lg focus:outline-none focus:border-medical-600 focus:bg-white"
                        >
                        <button type="button" onclick="filterProductsBySearch('searchInputDesktop')" class="absolute right-2.5 top-1/2 -translate-y-1/2 text-slate-400 hover:text-medical-600">
                            <i class="fa-solid fa-magnifying-glass text-xs"></i>
                        </button>
                    </div>
                </div>

                <!-- Thông tin địa chỉ văn bản nhẹ nhàng trên máy tính (Không để nút gọi ngay trên header tránh tràn viền) -->
                <div class="hidden xl:flex items-center gap-5 text-xs text-slate-600 shrink-0">
                    <div class="flex items-center gap-2">
                        <i class="fa-solid fa-shield-heart text-medical-600 text-base"></i>
                        <div class="leading-tight">
                            <span class="block font-semibold text-slate-800">Thiết bị & Dịch vụ chuẩn Y khoa</span>
                            <span class="text-[11px] text-slate-500">Hỗ trợ tận nhà tại Đà Nẵng & Miền Trung</span>
                        </div>
                    </div>
                </div>

                <!-- Nút tìm kiếm nhỏ trên Mobile -->
                <button id="mobileSearchToggle" type="button" aria-label="Tìm kiếm" class="md:hidden inline-flex items-center justify-center w-9 h-9 rounded-lg bg-slate-100 text-slate-700 shrink-0">
                    <i class="fa-solid fa-magnifying-glass text-sm"></i>
                </button>
            </div>

            <!-- Thanh tìm kiếm mở rộng trên Mobile -->
            <div id="mobileSearchBox" class="hidden md:hidden pt-2">
                <div class="relative w-full">
                    <input 
                        id="searchInputMobile"
                        type="text" 
                        placeholder="Nhập tên thiết bị hoặc dịch vụ y tế cần tìm..." 
                        class="w-full pl-3 pr-9 py-1.5 text-xs bg-slate-50 border border-slate-300 rounded-lg focus:outline-none focus:border-medical-600"
                    >
                    <button type="button" onclick="filterProductsBySearch('searchInputMobile')" class="absolute right-2.5 top-1/2 -translate-y-1/2 text-medical-600">
                        <i class="fa-solid fa-magnifying-glass text-xs"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- ==========================================
             3. THANH DANH MỤC TRÊN MÁY TÍNH (CHỮ NHỎ GỌN, VIẾT LIỀN TRÊN 1 HÀNG HOẶC XUỐNG HÀNG 2, KHÔNG GÃY TÊN DANH MỤC)
             ========================================== -->
        <nav class="hidden lg:block bg-medical-600 text-white border-t border-medical-500">
            <div class="container-flatsome py-1.5">
                <ul class="desktop-cat-list">
                    <li>
                        <a href="#trang-chu" class="desktop-cat-item bg-medical-700 text-white hover:bg-white hover:text-medical-700">
                            <i class="fa-solid fa-house mr-1.5 text-[11px]"></i>Trang chủ
                        </a>
                    </li>
                    <li>
                        <a href="#he-sinh-thai-dich-vu" class="desktop-cat-item text-white hover:bg-medical-700">
                            <i class="fa-solid fa-truck-medical mr-1.5 text-[11px] text-sky-200"></i>Xe Cấp Cứu 24/7
                        </a>
                    </li>
                    <li>
                        <a href="#danh-muc-thuc-te" onclick="selectCategoryFilter('oxy-may-tho')" class="desktop-cat-item text-white hover:bg-medical-700">
                            <i class="fa-solid fa-lungs mr-1.5 text-[11px] text-sky-200"></i>Bình Oxy & Máy Tạo Oxy
                        </a>
                    </li>
                    <li>
                        <a href="#danh-muc-thuc-te" onclick="selectCategoryFilter('oxy-may-tho')" class="desktop-cat-item text-white hover:bg-medical-700">
                            <i class="fa-solid fa-Mask-ventilator mr-1.5 text-[11px] text-sky-200"></i>Thuê Máy Thở & Trợ Thở
                        </a>
                    </li>
                    <li>
                        <a href="#he-sinh-thai-dich-vu" class="desktop-cat-item text-white hover:bg-medical-700">
                            <i class="fa-solid fa-user-nurse mr-1.5 text-[11px] text-sky-200"></i>Điều Dưỡng Tại Nhà
                        </a>
                    </li>
                    <li>
                        <a href="#danh-muc-thuc-te" onclick="selectCategoryFilter('y-te-gia-dinh')" class="desktop-cat-item text-white hover:bg-medical-700">
                            <i class="fa-solid fa-bed-pulse mr-1.5 text-[11px] text-sky-200"></i>Y Tế Gia Đình & Giường Bệnh
                        </a>
                    </li>
                    <li>
                        <a href="#danh-muc-thuc-te" onclick="selectCategoryFilter('y-te-chuyen-dung')" class="desktop-cat-item text-white hover:bg-medical-700">
                            <i class="fa-solid fa-stethoscope mr-1.5 text-[11px] text-sky-200"></i>Y Tế Chuyên Dùng
                        </a>
                    </li>
                    <li>
                        <a href="#danh-muc-thuc-te" onclick="selectCategoryFilter('cham-soc-suc-khoe')" class="desktop-cat-item text-white hover:bg-medical-700">
                            <i class="fa-solid fa-heart-pulse mr-1.5 text-[11px] text-sky-200"></i>Chăm Sóc Sức Khỏe
                        </a>
                    </li>
                    <li>
                        <a href="#form-bao-gia" class="desktop-cat-item text-white hover:bg-medical-700">
                            <i class="fa-solid fa-file-invoice mr-1.5 text-[11px] text-sky-200"></i>Yêu Cầu Báo Giá
                        </a>
                    </li>
                    <li>
                        <a href="#tin-tuc-y-te" class="desktop-cat-item text-white hover:bg-medical-700">
                            <i class="fa-solid fa-newspaper mr-1.5 text-[11px] text-sky-200"></i>Bài Viết Y Tế
                        </a>
                    </li>
                    <li>
                        <a href="#doi-tac-lien-he" class="desktop-cat-item text-white hover:bg-medical-700">
                            <i class="fa-solid fa-map-location-dot mr-1.5 text-[11px] text-sky-200"></i>Bản Đồ & Fanpage
                        </a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>

    <!-- ==========================================
         MENU DANH MỤC TRƯỢT TRÊN ĐIỆN THOẠI (OFF-CANVAS FLATSOME)
         ========================================== -->
    <div id="mobileDrawer" class="fixed inset-0 z-50 hidden">
        <div id="mobileDrawerBackdrop" class="fixed inset-0 bg-slate-900/60 backdrop-blur-xs"></div>
        <div class="relative w-72 max-w-[82vw] bg-white h-full shadow-2xl flex flex-col z-10 overflow-y-auto">
            <div class="p-3.5 bg-medical-600 text-white flex items-center justify-between">
                <div class="flex items-center gap-2">
                    <img src="https://lh3.googleusercontent.com/d/1WHFD2AqrulRIbWAiX3zw90FEpWxVS6Y9=w120" alt="Logo" class="w-7 h-7 rounded bg-white p-0.5 object-contain" onerror="handleDriveImageError(this, 'LOGO')">
                    <span class="font-bold text-xs tracking-wide">DANH MỤC THANH TÂM</span>
                </div>
                <button id="closeMobileDrawer" type="button" class="w-7 h-7 rounded bg-medical-700 flex items-center justify-center text-white">
                    <i class="fa-solid fa-xmark text-sm"></i>
                </button>
            </div>
            <div class="p-3 divide-y divide-slate-100 text-xs font-medium text-slate-700">
                <a href="#trang-chu" onclick="toggleMobileMenu(false)" class="flex items-center gap-2.5 py-2.5 hover:text-medical-600">
                    <i class="fa-solid fa-house text-medical-600 w-4 text-center"></i>Trang chủ Thanh Tâm Medical
                </a>
                <a href="#he-sinh-thai-dich-vu" onclick="toggleMobileMenu(false)" class="flex items-center gap-2.5 py-2.5 hover:text-medical-600">
                    <i class="fa-solid fa-truck-medical text-medical-600 w-4 text-center"></i>Dịch Vụ Xe Cấp Cứu Chuyển Viện
                </a>
                <a href="#danh-muc-thuc-te" onclick="selectCategoryFilter('oxy-may-tho'); toggleMobileMenu(false)" class="flex items-center gap-2.5 py-2.5 hover:text-medical-600">
                    <i class="fa-solid fa-lungs text-medical-600 w-4 text-center"></i>Cho Thuê Bình Oxy & Máy Tạo Oxy
                </a>
                <a href="#danh-muc-thuc-te" onclick="selectCategoryFilter('oxy-may-tho'); toggleMobileMenu(false)" class="flex items-center gap-2.5 py-2.5 hover:text-medical-600">
                    <i class="fa-solid fa-mask-ventilator text-medical-600 w-4 text-center"></i>Cho Thuê Máy Thở, Máy Trợ Thở
                </a>
                <a href="#he-sinh-thai-dich-vu" onclick="toggleMobileMenu(false)" class="flex items-center gap-2.5 py-2.5 hover:text-medical-600">
                    <i class="fa-solid fa-user-nurse text-medical-600 w-4 text-center"></i>Điều Dưỡng Chăm Sóc Tại Nhà 24/24
                </a>
                <a href="#danh-muc-thuc-te" onclick="selectCategoryFilter('y-te-gia-dinh'); toggleMobileMenu(false)" class="flex items-center gap-2.5 py-2.5 hover:text-medical-600">
                    <i class="fa-solid fa-bed-pulse text-medical-600 w-4 text-center"></i>Y Tế Gia Đình (Giường Bệnh, Huyết Áp...)
                </a>
                <a href="#danh-muc-thuc-te" onclick="selectCategoryFilter('y-te-chuyen-dung'); toggleMobileMenu(false)" class="flex items-center gap-2.5 py-2.5 hover:text-medical-600">
                    <i class="fa-solid fa-stethoscope text-medical-600 w-4 text-center"></i>Thiết Bị Y Tế Chuyên Dùng
                </a>
                <a href="#danh-muc-thuc-te" onclick="selectCategoryFilter('cham-soc-suc-khoe'); toggleMobileMenu(false)" class="flex items-center gap-2.5 py-2.5 hover:text-medical-600">
                    <i class="fa-solid fa-heart-pulse text-medical-600 w-4 text-center"></i>Chăm Sóc Sức Khỏe & Phục Hồi
                </a>
                <a href="#form-bao-gia" onclick="toggleMobileMenu(false)" class="flex items-center gap-2.5 py-2.5 hover:text-medical-600">
                    <i class="fa-solid fa-file-signature text-medical-600 w-4 text-center"></i>Form Yêu Cầu Tư Vấn & Báo Giá
                </a>
                <a href="#tin-tuc-y-te" onclick="toggleMobileMenu(false)" class="flex items-center gap-2.5 py-2.5 hover:text-medical-600">
                    <i class="fa-solid fa-newspaper text-medical-600 w-4 text-center"></i>Danh Mục Bài Viết Y Tế
                </a>
                <a href="#doi-tac-lien-he" onclick="toggleMobileMenu(false)" class="flex items-center gap-2.5 py-2.5 hover:text-medical-600">
                    <i class="fa-solid fa-location-dot text-medical-600 w-4 text-center"></i>Bản Đồ & Fanpage
                </a>
            </div>
            <div class="mt-auto p-3.5 bg-slate-50 border-t border-slate-200 text-[11.5px] text-slate-600 space-y-1">
                <p class="font-bold text-medical-700">THANH TÂM MEDICAL ĐÀ NẴNG</p>
                <p><i class="fa-solid fa-location-dot mr-1.5 text-medical-600"></i>64 Trần Cao Vân, P. Thanh Khê, Đà Nẵng</p>
                <p><i class="fa-solid fa-phone mr-1.5 text-medical-600"></i>Hotline 24/7: <strong>0932.552.313</strong></p>
            </div>
        </div>
    </div>

    <!-- ==========================================
         4. BANNER SLIDER TỰ TRƯỢT (2 SLIDE KÍCH THƯỚC BẰNG NHAU)
            - THIẾT KẾ RIÊNG BANNER MÁY TÍNH VÀ BANNER ĐIỆN THOẠI KHÁC NHAU
            - TỐI ƯU CHỮ NHỎ GỌN NẰM HẾT TRONG ẢNH BANNER, KHÔNG TRÀN VIỀN
         ========================================== -->
    <section id="trang-chu" class="py-3">
        <div class="container-flatsome">
            <div class="relative rounded-xl overflow-hidden shadow-sm border border-slate-200 bg-white">
                
                <!-- ================= SLIDE 1 ================= -->
                <div class="banner-slide block" data-slide="0">
                    
                    <!-- Bản Máy Tính (Desktop Banner 1 - Kích thước 350px cố định) -->
                    <div class="hidden md:flex desktop-banner-slide bg-gradient-to-r from-medical-800 via-medical-600 to-sky-600 text-white items-center justify-between px-10 lg:px-14 py-6 relative overflow-hidden">
                        <div class="w-7/12 pr-6 z-10 space-y-2.5">
                            <p class="text-sky-200 text-xs font-semibold uppercase tracking-wider">
                                HỆ SINH THÁI Y TẾ TẠI NHÀ TOÀN DIỆN - THANHTAMMEDICAL.COM
                            </p>
                            <h1 class="text-xl lg:text-2xl xl:text-3xl font-extrabold leading-snug text-white">
                                DỊCH VỤ Y TẾ TẠI NHÀ & CHO THUÊ MÁY THỞ, BÌNH OXY, XE CẤP CỨU 24/7
                            </h1>
                            <p class="text-xs lg:text-sm text-sky-100 leading-relaxed max-w-xl">
                                Đội ngũ Bác sĩ, Điều dưỡng chuyên môn cao chăm sóc tận nhà, tiêm truyền, thay băng cắt chỉ, đặt sonde và lắp đặt máy tạo oxy, máy trợ thở, giường bệnh nhân tận nơi tại Đà Nẵng & miền Trung.
                            </p>
                            <div class="pt-1 flex flex-wrap items-center gap-3 text-xs">
                                <span class="bg-white/15 border border-white/25 px-3 py-1.5 rounded-lg font-medium">
                                    <i class="fa-solid fa-location-dot mr-1 text-sky-200"></i>64 Trần Cao Vân, P. Thanh Khê, Đà Nẵng
                                </span>
                                <span class="bg-amber-400 text-slate-900 px-3.5 py-1.5 rounded-lg font-bold">
                                    <i class="fa-solid fa-phone-volume mr-1"></i>Hotline: 0932.552.313
                                </span>
                            </div>
                        </div>
                        <div class="w-5/12 flex items-center justify-end gap-3 z-10">
                            <div class="w-44 h-56 rounded-xl overflow-hidden border-2 border-white/40 shadow-lg bg-white p-1 shrink-0">
                                <img src="https://lh3.googleusercontent.com/d/1BQTBJdgaO-7RQSs5l_zyX1pt-zaLLvtt=w600" alt="Thiết bị y tế Thanh Tâm" class="w-full h-full object-cover rounded-lg" onerror="handleDriveImageError(this, 'IMG1')">
                            </div>
                            <div class="w-44 h-56 rounded-xl overflow-hidden border-2 border-white/40 shadow-lg bg-white p-1 shrink-0 hidden lg:block">
                                <img src="https://lh3.googleusercontent.com/d/1ow9bziyUSldt5B5MsYWw_ahyw84Ob71X=w600" alt="Máy tạo oxy & máy thở" class="w-full h-full object-cover rounded-lg" onerror="handleDriveImageError(this, 'IMG2')">
                            </div>
                        </div>
                    </div>

                    <!-- Bản Điện Thoại Thiết Kế Mới Riêng Biệt (Mobile Banner 1 - Kích thước 220px cố định, chữ nhỏ gọn nằm trọn bên trong) -->
                    <div class="flex md:hidden mobile-banner-slide bg-gradient-to-br from-medical-800 via-medical-600 to-sky-600 text-white p-3.5 items-center justify-between gap-2.5 relative overflow-hidden">
                        <div class="w-[65%] space-y-1.5 pr-1">
                            <p class="text-[10px] font-semibold text-sky-200 uppercase tracking-tight">
                                THANHTAMMEDICAL.COM
                            </p>
                            <h2 class="text-[13px] font-extrabold leading-tight text-white">
                                DỊCH VỤ Y TẾ TẠI NHÀ & THUÊ BÌNH OXY, MÁY THỞ ĐÀ NẴNG
                            </h2>
                            <p class="text-[10.5px] text-sky-100 leading-snug">
                                Điều dưỡng tại nhà, xe cấp cứu chuyển viện 24/7, giường bệnh nhân.
                            </p>
                            <div class="pt-0.5 text-[10px] font-semibold text-amber-300 leading-tight">
                                <div><i class="fa-solid fa-phone mr-1"></i>SĐT: 0932.552.313</div>
                                <div class="text-white/90 text-[9.5px]"><i class="fa-solid fa-location-dot mr-1"></i>64 Trần Cao Vân, Đà Nẵng</div>
                            </div>
                        </div>
                        <div class="w-[35%] flex justify-end shrink-0">
                            <div class="w-24 h-36 rounded-lg overflow-hidden border border-white/40 bg-white p-0.5 shadow-md">
                                <img src="https://lh3.googleusercontent.com/d/1BQTBJdgaO-7RQSs5l_zyX1pt-zaLLvtt=w400" alt="Thanh Tâm Medical" class="w-full h-full object-cover rounded" onerror="handleDriveImageError(this, 'IMG1')">
                            </div>
                        </div>
                    </div>

                </div>

                <!-- ================= SLIDE 2 ================= -->
                <div class="banner-slide hidden" data-slide="1">
                    
                    <!-- Bản Máy Tính (Desktop Banner 2 - Kích thước 350px cố định bằng hệt Slide 1) -->
                    <div class="hidden md:flex desktop-banner-slide bg-gradient-to-r from-teal-800 via-teal-600 to-medical-600 text-white items-center justify-between px-10 lg:px-14 py-6 relative overflow-hidden">
                        <div class="w-7/12 pr-6 z-10 space-y-2.5">
                            <p class="text-teal-100 text-xs font-semibold uppercase tracking-wider">
                                TRANG THIẾT BỊ Y TẾ GIA ĐÌNH & CHUYÊN DỤNG CHÍNH HÃNG
                            </p>
                            <h2 class="text-xl lg:text-2xl xl:text-3xl font-extrabold leading-snug text-white">
                                CUNG CẤP GIƯỜNG BỆNH NHÂN, MÁY TẠO OXY, MÁY HÚT DỊCH, ĐO HUYẾT ÁP
                            </h2>
                            <p class="text-xs lg:text-sm text-teal-50 leading-relaxed max-w-xl">
                                Phân phối và cho thuê thiết bị phục hồi chức năng, máy theo dõi SpO2, băng ca cấp cứu, xe lăn, đệm chống loét chính hãng. Giao lắp tận nơi nhanh chóng trong 15 - 30 phút.
                            </p>
                            <div class="pt-1 flex flex-wrap items-center gap-3 text-xs">
                                <span class="bg-white/15 border border-white/25 px-3 py-1.5 rounded-lg font-medium">
                                    <i class="fa-solid fa-circle-check mr-1 text-teal-200"></i>Bảo hành chính hãng - Hướng dẫn tận tâm
                                </span>
                                <span class="bg-amber-400 text-slate-900 px-3.5 py-1.5 rounded-lg font-bold">
                                    <i class="fa-solid fa-headset mr-1"></i>Tư vấn 24/7: 0932.552.313
                                </span>
                            </div>
                        </div>
                        <div class="w-5/12 flex items-center justify-end gap-3 z-10">
                            <div class="w-44 h-56 rounded-xl overflow-hidden border-2 border-white/40 shadow-lg bg-white p-1 shrink-0">
                                <img src="https://lh3.googleusercontent.com/d/1frQ_RtB3ptD-C6wzQIhkDLXyQO2QVX7i=w600" alt="Thiết bị y tế tại nhà" class="w-full h-full object-cover rounded-lg" onerror="handleDriveImageError(this, 'IMG3')">
                            </div>
                            <div class="w-44 h-56 rounded-xl overflow-hidden border-2 border-white/40 shadow-lg bg-white p-1 shrink-0 hidden lg:block">
                                <img src="https://lh3.googleusercontent.com/d/1biAq6JpYplG47CmnhQA3c7UdqbdXtMyN=w600" alt="Giường y tế & phụ kiện" class="w-full h-full object-cover rounded-lg" onerror="handleDriveImageError(this, 'IMG4')">
                            </div>
                        </div>
                    </div>

                    <!-- Bản Điện Thoại Thiết Kế Mới Riêng Biệt (Mobile Banner 2 - Kích thước 220px cố định bằng hệt Slide 1) -->
                    <div class="flex md:hidden mobile-banner-slide bg-gradient-to-br from-teal-800 via-teal-600 to-medical-600 text-white p-3.5 items-center justify-between gap-2.5 relative overflow-hidden">
                        <div class="w-[65%] space-y-1.5 pr-1">
                            <p class="text-[10px] font-semibold text-teal-200 uppercase tracking-tight">
                                THIẾT BỊ Y TẾ CHÍNH HÃNG
                            </p>
                            <h2 class="text-[13px] font-extrabold leading-tight text-white">
                                GIƯỜNG Y TẾ, MÁY TẠO OXY, MÁY ĐO HUYẾT ÁP & HÚT DỊCH
                            </h2>
                            <p class="text-[10.5px] text-teal-50 leading-snug">
                                Mua bán & cho thuê thiết bị y tế gia đình, giao lắp tận nhà nhanh chóng.
                            </p>
                            <div class="pt-0.5 text-[10px] font-semibold text-amber-300 leading-tight">
                                <div><i class="fa-solid fa-phone mr-1"></i>Hotline: 0932.552.313</div>
                                <div class="text-white/90 text-[9.5px]"><i class="fa-solid fa-location-dot mr-1"></i>64 Trần Cao Vân, Đà Nẵng</div>
                            </div>
                        </div>
                        <div class="w-[35%] flex justify-end shrink-0">
                            <div class="w-24 h-36 rounded-lg overflow-hidden border border-white/40 bg-white p-0.5 shadow-md">
                                <img src="https://lh3.googleusercontent.com/d/1frQ_RtB3ptD-C6wzQIhkDLXyQO2QVX7i=w400" alt="Thiết bị y tế Đà Nẵng" class="w-full h-full object-cover rounded" onerror="handleDriveImageError(this, 'IMG3')">
                            </div>
                        </div>
                    </div>

                </div>

                <!-- Nút chấm chuyển Slide Banner -->
                <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 flex items-center gap-2 z-20">
                    <button type="button" onclick="goToSlide(0)" id="dotSlide0" aria-label="Slide 1" class="w-6 h-2 rounded-full bg-white transition-all"></button>
                    <button type="button" onclick="goToSlide(1)" id="dotSlide1" aria-label="Slide 2" class="w-2.5 h-2 rounded-full bg-white/50 transition-all"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         5. DANH MỤC SẢN PHẨM & DỊCH VỤ TRANG CHỦ (LẤY TỪ WEB MẪU HOMECARETUANHOANG.COM)
            - TỐI ƯU HIỂN THỊ ĐẸP TRÊN CẢ MÁY TÍNH VÀ ĐIỆN THOẠI
            - CHỮ DANH MỤC NHỎ GỌN, VIẾT LIỀN TRÊN 1 DÒNG, KHÔNG XUỐNG DÒNG TÊN DANH MỤC
         ========================================== -->
    <section class="py-3">
        <div class="container-flatsome">
            <div class="bg-white rounded-xl p-3.5 md:p-4 shadow-xs border border-slate-200">
                <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 pb-3 mb-3 border-b border-slate-100">
                    <h2 class="text-xs md:text-sm font-bold text-medical-700 uppercase flex items-center gap-2">
                        <i class="fa-solid fa-layer-group text-medical-600"></i>
                        <span>DANH MỤC DỊCH VỤ & THIẾT BỊ Y TẾ THANH TÂM MEDICAL</span>
                    </h2>
                    <span class="text-[11px] text-slate-500">Chọn danh mục để lọc nhanh sản phẩm & dịch vụ</span>
                </div>

                <!-- Danh mục hiển thị gọn đẹp, chữ nhỏ gọn, viết liền không gãy chữ -->
                <div class="flex flex-wrap items-center gap-1.5 md:gap-2">
                    <button type="button" onclick="selectCategoryFilter('all')" data-cat-btn="all" class="cat-filter-btn home-cat-pill bg-medical-600 text-white font-semibold border border-medical-600">
                        <i class="fa-solid fa-border-all mr-1"></i>Tất cả danh mục
                    </button>
                    <button type="button" onclick="selectCategoryFilter('dich-vu-y-te')" data-cat-btn="dich-vu-y-te" class="cat-filter-btn home-cat-pill bg-slate-50 hover:bg-medical-50 text-slate-700 border border-slate-200 font-medium">
                        <i class="fa-solid fa-user-doctor mr-1 text-medical-600"></i>Dịch vụ Y tế tại nhà
                    </button>
                    <button type="button" onclick="selectCategoryFilter('oxy-may-tho')" data-cat-btn="oxy-may-tho" class="cat-filter-btn home-cat-pill bg-slate-50 hover:bg-medical-50 text-slate-700 border border-slate-200 font-medium">
                        <i class="fa-solid fa-lungs mr-1 text-medical-600"></i>Bình Oxy & Máy Thở
                    </button>
                    <button type="button" onclick="selectCategoryFilter('y-te-gia-dinh')" data-cat-btn="y-te-gia-dinh" class="cat-filter-btn home-cat-pill bg-slate-50 hover:bg-medical-50 text-slate-700 border border-slate-200 font-medium">
                        <i class="fa-solid fa-bed mr-1 text-medical-600"></i>Y tế gia đình
                    </button>
                    <button type="button" onclick="selectCategoryFilter('y-te-chuyen-dung')" data-cat-btn="y-te-chuyen-dung" class="cat-filter-btn home-cat-pill bg-slate-50 hover:bg-medical-50 text-slate-700 border border-slate-200 font-medium">
                        <i class="fa-solid fa-microscope mr-1 text-medical-600"></i>Y tế chuyên dùng
                    </button>
                    <button type="button" onclick="selectCategoryFilter('cham-soc-suc-khoe')" data-cat-btn="cham-soc-suc-khoe" class="cat-filter-btn home-cat-pill bg-slate-50 hover:bg-medical-50 text-slate-700 border border-slate-200 font-medium">
                        <i class="fa-solid fa-heart-circle-check mr-1 text-medical-600"></i>Chăm sóc sức khỏe
                    </button>
                    <button type="button" onclick="selectCategoryFilter('cham-soc-sac-dep')" data-cat-btn="cham-soc-sac-dep" class="cat-filter-btn home-cat-pill bg-slate-50 hover:bg-medical-50 text-slate-700 border border-slate-200 font-medium">
                        <i class="fa-solid fa-spa mr-1 text-medical-600"></i>Chăm sóc sắc đẹp
                    </button>
                </div>

                <!-- Danh sách các nhóm danh mục con chi tiết giống mẫu Homecare Tuấn Hoàng -->
                <div class="mt-3 pt-2.5 border-t border-slate-100 grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2 text-[11.5px] text-slate-600">
                    <div class="bg-slate-50/80 rounded-lg p-2 border border-slate-100">
                        <div class="font-bold text-medical-700 mb-1 whitespace-nowrap">1. Dịch vụ Y tế 24/7</div>
                        <ul class="space-y-0.5 text-[11px] text-slate-600">
                            <li class="whitespace-nowrap">• Xe cấp cứu chuyển viện</li>
                            <li class="whitespace-nowrap">• Bác sĩ gia đình Đà Nẵng</li>
                            <li class="whitespace-nowrap">• Điều dưỡng chăm sóc</li>
                            <li class="whitespace-nowrap">• Tiêm thuốc, truyền dịch</li>
                        </ul>
                    </div>
                    <div class="bg-slate-50/80 rounded-lg p-2 border border-slate-100">
                        <div class="font-bold text-medical-700 mb-1 whitespace-nowrap">2. Thuê Oxy & Máy Thở</div>
                        <ul class="space-y-0.5 text-[11px] text-slate-600">
                            <li class="whitespace-nowrap">• Bình oxy y tế 8L - 40L</li>
                            <li class="whitespace-nowrap">• Máy tạo oxy 5L - 10L</li>
                            <li class="whitespace-nowrap">• Máy thở xâm nhập/CPAP</li>
                            <li class="whitespace-nowrap">• Máy theo dõi Monitor</li>
                        </ul>
                    </div>
                    <div class="bg-slate-50/80 rounded-lg p-2 border border-slate-100">
                        <div class="font-bold text-medical-700 mb-1 whitespace-nowrap">3. Y tế gia đình</div>
                        <ul class="space-y-0.5 text-[11px] text-slate-600">
                            <li class="whitespace-nowrap">• Giường bệnh nhân tay quay</li>
                            <li class="whitespace-nowrap">• Máy đo huyết áp, tiểu đường</li>
                            <li class="whitespace-nowrap">• Máy xông khí dung, hút dịch</li>
                            <li class="whitespace-nowrap">• Đèn hồng ngoại, vớ y khoa</li>
                        </ul>
                    </div>
                    <div class="bg-slate-50/80 rounded-lg p-2 border border-slate-100">
                        <div class="font-bold text-medical-700 mb-1 whitespace-nowrap">4. Y tế chuyên dùng</div>
                        <ul class="space-y-0.5 text-[11px] text-slate-600">
                            <li class="whitespace-nowrap">• Băng ca xe cứu thương</li>
                            <li class="whitespace-nowrap">• Máy đo SpO2, điện tim</li>
                            <li class="whitespace-nowrap">• Nồi hấp tiệt trùng y tế</li>
                            <li class="whitespace-nowrap">• Bóp bóng Ambu, ống nghe</li>
                        </ul>
                    </div>
                    <div class="bg-slate-50/80 rounded-lg p-2 border border-slate-100">
                        <div class="font-bold text-medical-700 mb-1 whitespace-nowrap">5. Chăm sóc sức khỏe</div>
                        <ul class="space-y-0.5 text-[11px] text-slate-600">
                            <li class="whitespace-nowrap">• Đai lưng cột sống, cổ</li>
                            <li class="whitespace-nowrap">• Máy massage trị liệu</li>
                            <li class="whitespace-nowrap">• Máy tăm nước, chăn điện</li>
                            <li class="whitespace-nowrap">• Thiết bị trị ngáy</li>
                        </ul>
                    </div>
                    <div class="bg-slate-50/80 rounded-lg p-2 border border-slate-100">
                        <div class="font-bold text-medical-700 mb-1 whitespace-nowrap">6. Thủ thuật tại nhà</div>
                        <ul class="space-y-0.5 text-[11px] text-slate-600">
                            <li class="whitespace-nowrap">• Thay băng, cắt chỉ, rửa loét</li>
                            <li class="whitespace-nowrap">• Đặt Sonde tiểu, dạ dày</li>
                            <li class="whitespace-nowrap">• Lấy máu xét nghiệm tận nơi</li>
                            <li class="whitespace-nowrap">• Tập vật lý trị liệu PHCN</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         6. HỆ SINH THÁI 4 DỊCH VỤ TRỌNG TÂM (GIỐNG MẪU HOMECARETUANHOANG.COM)
         ========================================== -->
    <section id="he-sinh-thai-dich-vu" class="py-4">
        <div class="container-flatsome">
            <div class="flatsome-section-title">
                <h2 class="text-sm md:text-base">HỆ SINH THÁI DỊCH VỤ Y TẾ TẠI NHÀ ĐÀ NẴNG</h2>
                <span class="text-xs text-slate-500 hidden sm:inline">Phục vụ tận tâm 24/24 - Gọi 0932.552.313</span>
            </div>

            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-4">
                <!-- Dịch vụ 1 -->
                <div class="bg-white rounded-xl border border-slate-200 p-3.5 shadow-xs flex flex-col justify-between">
                    <div>
                        <div class="w-10 h-10 rounded-lg bg-sky-50 text-medical-600 flex items-center justify-center mb-2.5">
                            <i class="fa-solid fa-truck-medical text-lg"></i>
                        </div>
                        <h3 class="product-title-full text-xs md:text-sm font-bold text-slate-800 mb-1.5">
                            Dịch Vụ Xe Cấp Cứu Vận Chuyển Người Bệnh 24/7
                        </h3>
                        <p class="text-[11.5px] text-slate-600 leading-relaxed">
                            Hỗ trợ xe cứu thương chuyên dụng xuất viện, nhập viện, chuyển tuyến từ Đà Nẵng đi các tỉnh Nam - Bắc có oxy, máy thở và điều dưỡng đi kèm.
                        </p>
                    </div>
                    <div class="mt-3 pt-2.5 border-t border-slate-100">
                        <a href="#form-bao-gia" onclick="prefillService('Dịch vụ Xe cấp cứu vận chuyển bệnh nhân')" class="text-xs font-semibold text-medical-600 hover:underline inline-flex items-center gap-1">
                            <span>Đặt lịch tư vấn</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </div>

                <!-- Dịch vụ 2 -->
                <div class="bg-white rounded-xl border border-slate-200 p-3.5 shadow-xs flex flex-col justify-between">
                    <div>
                        <div class="w-10 h-10 rounded-lg bg-sky-50 text-medical-600 flex items-center justify-center mb-2.5">
                            <i class="fa-solid fa-mask-ventilator text-lg"></i>
                        </div>
                        <h3 class="product-title-full text-xs md:text-sm font-bold text-slate-800 mb-1.5">
                            Cho Thuê Máy Thở, Máy Trợ Thở Chuyên Nghiệp Tại Nhà
                        </h3>
                        <p class="text-[11.5px] text-slate-600 leading-relaxed">
                            Lắp đặt tận nơi máy thở xâm nhập, không xâm nhập CPAP/BiPAP, monitor theo dõi 5 thông số, phục vụ 24/24 nhanh chóng, chính xác cao.
                        </p>
                    </div>
                    <div class="mt-3 pt-2.5 border-t border-slate-100">
                        <a href="#form-bao-gia" onclick="prefillService('Thuê máy thở, máy trợ thở tại nhà')" class="text-xs font-semibold text-medical-600 hover:underline inline-flex items-center gap-1">
                            <span>Đặt lịch tư vấn</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </div>

                <!-- Dịch vụ 3 -->
                <div class="bg-white rounded-xl border border-slate-200 p-3.5 shadow-xs flex flex-col justify-between">
                    <div>
                        <div class="w-10 h-10 rounded-lg bg-sky-50 text-medical-600 flex items-center justify-center mb-2.5">
                            <i class="fa-solid fa-lungs text-lg"></i>
                        </div>
                        <h3 class="product-title-full text-xs md:text-sm font-bold text-slate-800 mb-1.5">
                            Mua Bán & Cho Thuê Bình Oxy, Máy Tạo Oxy Tại Nhà
                        </h3>
                        <p class="text-[11.5px] text-slate-600 leading-relaxed">
                            Cung ứng giao nhanh bình oxy y tế 8L, 10L, 40L và máy tạo oxy 5L - 10L tận nhà 24/24 tại Đà Nẵng, Quảng Nam, Huế.
                        </p>
                    </div>
                    <div class="mt-3 pt-2.5 border-t border-slate-100">
                        <a href="#form-bao-gia" onclick="prefillService('Mua bán / Cho thuê bình oxy, máy tạo oxy')" class="text-xs font-semibold text-medical-600 hover:underline inline-flex items-center gap-1">
                            <span>Đặt lịch tư vấn</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </div>

                <!-- Dịch vụ 4 -->
                <div class="bg-white rounded-xl border border-slate-200 p-3.5 shadow-xs flex flex-col justify-between">
                    <div>
                        <div class="w-10 h-10 rounded-lg bg-sky-50 text-medical-600 flex items-center justify-center mb-2.5">
                            <i class="fa-solid fa-user-nurse text-lg"></i>
                        </div>
                        <h3 class="product-title-full text-xs md:text-sm font-bold text-slate-800 mb-1.5">
                            Điều Dưỡng Chăm Sóc Tại Nhà - Tiêm Truyền, Thay Băng
                        </h3>
                        <p class="text-[11.5px] text-slate-600 leading-relaxed">
                            Chăm sóc người bệnh, người cao tuổi, tiêm thuốc, truyền dịch, thay băng rửa vết loét tỳ đè, đặt Sonde tiểu, Sonde dạ dày tại nhà.
                        </p>
                    </div>
                    <div class="mt-3 pt-2.5 border-t border-slate-100">
                        <a href="#form-bao-gia" onclick="prefillService('Điều dưỡng chăm sóc, tiêm truyền, thay băng tại nhà')" class="text-xs font-semibold text-medical-600 hover:underline inline-flex items-center gap-1">
                            <span>Đặt lịch tư vấn</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         7. DANH MỤC SẢN PHẨM & HÌNH ẢNH THỰC TẾ TỪ 6 FILE GOOGLE DRIVE
            - CHIA THÀNH 2 CỘT TRÊN ĐIỆN THOẠI (grid-cols-2), 3-4 CỘT TRÊN MÁY TÍNH
            - TÊN SẢN PHẨM ĐẦY ĐỦ, KHÔNG TRÀN VIỀN, KHÔNG BỊ CẮT THIẾU CHỮ
            - KHÔNG ĐỂ NHÃN DÁN (STICKER/BADGE) Ở TRANG CHỦ
         ========================================== -->
    <section id="danh-muc-thuc-te" class="py-4">
        <div class="container-flatsome">
            
            <!-- Nhóm 1: 6 Hình Ảnh Thực Tế Từ Google Drive Gắn Đúng Danh Mục & Tên Sản Phẩm -->
            <div class="flatsome-section-title">
                <h2 class="text-sm md:text-base">THIẾT BỊ Y TẾ & DỊCH VỤ THỰC TẾ TẠI THANH TÂM MEDICAL</h2>
                <span class="text-xs text-slate-500 hidden sm:inline">Hình ảnh thực tế tại 64 Trần Cao Vân, Đà Nẵng</span>
            </div>

            <!-- Grid chia 2 cột trên điện thoại (grid-cols-2), 3 cột trên máy tính -->
            <div id="productGridMain" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-3 gap-3 md:gap-4">
                
                <!-- Ảnh Thực Tế Drive 1: 1BQTBJdgaO-7RQSs5l_zyX1pt-zaLLvtt -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs flex flex-col justify-between" data-category="oxy-may-tho y-te-chuyen-dung">
                    <div>
                        <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden border-b border-slate-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1BQTBJdgaO-7RQSs5l_zyX1pt-zaLLvtt=w800" 
                                data-drive-id="1BQTBJdgaO-7RQSs5l_zyX1pt-zaLLvtt"
                                alt="Máy tạo oxy y tế và bình oxy lưu lượng cao tại nhà" 
                                class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
                                onerror="handleDriveImageError(this, 'IMG1')"
                            >
                        </div>
                        <div class="p-2.5 md:p-3.5">
                            <div class="text-[10.5px] text-medical-600 font-semibold mb-1">Danh mục: Bình Oxy & Máy Tạo Oxy</div>
                            <h3 class="product-title-full text-xs md:text-sm font-bold text-slate-800 mb-1.5">
                                Máy Tạo Oxy Y Tế Lưu Lượng Cao 5 Lít - 10 Lít Kèm Phụ Kiện Thở Tại Nhà
                            </h3>
                            <p class="text-[11px] text-slate-500 leading-snug">
                                Cung cấp oxy tinh khiết liên tục 24/24 cho bệnh nhân suy hô hấp, COPD, người cao tuổi tại nhà.
                            </p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 md:px-3.5 md:pb-3.5 pt-1 flex items-center justify-between border-t border-slate-100 mt-1">
                        <span class="text-xs font-bold text-medical-700">Liên hệ: 0932.552.313</span>
                        <a href="#form-bao-gia" onclick="prefillService('Máy Tạo Oxy Y Tế 5L - 10L tại nhà')" class="text-[11px] font-semibold text-white bg-medical-600 hover:bg-medical-700 px-2.5 py-1 rounded-md">
                            Báo giá
                        </a>
                    </div>
                </div>

                <!-- Ảnh Thực Tế Drive 2: 1ow9bziyUSldt5B5MsYWw_ahyw84Ob71X -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs flex flex-col justify-between" data-category="oxy-may-tho y-te-chuyen-dung">
                    <div>
                        <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden border-b border-slate-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1ow9bziyUSldt5B5MsYWw_ahyw84Ob71X=w800" 
                                data-drive-id="1ow9bziyUSldt5B5MsYWw_ahyw84Ob71X"
                                alt="Bình oxy y tế chuyên dụng kèm đồng hồ điều áp" 
                                class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
                                onerror="handleDriveImageError(this, 'IMG2')"
                            >
                        </div>
                        <div class="p-2.5 md:p-3.5">
                            <div class="text-[10.5px] text-medical-600 font-semibold mb-1">Danh mục: Bình Oxy & Máy Thở</div>
                            <h3 class="product-title-full text-xs md:text-sm font-bold text-slate-800 mb-1.5">
                                Bộ Bình Khí Oxy Y Tế 8 Lít - 40 Lít Kèm Đồng Hồ Điều Áp & Bình Làm Ẩm
                            </h3>
                            <p class="text-[11px] text-slate-500 leading-snug">
                                Mua bán và cho thuê bình oxy y tế tận nơi tại Đà Nẵng, giao nhanh 15 phút, kiểm định an toàn.
                            </p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 md:px-3.5 md:pb-3.5 pt-1 flex items-center justify-between border-t border-slate-100 mt-1">
                        <span class="text-xs font-bold text-medical-700">Liên hệ: 0932.552.313</span>
                        <a href="#form-bao-gia" onclick="prefillService('Bộ Bình Khí Oxy Y Tế 8L - 40L')" class="text-[11px] font-semibold text-white bg-medical-600 hover:bg-medical-700 px-2.5 py-1 rounded-md">
                            Báo giá
                        </a>
                    </div>
                </div>

                <!-- Ảnh Thực Tế Drive 3: 1frQ_RtB3ptD-C6wzQIhkDLXyQO2QVX7i -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs flex flex-col justify-between" data-category="oxy-may-tho y-te-chuyen-dung">
                    <div>
                        <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden border-b border-slate-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1frQ_RtB3ptD-C6wzQIhkDLXyQO2QVX7i=w800" 
                                data-drive-id="1frQ_RtB3ptD-C6wzQIhkDLXyQO2QVX7i"
                                alt="Máy thở và máy trợ thở CPAP BiPAP chuyên nghiệp" 
                                class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
                                onerror="handleDriveImageError(this, 'IMG3')"
                            >
                        </div>
                        <div class="p-2.5 md:p-3.5">
                            <div class="text-[10.5px] text-medical-600 font-semibold mb-1">Danh mục: Y Tế Chuyên Dùng</div>
                            <h3 class="product-title-full text-xs md:text-sm font-bold text-slate-800 mb-1.5">
                                Máy Thở & Máy Trợ Thở Không Xâm Nhập CPAP / BiPAP Chăm Sóc Hô Hấp Tại Nhà
                            </h3>
                            <p class="text-[11px] text-slate-500 leading-snug">
                                Thiết bị hỗ trợ hô hấp chuyên sâu, có kỹ thuật viên và bác sĩ cài đặt thông số tận nhà.
                            </p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 md:px-3.5 md:pb-3.5 pt-1 flex items-center justify-between border-t border-slate-100 mt-1">
                        <span class="text-xs font-bold text-medical-700">Liên hệ: 0932.552.313</span>
                        <a href="#form-bao-gia" onclick="prefillService('Máy Thở & Máy Trợ Thở CPAP/BiPAP')" class="text-[11px] font-semibold text-white bg-medical-600 hover:bg-medical-700 px-2.5 py-1 rounded-md">
                            Báo giá
                        </a>
                    </div>
                </div>

                <!-- Ảnh Thực Tế Drive 4: 1biAq6JpYplG47CmnhQA3c7UdqbdXtMyN -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs flex flex-col justify-between" data-category="y-te-gia-dinh cham-soc-suc-khoe">
                    <div>
                        <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden border-b border-slate-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1biAq6JpYplG47CmnhQA3c7UdqbdXtMyN=w800" 
                                data-drive-id="1biAq6JpYplG47CmnhQA3c7UdqbdXtMyN"
                                alt="Giường bệnh nhân y tế đa năng tay quay và điều khiển điện" 
                                class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
                                onerror="handleDriveImageError(this, 'IMG4')"
                            >
                        </div>
                        <div class="p-2.5 md:p-3.5">
                            <div class="text-[10.5px] text-medical-600 font-semibold mb-1">Danh mục: Y Tế Gia Đình</div>
                            <h3 class="product-title-full text-xs md:text-sm font-bold text-slate-800 mb-1.5">
                                Giường Bệnh Nhân Y Tế Đa Năng Nâng Đầu, Nghiêng Trái Phải Kèm Đệm Y Khoa
                            </h3>
                            <p class="text-[11px] text-slate-500 leading-snug">
                                Bán và cho thuê giường bệnh nhân 2 tay quay, 4 tay quay và giường điện hỗ trợ chăm sóc người bệnh.
                            </p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 md:px-3.5 md:pb-3.5 pt-1 flex items-center justify-between border-t border-slate-100 mt-1">
                        <span class="text-xs font-bold text-medical-700">Liên hệ: 0932.552.313</span>
                        <a href="#form-bao-gia" onclick="prefillService('Giường Bệnh Nhân Y Tế Đa Năng')" class="text-[11px] font-semibold text-white bg-medical-600 hover:bg-medical-700 px-2.5 py-1 rounded-md">
                            Báo giá
                        </a>
                    </div>
                </div>

                <!-- Ảnh Thực Tế Drive 5: 1YYsbngpl2d4g3t4V8gEZrOOGrwtM0LH6 -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs flex flex-col justify-between" data-category="y-te-gia-dinh y-te-chuyen-dung">
                    <div>
                        <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden border-b border-slate-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1YYsbngpl2d4g3t4V8gEZrOOGrwtM0LH6=w800" 
                                data-drive-id="1YYsbngpl2d4g3t4V8gEZrOOGrwtM0LH6"
                                alt="Máy hút dịch đờm và máy xông khí dung mũi họng" 
                                class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
                                onerror="handleDriveImageError(this, 'IMG5')"
                            >
                        </div>
                        <div class="p-2.5 md:p-3.5">
                            <div class="text-[10.5px] text-medical-600 font-semibold mb-1">Danh mục: Y Tế Gia Đình & Chuyên Dùng</div>
                            <h3 class="product-title-full text-xs md:text-sm font-bold text-slate-800 mb-1.5">
                                Máy Hút Dịch Đờm Y Tế 2 Bình & Máy Xông Khí Dung Mũi Họng Chuyên Dụng
                            </h3>
                            <p class="text-[11px] text-slate-500 leading-snug">
                                Hỗ trợ làm sạch đường thở, hút đờm dãi an toàn cho người già, người bệnh mở khí quản tại nhà.
                            </p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 md:px-3.5 md:pb-3.5 pt-1 flex items-center justify-between border-t border-slate-100 mt-1">
                        <span class="text-xs font-bold text-medical-700">Liên hệ: 0932.552.313</span>
                        <a href="#form-bao-gia" onclick="prefillService('Máy Hút Dịch Đờm & Máy Xông Mũi Họng')" class="text-[11px] font-semibold text-white bg-medical-600 hover:bg-medical-700 px-2.5 py-1 rounded-md">
                            Báo giá
                        </a>
                    </div>
                </div>

                <!-- Ảnh Thực Tế Drive 6: 1uhHDEkEdgk3ItTXJ0qRAPMP_t7V76mk5 -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs flex flex-col justify-between" data-category="dich-vu-y-te y-te-chuyen-dung">
                    <div>
                        <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden border-b border-slate-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1uhHDEkEdgk3ItTXJ0qRAPMP_t7V76mk5=w800" 
                                data-drive-id="1uhHDEkEdgk3ItTXJ0qRAPMP_t7V76mk5"
                                alt="Thiết bị theo dõi bệnh nhân Monitor SpO2 và dịch vụ chăm sóc tại nhà" 
                                class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
                                onerror="handleDriveImageError(this, 'IMG6')"
                            >
                        </div>
                        <div class="p-2.5 md:p-3.5">
                            <div class="text-[10.5px] text-medical-600 font-semibold mb-1">Danh mục: Dịch Vụ Y Tế & Theo Dõi</div>
                            <h3 class="product-title-full text-xs md:text-sm font-bold text-slate-800 mb-1.5">
                                Máy Monitor Theo Dõi Bệnh Nhân 5 Thông Số, Máy Đo SpO2 & Huyết Áp Điện Tử
                            </h3>
                            <p class="text-[11px] text-slate-500 leading-snug">
                                Theo dõi liên tục nhịp tim, nồng độ oxy máu SpO2, huyết áp, nhiệt độ và nhịp thở tại gia đình.
                            </p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 md:px-3.5 md:pb-3.5 pt-1 flex items-center justify-between border-t border-slate-100 mt-1">
                        <span class="text-xs font-bold text-medical-700">Liên hệ: 0932.552.313</span>
                        <a href="#form-bao-gia" onclick="prefillService('Máy Monitor Theo Dõi Bệnh Nhân & Đo SpO2')" class="text-[11px] font-semibold text-white bg-medical-600 hover:bg-medical-700 px-2.5 py-1 rounded-md">
                            Báo giá
                        </a>
                    </div>
                </div>

            </div>

            <!-- ==========================================
                 8. DANH SÁCH SẢN PHẨM THEO DANH MỤC WEB MẪU (CHIA 2 CỘT TRÊN ĐIỆN THOẠI, 4 CỘT TRÊN MÁY TÍNH)
                 ========================================== -->
            <div class="mt-7">
                <div class="flatsome-section-title">
                    <h2 class="text-sm md:text-base">DANH MỤC SẢN PHẨM Y TẾ GIA ĐÌNH & CHUYÊN DỤNG</h2>
                    <span class="text-xs text-slate-500 hidden sm:inline">Chính hãng - Giao tận nơi tại Đà Nẵng</span>
                </div>

                <!-- Chia đúng 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4) -->
                <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 md:gap-4">
                    
                    <!-- SP 1 -->
                    <div class="product-card bg-white rounded-xl border border-slate-200 p-2.5 md:p-3.5 flex flex-col justify-between" data-category="y-te-gia-dinh">
                        <div>
                            <div class="w-full h-28 md:h-36 rounded-lg bg-sky-50/70 flex items-center justify-center mb-2.5 border border-sky-100">
                                <i class="fa-solid fa-heart-pulse text-3xl md:text-4xl text-medical-600"></i>
                            </div>
                            <div class="text-[10px] text-slate-400 font-medium mb-0.5">Y tế gia đình</div>
                            <h3 class="product-title-full text-xs md:text-sm font-bold text-slate-800 mb-1">
                                Máy Đo Huyết Áp Bắp Tay Tự Động & Máy Đo Đường Huyết Tại Nhà
                            </h3>
                            <p class="text-[11px] text-slate-500">Đo chính xác chỉ số huyết áp tâm thu, tâm trương, cảnh báo rối loạn nhịp tim.</p>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-slate-100 flex items-center justify-between">
                            <span class="text-[11px] font-bold text-medical-600">0932.552.313</span>
                            <a href="#form-bao-gia" onclick="prefillService('Máy Đo Huyết Áp & Máy Đo Đường Huyết')" class="text-[11px] font-medium text-medical-700 hover:underline">Đặt mua</a>
                        </div>
                    </div>

                    <!-- SP 2 -->
                    <div class="product-card bg-white rounded-xl border border-slate-200 p-2.5 md:p-3.5 flex flex-col justify-between" data-category="y-te-gia-dinh cham-soc-suc-khoe">
                        <div>
                            <div class="w-full h-28 md:h-36 rounded-lg bg-sky-50/70 flex items-center justify-center mb-2.5 border border-sky-100">
                                <i class="fa-solid fa-wheelchair text-3xl md:text-4xl text-medical-600"></i>
                            </div>
                            <div class="text-[10px] text-slate-400 font-medium mb-0.5">Y tế gia đình</div>
                            <h3 class="product-title-full text-xs md:text-sm font-bold text-slate-800 mb-1">
                                Xe Lăn Y Tế Đa Năng Có Bô Vệ Sinh, Khung Tập Đi & Đệm Hơi Chống Loét
                            </h3>
                            <p class="text-[11px] text-slate-500">Hỗ trợ di chuyển và phòng ngừa loét tỳ đè cho người bệnh nằm lâu ngày.</p>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-slate-100 flex items-center justify-between">
                            <span class="text-[11px] font-bold text-medical-600">0932.552.313</span>
                            <a href="#form-bao-gia" onclick="prefillService('Xe Lăn Y Tế & Đệm Hơi Chống Loét')" class="text-[11px] font-medium text-medical-700 hover:underline">Đặt mua</a>
                        </div>
                    </div>

                    <!-- SP 3 -->
                    <div class="product-card bg-white rounded-xl border border-slate-200 p-2.5 md:p-3.5 flex flex-col justify-between" data-category="y-te-gia-dinh cham-soc-suc-khoe">
                        <div>
                            <div class="w-full h-28 md:h-36 rounded-lg bg-sky-50/70 flex items-center justify-center mb-2.5 border border-sky-100">
                                <i class="fa-solid fa-person-cane text-3xl md:text-4xl text-medical-600"></i>
                            </div>
                            <div class="text-[10px] text-slate-400 font-medium mb-0.5">Chăm sóc sức khỏe</div>
                            <h3 class="product-title-full text-xs md:text-sm font-bold text-slate-800 mb-1">
                                Vớ Y Khoa Giãn Tĩnh Mạch, Đai Lưng Cột Sống, Đèn Hồng Ngoại & Máy Trợ Thính
                            </h3>
                            <p class="text-[11px] text-slate-500">Thiết bị hỗ trợ điều trị xương khớp, suy giãn tĩnh mạch và chiếu đèn trị liệu.</p>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-slate-100 flex items-center justify-between">
                            <span class="text-[11px] font-bold text-medical-600">0932.552.313</span>
                            <a href="#form-bao-gia" onclick="prefillService('Vớ Y Khoa, Đai Lưng Cột Sống, Đèn Hồng Ngoại')" class="text-[11px] font-medium text-medical-700 hover:underline">Đặt mua</a>
                        </div>
                    </div>

                    <!-- SP 4 -->
                    <div class="product-card bg-white rounded-xl border border-slate-200 p-2.5 md:p-3.5 flex flex-col justify-between" data-category="y-te-chuyen-dung">
                        <div>
                            <div class="w-full h-28 md:h-36 rounded-lg bg-sky-50/70 flex items-center justify-center mb-2.5 border border-sky-100">
                                <i class="fa-solid fa-kit-medical text-3xl md:text-4xl text-medical-600"></i>
                            </div>
                            <div class="text-[10px] text-slate-400 font-medium mb-0.5">Y tế chuyên dùng</div>
                            <h3 class="product-title-full text-xs md:text-sm font-bold text-slate-800 mb-1">
                                Băng Ca Xe Cứu Thương, Bóp Bóng Ambu, Nồi Hấp Tiệt Trùng & Ống Nghe Y Khoa
                            </h3>
                            <p class="text-[11px] text-slate-500">Trang thiết bị y tế chuyên dùng cho phòng khám, xe cấp cứu và cơ sở y tế.</p>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-slate-100 flex items-center justify-between">
                            <span class="text-[11px] font-bold text-medical-600">0932.552.313</span>
                            <a href="#form-bao-gia" onclick="prefillService('Băng Ca Cứu Thương, Bóp Bóng Ambu, Ống Nghe')" class="text-[11px] font-medium text-medical-700 hover:underline">Đặt mua</a>
                        </div>
                    </div>

                    <!-- SP 5 -->
                    <div class="product-card bg-white rounded-xl border border-slate-200 p-2.5 md:p-3.5 flex flex-col justify-between" data-category="cham-soc-suc-khoe">
                        <div>
                            <div class="w-full h-28 md:h-36 rounded-lg bg-sky-50/70 flex items-center justify-center mb-2.5 border border-sky-100">
                                <i class="fa-solid fa-hand-holding-medical text-3xl md:text-4xl text-medical-600"></i>
                            </div>
                            <div class="text-[10px] text-slate-400 font-medium mb-0.5">Chăm sóc sức khỏe</div>
                            <h3 class="product-title-full text-xs md:text-sm font-bold text-slate-800 mb-1">
                                Máy Massage Trị Liệu Cổ Vai Gáy, Máy Tăm Nước, Thiết Bị Trị Ngáy & Chăn Đệm Điện
                            </h3>
                            <p class="text-[11px] text-slate-500">Chăm sóc giấc ngủ, vệ sinh răng miệng chuyên sâu và thư giãn cơ khớp tại nhà.</p>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-slate-100 flex items-center justify-between">
                            <span class="text-[11px] font-bold text-medical-600">0932.552.313</span>
                            <a href="#form-bao-gia" onclick="prefillService('Máy Massage Trị Liệu & Máy Tăm Nước')" class="text-[11px] font-medium text-medical-700 hover:underline">Đặt mua</a>
                        </div>
                    </div>

                    <!-- SP 6 -->
                    <div class="product-card bg-white rounded-xl border border-slate-200 p-2.5 md:p-3.5 flex flex-col justify-between" data-category="cham-soc-sac-dep">
                        <div>
                            <div class="w-full h-28 md:h-36 rounded-lg bg-sky-50/70 flex items-center justify-center mb-2.5 border border-sky-100">
                                <i class="fa-solid fa-spa text-3xl md:text-4xl text-medical-600"></i>
                            </div>
                            <div class="text-[10px] text-slate-400 font-medium mb-0.5">Chăm sóc sắc đẹp</div>
                            <h3 class="product-title-full text-xs md:text-sm font-bold text-slate-800 mb-1">
                                Máy Ánh Sáng Sinh Học Chăm Sóc Da Mặt, Máy Massage Mắt, Đai Quấn Nóng & Gen Định Hình
                            </h3>
                            <p class="text-[11px] text-slate-500">Thiết bị chăm sóc da công nghệ cao, hỗ trợ phục hồi vóc dáng sau sinh.</p>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-slate-100 flex items-center justify-between">
                            <span class="text-[11px] font-bold text-medical-600">0932.552.313</span>
                            <a href="#form-bao-gia" onclick="prefillService('Thiết Bị Chăm Sóc Da & Máy Massage Mắt')" class="text-[11px] font-medium text-medical-700 hover:underline">Đặt mua</a>
                        </div>
                    </div>

                    <!-- SP 7 -->
                    <div class="product-card bg-white rounded-xl border border-slate-200 p-2.5 md:p-3.5 flex flex-col justify-between" data-category="dich-vu-y-te">
                        <div>
                            <div class="w-full h-28 md:h-36 rounded-lg bg-sky-50/70 flex items-center justify-center mb-2.5 border border-sky-100">
                                <i class="fa-solid fa-syringe text-3xl md:text-4xl text-medical-600"></i>
                            </div>
                            <div class="text-[10px] text-slate-400 font-medium mb-0.5">Dịch vụ Y tế tại nhà</div>
                            <h3 class="product-title-full text-xs md:text-sm font-bold text-slate-800 mb-1">
                                Dịch Vụ Tiêm Thuốc, Truyền Dịch, Thay Băng Cắt Chỉ, Chăm Sóc Vết Loét Tỳ Đè Tại Nhà
                            </h3>
                            <p class="text-[11px] text-slate-500">Thực hiện đúng y lệnh bác sĩ, quy trình vô khuẩn tuyệt đối ngay tại nhà bệnh nhân.</p>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-slate-100 flex items-center justify-between">
                            <span class="text-[11px] font-bold text-medical-600">0932.552.313</span>
                            <a href="#form-bao-gia" onclick="prefillService('Tiêm truyền, Thay băng, Rửa vết loét tại nhà')" class="text-[11px] font-medium text-medical-700 hover:underline">Đặt lịch</a>
                        </div>
                    </div>

                    <!-- SP 8 -->
                    <div class="product-card bg-white rounded-xl border border-slate-200 p-2.5 md:p-3.5 flex flex-col justify-between" data-category="dich-vu-y-te">
                        <div>
                            <div class="w-full h-28 md:h-36 rounded-lg bg-sky-50/70 flex items-center justify-center mb-2.5 border border-sky-100">
                                <i class="fa-solid fa-vial-circle-check text-3xl md:text-4xl text-medical-600"></i>
                            </div>
                            <div class="text-[10px] text-slate-400 font-medium mb-0.5">Dịch vụ Y tế tại nhà</div>
                            <h3 class="product-title-full text-xs md:text-sm font-bold text-slate-800 mb-1">
                                Đặt Sonde Tiểu, Đặt Sonde Dạ Dày Nuôi Ăn & Lấy Máu Xét Nghiệm Trả Kết Quả Tận Nhà
                            </h3>
                            <p class="text-[11px] text-slate-500">Hỗ trợ bệnh nhân tai biến, khó nuốt, người cao tuổi hạn chế đi lại tại Đà Nẵng.</p>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-slate-100 flex items-center justify-between">
                            <span class="text-[11px] font-bold text-medical-600">0932.552.313</span>
                            <a href="#form-bao-gia" onclick="prefillService('Đặt Sonde tiểu, Sonde dạ dày & Lấy máu tại nhà')" class="text-[11px] font-medium text-medical-700 hover:underline">Đặt lịch</a>
                        </div>
                    </div>

                </div>
            </div>

        </div>
    </section>

    <!-- ==========================================
         9. CÙNG BẠN CHĂM SÓC GIA ĐÌNH - BÌNH PHỤC NHANH HƠN VỚI THANH TÂM MEDICAL
            (THIẾT KẾ GIỐNG WEB MẪU HOMECARETUANHOANG.COM)
         ========================================== -->
    <section class="py-4">
        <div class="container-flatsome">
            <div class="bg-gradient-to-r from-medical-700 to-medical-600 rounded-xl p-4 md:p-6 text-white shadow-xs">
                <div class="text-center max-w-2xl mx-auto mb-5">
                    <h2 class="text-sm md:text-lg font-extrabold uppercase tracking-wide">
                        CÙNG BẠN CHĂM SÓC GIA ĐÌNH - BÌNH PHỤC NHANH HƠN VỚI THANH TÂM MEDICAL
                    </h2>
                    <p class="text-xs text-sky-100 mt-1">
                        Uy tín - Chu đáo - Vô trùng - Có mặt nhanh chóng tại Đà Nẵng & khu vực Miền Trung
                    </p>
                </div>

                <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-4">
                    <div class="bg-white/10 border border-white/20 rounded-xl p-3.5">
                        <div class="text-sky-200 font-bold text-xs mb-1">"Chu đáo, tận tình"</div>
                        <h3 class="font-bold text-xs md:text-sm mb-1">Chăm sóc tại nhà - bệnh viện</h3>
                        <p class="text-[11px] text-sky-100 leading-relaxed">
                            Đội ngũ y bác sĩ, điều dưỡng Thanh Tâm Medical đến tận nhà hoặc bệnh viện chăm sóc theo yêu cầu.
                        </p>
                    </div>
                    <div class="bg-white/10 border border-white/20 rounded-xl p-3.5">
                        <div class="text-sky-200 font-bold text-xs mb-1">"An toàn, chính xác"</div>
                        <h3 class="font-bold text-xs md:text-sm mb-1">Trang thiết bị y tế hiện đại</h3>
                        <p class="text-[11px] text-sky-100 leading-relaxed">
                            Máy thở, máy tạo oxy, bình oxy, monitor và vật tư tiêu hao được kiểm định, khử khuẩn nghiêm ngặt.
                        </p>
                    </div>
                    <div class="bg-white/10 border border-white/20 rounded-xl p-3.5">
                        <div class="text-sky-200 font-bold text-xs mb-1">"Hiệu quả, tin cậy"</div>
                        <h3 class="font-bold text-xs md:text-sm mb-1">Nhân sự giàu y đức & kinh nghiệm</h3>
                        <p class="text-[11px] text-sky-100 leading-relaxed">
                            Tuyển chọn từ các bệnh viện lớn tại Đà Nẵng, đào tạo bài bản quy trình cấp cứu và điều dưỡng.
                        </p>
                    </div>
                    <div class="bg-white/10 border border-white/20 rounded-xl p-3.5">
                        <div class="text-sky-200 font-bold text-xs mb-1">"Thuận tiện, chủ động"</div>
                        <h3 class="font-bold text-xs md:text-sm mb-1">Luôn sẵn sàng 24/7</h3>
                        <p class="text-[11px] text-sky-100 leading-relaxed">
                            Hỗ trợ giao bình oxy, lắp đặt máy thở và điều xe cấp cứu chuyển viện bất kể ngày đêm.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         10. FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ
         ========================================== -->
    <section id="form-bao-gia" class="py-4">
        <div class="container-flatsome">
            <div class="bg-white rounded-xl border border-slate-200 p-4 md:p-6 shadow-xs">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-center">
                    
                    <!-- Cột thông tin hướng dẫn đặt lịch -->
                    <div class="lg:col-span-5 space-y-3">
                        <div class="inline-flex items-center gap-1.5 text-xs font-bold text-medical-600 uppercase">
                            <i class="fa-solid fa-headset"></i>
                            <span>Hỗ trợ nhanh 24/7 tại Đà Nẵng</span>
                        </div>
                        <h2 class="text-base md:text-xl font-extrabold text-slate-800 leading-snug">
                            ĐĂNG KÝ YÊU CẦU DỊCH VỤ & NHẬN BÁO GIÁ THIẾT BỊ Y TẾ
                        </h2>
                        <p class="text-xs text-slate-600 leading-relaxed">
                            Quý khách cần thuê bình oxy, máy tạo oxy, máy thở, giường bệnh nhân, gọi xe cấp cứu chuyển viện hoặc đặt lịch điều dưỡng chăm sóc tại nhà xin vui lòng điền thông tin bên cạnh.
                        </p>
                        <div class="bg-sky-50 border border-sky-100 rounded-xl p-3.5 space-y-2 text-xs">
                            <div class="flex items-center gap-2.5 text-slate-700">
                                <i class="fa-solid fa-location-dot text-medical-600 w-4 text-center"></i>
                                <span><strong>Địa chỉ:</strong> 64 Trần Cao Vân, Phường Thanh Khê, Tp.Đà Nẵng</span>
                            </div>
                            <div class="flex items-center gap-2.5 text-slate-700">
                                <i class="fa-solid fa-phone-volume text-medical-600 w-4 text-center"></i>
                                <span><strong>Hotline 24/7:</strong> <a href="tel:0932552313" class="text-medical-700 font-bold">0932.552.313</a></span>
                            </div>
                            <div class="flex items-center gap-2.5 text-slate-700">
                                <i class="fa-solid fa-globe text-medical-600 w-4 text-center"></i>
                                <span><strong>Website:</strong> thanhtammedical.com</span>
                            </div>
                        </div>
                    </div>

                    <!-- Cột Form Báo Giá -->
                    <div class="lg:col-span-7">
                        <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="bg-slate-50 p-4 md:p-5 rounded-xl border border-slate-200 space-y-3">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <div>
                                    <label class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên quý khách *</label>
                                    <input id="qName" type="text" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 text-xs bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-medical-600">
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại liên hệ *</label>
                                    <input id="qPhone" type="tel" required placeholder="Ví dụ: 0932552313" class="w-full px-3 py-2 text-xs bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-medical-600">
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <div>
                                    <label class="block text-xs font-semibold text-slate-700 mb-1">Dịch vụ / Thiết bị cần báo giá *</label>
                                    <select id="qService" class="w-full px-3 py-2 text-xs bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-medical-600">
                                        <option value="Mua bán / Cho thuê bình oxy, máy tạo oxy">Thuê / Mua Bình Oxy, Máy Tạo Oxy</option>
                                        <option value="Thuê máy thở, máy trợ thở tại nhà">Thuê Máy Thở, Máy Trợ Thở CPAP/BiPAP</option>
                                        <option value="Dịch vụ Xe cấp cứu vận chuyển bệnh nhân">Gọi Xe Cấp Cứu Vận Chuyển Bệnh Nhân 24/7</option>
                                        <option value="Điều dưỡng chăm sóc, tiêm truyền, thay băng tại nhà">Điều Dưỡng Chăm Sóc, Tiêm Truyền, Thay Băng</option>
                                        <option value="Giường Bệnh Nhân Y Tế Đa Năng">Thuê / Mua Giường Bệnh Nhân Y Tế</option>
                                        <option value="Đặt Sonde tiểu, Sonde dạ dày & Lấy máu tại nhà">Đặt Sonde Tiểu, Dạ Dày / Lấy Máu Tại Nhà</option>
                                        <option value="Thiết bị y tế gia đình & chuyên dùng khác">Thiết Bị Y Tế Gia Đình & Chuyên Dùng Khác</option>
                                    </select>
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold text-slate-700 mb-1">Địa chỉ nhận dịch vụ / giao thiết bị</label>
                                    <input id="qAddress" type="text" placeholder="Số nhà, đường, quận/huyện tại Đà Nẵng..." class="w-full px-3 py-2 text-xs bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-medical-600">
                                </div>
                            </div>

                            <div>
                                <label class="block text-xs font-semibold text-slate-700 mb-1">Ghi chú tình trạng hoặc yêu cầu chi tiết</label>
                                <textarea id="qNote" rows="2" placeholder="Nhập nhu cầu cụ thể (thuê theo ngày/tháng, tình trạng bệnh nhân...)" class="w-full px-3 py-2 text-xs bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-medical-600"></textarea>
                            </div>

                            <div class="flex flex-wrap items-center justify-between gap-2 pt-1">
                                <span class="text-[11px] text-slate-500"><i class="fa-solid fa-lock mr-1 text-medical-600"></i>Phản hồi báo giá ngay trong 3 - 5 phút</span>
                                <button type="submit" class="px-5 py-2 bg-medical-600 hover:bg-medical-700 text-white font-bold text-xs rounded-lg shadow-xs transition">
                                    <i class="fa-solid fa-paper-plane mr-1.5"></i>GỬI YÊU CẦU & NHẬN BÁO GIÁ
                                </button>
                            </div>

                            <!-- Hộp thông báo kết quả gửi form (Không dùng alert) -->
                            <div id="quoteSuccessMsg" class="hidden p-3 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs font-medium"></div>
                        </form>
                    </div>

                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         11. DANH MỤC CÁC BÀI VIẾT Y TẾ TRANG CHỦ (TIN TỨC & CẨM NANG)
         ========================================== -->
    <section id="tin-tuc-y-te" class="py-4">
        <div class="container-flatsome">
            <div class="flatsome-section-title">
                <h2 class="text-sm md:text-base">DANH MỤC BÀI VIẾT & CẨM NANG Y TẾ TẠI NHÀ</h2>
                <span class="text-xs text-slate-500 hidden sm:inline">Kiến thức chăm sóc sức khỏe từ Thanh Tâm Medical</span>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-3 md:gap-4">
                
                <!-- Bài viết 1 -->
                <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs flex flex-col justify-between">
                    <div>
                        <div class="h-36 bg-slate-100 overflow-hidden border-b border-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1BQTBJdgaO-7RQSs5l_zyX1pt-zaLLvtt=w500" alt="Hướng dẫn thuê bình oxy tại Đà Nẵng" class="w-full h-full object-cover" onerror="handleDriveImageError(this, 'IMG1')">
                        </div>
                        <div class="p-3">
                            <span class="text-[10.5px] font-semibold text-medical-600">Dịch vụ Oxy Y tế 24/7</span>
                            <h3 class="product-title-full text-xs md:text-sm font-bold text-slate-800 mt-1 mb-1.5">
                                Kinh Nghiệm Thuê Bình Oxy Y Tế & Máy Tạo Oxy Tại Nhà Ở Đà Nẵng An Toàn, Đúng Lưu Lượng
                            </h3>
                            <p class="text-[11px] text-slate-500 leading-relaxed">
                                Hướng dẫn cách điều chỉnh lưu lượng oxy phù hợp và quy trình kiểm tra bình làm ẩm cho bệnh nhân hô hấp tại nhà.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 pt-1 text-[11px] text-medical-600 font-semibold">
                        <a href="#form-bao-gia" class="hover:underline">Tư vấn miễn phí <i class="fa-solid fa-angle-right ml-0.5"></i></a>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs flex flex-col justify-between">
                    <div>
                        <div class="h-36 bg-slate-100 overflow-hidden border-b border-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1frQ_RtB3ptD-C6wzQIhkDLXyQO2QVX7i=w500" alt="Cho thuê máy thở chuyên nghiệp tại nhà" class="w-full h-full object-cover" onerror="handleDriveImageError(this, 'IMG3')">
                        </div>
                        <div class="p-3">
                            <span class="text-[10.5px] font-semibold text-medical-600">Hỗ trợ Hô hấp</span>
                            <h3 class="product-title-full text-xs md:text-sm font-bold text-slate-800 mt-1 mb-1.5">
                                Khi Nào Cần Thuê Máy Thở, Máy Trợ Thở CPAP / BiPAP Chuyên Nghiệp Tại Nhà?
                            </h3>
                            <p class="text-[11px] text-slate-500 leading-relaxed">
                                Giải pháp hỗ trợ thở tại gia đình cho bệnh nhân COPD, ngưng thở khi ngủ và bệnh nhân xuất viện cần duy trì máy thở.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 pt-1 text-[11px] text-medical-600 font-semibold">
                        <a href="#form-bao-gia" class="hover:underline">Tư vấn miễn phí <i class="fa-solid fa-angle-right ml-0.5"></i></a>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs flex flex-col justify-between">
                    <div>
                        <div class="h-36 bg-slate-100 overflow-hidden border-b border-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1biAq6JpYplG47CmnhQA3c7UdqbdXtMyN=w500" alt="Chăm sóc người bệnh liệt giường và vết loét tỳ đè" class="w-full h-full object-cover" onerror="handleDriveImageError(this, 'IMG4')">
                        </div>
                        <div class="p-3">
                            <span class="text-[10.5px] font-semibold text-medical-600">Điều dưỡng tại nhà</span>
                            <h3 class="product-title-full text-xs md:text-sm font-bold text-slate-800 mt-1 mb-1.5">
                                Quy Trình Thay Băng, Rửa Vết Thương & Chăm Sóc Vết Loét Tỳ Đè Tại Nhà Chuẩn Y Khoa
                            </h3>
                            <p class="text-[11px] text-slate-500 leading-relaxed">
                                Kết hợp sử dụng giường bệnh nhân đa năng, đệm chống loét và điều dưỡng chăm sóc vết thương vô khuẩn hàng ngày.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 pt-1 text-[11px] text-medical-600 font-semibold">
                        <a href="#form-bao-gia" class="hover:underline">Tư vấn miễn phí <i class="fa-solid fa-angle-right ml-0.5"></i></a>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs flex flex-col justify-between">
                    <div>
                        <div class="h-36 bg-slate-100 overflow-hidden border-b border-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1uhHDEkEdgk3ItTXJ0qRAPMP_t7V76mk5=w500" alt="Dịch vụ xe cứu thương chuyển viện Đà Nẵng" class="w-full h-full object-cover" onerror="handleDriveImageError(this, 'IMG6')">
                        </div>
                        <div class="p-3">
                            <span class="text-[10.5px] font-semibold text-medical-600">Xe cấp cứu 24/7</span>
                            <h3 class="product-title-full text-xs md:text-sm font-bold text-slate-800 mt-1 mb-1.5">
                                Dịch Vụ Gọi Xe Cứu Thương Chuyển Viện Từ Đà Nẵng Đi Các Tỉnh Có Y Tá & Máy Thở Đi Kèm
                            </h3>
                            <p class="text-[11px] text-slate-500 leading-relaxed">
                                Đảm bảo an toàn tối đa trên suốt hành trình chuyển viện Bắc - Nam với trang thiết bị cấp cứu đồng bộ.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 pt-1 text-[11px] text-medical-600 font-semibold">
                        <a href="#form-bao-gia" class="hover:underline">Tư vấn miễn phí <i class="fa-solid fa-angle-right ml-0.5"></i></a>
                    </div>
                </article>

            </div>
        </div>
    </section>

    <!-- ==========================================
         12. DANH MỤC CÁC ĐỐI TÁC Y TẾ UY TÍN
         ========================================== -->
    <section class="py-4">
        <div class="container-flatsome">
            <div class="flatsome-section-title">
                <h2 class="text-sm md:text-base">ĐỐI TÁC THIẾT BỊ & ĐƠN VỊ Y TẾ ĐỒNG HÀNH</h2>
                <span class="text-xs text-slate-500 hidden sm:inline">Thương hiệu y khoa chính hãng hàng đầu</span>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2.5 md:gap-3">
                <div class="bg-white border border-slate-200 rounded-xl p-3 text-center shadow-2xs flex flex-col items-center justify-center">
                    <span class="font-extrabold text-sm text-medical-700 tracking-wide">OMRON</span>
                    <span class="text-[10.5px] text-slate-500 mt-0.5">Y tế Gia đình Nhật Bản</span>
                </div>
                <div class="bg-white border border-slate-200 rounded-xl p-3 text-center shadow-2xs flex flex-col items-center justify-center">
                    <span class="font-extrabold text-sm text-medical-700 tracking-wide">YUWELL</span>
                    <span class="text-[10.5px] text-slate-500 mt-0.5">Máy tạo Oxy & Hút dịch</span>
                </div>
                <div class="bg-white border border-slate-200 rounded-xl p-3 text-center shadow-2xs flex flex-col items-center justify-center">
                    <span class="font-extrabold text-sm text-medical-700 tracking-wide">PHILIPS RESPIRONICS</span>
                    <span class="text-[10.5px] text-slate-500 mt-0.5">Máy thở & Trợ thở</span>
                </div>
                <div class="bg-white border border-slate-200 rounded-xl p-3 text-center shadow-2xs flex flex-col items-center justify-center">
                    <span class="font-extrabold text-sm text-medical-700 tracking-wide">MICROLIFE</span>
                    <span class="text-[10.5px] text-slate-500 mt-0.5">Thiết bị Đo lường Y khoa</span>
                </div>
                <div class="bg-white border border-slate-200 rounded-xl p-3 text-center shadow-2xs flex flex-col items-center justify-center">
                    <span class="font-extrabold text-sm text-medical-700 tracking-wide">PARAMOUNT BED</span>
                    <span class="text-[10.5px] text-slate-500 mt-0.5">Giường bệnh nhân cao cấp</span>
                </div>
                <div class="bg-white border border-slate-200 rounded-xl p-3 text-center shadow-2xs flex flex-col items-center justify-center">
                    <span class="font-extrabold text-sm text-medical-700 tracking-wide">BEURER GERMANY</span>
                    <span class="text-[10.5px] text-slate-500 mt-0.5">Chăm sóc sức khỏe Đức</span>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         13. ĐƯA FANPAGE VÀ BẢN ĐỒ GOOGLE MAP RA NGOÀI TRANG CHỦ
             - ĐỊA CHỈ: 64 TRẦN CAO VÂN, PHƯỜNG THANH KHÊ, TP.ĐÀ NẴNG
             - FANPAGE: https://www.facebook.com/dichvuytetainhataidanang
         ========================================== -->
    <section id="doi-tac-lien-he" class="py-4">
        <div class="container-flatsome">
            <div class="flatsome-section-title">
                <h2 class="text-sm md:text-base">BẢN ĐỒ GOOGLE MAP & FANPAGE THANH TÂM MEDICAL</h2>
                <span class="text-xs text-slate-500 hidden sm:inline">64 Trần Cao Vân, Phường Thanh Khê, Tp.Đà Nẵng</span>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-2 gap-4">
                
                <!-- Khung Bản Đồ Google Map ngoài trang chủ -->
                <div class="bg-white rounded-xl border border-slate-200 p-3.5 shadow-xs flex flex-col justify-between">
                    <div class="mb-2.5 flex items-center justify-between gap-2">
                        <div>
                            <h3 class="text-xs md:text-sm font-bold text-slate-800">
                                <i class="fa-solid fa-map-location-dot text-medical-600 mr-1.5"></i>Vị Trí Google Map Thanh Tâm Medical
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-0.5">
                                Địa chỉ: 64 Trần Cao Vân, Phường Thanh Khê, Tp.Đà Nẵng
                            </p>
                        </div>
                        <a 
                            href="https://www.google.com/maps/search/?api=1&query=64+Tr%E1%BA%A7n+Cao+V%C3%A2n,+Thanh+Kh%C3%AA,+%C4%90%C3%A0+N%E1%BA%B5ng" 
                            target="_blank" 
                            rel="noopener noreferrer"
                            class="text-[11px] font-semibold text-medical-600 bg-sky-50 hover:bg-sky-100 px-2.5 py-1.5 rounded-lg shrink-0"
                        >
                            <i class="fa-solid fa-diamond-turn-right mr-1"></i>Chỉ đường
                        </a>
                    </div>
                    <div class="w-full h-64 rounded-lg overflow-hidden border border-slate-200 bg-slate-100">
                        <iframe 
                            title="Bản đồ 64 Trần Cao Vân, Phường Thanh Khê, Tp.Đà Nẵng"
                            src="https://maps.google.com/maps?q=64%20Tr%E1%BA%A7n%20Cao%20V%C3%A2n,%20Thanh%20Kh%C3%AA,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed" 
                            width="100%" 
                            height="100%" 
                            style="border:0;" 
                            allowfullscreen="" 
                            loading="lazy" 
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>
                </div>

                <!-- Khung Fanpage Facebook ngoài trang chủ -->
                <div class="bg-white rounded-xl border border-slate-200 p-3.5 shadow-xs flex flex-col justify-between">
                    <div class="mb-2.5 flex items-center justify-between gap-2">
                        <div>
                            <h3 class="text-xs md:text-sm font-bold text-slate-800">
                                <i class="fa-brands fa-facebook text-blue-600 mr-1.5"></i>Fanpage Dịch Vụ Y Tế Tại Nhà Tại Đà Nẵng
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-0.5">
                                Kết nối trực tiếp qua Fanpage chính thức của Thanh Tâm Medical
                            </p>
                        </div>
                        <a 
                            href="https://www.facebook.com/dichvuytetainhataidanang" 
                            target="_blank" 
                            rel="noopener noreferrer"
                            class="text-[11px] font-semibold text-white bg-blue-600 hover:bg-blue-700 px-2.5 py-1.5 rounded-lg shrink-0"
                        >
                            <i class="fa-brands fa-facebook-messenger mr-1"></i>Mở Fanpage
                        </a>
                    </div>

                    <!-- Khung hiển thị trực quan Fanpage + Nhúng Plugin Facebook -->
                    <div class="rounded-lg border border-slate-200 bg-slate-50 p-3 flex flex-col justify-between gap-3">
                        <div class="flex items-center gap-3">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1WHFD2AqrulRIbWAiX3zw90FEpWxVS6Y9=w200" 
                                alt="Logo Fanpage Thanh Tâm Medical" 
                                class="w-12 h-12 rounded-lg bg-white border border-slate-200 p-0.5 object-contain shrink-0"
                                onerror="handleDriveImageError(this, 'LOGO')"
                            >
                            <div class="min-w-0">
                                <a href="https://www.facebook.com/dichvuytetainhataidanang" target="_blank" rel="noopener noreferrer" class="font-bold text-xs md:text-sm text-blue-700 hover:underline block truncate">
                                    Dịch Vụ Y Tế Tại Nhà Tại Đà Nẵng - Thanh Tâm Medical
                                </a>
                                <p class="text-[11px] text-slate-600">facebook.com/dichvuytetainhataidanang</p>
                                <p class="text-[11px] text-emerald-700 font-medium mt-0.5">
                                    <i class="fa-solid fa-circle-check mr-1"></i>Trực tuyến 24/7 • Hotline: 0932.552.313
                                </p>
                            </div>
                        </div>

                        <div class="w-full overflow-hidden rounded-lg bg-white border border-slate-200 flex justify-center">
                            <iframe 
                                title="Fanpage Dịch Vụ Y Tế Tại Nhà Tại Đà Nẵng"
                                src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fdichvuytetainhataidanang&tabs=&width=500&height=130&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true" 
                                width="500" 
                                height="130" 
                                style="border:none;overflow:hidden;max-width:100%;" 
                                scrolling="no" 
                                frameborder="0" 
                                allowfullscreen="true" 
                                allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                            </iframe>
                        </div>

                        <div class="flex flex-wrap items-center justify-between gap-2 text-[11px] text-slate-600 pt-1">
                            <span><i class="fa-solid fa-location-dot mr-1 text-medical-600"></i>64 Trần Cao Vân, Phường Thanh Khê, Tp.Đà Nẵng</span>
                            <a href="https://www.facebook.com/dichvuytetainhataidanang" target="_blank" rel="noopener noreferrer" class="font-semibold text-blue-600 hover:underline">
                                Nhắn tin tư vấn qua Facebook →
                            </a>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         14. FOOTER CHÂN TRANG (CHUẨN CẤU TRÚC FLATSOME)
         ========================================== -->
    <footer class="bg-slate-900 text-slate-300 pt-8 pb-20 md:pb-8 mt-6 border-t border-slate-800">
        <div class="container-flatsome">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 pb-6 border-b border-slate-800 text-xs">
                
                <!-- Cột 1: Thông tin Thanh Tâm Medical -->
                <div class="space-y-2.5">
                    <div class="flex items-center gap-2.5">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1WHFD2AqrulRIbWAiX3zw90FEpWxVS6Y9=w160" 
                            alt="Logo Thanh Tâm Medical" 
                            class="w-9 h-9 rounded-lg bg-white p-0.5 object-contain shrink-0"
                            onerror="handleDriveImageError(this, 'LOGO')"
                        >
                        <div>
                            <div class="font-extrabold text-white text-sm">THANH TÂM MEDICAL</div>
                            <div class="text-[11px] text-sky-400">thanhtammedical.com</div>
                        </div>
                    </div>
                    <p class="text-slate-400 leading-relaxed text-[11.5px]">
                        Hệ sinh thái dịch vụ y tế tại nhà, bác sĩ gia đình, điều dưỡng chăm sóc bệnh nhân, cho thuê bình oxy, máy tạo oxy, máy thở, giường y tế và vận chuyển cấp cứu 24/7 tại Đà Nẵng.
                    </p>
                </div>

                <!-- Cột 2: Thông tin liên hệ -->
                <div class="space-y-2">
                    <h4 class="font-bold text-white uppercase tracking-wider text-xs">THÔNG TIN LIÊN HỆ</h4>
                    <ul class="space-y-1.5 text-[11.5px] text-slate-300">
                        <li><i class="fa-solid fa-location-dot mr-2 text-sky-400"></i>Địa chỉ: 64 Trần Cao Vân, Phường Thanh Khê, Tp.Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone mr-2 text-sky-400"></i>Số điện thoại / Zalo: <a href="tel:0932552313" class="text-white font-bold">0932.552.313</a></li>
                        <li><i class="fa-solid fa-globe mr-2 text-sky-400"></i>Website: thanhtammedical.com</li>
                        <li><i class="fa-brands fa-facebook mr-2 text-sky-400"></i>Fanpage: <a href="https://www.facebook.com/dichvuytetainhataidanang" target="_blank" rel="noopener noreferrer" class="underline hover:text-white">fb.com/dichvuytetainhataidanang</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Dịch vụ y tế tại nhà -->
                <div class="space-y-2">
                    <h4 class="font-bold text-white uppercase tracking-wider text-xs">DỊCH VỤ Y TẾ TẠI NHÀ</h4>
                    <ul class="space-y-1.5 text-[11.5px] text-slate-400">
                        <li>• Dịch vụ xe cứu thương chuyển viện 24/7</li>
                        <li>• Mua bán, cho thuê bình oxy & máy tạo oxy</li>
                        <li>• Cho thuê máy thở, máy trợ thở tại nhà</li>
                        <li>• Điều dưỡng chăm sóc người bệnh 24/24</li>
                        <li>• Tiêm thuốc, truyền dịch, thay băng cắt chỉ</li>
                        <li>• Đặt Sonde tiểu, Sonde dạ dày, lấy máu xét nghiệm</li>
                    </ul>
                </div>

                <!-- Cột 4: Danh mục thiết bị y tế -->
                <div class="space-y-2">
                    <h4 class="font-bold text-white uppercase tracking-wider text-xs">DANH MỤC SẢN PHẨM</h4>
                    <ul class="space-y-1.5 text-[11.5px] text-slate-400">
                        <li>• Giường bệnh nhân cao cấp tay quay & điện</li>
                        <li>• Máy đo huyết áp, đường huyết, nhiệt kế</li>
                        <li>• Máy hút dịch đờm, máy xông mũi họng</li>
                        <li>• Máy đo nồng độ oxy SpO2, Monitor y tế</li>
                        <li>• Xe lăn đa năng, đệm hơi chống loét</li>
                        <li>• Vớ y khoa, đai lưng cột sống, đèn hồng ngoại</li>
                    </ul>
                </div>

            </div>

            <div class="pt-4 flex flex-col sm:flex-row items-center justify-between gap-2 text-[11px] text-slate-400">
                <div>© Bản quyền thuộc về <strong>Thanh Tâm Medical (thanhtammedical.com)</strong> - 64 Trần Cao Vân, Phường Thanh Khê, Tp.Đà Nẵng.</div>
                <div>Hotline trực cấp cứu & oxy y tế 24/7: <strong class="text-white">0932.552.313</strong></div>
            </div>
        </div>
    </footer>

    <!-- ==========================================
         15. NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
             TƯƠNG THÍCH TRÊN CẢ MÁY TÍNH VÀ ĐIỆN THOẠI, KHÔNG TRÀN VIỀN
         ========================================== -->
    <div class="fixed right-3 bottom-4 z-50 flex flex-col items-end gap-2.5">
        
        <!-- Nút Zalo nổi bật -->
        <a 
            href="https://zalo.me/0932552313" 
            target="_blank" 
            rel="noopener noreferrer"
            aria-label="Chat Zalo 0932.552.313"
            class="contact-float-btn flex items-center gap-2 bg-sky-500 hover:bg-sky-600 text-white px-3 py-2 rounded-full shadow-lg border border-white/30 transition transform hover:-translate-y-0.5"
        >
            <span class="w-6 h-6 rounded-full bg-white text-sky-600 font-extrabold text-[11px] flex items-center justify-center shrink-0">Zalo</span>
            <span class="text-xs font-bold pr-1 hidden sm:inline">Chat Zalo</span>
        </a>

        <!-- Nút Facebook Fanpage nổi bật -->
        <a 
            href="https://www.facebook.com/dichvuytetainhataidanang" 
            target="_blank" 
            rel="noopener noreferrer"
            aria-label="Fanpage Thanh Tâm Medical"
            class="contact-float-btn flex items-center gap-2 bg-blue-600 hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg border border-white/30 transition transform hover:-translate-y-0.5"
        >
            <span class="w-6 h-6 rounded-full bg-white text-blue-600 flex items-center justify-center shrink-0">
                <i class="fa-brands fa-facebook-f text-xs"></i>
            </span>
            <span class="text-xs font-bold pr-1 hidden sm:inline">Fanpage</span>
        </a>

        <!-- Nút Hotline nổi bật -->
        <a 
            href="tel:0932552313" 
            aria-label="Gọi Hotline 0932.552.313"
            class="contact-float-btn flex items-center gap-2 bg-rose-600 hover:bg-rose-700 text-white px-3.5 py-2 rounded-full shadow-lg border border-white/30 transition transform hover:-translate-y-0.5"
        >
            <span class="w-6 h-6 rounded-full bg-white text-rose-600 flex items-center justify-center shrink-0">
                <i class="fa-solid fa-phone-volume text-xs"></i>
            </span>
            <span class="text-xs font-extrabold pr-0.5">0932.552.313</span>
        </a>

    </div>

    <!-- ==========================================
         JAVASCRIPT XỬ LÝ SLIDER TỰ TRƯỢT, LỌC DANH MỤC, FORM BÁO GIÁ & FALLBACK ẢNH DRIVE
         ========================================== -->
    <script>
        // 1. Tự động chuyển 2 Banner mỗi 4.5 giây
        let currentBannerSlide = 0;
        const totalBannerSlides = 2;

        function goToSlide(index) {
            currentBannerSlide = index;
            const slides = document.querySelectorAll('.banner-slide');
            slides.forEach((slide, i) => {
                if (i === index) {
                    slide.classList.remove('hidden');
                    slide.classList.add('block');
                } else {
                    slide.classList.remove('block');
                    slide.classList.add('hidden');
                }
            });

            const dot0 = document.getElementById('dotSlide0');
            const dot1 = document.getElementById('dotSlide1');
            if (dot0 && dot1) {
                if (index === 0) {
                    dot0.className = 'w-6 h-2 rounded-full bg-white transition-all';
                    dot1.className = 'w-2.5 h-2 rounded-full bg-white/50 transition-all';
                } else {
                    dot0.className = 'w-2.5 h-2 rounded-full bg-white/50 transition-all';
                    dot1.className = 'w-6 h-2 rounded-full bg-white transition-all';
                }
            }
        }

        setInterval(() => {
            const next = (currentBannerSlide + 1) % totalBannerSlides;
            goToSlide(next);
        }, 4500);

        // 2. Đóng / Mở Menu trên điện thoại
        const mobileMenuBtn = document.getElementById('mobileMenuBtn');
        const closeMobileDrawer = document.getElementById('closeMobileDrawer');
        const mobileDrawerBackdrop = document.getElementById('mobileDrawerBackdrop');
        const mobileDrawer = document.getElementById('mobileDrawer');

        function toggleMobileMenu(show) {
            if (!mobileDrawer) return;
            if (show) {
                mobileDrawer.classList.remove('hidden');
            } else {
                mobileDrawer.classList.add('hidden');
            }
        }

        if (mobileMenuBtn) mobileMenuBtn.addEventListener('click', () => toggleMobileMenu(true));
        if (closeMobileDrawer) closeMobileDrawer.addEventListener('click', () => toggleMobileMenu(false));
        if (mobileDrawerBackdrop) mobileDrawerBackdrop.addEventListener('click', () => toggleMobileMenu(false));

        // Mở ô tìm kiếm trên Mobile
        const mobileSearchToggle = document.getElementById('mobileSearchToggle');
        const mobileSearchBox = document.getElementById('mobileSearchBox');
        if (mobileSearchToggle && mobileSearchBox) {
            mobileSearchToggle.addEventListener('click', () => {
                mobileSearchBox.classList.toggle('hidden');
            });
        }

        // 3. Lọc sản phẩm theo Danh mục trên trang chủ
        function selectCategoryFilter(categoryKey) {
            const buttons = document.querySelectorAll('.cat-filter-btn');
            buttons.forEach(btn => {
                if (btn.getAttribute('data-cat-btn') === categoryKey) {
                    btn.className = 'cat-filter-btn home-cat-pill bg-medical-600 text-white font-semibold border border-medical-600';
                } else {
                    btn.className = 'cat-filter-btn home-cat-pill bg-slate-50 hover:bg-medical-50 text-slate-700 border border-slate-200 font-medium';
                }
            });

            const cards = document.querySelectorAll('.product-card');
            cards.forEach(card => {
                const cats = card.getAttribute('data-category') || '';
                if (categoryKey === 'all' || cats.includes(categoryKey)) {
                    card.classList.remove('hidden');
                    card.classList.add('flex');
                } else {
                    card.classList.remove('flex');
                    card.classList.add('hidden');
                }
            });
        }

        // 4. Tìm kiếm nhanh sản phẩm
        function filterProductsBySearch(inputId) {
            const input = document.getElementById(inputId);
            if (!input) return;
            const keyword = input.value.trim().toLowerCase();
            const cards = document.querySelectorAll('.product-card');
            cards.forEach(card => {
                const text = card.innerText.toLowerCase();
                if (!keyword || text.includes(keyword)) {
                    card.classList.remove('hidden');
                    card.classList.add('flex');
                } else {
                    card.classList.remove('flex');
                    card.classList.add('hidden');
                }
            });
            const prodSection = document.getElementById('danh-muc-thuc-te');
            if (prodSection && keyword) {
                prodSection.scrollIntoView({ behavior: 'smooth' });
            }
        }

        // 5. Điền sẵn tên dịch vụ vào Form Báo Giá khi bấm từ thẻ sản phẩm
        function prefillService(serviceName) {
            const select = document.getElementById('qService');
            const note = document.getElementById('qNote');
            if (note) {
                note.value = 'Yêu cầu tư vấn & báo giá: ' + serviceName;
            }
            if (select) {
                for (let i = 0; i < select.options.length; i++) {
                    if (select.options[i].value === serviceName) {
                        select.selectedIndex = i;
                        break;
                    }
                }
            }
        }

        // 6. Xử lý gửi Form Yêu Cầu & Báo Giá (Hiển thị thông báo trực tiếp, không dùng alert)
        function submitQuoteForm(event) {
            event.preventDefault();
            const name = document.getElementById('qName').value.trim();
            const phone = document.getElementById('qPhone').value.trim();
            const service = document.getElementById('qService').value;
            const address = document.getElementById('qAddress').value.trim();
            const msgBox = document.getElementById('quoteSuccessMsg');

            if (msgBox) {
                msgBox.classList.remove('hidden');
                msgBox.innerHTML = '<i class="fa-solid fa-circle-check mr-1.5 text-emerald-600"></i>' +
                    'Cảm ơn <strong>' + name + '</strong> (' + phone + ')! Yêu cầu báo giá <strong>"' + service + '"</strong> ' +
                    (address ? 'tại địa chỉ <strong>' + address + '</strong> ' : '') +
                    'đã được ghi nhận. Bộ phận trực 24/7 của <strong>Thanh Tâm Medical (0932.552.313)</strong> sẽ liên hệ lại ngay!';
            }
        }

        // 7. Cơ chế dự phòng đa tầng cho ảnh Google Drive (Thử link thumbnail Google Drive trước, sau đó mới dùng ảnh minh họa y khoa)
        function handleDriveImageError(imgElement, typeKey) {
            const driveId = imgElement.getAttribute('data-drive-id');
            const triedThumb = imgElement.getAttribute('data-tried-thumb');

            if (driveId && !triedThumb) {
                imgElement.setAttribute('data-tried-thumb', 'true');
                imgElement.src = 'https://drive.google.com/thumbnail?id=' + driveId + '&sz=w800';
                return;
            }

            const fallbacks = {
                'LOGO': 'https://placehold.co/200x200/0072bc/ffffff?text=THANH+TAM+MEDICAL',
                'IMG1': 'https://placehold.co/600x450/0072bc/ffffff?text=May+Tao+Oxy+Y+Te+5L-10L',
                'IMG2': 'https://placehold.co/600x450/035388/ffffff?text=Binh+Oxy+Y+Te+Tai+Nha',
                'IMG3': 'https://placehold.co/600x450/0d9488/ffffff?text=May+Tho+CPAP+BiPAP',
                'IMG4': 'https://placehold.co/600x450/0072bc/ffffff?text=Giuong+Benh+Nhan+Da+Nang',
                'IMG5': 'https://placehold.co/600x450/035388/ffffff?text=May+Hut+Dich+Xong+Khi+Dung',
                'IMG6': 'https://placehold.co/600x450/0d9488/ffffff?text=Monitor+SpO2+Y+Te+Tai+Nha'
            };
            imgElement.onerror = null;
            imgElement.src = fallbacks[typeKey] || fallbacks['IMG1'];
        }
    </script>
</body>
</html>
