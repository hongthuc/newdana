<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
  <title>CÔNG TY CỔ PHẦN XÂY DỰNG NEWDANA | Thiết Kế & Thi Công Xây Dựng Đà Nẵng - newdana.com</title>
  <meta name="description" content="CÔNG TY CỔ PHẦN XÂY DỰNG NEWDANA (newdana.com) - Chuyên thiết kế kiến trúc, thi công xây dựng phần thô, hoàn thiện, xây nhà trọn gói, biệt thự, khách sạn, căn hộ tại Đà Nẵng. Hotline: 05956392 - 086755528.">

  <!-- Meta Thumbnail chia sẻ liên kết sử dụng Logo NEWDANA -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://newdana.com/">
  <meta property="og:title" content="CÔNG TY CỔ PHẦN XÂY DỰNG NEWDANA - newdana.com">
  <meta property="og:description" content="Thiết kế & Thi công xây dựng trọn gói Nhà phố, Biệt thự, Khách sạn, Căn hộ, Văn phòng tại Đà Nẵng. Địa chỉ: Tổ 19, Phường Cẩm Lệ, TP. Đà Nẵng.">
  <meta property="og:image" content="https://lh3.googleusercontent.com/d/10DID_zhF4atD9QeooXRz3RcvQADZsI5w=w1200">
  <meta property="og:image:secure_url" content="https://lh3.googleusercontent.com/d/10DID_zhF4atD9QeooXRz3RcvQADZsI5w=w1200">
  <meta property="og:image:alt" content="Logo Công ty Cổ phần Xây dựng NEWDANA">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:title" content="CÔNG TY CỔ PHẦN XÂY DỰNG NEWDANA - newdana.com">
  <meta name="twitter:description" content="Thiết kế & Thi công xây dựng trọn gói chuyên nghiệp tại Đà Nẵng.">
  <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/10DID_zhF4atD9QeooXRz3RcvQADZsI5w=w1200">
  <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/10DID_zhF4atD9QeooXRz3RcvQADZsI5w=w256">

  <!-- Google Fonts: Inter -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
          },
          colors: {
            brand: {
              primary: 'var(--brand-primary)',
              dark: 'var(--brand-dark)',
              light: 'var(--brand-light)',
              accent: 'var(--brand-accent)',
              accentHover: 'var(--brand-accent-hover)',
            }
          }
        }
      }
    }
  </script>

  <style>
    /* =========================================================================
       BIẾN MÀU THƯƠNG HIỆU NEWDANA (Đồng bộ màu Logo - Dễ chỉnh trong Flatsome)
       ========================================================================= */
    :root {
      --brand-primary: #0B3C6D;       /* Xanh Navy đậm chủ đạo theo nhận diện xây dựng NEWDANA */
      --brand-dark: #072748;          /* Xanh đậm cho Topbar & Footer */
      --brand-light: #EEF4FA;         /* Nền xanh nhạt tinh tế */
      --brand-accent: #E67E22;        /* Cam vàng nổi bật tạo điểm nhấn */
      --brand-accent-hover: #CF6D17;  /* Cam đậm khi hover */
      --text-main: #1F2937;
      --text-muted: #4B5563;
      --border-soft: #E5E7EB;
    }

    *, *::before, *::after {
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
      overflow-x: hidden;
      width: 100%;
      max-width: 100%;
    }

    body {
      font-family: 'Inter', sans-serif;
      color: var(--text-main);
      background-color: #FFFFFF;
      margin: 0;
      padding: 0;
      overflow-x: hidden;
      width: 100%;
      max-width: 100%;
      -webkit-font-smoothing: antialiased;
    }

    /* Chiều ngang giao diện trên máy tính đúng 95%, không tràn viền, không lệch phải */
    .container-95 {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }

    @media (min-width: 1024px) {
      .container-95 {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Flatsome Section Title Underline Style */
    .section-heading {
      position: relative;
      display: inline-block;
      padding-bottom: 10px;
    }
    .section-heading::after {
      content: "";
      position: absolute;
      left: 50%;
      bottom: 0;
      transform: translateX(-50%);
      width: 64px;
      height: 3px;
      border-radius: 999px;
      background-color: var(--brand-accent);
    }

    /* Dropdown Menu mượt kiểu Flatsome */
    .nav-item-dropdown {
      position: relative;
    }
    .nav-dropdown-menu {
      opacity: 0;
      visibility: hidden;
      transform: translateY(8px);
      transition: all 0.2s ease;
      position: absolute;
      top: 100%;
      left: 0;
      min-width: 230px;
      background: #FFFFFF;
      border: 1px solid #E5E7EB;
      border-top: 2px solid var(--brand-accent);
      border-radius: 0 0 8px 8px;
      box-shadow: 0 12px 28px rgba(11, 60, 109, 0.12);
      z-index: 60;
      padding: 6px 0;
    }
    .nav-item-dropdown:hover .nav-dropdown-menu,
    .nav-item-dropdown:focus-within .nav-dropdown-menu {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }

    /* Thanh danh mục sản phẩm / dự án gọn đẹp, không vỡ dòng chữ */
    .cat-tab-btn {
      white-space: nowrap;
      transition: all 0.2s ease;
      border: 1px solid #D1D5DB;
      background: #FFFFFF;
      color: #374151;
    }
    .cat-tab-btn:hover {
      border-color: var(--brand-primary);
      color: var(--brand-primary);
      background: var(--brand-light);
    }
    .cat-tab-btn.active {
      background-color: var(--brand-primary);
      border-color: var(--brand-primary);
      color: #FFFFFF;
      box-shadow: 0 4px 10px rgba(11, 60, 109, 0.18);
    }

    /* Banner Slider - 2 ảnh kích thước tuyệt đối bằng nhau trên cả Desktop & Mobile */
    .hero-slider-wrapper {
      position: relative;
      width: 100%;
      overflow: hidden;
      background-color: var(--brand-dark);
    }
    .hero-slides-track {
      display: flex;
      width: 200%;
      transition: transform 0.65s cubic-bezier(0.25, 0.8, 0.25, 1);
    }
    .hero-slide-item {
      width: 50%;
      flex: 0 0 50%;
      position: relative;
      display: flex;
      align-items: center;
      justify-content: center;
      min-height: 330px;
    }
    @media (min-width: 640px) {
      .hero-slide-item {
        min-height: 410px;
      }
    }
    @media (min-width: 1024px) {
      .hero-slide-item {
        min-height: 500px;
      }
    }
    @media (min-width: 1280px) {
      .hero-slide-item {
        min-height: 540px;
      }
    }

    /* Card hover tinh tế kiểu Flatsome */
    .flatsome-card {
      transition: transform 0.25s ease, box-shadow 0.25s ease;
    }
    .flatsome-card:hover {
      transform: translateY(-4px);
      box-shadow: 0 12px 24px rgba(11, 60, 109, 0.10);
    }
    .flatsome-card img {
      transition: transform 0.45s ease;
    }
    .flatsome-card:hover img {
      transform: scale(1.05);
    }

    /* Nút liên hệ nổi bật Pulse animation */
    @keyframes ringPulse {
      0% { transform: scale(1); opacity: 0.7; }
      70% { transform: scale(1.38); opacity: 0; }
      100% { transform: scale(1.38); opacity: 0; }
    }
    .pulse-ring::before {
      content: "";
      position: absolute;
      inset: 0;
      border-radius: 9999px;
      background: inherit;
      z-index: -1;
      animation: ringPulse 2s infinite;
    }

    /* Khoảng trống dưới cùng trên điện thoại cho thanh liên hệ nổi */
    @media (max-width: 767px) {
      body {
        padding-bottom: 62px;
      }
    }
  </style>
</head>
<body class="bg-white text-gray-800">

  <!-- =======================================================================
       TOP BAR (Thông tin liên hệ chuẩn Flatsome - Không thanh chỉnh sửa UXBuilder)
       ======================================================================= -->
  <div class="w-full text-white text-xs" style="background-color: var(--brand-dark);">
    <div class="container-95 py-2 flex flex-wrap items-center justify-between gap-2">
      <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
        <a href="tel:086755528" class="inline-flex items-center gap-1.5 hover:text-amber-300 transition-colors">
          <i class="fa-solid fa-phone text-[11px]" style="color: var(--brand-accent);"></i>
          <span class="font-medium">05956392 - 086755528</span>
        </a>
        <span class="hidden sm:inline text-white/30">|</span>
        <span class="hidden sm:inline-flex items-center gap-1.5 text-white/90">
          <i class="fa-solid fa-globe text-[11px]" style="color: var(--brand-accent);"></i>
          <span>newdana.com</span>
        </span>
        <span class="hidden md:inline text-white/30">|</span>
        <span class="hidden md:inline-flex items-center gap-1.5 text-white/90">
          <i class="fa-solid fa-location-dot text-[11px]" style="color: var(--brand-accent);"></i>
          <span>Tổ 19, Phường Cẩm Lệ, Thành Phố Đà Nẵng</span>
        </span>
      </div>
      <div class="flex items-center gap-3">
        <a href="https://www.facebook.com/profile.php?id=100090930772992" target="_blank" rel="noopener noreferrer" aria-label="Facebook NEWDANA" class="hover:text-amber-300 transition-colors">
          <i class="fa-brands fa-facebook-f"></i>
        </a>
        <a href="https://zalo.me/086755528" target="_blank" rel="noopener noreferrer" aria-label="Zalo NEWDANA" class="font-bold text-[11px] hover:text-amber-300 transition-colors">
          Zalo
        </a>
        <a href="mailto:lienhe@newdana.com" aria-label="Email NEWDANA" class="hover:text-amber-300 transition-colors">
          <i class="fa-solid fa-envelope"></i>
        </a>
      </div>
    </div>
  </div>

  <!-- =======================================================================
       HEADER CHÍNH (Logo gọn nhỏ, Menu 1 hàng không xuống dòng, KHÔNG nút gọi ngay)
       ======================================================================= -->
  <header id="main-header" class="sticky top-0 z-50 w-full bg-white border-b border-gray-200 shadow-sm">
    <div class="container-95 h-16 lg:h-[72px] flex items-center justify-between gap-3">
      <!-- Logo công ty chỉnh gọn nhỏ -->
      <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 focus:outline-none" aria-label="Trang chủ NEWDANA">
        <img
          id="brand-logo-img"
          src="https://lh3.googleusercontent.com/d/10DID_zhF4atD9QeooXRz3RcvQADZsI5w=w400"
          data-drive-id="10DID_zhF4atD9QeooXRz3RcvQADZsI5w"
          alt="Logo CÔNG TY CỔ PHẦN XÂY DỰNG NEWDANA"
          class="h-10 lg:h-11 w-auto max-w-[140px] object-contain rounded"
          onerror="handleDriveImageError(this, 'NEWDANA')"
        >
        <div class="leading-tight">
          <div class="text-sm lg:text-[15px] font-extrabold tracking-tight" style="color: var(--brand-primary);">NEWDANA</div>
          <div class="text-[10px] font-medium text-gray-500 uppercase tracking-wide">Xây dựng Đà Nẵng</div>
        </div>
      </a>

      <!-- Menu máy tính: chữ gọn, viết liền trên 1 hàng, không xuống dòng -->
      <nav aria-label="Menu chính" class="hidden lg:flex items-center justify-end flex-nowrap gap-x-3 xl:gap-x-5">
        <a href="#trang-chu" class="whitespace-nowrap text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight text-gray-800 hover:text-[var(--brand-accent)] transition-colors py-2">
          Trang chủ
        </a>
        <a href="#gioi-thieu" class="whitespace-nowrap text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight text-gray-800 hover:text-[var(--brand-accent)] transition-colors py-2">
          Giới thiệu
        </a>

        <!-- Dropdown Công trình thực tế -->
        <div class="nav-item-dropdown">
          <a href="#cong-trinh-thuc-te" class="whitespace-nowrap inline-flex items-center gap-1 text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight text-gray-800 hover:text-[var(--brand-accent)] transition-colors py-2">
            <span>Công trình thực tế</span>
            <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
          </a>
          <div class="nav-dropdown-menu">
            <a href="#cong-trinh-thuc-te" onclick="selectProductCategory('khach-san-can-ho')" class="block px-4 py-2 text-[13px] text-gray-700 hover:bg-gray-50 hover:text-[var(--brand-primary)]">Khách sạn – Căn hộ – Phòng trọ</a>
            <a href="#cong-trinh-thuc-te" onclick="selectProductCategory('biet-thu')" class="block px-4 py-2 text-[13px] text-gray-700 hover:bg-gray-50 hover:text-[var(--brand-primary)]">Biệt thự</a>
            <a href="#cong-trinh-thuc-te" onclick="selectProductCategory('nha-pho')" class="block px-4 py-2 text-[13px] text-gray-700 hover:bg-gray-50 hover:text-[var(--brand-primary)]">Nhà phố</a>
            <a href="#cong-trinh-thuc-te" onclick="selectProductCategory('van-phong')" class="block px-4 py-2 text-[13px] text-gray-700 hover:bg-gray-50 hover:text-[var(--brand-primary)]">Văn phòng</a>
          </div>
        </div>

        <!-- Dropdown Lĩnh vực hoạt động -->
        <div class="nav-item-dropdown">
          <a href="#dich-vu-tieu-bieu" class="whitespace-nowrap inline-flex items-center gap-1 text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight text-gray-800 hover:text-[var(--brand-accent)] transition-colors py-2">
            <span>Lĩnh vực hoạt động</span>
            <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
          </a>
          <div class="nav-dropdown-menu">
            <a href="#dich-vu-tieu-bieu" class="block px-4 py-2 text-[13px] text-gray-700 hover:bg-gray-50 hover:text-[var(--brand-primary)]">Thiết kế Kiến trúc – Nội thất</a>
            <a href="#cong-trinh-thuc-te" onclick="selectProductCategory('phan-tho')" class="block px-4 py-2 text-[13px] text-gray-700 hover:bg-gray-50 hover:text-[var(--brand-primary)]">Thi công phần thô</a>
            <a href="#cong-trinh-thuc-te" onclick="selectProductCategory('nha-pho')" class="block px-4 py-2 text-[13px] text-gray-700 hover:bg-gray-50 hover:text-[var(--brand-primary)]">Thi công hoàn thiện</a>
            <a href="#cong-trinh-thuc-te" onclick="selectProductCategory('noi-that')" class="block px-4 py-2 text-[13px] text-gray-700 hover:bg-gray-50 hover:text-[var(--brand-primary)]">Thi công nội thất</a>
          </div>
        </div>

        <a href="#du-an-da-nang" class="whitespace-nowrap text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight text-gray-800 hover:text-[var(--brand-accent)] transition-colors py-2">
          Dự án Đà Nẵng
        </a>

        <!-- Dropdown Báo giá -->
        <div class="nav-item-dropdown">
          <a href="#bao-gia" class="whitespace-nowrap inline-flex items-center gap-1 text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight text-gray-800 hover:text-[var(--brand-accent)] transition-colors py-2">
            <span>Báo giá</span>
            <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
          </a>
          <div class="nav-dropdown-menu">
            <a href="#bao-gia" class="block px-4 py-2 text-[13px] text-gray-700 hover:bg-gray-50 hover:text-[var(--brand-primary)]">Báo giá thiết kế kiến trúc</a>
            <a href="#bao-gia" class="block px-4 py-2 text-[13px] text-gray-700 hover:bg-gray-50 hover:text-[var(--brand-primary)]">Báo giá thi công phần thô</a>
            <a href="#bao-gia" class="block px-4 py-2 text-[13px] text-gray-700 hover:bg-gray-50 hover:text-[var(--brand-primary)]">Báo giá thi công hoàn thiện</a>
            <a href="#bao-gia" class="block px-4 py-2 text-[13px] text-gray-700 hover:bg-gray-50 hover:text-[var(--brand-primary)]">Báo giá thi công trọn gói</a>
          </div>
        </div>

        <a href="#tin-tuc" class="whitespace-nowrap text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight text-gray-800 hover:text-[var(--brand-accent)] transition-colors py-2">
          Tin tức
        </a>
        <a href="#lien-he" class="whitespace-nowrap text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight text-gray-800 hover:text-[var(--brand-accent)] transition-colors py-2">
          Liên hệ
        </a>
      </nav>

      <!-- Nút mở Menu trên điện thoại / máy tính bảng -->
      <button
        id="mobile-menu-open"
        type="button"
        aria-label="Mở menu điều hướng"
        class="lg:hidden p-2.5 rounded-lg border border-gray-200 text-gray-700 hover:bg-gray-100 focus:outline-none"
      >
        <i class="fa-solid fa-bars text-lg"></i>
      </button>
    </div>
  </header>

  <!-- Mobile Navigation Drawer (Flatsome Off-Canvas Style) -->
  <div id="mobile-drawer-overlay" class="fixed inset-0 bg-black/50 z-[70] hidden transition-opacity"></div>
  <aside id="mobile-drawer" class="fixed top-0 left-0 bottom-0 w-[290px] max-w-[85vw] bg-white z-[80] shadow-2xl transform -translate-x-full transition-transform duration-300 flex flex-col">
    <div class="p-4 border-b border-gray-200 flex items-center justify-between" style="background-color: var(--brand-primary);">
      <div class="flex items-center gap-2 text-white">
        <span class="font-bold text-sm tracking-wide">NEWDANA.COM</span>
      </div>
      <button id="mobile-menu-close" type="button" aria-label="Đóng menu" class="text-white/90 hover:text-white p-1.5">
        <i class="fa-solid fa-xmark text-lg"></i>
      </button>
    </div>
    <nav class="flex-1 overflow-y-auto py-3 px-4 space-y-1 text-sm font-medium text-gray-800">
      <a href="#trang-chu" class="mobile-nav-link block py-2.5 border-b border-gray-100 hover:text-[var(--brand-primary)]">Trang chủ</a>
      <a href="#gioi-thieu" class="mobile-nav-link block py-2.5 border-b border-gray-100 hover:text-[var(--brand-primary)]">Giới thiệu</a>
      <div class="border-b border-gray-100 py-2">
        <a href="#cong-trinh-thuc-te" class="mobile-nav-link block font-semibold text-gray-900 mb-1.5">Công trình thực tế</a>
        <div class="pl-3 space-y-1 text-xs text-gray-600">
          <a href="#cong-trinh-thuc-te" onclick="selectProductCategory('khach-san-can-ho')" class="mobile-nav-link block py-1">Khách sạn – Căn hộ – Phòng trọ</a>
          <a href="#cong-trinh-thuc-te" onclick="selectProductCategory('biet-thu')" class="mobile-nav-link block py-1">Biệt thự</a>
          <a href="#cong-trinh-thuc-te" onclick="selectProductCategory('nha-pho')" class="mobile-nav-link block py-1">Nhà phố</a>
          <a href="#cong-trinh-thuc-te" onclick="selectProductCategory('van-phong')" class="mobile-nav-link block py-1">Văn phòng</a>
        </div>
      </div>
      <a href="#dich-vu-tieu-bieu" class="mobile-nav-link block py-2.5 border-b border-gray-100 hover:text-[var(--brand-primary)]">Lĩnh vực hoạt động</a>
      <a href="#du-an-da-nang" class="mobile-nav-link block py-2.5 border-b border-gray-100 hover:text-[var(--brand-primary)]">Dự án tại Đà Nẵng</a>
      <a href="#bao-gia" class="mobile-nav-link block py-2.5 border-b border-gray-100 hover:text-[var(--brand-primary)]">Báo giá thi công</a>
      <a href="#tu-van-bao-gia" class="mobile-nav-link block py-2.5 border-b border-gray-100 hover:text-[var(--brand-primary)]">Yêu cầu báo giá</a>
      <a href="#tin-tuc" class="mobile-nav-link block py-2.5 border-b border-gray-100 hover:text-[var(--brand-primary)]">Tin tức</a>
      <a href="#lien-he" class="mobile-nav-link block py-2.5 hover:text-[var(--brand-primary)]">Liên hệ & Bản đồ</a>
    </nav>
    <div class="p-4 bg-gray-50 border-t border-gray-200 text-xs text-gray-600 space-y-1.5">
      <div class="font-semibold text-gray-800">CÔNG TY CỔ PHẦN XÂY DỰNG NEWDANA</div>
      <div><i class="fa-solid fa-location-dot mr-1.5" style="color: var(--brand-accent);"></i>Tổ 19, Phường Cẩm Lệ, TP. Đà Nẵng</div>
      <div><i class="fa-solid fa-phone mr-1.5" style="color: var(--brand-accent);"></i>05956392 - 086755528</div>
    </div>
  </aside>

  <!-- =======================================================================
       SECTION 1: 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP (Kích thước bằng nhau, chữ nằm trọn trong banner & cách xa viền)
       ======================================================================= -->
  <section id="trang-chu" class="w-full py-3 lg:py-4 bg-gray-50">
    <div class="container-95">
      <div id="hero-slider" class="hero-slider-wrapper rounded-xl shadow-md">
        <div id="hero-slides-track" class="hero-slides-track">

          <!-- BANNER 1 -->
          <div class="hero-slide-item">
            <img
              src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w1400"
              data-drive-id="13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
              alt="Thi công xây dựng trọn gói NEWDANA Đà Nẵng"
              class="absolute inset-0 w-full h-full object-cover object-center"
              onerror="handleDriveImageError(this, 'XAY DUNG NEWDANA')"
            >
            <!-- Lớp phủ tối đảm bảo chữ rõ nét, tách nền sạch -->
            <div class="absolute inset-0" style="background: linear-gradient(105deg, rgba(7, 39, 72, 0.88) 0%, rgba(11, 60, 109, 0.72) 55%, rgba(7, 39, 72, 0.45) 100%);"></div>

            <!-- Nội dung chữ luôn nằm trọn trong khung với lề rộng cách xa viền trên cả điện thoại & máy tính -->
            <div class="relative z-10 w-full px-10 py-10 sm:px-16 sm:py-14 lg:px-24 lg:py-16">
              <div class="max-w-2xl text-white">
                <p class="text-[11px] sm:text-xs lg:text-sm font-semibold uppercase tracking-widest mb-2.5" style="color: #FCD34D;">
                  CÔNG TY CỔ PHẦN XÂY DỰNG NEWDANA
                </p>
                <h1 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-snug mb-3 sm:mb-4">
                  THIẾT KẾ &amp; THI CÔNG XÂY DỰNG TRỌN GÓI TẠI ĐÀ NẴNG
                </h1>
                <p class="text-xs sm:text-sm lg:text-base text-white/90 leading-relaxed mb-5 sm:mb-7">
                  Chuyên thiết kế kiến trúc, thi công phần thô, hoàn thiện nhà phố, biệt thự, khách sạn và căn hộ đạt chuẩn kỹ thuật – đúng tiến độ – minh bạch chi phí.
                </p>
                <div class="flex flex-wrap items-center gap-2.5 sm:gap-3">
                  <a href="#tu-van-bao-gia" class="inline-flex items-center justify-center px-4 py-2 sm:px-6 sm:py-2.5 rounded-lg text-xs sm:text-sm font-semibold text-white shadow transition-colors" style="background-color: var(--brand-accent);">
                    Nhận báo giá miễn phí
                  </a>
                  <a href="#du-an-da-nang" class="inline-flex items-center justify-center px-4 py-2 sm:px-6 sm:py-2.5 rounded-lg text-xs sm:text-sm font-semibold text-white border border-white/70 hover:bg-white/15 transition-colors">
                    Xem dự án Đà Nẵng
                  </a>
                </div>
              </div>
            </div>
          </div>

          <!-- BANNER 2 (Cùng cấu trúc & kích thước tuyệt đối bằng Banner 1) -->
          <div class="hero-slide-item">
            <img
              src="https://lh3.googleusercontent.com/d/1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_=w1400"
              data-drive-id="1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_"
              alt="Thi công biệt thự khách sạn căn hộ NEWDANA"
              class="absolute inset-0 w-full h-full object-cover object-center"
              onerror="handleDriveImageError(this, 'CONG TRINH NEWDANA')"
            >
            <div class="absolute inset-0" style="background: linear-gradient(105deg, rgba(7, 39, 72, 0.88) 0%, rgba(11, 60, 109, 0.72) 55%, rgba(7, 39, 72, 0.45) 100%);"></div>

            <div class="relative z-10 w-full px-10 py-10 sm:px-16 sm:py-14 lg:px-24 lg:py-16">
              <div class="max-w-2xl text-white">
                <p class="text-[11px] sm:text-xs lg:text-sm font-semibold uppercase tracking-widest mb-2.5" style="color: #FCD34D;">
                  NHÀ Ở GIA ĐÌNH – TIÊU CHUẨN CÔNG TRÌNH
                </p>
                <h2 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-snug mb-3 sm:mb-4">
                  KIẾN TẠO KHÔNG GIAN SỐNG BỀN VỮNG &amp; ĐẲNG CẤP
                </h2>
                <p class="text-xs sm:text-sm lg:text-base text-white/90 leading-relaxed mb-5 sm:mb-7">
                  Đội ngũ kỹ sư, kiến trúc sư giàu kinh nghiệm trực tiếp giám sát thi công từ móng đến mái, bảo hành kết cấu dài hạn trên toàn khu vực Đà Nẵng.
                </p>
                <div class="flex flex-wrap items-center gap-2.5 sm:gap-3">
                  <a href="#cong-trinh-thuc-te" class="inline-flex items-center justify-center px-4 py-2 sm:px-6 sm:py-2.5 rounded-lg text-xs sm:text-sm font-semibold text-white shadow transition-colors" style="background-color: var(--brand-accent);">
                    Công trình thực tế
                  </a>
                  <a href="#lien-he" class="inline-flex items-center justify-center px-4 py-2 sm:px-6 sm:py-2.5 rounded-lg text-xs sm:text-sm font-semibold text-white border border-white/70 hover:bg-white/15 transition-colors">
                    Liên hệ tư vấn
                  </a>
                </div>
              </div>
            </div>
          </div>

        </div>

        <!-- Nút điều hướng Trái / Phải đặt gọn sát mép, không đè chữ -->
        <button id="banner-prev" type="button" aria-label="Banner trước" class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition-colors">
          <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
        </button>
        <button id="banner-next" type="button" aria-label="Banner tiếp theo" class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition-colors">
          <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
        </button>

        <!-- Chấm chuyển slide -->
        <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
          <button type="button" data-slide="0" aria-label="Chuyển banner 1" class="banner-dot w-7 h-2 rounded-full bg-white transition-all"></button>
          <button type="button" data-slide="1" aria-label="Chuyển banner 2" class="banner-dot w-2.5 h-2 rounded-full bg-white/50 transition-all"></button>
        </div>
      </div>
    </div>
  </section>

  <!-- =======================================================================
       SECTION 2: DỊCH VỤ TIÊU BIỂU (Bố cục 3 cột chuẩn mẫu Tín Trường Thịnh)
       ======================================================================= -->
  <section id="dich-vu-tieu-bieu" class="w-full py-10 lg:py-14 bg-white">
    <div class="container-95">
      <div class="text-center mb-8">
        <h2 class="section-heading text-xl sm:text-2xl lg:text-[26px] font-bold uppercase tracking-tight" style="color: var(--brand-primary);">
          Dịch vụ tiêu biểu
        </h2>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-3 gap-4 lg:gap-6">
        <!-- Dịch vụ 1: THIẾT KẾ -->
        <a href="#tu-van-bao-gia" class="flatsome-card group relative rounded-xl overflow-hidden shadow-sm border border-gray-200 aspect-[16/10] flex items-end">
          <img
            src="https://lh3.googleusercontent.com/d/1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn=w900"
            data-drive-id="1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn"
            alt="Thiết kế kiến trúc NEWDANA"
            class="absolute inset-0 w-full h-full object-cover"
            onerror="handleDriveImageError(this, 'THIET KE')"
          >
          <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
          <div class="relative z-10 w-full p-5 text-white">
            <h3 class="text-lg lg:text-xl font-bold uppercase tracking-wide mb-1">THIẾT KẾ</h3>
            <p class="text-xs sm:text-sm text-white/85">Thiết kế kiến trúc nhà phố, biệt thự, khách sạn, căn hộ tối ưu công năng.</p>
          </div>
        </a>

        <!-- Dịch vụ 2: THI CÔNG -->
        <a href="#cong-trinh-thuc-te" class="flatsome-card group relative rounded-xl overflow-hidden shadow-sm border border-gray-200 aspect-[16/10] flex items-end">
          <img
            src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w900"
            data-drive-id="1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR"
            alt="Thi công xây dựng NEWDANA"
            class="absolute inset-0 w-full h-full object-cover"
            onerror="handleDriveImageError(this, 'THI CONG')"
          >
          <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
          <div class="relative z-10 w-full p-5 text-white">
            <h3 class="text-lg lg:text-xl font-bold uppercase tracking-wide mb-1">THI CÔNG</h3>
            <p class="text-xs sm:text-sm text-white/85">Thi công phần thô, hoàn thiện &amp; xây dựng trọn gói chìa khóa trao tay.</p>
          </div>
        </a>

        <!-- Dịch vụ 3: NỘI THẤT -->
        <a href="#cong-trinh-thuc-te" onclick="selectProductCategory('noi-that')" class="flatsome-card group relative rounded-xl overflow-hidden shadow-sm border border-gray-200 aspect-[16/10] flex items-end">
          <img
            src="https://lh3.googleusercontent.com/d/1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t=w900"
            data-drive-id="1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t"
            alt="Thi công nội thất NEWDANA"
            class="absolute inset-0 w-full h-full object-cover"
            onerror="handleDriveImageError(this, 'NOI THAT')"
          >
          <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
          <div class="relative z-10 w-full p-5 text-white">
            <h3 class="text-lg lg:text-xl font-bold uppercase tracking-wide mb-1">NỘI THẤT</h3>
            <p class="text-xs sm:text-sm text-white/85">Thi công hoàn thiện nội thất hiện đại, đồng bộ vật liệu cao cấp bền đẹp.</p>
          </div>
        </a>
      </div>
    </div>
  </section>

  <!-- =======================================================================
       SECTION 3: GIỚI THIỆU CÔNG TY & THẾ MẠNH CỦA CHÚNG TÔI (Giống web mẫu)
       ======================================================================= -->
  <section id="gioi-thieu" class="w-full py-10 lg:py-14" style="background-color: var(--brand-light);">
    <div class="container-95">
      <!-- Khối giới thiệu công ty -->
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center mb-12">
        <div class="lg:col-span-6">
          <div class="rounded-xl overflow-hidden shadow-md border border-white bg-white">
            <img
              src="https://lh3.googleusercontent.com/d/1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv=w1000"
              data-drive-id="1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv"
              alt="Công trình thực tế Công ty Cổ phần Xây dựng NEWDANA"
              class="w-full aspect-[16/10] object-cover"
              onerror="handleDriveImageError(this, 'NEWDANA DA NANG')"
            >
          </div>
        </div>
        <div class="lg:col-span-6 space-y-4">
          <h2 class="text-xl sm:text-2xl lg:text-[26px] font-bold leading-snug" style="color: var(--brand-primary);">
            CÔNG TY CỔ PHẦN XÂY DỰNG NEWDANA
          </h2>
          <div class="w-16 h-1 rounded-full" style="background-color: var(--brand-accent);"></div>
          <p class="text-sm sm:text-[15px] text-gray-700 leading-relaxed">
            <strong>NEWDANA</strong> chuyên Thiết kế – Thi công Xây dựng – Hoàn thiện Nội thất các công trình Nhà phố, Biệt thự, Khách sạn, Căn hộ, Văn phòng và Hạ tầng kỹ thuật tại khu vực Thành phố Đà Nẵng và miền Trung.
          </p>
          <p class="text-sm sm:text-[15px] text-gray-700 leading-relaxed">
            Với chứng chỉ năng lực hoạt động xây dựng chính quy (MST: <strong>0402160250</strong>) cùng tiêu chí <em>“An Toàn – Chất Lượng – Tiến Độ – Tận Tâm”</em>, đội ngũ kỹ sư và kiến trúc sư của NEWDANA luôn đồng hành sát sao trong từng giai đoạn, đảm bảo mỗi công trình đều vững chắc theo thời gian và hài lòng tuyệt đối chủ đầu tư.
          </p>
          <div class="grid grid-cols-3 gap-3 pt-2">
            <div class="bg-white rounded-lg p-3 text-center border border-gray-200">
              <div class="text-lg sm:text-2xl font-extrabold" style="color: var(--brand-primary);">100+</div>
              <div class="text-[11px] sm:text-xs text-gray-600 mt-0.5">Công trình hoàn thiện</div>
            </div>
            <div class="bg-white rounded-lg p-3 text-center border border-gray-200">
              <div class="text-lg sm:text-2xl font-extrabold" style="color: var(--brand-accent);">100%</div>
              <div class="text-[11px] sm:text-xs text-gray-600 mt-0.5">Đúng tiến độ cam kết</div>
            </div>
            <div class="bg-white rounded-lg p-3 text-center border border-gray-200">
              <div class="text-lg sm:text-2xl font-extrabold" style="color: var(--brand-primary);">5 Năm</div>
              <div class="text-[11px] sm:text-xs text-gray-600 mt-0.5">Bảo hành kết cấu</div>
            </div>
          </div>
        </div>
      </div>

      <!-- 6 Thế mạnh của NEWDANA (Chuẩn bố cục 6 ô Tín Trường Thịnh) -->
      <div class="text-center mb-7">
        <h3 class="section-heading text-lg sm:text-2xl font-bold uppercase" style="color: var(--brand-primary);">
          Thế mạnh của chúng tôi
        </h3>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 lg:gap-5">
        <div class="bg-white rounded-xl p-5 border border-gray-200 shadow-sm flex items-start gap-3.5">
          <div class="w-11 h-11 rounded-lg shrink-0 flex items-center justify-center text-white" style="background-color: var(--brand-primary);">
            <i class="fa-solid fa-helmet-safety text-lg"></i>
          </div>
          <div>
            <h4 class="text-sm sm:text-[15px] font-bold text-gray-900 mb-1">Đội ngũ kiến trúc sư, kỹ sư chuyên nghiệp</h4>
            <p class="text-xs sm:text-[13px] text-gray-600 leading-relaxed">Đội ngũ kỹ sư kết cấu, kiến trúc sư sáng tạo cùng tổ đội thi công tay nghề cao trực tiếp đảm nhận.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-5 border border-gray-200 shadow-sm flex items-start gap-3.5">
          <div class="w-11 h-11 rounded-lg shrink-0 flex items-center justify-center text-white" style="background-color: var(--brand-accent);">
            <i class="fa-solid fa-compass-drafting text-lg"></i>
          </div>
          <div>
            <h4 class="text-sm sm:text-[15px] font-bold text-gray-900 mb-1">Cập nhật xu hướng thiết kế hiện đại</h4>
            <p class="text-xs sm:text-[13px] text-gray-600 leading-relaxed">Ứng dụng giải pháp kiến trúc thông thoáng, vật liệu mới và phương pháp thi công tối ưu công năng.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-5 border border-gray-200 shadow-sm flex items-start gap-3.5">
          <div class="w-11 h-11 rounded-lg shrink-0 flex items-center justify-center text-white" style="background-color: var(--brand-primary);">
            <i class="fa-solid fa-clipboard-check text-lg"></i>
          </div>
          <div>
            <h4 class="text-sm sm:text-[15px] font-bold text-gray-900 mb-1">Giám sát tiến độ chuẩn xác</h4>
            <p class="text-xs sm:text-[13px] text-gray-600 leading-relaxed">Báo cáo tiến độ công trường minh bạch hàng tuần giúp chủ đầu tư theo dõi dễ dàng mọi lúc mọi nơi.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-5 border border-gray-200 shadow-sm flex items-start gap-3.5">
          <div class="w-11 h-11 rounded-lg shrink-0 flex items-center justify-center text-white" style="background-color: var(--brand-accent);">
            <i class="fa-solid fa-shield-halved text-lg"></i>
          </div>
          <div>
            <h4 class="text-sm sm:text-[15px] font-bold text-gray-900 mb-1">Bảo hành công trình dài hạn</h4>
            <p class="text-xs sm:text-[13px] text-gray-600 leading-relaxed">Chế độ hậu mãi rõ ràng, kiểm tra và hỗ trợ xử lý nhanh chóng giúp khách hàng an tâm sử dụng lâu dài.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-5 border border-gray-200 shadow-sm flex items-start gap-3.5">
          <div class="w-11 h-11 rounded-lg shrink-0 flex items-center justify-center text-white" style="background-color: var(--brand-primary);">
            <i class="fa-solid fa-file-invoice-dollar text-lg"></i>
          </div>
          <div>
            <h4 class="text-sm sm:text-[15px] font-bold text-gray-900 mb-1">Chi phí minh bạch, hợp lý</h4>
            <p class="text-xs sm:text-[13px] text-gray-600 leading-relaxed">Dự toán chi tiết từng hạng mục, cam kết không phát sinh vô lý và sử dụng đúng chủng loại vật tư.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-5 border border-gray-200 shadow-sm flex items-start gap-3.5">
          <div class="w-11 h-11 rounded-lg shrink-0 flex items-center justify-center text-white" style="background-color: var(--brand-accent);">
            <i class="fa-solid fa-headset text-lg"></i>
          </div>
          <div>
            <h4 class="text-sm sm:text-[15px] font-bold text-gray-900 mb-1">Hỗ trợ tư vấn miễn phí 24/7</h4>
            <p class="text-xs sm:text-[13px] text-gray-600 leading-relaxed">Khảo sát hiện trạng, tư vấn pháp lý xây dựng và lên phương án sơ bộ hoàn toàn miễn phí tại Đà Nẵng.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- =======================================================================
       SECTION 4: CÔNG TRÌNH THỰC TẾ & DANH MỤC SẢN PHẨM (9 Ảnh thi công thực tế Drive)
       - Danh mục nhỏ gọn, 1 hàng (hoặc tối đa 2 hàng gọn), không vỡ tên danh mục
       - 2 cột trên điện thoại, 3-4 cột trên máy tính, tên sản phẩm hiển thị đầy đủ
       - KHÔNG để các nhãn dán/badge đè lên hình
       ======================================================================= -->
  <section id="cong-trinh-thuc-te" class="w-full py-10 lg:py-14 bg-white">
    <div class="container-95">
      <div class="text-center mb-6">
        <h2 class="section-heading text-xl sm:text-2xl lg:text-[26px] font-bold uppercase" style="color: var(--brand-primary);">
          Công trình thực tế &amp; Danh mục thi công
        </h2>
        <p class="text-xs sm:text-sm text-gray-600 mt-3 max-w-2xl mx-auto">
          Hình ảnh thi công thực tế tại công trường của CÔNG TY CỔ PHẦN XÂY DỰNG NEWDANA theo từng hạng mục công trình.
        </p>
      </div>

      <!-- Thanh lọc Danh mục sản phẩm: Gọn đẹp trên máy tính (1 hàng) & điện thoại -->
      <div id="product-category-tabs" class="flex flex-wrap items-center justify-center gap-2 mb-7">
        <button type="button" data-cat="all" class="cat-tab-btn active px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold">
          Tất cả
        </button>
        <button type="button" data-cat="khach-san-can-ho" class="cat-tab-btn px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold">
          Khách sạn – Căn hộ – Phòng trọ
        </button>
        <button type="button" data-cat="biet-thu" class="cat-tab-btn px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold">
          Biệt thự
        </button>
        <button type="button" data-cat="nha-pho" class="cat-tab-btn px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold">
          Nhà phố
        </button>
        <button type="button" data-cat="van-phong" class="cat-tab-btn px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold">
          Văn phòng
        </button>
        <button type="button" data-cat="phan-tho" class="cat-tab-btn px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold">
          Thi công phần thô
        </button>
        <button type="button" data-cat="noi-that" class="cat-tab-btn px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold">
          Thiết kế &amp; Nội thất
        </button>
      </div>

      <!-- Lưới sản phẩm thi công: 2 cột điện thoại, 3 cột tablet, 3 cột lớn trên desktop (9 ảnh chia đều 3x3) -->
      <div id="products-grid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
        <!-- Dữ liệu được render tự động từ mảng PRODUCTS_DATA để dễ quản lý & lọc -->
      </div>
    </div>
  </section>

  <!-- =======================================================================
       SECTION 5: DANH MỤC CÁC DỰ ÁN TẠI ĐÀ NẴNG (10 Ảnh dự án Đà Nẵng từ Drive)
       ======================================================================= -->
  <section id="du-an-da-nang" class="w-full py-10 lg:py-14 bg-gray-50 border-y border-gray-200">
    <div class="container-95">
      <div class="text-center mb-6">
        <h2 class="section-heading text-xl sm:text-2xl lg:text-[26px] font-bold uppercase" style="color: var(--brand-primary);">
          Các dự án tiêu biểu tại Đà Nẵng
        </h2>
        <p class="text-xs sm:text-sm text-gray-600 mt-3 max-w-2xl mx-auto">
          Tổng hợp các dự án nhà ở, biệt thự, căn hộ, khách sạn và công trình dân dụng do NEWDANA triển khai tại các quận trên địa bàn Thành phố Đà Nẵng.
        </p>
      </div>

      <!-- Bộ lọc khu vực Đà Nẵng gọn đẹp -->
      <div id="danang-area-tabs" class="flex flex-wrap items-center justify-center gap-2 mb-7">
        <button type="button" data-area="all" class="cat-tab-btn active px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold">
          Tất cả Đà Nẵng
        </button>
        <button type="button" data-area="cam-le" class="cat-tab-btn px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold">
          Quận Cẩm Lệ
        </button>
        <button type="button" data-area="hai-chau" class="cat-tab-btn px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold">
          Quận Hải Châu
        </button>
        <button type="button" data-area="son-tra-nhs" class="cat-tab-btn px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold">
          Sơn Trà – Ngũ Hành Sơn
        </button>
        <button type="button" data-area="lien-chieu-tk" class="cat-tab-btn px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold">
          Liên Chiểu – Thanh Khê
        </button>
      </div>

      <!-- Lưới 10 Dự án Đà Nẵng: 2 cột trên điện thoại, 5 cột trên máy tính (2 hàng x 5 ảnh cân đối) -->
      <div id="danang-projects-grid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
        <!-- Dữ liệu được render tự động từ mảng DANANG_PROJECTS -->
      </div>
    </div>
  </section>

  <!-- =======================================================================
       SECTION 6: BÁO GIÁ THIẾT KẾ & THI CÔNG (Danh mục báo giá web mẫu)
       ======================================================================= -->
  <section id="bao-gia" class="w-full py-10 lg:py-14 bg-white">
    <div class="container-95">
      <div class="text-center mb-8">
        <h2 class="section-heading text-xl sm:text-2xl lg:text-[26px] font-bold uppercase" style="color: var(--brand-primary);">
          Báo giá thiết kế &amp; thi công
        </h2>
        <p class="text-xs sm:text-sm text-gray-600 mt-3">
          Đơn giá tham khảo năm 2026 tại khu vực Đà Nẵng – Liên hệ trực tiếp để nhận dự toán chi tiết theo diện tích thực tế.
        </p>
      </div>

      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
        <div class="flatsome-card bg-white rounded-xl border border-gray-200 p-4 sm:p-5 flex flex-col justify-between">
          <div>
            <h3 class="text-sm sm:text-base font-bold mb-1.5" style="color: var(--brand-primary);">Thiết kế kiến trúc</h3>
            <div class="text-base sm:text-xl font-extrabold mb-3" style="color: var(--brand-accent);">120.000đ – 180.000đ<span class="text-xs font-normal text-gray-500">/m²</span></div>
            <ul class="space-y-1.5 text-xs sm:text-[13px] text-gray-600 mb-4">
              <li><i class="fa-solid fa-check mr-1.5 text-emerald-600"></i>Hồ sơ kiến trúc 2D &amp; 3D</li>
              <li><i class="fa-solid fa-check mr-1.5 text-emerald-600"></i>Kết cấu &amp; điện nước M&amp;E</li>
              <li><i class="fa-solid fa-check mr-1.5 text-emerald-600"></i>Hỗ trợ xin phép xây dựng</li>
            </ul>
          </div>
          <a href="#tu-van-bao-gia" class="w-full block text-center py-2 rounded-lg text-xs sm:text-sm font-semibold border transition-colors hover:text-white" style="border-color: var(--brand-primary); color: var(--brand-primary);" onmouseover="this.style.backgroundColor='var(--brand-primary)'; this.style.color='#fff';" onmouseout="this.style.backgroundColor='transparent'; this.style.color='var(--brand-primary)';">
            Nhận báo giá
          </a>
        </div>

        <div class="flatsome-card bg-white rounded-xl border border-gray-200 p-4 sm:p-5 flex flex-col justify-between">
          <div>
            <h3 class="text-sm sm:text-base font-bold mb-1.5" style="color: var(--brand-primary);">Thi công phần thô</h3>
            <div class="text-base sm:text-xl font-extrabold mb-3" style="color: var(--brand-accent);">3.500.000đ – 3.900.000đ<span class="text-xs font-normal text-gray-500">/m²</span></div>
            <ul class="space-y-1.5 text-xs sm:text-[13px] text-gray-600 mb-4">
              <li><i class="fa-solid fa-check mr-1.5 text-emerald-600"></i>Vật tư thô chuẩn chính hãng</li>
              <li><i class="fa-solid fa-check mr-1.5 text-emerald-600"></i>Nhân công hoàn thiện toàn bộ</li>
              <li><i class="fa-solid fa-check mr-1.5 text-emerald-600"></i>Kỹ sư giám sát tại công trình</li>
            </ul>
          </div>
          <a href="#tu-van-bao-gia" class="w-full block text-center py-2 rounded-lg text-xs sm:text-sm font-semibold border transition-colors" style="border-color: var(--brand-primary); color: var(--brand-primary);" onmouseover="this.style.backgroundColor='var(--brand-primary)'; this.style.color='#fff';" onmouseout="this.style.backgroundColor='transparent'; this.style.color='var(--brand-primary)';">
            Nhận báo giá
          </a>
        </div>

        <div class="flatsome-card bg-white rounded-xl border border-gray-200 p-4 sm:p-5 flex flex-col justify-between">
          <div>
            <h3 class="text-sm sm:text-base font-bold mb-1.5" style="color: var(--brand-primary);">Thi công hoàn thiện</h3>
            <div class="text-base sm:text-xl font-extrabold mb-3" style="color: var(--brand-accent);">2.300.000đ – 3.200.000đ<span class="text-xs font-normal text-gray-500">/m²</span></div>
            <ul class="space-y-1.5 text-xs sm:text-[13px] text-gray-600 mb-4">
              <li><i class="fa-solid fa-check mr-1.5 text-emerald-600"></i>Ốp lát gạch, sơn nước, trần thạch cao</li>
              <li><i class="fa-solid fa-check mr-1.5 text-emerald-600"></i>Lắp đặt cửa, thiết bị điện &amp; vệ sinh</li>
              <li><i class="fa-solid fa-check mr-1.5 text-emerald-600"></i>Nghiệm thu từng hạng mục</li>
            </ul>
          </div>
          <a href="#tu-van-bao-gia" class="w-full block text-center py-2 rounded-lg text-xs sm:text-sm font-semibold border transition-colors" style="border-color: var(--brand-primary); color: var(--brand-primary);" onmouseover="this.style.backgroundColor='var(--brand-primary)'; this.style.color='#fff';" onmouseout="this.style.backgroundColor='transparent'; this.style.color='var(--brand-primary)';">
            Nhận báo giá
          </a>
        </div>

        <div class="flatsome-card bg-white rounded-xl border-2 p-4 sm:p-5 flex flex-col justify-between shadow-sm" style="border-color: var(--brand-primary);">
          <div>
            <h3 class="text-sm sm:text-base font-bold mb-1.5" style="color: var(--brand-primary);">Thi công trọn gói</h3>
            <div class="text-base sm:text-xl font-extrabold mb-3" style="color: var(--brand-accent);">5.800.000đ – 7.200.000đ<span class="text-xs font-normal text-gray-500">/m²</span></div>
            <ul class="space-y-1.5 text-xs sm:text-[13px] text-gray-600 mb-4">
              <li><i class="fa-solid fa-check mr-1.5 text-emerald-600"></i>Chìa khóa trao tay từ A – Z</li>
              <li><i class="fa-solid fa-check mr-1.5 text-emerald-600"></i>Miễn phí thiết kế &amp; xin phép XD</li>
              <li><i class="fa-solid fa-check mr-1.5 text-emerald-600"></i>Bảo hành kết cấu đến 5 năm</li>
            </ul>
          </div>
          <a href="#tu-van-bao-gia" class="w-full block text-center py-2 rounded-lg text-xs sm:text-sm font-semibold text-white transition-opacity hover:opacity-90" style="background-color: var(--brand-primary);">
            Nhận báo giá
          </a>
        </div>
      </div>
    </div>
  </section>

  <!-- =======================================================================
       SECTION 7: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ (Chuẩn mẫu Tín Trường Thịnh)
       ======================================================================= -->
  <section id="tu-van-bao-gia" class="w-full py-10 lg:py-14" style="background-color: var(--brand-primary);">
    <div class="container-95">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
        <!-- Cột thông tin bên trái -->
        <div class="lg:col-span-5 text-white space-y-4">
          <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold uppercase leading-snug">
            MIỄN PHÍ TƯ VẤN &amp; BÁO GIÁ XÂY DỰNG
          </h2>
          <div class="w-16 h-1 rounded-full" style="background-color: var(--brand-accent);"></div>
          <p class="text-xs sm:text-sm text-white/90 leading-relaxed">
            Để lại thông tin dự án của Quý khách, kỹ sư của <strong>CÔNG TY CỔ PHẦN XÂY DỰNG NEWDANA</strong> sẽ liên hệ khảo sát thực tế, tư vấn phương án kiến trúc và gửi bảng dự toán chi tiết hoàn toàn miễn phí trong vòng 30 phút.
          </p>
          <div class="space-y-2.5 pt-2 text-xs sm:text-sm">
            <div class="flex items-center gap-3">
              <span class="w-8 h-8 rounded-lg flex items-center justify-center bg-white/15 shrink-0">
                <i class="fa-solid fa-phone" style="color: #FCD34D;"></i>
              </span>
              <span>Hotline: <strong>05956392 - 086755528</strong></span>
            </div>
            <div class="flex items-center gap-3">
              <span class="w-8 h-8 rounded-lg flex items-center justify-center bg-white/15 shrink-0">
                <i class="fa-solid fa-location-dot" style="color: #FCD34D;"></i>
              </span>
              <span>Địa chỉ: Tổ 19, Phường Cẩm Lệ, Thành Phố Đà Nẵng</span>
            </div>
            <div class="flex items-center gap-3">
              <span class="w-8 h-8 rounded-lg flex items-center justify-center bg-white/15 shrink-0">
                <i class="fa-solid fa-clock" style="color: #FCD34D;"></i>
              </span>
              <span>Làm việc: Thứ 2 – Thứ 7 (07:30 – 17:30)</span>
            </div>
          </div>
        </div>

        <!-- Cột Form bên phải -->
        <div class="lg:col-span-7 bg-white rounded-xl p-5 sm:p-7 shadow-xl">
          <form id="quote-form" class="space-y-4" novalidate>
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
              <div>
                <label for="q-name" class="block text-xs font-semibold text-gray-700 mb-1">Họ và tên *</label>
                <input id="q-name" name="name" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-gray-300 focus:outline-none focus:border-[var(--brand-primary)]">
              </div>
              <div>
                <label for="q-phone" class="block text-xs font-semibold text-gray-700 mb-1">Số điện thoại *</label>
                <input id="q-phone" name="phone" type="tel" required placeholder="Nhập số điện thoại liên hệ" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-gray-300 focus:outline-none focus:border-[var(--brand-primary)]">
              </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
              <div>
                <label for="q-type" class="block text-xs font-semibold text-gray-700 mb-1">Loại công trình</label>
                <select id="q-type" name="type" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-gray-300 bg-white focus:outline-none focus:border-[var(--brand-primary)]">
                  <option value="Nhà phố">Nhà phố</option>
                  <option value="Biệt thự">Biệt thự</option>
                  <option value="Khách sạn – Căn hộ cho thuê – Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                  <option value="Văn phòng">Văn phòng</option>
                  <option value="Thi công phần thô">Thi công phần thô</option>
                  <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                </select>
              </div>
              <div>
                <label for="q-budget" class="block text-xs font-semibold text-gray-700 mb-1">Mức đầu tư dự kiến</label>
                <select id="q-budget" name="budget" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-gray-300 bg-white focus:outline-none focus:border-[var(--brand-primary)]">
                  <option value="Chưa xác định">Chưa xác định</option>
                  <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                  <option value="500 triệu – 1 tỷ">500 triệu – 1 tỷ</option>
                  <option value="1 – 2 tỷ">1 – 2 tỷ</option>
                  <option value="2 – 3 tỷ">2 – 3 tỷ</option>
                  <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                </select>
              </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
              <div>
                <label for="q-email" class="block text-xs font-semibold text-gray-700 mb-1">Email (không bắt buộc)</label>
                <input id="q-email" name="email" type="email" placeholder="example@gmail.com" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-gray-300 focus:outline-none focus:border-[var(--brand-primary)]">
              </div>
              <div>
                <label for="q-area" class="block text-xs font-semibold text-gray-700 mb-1">Khu vực / Diện tích đất</label>
                <input id="q-area" name="area" type="text" placeholder="VD: Cẩm Lệ, Đà Nẵng – 100m²" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-gray-300 focus:outline-none focus:border-[var(--brand-primary)]">
              </div>
            </div>

            <div>
              <label for="q-note" class="block text-xs font-semibold text-gray-700 mb-1">Nội dung yêu cầu</label>
              <textarea id="q-note" name="note" rows="3" placeholder="Mô tả sơ bộ số tầng, nhu cầu thiết kế hoặc thời gian dự kiến khởi công..." class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-gray-300 focus:outline-none focus:border-[var(--brand-primary)]"></textarea>
            </div>

            <!-- Hộp thông báo trạng thái Form (Không dùng alert) -->
            <div id="quote-feedback" class="hidden rounded-lg px-4 py-3 text-xs sm:text-sm font-medium"></div>

            <button type="submit" class="w-full py-3 rounded-lg text-sm font-bold uppercase tracking-wide text-white shadow transition-opacity hover:opacity-95" style="background-color: var(--brand-accent);">
              Gửi yêu cầu tư vấn &amp; báo giá
            </button>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- =======================================================================
       SECTION 8: DANH MỤC CÁC BÀI VIẾT / TIN TỨC TRANG CHỦ
       ======================================================================= -->
  <section id="tin-tuc" class="w-full py-10 lg:py-14 bg-white">
    <div class="container-95">
      <div class="text-center mb-8">
        <h2 class="section-heading text-xl sm:text-2xl lg:text-[26px] font-bold uppercase" style="color: var(--brand-primary);">
          Tin tức &amp; Cẩm nang xây dựng
        </h2>
      </div>

      <div id="news-grid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
        <!-- Render tự động từ NEWS_DATA -->
      </div>
    </div>
  </section>

  <!-- =======================================================================
       SECTION 9: DANH MỤC CÁC ĐỐI TÁC
       ======================================================================= -->
  <section id="doi-tac" class="w-full py-10 lg:py-12 bg-gray-50 border-t border-gray-200">
    <div class="container-95">
      <div class="text-center mb-7">
        <h2 class="section-heading text-xl sm:text-2xl font-bold uppercase" style="color: var(--brand-primary);">
          Đối tác cung ứng vật tư &amp; đồng hành
        </h2>
      </div>

      <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-3">
        <div class="bg-white rounded-lg border border-gray-200 px-3 py-4 flex flex-col items-center justify-center text-center shadow-sm">
          <span class="text-xs sm:text-sm font-extrabold tracking-tight" style="color: #004A99;">HÒA PHÁT</span>
          <span class="text-[10px] text-gray-500 mt-0.5">Thép xây dựng</span>
        </div>
        <div class="bg-white rounded-lg border border-gray-200 px-3 py-4 flex flex-col items-center justify-center text-center shadow-sm">
          <span class="text-xs sm:text-sm font-extrabold tracking-tight" style="color: #C0392B;">SÔNG GIANH</span>
          <span class="text-[10px] text-gray-500 mt-0.5">Xi măng</span>
        </div>
        <div class="bg-white rounded-lg border border-gray-200 px-3 py-4 flex flex-col items-center justify-center text-center shadow-sm">
          <span class="text-xs sm:text-sm font-extrabold tracking-tight" style="color: #1D4ED8;">DULUX</span>
          <span class="text-[10px] text-gray-500 mt-0.5">Sơn trang trí</span>
        </div>
        <div class="bg-white rounded-lg border border-gray-200 px-3 py-4 flex flex-col items-center justify-center text-center shadow-sm">
          <span class="text-xs sm:text-sm font-extrabold tracking-tight" style="color: #B45309;">ĐỒNG TÂM</span>
          <span class="text-[10px] text-gray-500 mt-0.5">Gạch ốp lát</span>
        </div>
        <div class="bg-white rounded-lg border border-gray-200 px-3 py-4 flex flex-col items-center justify-center text-center shadow-sm">
          <span class="text-xs sm:text-sm font-extrabold tracking-tight" style="color: #0F172A;">TOTO</span>
          <span class="text-[10px] text-gray-500 mt-0.5">Thiết bị vệ sinh</span>
        </div>
        <div class="bg-white rounded-lg border border-gray-200 px-3 py-4 flex flex-col items-center justify-center text-center shadow-sm">
          <span class="text-xs sm:text-sm font-extrabold tracking-tight" style="color: #DC2626;">CADIVI</span>
          <span class="text-[10px] text-gray-500 mt-0.5">Dây cáp điện</span>
        </div>
        <div class="bg-white rounded-lg border border-gray-200 px-3 py-4 flex flex-col items-center justify-center text-center shadow-sm">
          <span class="text-xs sm:text-sm font-extrabold tracking-tight" style="color: #0369A1;">BÌNH MINH</span>
          <span class="text-[10px] text-gray-500 mt-0.5">Ống cấp thoát nước</span>
        </div>
        <div class="bg-white rounded-lg border border-gray-200 px-3 py-4 flex flex-col items-center justify-center text-center shadow-sm">
          <span class="text-xs sm:text-sm font-extrabold tracking-tight" style="color: #334155;">XINGFA</span>
          <span class="text-[10px] text-gray-500 mt-0.5">Nhôm kính cao cấp</span>
        </div>
      </div>
    </div>
  </section>

  <!-- =======================================================================
       SECTION 10: GOOGLE MAP & FANPAGE FACEBOOK NGOÀI TRANG CHỦ
       ======================================================================= -->
  <section id="lien-he" class="w-full py-10 lg:py-14 bg-white border-t border-gray-200">
    <div class="container-95">
      <div class="text-center mb-8">
        <h2 class="section-heading text-xl sm:text-2xl lg:text-[26px] font-bold uppercase" style="color: var(--brand-primary);">
          Bản đồ trụ sở &amp; Kết nối Fanpage
        </h2>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6">
        <!-- Cột trái: Google Map trụ sở Tổ 19, Phường Cẩm Lệ, TP. Đà Nẵng -->
        <div class="lg:col-span-7 flex flex-col">
          <div class="bg-white rounded-xl border border-gray-200 overflow-hidden shadow-sm flex-1 flex flex-col">
            <div class="px-4 py-3 border-b border-gray-200 flex flex-wrap items-center justify-between gap-2 bg-gray-50">
              <div class="flex items-center gap-2 text-xs sm:text-sm font-bold" style="color: var(--brand-primary);">
                <i class="fa-solid fa-map-location-dot" style="color: var(--brand-accent);"></i>
                <span>Trụ sở: Tổ 19, Phường Cẩm Lệ, Thành Phố Đà Nẵng</span>
              </div>
              <a
                href="https://www.google.com/maps/search/?api=1&query=Tổ+19,+Phường+Hòa+Thọ+Tây,+Cẩm+Lệ,+Đà+Nẵng"
                target="_blank"
                rel="noopener noreferrer"
                class="text-xs font-semibold hover:underline"
                style="color: var(--brand-accent);"
              >
                Chỉ đường Google Maps <i class="fa-solid fa-arrow-up-right-from-square text-[10px] ml-0.5"></i>
              </a>
            </div>
            <div class="w-full h-[320px] sm:h-[360px] flex-1">
              <iframe
                title="Bản đồ CÔNG TY CỔ PHẦN XÂY DỰNG NEWDANA - Tổ 19, Phường Cẩm Lệ, TP. Đà Nẵng"
                src="https://maps.google.com/maps?q=T%E1%BB%95%2019,%20Ph%C6%B0%E1%BB%9Dng%20H%C3%B2a%20Th%E1%BB%8D%20T%C3%A2y,%20C%E1%BA%A9m%20L%E1%BB%87,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=15&ie=UTF8&iwloc=&output=embed"
                class="w-full h-full border-0"
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade"
              ></iframe>
            </div>
          </div>
        </div>

        <!-- Cột phải: Fanpage Facebook chính thức hiển thị trực tiếp ngoài trang chủ -->
        <div class="lg:col-span-5 flex flex-col">
          <div class="bg-white rounded-xl border border-gray-200 overflow-hidden shadow-sm flex-1 flex flex-col">
            <div class="px-4 py-3 border-b border-gray-200 flex items-center justify-between bg-gray-50">
              <div class="flex items-center gap-2 text-xs sm:text-sm font-bold text-[#1877F2]">
                <i class="fa-brands fa-facebook text-base"></i>
                <span>Fanpage chính thức NEWDANA</span>
              </div>
              <a
                href="https://www.facebook.com/profile.php?id=100090930772992"
                target="_blank"
                rel="noopener noreferrer"
                class="text-xs font-semibold text-[#1877F2] hover:underline"
              >
                Theo dõi trang
              </a>
            </div>

            <!-- Khối hiển thị Fanpage (Kết hợp Card trực quan + Facebook Page Plugin) -->
            <div class="p-4 flex-1 flex flex-col justify-between gap-4">
              <!-- Card đại diện Fanpage luôn hiển thị đẹp ngay cả khi trình duyệt chặn cookie Facebook -->
              <div class="rounded-xl overflow-hidden border border-gray-200 bg-gray-50">
                <div class="relative h-28 sm:h-32 w-full">
                  <img
                    src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w800"
                    data-drive-id="157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
                    alt="Ảnh bìa Fanpage NEWDANA"
                    class="w-full h-full object-cover"
                    onerror="handleDriveImageError(this, 'FANPAGE NEWDANA')"
                  >
                  <div class="absolute inset-0 bg-gradient-to-t from-black/75 via-black/25 to-transparent"></div>
                  <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3">
                    <img
                      src="https://lh3.googleusercontent.com/d/10DID_zhF4atD9QeooXRz3RcvQADZsI5w=w200"
                      data-drive-id="10DID_zhF4atD9QeooXRz3RcvQADZsI5w"
                      alt="Avatar Fanpage NEWDANA"
                      class="w-12 h-12 rounded-lg bg-white p-1 object-contain border border-white shadow"
                      onerror="handleDriveImageError(this, 'ND')"
                    >
                    <div class="text-white min-w-0">
                      <div class="text-sm font-bold leading-tight truncate">CÔNG TY CỔ PHẦN XÂY DỰNG NEWDANA</div>
                      <div class="text-[11px] text-white/85">Xây dựng trọn gói • Thiết kế • Thi công Đà Nẵng</div>
                    </div>
                  </div>
                </div>
                <div class="p-3.5 bg-white space-y-2.5">
                  <p class="text-xs text-gray-600 leading-relaxed">
                    Cập nhật hình ảnh tiến độ thi công hàng ngày tại các công trường Đà Nẵng, chia sẻ mẫu thiết kế nhà đẹp và ưu đãi báo giá xây nhà trọn gói.
                  </p>
                  <div class="flex flex-wrap gap-2">
                    <a
                      href="https://www.facebook.com/profile.php?id=100090930772992"
                      target="_blank"
                      rel="noopener noreferrer"
                      class="flex-1 inline-flex items-center justify-center gap-1.5 px-3 py-2 rounded-lg text-xs font-semibold text-white bg-[#1877F2] hover:bg-[#1565C0] transition-colors"
                    >
                      <i class="fa-brands fa-facebook-f"></i>
                      <span>Truy cập Fanpage</span>
                    </a>
                    <a
                      href="https://www.facebook.com/profile.php?id=100090930772992"
                      target="_blank"
                      rel="noopener noreferrer"
                      class="flex-1 inline-flex items-center justify-center gap-1.5 px-3 py-2 rounded-lg text-xs font-semibold border border-gray-300 text-gray-700 hover:bg-gray-100 transition-colors"
                    >
                      <i class="fa-brands fa-facebook-messenger text-[#0084FF]"></i>
                      <span>Nhắn tin tư vấn</span>
                    </a>
                  </div>
                </div>
              </div>

              <!-- Facebook Embed Plugin bổ trợ -->
              <div class="w-full overflow-hidden rounded-lg border border-gray-200 bg-white">
                <iframe
                  title="Fanpage Facebook CÔNG TY CỔ PHẦN XÂY DỰNG NEWDANA"
                  src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D100090930772992&tabs=&width=450&height=130&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true"
                  class="w-full h-[130px] border-0 overflow-hidden"
                  scrolling="no"
                  frameborder="0"
                  allowfullscreen="true"
                  loading="lazy"
                  allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
                ></iframe>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- =======================================================================
       FOOTER (Cấu trúc chuẩn Flatsome giống Tín Trường Thịnh)
       ======================================================================= -->
  <footer class="w-full text-white" style="background-color: var(--brand-dark);">
    <div class="container-95 py-10 lg:py-12">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-12 gap-8">
        <!-- Cột 1: Thông tin công ty -->
        <div class="lg:col-span-5 space-y-3">
          <div class="flex items-center gap-2.5">
            <img
              src="https://lh3.googleusercontent.com/d/10DID_zhF4atD9QeooXRz3RcvQADZsI5w=w300"
              data-drive-id="10DID_zhF4atD9QeooXRz3RcvQADZsI5w"
              alt="Logo NEWDANA"
              class="h-10 w-auto bg-white rounded p-1 object-contain"
              onerror="handleDriveImageError(this, 'NEWDANA')"
            >
            <div>
              <div class="text-sm sm:text-base font-extrabold tracking-wide">CÔNG TY CỔ PHẦN XÂY DỰNG NEWDANA</div>
              <div class="text-xs text-white/75">Website: newdana.com</div>
            </div>
          </div>
          <ul class="space-y-2 text-xs sm:text-sm text-white/85 pt-1">
            <li class="flex items-start gap-2">
              <i class="fa-solid fa-location-dot mt-1 shrink-0" style="color: var(--brand-accent);"></i>
              <span>Trụ sở: Tổ 19, Phường Cẩm Lệ, Thành Phố Đà Nẵng</span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-phone shrink-0" style="color: var(--brand-accent);"></i>
              <span>Hotline: <a href="tel:086755528" class="hover:text-amber-300 font-semibold">05956392 - 086755528</a></span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-building-shield shrink-0" style="color: var(--brand-accent);"></i>
              <span>Mã số thuế: 0402160250</span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-brands fa-facebook shrink-0" style="color: var(--brand-accent);"></i>
              <a href="https://www.facebook.com/profile.php?id=100090930772992" target="_blank" rel="noopener noreferrer" class="hover:text-amber-300 underline">
                Fanpage: Công ty Cổ phần Xây dựng NEWDANA
              </a>
            </li>
          </ul>
        </div>

        <!-- Cột 2: Lĩnh vực hoạt động -->
        <div class="lg:col-span-3 space-y-3">
          <h4 class="text-sm font-bold uppercase tracking-wider text-white border-b border-white/15 pb-2">
            Lĩnh vực hoạt động
          </h4>
          <ul class="space-y-2 text-xs sm:text-sm text-white/80">
            <li><a href="#dich-vu-tieu-bieu" class="hover:text-amber-300 transition-colors">Thiết kế kiến trúc – Nội thất</a></li>
            <li><a href="#cong-trinh-thuc-te" onclick="selectProductCategory('phan-tho')" class="hover:text-amber-300 transition-colors">Thi công phần thô</a></li>
            <li><a href="#cong-trinh-thuc-te" onclick="selectProductCategory('nha-pho')" class="hover:text-amber-300 transition-colors">Thi công hoàn thiện nhà phố</a></li>
            <li><a href="#cong-trinh-thuc-te" onclick="selectProductCategory('biet-thu')" class="hover:text-amber-300 transition-colors">Xây dựng biệt thự trọn gói</a></li>
            <li><a href="#cong-trinh-thuc-te" onclick="selectProductCategory('khach-san-can-ho')" class="hover:text-amber-300 transition-colors">Thi công khách sạn – Căn hộ</a></li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục nhanh -->
        <div class="lg:col-span-4 space-y-3">
          <h4 class="text-sm font-bold uppercase tracking-wider text-white border-b border-white/15 pb-2">
            Thông tin &amp; Hỗ trợ khách hàng
          </h4>
          <ul class="space-y-2 text-xs sm:text-sm text-white/80">
            <li><a href="#du-an-da-nang" class="hover:text-amber-300 transition-colors">Các dự án tiêu biểu tại Đà Nẵng</a></li>
            <li><a href="#bao-gia" class="hover:text-amber-300 transition-colors">Bảng báo giá thi công xây dựng 2026</a></li>
            <li><a href="#tu-van-bao-gia" class="hover:text-amber-300 transition-colors">Đăng ký khảo sát &amp; dự toán miễn phí</a></li>
            <li><a href="#tin-tuc" class="hover:text-amber-300 transition-colors">Cẩm nang &amp; kinh nghiệm xây nhà</a></li>
            <li><a href="#lien-he" class="hover:text-amber-300 transition-colors">Bản đồ chỉ đường &amp; Liên hệ trụ sở</a></li>
          </ul>
        </div>
      </div>
    </div>

    <!-- Dòng bản quyền -->
    <div class="border-t border-white/10 py-4 text-center text-xs text-white/70">
      <div class="container-95">
        Copyright 2026 &copy; <strong>CÔNG TY CỔ PHẦN XÂY DỰNG NEWDANA</strong> (newdana.com). All rights reserved.
      </div>
    </div>
  </footer>

  <!-- =======================================================================
       CÁC NÚT LIÊN HỆ NỔI BẬT (Zalo, Facebook, Hotline)
       - Trên máy tính: Cột nút nổi bên phải có hiệu ứng tỏa sóng thu hút
       - Trên điện thoại: Thanh cố định dưới đáy 3 nút dễ bấm bằng một tay
       ======================================================================= -->
  <!-- Desktop Floating Contact Stack -->
  <div class="hidden md:flex fixed right-4 bottom-6 z-50 flex-col items-end gap-3">
    <!-- Zalo -->
    <a
      href="https://zalo.me/086755528"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="Chat Zalo NEWDANA"
      class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0055D4] text-white pl-3.5 pr-2 py-1.5 rounded-full shadow-lg transition-all"
    >
      <span class="text-xs font-bold tracking-wide">Chat Zalo</span>
      <span class="relative w-9 h-9 rounded-full bg-white text-[#0068FF] font-extrabold text-[11px] flex items-center justify-center">
        Zalo
      </span>
    </a>

    <!-- Facebook -->
    <a
      href="https://www.facebook.com/profile.php?id=100090930772992"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="Facebook NEWDANA"
      class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#1464CC] text-white pl-3.5 pr-2 py-1.5 rounded-full shadow-lg transition-all"
    >
      <span class="text-xs font-bold tracking-wide">Facebook</span>
      <span class="w-9 h-9 rounded-full bg-white text-[#1877F2] flex items-center justify-center">
        <i class="fa-brands fa-facebook-f text-base"></i>
      </span>
    </a>

    <!-- Hotline -->
    <a
      href="tel:086755528"
      aria-label="Gọi Hotline 05956392 - 086755528"
      class="group flex items-center gap-2 bg-[#DC2626] hover:bg-[#B91C1C] text-white pl-3.5 pr-2 py-1.5 rounded-full shadow-lg transition-all"
    >
      <span class="text-xs font-bold tracking-wide">086755528</span>
      <span class="pulse-ring relative w-9 h-9 rounded-full bg-white text-[#DC2626] flex items-center justify-center">
        <i class="fa-solid fa-phone-volume text-sm"></i>
      </span>
    </a>

    <!-- Lên đầu trang -->
    <button
      id="back-to-top"
      type="button"
      aria-label="Lên đầu trang"
      class="w-10 h-10 rounded-full bg-gray-800/80 hover:bg-gray-900 text-white shadow-md hidden items-center justify-center transition-all"
    >
      <i class="fa-solid fa-arrow-up text-xs"></i>
    </button>
  </div>

  <!-- Mobile Fixed Bottom Contact Bar (Tương thích hoàn hảo trên điện thoại) -->
  <div class="md:hidden fixed bottom-0 left-0 right-0 z-50 bg-white border-t border-gray-200 shadow-[0_-4px_16px_rgba(0,0,0,0.08)] grid grid-cols-3 divide-x divide-gray-200">
    <a
      href="tel:086755528"
      class="flex items-center justify-center gap-1.5 py-3 text-white font-bold text-xs"
      style="background-color: #DC2626;"
    >
      <i class="fa-solid fa-phone-volume text-sm"></i>
      <span>Hotline</span>
    </a>
    <a
      href="https://zalo.me/086755528"
      target="_blank"
      rel="noopener noreferrer"
      class="flex items-center justify-center gap-1.5 py-3 text-white font-bold text-xs"
      style="background-color: #0068FF;"
    >
      <i class="fa-solid fa-comment-dots text-sm"></i>
      <span>Zalo</span>
    </a>
    <a
      href="https://www.facebook.com/profile.php?id=100090930772992"
      target="_blank"
      rel="noopener noreferrer"
      class="flex items-center justify-center gap-1.5 py-3 text-white font-bold text-xs"
      style="background-color: #1877F2;"
    >
      <i class="fa-brands fa-facebook-f text-sm"></i>
      <span>Facebook</span>
    </a>
  </div>

  <!-- =======================================================================
       MODAL XEM CHI TIẾT CÔNG TRÌNH / DỰ ÁN / BÀI VIẾT
       ======================================================================= -->
  <div id="detail-modal" class="fixed inset-0 z-[90] hidden items-center justify-center p-3 sm:p-5 bg-black/70">
    <div class="bg-white rounded-xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl relative">
      <button id="detail-modal-close" type="button" aria-label="Đóng cửa sổ" class="sticky top-3 float-right mr-3 mt-3 z-10 w-8 h-8 rounded-full bg-gray-900/75 text-white hover:bg-gray-900 flex items-center justify-center">
        <i class="fa-solid fa-xmark"></i>
      </button>
      <div id="detail-modal-body" class="clear-both p-4 sm:p-6 pt-2"></div>
    </div>
  </div>

  <!-- =======================================================================
       JAVASCRIPT: XỬ LÝ DỮ LIỆU ẢNH GOOGLE DRIVE, SLIDER, BỘ LỌC & FORM
       ======================================================================= -->
  <script>
    /**
     * Hàm dự phòng khi tải ảnh từ Google Drive:
     * Bước 1: Thử đường dẫn thumbnail trực tiếp từ Google Drive
     * Bước 2: Nếu trình duyệt bị chặn mạng/Drive riêng tư, hiển thị ảnh placeholder sạch
     */
    function handleDriveImageError(imgEl, fallbackLabel) {
      try {
        var driveId = imgEl.getAttribute('data-drive-id');
        var retryCount = parseInt(imgEl.getAttribute('data-retry') || '0', 10);

        if (driveId && retryCount === 0) {
          imgEl.setAttribute('data-retry', '1');
          imgEl.src = 'https://drive.google.com/thumbnail?id=' + driveId + '&sz=w1000';
          return;
        }

        if (retryCount < 2) {
          imgEl.setAttribute('data-retry', '2');
          var text = encodeURIComponent(fallbackLabel || 'NEWDANA');
          imgEl.src = 'https://placehold.co/800x600/0B3C6D/FFFFFF?text=' + text;
        }
      } catch (err) {
        // Bỏ qua lỗi phụ để không gián đoạn hiển thị
      }
    }

    /**
     * 1. DỮ LIỆU 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG (Đúng 9 link Google Drive đã cung cấp)
     *    Phân bổ vào đúng danh mục sản phẩm chuẩn web mẫu Tín Trường Thịnh
     */
    const PRODUCTS_DATA = [
      {
        id: 'sp-1',
        driveId: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        title: 'Thi công nhà phố trọn gói 3 tầng hiện đại',
        category: 'nha-pho',
        categoryName: 'Nhà phố',
        location: 'Đà Nẵng',
        desc: 'Hạng mục thi công trọn gói từ kết cấu phần thô đến hoàn thiện mặt tiền, tối ưu thông gió tự nhiên và ánh sáng cho nhà phố đô thị.'
      },
      {
        id: 'sp-2',
        driveId: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
        title: 'Thi công phần thô kết cấu bê tông cốt thép',
        category: 'phan-tho',
        categoryName: 'Thi công phần thô',
        location: 'Đà Nẵng',
        desc: 'Công tác lắp dựng cốt thép dầm sàn, coppha và đổ bê tông thương phẩm đúng mác thiết kế, đảm bảo chất lượng kết cấu chịu lực bền vững.'
      },
      {
        id: 'sp-3',
        driveId: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
        title: 'Thi công hoàn thiện nhà phố mặt tiền hiện đại',
        category: 'nha-pho',
        categoryName: 'Nhà phố',
        location: 'Đà Nẵng',
        desc: 'Hoàn thiện xây tô, chống thấm, sơn nước ngoại thất và lắp đặt hệ cửa nhôm kính cao cấp chuẩn thẩm mỹ theo bản vẽ 3D.'
      },
      {
        id: 'sp-4',
        driveId: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
        title: 'Thi công xây dựng biệt thự hiện đại trọn gói',
        category: 'biet-thu',
        categoryName: 'Biệt thự',
        location: 'Đà Nẵng',
        desc: 'Triển khai thi công biệt thự sân vườn với hệ kết cấu vượt nhịp, vật liệu hoàn thiện cao cấp và giám sát kỹ thuật nghiêm ngặt.'
      },
      {
        id: 'sp-5',
        driveId: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
        title: 'Thi công khách sạn & căn hộ cho thuê cao tầng',
        category: 'khach-san-can-ho',
        categoryName: 'Khách sạn – Căn hộ – Phòng trọ',
        location: 'Đà Nẵng',
        desc: 'Giải pháp thi công tối ưu công năng khai thác phòng, tích hợp đồng bộ hệ thống cấp thoát nước, PCCC và điện lạnh M&E.'
      },
      {
        id: 'sp-6',
        driveId: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
        title: 'Thiết kế & thi công hoàn thiện nội thất trọn gói',
        category: 'noi-that',
        categoryName: 'Thiết kế & Nội thất',
        location: 'Đà Nẵng',
        desc: 'Thi công trần thạch cao, hệ đèn chiếu sáng, ốp lát cao cấp và nội thất gỗ đồng bộ mang lại không gian sống sang trọng, tiện nghi.'
      },
      {
        id: 'sp-7',
        driveId: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
        title: 'Thi công xây dựng văn phòng & trụ sở làm việc',
        category: 'van-phong',
        categoryName: 'Văn phòng',
        location: 'Đà Nẵng',
        desc: 'Thi công công trình văn phòng kết hợp thương mại hiện đại, không gian làm việc mở, đáp ứng tiến độ bàn giao nhanh cho doanh nghiệp.'
      },
      {
        id: 'sp-8',
        driveId: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
        title: 'Thi công phần thô móng cọc & khung kết cấu',
        category: 'phan-tho',
        categoryName: 'Thi công phần thô',
        location: 'Đà Nẵng',
        desc: 'Thi công nền móng, đà kiềng, cột dầm sàn đúng quy trình nghiệm thu kỹ thuật, bảo dưỡng bê tông chuẩn tiêu chuẩn xây dựng Việt Nam.'
      },
      {
        id: 'sp-9',
        driveId: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
        title: 'Thiết kế & thi công biệt thự 2 mặt tiền sang trọng',
        category: 'biet-thu',
        categoryName: 'Biệt thự',
        location: 'Đà Nẵng',
        desc: 'Kiến trúc 2 mặt tiền ấn tượng, xử lý chống nóng hiệu quả cùng hệ ban công thoáng rộng phù hợp khí hậu miền Trung.'
      }
    ];

    /**
     * 2. DỮ LIỆU 10 DỰ ÁN TẠI ĐÀ NẴNG (Đúng 10 link Google Drive đã cung cấp)
     */
    const DANANG_PROJECTS = [
      {
        id: 'dn-1',
        driveId: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
        title: 'Nhà phố hiện đại Khu đô thị Hòa Xuân – Cẩm Lệ',
        area: 'cam-le',
        areaName: 'Quận Cẩm Lệ, Đà Nẵng',
        desc: 'Dự án thiết kế và thi công trọn gói nhà phố 3 tầng tại Khu đô thị sinh thái Hòa Xuân, Quận Cẩm Lệ.'
      },
      {
        id: 'dn-2',
        driveId: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
        title: 'Biệt thự phố Khu Nam Việt Á – Ngũ Hành Sơn',
        area: 'son-tra-nhs',
        areaName: 'Ngũ Hành Sơn, Đà Nẵng',
        desc: 'Thi công xây dựng biệt thự hiện đại diện tích sàn 320m² với không gian xanh thoáng đãng tại Nam Việt Á.'
      },
      {
        id: 'dn-3',
        driveId: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
        title: 'Căn hộ cho thuê cao cấp – Quận Sơn Trà',
        area: 'son-tra-nhs',
        areaName: 'Quận Sơn Trà, Đà Nẵng',
        desc: 'Xây dựng trọn gói tòa căn hộ dịch vụ 5 tầng gần biển, tối ưu số lượng căn hộ và chất lượng cách âm.'
      },
      {
        id: 'dn-4',
        driveId: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
        title: 'Nhà phố 3 tầng Phường Hòa Thọ Tây – Cẩm Lệ',
        area: 'cam-le',
        areaName: 'Quận Cẩm Lệ, Đà Nẵng',
        desc: 'Thi công phần thô và hoàn thiện nhà ở gia đình tại khu vực Hòa Thọ Tây, bàn giao vượt tiến độ 10 ngày.'
      },
      {
        id: 'dn-5',
        driveId: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
        title: 'Khách sạn nghỉ dưỡng ven biển Mỹ Khê',
        area: 'son-tra-nhs',
        areaName: 'Sơn Trà – Ngũ Hành Sơn',
        desc: 'Thiết kế và thi công hoàn thiện khách sạn du lịch ven biển Đà Nẵng với mặt tiền kiến trúc nổi bật.'
      },
      {
        id: 'dn-6',
        driveId: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
        title: 'Nhà phố thương mại trung tâm Quận Hải Châu',
        area: 'hai-chau',
        areaName: 'Quận Hải Châu, Đà Nẵng',
        desc: 'Thi công nhà ở kết hợp mặt bằng kinh doanh tại trung tâm thành phố, xử lý nền móng an toàn tuyệt đối.'
      },
      {
        id: 'dn-7',
        driveId: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
        title: 'Biệt thự sân vườn Khu Phước Lý – Liên Chiểu',
        area: 'lien-chieu-tk',
        areaName: 'Quận Liên Chiểu, Đà Nẵng',
        desc: 'Công trình biệt thự 2 tầng phong cách hiện đại có gara ô tô và sân vườn rộng rãi tại Khu đô thị Phước Lý.'
      },
      {
        id: 'dn-8',
        driveId: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
        title: 'Thi công văn phòng doanh nghiệp Quận Thanh Khê',
        area: 'lien-chieu-tk',
        areaName: 'Quận Thanh Khê, Đà Nẵng',
        desc: 'Hoàn thiện trụ sở văn phòng 4 tầng với hệ vách kính cường lực, trần âm thanh và hạ tầng điện mạng đồng bộ.'
      },
      {
        id: 'dn-9',
        driveId: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
        title: 'Nhà phố đường Tiểu La – Quận Hải Châu',
        area: 'hai-chau',
        areaName: 'Quận Hải Châu, Đà Nẵng',
        desc: 'Thi công cải tạo nâng tầng và hoàn thiện nội thất trọn gói cho nhà phố khu vực trung tâm Hải Châu.'
      },
      {
        id: 'dn-10',
        driveId: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
        title: 'Nhà phố liền kề Khu đô thị FPT City Đà Nẵng',
        area: 'son-tra-nhs',
        areaName: 'Ngũ Hành Sơn, Đà Nẵng',
        desc: 'Thi công hoàn thiện mặt ngoài và nội thất nhà phố liền kề đạt chuẩn mỹ quan khu đô thị công nghệ FPT City.'
      }
    ];

    /**
     * 3. DỮ LIỆU BÀI VIẾT TIN TỨC TRANG CHỦ (Tương đồng chủ đề xây dựng của web mẫu)
     */
    const NEWS_DATA = [
      {
        id: 'news-1',
        driveId: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
        date: '18/11/2026',
        title: 'Hướng dẫn bảo dưỡng bê tông móng đúng kỹ thuật giúp tăng tuổi thọ công trình',
        excerpt: 'Bảo dưỡng bê tông đúng quy trình trong 7 ngày đầu sau khi đổ giúp kết cấu đạt cường độ tối đa và hạn chế nứt bề mặt.',
        content: 'Trong quá trình thi công phần thô, bê tông móng đóng vai trò chịu toàn bộ tải trọng của ngôi nhà. Sau khi đổ bê tông từ 4 đến 6 giờ, cần tiến hành che phủ bằng bao tải ẩm và tưới nước giữ ẩm đều đặn trong tối thiểu 7 ngày liên tiếp, tránh để ánh nắng gắt làm mất nước đột ngột gây rạn nứt chân chim.'
      },
      {
        id: 'news-2',
        driveId: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        date: '12/11/2026',
        title: '03 nỗi lo lớn nhất khi xây nhà trọn gói tại Đà Nẵng và giải pháp khắc phục',
        excerpt: 'Phát sinh chi phí, chậm tiến độ và vật tư không đúng cam kết là 3 vấn đề chủ nhà cần kiểm soát chặt trước khi ký hợp đồng.',
        content: 'Để tránh rủi ro khi xây nhà, chủ đầu tư nên lựa chọn nhà thầu có hồ sơ thiết kế chi tiết, bảng dự toán vật tư ghi rõ thương hiệu chủng loại (thép, xi măng, dây điện, sơn nước) và điều khoản cam kết tiến độ rõ ràng theo từng đợt nghiệm thu.'
      },
      {
        id: 'news-3',
        driveId: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
        date: '05/11/2026',
        title: 'Thiết kế nội thất thông minh: Tối ưu ánh sáng và công năng cho nhà phố Đà Nẵng',
        excerpt: 'Bố trí giếng trời, chọn bảng màu trung tính và vật liệu chống ẩm giúp ngôi nhà luôn thoáng mát quanh năm.',
        content: 'Khí hậu Đà Nẵng có mùa nắng nóng và mùa mưa bão rõ rệt. Do đó, giải pháp bố trí giếng trời thông tầng kết hợp cửa nhôm kính cách nhiệt và vật liệu nội thất chống ẩm sẽ giúp không gian sống vừa thẩm mỹ vừa bền bỉ nhiều năm.'
      },
      {
        id: 'news-4',
        driveId: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
        date: '28/10/2026',
        title: 'Chứng chỉ năng lực hoạt động xây dựng quan trọng như thế nào khi chọn nhà thầu?',
        excerpt: 'Chứng chỉ năng lực do cơ quan quản lý cấp là bảo chứng pháp lý và chuyên môn cho chất lượng công trình của bạn.',
        content: 'Nhà thầu có chứng chỉ năng lực hoạt động xây dựng chính quy đã được thẩm định về năng lực kỹ sư chủ trì, kinh nghiệm thi công thực tế và hệ thống quản lý an toàn lao động. Đây là cơ sở quan trọng giúp chủ đầu tư an tâm khi giao phó công trình.'
      }
    ];

    // =========================================================================
    // RENDER CÔNG TRÌNH THỰC TẾ (2 cột điện thoại, tên sản phẩm đầy đủ không cắt chữ, không nhãn dán)
    // =========================================================================
    function renderProducts(category) {
      const grid = document.getElementById('products-grid');
      if (!grid) return;

      const filtered = category === 'all'
        ? PRODUCTS_DATA
        : PRODUCTS_DATA.filter(function(item) { return item.category === category; });

      grid.innerHTML = filtered.map(function(item) {
        return (
          '<article onclick="openDetailModal(\'product\', \'' + item.id + '\')" class="flatsome-card cursor-pointer bg-white rounded-xl border border-gray-200 overflow-hidden shadow-sm flex flex-col">' +
            '<div class="w-full aspect-[4/3] overflow-hidden bg-gray-100">' +
              '<img src="https://lh3.googleusercontent.com/d/' + item.driveId + '=w800" data-drive-id="' + item.driveId + '" alt="' + item.title + '" loading="lazy" class="w-full h-full object-cover" onerror="handleDriveImageError(this, \'' + item.categoryName + '\')">' +
            '</div>' +
            '<div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">' +
              '<div>' +
                '<div class="text-[11px] font-medium text-gray-500 mb-1">' + item.categoryName + '</div>' +
                '<h3 class="text-[13px] sm:text-[15px] font-bold text-gray-900 leading-snug break-words">' + item.title + '</h3>' +
              '</div>' +
              '<div class="mt-2.5 pt-2 border-t border-gray-100 flex items-center justify-between text-[11px] sm:text-xs font-semibold" style="color: var(--brand-primary);">' +
                '<span>Xem chi tiết</span>' +
                '<i class="fa-solid fa-arrow-right text-[10px]"></i>' +
              '</div>' +
            '</div>' +
          '</article>'
        );
      }).join('');
    }

    function selectProductCategory(cat) {
      const tabs = document.querySelectorAll('#product-category-tabs .cat-tab-btn');
      tabs.forEach(function(btn) {
        if (btn.getAttribute('data-cat') === cat) {
          btn.classList.add('active');
        } else {
          btn.classList.remove('active');
        }
      });
      renderProducts(cat);
    }

    // =========================================================================
    // RENDER 10 DỰ ÁN TẠI ĐÀ NẴNG
    // =========================================================================
    function renderDanangProjects(area) {
      const grid = document.getElementById('danang-projects-grid');
      if (!grid) return;

      const filtered = area === 'all'
        ? DANANG_PROJECTS
        : DANANG_PROJECTS.filter(function(item) { return item.area === area; });

      grid.innerHTML = filtered.map(function(item) {
        return (
          '<article onclick="openDetailModal(\'project\', \'' + item.id + '\')" class="flatsome-card cursor-pointer bg-white rounded-xl border border-gray-200 overflow-hidden shadow-sm flex flex-col">' +
            '<div class="w-full aspect-[4/3] overflow-hidden bg-gray-100">' +
              '<img src="https://lh3.googleusercontent.com/d/' + item.driveId + '=w700" data-drive-id="' + item.driveId + '" alt="' + item.title + '" loading="lazy" class="w-full h-full object-cover" onerror="handleDriveImageError(this, \'DU AN DA NANG\')">' +
            '</div>' +
            '<div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">' +
              '<div>' +
                '<div class="text-[10px] sm:text-[11px] text-gray-500 mb-1"><i class="fa-solid fa-location-dot mr-1" style="color: var(--brand-accent);"></i>' + item.areaName + '</div>' +
                '<h3 class="text-[12px] sm:text-[13px] font-bold text-gray-900 leading-snug break-words">' + item.title + '</h3>' +
              '</div>' +
            '</div>' +
          '</article>'
        );
      }).join('');
    }

    // =========================================================================
    // RENDER TIN TỨC TRANG CHỦ
    // =========================================================================
    function renderNews() {
      const grid = document.getElementById('news-grid');
      if (!grid) return;

      grid.innerHTML = NEWS_DATA.map(function(post) {
        return (
          '<article onclick="openDetailModal(\'news\', \'' + post.id + '\')" class="flatsome-card cursor-pointer bg-white rounded-xl border border-gray-200 overflow-hidden shadow-sm flex flex-col">' +
            '<div class="w-full aspect-[16/10] overflow-hidden bg-gray-100">' +
              '<img src="https://lh3.googleusercontent.com/d/' + post.driveId + '=w700" data-drive-id="' + post.driveId + '" alt="' + post.title + '" loading="lazy" class="w-full h-full object-cover" onerror="handleDriveImageError(this, \'TIN TUC NEWDANA\')">' +
            '</div>' +
            '<div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">' +
              '<div>' +
                '<div class="text-[11px] text-gray-500 mb-1.5">' + post.date + '</div>' +
                '<h3 class="text-[13px] sm:text-sm font-bold text-gray-900 leading-snug mb-1.5 break-words">' + post.title + '</h3>' +
                '<p class="hidden sm:block text-xs text-gray-600 leading-relaxed">' + post.excerpt + '</p>' +
              '</div>' +
              '<div class="mt-2.5 text-[11px] sm:text-xs font-semibold" style="color: var(--brand-primary);">Đọc tiếp &rarr;</div>' +
            '</div>' +
          '</article>'
        );
      }).join('');
    }

    // =========================================================================
    // MODAL XEM CHI TIẾT
    // =========================================================================
    function openDetailModal(type, id) {
      const modal = document.getElementById('detail-modal');
      const body = document.getElementById('detail-modal-body');
      if (!modal || !body) return;

      let item = null;
      let subtitle = '';
      let contentText = '';

      if (type === 'product') {
        item = PRODUCTS_DATA.find(function(x) { return x.id === id; });
        if (item) {
          subtitle = item.categoryName + ' • ' + item.location;
          contentText = item.desc;
        }
      } else if (type === 'project') {
        item = DANANG_PROJECTS.find(function(x) { return x.id === id; });
        if (item) {
          subtitle = item.areaName;
          contentText = item.desc;
        }
      } else if (type === 'news') {
        item = NEWS_DATA.find(function(x) { return x.id === id; });
        if (item) {
          subtitle = 'Đăng ngày ' + item.date + ' • CÔNG TY CỔ PHẦN XÂY DỰNG NEWDANA';
          contentText = item.content;
        }
      }

      if (!item) return;

      body.innerHTML =
        '<div class="rounded-lg overflow-hidden mb-4 bg-gray-100">' +
          '<img src="https://lh3.googleusercontent.com/d/' + item.driveId + '=w1200" data-drive-id="' + item.driveId + '" alt="' + item.title + '" class="w-full max-h-[380px] object-cover" onerror="handleDriveImageError(this, \'NEWDANA\')">' +
        '</div>' +
        '<div class="text-xs font-semibold mb-1" style="color: var(--brand-accent);">' + subtitle + '</div>' +
        '<h3 class="text-lg sm:text-xl font-bold text-gray-900 mb-3 leading-snug">' + item.title + '</h3>' +
        '<p class="text-sm text-gray-700 leading-relaxed mb-5">' + contentText + '</p>' +
        '<div class="flex flex-wrap items-center gap-2.5 pt-3 border-t border-gray-200">' +
          '<a href="#tu-van-bao-gia" onclick="closeDetailModal()" class="px-4 py-2 rounded-lg text-xs sm:text-sm font-semibold text-white" style="background-color: var(--brand-primary);">Yêu cầu tư vấn &amp; báo giá</a>' +
          '<a href="tel:086755528" class="px-4 py-2 rounded-lg text-xs sm:text-sm font-semibold text-white" style="background-color: var(--brand-accent);">Hotline: 05956392 - 086755528</a>' +
        '</div>';

      modal.classList.remove('hidden');
      modal.classList.add('flex');
      document.body.style.overflow = 'hidden';
    }

    function closeDetailModal() {
      const modal = document.getElementById('detail-modal');
      if (!modal) return;
      modal.classList.add('hidden');
      modal.classList.remove('flex');
      document.body.style.overflow = '';
    }

    // =========================================================================
    // KHỞI TẠO KHI TRANG TẢI XONG
    // =========================================================================
    document.addEventListener('DOMContentLoaded', function() {
      // 1. Render danh sách ban đầu
      renderProducts('all');
      renderDanangProjects('all');
      renderNews();

      // 2. Sự kiện lọc danh mục sản phẩm
      document.querySelectorAll('#product-category-tabs .cat-tab-btn').forEach(function(btn) {
        btn.addEventListener('click', function() {
          selectProductCategory(this.getAttribute('data-cat'));
        });
      });

      // 3. Sự kiện lọc dự án Đà Nẵng
      document.querySelectorAll('#danang-area-tabs .cat-tab-btn').forEach(function(btn) {
        btn.addEventListener('click', function() {
          document.querySelectorAll('#danang-area-tabs .cat-tab-btn').forEach(function(b) {
            b.classList.remove('active');
          });
          this.classList.add('active');
          renderDanangProjects(this.getAttribute('data-area'));
        });
      });

      // 4. Banner tự trượt (2 ảnh kích thước bằng nhau + hỗ trợ vuốt trên điện thoại)
      let currentSlide = 0;
      const totalSlides = 2;
      const track = document.getElementById('hero-slides-track');
      const dots = document.querySelectorAll('.banner-dot');
      let sliderTimer = null;

      function goToSlide(index) {
        currentSlide = (index + totalSlides) % totalSlides;
        if (track) {
          track.style.transform = 'translateX(-' + (currentSlide * 50) + '%)';
        }
        dots.forEach(function(dot, i) {
          if (i === currentSlide) {
            dot.classList.remove('w-2.5', 'bg-white/50');
            dot.classList.add('w-7', 'bg-white');
          } else {
            dot.classList.remove('w-7', 'bg-white');
            dot.classList.add('w-2.5', 'bg-white/50');
          }
        });
      }

      function startAutoSlide() {
        stopAutoSlide();
        sliderTimer = setInterval(function() {
          goToSlide(currentSlide + 1);
        }, 5000);
      }

      function stopAutoSlide() {
        if (sliderTimer) clearInterval(sliderTimer);
      }

      const prevBtn = document.getElementById('banner-prev');
      const nextBtn = document.getElementById('banner-next');
      if (prevBtn) prevBtn.addEventListener('click', function() { goToSlide(currentSlide - 1); startAutoSlide(); });
      if (nextBtn) nextBtn.addEventListener('click', function() { goToSlide(currentSlide + 1); startAutoSlide(); });

      dots.forEach(function(dot) {
        dot.addEventListener('click', function() {
          goToSlide(parseInt(this.getAttribute('data-slide'), 10));
          startAutoSlide();
        });
      });

      // Hỗ trợ vuốt cảm ứng (Touch swipe) cho Banner trên điện thoại
      const sliderEl = document.getElementById('hero-slider');
      let touchStartX = 0;
      if (sliderEl) {
        sliderEl.addEventListener('touchstart', function(e) {
          touchStartX = e.changedTouches[0].screenX;
          stopAutoSlide();
        }, { passive: true });
        sliderEl.addEventListener('touchend', function(e) {
          const diff = e.changedTouches[0].screenX - touchStartX;
          if (Math.abs(diff) > 40) {
            goToSlide(diff < 0 ? currentSlide + 1 : currentSlide - 1);
          }
          startAutoSlide();
        }, { passive: true });
      }
      startAutoSlide();

      // 5. Mobile Drawer Menu
      const openMenuBtn = document.getElementById('mobile-menu-open');
      const closeMenuBtn = document.getElementById('mobile-menu-close');
      const drawer = document.getElementById('mobile-drawer');
      const overlay = document.getElementById('mobile-drawer-overlay');

      function openDrawer() {
        if (!drawer || !overlay) return;
        drawer.classList.remove('-translate-x-full');
        overlay.classList.remove('hidden');
        document.body.style.overflow = 'hidden';
      }
      function closeDrawer() {
        if (!drawer || !overlay) return;
        drawer.classList.add('-translate-x-full');
        overlay.classList.add('hidden');
        document.body.style.overflow = '';
      }

      if (openMenuBtn) openMenuBtn.addEventListener('click', openDrawer);
      if (closeMenuBtn) closeMenuBtn.addEventListener('click', closeDrawer);
      if (overlay) overlay.addEventListener('click', closeDrawer);
      document.querySelectorAll('.mobile-nav-link').forEach(function(link) {
        link.addEventListener('click', closeDrawer);
      });

      // 6. Modal đóng khi bấm nút X hoặc bấm ra ngoài
      const modalCloseBtn = document.getElementById('detail-modal-close');
      const detailModal = document.getElementById('detail-modal');
      if (modalCloseBtn) modalCloseBtn.addEventListener('click', closeDetailModal);
      if (detailModal) {
        detailModal.addEventListener('click', function(e) {
          if (e.target === detailModal) closeDetailModal();
        });
      }

      // 7. Xử lý Form yêu cầu tư vấn & báo giá (Hiển thị thông báo trực tiếp, không dùng alert)
      const quoteForm = document.getElementById('quote-form');
      const quoteFeedback = document.getElementById('quote-feedback');
      if (quoteForm && quoteFeedback) {
        quoteForm.addEventListener('submit', function(e) {
          e.preventDefault();
          const name = document.getElementById('q-name').value.trim();
          const phone = document.getElementById('q-phone').value.trim();

          if (!name || !phone) {
            quoteFeedback.className = 'rounded-lg px-4 py-3 text-xs sm:text-sm font-medium bg-red-50 text-red-700 border border-red-200';
            quoteFeedback.textContent = 'Vui lòng nhập đầy đủ Họ và tên và Số điện thoại để NEWDANA liên hệ tư vấn.';
            quoteFeedback.classList.remove('hidden');
            return;
          }

          quoteFeedback.className = 'rounded-lg px-4 py-3 text-xs sm:text-sm font-medium bg-emerald-50 text-emerald-800 border border-emerald-200';
          quoteFeedback.textContent = 'Cảm ơn ' + name + '! Yêu cầu báo giá của Quý khách đã được gửi thành công. Kỹ sư NEWDANA sẽ liên hệ qua số ' + phone + ' trong thời gian sớm nhất.';
          quoteFeedback.classList.remove('hidden');
          quoteForm.reset();
        });
      }

      // 8. Nút lên đầu trang
      const backToTop = document.getElementById('back-to-top');
      if (backToTop) {
        window.addEventListener('scroll', function() {
          if (window.scrollY > 400) {
            backToTop.classList.remove('hidden');
            backToTop.classList.add('flex');
          } else {
            backToTop.classList.add('hidden');
            backToTop.classList.remove('flex');
          }
        });
        backToTop.addEventListener('click', function() {
          window.scrollTo({ top: 0, behavior: 'smooth' });
        });
      }
    });
  </script>
</body>
</html>
