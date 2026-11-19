<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CÔNG TY TNHH XÂY DỰNG THƯƠNG MẠI HẢI CƯỜNG THỊNH | haicuongthinh.com</title>
  <meta name="description" content="Công ty TNHH Xây Dựng Thương Mại Hải Cường Thịnh - Chuyên thiết kế kiến trúc, thi công xây dựng phần thô, hoàn thiện, nội thất trọn gói uy tín tại Đà Nẵng. Hotline: 0934.783.967." />

  <!-- Meta Open Graph / Thumbnail chia sẻ đường link sử dụng Logo công ty -->
  <meta property="og:type" content="website" />
  <meta property="og:site_name" content="Hải Cường Thịnh - haicuongthinh.com" />
  <meta property="og:url" content="https://haicuongthinh.com/" />
  <meta property="og:title" content="CÔNG TY TNHH XÂY DỰNG THƯƠNG MẠI HẢI CƯỜNG THỊNH" />
  <meta property="og:description" content="Thiết kế & Thi công xây dựng trọn gói chuyên nghiệp tại Đà Nẵng. Địa chỉ: 248 Dương Đình Nghệ, Phường An Hải, TP Đà Nẵng. Hotline: 0934.783.967." />
  <!-- Khi đưa lên WordPress/Flatsome, thay đường dẫn ảnh logo .png/.jpg đã tải lên thư viện Media -->
  <meta property="og:image" content="https://haicuongthinh.com/wp-content/uploads/logo-hai-cuong-thinh-thumbnail.png" />
  <meta property="og:image:width" content="1200" />
  <meta property="og:image:height" content="630" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="CÔNG TY TNHH XÂY DỰNG THƯƠNG MẠI HẢI CƯỜNG THỊNH" />
  <meta name="twitter:description" content="Thiết kế - Thi công xây dựng - Nội thất trọn gói uy tín tại Đà Nẵng." />
  <meta name="twitter:image" content="https://haicuongthinh.com/wp-content/uploads/logo-hai-cuong-thinh-thumbnail.png" />

  <!-- Favicon Logo SVG -->
  <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='12' fill='%230F2C59'/%3E%3Cpath d='M12 46V24L32 12L52 24V46H44V28.5L32 21.5L20 28.5V46H12Z' fill='%23D4952A'/%3E%3Crect x='26' y='30' width='12' height='16' fill='%23FFFFFF'/%3E%3C/svg%3E" />

  <!-- Font Inter chuẩn hiện đại & dễ đọc -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
          },
          colors: {
            brand: {
              navy: '#0F2C59',
              navyDark: '#0A1E3D',
              navyLight: '#1B427E',
              gold: '#C88A2E',
              goldLight: '#E0A84B',
              goldSoft: '#FDF7EC',
              slate: '#334155',
              surface: '#F6F8FB',
            }
          }
        }
      }
    }
  </script>

  <style>
    /* Thiết lập chuẩn chống tràn viền, chống lệch phải tuyệt đối */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      font-family: 'Inter', system-ui, -apple-system, sans-serif;
      color: #1E293B;
      background-color: #FFFFFF;
      scroll-behavior: smooth;
      -webkit-font-smoothing: antialiased;
    }

    /* Container chuẩn Flatsome: Chiều ngang máy tính đúng 95% màn hình, căn giữa hoàn hảo */
    .hct-container {
      width: 100%;
      max-width: 100%;
      padding-left: 14px;
      padding-right: 14px;
      margin-left: auto;
      margin-right: auto;
    }
    @media (min-width: 1024px) {
      .hct-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
        margin-left: auto;
        margin-right: auto;
      }
    }

    /* Menu dropdown Flatsome trên máy tính */
    .nav-item {
      position: relative;
    }
    .nav-dropdown {
      opacity: 0;
      visibility: hidden;
      transform: translateY(8px);
      transition: all 0.2s ease;
      position: absolute;
      top: 100%;
      left: 0;
      min-width: 230px;
      z-index: 60;
    }
    .nav-item:hover .nav-dropdown,
    .nav-item:focus-within .nav-dropdown {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }

    /* Hiệu ứng trượt mượt cho Banner Slider 2 ảnh bằng nhau */
    .banner-track {
      display: flex;
      width: 200%;
      transition: transform 0.65s cubic-bezier(0.25, 0.8, 0.25, 1);
    }
    .banner-slide {
      width: 50%;
      flex-shrink: 0;
      position: relative;
      overflow: hidden;
    }

    /* Gạch chân tiêu đề chuẩn Flatsome */
    .section-divider {
      width: 56px;
      height: 3px;
      background-color: #C88A2E;
      border-radius: 999px;
      margin: 10px auto 0;
    }
    .section-divider-left {
      width: 56px;
      height: 3px;
      background-color: #C88A2E;
      border-radius: 999px;
      margin: 10px 0 0;
    }

    /* Hiệu ứng sóng nhẹ cho nút Hotline nổi */
    @keyframes hctPulse {
      0% { box-shadow: 0 0 0 0 rgba(200, 138, 46, 0.55); }
      70% { box-shadow: 0 0 0 12px rgba(200, 138, 46, 0); }
      100% { box-shadow: 0 0 0 0 rgba(200, 138, 46, 0); }
    }
    .hotline-pulse {
      animation: hctPulse 2.2s infinite;
    }

    /* Ảnh thẻ sản phẩm / dự án mượt khi hover */
    .card-img-zoom {
      transition: transform 0.45s ease;
    }
    .group:hover .card-img-zoom {
      transform: scale(1.04);
    }
  </style>
