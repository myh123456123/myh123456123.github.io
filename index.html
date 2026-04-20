<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>中国高铁 · 畅行无忧</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --primary: #0066CC;
            --primary-dark: #004A99;
            --accent: #FF6B35;
            --bg-light: #F5F7FA;
            --text-dark: #1A1A2E;
            --text-gray: #6B7280;
            --white: #FFFFFF;
            --shadow: 0 4px 20px rgba(0,0,0,0.08);
            --shadow-hover: 0 8px 30px rgba(0,0,0,0.15);
            --radius: 12px;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", "PingFang SC", "Hiragino Sans GB", "Microsoft YaHei", sans-serif;
            color: var(--text-dark);
            background: var(--bg-light);
            line-height: 1.6;
        }

        /* ===== NAV ===== */
        nav {
            position: fixed;
            top: 0;
            width: 100%;
            background: rgba(255,255,255,0.95);
            backdrop-filter: blur(12px);
            z-index: 1000;
            border-bottom: 1px solid rgba(0,0,0,0.06);
            transition: box-shadow 0.3s;
        }
        nav.scrolled { box-shadow: 0 2px 20px rgba(0,0,0,0.1); }
        .nav-inner {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 24px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            height: 64px;
        }
        .logo {
            font-size: 22px;
            font-weight: 800;
            color: var(--primary);
            display: flex;
            align-items: center;
            gap: 8px;
            text-decoration: none;
        }
        .logo svg { width: 32px; height: 32px; }
        .nav-links { display: flex; gap: 32px; list-style: none; }
        .nav-links a {
            text-decoration: none;
            color: var(--text-gray);
            font-size: 14px;
            font-weight: 500;
            transition: color 0.2s;
            position: relative;
        }
        .nav-links a:hover, .nav-links a.active { color: var(--primary); }
        .nav-links a::after {
            content: '';
            position: absolute;
            bottom: -4px;
            left: 0;
            width: 0;
            height: 2px;
            background: var(--primary);
            transition: width 0.3s;
        }
        .nav-links a:hover::after, .nav-links a.active::after { width: 100%; }
        .hamburger { display: none; background: none; border: none; cursor: pointer; }

        /* ===== HERO ===== */
        .hero {
            margin-top: 64px;
            background: linear-gradient(135deg, #0066CC 0%, #003D7A 50%, #001F3F 100%);
            color: white;
            padding: 100px 24px 80px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        .hero::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(ellipse at 30% 50%, rgba(255,255,255,0.08) 0%, transparent 60%);
        }
        .hero h1 {
            font-size: 48px;
            font-weight: 800;
            margin-bottom: 16px;
            position: relative;
        }
        .hero p {
            font-size: 18px;
            opacity: 0.85;
            max-width: 600px;
            margin: 0 auto 40px;
            position: relative;
        }
        .hero-stats {
            display: flex;
            justify-content: center;
            gap: 60px;
            position: relative;
        }
        .hero-stat { text-align: center; }
        .hero-stat .num { font-size: 36px; font-weight: 800; }
        .hero-stat .label { font-size: 14px; opacity: 0.7; margin-top: 4px; }

        /* ===== SECTIONS ===== */
        section {
            max-width: 1200px;
            margin: 0 auto;
            padding: 80px 24px;
        }
        .section-header {
            text-align: center;
            margin-bottom: 48px;
        }
        .section-header h2 {
            font-size: 32px;
            font-weight: 700;
            margin-bottom: 12px;
        }
        .section-header p {
            color: var(--text-gray);
            font-size: 16px;
        }
        .section-tag {
            display: inline-block;
            background: rgba(0,102,204,0.1);
            color: var(--primary);
            padding: 4px 14px;
            border-radius: 20px;
            font-size: 13px;
            font-weight: 600;
            margin-bottom: 12px;
        }

        /* ===== 车次查询 ===== */
        .search-box {
            background: var(--white);
            border-radius: var(--radius);
            padding: 32px;
            box-shadow: var(--shadow);
            margin-bottom: 32px;
        }
        .search-form {
            display: flex;
            gap: 16px;
            align-items: flex-end;
            flex-wrap: wrap;
        }
        .form-group { flex: 1; min-width: 180px; }
        .form-group label {
            display: block;
            font-size: 13px;
            font-weight: 600;
            color: var(--text-gray);
            margin-bottom: 6px;
        }
        .form-group input, .form-group select {
            width: 100%;
            padding: 12px 16px;
            border: 2px solid #E5E7EB;
            border-radius: 8px;
            font-size: 15px;
            transition: border-color 0.2s;
            outline: none;
            background: var(--bg-light);
        }
        .form-group input:focus, .form-group select:focus {
            border-color: var(--primary);
            background: var(--white);
        }
        .btn {
            padding: 12px 32px;
            border: none;
            border-radius: 8px;
            font-size: 15px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.2s;
        }
        .btn-primary {
            background: var(--primary);
            color: white;
        }
        .btn-primary:hover { background: var(--primary-dark); transform: translateY(-1px); }
        .btn-accent {
            background: var(--accent);
            color: white;
        }
        .btn-accent:hover { background: #E55A2B; }

        .train-table {
            width: 100%;
            background: var(--white);
            border-radius: var(--radius);
            overflow: hidden;
            box-shadow: var(--shadow);
        }
        .train-table table {
            width: 100%;
            border-collapse: collapse;
        }
        .train-table th {
            background: var(--primary);
            color: white;
            padding: 16px 20px;
            text-align: left;
            font-size: 14px;
            font-weight: 600;
        }
        .train-table td {
            padding: 16px 20px;
            border-bottom: 1px solid #F0F0F0;
            font-size: 14px;
        }
        .train-table tr:hover td { background: #F8FAFF; }
        .train-number {
            color: var(--primary);
            font-weight: 700;
            font-size: 16px;
        }
        .time-big { font-size: 20px; font-weight: 700; }
        .time-small { font-size: 12px; color: var(--text-gray); }
        .duration { color: var(--accent); font-weight: 600; }
        .status-badge {
            padding: 4px 12px;
            border-radius: 20px;
            font-size: 12px;
            font-weight: 600;
        }
        .status-on { background: #D1FAE5; color: #065F46; }
        .status-wait { background: #FEF3C7; color: #92400E; }

        /* ===== 车站信息 ===== */
        .station-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
            gap: 24px;
        }
        .station-card {
            background: var(--white);
            border-radius: var(--radius);
            overflow: hidden;
            box-shadow: var(--shadow);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .station-card:hover {
            transform: translateY(-4px);
            box-shadow: var(--shadow-hover);
        }
        .station-img {
            height: 180px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 48px;
            position: relative;
        }
        .station-img::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            height: 40px;
            background: linear-gradient(transparent, rgba(0,0,0,0.1));
        }
        .station-info { padding: 20px; }
        .station-info h3 { font-size: 18px; margin-bottom: 8px; }
        .station-info p { font-size: 14px; color: var(--text-gray); margin-bottom: 12px; }
        .station-tags { display: flex; gap: 8px; flex-wrap: wrap; }
        .station-tag {
            padding: 3px 10px;
            background: var(--bg-light);
            border-radius: 6px;
            font-size: 12px;
            color: var(--text-gray);
        }

        /* ===== 设施设备 ===== */
        .facility-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 24px;
        }
        .facility-card {
            background: var(--white);
            border-radius: var(--radius);
            padding: 32px 24px;
            text-align: center;
            box-shadow: var(--shadow);
            transition: transform 0.3s;
        }
        .facility-card:hover { transform: translateY(-4px); }
        .facility-icon {
            width: 64px;
            height: 64px;
            margin: 0 auto 16px;
            background: linear-gradient(135deg, rgba(0,102,204,0.1), rgba(0,102,204,0.05));
            border-radius: 16px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 28px;
        }
        .facility-card h3 { font-size: 16px; margin-bottom: 8px; }
        .facility-card p { font-size: 13px; color: var(--text-gray); }

        /* ===== 高铁订餐 ===== */
        .meal-section { background: var(--white); border-radius: var(--radius); padding: 40px; box-shadow: var(--shadow); }
        .meal-tabs {
            display: flex;
            gap: 8px;
            margin-bottom: 24px;
            border-bottom: 2px solid #F0F0F0;
            padding-bottom: 12px;
        }
        .meal-tab {
            padding: 8px 20px;
            border: none;
            background: none;
            font-size: 14px;
            font-weight: 600;
            color: var(--text-gray);
            cursor: pointer;
            border-radius: 8px;
            transition: all 0.2s;
        }
        .meal-tab.active { background: var(--primary); color: white; }
        .meal-tab:hover:not(.active) { background: var(--bg-light); }
        .meal-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
            gap: 20px;
        }
        .meal-card {
            border: 2px solid #F0F0F0;
            border-radius: var(--radius);
            overflow: hidden;
            transition: border-color 0.2s;
        }
        .meal-card:hover { border-color: var(--primary); }
        .meal-img {
            height: 140px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 48px;
            background: linear-gradient(135deg, #FFF5EB, #FFE8D6);
        }
        .meal-detail { padding: 16px; }
        .meal-detail h4 { font-size: 15px; margin-bottom: 4px; }
        .meal-detail .desc { font-size: 12px; color: var(--text-gray); margin-bottom: 12px; }
        .meal-bottom {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .meal-price { color: var(--accent); font-weight: 700; font-size: 18px; }
        .meal-btn {
            padding: 6px 16px;
            border: 2px solid var(--primary);
            background: none;
            color: var(--primary);
            border-radius: 6px;
            font-size: 13px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.2s;
        }
        .meal-btn:hover { background: var(--primary); color: white; }

        /* 购物车 */
        .cart-bar {
            position: fixed;
            bottom: 24px;
            right: 24px;
            background: var(--primary);
            color: white;
            width: 56px;
            height: 56px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 24px;
            cursor: pointer;
            box-shadow: 0 4px 20px rgba(0,102,204,0.4);
            transition: transform 0.2s;
            z-index: 999;
        }
        .cart-bar:hover { transform: scale(1.1); }
        .cart-count {
            position: absolute;
            top: -4px;
            right: -4px;
            background: var(--accent);
            color: white;
            width: 22px;
            height: 22px;
            border-radius: 50%;
            font-size: 12px;
            font-weight: 700;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        /* ===== 铁路书籍 ===== */
        .books-note {
            background: linear-gradient(135deg, #FFF5EB, #FFE8D6);
            border-left: 4px solid var(--accent);
            padding: 16px 24px;
            border-radius: 0 8px 8px 0;
            margin-bottom: 32px;
            font-size: 14px;
            color: #92400E;
        }
        .books-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(260px, 1fr));
            gap: 24px;
        }
        .book-card {
            background: var(--white);
            border-radius: var(--radius);
            overflow: hidden;
            box-shadow: var(--shadow);
            transition: transform 0.3s;
        }
        .book-card:hover { transform: translateY(-4px); }
        .book-cover {
            height: 200px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 14px;
            font-weight: 600;
            text-align: center;
            padding: 20px;
            line-height: 1.4;
        }
        .book-content { padding: 20px; }
        .book-content h3 { font-size: 16px; margin-bottom: 6px; }
        .book-content .author { font-size: 13px; color: var(--text-gray); margin-bottom: 8px; }
        .book-content .intro { font-size: 13px; color: var(--text-gray); margin-bottom: 16px; display: -webkit-box; -webkit-line-clamp: 2; -webkit-box-orient: vertical; overflow: hidden; }
        .btn-read {
            display: inline-block;
            padding: 8px 20px;
            background: var(--primary);
            color: white;
            border: none;
            border-radius: 6px;
            font-size: 13px;
            font-weight: 600;
            cursor: pointer;
            transition: background 0.2s;
        }
        .btn-read:hover { background: var(--primary-dark); }
        .free-badge {
            display: inline-block;
            background: #D1FAE5;
            color: #065F46;
            padding: 2px 8px;
            border-radius: 4px;
            font-size: 11px;
            font-weight: 700;
            margin-left: 8px;
        }

        /* ===== 旅游景点 ===== */
        .travel-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
            gap: 24px;
        }
        .travel-card {
            background: var(--white);
            border-radius: var(--radius);
            overflow: hidden;
            box-shadow: var(--shadow);
            display: flex;
            transition: transform 0.3s;
        }
        .travel-card:hover { transform: translateY(-4px); }
        .travel-img {
            width: 160px;
            min-height: 180px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 48px;
            flex-shrink: 0;
        }
        .travel-info { padding: 20px; flex: 1; }
        .travel-info h3 { font-size: 17px; margin-bottom: 6px; }
        .travel-info .location { font-size: 13px; color: var(--text-gray); margin-bottom: 8px; }
        .travel-info .desc { font-size: 13px; color: var(--text-gray); margin-bottom: 12px; line-height: 1.5; }
        .travel-tags { display: flex; gap: 6px; flex-wrap: wrap; }
        .travel-tag {
            padding: 3px 10px;
            background: rgba(0,102,204,0.08);
            color: var(--primary);
            border-radius: 6px;
            font-size: 11px;
            font-weight: 600;
        }

        /* ===== 阅读弹窗 ===== */
        .modal-overlay {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,0.6);
            z-index: 2000;
            justify-content: center;
            align-items: center;
        }
        .modal-overlay.show { display: flex; }
        .modal {
            background: var(--white);
            border-radius: 16px;
            width: 90%;
            max-width: 720px;
            max-height: 80vh;
            overflow-y: auto;
            padding: 40px;
            position: relative;
        }
        .modal-close {
            position: absolute;
            top: 16px;
            right: 16px;
            width: 36px;
            height: 36px;
            border: none;
            background: var(--bg-light);
            border-radius: 50%;
            font-size: 18px;
            cursor: pointer;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .modal h2 { font-size: 24px; margin-bottom: 8px; }
        .modal .meta { color: var(--text-gray); font-size: 14px; margin-bottom: 24px; }
        .modal .book-text { font-size: 15px; line-height: 2; color: #333; }
        .modal .book-text p { margin-bottom: 16px; text-indent: 2em; }

        /* ===== 购物车弹窗 ===== */
        .cart-modal .modal {
            max-width: 500px;
            padding: 32px;
        }
        .cart-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 12px 0;
            border-bottom: 1px solid #F0F0F0;
        }
        .cart-item-info h4 { font-size: 14px; }
        .cart-item-info span { font-size: 13px; color: var(--text-gray); }
        .cart-item-actions { display: flex; align-items: center; gap: 12px; }
        .qty-btn {
            width: 28px;
            height: 28px;
            border: 1px solid #E5E7EB;
            background: var(--white);
            border-radius: 6px;
            cursor: pointer;
            font-size: 16px;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .cart-total {
            margin-top: 20px;
            padding-top: 16px;
            border-top: 2px solid #F0F0F0;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .cart-total .price { font-size: 24px; font-weight: 700; color: var(--accent); }

        /* ===== FOOTER ===== */
        footer {
            background: var(--text-dark);
            color: rgba(255,255,255,0.7);
            padding: 48px 24px;
            text-align: center;
        }
        footer .footer-inner {
            max-width: 1200px;
            margin: 0 auto;
        }
        footer h3 { color: white; font-size: 20px; margin-bottom: 8px; }
        footer p { font-size: 14px; margin-bottom: 4px; }
        footer .divider { width: 60px; height: 3px; background: var(--primary); margin: 24px auto; border-radius: 2px; }

        /* ===== RESPONSIVE ===== */
        @media (max-width: 768px) {
            .nav-links { display: none; }
            .hamburger { display: block; }
            .nav-links.open {
                display: flex;
                flex-direction: column;
                position: absolute;
                top: 64px;
                left: 0;
                right: 0;
                background: white;
                padding: 20px;
                gap: 16px;
                box-shadow: 0 4px 20px rgba(0,0,0,0.1);
            }
            .hero h1 { font-size: 32px; }
            .hero-stats { gap: 30px; }
            .hero-stat .num { font-size: 28px; }
            .search-form { flex-direction: column; }
            .form-group { min-width: 100%; }
            .travel-card { flex-direction: column; }
            .travel-img { width: 100%; min-height: 140px; }
            .meal-grid { grid-template-columns: repeat(auto-fill, minmax(180px, 1fr)); }
            .train-table { overflow-x: auto; }
        }

        /* ===== ANIMATIONS ===== */
        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .animate { opacity: 0; }
        .animate.visible {
            animation: fadeInUp 0.6s ease forwards;
        }
    </style>
</head>
<body>

<!-- NAV -->
<nav id="navbar">
    <div class="nav-inner">
        <a href="#" class="logo">
            <svg viewBox="0 0 32 32" fill="none">
                <rect width="32" height="32" rx="8" fill="#0066CC"/>
                <path d="M8 20h16M12 14h8M10 24h12" stroke="white" stroke-width="2" stroke-linecap="round"/>
                <circle cx="16" cy="10" r="3" stroke="white" stroke-width="2"/>
            </svg>
            中国高铁
        </a>
        <ul class="nav-links" id="navLinks">
            <li><a href="#trains" class="active">车次查询</a></li>
            <li><a href="#stations">车站信息</a></li>
            <li><a href="#facilities">设施设备</a></li>
            <li><a href="#meals">高铁订餐</a></li>
            <li><a href="#books">铁路书籍</a></li>
            <li><a href="#travel">旅游景点</a></li>
        </ul>
        <button class="hamburger" onclick="toggleNav()">☰</button>
    </div>
</nav>

<!-- HERO -->
<div class="hero">
    <h1>🚄 畅行中国 高铁无界</h1>
    <p>覆盖全国主要城市，时速高达350km/h，为您提供安全、舒适、高效的出行体验</p>
    <div class="hero-stats">
        <div class="hero-stat">
            <div class="num">42,000+</div>
            <div class="label">运营里程(km)</div>
        </div>
        <div class="hero-stat">
            <div class="num">350</div>
            <div class="label">最高时速(km/h)</div>
        </div>
        <div class="hero-stat">
            <div class="num">5,600+</div>
            <div class="label">日均列车(列)</div>
        </div>
    </div>
</div>

<!-- 车次查询 -->
<section id="trains">
    <div class="section-header animate">
        <span class="section-tag">实时查询</span>
        <h2>高铁车次查询</h2>
        <p>输入出发地和目的地，快速查询列车信息</p>
    </div>
    <div class="search-box animate">
        <div class="search-form">
            <div class="form-group">
                <label>出发城市</label>
                <input type="text" id="fromCity" placeholder="如：北京" value="北京">
            </div>
            <div class="form-group">
                <label>到达城市</label>
                <input type="text" id="toCity" placeholder="如：上海" value="上海">
            </div>
            <div class="form-group">
                <label>出发日期</label>
                <input type="date" id="travelDate">
            </div>
            <button class="btn btn-primary" onclick="searchTrains()">🔍 查询车次</button>
        </div>
    </div>
    <div class="train-table animate" id="trainResult">
        <table>
            <thead>
                <tr>
                    <th>车次</th>
                    <th>出发站</th>
                    <th>到达站</th>
                    <th>出发时间</th>
                    <th>到达时间</th>
                    <th>历时</th>
                    <th>商务座</th>
                    <th>一等座</th>
                    <th>二等座</th>
                    <th>状态</th>
                </tr>
            </thead>
            <tbody id="trainBody"></tbody>
        </table>
    </div>
</section>

<!-- 车站信息 -->
<section id="stations">
    <div class="section-header animate">
        <span class="section-tag">枢纽站点</span>
        <h2>高铁车站信息</h2>
        <p>主要高铁枢纽车站详细信息</p>
    </div>
    <div class="station-grid animate">
        <div class="station-card">
            <div class="station-img" style="background: linear-gradient(135deg, #E53E3E, #C53030);">🏛️</div>
            <div class="station-info">
                <h3>北京南站</h3>
                <p>亚洲最大火车站之一，京沪高铁起点，建筑面积约32万平方米，日均客流量超15万人次。</p>
                <div class="station-tags">
                    <span class="station-tag">特等站</span>
                    <span class="station-tag">13台24线</span>
                    <span class="station-tag">京沪高铁</span>
                    <span class="station-tag">地铁4/14号线</span>
                </div>
            </div>
        </div>
        <div class="station-card">
            <div class="station-img" style="background: linear-gradient(135deg, #3182CE, #2C5282);">🌊</div>
            <div class="station-info">
                <h3>上海虹桥站</h3>
                <p>华东地区最大铁路枢纽，与虹桥机场无缝衔接，建筑面积约44万平方米。</p>
                <div class="station-tags">
                    <span class="station-tag">特等站</span>
                    <span class="station-tag">16台30线</span>
                    <span class="station-tag">京沪/沪昆高铁</span>
                    <span class="station-tag">地铁2/10/17号线</span>
                </div>
            </div>
        </div>
        <div class="station-card">
            <div class="station-img" style="background: linear-gradient(135deg, #D69E2E, #B7791F);">🐼</div>
            <div class="station-info">
                <h3>成都东站</h3>
                <p>西南地区重要高铁枢纽，建筑面积约22万平方米，是西成高铁、成渝高铁的核心站点。</p>
                <div class="station-tags">
                    <span class="station-tag">特等站</span>
                    <span class="station-tag">14台26线</span>
                    <span class="station-tag">西成/成渝高铁</span>
                    <span class="station-tag">地铁2/7号线</span>
                </div>
            </div>
        </div>
        <div class="station-card">
            <div class="station-img" style="background: linear-gradient(135deg, #38A169, #276749);">🌸</div>
            <div class="station-info">
                <h3>武汉站</h3>
                <p>中部地区高铁心脏，京广高铁与沪汉蓉铁路交汇点，建筑面积约37万平方米。</p>
                <div class="station-tags">
                    <span class="station-tag">特等站</span>
                    <span class="station-tag">11台20线</span>
                    <span class="station-tag">京广高铁</span>
                    <span class="station-tag">地铁4/5号线</span>
                </div>
            </div>
        </div>
        <div class="station-card">
            <div class="station-img" style="background: linear-gradient(135deg, #805AD5, #553C9A);">🌙</div>
            <div class="station-info">
                <h3>广州南站</h3>
                <p>华南地区最大高铁站，京广高铁南端终点，日均客流量全国前列，建筑面积约61.5万平方米。</p>
                <div class="station-tags">
                    <span class="station-tag">特等站</span>
                    <span class="station-tag">15台28线</span>
                    <span class="station-tag">京广/广深港高铁</span>
                    <span class="station-tag">地铁2/7/22号线</span>
                </div>
            </div>
        </div>
        <div class="station-card">
            <div class="station-img" style="background: linear-gradient(135deg, #DD6B20, #C05621);">🏰</div>
            <div class="station-info">
                <h3>西安北站</h3>
                <p>西北地区最大高铁站，建筑面积约33.6万平方米，郑西、西宝、大西高铁交汇于此。</p>
                <div class="station-tags">
                    <span class="station-tag">特等站</span>
                    <span class="station-tag">18台34线</span>
                    <span class="station-tag">郑西/西宝高铁</span>
                    <span class="station-tag">地铁2/4/14号线</span>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- 设施设备 -->
<section id="facilities">
    <div class="section-header animate">
        <span class="section-tag">舒适体验</span>
        <h2>列车设施设备</h2>
        <p>复兴号智能动车组为您提供全方位的舒适体验</p>
    </div>
    <div class="facility-grid animate">
        <div class="facility-card">
            <div class="facility-icon">💺</div>
            <h3>智能座椅</h3>
            <p>人体工学设计，可调节靠背角度，配备USB充电口和阅读灯，商务座支持180°平躺。</p>
        </div>
        <div class="facility-card">
            <div class="facility-icon">📶</div>
            <h3>全车WiFi</h3>
            <p>全列车覆盖高速WiFi网络，支持在线视频、游戏、办公，让您旅途不间断。</p>
        </div>
        <div class="facility-card">
            <div class="facility-icon">🍽️</div>
            <h3>餐车服务</h3>
            <p>5号车厢设有餐车，提供热链盒饭、冷链套餐、零食饮品，支持手机扫码点餐送座。</p>
        </div>
        <div class="facility-card">
            <div class="facility-icon">❄️</div>
            <h3>空调系统</h3>
            <p>智能温控系统，根据室外温度自动调节，每节车厢独立控制，确保舒适温度。</p>
        </div>
        <div class="facility-card">
            <div class="facility-icon">🚻</div>
            <h3>无障碍卫生间</h3>
            <p>每列车配备无障碍卫生间，空间宽敞，配有扶手、紧急呼叫按钮，方便特殊旅客使用。</p>
        </div>
        <div class="facility-card">
            <div class="facility-icon">👶</div>
            <h3>母婴护理台</h3>
            <p>专用母婴室配备护理台、温奶器、热水等设备，为带婴儿出行的旅客提供便利。</p>
        </div>
        <div class="facility-card">
            <div class="facility-icon">📺</div>
            <h3>信息显示屏</h3>
            <p>车厢两端设LED信息屏，实时显示车速、到站信息、车厢温度、前方景点等。</p>
        </div>
        <div class="facility-card">
            <div class="facility-icon">🧳</div>
            <h3>大件行李架</h3>
            <p>每节车厢连接处设专用大件行李存放区，配备固定绑带，确保行李安全。</p>
        </div>
    </div>
</section>

<!-- 高铁订餐 -->
<section id="meals">
    <div class="section-header animate">
        <span class="section-tag">旅途美食</span>
        <h2>高铁订餐</h2>
        <p>精选各地特色美食，扫码下单，送餐到座</p>
    </div>
    <div class="meal-section animate">
        <div class="meal-tabs">
            <button class="meal-tab active" onclick="switchMealTab(this, 'hot')">🍱 热链套餐</button>
            <button class="meal-tab" onclick="switchMealTab(this, 'cold')">🥗 冷链精选</button>
            <button class="meal-tab" onclick="switchMealTab(this, 'snack')">🍪 零食饮品</button>
            <button class="meal-tab" onclick="switchMealTab(this, 'special')">⭐ 地方特色</button>
        </div>
        <div class="meal-grid" id="mealGrid"></div>
    </div>
</section>

<!-- 铁路书籍 -->
<section id="books">
    <div class="section-header animate">
        <span class="section-tag">免费阅读</span>
        <h2>铁路主题书籍</h2>
        <p>精选铁路文化与历史书籍，纯公益阅读，不售卖</p>
    </div>
    <div class="books-note animate">
        📢 本平台所有书籍均为公益性质，免费开放阅读，不提供购买功能。旨在传播铁路文化，让更多人了解中国铁路发展历程。
    </div>
    <div class="books-grid animate">
        <div class="book-card">
            <div class="book-cover" style="background: linear-gradient(135deg, #1A365D, #2A4365);">
                📖<br>中国高铁<br>创新发展之路
            </div>
            <div class="book-content">
                <h3>中国高铁创新发展之路 <span class="free-badge">免费</span></h3>
                <div class="author">作者：张明远</div>
                <div class="intro">全面记录中国高铁从引进、消化、吸收到自主创新的发展历程，揭秘复兴号背后的技术突破。</div>
                <button class="btn-read" onclick="openBook(0)">📖 立即阅读</button>
            </div>
        </div>
        <div class="book-card">
            <div class="book-cover" style="background: linear-gradient(135deg, #744210, #975A16);">
                📖<br>百年中国<br>铁路史话
            </div>
            <div class="book-content">
                <h3>百年中国铁路史话 <span class="free-badge">免费</span></h3>
                <div class="author">作者：李铁道</div>
                <div class="intro">从唐胥铁路到京张高铁，梳理中国铁路150年波澜壮阔的发展史，讲述一代代铁路人的奋斗故事。</div>
                <button class="btn-read" onclick="openBook(1)">📖 立即阅读</button>
            </div>
        </div>
        <div class="book-card">
            <div class="book-cover" style="background: linear-gradient(135deg, #285E61, #2C7A7B);">
                📖<br>高铁乘务<br>服务指南
            </div>
            <div class="book-content">
                <h3>高铁乘务服务指南 <span class="free-badge">免费</span></h3>
                <div class="author">作者：王丽华</div>
                <div class="intro">详细介绍高铁乘务工作流程、服务标准、应急处理等，是了解高铁乘务工作的权威读本。</div>
                <button class="btn-read" onclick="openBook(2)">📖 立即阅读</button>
            </div>
        </div>
        <div class="book-card">
            <div class="book-cover" style="background: linear-gradient(135deg, #553C9A, #6B46C1);">
                📖<br>轨道上的<br>中国
            </div>
            <div class="book-content">
                <h3>轨道上的中国 <span class="free-badge">免费</span></h3>
                <div class="author">作者：陈晓风</div>
                <div class="intro">以铁路为线索，描绘中国大地上的城市变迁、人文风情和经济发展，展现铁轨上的中国画卷。</div>
                <button class="btn-read" onclick="openBook(3)">📖 立即阅读</button>
            </div>
        </div>
        <div class="book-card">
            <div class="book-cover" style="background: linear-gradient(135deg, #9B2C2C, #C53030);">
                📖<br>詹天佑<br>与中国铁路
            </div>
            <div class="book-content">
                <h3>詹天佑与中国铁路 <span class="free-badge">免费</span></h3>
                <div class="author">作者：赵铁生</div>
                <div class="intro">讲述"中国铁路之父"詹天佑的传奇人生，从京张铁路的人字形设计到自主修建的第一条干线铁路。</div>
                <button class="btn-read" onclick="openBook(4)">📖 立即阅读</button>
            </div>
        </div>
        <div class="book-card">
            <div class="book-cover" style="background: linear-gradient(135deg, #276749, #38A169);">
                📖<br>高铁旅行<br>完全手册
            </div>
            <div class="book-content">
                <h3>高铁旅行完全手册 <span class="free-badge">免费</span></h3>
                <div class="author">作者：孙行者</div>
                <div class="intro">实用的高铁出行指南，涵盖购票攻略、乘车须知、沿途景点推荐、美食攻略等实用信息。</div>
                <button class="btn-read" onclick="openBook(5)">📖 立即阅读</button>
            </div>
        </div>
    </div>
</section>

<!-- 旅游景点 -->
<section id="travel">
    <div class="section-header animate">
        <span class="section-tag">沿途风光</span>
        <h2>高铁沿线旅游景点</h2>
        <p>乘坐高铁，沿途发现中国之美</p>
    </div>
    <div class="travel-grid animate">
        <div class="travel-card">
            <div class="travel-img" style="background: linear-gradient(135deg, #FED7D7, #FEB2B2);">🏯</div>
            <div class="travel-info">
                <h3>故宫博物院</h3>
                <div class="location">📍 北京 · 距北京南站约30分钟地铁</div>
                <div class="desc">中国最大的古代文化艺术博物馆，世界现存规模最大的宫殿建筑群，拥有近70万件珍贵文物。</div>
                <div class="travel-tags">
                    <span class="travel-tag">世界遗产</span>
                    <span class="travel-tag">5A景区</span>
                    <span class="travel-tag">历史文化</span>
                </div>
            </div>
        </div>
        <div class="travel-card">
            <div class="travel-img" style="background: linear-gradient(135deg, #C6F6D5, #9AE6B4);">🌿</div>
            <div class="travel-info">
                <h3>杭州西湖</h3>
                <div class="location">📍 杭州 · 距杭州东站约25分钟地铁</div>
                <div class="desc">"欲把西湖比西子，淡妆浓抹总相宜"，湖光山色与人文景观完美融合的世界文化遗产。</div>
                <div class="travel-tags">
                    <span class="travel-tag">世界遗产</span>
                    <span class="travel-tag">免费开放</span>
                    <span class="travel-tag">自然风光</span>
                </div>
            </div>
        </div>
        <div class="travel-card">
            <div class="travel-img" style="background: linear-gradient(135deg, #FEEBC8, #FBD38D);">🗻</div>
            <div class="travel-info">
                <h3>泰山风景区</h3>
                <div class="location">📍 泰安 · 距泰安站约40分钟车程</div>
                <div class="desc">五岳之首，自古被视为直通帝座的天堂。泰山日出、云海玉盘、晚霞夕照为三大奇观。</div>
                <div class="travel-tags">
                    <span class="travel-tag">世界遗产</span>
                    <span class="travel-tag">5A景区</span>
                    <span class="travel-tag">登山徒步</span>
                </div>
            </div>
        </div>
        <div class="travel-card">
            <div class="travel-img" style="background: linear-gradient(135deg, #E9D8FD, #D6BCFA);">🏔️</div>
            <div class="travel-info">
                <h3>西安兵马俑</h3>
                <div class="location">📍 西安 · 距西安北站约50分钟车程</div>
                <div class="desc">"世界第八大奇迹"，秦始皇陵兵马俑坑，8000余件陶俑陶马，排列成严整的军阵。</div>
                <div class="travel-tags">
                    <span class="travel-tag">世界遗产</span>
                    <span class="travel-tag">5A景区</span>
                    <span class="travel-tag">历史遗迹</span>
                </div>
            </div>
        </div>
        <div class="travel-card">
            <div class="travel-img" style="background: linear-gradient(135deg, #BEE3F8, #90CDF4);">🌊</div>
            <div class="travel-info">
                <h3>桂林山水</h3>
                <div class="location">📍 桂林 · 距桂林北站约30分钟车程</div>
                <div class="desc">"桂林山水甲天下"，漓江两岸奇峰倒影、碧水青山，如诗如画的喀斯特地貌景观。</div>
                <div class="travel-tags">
                    <span class="travel-tag">5A景区</span>
                    <span class="travel-tag">自然风光</span>
                    <span class="travel-tag">漓江漂流</span>
                </div>
            </div>
        </div>
        <div class="travel-card">
            <div class="travel-img" style="background: linear-gradient(135deg, #FEFCBF, #FAF089);">🌸</div>
            <div class="travel-info">
                <h3>成都大熊猫基地</h3>
                <div class="location">📍 成都 · 距成都东站约35分钟车程</div>
                <div class="desc">全球最大的大熊猫繁育研究基地，近距离观赏国宝大熊猫，感受萌宠魅力。</div>
                <div class="travel-tags">
                    <span class="travel-tag">4A景区</span>
                    <span class="travel-tag">亲子游</span>
                    <span class="travel-tag">生态观光</span>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- FOOTER -->
<footer>
    <div class="footer-inner">
        <h3>🚄 中国高铁 · 畅行无忧</h3>
        <p>让出行更美好，让旅途更精彩</p>
        <div class="divider"></div>
        <p>服务热线：12306 | 官方网站：www.12306.cn</p>
        <p style="margin-top: 16px; font-size: 12px; opacity: 0.5;">© 2024 高铁信息服务平台 · 本站为演示网站，所有数据均为虚拟</p>
    </div>
</footer>

<!-- 购物车浮动按钮 -->
<div class="cart-bar" onclick="openCart()">
    🛒
    <span class="cart-count" id="cartCount">0</span>
</div>

<!-- 阅读弹窗 -->
<div class="modal-overlay" id="bookModal">
    <div class="modal">
        <button class="modal-close" onclick="closeBook()">✕</button>
        <h2 id="bookTitle"></h2>
        <div class="meta" id="bookMeta"></div>
        <div class="book-text" id="bookText"></div>
    </div>
</div>

<!-- 购物车弹窗 -->
<div class="modal-overlay cart-modal" id="cartModal">
    <div class="modal">
        <button class="modal-close" onclick="closeCart()">✕</button>
        <h2>🛒 我的餐车</h2>
        <div id="cartItems"></div>
        <div class="cart-total" id="cartTotal" style="display:none;">
            <span>合计：</span>
            <span class="price" id="cartTotalPrice">¥0</span>
            <button class="btn btn-accent" onclick="checkout()" style="margin-left: 16px;">提交订单</button>
        </div>
        <p id="cartEmpty" style="text-align:center; color: var(--text-gray); padding: 40px 0;">购物车空空如也，快去挑选美食吧~</p>
    </div>
</div>

<script>
    // ===== 数据 =====
    const trainsData = [
        { no: 'G1', from: '北京南', to: '上海虹桥', dep: '06:36', arr: '11:18', dur: '4h42m', business: 6, first: 18, second: 86, status: '可预订' },
        { no: 'G3', from: '北京南', to: '上海虹桥', dep: '07:00', arr: '11:40', dur: '4h40m', business: 3, first: 12, second: 54, status: '可预订' },
        { no: 'G5', from: '北京南', to: '上海虹桥', dep: '07:36', arr: '12:22', dur: '4h46m', business: 0, first: 6, second: 23, status: '可预订' },
        { no: 'G7', from: '北京南', to: '上海虹桥', dep: '08:00', arr: '12:38', dur: '4h38m', business: 8, first: 22, second: 108, status: '可预订' },
        { no: 'G9', from: '北京南', to: '上海虹桥', dep: '09:00', arr: '13:48', dur: '4h48m', business: 4, first: 15, second: 67, status: '可预订' },
        { no: 'G11', from: '北京南', to: '上海虹桥', dep: '10:00', arr: '14:36', dur: '4h36m', business: 2, first: 9, second: 31, status: '可预订' },
    ];

    const mealsData = {
        hot: [
            { name: '京味红烧肉套餐', desc: '红烧肉+米饭+时蔬+汤', price: 45, emoji: '🍖' },
            { name: '鱼香肉丝套餐', desc: '鱼香肉丝+米饭+小菜+饮料', price: 38, emoji: '🍛' },
            { name: '宫保鸡丁套餐', desc: '宫保鸡丁+米饭+水果+酸奶', price: 42, emoji: '🍗' },
            { name: '红烧牛腩套餐', desc: '红烧牛腩+米饭+青菜+例汤', price: 48, emoji: '🥩' },
            { name: '番茄鸡蛋套餐', desc: '番茄炒蛋+米饭+蔬菜沙拉', price: 32, emoji: '🍅' },
            { name: '黑椒牛柳套餐', desc: '黑椒牛柳+意面+玉米浓汤', price: 52, emoji: '🥘' },
        ],
        cold: [
            { name: '三文鱼沙拉', desc: '新鲜三文鱼+混合蔬菜+油醋汁', price: 38, emoji: '🥗' },
            { name: '鸡肉凯撒卷', desc: '烤鸡肉+生菜+凯撒酱+全麦卷', price: 35, emoji: '🌯' },
            { name: '日式便当', desc: '寿司拼盘+味噌汤+日式小菜', price: 42, emoji: '🍱' },
            { name: '越南春卷套餐', desc: '鲜虾春卷+花生酱+水果杯', price: 36, emoji: '🥢' },
        ],
        snack: [
            { name: '综合坚果礼包', desc: '混合坚果200g+蔓越莓干', price: 28, emoji: '🥜' },
            { name: '饼干礼盒', desc: '曲奇饼干+蛋卷+巧克力', price: 22, emoji: '🍪' },
            { name: '新鲜果汁', desc: '橙汁/苹果汁 350ml', price: 15, emoji: '🧃' },
            { name: '精品咖啡', desc: '现磨美式/拿铁 330ml', price: 25, emoji: '☕' },
            { name: '矿泉水', desc: '农夫山泉 550ml', price: 5, emoji: '💧' },
            { name: '酸奶', desc: '伊利/蒙牛 200g', price: 8, emoji: '🥛' },
        ],
        special: [
            { name: '南京盐水鸭', desc: '正宗金陵盐水鸭200g+烧饼', price: 42, emoji: '🦆' },
            { name: '武汉热干面', desc: '正宗蔡林记热干面+蛋酒', price: 28, emoji: '🍜' },
            { name: '西安肉夹馍', desc: '腊汁肉夹馍+冰峰汽水', price: 32, emoji: '🥙' },
            { name: '广东煲仔饭', desc: '广式腊味煲仔饭+老火汤', price: 45, emoji: '🍚' },
            { name: '四川担担面', desc: '麻辣担担面+冰粉', price: 30, emoji: '🌶️' },
            { name: '上海小笼包', desc: '南翔小笼包12只+酸辣汤', price: 38, emoji: '🥟' },
        ]
    };

    const booksData = [
        {
            title: '中国高铁创新发展之路',
            author: '张明远 著',
            publisher: '人民铁道出版社',
            content: `<p>中国高铁，作为国家名片，其发展历程是一部波澜壮阔的创新史诗。从2004年引进消化吸收再创新，到2017年"复兴号"中国标准动车组投入运营，中国高铁用短短十余年时间走完了发达国家半个世纪的历程。</p>
            <p>第一章讲述的是中国高铁的起步。2004年1月，国务院常务会议审议通过了《中长期铁路网规划》，明确提出建设"四纵四横"客运专线。同年，原铁道部通过"引进先进技术、联合设计生产、打造中国品牌"的方针，与德国西门子、法国阿尔斯通、日本川崎重工等企业合作，开始了中国高铁的技术引进之路。</p>
            <p>在引进技术的同时，中国铁路科研人员从未停止自主创新的步伐。通过对引进技术的消化吸收，结合中国特有的地理环境和运营需求，中国工程师们攻克了高原铁路、高寒铁路、热带铁路等一系列世界性难题。</p>
            <p>2017年6月26日，"复兴号"中国标准动车组在京沪高铁双向首发。这标志着中国高铁技术实现了从"跟跑"到"领跑"的历史性跨越。复兴号具有完全自主知识产权，采用254项重要标准中中国标准占84%，整体设计和关键技术全部自主研发。</p>
            <p>截至2023年底，中国高铁运营里程突破4.5万公里，稳居世界第一。"八纵八横"高铁网日益完善，高铁已成为中国人民出行的首选方式，也成为连接中国经济社会高质量发展的重要纽带。</p>`
        },
        {
            title: '百年中国铁路史话',
            author: '李铁道 著',
            publisher: '中国铁道出版社',
            content: `<p>中国铁路的历史，是一部浓缩的中国近现代史。从1876年中国第一条铁路——吴淞铁路的建成，到今天高铁网络覆盖全国，中国铁路走过了150多年的风雨历程。</p>
            <p>1881年，唐胥铁路建成通车，这是中国自建的第一条标准轨距铁路。虽然最初只有一条9.7公里的短线，但它标志着中国铁路建设的正式起步。为了不让蒸汽机车"震动皇陵"，清政府甚至要求用骡马牵引列车，这段历史被后人戏称为"马车铁路"。</p>
            <p>1909年，詹天佑主持修建的京张铁路全线通车。这条铁路穿越居庸关、八达岭，创造性地设计了"人"字形线路，解决了坡度难题，成为中国铁路史上的里程碑。这是第一条完全由中国人自行设计和建造的干线铁路。</p>
            <p>新中国成立后，铁路建设进入快速发展期。成渝铁路、宝成铁路、成昆铁路等重大工程相继建成。特别是成昆铁路，穿越地质最复杂的山区，被联合国誉为"象征二十世纪人类征服自然的三大奇迹"之一。</p>
            <p>改革开放以来，中国铁路经历了多次大提速。2007年第六次大提速后，"和谐号"动车组正式上线运营，中国正式迈入高铁时代。从此，中国铁路开启了令世界瞩目的发展加速度。</p>`
        },
        {
            title: '高铁乘务服务指南',
            author: '王丽华 著',
            publisher: '中国铁道出版社',
            content: `<p>高铁乘务员是铁路服务的重要窗口，她们的服务质量直接影响旅客的出行体验。本书系统介绍了高铁乘务工作的各项标准与流程，是了解高铁乘务工作的权威指南。</p>
            <p>高铁乘务员的上岗有着严格的标准。首先需要通过铁路院校的專業培训，掌握铁路基础知识、服务礼仪、应急处理等技能。上岗前还需通过体检、面试、实操考核等多重筛选。</p>
            <p>每天出乘前，乘务组需要进行班前准备会，明确列车运行区段、重点旅客信息、应急预案等内容。乘务员的仪容仪表也有严格规定：统一着装、妆容得体、佩戴工牌、微笑服务。</p>
            <p>在列车运行过程中，乘务员需要完成验票、引导、解答咨询、清洁卫生、餐饮供应等多项工作。对于重点旅客（老幼病残孕），乘务组会提供"一对一"的贴心服务，确保他们的旅途安全舒适。</p>
            <p>应急处理是乘务员的重要能力。遇到设备故障、旅客突发疾病、恶劣天气等情况时，乘务员需要冷静应对，按照标准流程进行处置，最大程度保障旅客安全和列车秩序。</p>`
        },
        {
            title: '轨道上的中国',
            author: '陈晓风 著',
            publisher: '中信出版社',
            content: `<p>铁路，是观察中国发展的最佳窗口。从绿皮慢车到复兴号动车，从"一票难求"到手机购票，从"铁老大"到"人民铁路为人民"，铁路的变迁折射出中国社会的巨大变革。</p>
            <p>本书以铁路为线索，走访了沿线数十座城市和乡村，记录了铁轨上的中国故事。在东北，我们看到高铁如何振兴老工业基地；在西北，我们见证铁路如何打通丝绸之路经济带；在西南，我们感受高铁如何让"蜀道难"成为历史。</p>
            <p>高铁不仅改变了人们的出行方式，更重塑了中国的经济地理格局。"同城效应"让京津冀、长三角、珠三角城市群联系更加紧密。"双城生活"成为现实，早上在广州喝早茶，中午在长沙吃湘菜，晚上在武汉看夜景，已不再是梦想。</p>
            <p>铁路沿线的小站也发生了翻天覆地的变化。一些曾经默默无闻的小镇，因为高铁站的设立而焕发新生。站前广场拔地而起，商业街区鳞次栉比，高铁正在成为中国新型城镇化的重要推动力。</p>`
        },
        {
            title: '詹天佑与中国铁路',
            author: '赵铁生 著',
            publisher: '商务印书馆',
            content: `<p>詹天佑（1861-1919），字眷诚，号达潮，广东南海人。他是中国近代铁路工程的奠基人，被誉为"中国铁路之父"。他的一生，与中国铁路的诞生和发展紧密相连。</p>
            <p>1872年，年仅12岁的詹天佑作为首批留美幼童之一赴美留学。1881年，他以优异成绩毕业于耶鲁大学土木工程系，主攻铁路工程。然而回国后，他却一度被派往福建水师学堂学习海船驾驶，才华无处施展。</p>
            <p>1905年，清政府决定自建京张铁路，任命詹天佑为总工程师。这条铁路从北京到张家口，全长201.2公里，沿途山高谷深，工程极为艰巨。尤其是居庸关至八达岭段，坡度陡峭，当时许多外国专家认为中国人不可能独立完成。</p>
            <p>面对困难，詹天佑创造性地设计了"人"字形线路，采用双机车牵引，成功解决了八达岭隧道段的爬坡难题。他还在施工中采用了"竖井开凿法"，大大缩短了隧道施工时间。1909年，京张铁路提前两年全线通车，耗资仅为外国预算的五分之一。</p>
            <p>詹天佑不仅是一位杰出的工程师，更是一位爱国者。他曾说："各出所学，各尽所知，使国家富强不受外侮，足以自立于地球之上。"这种精神，至今仍激励着每一位中国铁路人。</p>`
        },
        {
            title: '高铁旅行完全手册',
            author: '孙行者 著',
            publisher: '人民邮电出版社',
            content: `<p>高铁时代，旅行变得更加便捷高效。本书从实用角度出发，为您全面梳理高铁出行的各个环节，让您的旅途更加轻松愉快。</p>
            <p><strong>购票攻略：</strong>目前可通过12306官网、12306APP、车站窗口、代售点等多种渠道购票。建议提前15天以上购票，节假日期间更需尽早规划。学生票享受二等座7.5折优惠，儿童票按身高或年龄优惠。</p>
            <p><strong>乘车须知：</strong>建议提前30-40分钟到达车站，预留安检和检票时间。携带有效身份证件，目前全国高铁站均已支持电子客票，刷身份证即可进站乘车。行李重量不超过20公斤，长宽高之和不超过130厘米。</p>
            <p><strong>座位选择：</strong>二等座采用"3+2"布局，性价比最高；一等座采用"2+2"布局，空间更宽敞；商务座采用"2+1"或"1+1"布局，可平躺休息。靠窗座位风景更好，过道座位出入方便。</p>
            <p><strong>餐饮服务：</strong>列车餐车一般位于5号或9号车厢，提供热链盒饭、冷链套餐和零食饮品。也可通过12306APP提前预订沿途车站的社会品牌餐饮，列车工作人员会送餐到您的座位。</p>
            <p><strong>沿途风景：</strong>中国高铁穿越壮美山河，沿途风景如画。京沪高铁途经华北平原、江南水乡；沪昆高铁穿越华东丘陵、云贵高原；哈大高铁纵贯东北平原。善用高铁旅行，每一步都是风景。</p>`
        }
    ];

    let cart = [];

    // ===== 初始化 =====
    document.addEventListener('DOMContentLoaded', () => {
        searchTrains();
        switchMealTab(document.querySelector('.meal-tab.active'), 'hot');
        // 设置默认日期为明天
        const tomorrow = new Date();
        tomorrow.setDate(tomorrow.getDate() + 1);
        document.getElementById('travelDate').value = tomorrow.toISOString().split('T')[0];

        // 滚动动画
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                }
            });
        }, { threshold: 0.1 });
        document.querySelectorAll('.animate').forEach(el => observer.observe(el));

        // 导航滚动效果
        window.addEventListener('scroll', () => {
            document.getElementById('navbar').classList.toggle('scrolled', window.scrollY > 10);
        });
    });

    // ===== 导航 =====
    function toggleNav() {
        document.getElementById('navLinks').classList.toggle('open');
    }

    // 平滑滚动
    document.querySelectorAll('.nav-links a').forEach(link => {
        link.addEventListener('click', (e) => {
            e.preventDefault();
            const target = document.querySelector(link.getAttribute('href'));
            if (target) {
                target.scrollIntoView({ behavior: 'smooth', block: 'start' });
            }
            document.querySelectorAll('.nav-links a').forEach(l => l.classList.remove('active'));
            link.classList.add('active');
            document.getElementById('navLinks').classList.remove('open');
        });
    });

    // ===== 车次查询 =====
    function searchTrains() {
        const tbody = document.getElementById('trainBody');
        tbody.innerHTML = '';
        trainsData.forEach(t => {
            const row = document.createElement('tr');
            row.innerHTML = `
                <td><span class="train-number">${t.no}</span></td>
                <td>${t.from}</td>
                <td>${t.to}</td>
                <td><span class="time-big">${t.dep}</span></td>
                <td><span class="time-big">${t.arr}</span></td>
                <td><span class="duration">${t.dur}</span></td>
                <td>¥${(parseInt(t.business) > 0 ? '1,748' : '—')}</td>
                <td>¥${(parseInt(t.first) > 0 ? '933' : '—')}</td>
                <td>¥${(parseInt(t.second) > 0 ? '553' : '—')}</td>
                <td><span class="status-badge ${parseInt(t.second) > 20 ? 'status-on' : 'status-wait'}">${parseInt(t.second) > 20 ? '充足' : (parseInt(t.second) > 0 ? '紧张' : '候补')}</span></td>
            `;
            tbody.appendChild(row);
        });
    }

    // ===== 高铁订餐 =====
    function switchMealTab(btn, type) {
        document.querySelectorAll('.meal-tab').forEach(t => t.classList.remove('active'));
        btn.classList.add('active');
        const grid = document.getElementById('mealGrid');
        grid.innerHTML = '';
        mealsData[type].forEach(m => {
            grid.innerHTML += `
                <div class="meal-card">
                    <div class="meal-img">${m.emoji}</div>
                    <div class="meal-detail">
                        <h4>${m.name}</h4>
                        <div class="desc">${m.desc}</div>
                        <div class="meal-bottom">
                            <span class="meal-price">¥${m.price}</span>
                            <button class="meal-btn" onclick="addToCart('${m.name}', ${m.price})">加入购物车</button>
                        </div>
                    </div>
                </div>
            `;
        });
    }

    function addToCart(name, price) {
        const existing = cart.find(item => item.name === name);
        if (existing) {
            existing.qty++;
        } else {
            cart.push({ name, price, qty: 1 });
        }
        updateCartCount();
        // 简单动画提示
        const btn = event.target;
        btn.textContent = '已加入 ✓';
        btn.style.background = 'var(--primary)';
        btn.style.color = 'white';
        setTimeout(() => {
            btn.textContent = '加入购物车';
            btn.style.background = '';
            btn.style.color = '';
        }, 1000);
    }

    function updateCartCount() {
        const total = cart.reduce((sum, item) => sum + item.qty, 0);
        document.getElementById('cartCount').textContent = total;
    }

    function openCart() {
        const modal = document.getElementById('cartModal');
        const itemsDiv = document.getElementById('cartItems');
        const totalDiv = document.getElementById('cartTotal');
        const emptyP = document.getElementById('cartEmpty');

        if (cart.length === 0) {
            itemsDiv.innerHTML = '';
            totalDiv.style.display = 'none';
            emptyP.style.display = 'block';
        } else {
            emptyP.style.display = 'none';
            totalDiv.style.display = 'flex';
            itemsDiv.innerHTML = cart.map((item, i) => `
                <div class="cart-item">
                    <div class="cart-item-info">
                        <h4>${item.name}</h4>
                        <span>¥${item.price} × ${item.qty}</span>
                    </div>
                    <div class="cart-item-actions">
                        <button class="qty-btn" onclick="changeQty(${i}, -1)">−</button>
                        <span>${item.qty}</span>
                        <button class="qty-btn" onclick="changeQty(${i}, 1)">+</button>
                    </div>
                </div>
            `).join('');
            const total = cart.reduce((sum, item) => sum + item.price * item.qty, 0);
            document.getElementById('cartTotalPrice').textContent = '¥' + total;
        }
        modal.classList.add('show');
    }

    function closeCart() {
        document.getElementById('cartModal').classList.remove('show');
    }

    function changeQty(index, delta) {
        cart[index].qty += delta;
        if (cart[index].qty <= 0) {
            cart.splice(index, 1);
        }
        updateCartCount();
        openCart();
    }

    function checkout() {
        if (cart.length === 0) return;
        const total = cart.reduce((sum, item) => sum + item.price * item.qty, 0);
        alert(`🎉 订单提交成功！\n\n共 ${cart.reduce((s, i) => s + i.qty, 0)} 件商品\n合计：¥${total}\n\n餐食将在旅途中送达您的座位。`);
        cart = [];
        updateCartCount();
        closeCart();
    }

    // ===== 书籍阅读 =====
    function openBook(index) {
        const book = booksData[index];
        document.getElementById('bookTitle').textContent = book.title;
        document.getElementById('bookMeta').textContent = `${book.author} · ${book.publisher}`;
        document.getElementById('bookText').innerHTML = book.content;
        document.getElementById('bookModal').classList.add('show');
        document.body.style.overflow = 'hidden';
    }

    function closeBook() {
        document.getElementById('bookModal').classList.remove('show');
        document.body.style.overflow = '';
    }

    // 点击遮罩关闭
    document.getElementById('bookModal').addEventListener('click', (e) => {
        if (e.target === e.currentTarget) closeBook();
    });
    document.getElementById('cartModal').addEventListener('click', (e) => {
        if (e.target === e.currentTarget) closeCart();
    });
</script>

</body>
</html>
