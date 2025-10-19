<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vinh Danh Học Sinh Xuất Sắc - 20 Năm học</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@400;500;600;700&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700;800;900&display=swap" rel="stylesheet">
    <style>
        /* ===== RESET & BASE STYLES ===== */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Quicksand', sans-serif;
        }
        
        :root {
            --primary-color: #1a2a6c;
            --secondary-color: #2A4D9B;
            --accent-color: #3a6dc9;
            --gold-color: #FFD700;
            --gold-light: #FFEC8B;
            --orange-color: #FF8C42;
            --text-light: #F8F6F2;
            --text-dark: #0a192f;
            --shadow-light: rgba(255, 255, 255, 0.1);
            --shadow-dark: rgba(0, 0, 0, 0.3);
            --gradient-primary: linear-gradient(135deg, #1a2a6c, #2A4D9B, #3a6dc9);
            --gradient-gold: linear-gradient(45deg, #FFD700, #FFA500, #FFD700);
            --gradient-card: linear-gradient(135deg, rgba(58, 109, 201, 0.8), rgba(42, 77, 155, 0.9));
            --gradient-orange: linear-gradient(135deg, rgba(255, 140, 66, 0.9), rgba(232, 106, 51, 0.9));
            --transition-slow: all 0.8s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            --transition-medium: all 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            --transition-fast: all 0.3s ease;
        }
        
        body {
            background: var(--gradient-primary);
            color: var(--text-light);
            min-height: 100vh;
            overflow-x: hidden;
            position: relative;
        }
        
        /* ===== BACKGROUND EFFECTS ===== */
        .dynamic-bg {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -3;
            background: linear-gradient(-45deg, #1a2a6c, #2A4D9B, #3a6dc9, #4d8ae6, #1a2a6c);
            background-size: 400% 400%;
            animation: gradientShift 20s ease infinite;
        }
        
        @keyframes gradientShift {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
        
        .particles {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -2;
            overflow: hidden;
        }
        
        .particle {
            position: absolute;
            background: radial-gradient(circle, rgba(255, 215, 0, 0.7) 0%, rgba(255, 215, 0, 0) 70%);
            border-radius: 50%;
            animation: particleFloat 25s infinite linear;
            filter: blur(1px);
        }
        
        @keyframes particleFloat {
            0% {
                transform: translateY(100vh) rotate(0deg);
                opacity: 0;
            }
            10% {
                opacity: 1;
            }
            90% {
                opacity: 1;
            }
            100% {
                transform: translateY(-100px) rotate(360deg);
                opacity: 0;
            }
        }
        
        .floating-elements {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: -1;
        }
        
        .floating-element {
            position: absolute;
            background: rgba(255, 215, 0, 0.1);
            border-radius: 50%;
            animation: float 25s infinite linear;
            box-shadow: 0 0 30px rgba(255, 215, 0, 0.3);
        }
        
        @keyframes float {
            0% {
                transform: translateY(0) rotate(0deg);
                opacity: 0;
            }
            10% {
                opacity: 1;
            }
            90% {
                opacity: 1;
            }
            100% {
                transform: translateY(-1000px) rotate(360deg);
                opacity: 0;
            }
        }
        
        .spotlight {
            position: fixed;
            width: 300px;
            height: 300px;
            border-radius: 50%;
            background: radial-gradient(circle, rgba(255,215,0,0.2) 0%, rgba(255,215,0,0) 70%);
            pointer-events: none;
            z-index: -1;
            animation: spotlightMove 20s infinite linear;
            filter: blur(15px);
        }
        
        @keyframes spotlightMove {
            0% { transform: translate(10vw, 10vh); }
            25% { transform: translate(80vw, 30vh); }
            50% { transform: translate(40vw, 70vh); }
            75% { transform: translate(70vw, 50vh); }
            100% { transform: translate(10vw, 10vh); }
        }
        
        /* ===== CONTAINER & LAYOUT ===== */
        .container {
            width: 100%;
            min-height: 100vh;
            background: rgba(10, 25, 47, 0.85);
            backdrop-filter: blur(20px);
            position: relative;
            overflow: hidden;
        }
        
        .container::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: 
                url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" preserveAspectRatio="none"><defs><pattern id="grain" width="100" height="100" patternUnits="userSpaceOnUse"><circle cx="50" cy="50" r="1" fill="rgba(255,255,255,0.03)"/></pattern></defs><rect width="100" height="100" fill="url(%23grain)"/></svg>'),
                linear-gradient(135deg, transparent 0%, rgba(255, 215, 0, 0.05) 100%);
            pointer-events: none;
            z-index: 0;
        }
        
        /* ===== HEADER STYLES ===== */
        header {
            background: 
                linear-gradient(135deg, rgba(42, 77, 155, 0.9), rgba(58, 109, 201, 0.8)),
                url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" preserveAspectRatio="none"><path d="M0,0 L100,0 L100,100 Z" fill="rgba(255,215,0,0.1)"/></svg>');
            color: var(--text-light);
            text-align: center;
            padding: 120px 20px 100px;
            position: relative;
            overflow: hidden;
            border-bottom: 1px solid rgba(255, 215, 0, 0.3);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
        }
        
        header::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: 
                radial-gradient(circle at 20% 80%, rgba(255, 215, 0, 0.1) 0%, transparent 50%),
                radial-gradient(circle at 80% 20%, rgba(255, 215, 0, 0.1) 0%, transparent 50%);
            z-index: 1;
        }
        
        .header-content {
            position: relative;
            z-index: 2;
        }
        
        .header-logo {
            position: absolute;
            top: 30px;
            left: 50px;
            height: 180px;
            width: auto;
            z-index: 10;
            filter: drop-shadow(0 0 15px rgba(255, 215, 0, 0.7));
            transition: var(--transition-medium);
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.1);
            padding: 10px;
            backdrop-filter: blur(10px);
        }
        
        .header-logo:hover {
            transform: scale(1.1) rotate(5deg);
            filter: drop-shadow(0 0 20px rgba(255, 215, 0, 0.9));
        }
        
        .header-icon {
            font-size: 4rem;
            color: var(--gold-color);
            margin-bottom: 30px;
            text-shadow: 0 0 15px rgba(255, 215, 0, 0.7);
            animation: float 3s ease-in-out infinite;
        }
        
        @keyframes float {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-10px);
            }
        }
        
        /* CHỈNH SỬA: Làm chữ VINH DANH to hơn */
        .glowing-text {
            font-size: 7rem; /* Tăng từ 5rem lên 7rem */
            margin-bottom: 20px;
            text-shadow: 0 0 10px rgba(254 , 224 , 255 , 0 ), 0 0 20px rgba(255, 215, 0, 0.5), 0 0 30px rgba(255, 215, 0, 0 );
            position: relative;
            background: linear-gradient(45deg, #FFD700, #FFA500, #FFD700);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-weight: 700;
            letter-spacing: 2px;
            animation: glow 3s ease-in-out infinite alternate;
            font-family: 'Playfair Display', serif;
        }
        
        @keyframes glow {
            0% {
                text-shadow: 0 0 10px rgba(255, 215, 0, 0), 0 0 20px rgba(255, 215, 0, 0.5), 0 0 30px rgba(255, 215, 0, 0 );
            }
            100% {
                text-shadow: 0 0 15px rgba(255, 215, 0, 0.8), 0 0 25px rgba(255, 215, 0, 0.6), 0 0 35px rgba(255, 215, 0, 0.4);
            }
        }
        
        .subtitle {
            font-size: 2.2rem;
            margin-bottom: 10px;
            position: relative;
            color: #e0e0ff;
            font-weight: 500;
        }
        
        .header-decoration {
            position: absolute;
            bottom: 0;
            left: 0;
            width: 100%;
            height: 20px;
            background: linear-gradient(90deg, transparent, var(--gold-color), transparent);
            opacity: 0.5;
        }
        
        /* ===== MAIN CONTENT STYLES ===== */
        .main-content {
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 80vh;
            padding: 80px 20px;
            flex-direction: column;
            gap: 100px;
        }
        
        .section-title {
            font-size: 3.5rem;
            text-align: center;
            margin-bottom: 60px;
            background: linear-gradient(45deg, #FFD700, #FFA500, #FFD700);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-shadow: 0 0 15px rgba(255, 215, 0, 0.5);
            font-weight: 700;
            position: relative;
            display: inline-block;
            padding: 0 20px;
            font-family: 'Playfair Display', serif;
        }
        
        .section-title::after {
            content: "";
            position: absolute;
            bottom: -15px;
            left: 20%;
            width: 60%;
            height: 4px;
            background: linear-gradient(90deg, transparent, #FFD700, transparent);
            border-radius: 2px;
        }
        
        .section-title i {
            margin-right: 15px;
            font-size: 3rem;
            vertical-align: middle;
        }
        
        /* ===== YEAR CARDS STYLES ===== */
        .large-years {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-wrap: wrap;
            gap: 50px;
            width: 100%;
            max-width: 1600px;
        }
        
        .large-year {
            background: linear-gradient(135deg, rgba(58, 109, 201, 0.8), rgba(42, 77, 155, 0.9));
            border-radius: 25px;
            width: 320px;
            height: 380px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            font-size: 2.8rem;
            font-weight: bold;
            border: 2px solid rgba(255, 215, 0, 0.4);
            transition: all 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.3), 0 0 25px rgba(255, 215, 0, 0.2);
            cursor: pointer;
            text-align: center;
            padding: 30px;
            position: relative;
            overflow: hidden;
        }
        
        .large-year::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(45deg, transparent, rgba(255,255,255,0.1), transparent);
            transform: translateX(-100%) skewX(-15deg);
            transition: transform 0.8s;
        }
        
        .large-year:hover::before {
            transform: translateX(100%) skewX(-15deg);
        }
        
        .large-year:hover {
            transform: translateY(-15px) scale(1.05);
            box-shadow: 0 25px 50px rgba(0, 0, 0, 0.4), 0 0 40px rgba(255, 215, 0, 0.4);
        }
        
        .large-year .year-icon {
            font-size: 7rem;
            margin-bottom: 30px;
            color: #FFD700;
            text-shadow: 0 0 20px rgba(255, 215, 0, 0.7);
            filter: drop-shadow(0 0 10px rgba(255, 215, 0, 0.5));
            transition: all 0.4s;
        }
        
        .large-year:hover .year-icon {
            transform: scale(1.2) rotate(10deg);
            filter: drop-shadow(0 0 15px rgba(255, 215, 0, 0.8));
        }
        
        .large-year .year-period {
            font-size: 3rem;
            margin-bottom: 15px;
            background: linear-gradient(45deg, #FFD700, #FFA500);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-weight: 700;
        }
        
        .large-year .year-label {
            font-size: 1.6rem;
            opacity: 0.9;
            color: #e0e0ff;
            font-weight: 500;
        }
        
        /* ===== MASTERS/PHD BUTTON STYLES ===== */
        .masters-phd-section {
            width: 100%;
            text-align: center;
            margin-top: 30px;
        }
        
        .masters-phd-button {
            background: linear-gradient(135deg, rgba(255, 140, 66, 0.9), rgba(232, 106, 51, 0.9));
            border-radius: 35px;
            width: 650px;
            height: 240px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            font-size: 3rem;
            font-weight: bold;
            border: 4px solid rgba(255, 215, 0, 0.7);
            transition: all 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            box-shadow: 0 25px 50px rgba(0, 0, 0, 0.5), 0 0 40px rgba(255, 140, 66, 0.6);
            cursor: pointer;
            text-align: center;
            padding: 40px;
            margin: 0 auto;
            position: relative;
            overflow: hidden;
        }
        
        .masters-phd-button::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(45deg, transparent, rgba(255,255,255,0.2), transparent);
            transform: translateX(-100%) skewX(-15deg);
            transition: transform 0.8s;
        }
        
        .masters-phd-button:hover::before {
            transform: translateX(100%) skewX(-15deg);
        }
        
        .masters-phd-button:hover {
            transform: translateY(-15px) scale(1.1);
            box-shadow: 0 35px 70px rgba(0, 0, 0, 0.6), 0 0 60px rgba(255, 140, 66, 0.8);
        }
        
        .masters-phd-button .button-icon {
            font-size: 5.5rem;
            margin-bottom: 20px;
            color: #FFD700;
            text-shadow: 0 0 30px rgba(255, 215, 0, 0.9);
            filter: drop-shadow(0 0 20px rgba(255, 215, 0, 0.7));
            transition: all 0.4s;
        }
        
        .masters-phd-button:hover .button-icon {
            transform: scale(1.3) rotate(15deg);
            filter: drop-shadow(0 0 25px rgba(255, 215, 0, 1));
        }
        
        .masters-phd-button .button-text {
            background: linear-gradient(45deg, #FFD700, #FFA500);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-weight: 800;
            letter-spacing: 1px;
            text-shadow: 0 0 15px rgba(255, 215, 0, 0.5);
            line-height: 1.2;
        }
        
        /* ===== YEAR BUTTONS CONTAINER ===== */
        .year-buttons-container {
            display: none;
            flex-direction: column;
            align-items: center;
            margin-top: 40px;
            padding: 40px 20px;
            background: rgba(20, 40, 80, 0.9);
            border-radius: 0;
            width: 100%;
            min-height: 100vh;
            border: none;
            box-shadow: none;
        }
        
        .year-buttons-title {
            font-size: 3rem;
            margin-bottom: 40px;
            text-align: center;
            background: linear-gradient(45deg, #FFD700, #FFA500);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-weight: 700;
        }
        
        .year-buttons {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 25px;
            width: 100%;
            max-width: 1200px;
        }
        
        .year-button {
            background: linear-gradient(135deg, rgba(58, 109, 201, 0.8), rgba(42, 77, 155, 0.9));
            border-radius: 15px;
            padding: 25px 35px;
            font-size: 1.8rem;
            font-weight: bold;
            border: 2px solid rgba(255, 215, 0, 0.4);
            transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.3), 0 0 15px rgba(255, 215, 0, 0.2);
            cursor: pointer;
            min-width: 180px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        
        .year-button::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(45deg, transparent, rgba(255,255,255,0.1), transparent);
            transform: translateX(-100%) skewX(-15deg);
            transition: transform 0.6s;
        }
        
        .year-button:hover::before {
            transform: translateX(100%) skewX(-15deg);
        }
        
        .year-button:hover {
            transform: scale(1.08);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.4), 0 0 25px rgba(255, 215, 0, 0.4);
        }
        
        /* ===== BUTTON STYLES ===== */
        .back-button {
            background: linear-gradient(135deg, rgba(255, 140, 66, 0.9), rgba(232, 106, 51, 0.9));
            margin-top: 40px;
            padding: 18px 35px;
            border-radius: 12px;
            font-weight: bold;
            cursor: pointer;
            border: none;
            color: #F8F6F2;
            font-size: 1.5rem;
            transition: all 0.4s;
            border: 2px solid rgba(255, 215, 0, 0.4);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.3);
        }
        
        .back-button:hover {
            transform: scale(1.05);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.4), 0 0 20px rgba(255, 140, 66, 0.5);
        }
        
        /* ===== STUDENT PAGE STYLES ===== */
        .student-page {
            display: none;
            padding: 60px 20px;
            text-align: center;
            min-height: 100vh;
            width: 100%;
        }
        
        .student-page h2 {
            font-size: 3.5rem;
            margin-bottom: 50px;
            background: linear-gradient(45deg, #FFD700, #FFA500, #FFD700);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-shadow: 0 0 15px rgba(255, 215, 0, 0.5);
            font-weight: 700;
        }
        
        .students-list {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
            gap: 35px;
            margin-top: 40px;
            width: 100%;
            max-width: 1400px;
            margin-left: auto;
            margin-right: auto;
        }
        
        .student-card {
            background: linear-gradient(135deg, rgba(58, 109, 201, 0.7), rgba(42, 77, 155, 0.8));
            border-radius: 20px;
            padding: 35px;
            border: 2px solid rgba(255, 215, 0, 0.4);
            transition: all 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            cursor: pointer;
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
            min-height: 420px;
            justify-content: space-between;
            position: relative;
            overflow: hidden;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.3);
        }
        
        .student-card::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(45deg, transparent, rgba(255,255,255,0.1), transparent);
            transform: translateX(-100%) skewX(-15deg);
            transition: transform 0.8s;
        }
        
        .student-card:hover::before {
            transform: translateX(100%) skewX(-15deg);
        }
        
        .student-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 25px 50px rgba(0, 0, 0, 0.4), 0 0 30px rgba(255, 215, 0, 0.4);
        }
        
        .student-image {
            width: 160px;
            height: 160px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid rgba(255, 215, 0, 0.5);
            margin-bottom: 25px;
            box-shadow: 0 0 20px rgba(255, 215, 0, 0.4);
        }
        
        .student-card h3 {
            font-size: 2rem;
            margin-bottom: 15px;
            background: linear-gradient(45deg, #FFD700, #FFA500);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-weight: 700;
        }
        
        .student-card p {
            margin-bottom: 10px;
            font-size: 1.3rem;
            color: #e0e0ff;
        }
        
        .student-icon {
            font-size: 3rem;
            margin-bottom: 20px;
            color: #FFD700;
            text-shadow: 0 0 15px rgba(255, 215, 0, 0.7);
            filter: drop-shadow(0 0 8px rgba(255, 215, 0, 0.5));
        }
        
        .back-to-years {
            background: linear-gradient(135deg, rgba(58, 109, 201, 0.9), rgba(42, 77, 155, 0.9));
            margin-top: 50px;
            padding: 18px 40px;
            border-radius: 12px;
            font-weight: bold;
            cursor: pointer;
            border: none;
            color: #F8F6F2;
            font-size: 1.5rem;
            transition: all 0.4s;
            border: 2px solid rgba(255, 215, 0, 0.4);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.3);
        }
        
        .back-to-years:hover {
            transform: scale(1.05);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.4), 0 0 20px rgba(58, 109, 201, 0.5);
        }
        
        /* ===== MASTERS/PHD PAGE STYLES ===== */
        .masters-phd-page {
            display: none;
            padding: 60px 20px;
            text-align: center;
            min-height: 100vh;
            width: 100%;
        }
        
        .masters-phd-page h2 {
            font-size: 3.5rem;
            margin-bottom: 50px;
            background: linear-gradient(45deg, #FFD700, #FFA500, #FFD700);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-shadow: 0 0 15px rgba(255, 215, 0, 0.5);
            font-weight: 700;
        }
        
        .graduates-list {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(400px, 1fr));
            gap: 40px;
            margin-top: 40px;
            width: 100%;
            max-width: 1400px;
            margin-left: auto;
            margin-right: auto;
        }
        
        .graduate-card {
            background: linear-gradient(135deg, rgba(255, 140, 66, 0.7), rgba(232, 106, 51, 0.8));
            border-radius: 20px;
            padding: 40px;
            border: 2px solid rgba(255, 215, 0, 0.5);
            transition: all 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            cursor: pointer;
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
            min-height: 480px;
            justify-content: space-between;
            position: relative;
            overflow: hidden;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.3);
        }
        
        .graduate-card::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(45deg, transparent, rgba(255,255,255,0.15), transparent);
            transform: translateX(-100%) skewX(-15deg);
            transition: transform 0.8s;
        }
        
        .graduate-card:hover::before {
            transform: translateX(100%) skewX(-15deg);
        }
        
        .graduate-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 25px 50px rgba(0, 0, 0, 0.4), 0 0 30px rgba(255, 140, 66, 0.6);
        }
        
        .graduate-image {
            width: 180px;
            height: 180px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid rgba(255, 215, 0, 0.6);
            margin-bottom: 25px;
            box-shadow: 0 0 25px rgba(255, 215, 0, 0.5);
        }
        
        .graduate-card h3 {
            font-size: 2.2rem;
            margin-bottom: 15px;
            background: linear-gradient(45deg, #FFD700, #FFA500);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-weight: 700;
        }
        
        .degree-badge {
            background: linear-gradient(135deg, #FF8C42, #E86A33);
            padding: 10px 25px;
            border-radius: 25px;
            font-weight: bold;
            margin-bottom: 20px;
            font-size: 1.4rem;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
            border: 1px solid rgba(255, 215, 0, 0.5);
        }
        
        .graduate-card p {
            margin-bottom: 12px;
            font-size: 1.3rem;
            color: #fff;
        }
        
        .graduate-icon {
            font-size: 3.5rem;
            margin-bottom: 25px;
            color: #FFD700;
            text-shadow: 0 0 20px rgba(255, 215, 0, 0.7);
            filter: drop-shadow(0 0 10px rgba(255, 215, 0, 0.5));
        }
        
        .back-to-main {
            background: linear-gradient(135deg, rgba(58, 109, 201, 0.9), rgba(42, 77, 155, 0.9));
            margin-top: 50px;
            padding: 18px 40px;
            border-radius: 12px;
            font-weight: bold;
            cursor: pointer;
            border: none;
            color: #F8F6F2;
            font-size: 1.5rem;
            transition: all 0.4s;
            border: 2px solid rgba(255, 215, 0, 0.4);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.3);
        }
        
        .back-to-main:hover {
            transform: scale(1.05);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.4), 0 0 20px rgba(58, 109, 201, 0.5);
        }
        
        /* ===== MODAL STYLES ===== */
        .detail-modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.9);
            z-index: 1000;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }
        
        .modal-content {
            background: linear-gradient(135deg, rgba(20, 40, 80, 0.95), rgba(42, 77, 155, 0.95));
            border-radius: 25px;
            padding: 40px;
            max-width: 800px;
            width: 100%;
            max-height: 90vh;
            overflow-y: auto;
            position: relative;
            box-shadow: 0 25px 60px rgba(0, 0, 0, 0.6);
            border: 2px solid rgba(255, 215, 0, 0.5);
            animation: modalAppear 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        }
        
        @keyframes modalAppear {
            0% {
                opacity: 0;
                transform: scale(0.8) translateY(-50px);
            }
            100% {
                opacity: 1;
                transform: scale(1) translateY(0);
            }
        }
        
        .close-modal {
            position: absolute;
            top: 20px;
            right: 25px;
            font-size: 2.5rem;
            cursor: pointer;
            color: #FFD700;
            transition: transform 0.3s;
            text-shadow: 0 0 10px rgba(255, 215, 0, 0.7);
        }
        
        .close-modal:hover {
            transform: scale(1.2) rotate(90deg);
        }
        
        .modal-header {
            text-align: center;
            margin-bottom: 30px;
        }
        
        .modal-header h3 {
            font-size: 2.5rem;
            background: linear-gradient(45deg, #FFD700, #FFA500);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 15px;
            font-weight: 700;
        }
        
        .modal-body {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 25px;
        }
        
        .modal-image {
            width: 220px;
            height: 220px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid rgba(255, 215, 0, 0.6);
            box-shadow: 0 0 30px rgba(255, 215, 0, 0.5);
        }
        
        .modal-info {
            width: 100%;
            text-align: left;
            background: rgba(255, 255, 255, 0.05);
            border-radius: 15px;
            padding: 25px;
            border: 1px solid rgba(255, 215, 0, 0.3);
        }
        
        .modal-info p {
            margin-bottom: 12px;
            font-size: 1.3rem;
            padding: 8px 0;
            border-bottom: 1px solid rgba(255, 215, 0, 0.2);
        }
        
        .modal-info strong {
            background: linear-gradient(45deg, #FFD700, #FFA500);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        
        /* ===== FOOTER STYLES ===== */
        footer {
            text-align: center;
            padding: 40px;
            background: rgba(15, 30, 60, 0.8);
            color: #b0b0ff;
            border-top: 1px solid rgba(255, 215, 0, 0.2);
            font-size: 1.2rem;
        }
        
        .footer-text {
            background: linear-gradient(45deg, #FFD700, #FFA500);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-weight: 600;
        }
        
        /* ===== ENHANCED STYLES ===== */
        .enhanced-card {
            position: relative;
            overflow: hidden;
            transition: all 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        }
        
        .enhanced-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.2), transparent);
            transition: left 0.7s;
        }
        
        .enhanced-card:hover::before {
            left: 100%;
        }
        
        .enhanced-card:hover {
            transform: translateY(-10px) scale(1.03);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.4), 0 0 40px rgba(255, 215, 0, 0.5);
        }
        
        .page-transition {
            animation: pageFadeIn 0.8s ease-out;
        }
        
        @keyframes pageFadeIn {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .loading-spinner {
            display: none;
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            z-index: 9999;
        }
        
        .spinner {
            width: 70px;
            height: 70px;
            border: 7px solid rgba(255, 215, 0, 0.3);
            border-radius: 50%;
            border-top-color: #FFD700;
            animation: spin 1s linear infinite;
        }
        
        @keyframes spin {
            100% { transform: rotate(360deg); }
        }
        
        .typewriter {
            overflow: hidden;
            border-right: .15em solid #FFD700;
            white-space: nowrap;
            margin: 0 auto;
            animation: typing 3.5s steps(40, end), blink-caret .75s step-end infinite;
        }
        
        @keyframes typing {
            from { width: 0 }
            to { width: 100% }
        }
        
        @keyframes blink-caret {
            from, to { border-color: transparent }
            50% { border-color: #FFD700; }
        }
        
        .image-3d {
            transition: transform 0.5s ease;
            transform-style: preserve-3d;
        }
        
        .image-3d:hover {
            transform: perspective(1000px) rotateY(10deg) rotateX(5deg) scale(1.05);
        }
        
        .magic-button {
            position: relative;
            overflow: hidden;
        }
        
        .magic-button::after {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: conic-gradient(from 0deg, transparent, rgba(255,215,0,0.5), transparent);
            animation: rotate 3s linear infinite;
        }
        
        @keyframes rotate {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        
        .magic-button:hover::after {
            animation-duration: 1s;
        }
        
        /* ===== RESPONSIVE STYLES ===== */
        @media (max-width: 1200px) {
            .large-years {
                gap: 30px;
            }
            
            .large-year {
                width: 280px;
                height: 340px;
            }
            
            .large-year .year-period {
                font-size: 2.5rem;
            }
            
            .masters-phd-button {
                width: 500px;
                height: 200px;
                font-size: 2.5rem;
            }
            
            .masters-phd-button .button-icon {
                font-size: 4.5rem;
            }
        }
        
        @media (max-width: 768px) {
            .header-logo {
                height: 80px;
                top: 20px;
                left: 20px;
            }
            
            /* CHỈNH SỬA: Responsive cho chữ VINH DANH */
            .glowing-text {
                font-size: 4.5rem; /* Tăng từ 3rem lên 4.5rem */
            }
            
            .subtitle {
                font-size: 1.6rem;
            }
            
            .large-years {
                flex-direction: column;
                gap: 25px;
            }
            
            .large-year {
                width: 280px;
                height: 320px;
            }
            
            .large-year .year-period {
                font-size: 2.2rem;
            }
            
            .large-year .year-label {
                font-size: 1.3rem;
            }
            
            .masters-phd-button {
                width: 350px;
                height: 160px;
                font-size: 2.2rem;
                padding: 30px;
            }
            
            .masters-phd-button .button-icon {
                font-size: 4rem;
                margin-bottom: 15px;
            }
            
            .section-title {
                font-size: 2.5rem;
            }
            
            .year-buttons {
                flex-direction: column;
                align-items: center;
            }
            
            .year-button {
                width: 90%;
                max-width: 300px;
            }
            
            .students-list, .graduates-list {
                grid-template-columns: 1fr;
            }
        }
        
        @media (max-width: 480px) {
            .header-logo {
                height: 60px;
                top: 15px;
                left: 15px;
            }
            
            /* CHỈNH SỬA: Responsive cho chữ VINH DANH */
            .glowing-text {
                font-size: 3.5rem; /* Tăng từ 2.2rem lên 3.5rem */
            }
            
            .subtitle {
                font-size: 1.3rem;
            }
            
            .large-year {
                width: 260px;
                height: 300px;
            }
            
            .large-year .year-period {
                font-size: 2rem;
            }
            
            .large-year .year-icon {
                font-size: 5rem;
            }
            
            .masters-phd-button {
                width: 300px;
                height: 140px;
                font-size: 1.8rem;
                padding: 25px;
            }
            
            .masters-phd-button .button-icon {
                font-size: 3.5rem;
                margin-bottom: 10px;
            }
            
            .section-title {
                font-size: 2rem;
            }
            
            .modal-content {
                padding: 25px;
            }
            
            .modal-image {
                width: 180px;
                height: 180px;
            }
        }
    </style>
</head>
<body>
    <!-- Hiệu ứng nền động -->
    <div class="dynamic-bg"></div>
    
    <!-- Hiệu ứng hạt ánh sáng -->
    <div class="particles" id="particles"></div>
    
    <!-- Hiệu ứng ánh sáng chiếu -->
    <div class="spotlight"></div>
    
    <!-- Loading spinner -->
    <div class="loading-spinner" id="loadingSpinner">
        <div class="spinner"></div>
    </div>
    
    <div class="floating-elements">
        <!-- Thêm nhiều phần tử trôi nổi hơn -->
        <div class="floating-element" style="width: 80px; height: 80px; top: 5%; left: 5%; animation-delay: 0s; animation-duration: 25s;"></div>
        <div class="floating-element" style="width: 120px; height: 120px; top: 15%; left: 80%; animation-delay: -2s; animation-duration: 30s;"></div>
        <div class="floating-element" style="width: 60px; height: 60px; top: 70%; left: 10%; animation-delay: -5s; animation-duration: 20s;"></div>
        <div class="floating-element" style="width: 100px; height: 100px; top: 40%; left: 60%; animation-delay: -8s; animation-duration: 35s;"></div>
        <div class="floating-element" style="width: 90px; height: 90px; top: 85%; left: 75%; animation-delay: -12s; animation-duration: 28s;"></div>
        <div class="floating-element" style="width: 70px; height: 70px; top: 20%; left: 30%; animation-delay: -15s; animation-duration: 22s;"></div>
    </div>
    
    <div class="container">
        <header>
            <div class="header-content">
                <div class="header-icon">
                    <i class="fas fa-trophy"></i>
                </div>
                <h1 class="glowing-text typewriter">BẢNG VINH DANH</h1>
                <div class="subtitle">20 NĂM HỌC THÀNH TÍCH RỰC RỠ</div>
            </div>
            <img src="https://i.postimg.cc/zGwcmPH1/image.png" alt="Logo" class="header-logo">
        </header>
        
        <!-- TRANG CHÍNH -->
        <div class="main-content page-transition" id="mainPage">
            <!-- Mảng 1: Vinh danh học sinh giỏi -->
            <div class="students-section">
                <h2 class="section-title">
                    <i class="fas fa-crown"></i> VINH DANH HỌC SINH CÓ THÀNH TÍCH CAO 
                </h2>
                <div class="large-years">
                    <div class="large-year enhanced-card magic-button" data-year="2005-2010">
                        <div class="year-icon"><i class="fas fa-seedling"></i></div>
                        <div class="year-period">2005-2010</div>
                        <div class="year-label">Giai đoạn Khởi đầu</div>
                    </div>
                    <div class="large-year enhanced-card magic-button" data-year="2010-2015">
                        <div class="year-icon"><i class="fas fa-chart-line"></i></div>
                        <div class="year-period">2010-2015</div>
                        <div class="year-label">Giai đoạn Phát triển</div>
                    </div>
                    <div class="large-year enhanced-card magic-button" data-year="2015-2020">
                        <div class="year-icon"><i class="fas fa-user-graduate"></i></div>
                        <div class="year-period">2015-2020</div>
                        <div class="year-label">Giai đoạn Trưởng thành</div>
                    </div>
                    <div class="large-year enhanced-card magic-button" data-year="2020-2025">
                        <div class="year-icon"><i class="fas fa-laptop-code"></i></div>
                        <div class="year-period">2020-2025</div>
                        <div class="year-label">Giai đoạn Hiện đại</div>
                    </div>
                    <div class="large-year enhanced-card magic-button" data-year="2025-2030">
                        <div class="year-icon"><i class="fas fa-rocket"></i></div>
                        <div class="year-period">2025-2030</div>
                        <div class="year-label">Giai đoạn Tương lai</div>
                    </div>
                </div>
            </div>
            
            <!-- Mảng 2: Vinh danh Thạc sĩ, Tiến sĩ - NÚT LỚN HƠN với chữ nhỏ hơn -->
            <div class="masters-phd-section">
                <h2 class="section-title">
                    <i class="fas fa-gem"></i> VINH DANH THẠC SĨ - TIẾN SĨ
                </h2>
                <div class="masters-phd-button enhanced-card magic-button" id="mastersPhdButton">
                    <div class="button-icon"><i class="fas fa-award"></i></div>
                    <div class="button-text">KHÁM PHÁ DANH SÁCH</div>
                </div>
            </div>
        </div>
        
        <!-- Container for year buttons -->
        <div class="year-buttons-container page-transition" id="yearButtonsContainer">
            <h2 class="year-buttons-title" id="yearButtonsTitle">Học sinh xuất sắc năm học</h2>
            <div class="year-buttons" id="yearButtons"></div>
            <button class="back-button magic-button" id="backButton">Quay lại</button>
        </div>
        
        <!-- Container for student page -->
        <div class="student-page page-transition" id="studentPage">
            <h2 id="studentPageTitle">VINH DANH HỌC SINH XUẤT SẮC NĂM HỌC</h2>
            <div class="students-list" id="studentsList"></div>
            <button class="back-to-years magic-button" id="backToYears">Quay lại danh sách năm học</button>
        </div>
        
        <!-- TRANG THẠC SĨ, TIẾN SĨ -->
        <div class="masters-phd-page page-transition" id="mastersPhdPage">
            <h2><i class="fas fa-gem"></i> VINH DANH CỰU HỌC SINH ĐẠT THẠC SĨ - TIẾN SĨ</h2>
            <div class="graduates-list" id="graduatesList"></div>
            <button class="back-to-main magic-button" id="backToMain">Quay lại trang chính</button>
        </div>
        
        <!-- Modal for details -->
        <div class="detail-modal" id="detailModal">
            <div class="modal-content">
                <span class="close-modal" id="closeModal">&times;</span>
                <div class="modal-header">
                    <h3 id="modalPersonName">Học sinh 1</h3>
                </div>
                <div class="modal-body">
                    <img src="" alt="Ảnh" class="modal-image image-3d" id="modalPersonImage">
                    <div class="modal-info" id="modalPersonInfo">
                        <!-- Information will be inserted here -->
                    </div>
                </div>
            </div>
        </div>
    </div>

    <script>
        // ===== DỮ LIỆU HỌC SINH THỰC TẾ =====
        const studentsData = {
            // ===== 2005-2010 =====
            "2005-2006": [
                {
                    name: "NGUYỄN CÔNG ĐỊNH",
                    class: "9A",
                    achievement: "Giải Nhất Vật Lý cấp Huyện, Giải Ba Vật Lý cấp Tỉnh",
                    score: "19"
                },
                {
                    name: "PHẠM THỊ NGỌC MAI",
                    class: "9A",
                    achievement: "Giải Nhất Sinh Học cấp Huyện, Giải Nhì Sinh Học cấp Tỉnh",
                    score: "19"
                },
                {
                    name: "ĐỖ XUÂN TUẤN",
                    class: "9A",
                    achievement: "Giải Nhất Thể Dục cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN THỊ PHƯƠNG ANH",
                    class: "9B",
                    achievement: "Giải Ba Thể Dục cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LÊ THỊ HÀ",
                    class: "7C",
                    achievement: "Giải Nhất Thể Dục cấp Tỉnh",
                    teacher: "",
                    score: ""
                }
            ],
            
            "2006-2007": [
                {
                    name: "NGUYỄN CÔNG ĐỊNH",
                    class: "9A",
                    achievement: "Giải Nhất Vật Lý cấp Huyện, Giải Ba Vật Lý cấp Tỉnh",
                    score: "19"
                },
                {
                    name: "PHẠM THỊ NGỌC MAI",
                    class: "9A",
                    achievement: "Giải Nhất Sinh Học cấp Huyện, Giải Nhì Sinh Học cấp Tỉnh",
                    score: "19"
                },
                {
                    name: "ĐỖ XUÂN TUẤN",
                    class: "9A",
                    achievement: "Giải Nhất Thể Dục cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN THỊ PHƯƠNG ANH",
                    class: "9B",
                    achievement: "Giải Ba Thể Dục cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LÊ THỊ HÀ",
                    class: "7C",
                    achievement: "Giải Nhất Thể Dục cấp Tỉnh",
                    teacher: "",
                    score: ""
                }
            ],
            
            "2007-2008": [
                {
                {
                    name: "ĐỖ NGỌC TRÂM",
                    class: "9A",
                    achievement: "Giải Nhất CASSIO cấp Huyện",
                    teacher: "LÊ THỊ THU NGA",
                    score: ""
                },
                {
                    name: "ĐỖ THỊ TRANG DUYÊN",
                    class: "9A",
                    achievement: "Giải Nhất Hóa Học cấp Huyện",
                    teacher: "ĐINH THỊ THO",
                    score: "18.5"
                },
                {
                    name: "HỒ VIỆT TÍN",
                    class: "9C",
                    achievement: "Giải Nhất Hóa Học cấp Huyện",
                    teacher: "ĐINH THỊ THO",
                    score: "18"
                },
                {
                    name: "PHẠM MẠNH HÙNG",
                    class: "9B",
                    achievement: "Cúp Vô Địch Bóng Rổ Nam cấp Tỉnh, Thành tích Điền Kinh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "VŨ QUANG SƠN",
                    class: "9B",
                    achievement: "Cúp Vô Địch Bóng Rổ Nam cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "HỒ QUÝ LY",
                    class: "9D",
                    achievement: "Cúp Vô Địch Bóng Rổ Nam cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "HỒ QUANG TÂM",
                    class: "9D",
                    achievement: "Giải Nhì Bóng Rổ Nam cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "ĐÀO XUÂN LAM",
                    class: "9D",
                    achievement: "Cúp Vô Địch Bóng Rổ Nam cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRẦN THÁI HỌC",
                    class: "9D",
                    achievement: "Giải Nhì Bóng Rổ Nam cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN NGỌC QUÝ",
                    class: "8A",
                    achievement: "Cúp Vô Địch Bóng Rổ Nam cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LƯƠNG THANH HIẾU",
                    class: "9A",
                    achievement: "Cúp Vô Địch Bóng Rổ Nam cấp Tỉnh, Thành tích Điền Kinh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN NGỌC ANH",
                    class: "9A",
                    achievement: "Cúp Vô Địch Bóng Rổ Nam cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGÔ QUỐC HUY",
                    class: "9D",
                    achievement: "Giải Nhì Bóng Rổ Nam cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRẦN TẤN THỊNH",
                    class: "8C",
                    achievement: "Cúp Vô Địch Bóng Rổ Nam cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN CÔNG TRÚC",
                    class: "9A",
                    achievement: "Giải Nhì Bóng Rổ Nam cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM VĂN THẮNG",
                    class: "8B",
                    achievement: "Cúp Vô Địch Bóng Rổ Nam cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM QUỐC HOÀNG",
                    class: "8C",
                    achievement: "Giải Nhì Bóng Rổ Nam cấp Tỉnh, Thành tích Điền Kinh",
                    teacher: "Trần Công Vinh",
                    score: ""
                },
                {
                    name: "HỒ LÊ XUÂN QUYỀN",
                    class: "9A",
                    achievement: "Giải Nhì Bóng Rổ Nam cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM THỊ THƯƠNG",
                    class: "9D",
                    achievement: "Giải Nhì Bóng Rổ Nam cấp Tỉnh, Thành tích Bóng rổ",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRƯƠNG QUANG NGỌC",
                    class: "9A",
                    achievement: "Giải Nhì Bóng Bàn cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN SƠN TRƯỜNG",
                    class: "9A",
                    achievement: "Giải Nhì - Ba Bóng Bàn cấp Tỉnh, Thành tích Bóng bàn cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LÊ TRƯỜNG THỌ",
                    class: "8C",
                    achievement: "Giải Nhì - Ba Bóng Bàn cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LÊ THỊ HÀ",
                    class: "9C",
                    achievement: "Giải Ba Bóng Bàn cấp Tỉnh, Thành tích Bóng bàn cấp Huyện",
                    teacher: "Lê Viết Tương",
                    score: ""
                },
                {
                    name: "TẠ NGỌC THẾ",
                    class: "8D",
                    achievement: "Giải Ba Bóng Bàn cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "ĐỖ NGỌC TRANG NHUNG",
                    class: "7A",
                    achievement: "Giải Nhì - Ba Bóng Bàn cấp Tỉnh, Giải Nhất Bóng Bàn cấp Huyện",
                    teacher: "Trần Công Vinh",
                    score: ""
                },
                {
                    name: "NGUYỄN THỊ THANH XUÂN",
                    class: "7A",
                    achievement: "Giải Nhì - Ba Bóng Bàn cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN HUỆ NHẠN",
                    class: "9C",
                    achievement: "Giải Nhì - Ba Bóng Bàn cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM THÁI THÚY THÚY",
                    class: "9C",
                    achievement: "2 Giải Nhất Bóng Bàn cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM THỊ THẢO NGUYÊN",
                    class: "9C",
                    achievement: "Giải Nhất - Nhì Bóng Bàn cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LÊ THỊ MỸ VÂN",
                    class: "9D",
                    achievement: "Thành tích Bắn nỏ",
                    teacher: "",
                    score: ""
                },
                {
                    name: "ĐỖ ĐÌNH ĐỨC",
                    class: "9D",
                    achievement: "Thành tích Bắn nỏ",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN THỊ HOÀI VI",
                    class: "9A",
                    achievement: "Thành tích Bóng rổ",
                    teacher: "",
                    score: ""
                },
                {
                    name: "VƯƠNG THỊ PHƯƠNG DUYÊN",
                    class: "9A",
                    achievement: "Thành tích Bóng rổ",
                    teacher: "",
                    score: ""
                },
                {
                    name: "HỒ THỊ BẢO MI",
                    class: "9A",
                    achievement: "Thành tích Bóng rổ",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LÊ THỊ TÂN LỢI",
                    class: "9A",
                    achievement: "Thành tích Bóng rổ",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LÊ THỊ LINH NGUYÊN",
                    class: "9A",
                    achievement: "Thành tích Bóng rổ",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN THỊ THU HƯƠNG",
                    class: "9D",
                    achievement: "Thành tích Bóng rổ",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN THỊ THU PHƯƠNG",
                    class: "9D",
                    achievement: "Thành tích Bóng rổ",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN THỊ HẠNH",
                    class: "9B",
                    achievement: "Thành tích Bóng rổ",
                    teacher: "",
                    score: ""
                },
                {
                    name: "ĐOÀN THỊ THẢO",
                    class: "9B",
                    achievement: "Thành tích Bóng rổ",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRẦN THÙY TRANG",
                    class: "9B",
                    achievement: "Thành tích Bóng rổ",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN THỊ NGỌC TRÂM",
                    class: "9B",
                    achievement: "Thành tích Bóng rổ",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN LÊ TUYÊN",
                    class: "8C",
                    achievement: "Thành tích Điền Kinh",
                    teacher: "",
                    score: ""
                }
            ],
            
            "2009-2010": [
                               {
                    name: "NGUYỄN VĂN MẪN",
                    class: "9A",
                    achievement: "Giải Nhất Vật Lý cấp Huyện",
                    teacher: "NGUYỄN THỊ NGÂN",
                    score: "18.5"
                },
                {
                    name: "ĐẶNG HOÀNG LÂM",
                    class: "9A",
                    achievement: "Giải Nhất Sinh Học cấp Huyện, Giải Nhì Sinh Học cấp Tỉnh",
                    teacher: "BÙI THỊ TUYẾT",
                    score: "18"
                },
                {
                    name: "NGUYỄN THU HÀ",
                    class: "9A",
                    achievement: "Giải Nhất Lịch Sử cấp Huyện",
                    teacher: "ĐINH LƯƠNG BÀNH",
                    score: "18"
                },
                {
                    name: "CHU TRƯỜNG ĐẠT",
                    class: "9A",
                    achievement: "Giải Ba Toán cấp Tỉnh",
                    teacher: "LÊ THỊ THU NGA",
                    score: ""
                },
                {
                    name: "VŨ NGỌC THỦY TIÊN",
                    class: "9A",
                    achievement: "Giải Nhất CASSIO cấp Tỉnh",
                    teacher: "LÊ THỊ THU NGA",
                    score: ""
                },
                {
                    name: "NGUYỄN MINH LƯƠNG",
                    class: "9A",
                    achievement: "Giải Nhì Vật Lí cấp Tỉnh",
                    teacher: "NGUYỄN THỊ NGÂN",
                    score: ""
                },
                {
                    name: "TRẦN DUY HIỀN",
                    class: "9A",
                    achievement: "Giải Nhì Vật Lí cấp Tỉnh",
                    teacher: "NGUYỄN THỊ NGÂN",
                    score: ""
                },
                {
                    name: "TRẦN TẤN THỊNH",
                    class: "9C",
                    achievement: "Giải Nhất Bóng Rổ Nam cấp Huyện, Huy chương Bạc Bóng Rổ Nam cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "THÁI VIẾT NÔ VA",
                    class: "9C",
                    achievement: "Giải Nhất Bóng Rổ Nam cấp Huyện, Huy chương Bạc Bóng Rổ Nam cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM QUỐC HOÀNG",
                    class: "9C",
                    achievement: "Giải Nhất Bóng Rổ Nam cấp Huyện, Huy chương Bạc Bóng Rổ Nam cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "VŨ NGỌC SƯ HUYNH",
                    class: "8A",
                    achievement: "Giải Nhất Bóng Rổ Nam cấp Huyện, Huy chương Bạc Bóng Rổ Nam cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN MẠNH DŨNG",
                    class: "7A",
                    achievement: "Giải Nhất Bóng Rổ Nam cấp Huyện, Huy chương Bạc Bóng Rổ Nam cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN NGỌC QUÝ",
                    class: "9A",
                    achievement: "Giải Nhất Bóng Rổ Nam cấp Huyện, Huy chương Bạc Bóng Rổ Nam cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "VÕ THANH PHỤNG",
                    class: "9C",
                    achievement: "Giải Nhất Bóng Rổ Nam cấp Huyện, Huy chương Bạc Bóng Rổ Nam cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN BÁ RÔN",
                    class: "9C",
                    achievement: "Giải Nhất Bóng Rổ Nam cấp Huyện, Huy chương Bạc Bóng Rổ Nam cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TẠ QUANG DŨNG",
                    class: "9C",
                    achievement: "Giải Nhất Bóng Rổ Nam cấp Huyện, Huy chương Bạc Bóng Rổ Nam cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "VŨ XUÂN TRƯỜNG",
                    class: "7A",
                    achievement: "Giải Nhất Bóng Rổ Nam cấp Huyện, Huy chương Bạc Bóng Rổ Nam cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN THỊ TIỂU MY",
                    class: "9C",
                    achievement: "Giải Nhất Bóng Rổ Nữ cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "VŨ THỊ LAN ANH",
                    class: "9C",
                    achievement: "Giải Nhất Bóng Rổ Nữ cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM BÍCH PHƯỢNG",
                    class: "9C",
                    achievement: "Giải Nhất Bóng Rổ Nữ cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "BÙI THỊ THU TRANG",
                    class: "9C",
                    achievement: "Giải Nhất Bóng Rổ Nữ cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LÊ HUỲNH DUYÊN",
                    class: "8B",
                    achievement: "Giải Nhất Bóng Rổ Nữ cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM THỊ LINH PHƯƠNG",
                    class: "8B",
                    achievement: "Giải Nhất Bóng Rổ Nữ cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "VŨ THỊ THU HẠNH",
                    class: "8B",
                    achievement: "Giải Nhất Bóng Rổ Nữ cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "BÙI THỊ THÚY VÂN",
                    class: "8B",
                    achievement: "Giải Nhất Bóng Rổ Nữ cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "HOÀNG THỊ VÂN ANH",
                    class: "8B",
                    achievement: "Giải Nhất Bóng Rổ Nữ cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN THỊ HOÀI NHI",
                    class: "8A",
                    achievement: "Giải Nhất Bóng Rổ Nữ cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN THỊ NGỌC THU",
                    class: "8C",
                    achievement: "Giải Nhất Bóng Rổ Nữ cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN ĐĂNG HẢI",
                    class: "9C",
                    achievement: "Giải Nhì Bóng Ném Nam cấp Huyện, Huy chương Vàng Bóng Ném Nam cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM CHÍ TUÂN",
                    class: "9D",
                    achievement: "Giải Nhì Bóng Ném Nam cấp Huyện, Huy chương Vàng Bóng Ném Nam cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRẦN QUANG NGUYÊN",
                    class: "9C",
                    achievement: "Giải Nhì Bóng Ném Nam cấp Huyện, Huy chương Vàng Bóng Ném Nam cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM HỮU QUYẾT",
                    class: "9B",
                    achievement: "Giải Nhì Bóng Ném Nam cấp Huyện, Huy chương Vàng Bóng Ném Nam cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN TRỌNG THƯƠNG",
                    class: "9B",
                    achievement: "Giải Nhì Bóng Ném Nam cấp Huyện, Huy chương Vàng Bóng Ném Nam cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "ĐÀO NGỌC HOÀNG",
                    class: "9C",
                    achievement: "Giải Nhì Bóng Ném Nam cấp Huyện, Huy chương Vàng Bóng Ném Nam cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHÙNG HOÀNG TRUNG",
                    class: "9D",
                    achievement: "Giải Nhì Bóng Ném Nam cấp Huyện, Huy chương Vàng Bóng Ném Nam cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LÊ HẢI NAM",
                    class: "9C",
                    achievement: "Giải Nhì Bóng Ném Nam cấp Huyện, Huy chương Vàng Bóng Ném Nam cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "BÙI THỊ THẢO NHƯ",
                    class: "8A",
                    achievement: "Giải Nhất Aerobic cấp Huyện, 2 Huy chương Vàng Aerobic cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "VŨ THỊ THANH TÂM",
                    class: "8A",
                    achievement: "Giải Nhất Aerobic cấp Huyện, 2 Huy chương Vàng Aerobic cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM THỊ BÍCH NGỌC",
                    class: "8A",
                    achievement: "Giải Nhất Aerobic cấp Huyện, 2 Huy chương Vàng Aerobic cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHAN THỊ ÁNH TUYẾT",
                    class: "8A",
                    achievement: "Giải Nhất Aerobic cấp Huyện, 2 Huy chương Vàng Aerobic cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LÊ THỊ TRÚC KHƯƠNG",
                    class: "8B",
                    achievement: "Giải Nhất Aerobic cấp Huyện, 2 Huy chương Vàng Aerobic cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN THỊ NGỌC ÁNH",
                    class: "8C",
                    achievement: "Giải Nhất Aerobic cấp Huyện, 2 Huy chương Vàng Aerobic cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRẦN THỊ THÙY TRÂM",
                    class: "8C",
                    achievement: "Giải Nhất Aerobic cấp Huyện, 2 Huy chương Vàng Aerobic cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LÊ THỊ THƯƠNG",
                    class: "8D",
                    achievement: "Giải Nhất Aerobic cấp Huyện, 2 Huy chương Vàng Aerobic cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LƯƠNG THỊ PHƯƠNG HIẾU",
                    class: "6A",
                    achievement: "Giải Nhất Aerobic cấp Huyện, 2 Huy chương Vàng Aerobic cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN DƯƠNG ANH TUẤN",
                    class: "9D",
                    achievement: "Giải Nhất Bóng Đá cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN THỐNG NHẤT",
                    class: "9D",
                    achievement: "Giải Nhất Bóng Đá cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LÊ VĂN THÀNH",
                    class: "9D",
                    achievement: "Giải Nhất Bóng Đá cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LÊ TRỌNG ĐỨC",
                    class: "9D",
                    achievement: "Giải Nhất Bóng Đá cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN LÊ TUYÊN",
                    class: "9C",
                    achievement: "Giải Nhất Bóng Đá cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM BÁ KHẢI",
                    class: "8A",
                    achievement: "Giải Nhất Bóng Đá cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN TIẾN NGUYÊN",
                    class: "8A",
                    achievement: "Giải Nhất Bóng Đá cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN KIẾN THỨC",
                    class: "9C",
                    achievement: "Giải Nhất Bóng Đá cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN HỒNG QUANG",
                    class: "9D",
                    achievement: "Giải Nhất Bóng Đá cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN THỊ XUÂN",
                    class: "8A",
                    achievement: "Giải Nhất Bóng Bàn cấp Huyện, 1 Huy chương Đồng Bóng Bàn cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LÊ THỊ KIM ANH",
                    class: "7A",
                    achievement: "Giải Nhất Nghi thức Đội cấp Huyện",
                    teacher: "",
                    score: ""
                }
            ],
            
            // ===== 2010-2015 =====
            "2010-2011": 
            [
                {
                    name: "PHẠM QUỲNH HƯƠNG",
                    class: "8A",
                    achievement: "Giải Nhất Tiếng Anh cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGÔ THỊ ÁI QUYÊN",
                    class: "8A", 
                    achievement: "Giải Nhất Tiếng Anh cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "VŨ HỒNG VÂN",
                    class: "8A",
                    achievement: "Giải Nhất Tiếng Anh cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LÊ HOÀNG HUY",
                    class: "8C",
                    achievement: "Giải Nhất Tiếng Anh cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRẦN THỊ THU NGỌC",
                    class: "8C",
                    achievement: "Giải Nhất Tiếng Anh cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN HOÀNG CHÂU",
                    class: "9A",
                    achievement: "Giải Nhất Tiếng Anh cấp Huyện, Giải Ba Tiếng Anh cấp Tỉnh, Huy chương Bạc Tiếng Anh Quốc gia",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRẦN ĐÌNH NGUYÊN",
                    class: "9A",
                    achievement: "Giải Nhất Tiếng Anh cấp Huyện, Huy chương Vàng Tiếng Anh Quốc gia",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM THÀNH NGUYÊN",
                    class: "9A",
                    achievement: "Giải Nhất Tiếng Anh cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "ĐỖ NGỌC TRANG NHUNG",
                    class: "9A",
                    achievement: "Giải Nhất Tiếng Anh cấp Huyện, Giải Ba CASSIO cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LƯƠNG THỊ NGỌC THÚY",
                    class: "9A",
                    achievement: "Giải Nhất Tiếng Anh cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN THỊ NGỌC ANH",
                    class: "9A",
                    achievement: "Giải Nhất Tiếng Anh cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "HUỲNH TRẦN NGÂN PHƯƠNG",
                    class: "9A",
                    achievement: "Giải Nhất Tiếng Anh cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM THỊ KIM DUYÊN",
                    class: "9A",
                    achievement: "Giải Nhất Tiếng Anh cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN THỊ THANH XUÂN",
                    class: "9A",
                    achievement: "Giải Nhất Tiếng Anh cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRẦN MINH SANG",
                    class: "9B",
                    achievement: "Giải Nhất Tiếng Anh cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LÊ THỊ TRÚC KHƯƠNG",
                    class: "9B",
                    achievement: "Giải Nhất Tiếng Anh cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "ĐÀO HỒNG SƠN",
                    class: "9C",
                    achievement: "Giải Nhất Tiếng Anh cấp Huyện, Huy chương Bạc Tiếng Anh Quốc gia",
                    teacher: "",
                    score: ""
                },
                {
                    name: "HỒ VĂN TÚ",
                    class: "9C",
                    achievement: "Giải Nhất Tiếng Anh cấp Huyện",
                    teacher: "",
                    score: ""
                }
            ],
            
            "2011-2012": [
                                {
                    name: "VŨ HỒNG VÂN",
                    class: "9A",
                    achievement: "Giải Ba Toán cấp Tỉnh",
                    teacher: "ĐỖ VIẾT THÀNH",
                    score: "8.5"
                },
                {
                    name: "PHAN THỊ KIM NGÂN",
                    class: "9A",
                    achievement: "Giải Nhất Toán Internet cấp Huyện",
                    teacher: "ĐỖ VIẾT THÀNH",
                    score: "300"
                },
                {
                    name: "NGUYỄN VĂN MẠNH",
                    class: "8A",
                    achievement: "Giải Nhất Toán Internet cấp Huyện",
                    teacher: "BÙI NGUYÊN BÌNH",
                    score: "300"
                },
                {
                    name: "ĐẶNG THẢO VY",
                    class: "6A",
                    achievement: "Giải Nhất Toán Internet cấp Huyện",
                    teacher: "ĐỖ VIẾT THÀNH",
                    score: "250"
                },
                {
                    name: "NGUYỄN NGỌC SƠN",
                    class: "6A",
                    achievement: "Giải Nhất Toán Internet cấp Huyện",
                    teacher: "",
                    score: "250"
                },
                {
                    name: "HOÀNG PHI HÙNG",
                    class: "6A",
                    achievement: "Giải Nhất Toán Internet cấp Huyện",
                    teacher: "",
                    score: "250"
                },
                {
                    name: "HỒ PHƯƠNG THỦY",
                    class: "6A",
                    achievement: "Giải Nhất Toán Internet cấp Huyện",
                    teacher: "",
                    score: "250"
                },
                {
                    name: "VŨ TIẾN THIỆN QUANG",
                    class: "6A",
                    achievement: "Giải Nhất Toán Internet cấp Huyện",
                    teacher: "",
                    score: "250"
                },
                {
                    name: "NGUYỄN PHÚ TRUNG ANH",
                    class: "6B",
                    achievement: "Giải Nhất Toán Internet cấp Huyện",
                    teacher: "",
                    score: "250"
                },
                {
                    name: "NGUYỄN THỊ THU THẢO",
                    class: "6B",
                    achievement: "Giải Nhất Toán Internet cấp Huyện",
                    teacher: "",
                    score: "250"
                },
                {
                    name: "TRẦN DUY ANH",
                    class: "6A",
                    achievement: "Giải Nhất Toán Internet cấp Huyện",
                    teacher: "",
                    score: "250"
                },
                {
                    name: "TRẦN THỊ THU NGỌC",
                    class: "9C",
                    achievement: "Giải Nhất Tiếng Anh Internet cấp Huyện",
                    teacher: "DƯƠNG KHẮC NGỌC",
                    score: "300"
                },
                {
                    name: "LÊ THỊ THÙY TRANG",
                    class: "9A",
                    achievement: "Giải Nhất Tiếng Anh Internet cấp Huyện",
                    teacher: "",
                    score: "300"
                },
                {
                    name: "HOÀNG THỊ PHƯƠNG THẢO",
                    class: "9A",
                    achievement: "Giải Nhất Tiếng Anh Internet cấp Huyện",
                    teacher: "",
                    score: "300"
                },
                {
                    name: "ĐỖ THỊ HUYỀN TRANG",
                    class: "8A",
                    achievement: "Giải Nhất Tiếng Anh Internet cấp Huyện",
                    teacher: "",
                    score: "300"
                },
                {
                    name: "TRẦN THIÊN NGÂN",
                    class: "8A",
                    achievement: "Giải Nhất Tiếng Anh Internet cấp Huyện",
                    teacher: "",
                    score: "300"
                },
                {
                    name: "ĐỖ THỊ THU UYÊN",
                    class: "8A",
                    achievement: "Giải Nhất Tiếng Anh Internet cấp Huyện",
                    teacher: "",
                    score: "300"
                },
                {
                    name: "TRƯƠNG THỊ HIẾU NHƯ",
                    class: "8A",
                    achievement: "Giải Nhất Tiếng Anh Internet cấp Huyện",
                    teacher: "",
                    score: "300"
                },
                {
                    name: "NGUYỄN NGỌC NGUYÊN",
                    class: "8A",
                    achievement: "Giải Nhất Tiếng Anh Internet cấp Huyện",
                    teacher: "",
                    score: "300"
                },
                {
                    name: "ĐẶNG THỊ TUYẾT NHUNG",
                    class: "8A",
                    achievement: "Giải Nhất Tiếng Anh Internet cấp Huyện",
                    teacher: "",
                    score: "300"
                },
                {
                    name: "CAO THỊ LỆ HUYỀN",
                    class: "8A",
                    achievement: "Giải Nhất Tiếng Anh Internet cấp Huyện",
                    teacher: "",
                    score: "300"
                },
                {
                    name: "NGUYỄN TUẤN ANH",
                    class: "8B",
                    achievement: "Giải Nhất Tiếng Anh Internet cấp Huyện",
                    teacher: "NGUYỄN QUỐC HÒA",
                    score: "300"
                },
                {
                    name: "TRẦN ĐÀO XUÂN TRỌNG",
                    class: "8B",
                    achievement: "Giải Nhất Tiếng Anh Internet cấp Huyện",
                    teacher: "",
                    score: "300"
                },
                {
                    name: "NGUYỄN BẢO THIÊN",
                    class: "8B",
                    achievement: "Giải Nhất Tiếng Anh Internet cấp Huyện",
                    teacher: "",
                    score: "300"
                },
                {
                    name: "PHẠM THỊ PHƯƠNG TRÂM",
                    class: "7A",
                    achievement: "Giải Nhất Tiếng Anh Internet cấp Huyện",
                    teacher: "NGÔ THỊ LIỄU",
                    score: "300"
                },
                {
                    name: "NGUYỄN TRUNG KIÊN",
                    class: "7B",
                    achievement: "Giải Nhất Tiếng Anh Internet cấp Huyện",
                    teacher: "",
                    score: "300"
                },
                {
                    name: "NGUYỄN THANH PHƯƠNG",
                    class: "7A",
                    achievement: "Giải Nhất Tiếng Anh Internet cấp Huyện",
                    teacher: "",
                    score: "300"
                },
                {
                    name: "ĐÀO THỊ QUỲNH TRANG",
                    class: "7A",
                    achievement: "Giải Nhất Tiếng Anh Internet cấp Huyện",
                    teacher: "",
                    score: "300"
                },
                {
                    name: "NGUYỄN THỊ THÙY DƯƠNG",
                    class: "7A",
                    achievement: "Giải Nhất Tiếng Anh Internet cấp Huyện",
                    teacher: "",
                    score: "300"
                }
            ],
            
            "2012-2013": 
            [
                {
                    name: "NGUYỄN THIÊN NGÂN",
                    class: "9A",
                    achievement: "Giải Ba MTCasio cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "ĐỖ THỊ HUYỀN TRANG",
                    class: "9A",
                    achievement: "Giải Nhì MTCasio cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN NGỌC CAO",
                    class: "9A",
                    achievement: "Giải Ba Vật lí cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN THỊ TRÀ MY",
                    class: "9C",
                    achievement: "Giải Ba Địa lí cấp Tỉnh",
                    teacher: "",
                    score: ""
                }
            ],
            
            "2013-2014": 
            [
                {
                    name: "HÀ THỊ MINH THI",
                    class: "",
                    achievement: "Giải Nhất MTCT CASIO cấp Huyện, Giải Ba MTCT CASIO cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN THỊ PHƯƠNG MAI",
                    class: "",
                    achievement: "Giải Ba Sinh học cấp Tỉnh",
                    teacher: "",
                    score: ""
                }
            ],
            
            "2014-2015": [
                {
                    name: "PHÙNG THỊ BẢO QUỲNH",
                    class: "9A",
                    achievement: "Giải Nhất Sinh học cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN CỘNG MINH",
                    class: "9A",
                    achievement: "Giải Ba Vật lí cấp Tỉnh",
                    teacher: "",
                    score: ""
                }
            ],
            
            // ===== 2015-2020 =====
            "2015-2016": 
            [
                {
                    name: "PHẠM TRUNG KIÊN",
                    class: "9A",
                    achievement: "Giải Nhất Tiếng Anh cấp Huyện, Giải Nhì cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN THỊ NGUYỆT HÀ",
                    class: "9A",
                    achievement: "Giải Nhất Sinh học cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN NGÔ TRUNG KIÊN",
                    class: "9A",
                    achievement: "Giải Nhất MTCT Cassio cấp Huyện",
                    teacher: "",
                    score: ""
                }
            ],
            
            // ===== 2020-2025 =====
            "2021-2022": 
            [
                {
                    name: "NGUYỄN TRỌNG QUANG MINH",
                    class: "",
                    achievement: "Huy chương Vàng Violympic Toán TV cấp Tỉnh, Huy chương Đồng Olympic Tiếng Anh Quốc gia",
                    teacher: "",
                    score: ""
                },
                {
                    name: "VÕ ANH SỰ",
                    class: "",
                    achievement: "Huy chương Vàng Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM NHẬT MINH",
                    class: "",
                    achievement: "Huy chương Đồng Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "KHÚC ĐẶNG THIÊN KHÚC",
                    class: "",
                    achievement: "Huy chương Đồng Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM NGUYỄN HÀ NGÂN",
                    class: "",
                    achievement: "Huy chương Đồng Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN THUỲ DUNG",
                    class: "",
                    achievement: "Huy chương Đồng Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRỊNH GIA HÂN",
                    class: "",
                    achievement: "Huy chương Bạc Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM ANH THÁI",
                    class: "",
                    achievement: "Huy chương Bạc Violympic Toán TV cấp Tỉnh, Giải Nhất Văn hoá đọc cấp Tỉnh, Khuyến khích Văn hoá đọc Quốc gia",
                    teacher: "",
                    score: ""
                },
                {
                    name: "HỒ THỊ THANH MỸ",
                    class: "",
                    achievement: "Huy chương Bạc Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN HỒNG LÂM",
                    class: "",
                    achievement: "Huy chương Vàng Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN LÊ MINH ĐỨC",
                    class: "",
                    achievement: "Huy chương Vàng Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRẦN NGUYỄN MINH NHẬT",
                    class: "",
                    achievement: "Huy chương Vàng Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "MAI BÁ TÙNG DƯƠNG",
                    class: "",
                    achievement: "Huy chương Vàng Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN VĂN THÀNH TIẾN",
                    class: "",
                    achievement: "Huy chương Vàng Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRẦN NGUYỄN LINH NHƯ",
                    class: "",
                    achievement: "Huy chương Vàng Violympic Vật lí cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "ĐỖ HOÀNG DUY KHOA",
                    class: "",
                    achievement: "Huy chương Bạc Violympic Vật lí cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN ĐỨC GIA BẢO",
                    class: "",
                    achievement: "Huy chương Bạc Violympic Vật lí cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM ANH THƯ",
                    class: "",
                    achievement: "Huy chương Bạc Violympic Vật lí cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN PHƯƠNG UYÊN",
                    class: "",
                    achievement: "Giải Nhất Văn hoá đọc cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN BÙI HÀ DƯƠNG",
                    class: "",
                    achievement: "Giải Nhì KHKT cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "VÕ DƯƠNG HÀ MY",
                    class: "",
                    achievement: "Giải Nhì KHKT cấp Tỉnh",
                    teacher: "",
                    score: ""
                }
            ],
            
            "2022-2023": 
            [
                {
                    name: "NGUYỄN BÙI KHÔI NGUYÊN",
                    class: "",
                    achievement: "Huy chương Bạc Violympic Toán TV cấp Tỉnh, Huy chương Đồng Violympic Toán TV Quốc gia",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM GIA VĨNH TƯỜNG",
                    class: "",
                    achievement: "Huy chương Vàng Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN NGỌC GIA NHI",
                    class: "",
                    achievement: "Huy chương Vàng Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN MINH DƯƠNG",
                    class: "",
                    achievement: "Huy chương Bạc Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LÊ ĐỨC MINH NHẬT",
                    class: "",
                    achievement: "Huy chương Bạc Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "BÙI NGỌC ANH THƯ",
                    class: "",
                    achievement: "Huy chương Bạc Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "CAO BẢO TRÂM",
                    class: "",
                    achievement: "Huy chương Bạc Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM THỊ KHÁNH LY",
                    class: "",
                    achievement: "Huy chương Đồng Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "CAO TUYẾT TRINH",
                    class: "",
                    achievement: "Huy chương Đồng Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN LÊ MINH ĐỨC",
                    class: "",
                    achievement: "Huy chương Bạc Violympic Toán TV cấp Tỉnh, Huy chương Bạc Violympic Toán TV Quốc gia",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN TRUNG PHONG",
                    class: "",
                    achievement: "Huy chương Đồng Violympic Toán TV cấp Tỉnh, Huy chương Đồng Violympic Toán TV Quốc gia",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN HỒNG LÂM",
                    class: "",
                    achievement: "Huy chương Bạc Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM GIA QUỲNH HƯƠNG",
                    class: "",
                    achievement: "Huy chương Bạc Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRẦN NGUYỄN LINH NHƯ",
                    class: "",
                    achievement: "Huy chương Bạc Violympic Toán TV cấp Tỉnh, Khuyến khích Văn hóa đọc Quốc gia",
                    teacher: "",
                    score: ""
                },
                {
                    name: "HÀ PHÚ ĐỨC",
                    class: "",
                    achievement: "Huy chương Bạc Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "ĐẶNG NGỌC BÌNH AN",
                    class: "",
                    achievement: "Huy chương Đồng Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN NGỌC BẢO CHÂU",
                    class: "",
                    achievement: "Huy chương Đồng Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRẦN VĂN KHANG",
                    class: "",
                    achievement: "Huy chương Đồng Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM ANH THƯ",
                    class: "",
                    achievement: "Huy chương Vàng Violympic Toán TV cấp Tỉnh, Huy chương Bạc Violympic Vật lý cấp Tỉnh, Khuyến khích Violympic Toán TV Quốc gia",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM NGUYỄN TUẤN MINH",
                    class: "",
                    achievement: "Huy chương Bạc Violympic Toán TV cấp Tỉnh, Huy chương Bạc Violympic Vật lý cấp Tỉnh, Giải Nhất STEM cấp Tỉnh, Khuyến khích Violympic Toán TV Quốc gia",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN ĐỨC GIA BẢO",
                    class: "",
                    achievement: "Huy chương Bạc Violympic Toán TV cấp Tỉnh, Giải Nhì STEM cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "ĐỖ HOÀNG DUY KHOA",
                    class: "",
                    achievement: "Huy chương Bạc Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "BÙI NHẬT LÂM",
                    class: "",
                    achievement: "Huy chương Bạc Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN THIỆN NHÂN",
                    class: "",
                    achievement: "Huy chương Bạc Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN PHƯƠNG UYÊN",
                    class: "",
                    achievement: "Huy chương Đồng Violympic Toán TV cấp Tỉnh, Giải Nhì STEM cấp Tỉnh, Giải Nhất Văn hóa đọc cấp Tỉnh, Khuyến khích Văn hóa đọc Quốc gia, Cây bút triển vọng UPU Quốc tế lần thứ 52",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN HOÀNG VŨ",
                    class: "",
                    achievement: "Huy chương Đồng Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "HỒ THỊ THANH MỸ",
                    class: "",
                    achievement: "Huy chương Bạc Violympic Toán TV cấp Tỉnh, Huy chương Bạc Violympic Toán TV Quốc gia",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN THUỲ DUNG",
                    class: "",
                    achievement: "Huy chương Bạc Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "MAI BÁ TÙNG DƯƠNG",
                    class: "",
                    achievement: "Huy chương Đồng Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRỊNH GIA HÂN",
                    class: "",
                    achievement: "Huy chương Đồng Violympic Toán TV cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGÔ NGỌC THẢO VIÊN",
                    class: "",
                    achievement: "Khuyến khích Violympic Toán TV Quốc gia",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN KHỞI NGUYÊN",
                    class: "",
                    achievement: "Khuyến khích Violympic Toán TV Quốc gia",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN THÀNH GIA BẢO",
                    class: "",
                    achievement: "Huy chương Bạc Violympic Vật lý cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN LƯƠNG CHÂU LONG",
                    class: "",
                    achievement: "Giải Nhì IOE cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN HÀ NGÂN",
                    class: "",
                    achievement: "Giải Ba IOE cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM NGUYỄN HÀ NGÂN",
                    class: "",
                    achievement: "Giải Ba IOE cấp Tỉnh, Giải Nhất HSG cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "MAI ĐỨC HƯNG",
                    class: "",
                    achievement: "Giải Ba IOE cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM THỊ NHƯ QUỲNH",
                    class: "",
                    achievement: "Giải Nhất HSG cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN BÙI HÀ DƯƠNG",
                    class: "",
                    achievement: "Giải Nhì KHKT cấp Tỉnh, Giải Nhì STEM cấp Tỉnh, Công nhận Quốc gia STEM",
                    teacher: "",
                    score: ""
                },
                {
                    name: "ĐỖ THÀNH THÁI",
                    class: "",
                    achievement: "Giải Nhì KHKT cấp Tỉnh, Giải Nhì STEM cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN VĂN THÀNH TIẾN",
                    class: "",
                    achievement: "Giải Nhất STEM cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN HỮU TẤT ANH",
                    class: "",
                    achievement: "Giải Nhất STEM cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "MAI NGUYỄN BẢO AN",
                    class: "",
                    achievement: "Giải Nhất STEM cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRẦN QUỐC HÙNG",
                    class: "",
                    achievement: "Giải Nhất STEM cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LÊ TIẾN ĐẠT",
                    class: "",
                    achievement: "Giải Nhì STEM cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN THU GIANG",
                    class: "",
                    achievement: "Giải Nhì STEM cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN NGỌC NHƯ Ý",
                    class: "",
                    achievement: "Giải Nhì Viết về thầy cô và mái trường cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN VÕ NGỌC HÀ",
                    class: "",
                    achievement: "Giải Nhì Văn hóa đọc cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "VÕ LÂM ĐOAN PHƯỢNG",
                    class: "",
                    achievement: "Giải Ba Văn hóa đọc Quốc gia",
                    teacher: "",
                    score: ""
                }
            ],
            
            "2023-2024": 
            [
                {
                    name: "DƯƠNG KHẮC VIỆT ANH",
                    class: "",
                    achievement: "Vàng Violympic Toán cấp Tỉnh, Đồng Vioedu cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN NGỌC BẢO ANH",
                    class: "",
                    achievement: "Đồng Violympic Toán cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM TRÍ DŨNG",
                    class: "9D",
                    achievement: "Bạc Violympic Toán cấp Tỉnh, Bạc Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LÊ NGUYỄN GIA HÂN",
                    class: "6A",
                    achievement: "Vàng Violympic Toán cấp Tỉnh, Đồng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "ĐỖ GIA HÂN",
                    class: "",
                    achievement: "Vàng Violympic Toán cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM NGUYỄN GIA HUY",
                    class: "6A",
                    achievement: "Vàng Violympic Toán cấp Tỉnh, Bạc Vioedu cấp Tỉnh, Bạc Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN NHẬT HUY",
                    class: "",
                    achievement: "Vàng Violympic Toán cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM MINH NGỌC",
                    class: "6A",
                    achievement: "Vàng Violympic Toán cấp Tỉnh, Vàng Vioedu cấp Tỉnh, Bạc Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN ĐÌNH MINH NHẬT",
                    class: "",
                    achievement: "Vàng Violympic Toán cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN PHƯƠNG NHI",
                    class: "",
                    achievement: "Vàng Violympic Toán cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN PHÚ QUÝ",
                    class: "6A",
                    achievement: "KK Quốc gia Violympic Toán, Đồng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LÊ NGUYỄN BẢO QUYÊN",
                    class: "",
                    achievement: "Bạc Violympic Toán cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN TRỌNG SINH",
                    class: "",
                    achievement: "Vàng Violympic Toán cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN CẨM TÚ",
                    class: "",
                    achievement: "Đồng Violympic Toán cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "ĐỖ PHAN KHÁNH THI",
                    class: "",
                    achievement: "Bạc Violympic Toán cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM GIA VĨNH TƯỜNG",
                    class: "",
                    achievement: "KK Quốc gia Violympic Toán",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN LÊ MINH ĐỨC",
                    class: "",
                    achievement: "Đồng Quốc gia Violympic Toán, Bạc Vioedu cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN NỮ KHÁNH TRANG",
                    class: "",
                    achievement: "KK Quốc gia Violympic Toán",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN NGỌC BẢO CHÂU",
                    class: "8A",
                    achievement: "KK Quốc gia Violympic Toán, Đồng Vioedu cấp Tỉnh, Bạc Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM GIA QUỲNH HƯƠNG",
                    class: "8A",
                    achievement: "Vàng Violympic Toán cấp Tỉnh, Đồng Vioedu cấp Tỉnh, Vàng Violympic KHTN cấp Tỉnh, Hoàn thành tốt IOE Quốc gia",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN HỒNG LÂM",
                    class: "8A",
                    achievement: "Đồng Violympic Toán cấp Tỉnh, Bóng đá cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM NHẬT MINH",
                    class: "8A",
                    achievement: "Bạc Violympic Toán cấp Tỉnh, Hoàn thành tốt IOE Quốc gia",
                    teacher: "",
                    score: ""
                },
                {
                    name: "HOÀNG MINH HIẾU",
                    class: "",
                    achievement: "Đồng Violympic Toán cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "ĐOÀN KHÁNH NHI",
                    class: "8A",
                    achievement: "Đồng Violympic Toán cấp Tỉnh, Bạc Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "HÀ PHÚ ĐỨC",
                    class: "8A",
                    achievement: "Bạc Violympic Toán cấp Tỉnh, Bạc Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN TRUNG PHONG",
                    class: "8A",
                    achievement: "Đồng Violympic Toán cấp Tỉnh, Đồng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM THÁI MINH PHÚC",
                    class: "8A",
                    achievement: "Bạc Violympic Toán cấp Tỉnh, Nhất IOE cấp Tỉnh, Bạc Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRẦN VĂN HOÀNG",
                    class: "8A",
                    achievement: "Đồng Violympic Toán cấp Tỉnh, Bóng bàn cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRẦN VĂN KHANG",
                    class: "8A",
                    achievement: "Đồng Violympic Toán cấp Tỉnh, Bóng bàn cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "HỒ VIẾT XUÂN",
                    class: "8A",
                    achievement: "Đồng Violympic Toán cấp Tỉnh, Bạc Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN THIỆN NHÂN",
                    class: "9D",
                    achievement: "Bạc Quốc gia Violympic Toán, KK Quốc gia Violympic KHTN",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM NGUYỄN TUẤN MINH",
                    class: "9D",
                    achievement: "Vàng Violympic Toán cấp Tỉnh, Vàng Vioedu cấp Tỉnh, KK Quốc gia Violympic KHTN",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN THẢO NGUYÊN",
                    class: "9D",
                    achievement: "Vàng Violympic Toán cấp Tỉnh, Nhất IOE cấp Tỉnh, Khuyến khích Tiếng Anh cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRỊNH CÔNG ĐỨC",
                    class: "",
                    achievement: "Đồng Quốc gia Violympic Toán",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM ANH THƯ",
                    class: "9D",
                    achievement: "Đồng Quốc gia Violympic Toán, Đồng Quốc gia Violympic KHTN",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRẦN MẠNH HÙNG",
                    class: "9D",
                    achievement: "Vàng Violympic Toán cấp Tỉnh, Hoàn thành tốt IOE Quốc gia",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRẦN MẠNH DŨNG",
                    class: "",
                    achievement: "KK Quốc gia Violympic Toán",
                    teacher: "",
                    score: ""
                },
                {
                    name: "ĐẶNG DUY BẢO",
                    class: "",
                    achievement: "KK Quốc gia Violympic Toán",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM LÊ ANH THƯ",
                    class: "",
                    achievement: "Vàng Violympic Toán cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "BÙI NHẬT LÂM",
                    class: "",
                    achievement: "Bạc Violympic Toán cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "HỒ NGỌC TƯỜNG NHI",
                    class: "9D",
                    achievement: "Đồng Violympic Toán cấp Tỉnh, KK Quốc gia Violympic KHTN",
                    teacher: "",
                    score: ""
                },
                {
                    name: "ĐỖ HOÀNG DUY KHOA",
                    class: "9D",
                    achievement: "Vàng Violympic Toán cấp Tỉnh, Đồng Vioedu cấp Tỉnh, KK Quốc gia Violympic KHTN, Nhất Toán cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LƯU GIA BẢO",
                    class: "9D",
                    achievement: "Vàng Violympic Toán cấp Tỉnh, Bóng đá cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN PHƯƠNG UYÊN",
                    class: "9D",
                    achievement: "Bạc Violympic Toán cấp Tỉnh, Đồng Quốc gia Violympic KHTN, Cây bút triển vọng Viết thư UPU",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRẦN NGUYỄN MINH NHẬT",
                    class: "",
                    achievement: "KK Quốc gia Violympic Toán",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN BÙI ĐÔNG PHƯƠNG",
                    class: "9C",
                    achievement: "KK Quốc gia IOE",
                    teacher: "",
                    score: ""
                },
                {
                    name: "HÀ CHÂU NGỌC PHƯƠNG",
                    class: "6A",
                    achievement: "Nhì IOE cấp Tỉnh, Bạc Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRẦN NGUYỄN LINH NHƯ",
                    class: "8A",
                    achievement: "Hoàn thành tốt IOE Quốc gia, Bạc Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LÊ HOÀNG TUẤN",
                    class: "8A",
                    achievement: "Nhì IOE cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN HÀ NGÂN",
                    class: "9D",
                    achievement: "Hoàn thành tốt IOE Quốc gia, Khuyến khích Tiếng Anh cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "VÕ NGỌC TRÂM ANH",
                    class: "9D",
                    achievement: "Hoàn thành tốt IOE Quốc gia",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN ÁNH CẦM",
                    class: "9D",
                    achievement: "Hoàn thành tốt IOE Quốc gia",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN ĐỨC GIA BẢO",
                    class: "9D",
                    achievement: "KK Quốc gia Violympic KHTN",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRỊNH NHẬT MINH",
                    class: "6A",
                    achievement: "Đồng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LÊ NGỌC ĐÔNG NHI",
                    class: "6A",
                    achievement: "Bạc Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRƯƠNG BÙI HOÀNG NHI",
                    class: "6A",
                    achievement: "Bạc Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "DƯƠNG HOÀNG MINH PHÚC",
                    class: "6A",
                    achievement: "Bạc Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN BÙI MINH TUẤN",
                    class: "6A",
                    achievement: "Bạc Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN NGỌC ANH",
                    class: "6B",
                    achievement: "Bạc Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN NGỌC GIA NHI",
                    class: "7A",
                    achievement: "Vàng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN TRẦN ĐÌNH QUÂN",
                    class: "8A",
                    achievement: "Đồng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM VIẾT BẢO LONG",
                    class: "8A",
                    achievement: "Bạc Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN NGỌC HỒNG ÂN",
                    class: "8A",
                    achievement: "Đồng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRẦN VÕ LÊ DŨNG",
                    class: "8A",
                    achievement: "Vàng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN BẢO TRUNG",
                    class: "6A",
                    achievement: "Cờ vua cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "VŨ KHẮC ĐẠT",
                    class: "9C",
                    achievement: "Bóng đá cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "BÙI THÀNH ĐẠT",
                    class: "9C",
                    achievement: "Bóng đá cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN TẤN HOÁ",
                    class: "9C",
                    achievement: "Bóng đá cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "HOÀNG GIA HƯNG",
                    class: "9C",
                    achievement: "Bóng đá cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN TRỌNG AN",
                    class: "9D",
                    achievement: "Bóng đá cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN TRẦN MINH PHÚC",
                    class: "9D",
                    achievement: "Bóng đá cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "CAO DUY QUÝ",
                    class: "9A",
                    achievement: "Bóng đá cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "MAI NGUYỄN BẢO AN",
                    class: "9D",
                    achievement: "Bóng đá cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN HOÀNG VŨ",
                    class: "",
                    achievement: "Nhất Hóa học cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN NHẬT AN",
                    class: "",
                    achievement: "Ba GDCD cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM PHƯƠNG VY",
                    class: "",
                    achievement: "Ba GDCD cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "VŨ PHAN ĐỨC BẢO",
                    class: "",
                    achievement: "Khuyến khích Tin học cấp Tỉnh",
                    teacher: "",
                    score: ""
                }
            ],
            
            "2024-2025": 
            [
                {
                    name: "CHU TUẤN HẢI",
                    class: "7B",
                    achievement: "Vàng Violympic Toán cấp Tỉnh, Bạc Vioedu cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM TRÍ DŨNG",
                    class: "7A",
                    achievement: "Vàng Violympic Toán cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN LÊ MINH ĐỨC",
                    class: "9A",
                    achievement: "Vàng Violympic Toán cấp Tỉnh, Đồng Violympic KHTN cấp Tỉnh, Ba Toán cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRẦN VĂN KHANG",
                    class: "9A",
                    achievement: "Vàng Violympic Toán cấp Tỉnh, Đồng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN NGỌC HỒNG ÂN",
                    class: "9A",
                    achievement: "Vàng Violympic Toán cấp Tỉnh, Vàng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM GIA VĨNH TƯỜNG",
                    class: "8A",
                    achievement: "Vàng Toán Tiếng Anh cấp Tỉnh, Đồng Violympic Toán cấp Tỉnh, Vàng Violympic KHTN cấp Tỉnh, Ba IOE cấp Tỉnh, Nhất Văn hóa đọc cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN BÙI KHÔI NGUYÊN",
                    class: "8A",
                    achievement: "Vàng Toán Tiếng Anh cấp Tỉnh, Ba Sản phẩm STEM cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN VIỆT KHANG",
                    class: "9A",
                    achievement: "Vàng Violympic Toán cấp Tỉnh, Bạc Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "BÙI KHẢ MY",
                    class: "6A",
                    achievement: "Bạc Violympic Toán cấp Tỉnh, Bạc Toán Tiếng Anh cấp Tỉnh, Bạc Violympic KHTN cấp Tỉnh, Ba IOE cấp Tỉnh, Đồng Vioedu cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LÊ NGỌC ĐÔNG NHI",
                    class: "7A",
                    achievement: "Bạc Violympic Toán cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM VIẾT BẢO LONG",
                    class: "9A",
                    achievement: "Bạc Violympic Toán cấp Tỉnh, Vàng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "CAO THỊ TUYẾT CHÂU",
                    class: "9A",
                    achievement: "Bạc Violympic Toán cấp Tỉnh, Đồng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN HỒNG LÂM",
                    class: "9A",
                    achievement: "Bạc Violympic Toán cấp Tỉnh, Vàng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM THÁI MINH PHÚC",
                    class: "9A",
                    achievement: "Bạc Violympic Toán cấp Tỉnh, Nhì IOE cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM MINH NGỌC",
                    class: "7A",
                    achievement: "Đồng Violympic Toán cấp Tỉnh, Ba IOE cấp Tỉnh, Đồng Vioedu cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN LÊ NHƯ Ý",
                    class: "6A",
                    achievement: "Vàng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "ĐỖ TRẦN THẢO NHI",
                    class: "6A",
                    achievement: "Vàng Violympic KHTN cấp Tỉnh, Đồng Vioedu cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "HOÀNG LÂM",
                    class: "7A",
                    achievement: "Vàng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN BÙI MINH TUẤN",
                    class: "7A",
                    achievement: "Vàng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "HOÀNG NHẬT VŨ",
                    class: "9A",
                    achievement: "Vàng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN NỮ KHÁNH TRANG",
                    class: "9A",
                    achievement: "Vàng Violympic KHTN cấp Tỉnh, Ba Lịch sử cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRẦN VĂN HOÀNG",
                    class: "9A",
                    achievement: "Vàng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHAN NGUYỄN NHÃ UYÊN",
                    class: "6A",
                    achievement: "Bạc Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN YẾN NHI",
                    class: "6A",
                    achievement: "Bạc Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "HUỲNH NGUYÊN PHÚC",
                    class: "7A",
                    achievement: "Bạc Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN NHẬT HUY",
                    class: "7A",
                    achievement: "Bạc Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM NGUYỄN GIA HUY",
                    class: "7A",
                    achievement: "Bạc Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LÊ NGUYỄN GIA HÂN",
                    class: "7A",
                    achievement: "Bạc Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN CẨM TÚ",
                    class: "7A",
                    achievement: "Bạc Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN TRÍ DŨNG",
                    class: "7A",
                    achievement: "Bạc Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN MINH DƯƠNG",
                    class: "8A",
                    achievement: "Bạc Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRẦN VÕ LÊ DŨNG",
                    class: "9A",
                    achievement: "Bạc Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "ĐỖ CHUỲ CHI",
                    class: "9A",
                    achievement: "Bạc Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "HỒ BÙI QUANG VINH",
                    class: "9A",
                    achievement: "Bạc Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM NHẬT MINH",
                    class: "9A",
                    achievement: "Bạc Violympic KHTN cấp Tỉnh, Nhì IOE cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM GIA QUỲNH HƯƠNG",
                    class: "9A",
                    achievement: "Bạc Violympic KHTN cấp Tỉnh, Nhì IOE cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "ĐOÀN KHÁNH NHI",
                    class: "9A",
                    achievement: "Bạc Violympic KHTN cấp Tỉnh, Ba GDCD cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN TRẦN ĐÌNH QUÂN",
                    class: "9A",
                    achievement: "Bạc Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN HOÀNG NGỌC ÁNH",
                    class: "6B",
                    achievement: "Đồng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHẠM NGUYỄN HIỀN NHI",
                    class: "6A",
                    achievement: "Đồng Violympic KHTN cấp Tỉnh, Nhất Sản phẩm STEM cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "ĐÀO NGUYỄN ĐĂNG KHOA",
                    class: "6A",
                    achievement: "Đồng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "ĐẶNG BẢO TRÂM",
                    class: "6A",
                    achievement: "Đồng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "VÕ NGỌC VŨ",
                    class: "6A",
                    achievement: "Đồng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN VŨ LÂM LY",
                    class: "6A",
                    achievement: "Đồng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN TRỌNG SINH",
                    class: "7A",
                    achievement: "Đồng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "PHAN NGUYỄN BẢO HÂN",
                    class: "7A",
                    achievement: "Đồng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "HOÀNG NGÂN HÀ",
                    class: "7A",
                    achievement: "Đồng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "DƯƠNG KHẮC VIỆT ANH",
                    class: "7A",
                    achievement: "Đồng Violympic KHTN cấp Tỉnh, Đồng Vioedu cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "ĐẶNG THỊ THANH HUYỀN",
                    class: "8A",
                    achievement: "Đồng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "CAO BẢO TRÂM",
                    class: "8A",
                    achievement: "Đồng Violympic KHTN cấp Tỉnh, Ba IOE cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "ĐỖ TRẦN ĐĂNG KHOA",
                    class: "8B",
                    achievement: "Đồng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "HÀ PHÚ ĐỨC",
                    class: "9A",
                    achievement: "Đồng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGÔ NGỌC THẢO VIÊN",
                    class: "9A",
                    achievement: "Đồng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN NGỌC BẢO CHÂU",
                    class: "9A",
                    achievement: "Đồng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LÊ HOÀNG TUẤN",
                    class: "9A",
                    achievement: "Đồng Violympic KHTN cấp Tỉnh, Ba IOE cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LÊ PHẠM NGUYÊN PHÚC",
                    class: "9A",
                    achievement: "Đồng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "ĐẶNG NGỌC BÌNH AN",
                    class: "9A",
                    achievement: "Đồng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LÊ NGUYỄN MINH THƯ",
                    class: "9A",
                    achievement: "Đồng Violympic KHTN cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "HÀ CHÂU NGỌC PHƯƠNG",
                    class: "7A",
                    achievement: "Nhì IOE cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN NGỌC GIA NHI",
                    class: "8A",
                    achievement: "Nhì IOE cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "VÕ PHẠM KHÁNH THY",
                    class: "8A",
                    achievement: "Ba IOE cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "LÊ BẢO NGỌC",
                    class: "8A",
                    achievement: "Vàng Violympic KHTN cấp Quốc gia",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRẦN NGUYỄN LINH NHƯ",
                    class: "9A",
                    achievement: "Nhì Ngữ văn cấp Tỉnh, Ba Văn hóa đọc cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "ĐÀO DIỆU CHI",
                    class: "9C",
                    achievement: "Ba Lịch sử cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRẦN THÀNH ĐẠT",
                    class: "6A",
                    achievement: "Ba Sản phẩm STEM cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN VÕ NGỌC HÀ",
                    class: "9A",
                    achievement: "Nhất Sản phẩm STEM cấp Huyện, Khuyến khích Văn hóa đọc cấp Tỉnh",
                    teacher: "",
                    score: ""
                },
                {
                    name: "TRƯƠNG CÔNG HOÀNG LONG",
                    class: "6A",
                    achievement: "Nhất Sản phẩm STEM cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "ĐỖ CHÙY CHI",
                    class: "6A",
                    achievement: "Nhất Sản phẩm STEM cấp Huyện",
                    teacher: "",
                    score: ""
                },
                {
                    name: "NGUYỄN THỊ HỒNG PHÚC",
                    class: "8A",
                    achievement: "Khuyến khích Văn hóa đọc cấp Tỉnh",
                    teacher: "",
                    score: ""
                }
            ],
            
            // ===== 2025-2030 (Dự kiến) =====
            "2025-2026": [
                {
                    name: "Học sinh 1",
                    class: "10A",
                    achievement: "Thành tích xuất sắc trong học tập",
                    teacher: "",
                    score: ""
                },
                {
                    name: "Học sinh 2",
                    class: "10B",
                    achievement: "Giải Nhất Olympic Toán",
                    teacher: "",
                    score: ""
                },
                {
                    name: "Học sinh 3",
                    class: "10C",
                    achievement: "Giải Nhất Olympic Vật Lý",
                    teacher: "",
                    score: ""
                },
                {
                    name: "Học sinh 4",
                    class: "10D",
                    achievement: "Giải Nhất Olympic Hóa Học",
                    teacher: "",
                    score: ""
                },
                {
                    name: "Học sinh 5",
                    class: "10A",
                    achievement: "Giải Nhất Olympic Tiếng Anh",
                    teacher: "",
                    score: ""
                }
            ]
        };

        // ===== DỮ LIỆU THẠC SĨ, TIẾN SĨ =====
        const graduatesData = [
            {
                name: "NGUYỄN VĂN A",
                degree: "Tiến sĩ",
                major: "Khoa học Máy tính",
                workplace: "Đại học Quốc gia Hà Nội",
                achievement: "Nghiên cứu về Trí tuệ Nhân tạo",
                year: 2010,
                icon: "fas fa-user-graduate"
            },
            {
                name: "TRẦN THỊ B",
                degree: "Thạc sĩ", 
                major: "Quản trị Kinh doanh",
                workplace: "Tập đoàn FPT",
                achievement: "Quản lý dự án phần mềm",
                year: 2012,
                icon: "fas fa-briefcase"
            },
            {
                name: "LÊ VĂN C",
                degree: "Tiến sĩ",
                major: "Y học",
                workplace: "Bệnh viện Bạch Mai",
                achievement: "Nghiên cứu điều trị ung thư",
                year: 2015,
                icon: "fas fa-user-md"
            },
            {
                name: "PHẠM THỊ D",
                degree: "Thạc sĩ",
                major: "Luật học",
                workplace: "Văn phòng Luật sư Dragon",
                achievement: "Chuyên gia luật quốc tế",
                year: 2013,
                icon: "fas fa-balance-scale"
            },
            {
                name: "HOÀNG VĂN E",
                degree: "Tiến sĩ",
                major: "Vật lý học",
                workplace: "Viện Hàn lâm Khoa học",
                achievement: "Nghiên cứu vật liệu mới",
                year: 2018,
                icon: "fas fa-atom"
            },
            {
                name: "VŨ THỊ F",
                degree: "Thạc sĩ",
                major: "Ngôn ngữ học",
                workplace: "Đại học Sư phạm Hà Nội",
                achievement: "Giáo viên xuất sắc",
                year: 2016,
                icon: "fas fa-chalkboard-teacher"
            }
        ];

        // Tạo hiệu ứng hạt ánh sáng
        function createParticles() {
            const particlesContainer = document.getElementById('particles');
            for (let i = 0; i < 50; i++) {
                const particle = document.createElement('div');
                particle.classList.add('particle');
                
                const size = Math.random() * 10 + 5;
                const left = Math.random() * 100;
                const animationDuration = Math.random() * 20 + 10;
                const animationDelay = Math.random() * 20;
                
                particle.style.width = `${size}px`;
                particle.style.height = `${size}px`;
                particle.style.left = `${left}%`;
                particle.style.animationDuration = `${animationDuration}s`;
                particle.style.animationDelay = `-${animationDelay}s`;
                
                particlesContainer.appendChild(particle);
            }
        }
        
        // Tạo hiệu ứng cho các phần tử trôi nổi
        function createFloatingElements() {
            const container = document.querySelector('.floating-elements');
            for (let i = 0; i < 15; i++) {
                const element = document.createElement('div');
                element.className = 'floating-element';
                const size = Math.random() * 80 + 40;
                const left = Math.random() * 100;
                const delay = Math.random() * 20;
                const duration = Math.random() * 20 + 20;
                
                element.style.width = `${size}px`;
                element.style.height = `${size}px`;
                element.style.top = `${Math.random() * 100}%`;
                element.style.left = `${left}%`;
                element.style.animationDelay = `-${delay}s`;
                element.style.animationDuration = `${duration}s`;
                
                container.appendChild(element);
            }
        }
        
        // Hiệu ứng loading
        function showLoading() {
            document.getElementById('loadingSpinner').style.display = 'block';
            setTimeout(() => {
                document.getElementById('loadingSpinner').style.display = 'none';
            }, 800);
        }
        
        // Hiệu ứng cho năm (cả nút nhỏ và nút lớn)
        document.querySelectorAll('.large-year').forEach(year => {
            year.addEventListener('click', function() {
                showLoading();
                setTimeout(() => {
                    const yearPeriod = this.getAttribute('data-year');
                    showYearButtons(yearPeriod);
                }, 500);
            });
        });
        
        // Xử lý nút Thạc sĩ, Tiến sĩ
        document.getElementById('mastersPhdButton').addEventListener('click', function() {
            showLoading();
            setTimeout(() => {
                showMastersPhdPage();
            }, 500);
        });
        
        // Hàm hiển thị các nút năm học
        function showYearButtons(yearPeriod) {
            // Ẩn nội dung chính
            document.getElementById('mainPage').style.display = 'none';
            
            // Hiển thị container các nút năm học
            const yearButtonsContainer = document.getElementById('yearButtonsContainer');
            yearButtonsContainer.style.display = 'flex';
            
            // Cập nhật tiêu đề
            document.getElementById('yearButtonsTitle').textContent = `Học sinh xuất sắc giai đoạn ${yearPeriod}`;
            
            // Tạo các nút năm học
            const yearButtons = document.getElementById('yearButtons');
            yearButtons.innerHTML = ''; // Xóa nội dung cũ
            
            // Lấy năm học bắt đầu và kết thúc từ yearPeriod (vd: "2005-2010")
            const [startYear, endYear] = yearPeriod.split('-').map(Number);
            
            // Tạo nút cho từng năm học trong giai đoạn
            for (let year = startYear; year <= endYear; year++) {
                const nextYear = year + 1;
                const yearButton = document.createElement('div');
                yearButton.className = 'year-button enhanced-card magic-button';
                yearButton.textContent = `Năm học ${year}-${nextYear}`;
                yearButton.addEventListener('click', function() {
                    showLoading();
                    setTimeout(() => {
                        showStudentPage(`${year}-${nextYear}`);
                    }, 500);
                });
                yearButtons.appendChild(yearButton);
            }
        }
        
        // Hàm hiển thị trang vinh danh học sinh
        function showStudentPage(year) {
            // Ẩn tất cả các phần khác
            document.getElementById('mainPage').style.display = 'none';
            document.getElementById('yearButtonsContainer').style.display = 'none';
            document.getElementById('mastersPhdPage').style.display = 'none';
            
            // Hiển thị trang học sinh
            const studentPage = document.getElementById('studentPage');
            studentPage.style.display = 'block';
            
            // Cập nhật tiêu đề
            document.getElementById('studentPageTitle').textContent = `VINH DANH HỌC SINH XUẤT SẮC NĂM HỌC ${year}`;
            
            // Tạo danh sách học sinh
            const studentsList = document.getElementById('studentsList');
            studentsList.innerHTML = ''; // Xóa nội dung cũ
            
            // Kiểm tra xem có dữ liệu cho năm này không
            if (studentsData[year]) {
                // Tạo card cho từng học sinh
                studentsData[year].forEach((student, index) => {
                    const studentCard = document.createElement('div');
                    studentCard.className = 'student-card enhanced-card';
                    studentCard.innerHTML = `
                        <div class="student-icon"><i class="fas fa-star"></i></div>
                        <img src="https://via.placeholder.com/160x160/3a6dc9/FFFFFF?text=${student.name.split(' ').pop()}" alt="${student.name}" class="student-image image-3d">
                        <h3>${student.name}</h3>
                        <p>Lớp: ${student.class}</p>
                        <p>Thành tích: ${student.achievement}</p>
                        ${student.score ? `<p>Điểm: ${student.score}</p>` : ''}
                        ${student.teacher ? `<p>GV: ${student.teacher}</p>` : ''}
                    `;
                    
                    // Thêm sự kiện click để hiển thị modal
                    studentCard.addEventListener('click', function() {
                        showDetailModal(student, year, 'student');
                    });
                    
                    studentsList.appendChild(studentCard);
                });
            } else {
                // Nếu không có dữ liệu cho năm này
                studentsList.innerHTML = '<p style="grid-column: 1/-1; font-size: 2rem; color: #e0e0ff;">Chưa có dữ liệu cho năm học này</p>';
            }
        }
        
        // Hàm hiển thị trang Thạc sĩ, Tiến sĩ
        function showMastersPhdPage() {
            // Ẩn tất cả các phần khác
            document.getElementById('mainPage').style.display = 'none';
            document.getElementById('yearButtonsContainer').style.display = 'none';
            document.getElementById('studentPage').style.display = 'none';
            
            // Hiển thị trang Thạc sĩ, Tiến sĩ
            const mastersPhdPage = document.getElementById('mastersPhdPage');
            mastersPhdPage.style.display = 'block';
            
            // Tạo danh sách cựu học sinh
            const graduatesList = document.getElementById('graduatesList');
            graduatesList.innerHTML = ''; // Xóa nội dung cũ
            
            // Tạo card cho từng cựu học sinh
            graduatesData.forEach((graduate, index) => {
                const graduateCard = document.createElement('div');
                graduateCard.className = 'graduate-card enhanced-card';
                graduateCard.innerHTML = `
                    <div class="graduate-icon"><i class="${graduate.icon}"></i></div>
                    <img src="https://via.placeholder.com/180x180/FF8C42/FFFFFF?text=${graduate.name.split(' ').pop()}" alt="${graduate.name}" class="graduate-image image-3d">
                    <div class="degree-badge">${graduate.degree}</div>
                    <h3>${graduate.name}</h3>
                    <p>Chuyên ngành: ${graduate.major}</p>
                    <p>Nơi công tác: ${graduate.workplace}</p>
                    <p>Tốt nghiệp: ${graduate.year}</p>
                `;
                
                // Thêm sự kiện click để hiển thị modal
                graduateCard.addEventListener('click', function() {
                    showDetailModal(graduate, '', 'graduate');
                });
                
                graduatesList.appendChild(graduateCard);
            });
        }
        
        // Hàm hiển thị modal thông tin chi tiết
        function showDetailModal(data, year, type) {
            const modal = document.getElementById('detailModal');
            const personName = document.getElementById('modalPersonName');
            const personImage = document.getElementById('modalPersonImage');
            const personInfo = document.getElementById('modalPersonInfo');
            
            if (type === 'student') {
                // Hiển thị thông tin học sinh
                const student = data;
                personName.textContent = student.name;
                personImage.src = `https://via.placeholder.com/220x220/3a6dc9/FFFFFF?text=${student.name.split(' ').pop()}`;
                personImage.alt = student.name;
                
                personInfo.innerHTML = `
                    <p><strong>Năm học:</strong> ${year}</p>
                    <p><strong>Lớp:</strong> ${student.class}</p>
                    <p><strong>Thành tích:</strong> ${student.achievement}</p>
                    ${student.score ? `<p><strong>Điểm:</strong> ${student.score}</p>` : ''}
                    ${student.teacher ? `<p><strong>Giáo viên hướng dẫn:</strong> ${student.teacher}</p>` : ''}
                    <p><strong>Ghi chú:</strong> Học sinh xuất sắc của trường</p>
                `;
            } else {
                // Hiển thị thông tin cựu học sinh
                const graduate = data;
                personName.textContent = graduate.name;
                personImage.src = `https://via.placeholder.com/220x220/FF8C42/FFFFFF?text=${graduate.name.split(' ').pop()}`;
                personImage.alt = graduate.name;
                
                personInfo.innerHTML = `
                    <p><strong>Học vị:</strong> ${graduate.degree}</p>
                    <p><strong>Chuyên ngành:</strong> ${graduate.major}</p>
                    <p><strong>Nơi công tác:</strong> ${graduate.workplace}</p>
                    <p><strong>Năm tốt nghiệp:</strong> ${graduate.year}</p>
                    <p><strong>Thành tích nổi bật:</strong> ${graduate.achievement}</p>
                    <p><strong>Ghi chú:</strong> Cựu học sinh xuất sắc của trường</p>
                `;
            }
            
            // Hiển thị modal
            modal.style.display = 'flex';
        }
        
        // Đóng modal
        document.getElementById('closeModal').addEventListener('click', function() {
            document.getElementById('detailModal').style.display = 'none';
        });
        
        // Đóng modal khi click bên ngoài
        window.addEventListener('click', function(event) {
            const modal = document.getElementById('detailModal');
            if (event.target === modal) {
                modal.style.display = 'none';
            }
        });
        
        // Xử lý nút quay lại từ danh sách năm học
        document.getElementById('backButton').addEventListener('click', function() {
            showLoading();
            setTimeout(() => {
                // Ẩn container các nút năm học
                document.getElementById('yearButtonsContainer').style.display = 'none';
                
                // Hiển thị lại nội dung chính
                document.getElementById('mainPage').style.display = 'flex';
            }, 500);
        });
        
        // Xử lý nút quay lại từ trang học sinh
        document.getElementById('backToYears').addEventListener('click', function() {
            showLoading();
            setTimeout(() => {
                // Ẩn trang học sinh
                document.getElementById('studentPage').style.display = 'none';
                
                // Hiển thị lại container các nút năm học
                document.getElementById('yearButtonsContainer').style.display = 'flex';
            }, 500);
        });
        
        // Xử lý nút quay lại từ trang Thạc sĩ, Tiến sĩ
        document.getElementById('backToMain').addEventListener('click', function() {
            showLoading();
            setTimeout(() => {
                // Ẩn trang Thạc sĩ, Tiến sĩ
                document.getElementById('mastersPhdPage').style.display = 'none';
                
                // Hiển thị lại nội dung chính
                document.getElementById('mainPage').style.display = 'flex';
            }, 500);
        });
        
        // Khởi tạo hiệu ứng khi trang tải xong
        window.addEventListener('DOMContentLoaded', function() {
            createParticles();
            createFloatingElements();
        });
    </script>
</body>
</html>
