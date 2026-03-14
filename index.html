<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>Интеллектуальный клуб «Крысиная канцелярия»</title>
    <style>
        /* -------------------- RESET & GLOBAL (mobile first) -------------------- */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            background-color: #203127; /* основной фон из 1го */
            color: #bdbdbd;            /* основной цвет текста из 1го */
            line-height: 1.5;
            -webkit-font-smoothing: antialiased;
        }

        body.menu-open {
            overflow: hidden;
        }

        /* Контейнер: от маленьких экранов к большим */
        .container {
            width: 100%;
            max-width: 1400px;
            margin: 0 auto;
            padding: 0 20px;
        }

        @media (min-width: 768px) {
            .container {
                padding: 0 40px;
            }
        }

        @media (min-width: 1200px) {
            .container {
                padding: 0 60px;
            }
        }

        /* -------------------- ТИПОГРАФИКА -------------------- */
        h1, h2, h3, h4 {
            font-weight: 450;
            letter-spacing: -0.02em;
            color: #bdbdbd;            /* светлый текст из 1го */
        }

        h1 {
            font-size: clamp(2.5rem, 8vw, 5rem);
            line-height: 1.1;
            margin-bottom: 1.2rem;
            font-weight: 470;
            animation: titleGlow 2s ease-in-out infinite alternate;
            color: #e3d2d2;             /* цвет заголовка из 1го */
        }

        @keyframes titleGlow {
            0% { text-shadow: 0 0 0 rgba(189,189,189,0.2); }
            100% { text-shadow: 2px 2px 20px rgba(189,189,189,0.3); }
        }

        h2 {
            font-size: clamp(2rem, 6vw, 3.8rem);
            margin-bottom: 1.8rem;
            font-weight: 440;
            border-bottom: 1px solid #3f5445;        /* тёмная граница */
            padding-bottom: 0.6rem;
            position: relative;
            overflow: hidden;
            color: #bdbdbd;
        }

        h2::after {
            content: '';
            position: absolute;
            bottom: -1px;
            left: -100%;
            width: 100%;
            height: 2px;
            background: linear-gradient(90deg, #bdbdbd, transparent);
            animation: borderReveal 1.5s ease-out forwards;
            animation-delay: 0.5s;
        }

        @keyframes borderReveal {
            0% { left: -100%; }
            100% { left: 0; }
        }

        h3 {
            font-size: clamp(1.5rem, 4vw, 2.2rem);
            font-weight: 460;
            margin-bottom: 1.2rem;
            color: #bdbdbd;
        }

        p {
            font-size: clamp(1rem, 2.5vw, 1.3rem);
            color: #bdbdbd;
            margin-bottom: 1.2rem;
            line-height: 1.6;
        }

        .lead-text {
            font-size: clamp(1.2rem, 3.5vw, 1.8rem);
            color: #bdbdbd;
            font-weight: 370;
            line-height: 1.5;
            max-width: 1000px;
            animation: fadeIn 0.8s ease-out;
        }

        /* -------------------- АНИМАЦИИ -------------------- */
        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }

        @keyframes slideUp {
            0% { opacity: 0; transform: translateY(30px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        @keyframes scaleIn {
            0% { opacity: 0; transform: scale(0.9); }
            100% { opacity: 1; transform: scale(1); }
        }

        /* -------------------- СЕТКИ -------------------- */
        .grid-2, .grid-3, .articles-grid {
            display: grid;
            gap: 2rem;
            margin: 2.5rem 0;
        }

        .grid-2, .grid-3, .articles-grid {
            grid-template-columns: 1fr;
        }

        @media (min-width: 640px) {
            .grid-2 {
                grid-template-columns: repeat(2, 1fr);
                gap: 2.2rem;
            }
        }

        @media (min-width: 768px) {
            .articles-grid {
                grid-template-columns: repeat(2, 1fr);
            }
        }

        @media (min-width: 900px) {
            .grid-3 {
                grid-template-columns: repeat(2, 1fr);
                gap: 2.5rem;
            }
        }

        @media (min-width: 1200px) {
            .grid-3 {
                grid-template-columns: repeat(3, 1fr);
                gap: 3rem;
            }
            .grid-2 {
                gap: 3rem;
            }
            .articles-grid {
                grid-template-columns: repeat(3, 1fr);
            }
        }

        /* -------------------- КАРТОЧКИ ПРЕИМУЩЕСТВ (из 1го) -------------------- */
        .benefit-card {
            background: #253126;           /* фон из 1го */
            padding: clamp(1.8rem, 4vw, 2.8rem) clamp(1.5rem, 3vw, 2.5rem);
            border-radius: clamp(24px, 4vw, 36px);
            transition: all 0.4s cubic-bezier(0.2, 0.9, 0.3, 1.1);
            box-shadow: 0 4px 14px rgba(0,0,0,0.3);
            opacity: 0;
            animation: cardAppear 0.6s ease-out forwards;
            position: relative;
            overflow: hidden;
            border: 1px solid rgba(180,157,157,0.1);
        }

        .benefit-card::before {
            content: '';
            position: absolute;
            top: var(--y, 50%);
            left: var(--x, 50%);
            width: 0;
            height: 0;
            border-radius: 50%;
            background: radial-gradient(circle, rgba(255,255,255,0.1), transparent 70%);
            transform: translate(-50%, -50%);
            transition: width 0.6s, height 0.6s;
            pointer-events: none;
        }

        .benefit-card:hover::before {
            width: 300px;
            height: 300px;
        }

        .benefit-card:nth-child(1) { animation-delay: 0.1s; }
        .benefit-card:nth-child(2) { animation-delay: 0.2s; }
        .benefit-card:nth-child(3) { animation-delay: 0.3s; }
        .benefit-card:nth-child(4) { animation-delay: 0.4s; }

        @keyframes cardAppear {
            0% { opacity: 0; transform: translateY(30px) scale(0.95); }
            60% { opacity: 0.8; transform: translateY(-2px) scale(1.01); }
            100% { opacity: 1; transform: translateY(0) scale(1); }
        }

        .benefit-card:hover {
            background: #2d3a2f;
            transform: translateY(-8px) scale(1.02);
            box-shadow: 0 28px 38px -20px rgba(0,0,0,0.5);
        }

        .benefit-icon {
            font-size: clamp(2.2rem, 5vw, 3.2rem);
            margin-bottom: 1.2rem;
            display: inline-block;
            transition: all 0.3s ease;
            color: #cecfb9;               /* цвет иконок из 1го */
        }

        .benefit-card:hover .benefit-icon {
            transform: rotate(5deg) scale(1.2);
            animation: iconPulse 1s infinite;
        }

        @keyframes iconPulse {
            0%, 100% { transform: rotate(5deg) scale(1.2); }
            50% { transform: rotate(0deg) scale(1.3); }
        }

        /* -------------------- КАРТОЧКИ СОБЫТИЙ / СТАТЕЙ -------------------- */
        .articles-grid, .events-grid {
            margin: 3rem 0;
        }

        .article-card, .event-card {
            background: #14271c;           /* тёмный фон карточек */
            border-radius: 24px;
            padding: 1.5rem;
            transition: all 0.4s cubic-bezier(0.2, 0.9, 0.3, 1.2);
            box-shadow: 0 4px 20px rgba(0,0,0,0.4);
            opacity: 0;
            animation: articleAppear 0.7s ease-out forwards;
            border: 1px solid rgba(153,136,136,0.2);
            position: relative;
            overflow: hidden;
        }

        .article-card:nth-child(1) { animation-delay: 0.1s; }
        .article-card:nth-child(2) { animation-delay: 0.2s; }
        .article-card:nth-child(3) { animation-delay: 0.3s; }
        .article-card:nth-child(4) { animation-delay: 0.4s; }
        .article-card:nth-child(5) { animation-delay: 0.5s; }
        .article-card:nth-child(6) { animation-delay: 0.6s; }

        @keyframes articleAppear {
            0% { 
                opacity: 0; 
                transform: translateY(40px) scale(0.9);
                filter: blur(5px);
            }
            60% { 
                opacity: 0.9; 
                transform: translateY(-3px) scale(1.01);
                filter: blur(0);
            }
            100% { 
                opacity: 1; 
                transform: translateY(0) scale(1);
                filter: blur(0);
            }
        }

        .article-card:hover, .event-card:hover {
            transform: translateY(-10px) scale(1.02);
            box-shadow: 0 30px 40px -20px #000;
            border-color: #906946;           /* акцент из 1го */
        }

        .article-img {
            background: linear-gradient(145deg, #2d3a2f, #1f2f24);
            border-radius: 20px;
            height: 200px;
            width: 100%;
            margin-bottom: 1.5rem;
            box-shadow: 0 14px 24px -16px #000;
            transition: all 0.4s ease;
            overflow: hidden;
            position: relative;
        }

        .article-img::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.05), transparent);
            transition: left 0.8s ease;
        }

        .article-card:hover .article-img::before {
            left: 100%;
        }

        .article-card h4, .event-card h4 {
            font-size: clamp(1.3rem, 3vw, 1.8rem);
            margin: 1rem 0 0.5rem;
            transition: all 0.3s ease;
            position: relative;
            display: inline-block;
            color: #998888;                /* цвет заголовков статей */
        }

        .article-card:hover h4 {
            color: #bdbdbd;
            transform: translateX(5px);
        }

        .meta {
            color: #5f748b;
            font-size: clamp(0.8rem, 2vw, 0.95rem);
            text-transform: uppercase;
            letter-spacing: 0.5px;
            transition: all 0.3s ease;
            display: inline-block;
            color: #857777;
        }

        .read-link {
            font-weight: 500;
            color: #906946;                /* цвет ссылок */
            text-decoration: none;
            border-bottom: 1px solid #906946;
            padding-bottom: 2px;
            font-size: clamp(1rem, 2.2vw, 1.1rem);
            transition: all 0.3s cubic-bezier(0.2, 0.9, 0.3, 1.2);
            display: inline-flex;
            align-items: center;
            gap: 5px;
            position: relative;
            overflow: hidden;
            cursor: pointer;
        }

        .read-link::after {
            content: '→';
            opacity: 0;
            transform: translateX(-10px);
            transition: all 0.3s ease;
            display: inline-block;
        }

        .read-link:hover {
            border-bottom-color: #bdbdbd;
            color: #bdbdbd;
            padding-bottom: 4px;
            padding-right: 20px;
        }

        .read-link:hover::after {
            opacity: 1;
            transform: translateX(5px);
        }

        .read-link:active {
            transform: scale(0.95);
        }

        /* NEW метка для статей (из 2го) */
        .article-card.new-article {
            position: relative;
        }

        .article-card.new-article::before {
            content: 'НОВОЕ';
            position: absolute;
            top: -5px;
            right: 20px;
            background: linear-gradient(135deg, #905712, #6a400e);
            color: white;
            padding: 5px 15px;
            border-radius: 30px;
            font-size: 0.8rem;
            font-weight: bold;
            animation: pulse 2s infinite;
            z-index: 10;
            box-shadow: 0 4px 15px rgba(144,87,18,0.4);
            letter-spacing: 0.5px;
            text-transform: uppercase;
        }

        @keyframes pulse {
            0% { transform: scale(1); box-shadow: 0 4px 15px rgba(144,87,18,0.4); }
            50% { transform: scale(1.1); box-shadow: 0 8px 25px rgba(144,87,18,0.6); }
            100% { transform: scale(1); box-shadow: 0 4px 15px rgba(144,87,18,0.4); }
        }

        /* -------------------- КНОПКИ (стили из 1го + анимации из 2го) -------------------- */
        .btn {
            display: inline-block;
            background: #2a573d;            /* зелёный из 1го */
            color: #bdbdbd;
            padding: clamp(0.8rem, 2vw, 1.2rem) clamp(1.8rem, 4vw, 3.5rem);
            border-radius: 60px;
            font-size: clamp(1rem, 2.2vw, 1.3rem);
            font-weight: 460;
            text-decoration: none;
            border: none;
            transition: all 0.3s cubic-bezier(0.2, 0.9, 0.3, 1.2);
            cursor: pointer;
            box-shadow: 0 10px 20px -12px rgba(0,0,0,0.5);
            letter-spacing: 0.3px;
            text-align: center;
            position: relative;
            overflow: hidden;
            animation: buttonPulse 2s infinite;
        }

        @keyframes buttonPulse {
            0%, 100% { box-shadow: 0 10px 20px -12px #000; }
            50% { box-shadow: 0 15px 30px -10px #1a3a28; }
        }

        .btn::before {
            content: '';
            position: absolute;
            top: 50%;
            left: 50%;
            width: 0;
            height: 0;
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.1);
            transform: translate(-50%, -50%);
            transition: width 0.6s, height 0.6s;
        }

        .btn:hover::before {
            width: 300px;
            height: 300px;
        }

        .btn:hover {
            background: #326b48;
            color: #fff;
            transform: translateY(-4px) scale(1.02);
            box-shadow: 0 22px 32px -16px #000;
            animation: none;
        }

        .btn:active {
            transform: translateY(0) scale(0.98);
        }

        .btn--outline {
            background: transparent;
            color: #bdbdbd;
            border: 1px solid #906946;
            box-shadow: none;
            animation: none;
        }

        .btn--outline:hover {
            background: rgba(144,105,70,0.2);
            border-color: #bdbdbd;
            color: #fff;
        }

        /* -------------------- НАВИГАЦИЯ (полное соответствие первому сайту) -------------------- */
        .navbar {
            padding: 20px 0;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid rgba(180,157,157,0.2); /* как в 1м */
            animation: navSlideDown 0.5s ease-out;
            position: sticky;
            top: 0;
            background: rgba(36,54,43,0.95);  /* #24362b из 1го */
            backdrop-filter: blur(10px);
            z-index: 100;
        }

        @keyframes navSlideDown {
            0% { opacity: 0; transform: translateY(-30px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        .logo {
            font-size: clamp(1.3rem, 4vw, 2rem);
            font-weight: 460;
            color: #7f7a7a;                /* цвет логотипа из 1го */
            text-decoration: none;
            border: 2px solid #7f7a7a;
            padding: 0.3rem 1.2rem;
            border-radius: 60px;
            letter-spacing: -0.01em;
            transition: all 0.3s ease;
            white-space: nowrap;
            position: relative;
            overflow: hidden;
            cursor: pointer;
        }

        .logo:hover {
            background: rgba(127,122,122,0.2);
            transform: scale(1.02);
            color: #bdbdbd;
            border-color: #bdbdbd;
        }

        /* Десктопное меню — пункты из первого сайта */
        .desktop-nav {
            display: none;
            gap: 2.5rem;
            font-size: 1.2rem;
        }

        .desktop-nav a {
            text-decoration: none;
            color: #7f7a7a;                /* цвет ссылок из 1го */
            border-bottom: 2px solid transparent;
            padding-bottom: 6px;
            transition: all 0.3s ease;
            display: inline-block;
            position: relative;
            cursor: pointer;
        }

        .desktop-nav a::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 0;
            height: 2px;
            background: #bdbdbd;
            transition: width 0.3s ease;
        }

        .desktop-nav a:hover::after {
            width: 100%;
        }

        .desktop-nav a:hover {
            color: #bdbdbd;
        }

        @media (min-width: 900px) {
            .desktop-nav {
                display: flex;
            }
            .burger, .mobile-menu, .overlay, .close-btn {
                display: none;
            }
        }

        /* Бургер-меню (цвета из 1го) */
        .burger {
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            width: 32px;
            height: 24px;
            cursor: pointer;
            z-index: 30;
            transition: all 0.3s ease;
        }

        .burger span {
            width: 100%;
            height: 3px;
            background-color: #ffffff;      /* белый как в 1м */
            border-radius: 3px;
            transition: all 0.3s ease;
        }

        .burger.open span:nth-child(1) {
            transform: translateY(10px) rotate(45deg);
            background-color: #bdbdbd;
        }

        .burger.open span:nth-child(2) {
            opacity: 0;
        }

        .burger.open span:nth-child(3) {
            transform: translateY(-10px) rotate(-45deg);
            background-color: #bdbdbd;
        }

        /* Мобильное меню (фон из 1го) */
        .mobile-menu {
            position: fixed;
            top: 0;
            right: -100%;
            width: 75%;
            max-width: 320px;
            height: 100vh;
            background: #203127;             /* основной фон */
            backdrop-filter: blur(10px);
            box-shadow: -10px 0 30px rgba(0,0,0,0.5);
            padding: 100px 30px 40px;
            display: flex;
            flex-direction: column;
            gap: 2rem;
            transition: right 0.4s cubic-bezier(0.2, 0.9, 0.3, 1.2);
            z-index: 200;
            border-left: 1px solid #3f5445;
        }

        .mobile-menu.active {
            right: 0;
        }

        .mobile-menu a {
            font-size: 1.5rem;
            text-decoration: none;
            color: #bdbdbd;                 /* светлый текст */
            font-weight: 440;
            padding: 0.5rem 0;
            transition: all 0.3s ease;
            position: relative;
            cursor: pointer;
            display: block;
        }

        .mobile-menu a::before {
            content: '';
            position: absolute;
            bottom: 0;
            left: -100%;
            width: 100%;
            height: 2px;
            background: #bdbdbd;
            transition: left 0.3s ease;
        }

        .mobile-menu a:hover {
            transform: translateX(10px);
            color: #fff;
        }

        .mobile-menu a:hover::before {
            left: 0;
        }

        .close-btn {
            position: absolute;
            top: 20px;
            right: 20px;
            width: 44px;
            height: 44px;
            border-radius: 50%;
            background: rgba(255,255,255,0.1);
            border: none;
            cursor: pointer;
            color: #bdbdbd;
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 28px;
            line-height: 1;
            padding: 0;
            z-index: 210;
        }

        .close-btn:hover {
            background: rgba(144,105,70,0.3);
            transform: rotate(90deg);
            color: #fff;
        }

        .overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,0.5);
            backdrop-filter: blur(2px);
            z-index: 150;
            opacity: 0;
            visibility: hidden;
            transition: all 0.3s ease;
        }

        .overlay.active {
            opacity: 1;
            visibility: visible;
        }

        /* -------------------- СЕКЦИИ -------------------- */
        .hero {
            padding: clamp(3rem, 8vw, 6rem) 0 clamp(2rem, 5vw, 4rem);
            animation: heroFade 1s ease-out;
        }

        @keyframes heroFade {
            0% { opacity: 0; transform: translateY(20px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        .section {
            padding: clamp(3.5rem, 8vw, 6rem) 0;
            border-bottom: 1px solid #2d3f31;
            animation: sectionFade 0.8s ease-out;
        }

        @keyframes sectionFade {
            0% { opacity: 0; transform: translateY(30px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        /* -------------------- БЛОК О КЛУБЕ (из 1го) -------------------- */
        .about-block {
            background: #2d1f24;            /* цвет секции О клубе */
            border-radius: 40px;
            overflow: hidden;
            margin: 2rem 0;
        }

        .about-grid {
            display: grid;
            grid-template-columns: 1fr;
        }

        @media (min-width: 768px) {
            .about-grid {
                grid-template-columns: 1fr 1fr;
            }
        }

        .about-text {
            padding: clamp(2rem, 5vw, 4rem);
            background: #bdbdbd;             /* фон текста */
            color: #1f2a36;
        }

        .about-text h2, .about-text p {
            color: #1f2a36 !important;
        }

        .about-image {
            min-height: 300px;
            background-size: cover;
            background-position: center;
        }

        /* -------------------- РЕСУРС ЛИСТЫ -------------------- */
        .resource-list {
            list-style: none;
            background: #14271c;
            padding: clamp(2rem, 4vw, 3rem) clamp(2rem, 4vw, 3rem);
            border-radius: 40px;
            box-shadow: inset 0 1px 4px rgba(255,255,255,0.05), 0 12px 28px -18px #000;
            transition: all 0.4s ease;
            opacity: 0;
            animation: listAppear 0.6s ease-out forwards;
            cursor: default;
            border: 1px solid #2d3f31;
        }

        .resource-list:nth-child(1) { animation-delay: 0.1s; }
        .resource-list:nth-child(2) { animation-delay: 0.2s; }
        .resource-list:nth-child(3) { animation-delay: 0.3s; }

        @keyframes listAppear {
            0% { opacity: 0; transform: translateX(-30px); }
            100% { opacity: 1; transform: translateX(0); }
        }

        .resource-list:hover {
            box-shadow: 0 20px 34px -20px #000, inset 0 1px 6px rgba(255,255,255,0.1);
            transform: scale(1.02) translateY(-5px);
        }

        .resource-list li {
            margin-bottom: 1rem;
            font-size: clamp(1rem, 2.2vw, 1.25rem);
            display: flex;
            align-items: baseline;
            gap: 0.8rem;
            transition: all 0.3s ease;
            cursor: pointer;
            color: #998888;
        }

        .resource-list li:hover {
            transform: translateX(15px);
            color: #bdbdbd;
        }

        .resource-list li::before {
            content: "—";
            color: #906946;
            transition: all 0.3s ease;
        }

        /* -------------------- КОНТАКТЫ -------------------- */
        .contact-grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: 2.5rem;
            background: #14271c;
            border-radius: 40px;
            padding: clamp(2rem, 5vw, 4rem);
            transition: all 0.4s ease;
            animation: contactFade 0.8s ease-out;
            border: 1px solid #2d3f31;
        }

        @keyframes contactFade {
            0% { opacity: 0; transform: scale(0.95); }
            100% { opacity: 1; transform: scale(1); }
        }

        .contact-grid:hover {
            box-shadow: 0 30px 50px -30px #000;
            transform: translateY(-5px);
        }

        @media (min-width: 768px) {
            .contact-grid {
                grid-template-columns: 1fr 1fr;
                gap: 3.5rem;
            }
        }

        .contact-item {
            margin-bottom: 2rem;
            animation: contactItemFade 0.5s ease-out forwards;
            opacity: 0;
        }

        .contact-item:nth-child(1) { animation-delay: 0.2s; }
        .contact-item:nth-child(2) { animation-delay: 0.4s; }
        .contact-item:nth-child(3) { animation-delay: 0.6s; }

        @keyframes contactItemFade {
            0% { opacity: 0; transform: translateY(20px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        .contact-item strong {
            font-weight: 550;
            color: #bdbdbd;
            font-size: clamp(1rem, 2vw, 1.2rem);
            display: block;
            margin-bottom: 0.5rem;
        }

        .contact-item span {
            font-size: clamp(1.2rem, 3vw, 1.8rem);
            color: #998888;
            word-break: break-word;
            transition: all 0.3s ease;
            display: inline-block;
            cursor: pointer;
        }

        .contact-item:hover span {
            color: #bdbdbd;
            transform: translateX(5px);
        }

        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: clamp(0.9rem, 2.5vw, 1.3rem) clamp(1.2rem, 3vw, 1.8rem);
            border: 1px solid #3f5445;
            border-radius: 50px;
            font-size: clamp(1rem, 2vw, 1.15rem);
            margin-bottom: 1.3rem;
            background: #1f2f24;
            color: #bdbdbd;
            transition: all 0.3s ease;
        }

        .contact-form input:focus, .contact-form textarea:focus {
            border-color: #906946;
            outline: none;
            box-shadow: 0 0 0 4px rgba(144,105,70,0.2);
        }

        .contact-form textarea {
            border-radius: 30px;
            min-height: 120px;
            resize: vertical;
        }

        /* -------------------- АКЦЕНТ-БЛОК -------------------- */
        .accent-block {
            background: #2d1f24;
            border-radius: 50px;
            padding: clamp(2.5rem, 7vw, 5rem) clamp(2rem, 5vw, 4rem);
            margin: 3rem 0 2rem;
            text-align: center;
            transition: all 0.4s ease;
            animation: accentFade 1s ease-out;
            position: relative;
            overflow: hidden;
            border: 1px solid #906946;
        }

        @keyframes accentFade {
            0% { opacity: 0; transform: translateY(30px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        .accent-block:hover {
            transform: translateY(-8px) scale(1.01);
            box-shadow: 0 40px 50px -30px #000;
        }

        .accent-block p {
            color: #bdbdbd;
        }

        .accent-block h3 {
            color: #fff;
            font-size: clamp(2rem, 5vw, 3.5rem);
            margin: 1rem 0;
        }

        /* -------------------- ФУТЕР -------------------- */
        .footer {
            padding: 3rem 0 4rem;
            color: #7f7a7a;
            display: flex;
            flex-direction: column;
            gap: 1rem;
            font-size: clamp(0.9rem, 2vw, 1.15rem);
            border-top: 1px solid #2d3f31;
            text-align: center;
            animation: footerFade 0.8s ease-out;
        }

        @keyframes footerFade {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }

        @media (min-width: 768px) {
            .footer {
                flex-direction: row;
                justify-content: space-between;
                text-align: left;
            }
        }

        .footer a {
            color: #7f7a7a;
            text-decoration: none;
            transition: all 0.3s ease;
            position: relative;
            cursor: pointer;
        }

        .footer a::after {
            content: '';
            position: absolute;
            bottom: -2px;
            left: 0;
            width: 0;
            height: 1px;
            background: #bdbdbd;
            transition: width 0.3s ease;
        }

        .footer a:hover {
            color: #bdbdbd;
        }

        .footer a:hover::after {
            width: 100%;
        }

        /* -------------------- МОДАЛЬНЫЕ ОКНА -------------------- */
        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,0.8);
            backdrop-filter: blur(5px);
            z-index: 1000;
            justify-content: center;
            align-items: center;
            opacity: 0;
            transition: opacity 0.3s ease;
        }

        .modal.active {
            display: flex;
            opacity: 1;
        }

        .modal-content {
            background: #203127;
            padding: 3rem;
            border-radius: 40px;
            max-width: 500px;
            width: 90%;
            position: relative;
            transform: scale(0.9);
            transition: transform 0.3s ease;
            box-shadow: 0 30px 60px rgba(0,0,0,0.5);
            border: 1px solid #906946;
        }

        .modal.active .modal-content {
            transform: scale(1);
        }

        .modal-close {
            position: absolute;
            top: 20px;
            right: 20px;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background: none;
            border: none;
            font-size: 28px;
            cursor: pointer;
            color: #bdbdbd;
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            justify-content: center;
            line-height: 1;
        }

        .modal-close:hover {
            transform: rotate(90deg);
            color: #906946;
            background: rgba(255,255,255,0.1);
        }

        .modal h3 {
            margin-bottom: 1.5rem;
            color: #bdbdbd;
        }

        /* -------------------- УВЕДОМЛЕНИЯ (TOAST) -------------------- */
        .toast {
            position: fixed;
            bottom: 30px;
            right: 30px;
            background: #203127;
            color: #bdbdbd;
            padding: 1rem 2rem;
            border-radius: 60px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.5);
            transform: translateX(400px);
            transition: transform 0.3s ease;
            z-index: 1001;
            border: 1px solid #906946;
        }

        .toast.show {
            transform: translateX(0);
        }

        .toast.success {
            background: #1e4f2e;
            border-color: #bdbdbd;
        }

        .toast.error {
            background: #5e2e2e;
            border-color: #b66d6d;
        }

        /* -------------------- УТИЛИТЫ -------------------- */
        .text-center {
            text-align: center;
        }

        .mt-4 {
            margin-top: 2rem;
        }

        .mb-4 {
            margin-bottom: 2rem;
        }

        /* -------------------- ИЗОБРАЖЕНИЯ-ЗАГЛУШКИ -------------------- */
        .img-placeholder {
            background: linear-gradient(145deg, #2d3a2f, #1f2f24);
            border-radius: clamp(24px, 4vw, 36px);
            height: clamp(160px, 30vw, 260px);
            width: 100%;
            margin-bottom: 1.5rem;
            box-shadow: inset 0 2px 8px rgba(255,255,255,0.05), 0 14px 24px -16px #000;
            transition: all 0.4s ease;
            position: relative;
            overflow: hidden;
        }

        .img-round {
            border-radius: 50%;
            width: clamp(120px, 20vw, 200px);
            height: clamp(120px, 20vw, 200px);
            background: #2d3a2f;
            box-shadow: 0 20px 30px -16px #000;
            margin: 0 auto 1.5rem;
            transition: all 0.5s ease;
            animation: float 3s infinite ease-in-out;
            cursor: pointer;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0) rotate(0deg); }
            50% { transform: translateY(-10px) rotate(2deg); }
        }

        /* заглушки изображений */
        .event-img-1 { background-image: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" fill="%2332543d"><rect width="100" height="100"/><text x="10" y="55" fill="%23906946" font-size="12">Костюм</text></svg>'); }
        .event-img-2 { background-image: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" fill="%2332543d"><rect width="100" height="100"/><text x="10" y="55" fill="%23906946" font-size="12">Театр</text></svg>'); }
        .event-img-3 { background-image: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" fill="%2332543d"><rect width="100" height="100"/><text x="10" y="55" fill="%23906946" font-size="12">Бородино</text></svg>'); }
        .article-img-1 { background-image: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" fill="%2332543d"><rect width="100" height="100"/><text x="10" y="55" fill="%23906946" font-size="10">Сапиосексуалы</text></svg>'); }
        .article-img-2 { background-image: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" fill="%2332543d"><rect width="100" height="100"/><text x="10" y="55" fill="%23906946" font-size="10">Крысы</text></svg>'); }
        .article-img-3 { background-image: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" fill="%2332543d"><rect width="100" height="100"/><text x="10" y="55" fill="%23906946" font-size="10">Салоны</text></svg>'); }

        @media (prefers-reduced-motion: reduce) {
            * { animation: none !important; transition: none !important; }
        }
    </style>
</head>
<body>
    <!-- НАВИГАЦИЯ: пункты строго как в первом сайте -->
    <nav class="navbar">
        <div class="container" style="display: flex; justify-content: space-between; align-items: center; width: 100%;">
            <a href="#home" class="logo" id="homeLink">КК</a>
            <div class="desktop-nav">
                <a href="#home" class="nav-link">Главная</a>
                <a href="#events" class="nav-link">Мероприятия</a>
                <a href="#articles" class="nav-link">Статьи</a>
                <a href="#online" class="nav-link">Онлайн обучение</a>
                <a href="#about" class="nav-link">О клубе</a>
                <a href="#contact" class="nav-link">Контакты</a>
            </div>
            <div class="burger" id="burger">
                <span></span><span></span><span></span>
            </div>
        </div>
    </nav>

    <!-- Мобильное меню с теми же пунктами -->
    <div class="mobile-menu" id="mobileMenu">
        <button class="close-btn" id="closeBtn" aria-label="Закрыть меню">×</button>
        <a href="#home" class="mobile-nav-link">Главная</a>
        <a href="#events" class="mobile-nav-link">Мероприятия</a>
        <a href="#articles" class="mobile-nav-link">Статьи</a>
        <a href="#online" class="mobile-nav-link">Онлайн обучение</a>
        <a href="#about" class="mobile-nav-link">О клубе</a>
        <a href="#contact" class="mobile-nav-link">Контакты</a>
    </div>
    <div class="overlay" id="overlay"></div>

    <!-- МОДАЛЬНЫЕ ОКНА -->
    <div class="modal" id="articleModal">
        <div class="modal-content">
            <button class="modal-close" id="closeModal">×</button>
            <h3 id="modalTitle">Заголовок</h3>
            <p id="modalContent">Содержание...</p>
            <button class="btn" id="closeModalBtn">Закрыть</button>
        </div>
    </div>
    <div class="modal" id="joinModal">
        <div class="modal-content">
            <button class="modal-close" id="closeJoinModal">×</button>
            <h3>Вступление в клуб</h3>
            <form id="joinForm">
                <input type="text" placeholder="Ваше имя" id="joinName" required style="width:100%; margin-bottom:1rem; padding:1rem; background:#1f2f24; border:1px solid #906946; color:#bdbdbd; border-radius:30px;">
                <input type="email" placeholder="Email" id="joinEmail" required style="width:100%; margin-bottom:1rem; padding:1rem; background:#1f2f24; border:1px solid #906946; color:#bdbdbd; border-radius:30px;">
                <textarea placeholder="Почему вы хотите вступить?" rows="3" id="joinReason" style="width:100%; margin-bottom:1rem; padding:1rem; background:#1f2f24; border:1px solid #906946; color:#bdbdbd; border-radius:30px;"></textarea>
                <button type="submit" class="btn" style="width:100%;">Отправить</button>
            </form>
        </div>
    </div>

    <!-- TOAST -->
    <div class="toast" id="toast">Сообщение</div>

    <!-- HERO (Главная) -->
    <section class="hero" id="home">
        <div class="container">
            <h1>Добро пожаловать в "Крысиный клуб"</h1>
            <p class="lead-text">Это пространство для тех, кто инвестирует в личный капитал. Развиваем гибкость мышления через глубокую насмотренность. Анализируем литературу и искусство, выходя за рамки шаблонов.</p>
            <div style="display: flex; gap: 1rem; flex-wrap: wrap; margin-top: 2rem;">
                <a href="#about" class="btn" id="learnMoreBtn">О клубе</a>
                <a href="#" class="btn btn--outline" id="joinBtn">Вступить</a>
            </div>
        </div>
    </section>

    <!-- ПРАКТИЧЕСКАЯ ПОЛЬЗА КЛУБА -->
    <section class="section" id="benefits">
        <div class="container">
            <h2>Практическая польза клуба.</h2>
            <div class="grid-3">
                <div class="benefit-card">
                    <div class="benefit-icon">💼</div>
                    <h3>В бизнесе и переговорах</h3>
                    <p>Чтение тренирует навык быстрой фильтрации данных, развивает речь, что конвертируется в высокий чек на переговорах.</p>
                </div>
                <div class="benefit-card">
                    <div class="benefit-icon">🧠</div>
                    <h3>Развитие критического мышления</h3>
                    <p>Участие в дискуссиях помогает тебе научиться анализировать информацию и делать обоснованные выводы.</p>
                </div>
                <div class="benefit-card">
                    <div class="benefit-icon">✨</div>
                    <h3>Интеллектуальная харизма</h3>
                    <p>Человек с широким кругозором мгновенно считывается как лидер мнений и человек более высокого статуса.</p>
                </div>
                <div class="benefit-card">
                    <div class="benefit-icon">🎨</div>
                    <h3>Повышение насмотренности</h3>
                    <p>Визуальный опыт помогает быстрее находить оригинальные идеи и решения задач.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- МЕРОПРИЯТИЯ -->
    <section class="section" id="events">
        <div class="container">
            <h2>Ближайшие события.</h2>
            <div class="events-grid articles-grid">
                <div class="event-card article-card">
                    <div class="article-img event-img-1"></div>
                    <div class="meta">Экскурсия</div>
                    <h4>Что общего между русским народным костюмом и Индией?</h4>
                    <p>Двойная экскурсия: русский народный костюм и костюм Индии. После - фотосессия в Большом Царицынском дворце.</p>
                    <a href="#" class="read-link event-link" data-event="1">Подробнее</a>
                </div>
                <div class="event-card article-card">
                    <div class="article-img event-img-2"></div>
                    <div class="meta">Экскурсия</div>
                    <h4>Экскурсия в Большой театр.</h4>
                    <p>Экскурсия с лекцией по истории театра. После - фотосессия.</p>
                    <a href="#" class="read-link event-link" data-event="2">Подробнее</a>
                </div>
                <div class="event-card article-card">
                    <div class="article-img event-img-3"></div>
                    <div class="meta">Поездка</div>
                    <h4>Поездка в Бородино.</h4>
                    <p>Поездка на Бородинское поле с лучшим в России историком-наполеонистом Павлом Алехиным.</p>
                    <a href="#" class="read-link event-link" data-event="3">Подробнее</a>
                </div>
            </div>
        </div>
    </section>

    <!-- СТАТЬИ -->
    <section class="section" id="articles">
        <div class="container">
            <h2>Полезные статьи.</h2>
            <div class="articles-grid">
                <article class="article-card" data-article="1">
                    <div class="article-img article-img-1"></div>
                    <div class="meta">15 марта 2026 · 8 мин</div>
                    <h4>Сапиосексуалы. Почему немодно быть безграмотным?</h4>
                    <p>В современном мире интеллект становится новой валютой.</p>
                    <a href="#" class="read-link article-link" data-article="1">Читать</a>
                </article>
                <article class="article-card" data-article="2">
                    <div class="article-img article-img-2"></div>
                    <div class="meta">10 марта 2026 · 6 мин</div>
                    <h4>Самые громкие истории "поедания" книг крысами</h4>
                    <p>Как грызуны влияли на сохранность библиотек.</p>
                    <a href="#" class="read-link article-link" data-article="2">Читать</a>
                </article>
                <article class="article-card new-article" data-article="3">
                    <div class="article-img article-img-3"></div>
                    <div class="meta">5 марта 2026 · 10 мин</div>
                    <h4>История интеллектуальных клубов: симпосии, салоны</h4>
                    <p>От Древней Греции до английских клубов.</p>
                    <a href="#" class="read-link article-link" data-article="3">Читать</a>
                </article>
            </div>
            <div class="text-center mt-4">
                <a href="#" class="btn" id="allArticlesBtn">Все статьи клуба →</a>
            </div>
        </div>
    </section>

    <!-- ОНЛАЙН ОБУЧЕНИЕ (заглушка) -->
    <section class="section" id="online">
        <div class="container">
            <h2>Онлайн обучение</h2>
            <p class="lead-text">Скоро здесь появятся курсы и лекции от наших экспертов.</p>
            <div style="height: 100px;"></div>
        </div>
    </section>

    <!-- О КЛУБЕ -->
    <section class="section" id="about">
        <div class="container">
            <div class="about-block about-grid">
                <div class="about-text">
                    <h2 style="color:#1f2a36; border-bottom-color:#906946;">О клубе</h2>
                    <p style="color:#1f2a36;">Основатель проекта — Кристина Егорова, выпускница Школы-студии МХАТ им. Чехова, экс-креативный продюсер Kion (МТС) и ведущая шоу «Деконструкция». В основе интеллектуального клуба лежит её многолетний опыт документальных съёмок по всей России и СНГ — от Владивостока до Узбекистана.</p>
                </div>
                <div class="about-image" style="background-image: url('data:image/svg+xml;utf8,<svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 100 100%22 fill=%22%2332543d%22><rect width=%22100%22 height=%22100%22/><text x=%2210%22 y=%2255%22 fill=%22%23906946%22 font-size=%2212%22>Кристина</text></svg>');"></div>
            </div>
        </div>
    </section>

    <!-- РЕСУРСЫ -->
    <section class="section" id="resources">
        <div class="container">
            <h2>Полезные материалы</h2>
            <div class="grid-3">
                <ul class="resource-list">
                    <li onclick="showToast('Скоро: философский словарь')">Философский словарь</li>
                    <li onclick="showToast('Подборка эссе о бюрократии')">Эссе о бюрократии</li>
                    <li onclick="showToast('Архив дискуссий')">Архив дискуссий</li>
                </ul>
                <ul class="resource-list">
                    <li onclick="showToast('Лекции по литературе XX века')">Лекции по литературе</li>
                    <li onclick="showToast('Критические статьи')">Критические статьи</li>
                    <li onclick="showToast('Интервью с мыслителями')">Интервью</li>
                </ul>
                <ul class="resource-list">
                    <li onclick="showToast('Календарь событий')">Календарь событий</li>
                    <li onclick="showToast('Библиотека PDF')">Библиотека PDF</li>
                    <li onclick="showToast('Подкасты')">Подкасты</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- АКЦЕНТ-БЛОК -->
    <div class="container">
        <div class="accent-block" id="accentBlock">
            <p>Присоединяйтесь к закрытому</p>
            <h3>Крысиному клубу</h3>
            <p>Доступ к эксклюзивным материалам и встречам</p>
            <a href="#" class="btn btn--outline" id="joinFromAccent" style="margin-top:1rem;">Стать членом</a>
        </div>
    </div>

    <!-- КОНТАКТЫ -->
    <section class="section" id="contact">
        <div class="container">
            <h2>Контакты</h2>
            <div class="contact-grid">
                <div>
                    <div class="contact-item" onclick="copyToClipboard('club@krysy.ru')">
                        <strong>Email</strong>
                        <span>club@krysy.ru</span>
                    </div>
                    <div class="contact-item" onclick="copyToClipboard('8 800 123-45-67')">
                        <strong>Телефон</strong>
                        <span>8 800 123-45-67</span>
                    </div>
                    <div class="contact-item" onclick="showToast('Москва, ул. Пушкинская, д. 10')">
                        <strong>Адрес</strong>
                        <span>ул. Пушкинская, д. 10, Москва</span>
                    </div>
                    <div class="img-round" id="contactImage"></div>
                </div>
                <div class="contact-form">
                    <h3 style="margin-bottom:1.5rem;">Напишите нам</h3>
                    <input type="text" placeholder="Ваше имя" id="contactName">
                    <input type="email" placeholder="Email" id="contactEmail">
                    <textarea placeholder="Сообщение" id="contactMessage"></textarea>
                    <button class="btn" id="sendMessageBtn" style="border:none;">Отправить</button>
                </div>
            </div>
        </div>
    </section>

    <!-- ФУТЕР -->
    <footer class="footer">
        <div class="container" style="display:flex; justify-content:space-between; align-items:center; width:100%; flex-wrap:wrap;">
            <div>© Крысиная канцелярия, 2026</div>
            <div style="display:flex; gap:2rem; flex-wrap:wrap;">
                <a href="#" onclick="showToast('Политика конфиденциальности')">Политика</a>
                <a href="#" onclick="showToast('Условия использования')">Условия</a>
            </div>
        </div>
    </footer>

    <script>
        // ==================== БУРГЕР-МЕНЮ ====================
        const burger = document.getElementById('burger');
        const mobileMenu = document.getElementById('mobileMenu');
        const overlay = document.getElementById('overlay');
        const closeBtn = document.getElementById('closeBtn');
        const body = document.body;

        function openMenu() { burger.classList.add('open'); mobileMenu.classList.add('active'); overlay.classList.add('active'); body.classList.add('menu-open'); }
        function closeMenu() { burger.classList.remove('open'); mobileMenu.classList.remove('active'); overlay.classList.remove('active'); body.classList.remove('menu-open'); }

        if (burger) burger.addEventListener('click', openMenu);
        if (closeBtn) closeBtn.addEventListener('click', closeMenu);
        if (overlay) overlay.addEventListener('click', closeMenu);

        // Плавный скролл для мобильных ссылок
        document.querySelectorAll('.mobile-nav-link').forEach(link => {
            link.addEventListener('click', (e) => {
                e.preventDefault();
                const href = link.getAttribute('href');
                if (href && href.startsWith('#')) {
                    closeMenu();
                    setTimeout(() => {
                        const target = document.getElementById(href.substring(1));
                        if (target) target.scrollIntoView({ behavior: 'smooth' });
                    }, 300);
                }
            });
        });

        // Плавный скролл для десктопных ссылок
        document.querySelectorAll('.nav-link, #homeLink, #learnMoreBtn').forEach(link => {
            link.addEventListener('click', (e) => {
                const href = link.getAttribute('href');
                if (href && href.startsWith('#')) {
                    e.preventDefault();
                    const target = document.getElementById(href.substring(1));
                    if (target) target.scrollIntoView({ behavior: 'smooth' });
                }
            });
        });

        // ==================== МОДАЛКИ ====================
        const articleModal = document.getElementById('articleModal');
        const joinModal = document.getElementById('joinModal');
        const modalTitle = document.getElementById('modalTitle');
        const modalContent = document.getElementById('modalContent');

        const articles = {
            1: { title: 'Сапиосексуалы', content: 'Интеллект как новая форма привлекательности. В современном мире ценится способность мыслить критически и иметь широкий кругозор. Именно таких людей называют сапиосексуалами.' },
            2: { title: 'Крысы и книги', content: 'Истории о том, как крысы уничтожали бесценные фолианты. В XV веке в библиотеках Европы крысы съедали целые полки.' },
            3: { title: 'История интеллектуальных клубов', content: 'От древнегреческих симпосиев до французских салонов XVIII века и русских литературных кружков. Всегда это было место рождения идей.' },
        };
        function openArticleModal(id) {
            if (articles[id]) { modalTitle.textContent = articles[id].title; modalContent.textContent = articles[id].content; articleModal.classList.add('active'); body.style.overflow = 'hidden'; }
        }
        function closeModal(modal) { modal.classList.remove('active'); body.style.overflow = ''; }

        document.querySelectorAll('.article-link').forEach(link => link.addEventListener('click', (e) => { e.preventDefault(); openArticleModal(link.dataset.article); }));
        document.querySelectorAll('.event-link').forEach(link => link.addEventListener('click', (e) => { e.preventDefault(); showToast('Информация о событии появится скоро'); }));

        document.getElementById('closeModal')?.addEventListener('click', () => closeModal(articleModal));
        document.getElementById('closeModalBtn')?.addEventListener('click', () => closeModal(articleModal));
        document.getElementById('closeJoinModal')?.addEventListener('click', () => closeModal(joinModal));
        articleModal.addEventListener('click', (e) => { if (e.target === articleModal) closeModal(articleModal); });
        joinModal.addEventListener('click', (e) => { if (e.target === joinModal) closeModal(joinModal); });

        // ==================== КНОПКИ ВСТУПЛЕНИЯ ====================
        document.getElementById('joinBtn')?.addEventListener('click', (e) => { e.preventDefault(); joinModal.classList.add('active'); body.style.overflow = 'hidden'; });
        document.getElementById('joinFromAccent')?.addEventListener('click', (e) => { e.preventDefault(); joinModal.classList.add('active'); body.style.overflow = 'hidden'; });
        document.getElementById('joinForm')?.addEventListener('submit', (e) => {
            e.preventDefault();
            const name = document.getElementById('joinName')?.value;
            if (name) showToast(`Спасибо, ${name}! Заявка отправлена`, 'success');
            else showToast('Заполните имя и email', 'error');
            closeModal(joinModal);
        });

        // ==================== TOAST ====================
        const toast = document.getElementById('toast');
        let toastTimeout;
        window.showToast = function(message, type = 'info') {
            clearTimeout(toastTimeout);
            toast.textContent = message;
            toast.className = 'toast show ' + (type === 'success' ? 'success' : type === 'error' ? 'error' : '');
            toastTimeout = setTimeout(() => toast.classList.remove('show'), 3000);
        };
        window.copyToClipboard = (text) => { navigator.clipboard?.writeText(text).then(() => showToast(`Скопировано`, 'success')).catch(() => showToast('Ошибка копирования', 'error')); };

        // ==================== ФОРМА КОНТАКТОВ ====================
        document.getElementById('sendMessageBtn')?.addEventListener('click', (e) => {
            e.preventDefault();
            const name = document.getElementById('contactName')?.value;
            if (name) showToast(`Сообщение отправлено, ${name}!`, 'success');
            else showToast('Заполните поля', 'error');
        });

        // ==================== БЛИКИ НА КАРТОЧКАХ ====================
        document.querySelectorAll('.benefit-card').forEach(card => {
            card.addEventListener('mousemove', function(e) {
                const rect = this.getBoundingClientRect();
                this.style.setProperty('--x', ((e.clientX - rect.left)/rect.width)*100 + '%');
                this.style.setProperty('--y', ((e.clientY - rect.top)/rect.height)*100 + '%');
            });
        });

        // ==================== КЛИК ПО ИЗОБРАЖЕНИЯМ ====================
        document.getElementById('contactImage')?.addEventListener('click', () => showToast('Наше сообщество'));

        // ==================== ВСЕ СТАТЬИ ====================
        document.getElementById('allArticlesBtn')?.addEventListener('click', (e) => { e.preventDefault(); showToast('Все статьи будут доступны после регистрации'); });

        console.log('Меню полностью исправлено и соответствует первому сайту');
    </script>
</body>
</html>