</head>
<body class="bg-white text-slate-800 antialiased selection:bg-brand-gold selection:text-white">

  <!-- ==================== FLATSOME TOP BAR ==================== -->
  <div class="bg-brand-navyDark text-white/90 text-xs py-2 border-b border-white/10">
    <div class="hct-container flex items-center justify-between gap-2">
      <div class="flex items-center gap-3 sm:gap-5 flex-wrap">
        <a href="tel:0934783967" class="inline-flex items-center gap-1.5 hover:text-brand-goldLight transition-colors whitespace-nowrap">
          <svg class="w-3.5 h-3.5 text-brand-goldLight flex-shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
          <span class="font-semibold">0934.783.967</span>
        </a>
        <span class="hidden sm:inline text-white/30">|</span>
        <span class="hidden sm:inline-flex items-center gap-1.5 whitespace-nowrap">
          <svg class="w-3.5 h-3.5 text-brand-goldLight flex-shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/></svg>
          lienhe@haicuongthinh.com
        </span>
      </div>
      <div class="hidden md:flex items-center gap-1.5 text-white/85 whitespace-nowrap">
        <svg class="w-3.5 h-3.5 text-brand-goldLight flex-shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
        <span>248 Dương Đình Nghệ, Phường An Hải, TP Đà Nẵng</span>
      </div>
    </div>
  </div>

  <!-- ==================== FLATSOME MAIN HEADER ==================== -->
  <!-- Lưu ý: Logo thiết kế gọn nhỏ tinh tế, không có nút Gọi ngay trên Header để tránh tràn viền -->
  <header id="main-header" class="sticky top-0 z-50 bg-white/95 backdrop-blur-md shadow-sm border-b border-slate-200/80">
    <div class="hct-container flex items-center justify-between h-16 lg:h-[72px] gap-4">

      <!-- Logo Công Ty TNHH Xây Dựng Thương Mại Hải Cường Thịnh (Gọn nhỏ chuyên nghiệp) -->
      <a href="#trang-chu" class="flex items-center gap-2.5 flex-shrink-0 group" aria-label="Hải Cường Thịnh Trang chủ">
        <svg class="w-9 h-9 sm:w-10 sm:h-10 flex-shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
          <rect width="64" height="64" rx="12" fill="#0F2C59"/>
          <!-- Khung mái kiến trúc và cột kết cấu vững chắc -->
          <path d="M11 47V24.5L32 12L53 24.5V47H45.5V28.5L32 20.5L18.5 28.5V47H11Z" fill="#C88A2E"/>
          <!-- Khối tòa nhà trung tâm chữ H cách điệu -->
          <path d="M23 47V29H28.5V36H35.5V29H41V47H35.5V40.5H28.5V47H23Z" fill="#FFFFFF"/>
          <!-- Đường nền móng -->
          <rect x="11" y="49.5" width="42" height="3.5" rx="1.75" fill="#E0A84B"/>
        </svg>
        <div class="flex flex-col leading-tight">
          <span class="text-[14px] sm:text-[15px] font-extrabold tracking-tight text-brand-navy group-hover:text-brand-gold transition-colors whitespace-nowrap">
            HẢI CƯỜNG THỊNH
          </span>
          <span class="text-[9.5px] sm:text-[10px] font-semibold uppercase tracking-wider text-brand-gold whitespace-nowrap">
            Xây Dựng &amp; Thương Mại
          </span>
        </div>
      </a>

      <!-- Menu Danh mục trên Máy tính: Viết liền trên 1 hàng, chữ nhỏ gọn, tuyệt đối không xuống dòng -->
      <nav class="hidden lg:flex items-center justify-end flex-nowrap gap-3.5 xl:gap-5 min-w-0" aria-label="Menu chính">
        <a href="#trang-chu" class="text-[12.5px] xl:text-[13px] font-semibold text-brand-navy hover:text-brand-gold transition-colors whitespace-nowrap py-2">
          Trang chủ
        </a>
        <a href="#gioi-thieu" class="text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition-colors whitespace-nowrap py-2">
          Giới thiệu
        </a>

        <!-- Dropdown Công trình thực tế (theo web mẫu tintruongthinh.com) -->
        <div class="nav-item">
          <a href="#cong-trinh-thuc-te" class="inline-flex items-center gap-1 text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition-colors whitespace-nowrap py-2">
            <span>Công trình thực tế</span>
            <svg class="w-3.5 h-3.5 opacity-70" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
          </a>
          <div class="nav-dropdown bg-white rounded-lg shadow-xl border border-slate-100 py-2">
            <a href="#cong-trinh-thuc-te" onclick="filterProducts('khach-san')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy font-medium whitespace-nowrap">Khách sạn – Căn hộ</a>
            <a href="#cong-trinh-thuc-te" onclick="filterProducts('biet-thu')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy font-medium whitespace-nowrap">Biệt thự</a>
            <a href="#cong-trinh-thuc-te" onclick="filterProducts('nha-pho')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy font-medium whitespace-nowrap">Nhà phố</a>
            <a href="#cong-trinh-thuc-te" onclick="filterProducts('van-phong')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy font-medium whitespace-nowrap">Văn phòng &amp; Nội thất</a>
          </div>
        </div>

        <!-- Dropdown Lĩnh vực hoạt động -->
        <div class="nav-item">
          <a href="#linh-vuc-hoat-dong" class="inline-flex items-center gap-1 text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition-colors whitespace-nowrap py-2">
            <span>Lĩnh vực hoạt động</span>
            <svg class="w-3.5 h-3.5 opacity-70" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
          </a>
          <div class="nav-dropdown bg-white rounded-lg shadow-xl border border-slate-100 py-2">
            <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy font-medium whitespace-nowrap">Thiết kế Kiến trúc – Nội thất</a>
            <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy font-medium whitespace-nowrap">Thi công phần thô</a>
            <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy font-medium whitespace-nowrap">Thi công hoàn thiện</a>
            <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy font-medium whitespace-nowrap">Thi công nội thất trọn gói</a>
          </div>
        </div>

        <a href="#du-an-da-nang" class="text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition-colors whitespace-nowrap py-2">
          Dự án Đà Nẵng
        </a>

        <!-- Dropdown Báo giá -->
        <div class="nav-item">
          <a href="#bao-gia" class="inline-flex items-center gap-1 text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition-colors whitespace-nowrap py-2">
            <span>Báo giá</span>
            <svg class="w-3.5 h-3.5 opacity-70" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
          </a>
          <div class="nav-dropdown bg-white rounded-lg shadow-xl border border-slate-100 py-2">
            <a href="#bao-gia" onclick="prefillQuote('Thiết kế kiến trúc')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy font-medium whitespace-nowrap">Báo giá thiết kế kiến trúc</a>
            <a href="#bao-gia" onclick="prefillQuote('Thi công phần thô')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy font-medium whitespace-nowrap">Báo giá thi công phần thô</a>
            <a href="#bao-gia" onclick="prefillQuote('Thi công hoàn thiện')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy font-medium whitespace-nowrap">Báo giá thi công hoàn thiện</a>
            <a href="#bao-gia" onclick="prefillQuote('Thi công trọn gói')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy font-medium whitespace-nowrap">Báo giá thi công trọn gói</a>
          </div>
        </div>

        <a href="#doi-tac" class="text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition-colors whitespace-nowrap py-2">
          Đối tác
        </a>
        <a href="#tin-tuc" class="text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition-colors whitespace-nowrap py-2">
          Tin tức
        </a>
        <a href="#lien-he" class="text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition-colors whitespace-nowrap py-2">
          Liên hệ
        </a>
      </nav>

      <!-- Nút mở Menu Mobile (Flatsome Off-Canvas) -->
      <button id="mobile-menu-btn" type="button" class="lg:hidden p-2.5 rounded-lg text-brand-navy hover:bg-slate-100 transition-colors focus:outline-none" aria-label="Mở menu điều hướng">
        <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16M4 18h16"/>
        </svg>
      </button>
    </div>
  </header>

  <!-- ==================== MOBILE DRAWER MENU (FLATSOME OFF-CANVAS) ==================== -->
  <div id="mobile-drawer-overlay" class="fixed inset-0 bg-slate-900/50 z-50 hidden opacity-0 transition-opacity duration-300 lg:hidden"></div>
  <aside id="mobile-drawer" class="fixed top-0 left-0 h-full w-[285px] max-w-[82vw] bg-white z-50 shadow-2xl transform -translate-x-full transition-transform duration-300 lg:hidden flex flex-col">
    <div class="flex items-center justify-between px-4 py-4 border-b border-slate-100 bg-brand-navy text-white">
      <div class="flex items-center gap-2">
        <svg class="w-7 h-7" viewBox="0 0 64 64" fill="none"><rect width="64" height="64" rx="12" fill="#0A1E3D"/><path d="M11 47V24.5L32 12L53 24.5V47H45.5V28.5L32 20.5L18.5 28.5V47H11Z" fill="#C88A2E"/><path d="M23 47V29H28.5V36H35.5V29H41V47H35.5V40.5H28.5V47H23Z" fill="#FFFFFF"/></svg>
        <span class="font-bold text-sm tracking-tight">HẢI CƯỜNG THỊNH</span>
      </div>
      <button id="mobile-drawer-close" type="button" class="p-1.5 rounded-lg text-white/80 hover:text-white hover:bg-white/10" aria-label="Đóng menu">
        <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/></svg>
      </button>
    </div>
    <nav class="flex-1 overflow-y-auto py-3 px-3 space-y-1">
      <a href="#trang-chu" class="mobile-nav-link block px-3 py-2.5 rounded-lg text-sm font-semibold text-brand-navy hover:bg-brand-goldSoft">Trang chủ</a>
      <a href="#gioi-thieu" class="mobile-nav-link block px-3 py-2.5 rounded-lg text-sm font-semibold text-slate-700 hover:bg-brand-goldSoft">Giới thiệu công ty</a>
      <a href="#linh-vuc-hoat-dong" class="mobile-nav-link block px-3 py-2.5 rounded-lg text-sm font-semibold text-slate-700 hover:bg-brand-goldSoft">Lĩnh vực hoạt động</a>
      <a href="#cong-trinh-thuc-te" class="mobile-nav-link block px-3 py-2.5 rounded-lg text-sm font-semibold text-slate-700 hover:bg-brand-goldSoft">Công trình thực tế</a>
      <a href="#du-an-da-nang" class="mobile-nav-link block px-3 py-2.5 rounded-lg text-sm font-semibold text-slate-700 hover:bg-brand-goldSoft">Dự án tại Đà Nẵng</a>
      <a href="#doi-tac" class="mobile-nav-link block px-3 py-2.5 rounded-lg text-sm font-semibold text-slate-700 hover:bg-brand-goldSoft">Đối tác chiến lược</a>
      <a href="#bao-gia" class="mobile-nav-link block px-3 py-2.5 rounded-lg text-sm font-semibold text-slate-700 hover:bg-brand-goldSoft">Yêu cầu báo giá</a>
      <a href="#tin-tuc" class="mobile-nav-link block px-3 py-2.5 rounded-lg text-sm font-semibold text-slate-700 hover:bg-brand-goldSoft">Tin tức xây dựng</a>
      <a href="#lien-he" class="mobile-nav-link block px-3 py-2.5 rounded-lg text-sm font-semibold text-slate-700 hover:bg-brand-goldSoft">Liên hệ &amp; Bản đồ</a>
    </nav>
    <div class="p-4 border-t border-slate-100 bg-slate-50 text-xs text-slate-600 space-y-1.5">
      <p class="font-bold text-brand-navy">Hotline: 0934.783.967</p>
      <p>248 Dương Đình Nghệ, P. An Hải, TP Đà Nẵng</p>
    </div>
  </aside>

  <!-- ==================== FLATSOME SECTION 1: HERO BANNER SLIDER (2 ẢNH BẰNG NHAU) ==================== -->
  <!-- Đảm bảo: 2 banner kích thước bằng nhau, chữ nằm trọn trong banner, cách xa viền ảnh, không mất chữ trên Mobile & PC -->
  <section id="trang-chu" class="w-full bg-brand-navyDark pt-3 pb-4 sm:py-5">
    <div class="hct-container">
      <div id="hero-slider" class="relative w-full overflow-hidden rounded-xl shadow-lg bg-brand-navyDark">
        <div id="banner-track" class="banner-track">

          <!-- SLIDE 1 -->
          <div class="banner-slide h-[360px] sm:h-[430px] md:h-[490px] lg:h-[540px]">
            <img
              src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w1600"
              data-fallback="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1600"
              onerror="handleDriveImageError(this, 'Thi Cong Xay Dung Hai Cuong Thinh')"
              referrerpolicy="no-referrer"
              alt="Thi công xây dựng trọn gói Hải Cường Thịnh Đà Nẵng"
              class="absolute inset-0 w-full h-full object-cover object-center"
            />
            <!-- Lớp phủ tối gradient giúp chữ nổi bật và sắc nét -->
            <div class="absolute inset-0 bg-gradient-to-r from-brand-navyDark/90 via-brand-navy/75 to-brand-navyDark/45"></div>

            <!-- Vùng chứa nội dung cách xa viền ảnh banner ở mọi kích thước màn hình -->
            <div class="relative z-10 h-full w-full flex items-center px-11 sm:px-16 md:px-20 lg:px-24 py-8 sm:py-12">
              <div class="max-w-2xl space-y-3 sm:space-y-4">
                <p class="text-[11px] sm:text-xs md:text-sm font-bold uppercase tracking-[0.18em] text-brand-goldLight">
                  HẢI CƯỜNG THỊNH — ĐÀ NẴNG
                </p>
                <h1 class="text-xl sm:text-3xl md:text-4xl lg:text-[42px] font-extrabold text-white leading-snug sm:leading-tight">
                  THIẾT KẾ &amp; THI CÔNG XÂY DỰNG TRỌN GÓI CHUYÊN NGHIỆP
                </h1>
                <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed max-w-xl">
                  Kiến tạo công trình nhà phố, biệt thự, khách sạn và căn hộ bền vững tại Đà Nẵng với quy trình giám sát kỹ thuật chuẩn xác và chi phí minh bạch.
                </p>
                <div class="pt-2 flex flex-wrap items-center gap-3">
                  <a href="#bao-gia" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-brand-gold hover:bg-brand-goldLight text-white font-semibold text-xs sm:text-sm transition-all shadow-md">
                    Nhận báo giá miễn phí
                  </a>
                  <a href="#cong-trinh-thuc-te" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/30 font-semibold text-xs sm:text-sm transition-all backdrop-blur-sm">
                    Xem công trình thực tế
                  </a>
                </div>
              </div>
            </div>
          </div>

          <!-- SLIDE 2 (Chiều cao và cấu trúc padding đồng nhất 100% với Slide 1) -->
          <div class="banner-slide h-[360px] sm:h-[430px] md:h-[490px] lg:h-[540px]">
            <img
              src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w1600"
              data-fallback="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1600"
              onerror="handleDriveImageError(this, 'Du An Tieu Bieu Tai Da Nang')"
              referrerpolicy="no-referrer"
              alt="Dự án xây dựng tiêu biểu tại Đà Nẵng Hải Cường Thịnh"
              class="absolute inset-0 w-full h-full object-cover object-center"
            />
            <div class="absolute inset-0 bg-gradient-to-r from-brand-navyDark/90 via-brand-navy/75 to-brand-navyDark/45"></div>

            <div class="relative z-10 h-full w-full flex items-center px-11 sm:px-16 md:px-20 lg:px-24 py-8 sm:py-12">
              <div class="max-w-2xl space-y-3 sm:space-y-4">
                <p class="text-[11px] sm:text-xs md:text-sm font-bold uppercase tracking-[0.18em] text-brand-goldLight">
                  CHẤT LƯỢNG TẠO DỰNG NIỀM TIN
                </p>
                <h2 class="text-xl sm:text-3xl md:text-4xl lg:text-[42px] font-extrabold text-white leading-snug sm:leading-tight">
                  NHÀ THẦU THI CÔNG PHẦN THÔ &amp; HOÀN THIỆN UY TÍN
                </h2>
                <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed max-w-xl">
                  Cam kết sử dụng vật tư chính hãng, thi công đúng tiến độ, bảo hành kết cấu dài hạn cho mọi công trình dân dụng và thương mại tại khu vực miền Trung.
                </p>
                <div class="pt-2 flex flex-wrap items-center gap-3">
                  <a href="#du-an-da-nang" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-brand-gold hover:bg-brand-goldLight text-white font-semibold text-xs sm:text-sm transition-all shadow-md">
                    Khám phá dự án Đà Nẵng
                  </a>
                  <a href="tel:0934783967" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/30 font-semibold text-xs sm:text-sm transition-all backdrop-blur-sm">
                    Tư vấn: 0934.783.967
                  </a>
                </div>
              </div>
            </div>
          </div>

        </div>

        <!-- Nút điều hướng trái / phải đặt gọn sát biên ngoài vùng chữ -->
        <button id="banner-prev" type="button" class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-brand-navyDark/60 hover:bg-brand-gold text-white flex items-center justify-center transition-colors" aria-label="Ảnh trước">
          <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M15 19l-7-7 7-7"/></svg>
        </button>
        <button id="banner-next" type="button" class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-brand-navyDark/60 hover:bg-brand-gold text-white flex items-center justify-center transition-colors" aria-label="Ảnh tiếp theo">
          <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7"/></svg>
        </button>

        <!-- Chấm chỉ báo vị trí Slide -->
        <div class="absolute bottom-3.5 sm:bottom-5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2.5">
          <button type="button" data-slide="0" class="banner-dot w-7 h-2 rounded-full bg-brand-gold transition-all" aria-label="Banner 1"></button>
          <button type="button" data-slide="1" class="banner-dot w-2.5 h-2 rounded-full bg-white/60 hover:bg-white transition-all" aria-label="Banner 2"></button>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== FLATSOME SECTION 2: DỊCH VỤ TIÊU BIỂU (LĨNH VỰC HOẠT ĐỘNG) ==================== -->
  <section id="linh-vuc-hoat-dong" class="py-12 sm:py-16 bg-white">
    <div class="hct-container">
      <div class="text-center max-w-2xl mx-auto mb-8 sm:mb-10">
        <h2 class="text-xl sm:text-2xl lg:text-[28px] font-extrabold text-brand-navy uppercase tracking-tight">
          Lĩnh Vực Hoạt Động Tiêu Biểu
        </h2>
        <div class="section-divider"></div>
        <p class="text-xs sm:text-sm text-slate-600 mt-3 leading-relaxed">
          Cung cấp giải pháp đồng bộ từ thiết kế kiến trúc, thi công xây dựng phần thô, hoàn thiện đến nội thất trọn gói.
        </p>
      </div>

      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3.5 sm:gap-5">
        <!-- Dịch vụ 1 -->
        <div class="bg-brand-surface rounded-xl p-4 sm:p-6 border border-slate-200/70 hover:border-brand-gold hover:shadow-md transition-all flex flex-col justify-between">
          <div>
            <div class="w-11 h-11 rounded-lg bg-brand-navy text-brand-goldLight flex items-center justify-center mb-4">
              <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 21h18M5 21V7l7-4 7 4v14M9 21v-6h6v6"/></svg>
            </div>
            <h3 class="text-sm sm:text-base font-bold text-brand-navy mb-2 leading-snug">Thiết Kế Kiến Trúc – Nội Thất</h3>
            <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">
              Thiết kế công năng khoa học, thẩm mỹ hiện đại cho nhà phố, biệt thự, khách sạn và văn phòng.
            </p>
          </div>
          <a href="#bao-gia" onclick="prefillQuote('Thiết kế kiến trúc')" class="mt-4 inline-flex items-center gap-1 text-xs font-semibold text-brand-gold hover:text-brand-navy transition-colors">
            Nhận tư vấn <span>&rarr;</span>
          </a>
        </div>

        <!-- Dịch vụ 2 -->
        <div class="bg-brand-surface rounded-xl p-4 sm:p-6 border border-slate-200/70 hover:border-brand-gold hover:shadow-md transition-all flex flex-col justify-between">
          <div>
            <div class="w-11 h-11 rounded-lg bg-brand-navy text-brand-goldLight flex items-center justify-center mb-4">
              <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4"/></svg>
            </div>
            <h3 class="text-sm sm:text-base font-bold text-brand-navy mb-2 leading-snug">Thi Công Xây Dựng Phần Thô</h3>
            <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">
              Thi công móng, kết cấu bê tông cốt thép, xây tô đúng tiêu chuẩn kỹ thuật, bền vững theo thời gian.
            </p>
          </div>
          <a href="#bao-gia" onclick="prefillQuote('Thi công phần thô')" class="mt-4 inline-flex items-center gap-1 text-xs font-semibold text-brand-gold hover:text-brand-navy transition-colors">
            Nhận tư vấn <span>&rarr;</span>
          </a>
        </div>

        <!-- Dịch vụ 3 -->
        <div class="bg-brand-surface rounded-xl p-4 sm:p-6 border border-slate-200/70 hover:border-brand-gold hover:shadow-md transition-all flex flex-col justify-between">
          <div>
            <div class="w-11 h-11 rounded-lg bg-brand-navy text-brand-goldLight flex items-center justify-center mb-4">
              <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M4 5a1 1 0 011-1h14a1 1 0 011 1v2a1 1 0 01-1 1H5a1 1 0 01-1-1V5zM4 13a1 1 0 011-1h6a1 1 0 011 1v6a1 1 0 01-1 1H5a1 1 0 01-1-1v-6zM16 13a1 1 0 011-1h2a1 1 0 011 1v6a1 1 0 01-1 1h-2a1 1 0 01-1-1v-6z"/></svg>
            </div>
            <h3 class="text-sm sm:text-base font-bold text-brand-navy mb-2 leading-snug">Thi Công Hoàn Thiện Trọn Gói</h3>
            <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">
              Ốp lát, sơn nước, điện nước M&amp;E, trần thạch cao, cửa nhôm kính đồng bộ chìa khóa trao tay.
            </p>
          </div>
          <a href="#bao-gia" onclick="prefillQuote('Thi công hoàn thiện')" class="mt-4 inline-flex items-center gap-1 text-xs font-semibold text-brand-gold hover:text-brand-navy transition-colors">
            Nhận tư vấn <span>&rarr;</span>
          </a>
        </div>

        <!-- Dịch vụ 4 -->
        <div class="bg-brand-surface rounded-xl p-4 sm:p-6 border border-slate-200/70 hover:border-brand-gold hover:shadow-md transition-all flex flex-col justify-between">
          <div>
            <div class="w-11 h-11 rounded-lg bg-brand-navy text-brand-goldLight flex items-center justify-center mb-4">
              <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M20 7l-8-4-8 4m16 0l-8 4m8-4v10l-8 4m0-10L4 7m8 4v10M4 7v10l8 4"/></svg>
            </div>
            <h3 class="text-sm sm:text-base font-bold text-brand-navy mb-2 leading-snug">Thi Công Nội Thất &amp; Cải Tạo</h3>
            <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">
              Sản xuất và lắp đặt nội thất gỗ công nghiệp, cải tạo sửa chữa nâng cấp không gian tối ưu chi phí.
            </p>
          </div>
          <a href="#bao-gia" onclick="prefillQuote('Thi công nội thất')" class="mt-4 inline-flex items-center gap-1 text-xs font-semibold text-brand-gold hover:text-brand-navy transition-colors">
            Nhận tư vấn <span>&rarr;</span>
          </a>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== FLATSOME SECTION 3: GIỚI THIỆU & THẾ MẠNH ==================== -->
  <section id="gioi-thieu" class="py-12 sm:py-16 bg-brand-surface border-y border-slate-200/70">
    <div class="hct-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 lg:gap-10 items-center">
        <!-- Cột trái: Ảnh thực tế thi công từ Google Drive -->
        <div class="lg:col-span-5">
          <div class="rounded-xl overflow-hidden shadow-md border border-slate-200 bg-white">
            <img
              src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w1200"
              data-fallback="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w1000"
              onerror="handleDriveImageError(this, 'Cong Ty Xay Dung Hai Cuong Thinh')"
              referrerpolicy="no-referrer"
              alt="Đội ngũ thi công Công ty TNHH Xây Dựng Thương Mại Hải Cường Thịnh"
              class="w-full aspect-[4/3] object-cover"
            />
          </div>
        </div>

        <!-- Cột phải: Nội dung giới thiệu & 6 thế mạnh cốt lõi -->
        <div class="lg:col-span-7 space-y-5">
          <div>
            <p class="text-xs font-bold uppercase tracking-widest text-brand-gold">Về Chúng Tôi</p>
            <h2 class="text-xl sm:text-2xl lg:text-[28px] font-extrabold text-brand-navy mt-1 leading-snug">
              CÔNG TY TNHH XÂY DỰNG THƯƠNG MẠI HẢI CƯỜNG THỊNH
            </h2>
            <div class="section-divider-left"></div>
          </div>

          <p class="text-sm text-slate-600 leading-relaxed">
            <strong>Hải Cường Thịnh</strong> chuyên tư vấn thiết kế, thi công xây dựng và cung ứng vật tư thương mại cho các công trình Nhà phố, Biệt thự, Khách sạn, Căn hộ cho thuê và Văn phòng tại khu vực <strong>Đà Nẵng – Quảng Nam</strong>. Với phương châm <em>“An Toàn – Chất Lượng – Tiến Độ – Minh Bạch”</em>, đội ngũ kỹ sư và thợ lành nghề của chúng tôi luôn đặt cái tâm vào từng hạng mục để kiến tạo không gian sống bền vững cho khách hàng.
          </p>

          <!-- 6 thế mạnh chuẩn bố cục Flatsome Icon Box -->
          <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5 pt-1">
            <div class="flex items-start gap-3 bg-white p-3.5 rounded-lg border border-slate-200/80">
              <div class="w-8 h-8 rounded-md bg-brand-goldSoft text-brand-gold flex items-center justify-center flex-shrink-0 font-bold text-sm">01</div>
              <div>
                <h4 class="text-[13px] font-bold text-brand-navy">Kỹ sư &amp; Kiến trúc sư kinh nghiệm</h4>
                <p class="text-xs text-slate-600 mt-0.5 leading-relaxed">Trực tiếp khảo sát, bóc tách khối lượng và giám sát kỹ thuật tại công trình.</p>
              </div>
            </div>
            <div class="flex items-start gap-3 bg-white p-3.5 rounded-lg border border-slate-200/80">
              <div class="w-8 h-8 rounded-md bg-brand-goldSoft text-brand-gold flex items-center justify-center flex-shrink-0 font-bold text-sm">02</div>
              <div>
                <h4 class="text-[13px] font-bold text-brand-navy">Cam kết tiến độ chuẩn xác</h4>
                <p class="text-xs text-slate-600 mt-0.5 leading-relaxed">Báo cáo tiến độ định kỳ minh bạch, bàn giao đúng lịch hẹn trong hợp đồng.</p>
              </div>
            </div>
            <div class="flex items-start gap-3 bg-white p-3.5 rounded-lg border border-slate-200/80">
              <div class="w-8 h-8 rounded-md bg-brand-goldSoft text-brand-gold flex items-center justify-center flex-shrink-0 font-bold text-sm">03</div>
              <div>
                <h4 class="text-[13px] font-bold text-brand-navy">Vật tư chính hãng rõ nguồn gốc</h4>
                <p class="text-xs text-slate-600 mt-0.5 leading-relaxed">Sử dụng thép, xi măng, thiết bị điện nước đạt chuẩn kiểm định chất lượng.</p>
              </div>
            </div>
            <div class="flex items-start gap-3 bg-white p-3.5 rounded-lg border border-slate-200/80">
              <div class="w-8 h-8 rounded-md bg-brand-goldSoft text-brand-gold flex items-center justify-center flex-shrink-0 font-bold text-sm">04</div>
              <div>
                <h4 class="text-[13px] font-bold text-brand-navy">Chi phí hợp lý, không phát sinh</h4>
                <p class="text-xs text-slate-600 mt-0.5 leading-relaxed">Dự toán rõ ràng từng hạng mục, tối ưu ngân sách đầu tư của chủ nhà.</p>
              </div>
            </div>
            <div class="flex items-start gap-3 bg-white p-3.5 rounded-lg border border-slate-200/80">
              <div class="w-8 h-8 rounded-md bg-brand-goldSoft text-brand-gold flex items-center justify-center flex-shrink-0 font-bold text-sm">05</div>
              <div>
                <h4 class="text-[13px] font-bold text-brand-navy">Bảo hành công trình lâu dài</h4>
                <p class="text-xs text-slate-600 mt-0.5 leading-relaxed">Chính sách bảo hành kết cấu và bảo trì chống thấm nhanh chóng, tận tâm.</p>
              </div>
            </div>
            <div class="flex items-start gap-3 bg-white p-3.5 rounded-lg border border-slate-200/80">
              <div class="w-8 h-8 rounded-md bg-brand-goldSoft text-brand-gold flex items-center justify-center flex-shrink-0 font-bold text-sm">06</div>
              <div>
                <h4 class="text-[13px] font-bold text-brand-navy">Hỗ trợ tư vấn miễn phí 24/7</h4>
                <p class="text-xs text-slate-600 mt-0.5 leading-relaxed">Hỗ trợ hồ sơ xin phép xây dựng, thiết kế mặt bằng sơ bộ trước khi ký kết.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== FLATSOME SECTION 4: CÔNG TRÌNH & SẢN PHẨM THI CÔNG THỰC TẾ (9 ẢNH DRIVE BỘ 1) ==================== -->
  <!-- Đảm bảo: 2 cột trên điện thoại, 3 cột trên máy tính, tên sản phẩm hiển thị đầy đủ không thiếu chữ, không dán nhãn trên ảnh -->
  <section id="cong-trinh-thuc-te" class="py-12 sm:py-16 bg-white">
    <div class="hct-container">
      <div class="text-center max-w-3xl mx-auto mb-6 sm:mb-8">
        <h2 class="text-xl sm:text-2xl lg:text-[28px] font-extrabold text-brand-navy uppercase tracking-tight">
          Công Trình &amp; Hạng Mục Thi Công Thực Tế
        </h2>
        <div class="section-divider"></div>
        <p class="text-xs sm:text-sm text-slate-600 mt-3">
          Hình ảnh thực tế thi công xây dựng phần thô, hoàn thiện kiến trúc và nội thất do Hải Cường Thịnh trực tiếp thực hiện.
        </p>
      </div>

      <!-- Bộ lọc danh mục nhỏ gọn, viết liền không vỡ dòng bên trong tên danh mục -->
      <div id="product-filter-bar" class="flex flex-wrap items-center justify-center gap-2 sm:gap-2.5 mb-7 sm:mb-9">
        <button type="button" data-filter="all" onclick="filterProducts('all')" class="filter-btn active px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand-navy text-white transition-all whitespace-nowrap">
          Tất cả
        </button>
        <button type="button" data-filter="khach-san" onclick="filterProducts('khach-san')" class="filter-btn px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand-surface text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy border border-slate-200 transition-all whitespace-nowrap">
          Khách sạn – Căn hộ
        </button>
        <button type="button" data-filter="biet-thu" onclick="filterProducts('biet-thu')" class="filter-btn px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand-surface text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy border border-slate-200 transition-all whitespace-nowrap">
          Biệt thự
        </button>
        <button type="button" data-filter="nha-pho" onclick="filterProducts('nha-pho')" class="filter-btn px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand-surface text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy border border-slate-200 transition-all whitespace-nowrap">
          Nhà phố
        </button>
        <button type="button" data-filter="van-phong" onclick="filterProducts('van-phong')" class="filter-btn px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand-surface text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy border border-slate-200 transition-all whitespace-nowrap">
          Văn phòng &amp; Nội thất
        </button>
      </div>

      <!-- Lưới sản phẩm thi công thực tế: 2 cột trên điện thoại, 3 cột trên máy tính -->
      <div id="products-grid" class="grid grid-cols-2 md:grid-cols-3 gap-3.5 sm:gap-5 lg:gap-6">
        <!-- Nội dung được render tự động từ dữ liệu 9 ảnh thực tế Google Drive -->
      </div>
    </div>
  </section>

  <!-- ==================== FLATSOME SECTION 5: CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (10 ẢNH DRIVE BỘ 2) ==================== -->
  <section id="du-an-da-nang" class="py-12 sm:py-16 bg-brand-surface border-y border-slate-200/70">
    <div class="hct-container">
      <div class="text-center max-w-3xl mx-auto mb-8 sm:mb-10">
        <h2 class="text-xl sm:text-2xl lg:text-[28px] font-extrabold text-brand-navy uppercase tracking-tight">
          Các Dự Án Tiêu Biểu Tại Đà Nẵng
        </h2>
        <div class="section-divider"></div>
        <p class="text-xs sm:text-sm text-slate-600 mt-3">
          Những công trình thực tế Hải Cường Thịnh đã và đang triển khai tại Sơn Trà, Hải Châu, Ngũ Hành Sơn, Hòa Xuân và các quận trung tâm Đà Nẵng.
        </p>
      </div>

      <!-- Lưới 10 dự án Đà Nẵng: 2 cột trên điện thoại, 3 cột trên tablet, 5 cột cân đối trên máy tính -->
      <div id="danang-projects-grid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-3.5 sm:gap-4 lg:gap-5">
        <!-- Nội dung được render tự động từ dữ liệu 10 ảnh dự án Đà Nẵng Google Drive -->
      </div>
    </div>
  </section>

  <!-- ==================== FLATSOME SECTION 6: DANH MỤC CÁC ĐỐI TÁC ==================== -->
  <section id="doi-tac" class="py-12 sm:py-14 bg-white">
    <div class="hct-container">
      <div class="text-center max-w-2xl mx-auto mb-8">
        <h2 class="text-xl sm:text-2xl lg:text-[26px] font-extrabold text-brand-navy uppercase tracking-tight">
          Đối Tác Cung Ứng &amp; Đồng Hành
        </h2>
        <div class="section-divider"></div>
        <p class="text-xs sm:text-sm text-slate-600 mt-3">
          Hợp tác cùng các thương hiệu vật liệu xây dựng và thiết bị nội thất hàng đầu Việt Nam &amp; Quốc tế.
        </p>
      </div>

      <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 gap-3 sm:gap-4">
        <div class="bg-brand-surface border border-slate-200/80 rounded-xl py-5 px-3 flex flex-col items-center justify-center text-center hover:border-brand-gold transition-colors">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">HÒA PHÁT</span>
          <span class="text-[11px] text-slate-500 mt-1">Thép xây dựng</span>
        </div>
        <div class="bg-brand-surface border border-slate-200/80 rounded-xl py-5 px-3 flex flex-col items-center justify-center text-center hover:border-brand-gold transition-colors">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">VIỆT NHẬT</span>
          <span class="text-[11px] text-slate-500 mt-1">Thép kết cấu</span>
        </div>
        <div class="bg-brand-surface border border-slate-200/80 rounded-xl py-5 px-3 flex flex-col items-center justify-center text-center hover:border-brand-gold transition-colors">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">SÔNG GIANH</span>
          <span class="text-[11px] text-slate-500 mt-1">Xi măng công trình</span>
        </div>
        <div class="bg-brand-surface border border-slate-200/80 rounded-xl py-5 px-3 flex flex-col items-center justify-center text-center hover:border-brand-gold transition-colors">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">JOTUN</span>
          <span class="text-[11px] text-slate-500 mt-1">Sơn nội ngoại thất</span>
        </div>
        <div class="bg-brand-surface border border-slate-200/80 rounded-xl py-5 px-3 flex flex-col items-center justify-center text-center hover:border-brand-gold transition-colors">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">DULUX</span>
          <span class="text-[11px] text-slate-500 mt-1">Sơn cao cấp</span>
        </div>
        <div class="bg-brand-surface border border-slate-200/80 rounded-xl py-5 px-3 flex flex-col items-center justify-center text-center hover:border-brand-gold transition-colors">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">XINGFA</span>
          <span class="text-[11px] text-slate-500 mt-1">Nhôm kính kiến trúc</span>
        </div>
        <div class="bg-brand-surface border border-slate-200/80 rounded-xl py-5 px-3 flex flex-col items-center justify-center text-center hover:border-brand-gold transition-colors">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">VIGLACERA</span>
          <span class="text-[11px] text-slate-500 mt-1">Gạch ốp lát &amp; Sứ</span>
        </div>
        <div class="bg-brand-surface border border-slate-200/80 rounded-xl py-5 px-3 flex flex-col items-center justify-center text-center hover:border-brand-gold transition-colors">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">AN CƯỜNG</span>
          <span class="text-[11px] text-slate-500 mt-1">Gỗ nội thất</span>
        </div>
        <div class="bg-brand-surface border border-slate-200/80 rounded-xl py-5 px-3 flex flex-col items-center justify-center text-center hover:border-brand-gold transition-colors">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">CADIVI</span>
          <span class="text-[11px] text-slate-500 mt-1">Dây &amp; Cáp điện</span>
        </div>
        <div class="bg-brand-surface border border-slate-200/80 rounded-xl py-5 px-3 flex flex-col items-center justify-center text-center hover:border-brand-gold transition-colors">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">SIKA</span>
          <span class="text-[11px] text-slate-500 mt-1">Chống thấm chuyên dụng</span>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== FLATSOME SECTION 7: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ ==================== -->
  <section id="bao-gia" class="py-12 sm:py-16 bg-brand-navy text-white">
    <div class="hct-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 lg:gap-10 items-center">
        <!-- Thông tin cam kết tư vấn bên trái -->
        <div class="lg:col-span-5 space-y-4">
          <p class="text-xs font-bold uppercase tracking-widest text-brand-goldLight">Miễn Phí Tư Vấn &amp; Khảo Sát</p>
          <h2 class="text-2xl sm:text-3xl font-extrabold leading-tight">
            Đăng Ký Nhận Báo Giá Thi Công Chi Tiết
          </h2>
          <div class="section-divider-left"></div>
          <p class="text-sm text-slate-200 leading-relaxed pt-1">
            Để lại thông tin công trình của quý khách, đội ngũ kỹ sư <strong>Hải Cường Thịnh</strong> sẽ liên hệ tư vấn phương án thiết kế tối ưu và gửi bảng dự toán chi phí chi tiết trong vòng 30 phút.
          </p>

          <div class="space-y-3 pt-2 text-sm text-slate-100">
            <div class="flex items-center gap-3">
              <span class="w-8 h-8 rounded-lg bg-white/10 text-brand-goldLight flex items-center justify-center flex-shrink-0">
                <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7"/></svg>
              </span>
              <span>Khảo sát hiện trạng thực tế miễn phí tại Đà Nẵng</span>
            </div>
            <div class="flex items-center gap-3">
              <span class="w-8 h-8 rounded-lg bg-white/10 text-brand-goldLight flex items-center justify-center flex-shrink-0">
                <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7"/></svg>
              </span>
              <span>Bóc tách dự toán vật tư minh bạch, rõ ràng từng hạng mục</span>
            </div>
            <div class="flex items-center gap-3">
              <span class="w-8 h-8 rounded-lg bg-white/10 text-brand-goldLight flex items-center justify-center flex-shrink-0">
                <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7"/></svg>
              </span>
              <span>Hotline tư vấn trực tiếp: <strong class="text-brand-goldLight">0934.783.967</strong></span>
            </div>
          </div>
        </div>

        <!-- Form nhập liệu chuẩn mẫu tintruongthinh.com -->
        <div class="lg:col-span-7">
          <form id="quote-form" class="bg-white text-slate-800 rounded-xl p-5 sm:p-7 shadow-xl space-y-4" novalidate>
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
              <div>
                <label for="q-name" class="block text-xs font-semibold text-brand-navy mb-1.5">Họ và tên *</label>
                <input id="q-name" type="text" required placeholder="Nhập họ tên quý khách" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-gold focus:ring-2 focus:ring-brand-gold/20 outline-none transition" />
              </div>
              <div>
                <label for="q-phone" class="block text-xs font-semibold text-brand-navy mb-1.5">Số điện thoại / Zalo *</label>
                <input id="q-phone" type="tel" required placeholder="Ví dụ: 0934 783 967" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-gold focus:ring-2 focus:ring-brand-gold/20 outline-none transition" />
              </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
              <div>
                <label for="q-type" class="block text-xs font-semibold text-brand-navy mb-1.5">Loại công trình / Hạng mục</label>
                <select id="q-type" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 bg-white focus:border-brand-gold focus:ring-2 focus:ring-brand-gold/20 outline-none transition">
                  <option value="Nhà phố">Nhà phố</option>
                  <option value="Biệt thự">Biệt thự</option>
                  <option value="Khách sạn – Căn hộ cho thuê">Khách sạn – Căn hộ cho thuê</option>
                  <option value="Văn phòng – Showroom">Văn phòng – Showroom</option>
                  <option value="Thiết kế kiến trúc">Thiết kế kiến trúc</option>
                  <option value="Thi công phần thô">Thi công phần thô</option>
                  <option value="Thi công hoàn thiện">Thi công hoàn thiện</option>
                  <option value="Thi công trọn gói">Thi công trọn gói</option>
                  <option value="Thi công nội thất">Thi công nội thất &amp; Cải tạo</option>
                </select>
              </div>
              <div>
                <label for="q-budget" class="block text-xs font-semibold text-brand-navy mb-1.5">Mức đầu tư dự kiến</label>
                <select id="q-budget" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 bg-white focus:border-brand-gold focus:ring-2 focus:ring-brand-gold/20 outline-none transition">
                  <option value="Chưa xác định">Chưa xác định</option>
                  <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                  <option value="500 triệu - 1 tỷ">500 triệu – 1 tỷ</option>
                  <option value="1 tỷ - 2 tỷ">1 tỷ – 2 tỷ</option>
                  <option value="2 tỷ - 3 tỷ">2 tỷ – 3 tỷ</option>
                  <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                </select>
              </div>
            </div>

            <div>
              <label for="q-email" class="block text-xs font-semibold text-brand-navy mb-1.5">Email (Không bắt buộc)</label>
              <input id="q-email" type="email" placeholder="Nhập địa chỉ email để nhận file báo giá" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-gold focus:ring-2 focus:ring-brand-gold/20 outline-none transition" />
            </div>

            <div>
              <label for="q-note" class="block text-xs font-semibold text-brand-navy mb-1.5">Mô tả yêu cầu (Diện tích, số tầng, địa điểm xây dựng)</label>
              <textarea id="q-note" rows="3" placeholder="Ví dụ: Xây nhà phố 3 tầng diện tích 5x20m tại quận Sơn Trà, Đà Nẵng..." class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-gold focus:ring-2 focus:ring-brand-gold/20 outline-none transition resize-none"></textarea>
            </div>

            <!-- Thông báo phản hồi trực tiếp trong form (không dùng alert) -->
            <div id="quote-feedback" class="hidden rounded-lg p-3.5 text-xs sm:text-sm font-medium"></div>

            <button type="submit" class="w-full py-3 px-6 rounded-lg bg-brand-gold hover:bg-brand-goldLight text-white font-bold text-sm uppercase tracking-wide shadow-md transition-all">
              Gửi Yêu Cầu Báo Giá Ngay
            </button>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== FLATSOME SECTION 8: DANH MỤC CÁC BÀI VIẾT / TIN TỨC TRANG CHỦ ==================== -->
  <section id="tin-tuc" class="py-12 sm:py-16 bg-white">
    <div class="hct-container">
      <div class="text-center max-w-2xl mx-auto mb-8 sm:mb-10">
        <h2 class="text-xl sm:text-2xl lg:text-[28px] font-extrabold text-brand-navy uppercase tracking-tight">
          Tin Tức &amp; Cẩm Nang Xây Dựng
        </h2>
        <div class="section-divider"></div>
        <p class="text-xs sm:text-sm text-slate-600 mt-3">
          Chia sẻ kiến thức kỹ thuật thi công, kinh nghiệm tối ưu chi phí xây nhà và xu hướng kiến trúc mới nhất.
        </p>
      </div>

      <div id="articles-grid" class="grid grid-cols-2 lg:grid-cols-4 gap-3.5 sm:gap-5">
        <!-- 4 bài viết trang chủ được render bằng JS có thể bấm xem chi tiết -->
      </div>
    </div>
  </section>

  <!-- ==================== FLATSOME SECTION 9: GOOGLE MAPS & FANPAGE FACEBOOK NGOÀI TRANG CHỦ ==================== -->
  <section id="lien-he" class="py-12 sm:py-16 bg-brand-surface border-t border-slate-200/80">
    <div class="hct-container">
      <div class="text-center max-w-2xl mx-auto mb-8 sm:mb-10">
        <h2 class="text-xl sm:text-2xl lg:text-[28px] font-extrabold text-brand-navy uppercase tracking-tight">
          Bản Đồ Văn Phòng &amp; Kết Nối Fanpage
        </h2>
        <div class="section-divider"></div>
        <p class="text-xs sm:text-sm text-slate-600 mt-3">
          Địa chỉ trụ sở: <strong>248 Dương Đình Nghệ, Phường An Hải, TP Đà Nẵng</strong> — Hotline: <strong>0934.783.967</strong>
        </p>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
        <!-- Cột trái (7 phần): Google Map thực tế hiển thị ngoài trang chủ -->
        <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
          <div class="px-4 py-3 bg-brand-navy text-white flex items-center justify-between gap-2">
            <div class="flex items-center gap-2 min-w-0">
              <svg class="w-4 h-4 text-brand-goldLight flex-shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
              <span class="text-xs sm:text-sm font-bold truncate">Vị trí trên Google Maps</span>
            </div>
            <a href="https://www.google.com/maps/search/?api=1&query=248+D%C6%B0%C6%A1ng+%C4%90%C3%ACnh+Ngh%E1%BB%87,+An+H%E1%BA%A3i,+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-brand-goldLight hover:underline whitespace-nowrap">
              Mở chỉ đường &rarr;
            </a>
          </div>
          <div class="w-full h-[300px] sm:h-[340px] flex-1 bg-slate-100">
            <iframe
              title="Bản đồ Công ty TNHH Xây Dựng Thương Mại Hải Cường Thịnh - 248 Dương Đình Nghệ, Đà Nẵng"
              src="https://maps.google.com/maps?q=248+D%C6%B0%C6%A1ng+%C4%90%C3%ACnh+Ngh%E1%BB%87,+An+H%E1%BA%A3i,+%C4%90%C3%A0+N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
              width="100%"
              height="100%"
              style="border:0;"
              allowfullscreen=""
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade"
            ></iframe>
          </div>
        </div>

        <!-- Cột phải (5 phần): Khung Fanpage Facebook trực tiếp ngoài trang chủ -->
        <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
          <div class="px-4 py-3 bg-[#1877F2] text-white flex items-center justify-between gap-2">
            <div class="flex items-center gap-2">
              <svg class="w-4 h-4 flex-shrink-0" fill="currentColor" viewBox="0 0 24 24"><path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/></svg>
              <span class="text-xs sm:text-sm font-bold">Fanpage Facebook Chính Thức</span>
            </div>
            <span class="text-[11px] text-white/90">haicuongthinh.com</span>
          </div>

          <!-- Giao diện Card Fanpage trực quan chuẩn Facebook Page Plugin (dễ thay iframe Page Plugin trên Flatsome) -->
          <div class="p-4 sm:p-5 flex-1 flex flex-col justify-between space-y-4">
            <!-- Ảnh bìa Fanpage lấy từ ảnh thi công thực tế -->
            <div class="relative rounded-lg overflow-hidden border border-slate-200">
              <img
                src="https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff=w900"
                data-fallback="https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w900"
                onerror="handleDriveImageError(this, 'Fanpage Hai Cuong Thinh')"
                referrerpolicy="no-referrer"
                alt="Ảnh bìa Fanpage Công ty Xây dựng Hải Cường Thịnh"
                class="w-full h-36 sm:h-40 object-cover"
              />
              <div class="absolute inset-0 bg-gradient-to-t from-brand-navyDark/85 via-brand-navyDark/30 to-transparent"></div>
              <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3">
                <div class="w-12 h-12 rounded-lg bg-white p-1 shadow-md flex-shrink-0">
                  <svg class="w-full h-full" viewBox="0 0 64 64" fill="none"><rect width="64" height="64" rx="10" fill="#0F2C59"/><path d="M11 47V24.5L32 12L53 24.5V47H45.5V28.5L32 20.5L18.5 28.5V47H11Z" fill="#C88A2E"/><path d="M23 47V29H28.5V36H35.5V29H41V47H35.5V40.5H28.5V47H23Z" fill="#FFFFFF"/></svg>
                </div>
                <div class="min-w-0 text-white">
                  <h3 class="text-sm font-bold leading-snug">Xây Dựng Hải Cường Thịnh - Đà Nẵng</h3>
                  <p class="text-[11px] text-white/85">Công ty Xây dựng &amp; Thiết kế kiến trúc</p>
                </div>
              </div>
            </div>

            <div class="text-xs sm:text-[13px] text-slate-600 leading-relaxed space-y-1.5">
              <p>Cập nhật tiến độ thi công hàng ngày tại các công trình Đà Nẵng, mẫu thiết kế mới và bảng giá xây dựng trọn gói.</p>
              <p class="text-slate-500"><strong>Địa chỉ:</strong> 248 Dương Đình Nghệ, Phường An Hải, TP Đà Nẵng</p>
            </div>

            <div class="grid grid-cols-2 gap-2.5 pt-1">
              <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer" class="inline-flex items-center justify-center gap-1.5 py-2.5 px-3 rounded-lg bg-[#1877F2] hover:bg-[#1465D1] text-white font-semibold text-xs transition-colors">
                <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 24 24"><path d="M14 9V5a3 3 0 00-3-3l-4 9v11h11.28a2 2 0 002-1.7l1.38-9a2 2 0 00-2-2.3H14zM7 22H4a2 2 0 01-2-2v-7a2 2 0 012-2h3"/></svg>
                <span>Thích Trang</span>
              </a>
              <a href="https://zalo.me/0934783967" target="_blank" rel="noopener noreferrer" class="inline-flex items-center justify-center gap-1.5 py-2.5 px-3 rounded-lg bg-brand-navy hover:bg-brand-navyLight text-white font-semibold text-xs transition-colors">
                <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M8 10h.01M12 10h.01M16 10h.01M9 16H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-5l-5 5v-5z"/></svg>
                <span>Nhắn Tin Tư Vấn</span>
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== FLATSOME FOOTER ==================== -->
  <footer class="bg-brand-navyDark text-slate-300 pt-12 pb-6">
    <div class="hct-container">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8 pb-10 border-b border-white/10">

        <!-- Cột 1: Thông tin doanh nghiệp -->
        <div class="lg:col-span-5 space-y-3.5">
          <div class="flex items-center gap-2.5">
            <svg class="w-9 h-9 flex-shrink-0" viewBox="0 0 64 64" fill="none">
              <rect width="64" height="64" rx="12" fill="#0F2C59"/>
              <path d="M11 47V24.5L32 12L53 24.5V47H45.5V28.5L32 20.5L18.5 28.5V47H11Z" fill="#C88A2E"/>
              <path d="M23 47V29H28.5V36H35.5V29H41V47H35.5V40.5H28.5V47H23Z" fill="#FFFFFF"/>
            </svg>
            <div>
              <h3 class="text-sm sm:text-base font-extrabold text-white leading-snug">CÔNG TY TNHH XÂY DỰNG THƯƠNG MẠI HẢI CƯỜNG THỊNH</h3>
              <p class="text-[11px] text-brand-goldLight font-medium">Website: haicuongthinh.com</p>
            </div>
          </div>

          <ul class="space-y-2 text-xs sm:text-[13px] leading-relaxed">
            <li><strong class="text-white">Mã số thuế:</strong> 0402073706</li>
            <li><strong class="text-white">Trụ sở chính:</strong> 248 Dương Đình Nghệ, Phường An Hải, TP Đà Nẵng</li>
            <li><strong class="text-white">Hotline / Zalo:</strong> <a href="tel:0934783967" class="text-brand-goldLight font-semibold hover:underline">0934.783.967</a></li>
            <li><strong class="text-white">Email:</strong> lienhe@haicuongthinh.com</li>
          </ul>
        </div>

        <!-- Cột 2: Lĩnh vực hoạt động -->
        <div class="lg:col-span-3 space-y-3">
          <h4 class="text-sm font-bold text-white uppercase tracking-wide">Lĩnh Vực Hoạt Động</h4>
          <ul class="space-y-2 text-xs sm:text-[13px]">
            <li><a href="#linh-vuc-hoat-dong" class="hover:text-brand-goldLight transition-colors">Thiết kế Kiến trúc – Nội thất</a></li>
            <li><a href="#linh-vuc-hoat-dong" class="hover:text-brand-goldLight transition-colors">Thi công xây dựng phần thô</a></li>
            <li><a href="#linh-vuc-hoat-dong" class="hover:text-brand-goldLight transition-colors">Thi công hoàn thiện trọn gói</a></li>
            <li><a href="#linh-vuc-hoat-dong" class="hover:text-brand-goldLight transition-colors">Thi công nội thất &amp; Cải tạo</a></li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục nhanh -->
        <div class="lg:col-span-2 space-y-3">
          <h4 class="text-sm font-bold text-white uppercase tracking-wide">Danh Mục</h4>
          <ul class="space-y-2 text-xs sm:text-[13px]">
            <li><a href="#cong-trinh-thuc-te" class="hover:text-brand-goldLight transition-colors">Công trình thực tế</a></li>
            <li><a href="#du-an-da-nang" class="hover:text-brand-goldLight transition-colors">Dự án tại Đà Nẵng</a></li>
            <li><a href="#doi-tac" class="hover:text-brand-goldLight transition-colors">Đối tác cung ứng</a></li>
            <li><a href="#tin-tuc" class="hover:text-brand-goldLight transition-colors">Tin tức xây dựng</a></li>
          </ul>
        </div>

        <!-- Cột 4: Báo giá -->
        <div class="lg:col-span-2 space-y-3">
          <h4 class="text-sm font-bold text-white uppercase tracking-wide">Báo Giá</h4>
          <ul class="space-y-2 text-xs sm:text-[13px]">
            <li><a href="#bao-gia" onclick="prefillQuote('Thiết kế kiến trúc')" class="hover:text-brand-goldLight transition-colors">Báo giá thiết kế</a></li>
            <li><a href="#bao-gia" onclick="prefillQuote('Thi công phần thô')" class="hover:text-brand-goldLight transition-colors">Báo giá phần thô</a></li>
            <li><a href="#bao-gia" onclick="prefillQuote('Thi công hoàn thiện')" class="hover:text-brand-goldLight transition-colors">Báo giá hoàn thiện</a></li>
            <li><a href="#bao-gia" onclick="prefillQuote('Thi công trọn gói')" class="hover:text-brand-goldLight transition-colors">Báo giá trọn gói</a></li>
          </ul>
        </div>
      </div>

      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400">
        <p>Copyright 2026 &copy; CÔNG TY TNHH XÂY DỰNG THƯƠNG MẠI HẢI CƯỜNG THỊNH.</p>
        <p>Thiết kế giao diện chuẩn Flatsome — haicuongthinh.com</p>
      </div>
    </div>
  </footer>

  <!-- ==================== MODAL XEM CHI TIẾT CÔNG TRÌNH / BÀI VIẾT ==================== -->
  <div id="detail-modal" class="fixed inset-0 z-[70] hidden items-center justify-center p-4 bg-slate-900/75 backdrop-blur-sm">
    <div class="bg-white rounded-xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl relative">
      <button id="modal-close-btn" type="button" class="absolute top-3 right-3 z-10 w-9 h-9 rounded-full bg-brand-navyDark/75 hover:bg-brand-gold text-white flex items-center justify-center transition-colors" aria-label="Đóng cửa sổ">
        <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/></svg>
      </button>
      <div class="bg-slate-100">
        <img id="modal-img" src="" alt="" referrerpolicy="no-referrer" class="w-full max-h-[380px] object-cover" />
      </div>
      <div class="p-5 sm:p-6 space-y-3">
        <p id="modal-subtitle" class="text-xs font-bold uppercase tracking-wider text-brand-gold"></p>
        <h3 id="modal-title" class="text-lg sm:text-xl font-extrabold text-brand-navy leading-snug"></h3>
        <p id="modal-desc" class="text-sm text-slate-600 leading-relaxed"></p>
        <div class="pt-3 flex flex-wrap items-center gap-3 border-t border-slate-100">
          <a href="#bao-gia" onclick="closeDetailModal()" class="px-5 py-2.5 rounded-lg bg-brand-gold hover:bg-brand-goldLight text-white font-semibold text-xs sm:text-sm transition-colors">
            Yêu cầu báo giá công trình tương tự
          </a>
          <a href="tel:0934783967" class="px-5 py-2.5 rounded-lg bg-brand-navy hover:bg-brand-navyLight text-white font-semibold text-xs sm:text-sm transition-colors">
            Gọi 0934.783.967
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- ==================== CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE ==================== -->
  <!-- Tương thích hoàn hảo trên cả máy tính và điện thoại, đặt gọn góc phải dưới không gây tràn viền -->
  <div class="fixed bottom-4 right-3.5 sm:bottom-6 sm:right-5 z-40 flex flex-col items-end gap-2.5">

    <!-- Nút Facebook -->
    <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer" aria-label="Liên hệ Facebook Hải Cường Thịnh" class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#1465D1] text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition-all">
      <svg class="w-5 h-5 flex-shrink-0" fill="currentColor" viewBox="0 0 24 24">
        <path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/>
      </svg>
      <span class="hidden sm:inline text-xs font-bold pr-1 whitespace-nowrap">Facebook</span>
    </a>

    <!-- Nút Zalo -->
    <a href="https://zalo.me/0934783967" target="_blank" rel="noopener noreferrer" aria-label="Chat Zalo 0934.783.967" class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0055D4] text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition-all">
      <span class="w-5 h-5 rounded-full bg-white text-[#0068FF] font-extrabold text-[10px] flex items-center justify-center flex-shrink-0 leading-none">Zalo</span>
      <span class="hidden sm:inline text-xs font-bold pr-1 whitespace-nowrap">Chat Zalo</span>
    </a>

    <!-- Nút Hotline nổi bật -->
    <a href="tel:0934783967" aria-label="Gọi Hotline 0934.783.967" class="hotline-pulse flex items-center gap-2 bg-brand-gold hover:bg-brand-goldLight text-white rounded-full shadow-xl p-3 sm:px-4 sm:py-2.5 transition-all">
      <svg class="w-5 h-5 flex-shrink-0" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/>
      </svg>
      <span class="hidden sm:inline text-xs font-extrabold pr-1 whitespace-nowrap">0934.783.967</span>
    </a>

    <!-- Nút Lên đầu trang -->
    <button id="scroll-top-btn" type="button" onclick="window.scrollTo({top: 0, behavior: 'smooth'})" aria-label="Lên đầu trang" class="hidden w-10 h-10 rounded-full bg-brand-navy/90 hover:bg-brand-navy text-white shadow-md items-center justify-center transition-all">
      <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M5 15l7-7 7 7"/></svg>
    </button>
  </div>

  <!-- ==================== JAVASCRIPT LOGIC ==================== -->
  <script>
    /**
     * Cơ chế dự phòng tải ảnh Google Drive đa tầng:
     * 1. Ảnh chính: lh3.googleusercontent.com/d/{ID}
     * 2. Dự phòng 1: drive.google.com/thumbnail?id={ID}&sz=w1000
     * 3. Dự phòng 2: Placehold.co đúng tông màu thương hiệu Hải Cường Thịnh
     */
    function handleDriveImageError(imgEl, labelText) {
      try {
        const step = imgEl.getAttribute('data-err-step') || '0';
        const fallbackUrl = imgEl.getAttribute('data-fallback');
        if (step === '0' && fallbackUrl) {
          imgEl.setAttribute('data-err-step', '1');
          imgEl.src = fallbackUrl;
        } else {
          imgEl.onerror = null;
          const safeText = encodeURIComponent(labelText || 'Hai Cuong Thinh');
          imgEl.src = 'https://placehold.co/800x600/0F2C59/E0A84B?text=' + safeText;
        }
      } catch (e) {
        imgEl.onerror = null;
      }
    }

    /**
     * DỮ LIỆU 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG (Bộ 1 Google Drive người dùng cung cấp)
     * Phân loại theo đúng danh mục sản phẩm/công trình chuẩn web mẫu tintruongthinh.com
     */
    const constructionProducts = [
      {
        id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        title: 'Thi Công Phần Thô & Kết Cấu Nhà Phố Hiện Đại',
        category: 'nha-pho',
        categoryName: 'Nhà phố',
        desc: 'Hạng mục thi công kết cấu móng, cột dầm sàn bê tông cốt thép đạt chuẩn kỹ thuật, đảm bảo độ vững chắc và tiến độ bàn giao đúng cam kết.'
      },
      {
        id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
        title: 'Thi Công Xây Dựng Trọn Gói Biệt Thự 2 Mặt Tiền',
        category: 'biet-thu',
        categoryName: 'Biệt thự',
        desc: 'Thiết kế và thi công trọn gói biệt thự phong cách hiện đại với không gian thông thoáng, vật tư hoàn thiện cao cấp và giám sát kỹ thuật 24/7.'
      },
      {
        id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
        title: 'Thi Công Khách Sạn & Căn Hộ Cho Thuê Cao Cấp',
        category: 'khach-san',
        categoryName: 'Khách sạn – Căn hộ',
        desc: 'Giải pháp thi công tối ưu công năng khai thác phòng, hệ thống M&E đồng bộ, chống thấm và cách âm tiêu chuẩn cho khách sạn – căn hộ dịch vụ.'
      },
      {
        id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
        title: 'Thi Công Hoàn Thiện Mặt Tiền Nhà Phố 3 Tầng',
        category: 'nha-pho',
        categoryName: 'Nhà phố',
        desc: 'Hoàn thiện tô trát, sơn nước ngoại thất chống thấm, lắp đặt lan can và hệ cửa nhôm kính cao cấp đảm bảo thẩm mỹ bền đẹp với khí hậu miền Trung.'
      },
      {
        id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
        title: 'Thi Công Nội Thất Văn Phòng & Showroom Thương Mại',
        category: 'van-phong',
        categoryName: 'Văn phòng & Nội thất',
        desc: 'Thi công hoàn thiện không gian làm việc hiện đại, trần thạch cao, hệ thống chiếu sáng, vách kính và nội thất gỗ công nghiệp chuẩn xác theo bản vẽ 3D.'
      },
      {
        id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
        title: 'Thi Công Căn Hộ Dịch Vụ & Phòng Trọ Cao Cấp',
        category: 'khach-san',
        categoryName: 'Khách sạn – Căn hộ',
        desc: 'Triển khai thi công nhanh gọn, tối ưu chi phí đầu tư, đảm bảo an toàn PCCC và công năng sử dụng bền bỉ cho mô hình căn hộ cho thuê.'
      },
      {
        id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
        title: 'Thi Công Biệt Thự Sân Vườn Phong Cách Tân Cổ Điển',
        category: 'biet-thu',
        categoryName: 'Biệt thự',
        desc: 'Chăm chút tỉ mỉ từng đường nét phào chỉ, kết cấu mái và cảnh quan sân vườn mang lại không gian sống sang trọng, đẳng cấp cho gia chủ.'
      },
      {
        id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
        title: 'Thi Công Hoàn Thiện Nội Thất Nhà Phố Trọn Gói',
        category: 'van-phong',
        categoryName: 'Văn phòng & Nội thất',
        desc: 'Hoàn thiện ốp lát gạch khổ lớn, hệ tủ bếp, cầu thang và trang thiết bị vệ sinh đồng bộ giúp khách hàng dọn vào ở ngay khi bàn giao.'
      },
      {
        id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
        title: 'Cải Tạo & Nâng Tầng Nhà Phố Khu Vực Trung Tâm',
        category: 'nha-pho',
        categoryName: 'Nhà phố',
        desc: 'Khảo sát kiểm định kết cấu cũ kỹ lưỡng, gia cố móng cột an toàn và cải tạo công năng hiện đại giúp lột xác hoàn toàn không gian nhà ở.'
      }
    ];

    /**
     * DỮ LIỆU 10 ẢNH DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (Bộ 2 Google Drive người dùng cung cấp)
     */
    const danangProjects = [
      {
        id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
        title: 'Nhà Phố Hiện Đại — An Hải, Sơn Trà',
        location: 'Phường An Hải, TP Đà Nẵng',
        desc: 'Công trình thi công trọn gói nhà phố 3 tầng gần biển Mỹ Khê, thiết kế tối ưu thông gió tự nhiên và ánh sáng giếng trời.'
      },
      {
        id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
        title: 'Căn Hộ Dịch Vụ — Dương Đình Nghệ',
        location: 'Quận Sơn Trà, TP Đà Nẵng',
        desc: 'Dự án xây dựng tòa nhà căn hộ cho thuê 6 tầng đầy đủ tiện nghi, hoàn thiện đúng tiến độ bàn giao cho chủ đầu tư.'
      },
      {
        id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
        title: 'Biệt Thự Khu Đô Thị Hòa Xuân',
        location: 'KĐT Hòa Xuân, TP Đà Nẵng',
        desc: 'Thi công phần thô và hoàn thiện biệt thự hiện đại sân vườn rộng rãi tại khu sinh thái Hòa Xuân.'
      },
      {
        id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
        title: 'Khách Sạn Mini — Khu Mỹ An',
        location: 'Ngũ Hành Sơn, TP Đà Nẵng',
        desc: 'Thiết kế và thi công khách sạn quy mô 18 phòng đạt chuẩn thẩm mỹ cao, tối ưu chi phí vận hành.'
      },
      {
        id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
        title: 'Nhà Phố 4 Tầng — Quận Hải Châu',
        location: 'Quận Hải Châu, TP Đà Nẵng',
        desc: 'Công trình nhà ở kết hợp văn phòng công ty tại khu vực trung tâm thành phố Đà Nẵng.'
      },
      {
        id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
        title: 'Biệt Thự Phố — Khu Nam Việt Á',
        location: 'Ngũ Hành Sơn, TP Đà Nẵng',
        desc: 'Thi công trọn gói biệt thự phố 3 tầng phong cách tối giản sang trọng, vật tư hoàn thiện cao cấp.'
      },
      {
        id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
        title: 'Văn Phòng & Showroom — Thanh Khê',
        location: 'Quận Thanh Khê, TP Đà Nẵng',
        desc: 'Thi công cải tạo và hoàn thiện nội thất trụ sở văn phòng giao dịch chuyên nghiệp, hiện đại.'
      },
      {
        id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
        title: 'Nhà Phố 3 Tầng — Khu Phước Lý',
        location: 'Quận Cẩm Lệ, TP Đà Nẵng',
        desc: 'Thi công xây dựng trọn gói nhà phố gia đình 3 tầng, tối ưu không gian sinh hoạt chung và phòng ngủ.'
      },
      {
        id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
        title: 'Căn Hộ Cao Cấp View Sông Hàn',
        location: 'Sơn Trà, TP Đà Nẵng',
        desc: 'Thi công hoàn thiện nội thất và mặt đứng tòa căn hộ dịch vụ đón gió sông Hàn mát mẻ quanh năm.'
      },
      {
        id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
        title: 'Nhà Phố Hiện Đại — Liên Chiểu',
        location: 'Quận Liên Chiểu, TP Đà Nẵng',
        desc: 'Thi công phần thô và nhân công hoàn thiện nhà phố 2 tầng 1 tum với tiến độ nhanh và chất lượng đảm bảo.'
      }
    ];

    /**
     * DỮ LIỆU 4 BÀI VIẾT / TIN TỨC TRANG CHỦ (Chuẩn phong cách tintruongthinh.com)
     */
    const homepageArticles = [
      {
        title: 'Hướng Dẫn Bảo Dưỡng Bê Tông Móng Đúng Kỹ Thuật Khi Xây Nhà',
        date: '14/11/2026',
        imgId: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        excerpt: 'Bảo dưỡng bê tông đúng quy trình giúp kết cấu móng đạt cường độ chịu lực tối đa, hạn chế nứt chân chim và tăng tuổi thọ công trình.',
        content: 'Sau khi đổ bê tông móng và sàn, việc giữ ẩm liên tục trong 7 ngày đầu đóng vai trò quyết định đến mác bê tông thực tế. Tại các công trình của Hải Cường Thịnh, kỹ sư luôn bố trí tưới nước bảo dưỡng định kỳ, che phủ bao tải giữ ẩm vào những ngày nắng gắt tại Đà Nẵng nhằm ngăn chặn hiện tượng mất nước đột ngột gây nứt bề mặt.'
      },
      {
        title: 'Kinh Nghiệm Chọn Nhà Thầu Xây Nhà Trọn Gói Uy Tín Tại Đà Nẵng',
        date: '09/11/2026',
        imgId: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
        excerpt: '05 tiêu chí quan trọng giúp chủ đầu tư đánh giá năng lực nhà thầu, minh bạch chủng loại vật tư và tránh phát sinh chi phí khi thi công.',
        content: 'Khi lựa chọn nhà thầu xây dựng trọn gói, gia chủ cần kiểm tra rõ pháp lý doanh nghiệp, tham quan công trình thực tế đang thi công, đối chiếu bảng vật tư chi tiết (thép, xi măng, dây điện, sơn, thiết bị vệ sinh) và điều khoản bảo hành kết cấu rõ ràng trong hợp đồng.'
      },
      {
        title: 'Lưu Ý Chống Thấm Mùa Mưa Bão Cho Nhà Phố Ven Biển Miền Trung',
        date: '02/11/2026',
        imgId: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
        excerpt: 'Giải pháp xử lý chống thấm sàn mái, tường vách giáp ranh và khu vực ban công bền vững trước thời tiết khắc nghiệt tại Đà Nẵng.',
        content: 'Khí hậu ven biển Đà Nẵng có độ ẩm cao và mưa bão lớn cuối năm. Do đó, công tác xử lý cổ ống xuyên sàn, tạo dốc thoát nước mái, sử dụng phụ gia chống thấm Sika kết hợp lưới thủy tinh gia cường góc chân tường là bắt buộc để ngôi nhà luôn khô ráo lâu dài.'
      },
      {
        title: 'Cập Nhật Đơn Giá Thi Công Phần Thô & Hoàn Thiện Mới Nhất',
        date: '25/10/2026',
        imgId: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
        excerpt: 'Cách tính diện tích xây dựng chuẩn xác theo hệ số móng, thân, mái giúp gia chủ chủ động dự trù ngân sách trước khi khởi công.',
        content: 'Đơn giá xây dựng phụ thuộc vào quy mô diện tích sàn, điều kiện hẻm vận chuyển vật tư, phong cách kiến trúc (hiện đại hay tân cổ điển) và gói vật tư hoàn thiện. Quý khách có thể điền thông tin tại mục Báo Giá phía trên để kỹ sư Hải Cường Thịnh bóc tách miễn phí dự toán sát thực tế nhất.'
      }
    ];

    /**
     * Render danh sách 9 công trình thi công thực tế (không dán nhãn trên ảnh, tên đầy đủ không bị cắt)
     */
    function renderProducts(filterKey) {
      const grid = document.getElementById('products-grid');
      if (!grid) return;

      const filtered = filterKey === 'all'
        ? constructionProducts
        : constructionProducts.filter(item => item.category === filterKey);

      grid.innerHTML = filtered.map((item) => {
        const primaryImg = 'https://lh3.googleusercontent.com/d/' + item.id + '=w1000';
        const fallbackImg = 'https://drive.google.com/thumbnail?id=' + item.id + '&sz=w1000';
        return `
          <article class="group bg-white rounded-xl border border-slate-200/80 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-gold transition-all flex flex-col cursor-pointer" onclick="openProjectModal('${item.id}', '${escapeQuote(item.title)}', '${escapeQuote(item.categoryName)}', '${escapeQuote(item.desc)}')">
            <div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">
              <img
                src="${primaryImg}"
                data-fallback="${fallbackImg}"
                onerror="handleDriveImageError(this, '${escapeQuote(item.categoryName)}')"
                referrerpolicy="no-referrer"
                loading="lazy"
                alt="${escapeQuote(item.title)}"
                class="w-full h-full object-cover card-img-zoom"
              />
            </div>
            <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
              <div>
                <p class="text-[11px] font-semibold text-brand-gold mb-1">${item.categoryName}</p>
                <h3 class="text-[13px] sm:text-[15px] font-bold text-brand-navy group-hover:text-brand-gold transition-colors leading-snug break-words">
                  ${item.title}
                </h3>
              </div>
              <div class="mt-2.5 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs text-slate-500">
                <span>Xem chi tiết</span>
                <span class="text-brand-gold font-bold">&rarr;</span>
              </div>
            </div>
          </article>
        `;
      }).join('');
    }

    /**
     * Lọc danh mục sản phẩm / công trình thực tế
     */
    function filterProducts(category) {
      renderProducts(category);
      const buttons = document.querySelectorAll('#product-filter-bar .filter-btn');
      buttons.forEach(btn => {
        const isActive = btn.getAttribute('data-filter') === category;
        if (isActive) {
          btn.classList.remove('bg-brand-surface', 'text-slate-700', 'border', 'border-slate-200');
          btn.classList.add('bg-brand-navy', 'text-white');
        } else {
          btn.classList.remove('bg-brand-navy', 'text-white');
          btn.classList.add('bg-brand-surface', 'text-slate-700', 'border', 'border-slate-200');
        }
      });
    }

    /**
     * Render danh sách 10 dự án tiêu biểu tại Đà Nẵng (2 cột trên điện thoại, 5 cột trên máy tính)
     */
    function renderDanangProjects() {
      const grid = document.getElementById('danang-projects-grid');
      if (!grid) return;

      grid.innerHTML = danangProjects.map((proj) => {
        const primaryImg = 'https://lh3.googleusercontent.com/d/' + proj.id + '=w900';
        const fallbackImg = 'https://drive.google.com/thumbnail?id=' + proj.id + '&sz=w900';
        return `
          <article class="group bg-white rounded-xl border border-slate-200/80 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-gold transition-all flex flex-col cursor-pointer" onclick="openProjectModal('${proj.id}', '${escapeQuote(proj.title)}', '${escapeQuote(proj.location)}', '${escapeQuote(proj.desc)}')">
            <div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">
              <img
                src="${primaryImg}"
                data-fallback="${fallbackImg}"
                onerror="handleDriveImageError(this, 'Du An Da Nang')"
                referrerpolicy="no-referrer"
                loading="lazy"
                alt="${escapeQuote(proj.title)}"
                class="w-full h-full object-cover card-img-zoom"
              />
            </div>
            <div class="p-3 flex-1 flex flex-col justify-between">
              <h3 class="text-[12.5px] sm:text-[13.5px] font-bold text-brand-navy group-hover:text-brand-gold transition-colors leading-snug break-words">
                ${proj.title}
              </h3>
              <p class="text-[11px] text-slate-500 mt-1.5 leading-snug">
                ${proj.location}
              </p>
            </div>
          </article>
        `;
      }).join('');
    }

    /**
     * Render danh mục bài viết trang chủ
     */
    function renderArticles() {
      const grid = document.getElementById('articles-grid');
      if (!grid) return;

      grid.innerHTML = homepageArticles.map((art, index) => {
        const primaryImg = 'https://lh3.googleusercontent.com/d/' + art.imgId + '=w800';
        const fallbackImg = 'https://drive.google.com/thumbnail?id=' + art.imgId + '&sz=w800';
        return `
          <article class="group bg-brand-surface rounded-xl border border-slate-200/80 overflow-hidden hover:shadow-md hover:border-brand-gold transition-all flex flex-col cursor-pointer" onclick="openArticleModal(${index})">
            <div class="w-full aspect-[16/10] overflow-hidden bg-slate-200">
              <img
                src="${primaryImg}"
                data-fallback="${fallbackImg}"
                onerror="handleDriveImageError(this, 'Tin Tuc Xay Dung')"
                referrerpolicy="no-referrer"
                loading="lazy"
                alt="${escapeQuote(art.title)}"
                class="w-full h-full object-cover card-img-zoom"
              />
            </div>
            <div class="p-3.5 sm:p-4 flex-1 flex flex-col justify-between">
              <div>
                <p class="text-[11px] text-slate-500 mb-1.5">${art.date}</p>
                <h3 class="text-[13px] sm:text-[14.5px] font-bold text-brand-navy group-hover:text-brand-gold transition-colors leading-snug break-words">
                  ${art.title}
                </h3>
                <p class="hidden sm:block text-xs text-slate-600 mt-2 leading-relaxed">
                  ${art.excerpt}
                </p>
              </div>
              <span class="mt-3 inline-flex items-center gap-1 text-xs font-semibold text-brand-gold">
                Đọc tiếp <span>&rarr;</span>
              </span>
            </div>
          </article>
        `;
      }).join('');
    }

    function escapeQuote(str) {
      return String(str || '').replace(/'/g, "\\'").replace(/"/g, '&quot;');
    }

    /**
     * Điều khiển Modal xem chi tiết công trình / bài viết
     */
    function openProjectModal(imgId, title, subtitle, desc) {
      const modal = document.getElementById('detail-modal');
      const img = document.getElementById('modal-img');
      img.removeAttribute('data-err-step');
      img.setAttribute('data-fallback', 'https://drive.google.com/thumbnail?id=' + imgId + '&sz=w1200');
      img.onerror = function() { handleDriveImageError(img, title); };
      img.src = 'https://lh3.googleusercontent.com/d/' + imgId + '=w1200';
      img.alt = title;

      document.getElementById('modal-subtitle').textContent = subtitle;
      document.getElementById('modal-title').textContent = title;
      document.getElementById('modal-desc').textContent = desc;

      modal.classList.remove('hidden');
      modal.classList.add('flex');
      document.body.style.overflow = 'hidden';
    }

    function openArticleModal(index) {
      const art = homepageArticles[index];
      if (!art) return;
      openProjectModal(art.imgId, art.title, 'Cẩm nang xây dựng — ' + art.date, art.content);
    }

    function closeDetailModal() {
      const modal = document.getElementById('detail-modal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
      document.body.style.overflow = '';
    }

    /**
     * Chọn nhanh loại báo giá khi bấm từ menu hoặc nút dịch vụ
     */
    function prefillQuote(typeValue) {
      const select = document.getElementById('q-type');
      if (select) {
        for (let i = 0; i < select.options.length; i++) {
          if (select.options[i].value === typeValue) {
            select.selectedIndex = i;
            break;
          }
        }
      }
    }

    /**
     * Khởi tạo toàn bộ tương tác sau khi DOM sẵn sàng
     */
    document.addEventListener('DOMContentLoaded', function() {
      // 1. Render các lưới sản phẩm, dự án Đà Nẵng và bài viết
      renderProducts('all');
      renderDanangProjects();
      renderArticles();

      // 2. Banner Slider 2 ảnh tự động trượt + hỗ trợ vuốt cảm ứng trên điện thoại
      const track = document.getElementById('banner-track');
      const dots = document.querySelectorAll('.banner-dot');
      const prevBtn = document.getElementById('banner-prev');
      const nextBtn = document.getElementById('banner-next');
      const sliderEl = document.getElementById('hero-slider');
      let currentSlide = 0;
      const totalSlides = 2;
      let autoSlideTimer = null;

      function goToSlide(idx) {
        currentSlide = (idx + totalSlides) % totalSlides;
        if (track) {
          track.style.transform = 'translateX(-' + (currentSlide * 50) + '%)';
        }
        dots.forEach((dot, i) => {
          if (i === currentSlide) {
            dot.classList.remove('w-2.5', 'bg-white/60');
            dot.classList.add('w-7', 'bg-brand-gold');
          } else {
            dot.classList.remove('w-7', 'bg-brand-gold');
            dot.classList.add('w-2.5', 'bg-white/60');
          }
        });
      }

      function startAutoSlide() {
        stopAutoSlide();
        autoSlideTimer = setInterval(() => goToSlide(currentSlide + 1), 5000);
      }

      function stopAutoSlide() {
        if (autoSlideTimer) clearInterval(autoSlideTimer);
      }

      if (prevBtn) prevBtn.addEventListener('click', () => { goToSlide(currentSlide - 1); startAutoSlide(); });
      if (nextBtn) nextBtn.addEventListener('click', () => { goToSlide(currentSlide + 1); startAutoSlide(); });
      dots.forEach(dot => {
        dot.addEventListener('click', () => {
          goToSlide(parseInt(dot.getAttribute('data-slide'), 10));
          startAutoSlide();
        });
      });

      // Hỗ trợ vuốt trái / phải trên điện thoại cho Banner
      let touchStartX = 0;
      if (sliderEl) {
        sliderEl.addEventListener('touchstart', (e) => {
          touchStartX = e.changedTouches[0].screenX;
          stopAutoSlide();
        }, { passive: true });
        sliderEl.addEventListener('touchend', (e) => {
          const deltaX = e.changedTouches[0].screenX - touchStartX;
          if (deltaX < -40) goToSlide(currentSlide + 1);
          if (deltaX > 40) goToSlide(currentSlide - 1);
          startAutoSlide();
        }, { passive: true });
        sliderEl.addEventListener('mouseenter', stopAutoSlide);
        sliderEl.addEventListener('mouseleave', startAutoSlide);
      }
      startAutoSlide();

      // 3. Menu Mobile Drawer (Flatsome Off-Canvas)
      const mobileBtn = document.getElementById('mobile-menu-btn');
      const mobileDrawer = document.getElementById('mobile-drawer');
      const mobileOverlay = document.getElementById('mobile-drawer-overlay');
      const mobileClose = document.getElementById('mobile-drawer-close');
      const mobileLinks = document.querySelectorAll('.mobile-nav-link');

      function openMobileMenu() {
        mobileOverlay.classList.remove('hidden');
        setTimeout(() => mobileOverlay.classList.remove('opacity-0'), 10);
        mobileDrawer.classList.remove('-translate-x-full');
        document.body.style.overflow = 'hidden';
      }

      function closeMobileMenu() {
        mobileOverlay.classList.add('opacity-0');
        mobileDrawer.classList.add('-translate-x-full');
        setTimeout(() => mobileOverlay.classList.add('hidden'), 300);
        document.body.style.overflow = '';
      }

      if (mobileBtn) mobileBtn.addEventListener('click', openMobileMenu);
      if (mobileClose) mobileClose.addEventListener('click', closeMobileMenu);
      if (mobileOverlay) mobileOverlay.addEventListener('click', closeMobileMenu);
      mobileLinks.forEach(link => link.addEventListener('click', closeMobileMenu));

      // 4. Đóng Modal khi nhấn nút X hoặc bấm ra nền tối
      const modalCloseBtn = document.getElementById('modal-close-btn');
      const detailModal = document.getElementById('detail-modal');
      if (modalCloseBtn) modalCloseBtn.addEventListener('click', closeDetailModal);
      if (detailModal) {
        detailModal.addEventListener('click', (e) => {
          if (e.target === detailModal) closeDetailModal();
        });
      }

      // 5. Xử lý Form Yêu cầu Báo giá (hiển thị thông báo trong trang, không dùng alert)
      const quoteForm = document.getElementById('quote-form');
      const feedbackBox = document.getElementById('quote-feedback');
      if (quoteForm && feedbackBox) {
        quoteForm.addEventListener('submit', function(e) {
          e.preventDefault();
          const name = document.getElementById('q-name').value.trim();
          const phone = document.getElementById('q-phone').value.trim();
          const type = document.getElementById('q-type').value;

          if (!name || !phone) {
            feedbackBox.className = 'rounded-lg p-3.5 text-xs sm:text-sm font-medium bg-red-50 text-red-700 border border-red-200';
            feedbackBox.textContent = 'Vui lòng nhập đầy đủ Họ và tên cùng Số điện thoại để Hải Cường Thịnh liên hệ báo giá.';
            feedbackBox.classList.remove('hidden');
            return;
          }

          feedbackBox.className = 'rounded-lg p-3.5 text-xs sm:text-sm font-medium bg-emerald-50 text-emerald-800 border border-emerald-200';
          feedbackBox.innerHTML = 'Cảm ơn <strong>' + name + '</strong>! Yêu cầu báo giá hạng mục <strong>' + type + '</strong> đã được ghi nhận. Kỹ sư Hải Cường Thịnh sẽ liên hệ qua số <strong>' + phone + '</strong> trong thời gian sớm nhất.';
          feedbackBox.classList.remove('hidden');
          quoteForm.reset();
        });
      }

      // 6. Nút cuộn lên đầu trang
      const scrollTopBtn = document.getElementById('scroll-top-btn');
      window.addEventListener('scroll', function() {
        if (!scrollTopBtn) return;
        if (window.scrollY > 360) {
          scrollTopBtn.classList.remove('hidden');
          scrollTopBtn.classList.add('flex');
        } else {
          scrollTopBtn.classList.add('hidden');
          scrollTopBtn.classList.remove('flex');
        }
      }, { passive: true });
    });
  </script>
</body>
</html>
