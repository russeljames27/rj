<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fernandez - Website</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }

        body {
            font-family: 'Courier New', monospace;
            background: #000;
            color: #00ff41;
            overflow-x: hidden;
            line-height: 1.6;
        }

        /* Matrix Rain Effect */
        .matrix-bg {
            position: fixed; top: 0; left: 0; width: 100%; height: 100%;
            z-index: -1; opacity: 0.1;
        }

        /* Navigation */
        nav {
            position: fixed; top: 0; width: 100%;
            background: rgba(0, 0, 0, 0.9);
            backdrop-filter: blur(10px);
            border-bottom: 2px solid #00ff41;
            z-index: 1000; padding: 1rem 0;
            transform: translateY(0);
            transition: transform 0.3s ease;
        }

        nav.nav-hidden {
            transform: translateY(-100%);
        }

        .nav-container {
            max-width: 1200px; margin: 0 auto;
            display: flex; justify-content: space-between; align-items: center;
            padding: 0 2rem;
        }

        .logo {
            font-size: 1.5rem; font-weight: bold; color: #00ff41;
            text-shadow: 0 0 10px #00ff41; animation: glow 2s ease-in-out infinite alternate;
        }

        .nav-links { display: flex; list-style: none; gap: 2rem; }

        .nav-links a {
            color: #00ff41; text-decoration: none; transition: all 0.3s ease;
            position: relative; padding: 0.5rem 1rem; border: 1px solid transparent;
        }

        .nav-links a:hover {
            border: 1px solid #00ff41; box-shadow: 0 0 15px #00ff41; transform: translateY(-2px);
        }

        /* Hero Section */
        .hero {
            height: 100vh; display: flex; align-items: center; justify-content: center;
            position: relative; background: linear-gradient(45deg, #000, #001a00);
            overflow: hidden;
        }
        .hero::before {
            content: ''; position: absolute; width: 200%; height: 200%;
            background: radial-gradient(circle at center, rgba(0,255,65,0.1) 0%, transparent 70%);
            animation: heroGlow 8s ease-in-out infinite alternate;
        }
        .hero::after {
            content: ''; position: absolute; inset: 0;
            background: repeating-linear-gradient(0deg, transparent, transparent 2px, rgba(0,255,65,0.03) 2px, rgba(0,255,65,0.03) 4px);
            animation: scanlines 8s linear infinite;
        }
        @keyframes heroGlow {
            from { transform: translate(-25%, -25%) scale(1); }
            to { transform: translate(-25%, -25%) scale(1.2); }
        }
        @keyframes scanlines {
            from { transform: translateY(0); }
            to { transform: translateY(10px); }
        }

        .hero-content { text-align: center; z-index: 2; position: relative; }

        .hero h1 {
            font-size: 4rem; margin-bottom: 1rem;
            white-space: nowrap; overflow: hidden; width: fit-content; margin: 0 auto 1rem;
            position: relative;
            background: linear-gradient(90deg, #00ff41, #00ff41, #ffffff, #00ff41, #00ff41);
            background-size: 200% auto;
            -webkit-background-clip: text;
            background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: textShimmer 3s linear infinite;
            filter: drop-shadow(0 0 20px rgba(0,255,65,0.5));
        }
        @keyframes textShimmer {
            to { background-position: 200% center; }
        }
        .hero h1::after {
            content: ''; display: inline-block; width: 2px; height: 1em; 
            background: linear-gradient(to bottom, transparent, #00ff41, transparent);
            margin-left: 6px; animation: caretBlink .8s steps(1, end) infinite, caretGlow 2s ease-in-out infinite;
            vertical-align: -0.15em;
        }
        @keyframes caretBlink { 50% { opacity: 0; } }
        @keyframes caretGlow {
            0%, 100% { box-shadow: 0 0 5px #00ff41; }
            50% { box-shadow: 0 0 20px #00ff41, 0 0 30px #00ff41; }
        }

        .hero .subtitle {
            font-size: 1.5rem; opacity: 0; animation: fadeInUp 1s ease 4s both, float 3s ease-in-out infinite 5s; 
            margin-bottom: 2rem;
            text-shadow: 0 0 10px rgba(0,255,65,0.5);
        }
        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
        }

        .cta-button {
            display: inline-block; padding: 1rem 2rem; background: transparent;
            border: 2px solid #00ff41; color: #00ff41; text-decoration: none; transition: all 0.3s ease;
            opacity: 0; animation: fadeInUp 1s ease 5s both, pulse 2s ease-in-out infinite 6s; 
            position: relative; overflow: hidden;
            box-shadow: 0 0 20px rgba(0,255,65,0.2), inset 0 0 20px rgba(0,255,65,0.1);
        }
        .cta-button:hover { 
            background: #00ff41; color: #000; 
            box-shadow: 0 0 40px #00ff41, 0 0 60px rgba(0,255,65,0.5), inset 0 0 20px rgba(0,255,65,0.3);
            transform: translateY(-5px) scale(1.05);
        }
        .cta-button::before {
            content: ''; position: absolute; top: 0; left: -100%; width: 100%; height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.4), transparent);
            transition: left 0.5s;
        }
        .cta-button:hover::before { left: 100%; }
        .cta-button::after {
            content: ''; position: absolute; inset: -2px;
            background: linear-gradient(45deg, transparent, #00ff41, transparent);
            border-radius: inherit; opacity: 0; transition: opacity 0.3s;
            z-index: -1; animation: borderRotate 3s linear infinite;
        }
        .cta-button:hover::after { opacity: 0.7; }
        @keyframes borderRotate {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }

        /* Section Styling */
        .section {
            padding: 5rem 2rem; max-width: 1200px; margin: 0 auto;
            opacity: 0; transform: translateY(50px); transition: all 0.8s ease;
        }
        .section.visible { opacity: 1; transform: translateY(0); }

        .section h2 {
            font-size: 2.5rem; margin-bottom: 3rem; text-align: center; position: relative; color: #00ff41;
        }
        .section h2::after {
            content: ''; position: absolute; bottom: -10px; left: 50%; transform: translateX(-50%);
            width: 100px; height: 3px; 
            background: linear-gradient(90deg, transparent, #00ff41, #00ff41, transparent); 
            animation: underlinePulse 2s ease-in-out infinite;
            box-shadow: 0 0 10px #00ff41;
        }
        @keyframes underlinePulse {
            0%, 100% { width: 100px; opacity: 1; }
            50% { width: 150px; opacity: 0.7; box-shadow: 0 0 20px #00ff41; }
        }

        /* About Section */
        .about-content { display: grid; grid-template-columns: 1fr 2fr; gap: 3rem; align-items: center; }

        .profile-image {
            width: 300px; height: 300px; border-radius: 50%; border: 3px solid #00ff41;
            box-shadow: 0 0 30px rgba(0, 255, 65, 0.3); transition: all 0.5s ease;
            display: block; object-fit: cover; object-position: center;
            position: relative; animation: profileFloat 4s ease-in-out infinite;
        }
        .profile-image:hover { 
            transform: scale(1.1) rotate(5deg); 
            box-shadow: 0 0 60px rgba(0, 255, 65, 0.6), 0 0 100px rgba(0, 255, 65, 0.3);
            border-color: #fff;
            filter: brightness(1.1) contrast(1.1);
        }
        @keyframes profileFloat {
            0%, 100% { transform: translateY(0px) scale(1); }
            50% { transform: translateY(-15px) scale(1.02); }
        }

        .about-text { font-size: 1.1rem; line-height: 1.8; }

        /* Skills Section */
        .skills-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 2rem; }
        .skill-card {
            background: rgba(0, 255, 65, 0.1); border: 1px solid #00ff41; padding: 2rem; border-radius: 10px;
            transition: all 0.5s cubic-bezier(0.34, 1.56, 0.64, 1); position: relative; overflow: hidden;
        }
        .skill-card::before {
            content: ''; position: absolute; top: -2px; left: -2px; right: -2px; bottom: -2px;
            background: linear-gradient(45deg, #00ff41, #008f11, #00ff41, #008f11);
            background-size: 400% 400%; z-index: -1; opacity: 0;
            transition: opacity 0.5s ease; border-radius: 10px;
            animation: gradientShift 3s ease infinite;
        }
        @keyframes gradientShift {
            0%, 100% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
        }
        .skill-card::after {
            content: ''; position: absolute; inset: 0; 
            background: radial-gradient(circle at var(--mouse-x, 50%) var(--mouse-y, 50%), rgba(0,255,65,0.2), transparent 60%);
            opacity: 0; transition: opacity 0.3s;
        }
        .skill-card:hover { 
            transform: translateY(-15px) scale(1.03); 
            box-shadow: 0 20px 40px rgba(0, 255, 65, 0.4), 0 0 60px rgba(0, 255, 65, 0.2);
            background: rgba(0, 255, 65, 0.15);
        }
        .skill-card:hover::before { opacity: 1; }
        .skill-card:hover::after { opacity: 1; }
        .skill-progress { width: 100%; height: 8px; background: rgba(0, 255, 65, 0.2); margin-top: 1rem; border-radius: 4px; overflow: hidden; position: relative; }
        .skill-progress::before {
            content: ''; position: absolute; inset: 0;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.3), transparent);
            animation: progressShimmer 2s infinite;
        }
        @keyframes progressShimmer {
            from { transform: translateX(-100%); }
            to { transform: translateX(200%); }
        }
        .progress-bar { 
            height: 100%; 
            background: linear-gradient(90deg, #00ff41, #00d638, #00ff41);
            background-size: 200% 100%;
            width: 0; transition: width 2s cubic-bezier(0.34, 1.56, 0.64, 1);
            animation: progressGlow 2s ease-in-out infinite;
            position: relative;
            box-shadow: 0 0 10px rgba(0,255,65,0.8), inset 0 0 10px rgba(255,255,255,0.3);
        }
        @keyframes progressGlow {
            0%, 100% { background-position: 0% 50%; filter: brightness(1); }
            50% { background-position: 100% 50%; filter: brightness(1.3); }
        }

        /* Certificates Section */
        .cert-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem; }
        .cert-card {
            background: linear-gradient(135deg, rgba(0, 255, 65, 0.1), rgba(0, 143, 17, 0.1));
            border: 2px solid #00ff41; padding: 2rem; border-radius: 15px; 
            transition: all 0.5s cubic-bezier(0.34, 1.56, 0.64, 1); position: relative;
            overflow: hidden;
        }
        .cert-card::before {
            content: ''; position: absolute; inset: -100%; 
            background: conic-gradient(from 0deg, transparent, #00ff41, transparent 30%);
            animation: certRotate 4s linear infinite; opacity: 0; transition: opacity 0.5s;
        }
        .cert-card:hover::before { opacity: 0.3; }
        @keyframes certRotate {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }
        .cert-card:hover { 
            transform: scale(1.08) translateY(-10px); 
            box-shadow: 0 0 50px rgba(0, 255, 65, 0.5), 0 20px 40px rgba(0, 255, 65, 0.3);
            border-color: #fff;
        }
        
        .cert-card h3 {
            margin-bottom: 0.5rem;
            font-size: 1.2rem;
        }
        
        .cert-card .cert-issuer {
            color: #00d638;
            font-size: 0.95rem;
            margin-bottom: 0.75rem;
        }
        
        .cert-card .cert-description {
            font-size: 0.9rem;
            opacity: 0.8;
            line-height: 1.6;
        }

        /* Experience / Education Timeline */
        .timeline { position: relative; margin: 2rem 0; }
        .timeline::before {
            content: ''; position: absolute; left: 50%; top: 0; bottom: 0; width: 2px;
            background: linear-gradient(to bottom, #00ff41, #008f11); transform: translateX(-50%);
        }
        .timeline-item { position: relative; margin: 3rem 0; opacity: 0; animation: slideIn 0.8s ease forwards; }
        .timeline-item:nth-child(even) { animation-delay: 0.2s; }
        .timeline-item:nth-child(odd) { animation-delay: 0.4s; }
        .timeline-content {
            background: rgba(0, 255, 65, 0.1); padding: 2rem; border-radius: 10px; border: 1px solid #00ff41;
            width: 45%; position: relative;
        }
        .timeline-item:nth-child(even) .timeline-content { margin-left: 55%; }
        .timeline-dot {
            position: absolute; left: 50%; top: 50%;
            transform: translate(-50%, -50%);
            width: 20px; height: 20px; background: #00ff41; border-radius: 50%;
            box-shadow: 0 0 20px rgba(0, 255, 65, 0.5);
            animation: dotPulse 2s infinite;
        }
        
        .timeline-content h3 {
            margin-bottom: 0.5rem;
            font-size: 1.3rem;
        }
        
        .timeline-content .position {
            color: #00d638;
            font-size: 1rem;
            margin-bottom: 0.5rem;
        }
        
        .timeline-content .period {
            color: #008f11;
            font-size: 0.9rem;
            margin-bottom: 1rem;
        }
        
        .timeline-content ul {
            list-style: none;
            padding-left: 0;
        }
        
        .timeline-content ul li {
            padding-left: 1.5rem;
            position: relative;
            margin-bottom: 0.5rem;
            font-size: 0.95rem;
        }
        
        .timeline-content ul li::before {
            content: '▹';
            position: absolute;
            left: 0;
            color: #00ff41;
        }

        @keyframes slideIn { from { opacity: 0; transform: translateX(-50px); } to { opacity: 1; transform: translateX(0); } }
        @keyframes dotPulse {
            0%, 100% { transform: translate(-50%, -50%) scale(1);   opacity: 1; }
            50%      { transform: translate(-50%, -50%) scale(1.1); opacity: 0.7; }
        }

        /* Projects Section */
        .projects-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(350px, 1fr)); gap: 2rem; }
        .project-card { 
            background: rgba(0, 255, 65, 0.05); border: 1px solid #00ff41; border-radius: 15px; 
            overflow: hidden; transition: all 0.5s cubic-bezier(0.34, 1.56, 0.64, 1); 
            position: relative; cursor: pointer;
        }
        .project-card::before {
            content: ''; position: absolute; inset: 0;
            background: linear-gradient(135deg, rgba(0,255,65,0.1), transparent, rgba(0,255,65,0.1));
            opacity: 0; transition: opacity 0.5s;
        }
        .project-card:hover::before { opacity: 1; }
        .project-card:hover { 
            transform: translateY(-15px) rotateX(5deg) scale(1.02); 
            box-shadow: 0 25px 50px rgba(0, 255, 65, 0.4), 0 0 80px rgba(0, 255, 65, 0.2);
            border-color: #fff;
        }

        .project-image {
            height: 200px; background: #001a00;
            display: flex; align-items: center; justify-content: center; position: relative; overflow: hidden;
        }
        .project-image img {
            width: 100%; height: 100%; object-fit: cover; display: block;
        }

        .project-info { padding: 2rem; }
        .project-tech { display: flex; flex-wrap: wrap; gap: 0.5rem; margin: 1rem 0; }
        .tech-tag { background: rgba(0, 255, 65, 0.2); color: #00ff41; padding: 0.3rem 0.8rem; border-radius: 20px; font-size: 0.8rem; border: 1px solid #00ff41; }

        /* Modal Styles */
        .modal {
            display: none; position: fixed; z-index: 10000; left: 0; top: 0; width: 100%; height: 100%;
            background: rgba(0, 0, 0, 0.95); backdrop-filter: blur(10px);
        }
        .modal.active { display: flex; align-items: center; justify-content: center; animation: fadeIn 0.3s ease; }
        
        .modal-content {
            background: linear-gradient(135deg, rgba(0, 20, 0, 0.9), rgba(0, 0, 0, 0.95));
            border: 2px solid #00ff41; border-radius: 20px; padding: 2rem; max-width: 900px; width: 90%;
            max-height: 90vh; overflow-y: auto; position: relative;
            box-shadow: 0 0 50px rgba(0, 255, 65, 0.3);
        }

        .modal-close {
            position: absolute; top: 1rem; right: 1rem; background: none; border: none;
            color: #00ff41; font-size: 2rem; cursor: pointer; transition: all 0.3s ease;
            width: 40px; height: 40px; display: flex; align-items: center; justify-content: center;
            border-radius: 50%; border: 1px solid #00ff41;
        }
        .modal-close:hover { background: #00ff41; color: #000; transform: rotate(90deg); }

        .modal-header { text-align: center; margin-bottom: 2rem; }
        .modal-header h2 {
            font-size: 2.5rem; color: #00ff41; margin-bottom: 0.5rem;
            text-shadow: 0 0 20px rgba(0, 255, 65, 0.5);
        }
        .modal-header p { font-size: 1.1rem; opacity: 0.8; margin-bottom: 1rem; }

        /* Carousel Styles */
        .carousel-container {
            position: relative; margin: 2rem 0; border-radius: 15px; overflow: hidden;
            border: 2px solid #00ff41; box-shadow: 0 0 30px rgba(0, 255, 65, 0.2);
        }
        .carousel-wrapper { position: relative; width: 100%; height: 400px; overflow: hidden; }
        .carousel-slide {
            position: absolute; top: 0; left: 0; width: 100%; height: 100%;
            opacity: 0; transition: opacity 0.5s ease-in-out;
            display: flex; align-items: center; justify-content: center;
            background: linear-gradient(135deg, #001a00, #003300);
        }
        .carousel-slide.active { opacity: 1; }
        .carousel-slide img { max-width: 100%; max-height: 100%; object-fit: contain; border-radius: 10px; }
        .carousel-slide video { max-width: 100%; max-height: 100%; object-fit: contain; border-radius: 10px; outline: none; }

        .carousel-nav {
            position: absolute; top: 50%; transform: translateY(-50%);
            background: rgba(0, 255, 65, 0.2); border: 1px solid #00ff41;
            color: #00ff41; font-size: 1.5rem; padding: 0.5rem 1rem;
            cursor: pointer; transition: all 0.3s ease; border-radius: 50%;
            width: 50px; height: 50px; display: flex; align-items: center; justify-content: center;
        }
        .carousel-nav:hover { background: #00ff41; color: #000; box-shadow: 0 0 20px rgba(0, 255, 65, 0.5); }
        .carousel-prev { left: 1rem; }
        .carousel-next { right: 1rem; }

        .carousel-indicators { display: flex; justify-content: center; gap: 0.5rem; margin-top: 1rem; flex-wrap: wrap; }
        .carousel-dot {
            width: 12px; height: 12px; border-radius: 50%; border: 2px solid #00ff41;
            background: transparent; cursor: pointer; transition: all 0.3s ease;
        }
        .carousel-dot.active { background: #00ff41; box-shadow: 0 0 15px rgba(0, 255, 65, 0.5); }

        .modal-tech { display: flex; flex-wrap: wrap; gap: 0.5rem; justify-content: center; margin: 1rem 0; }
        .modal-tech .tech-tag {
            background: rgba(0, 255, 65, 0.2); color: #00ff41; padding: 0.5rem 1rem;
            border-radius: 25px; border: 1px solid #00ff41; font-size: 0.9rem;
        }

        .modal-links { display: flex; justify-content: center; gap: 1rem; margin-top: 2rem; }
        .modal-link {
            padding: 0.8rem 2rem; background: transparent; border: 2px solid #00ff41;
            color: #00ff41; text-decoration: none; border-radius: 25px; transition: all 0.3s ease;
            display: inline-flex; align-items: center; gap: 0.5rem;
        }
        .modal-link:hover { background: #00ff41; color: #000; transform: translateY(-2px); }

        /* Footer */
        footer { background: #000; border-top: 2px solid #00ff41; padding: 2rem; text-align: center; }
        .social-links { display: flex; justify-content: center; gap: 2rem; margin-bottom: 1rem; }
        .social-links a {
            color: #00ff41; font-size: 1.5rem; transition: all 0.3s ease;
            text-decoration: none; border-bottom: none;
        }
        .social-links a:hover, .social-links a:focus {
            transform: scale(1.2); text-shadow: 0 0 15px #00ff41; text-decoration: none; outline: none;
        }

        /* Animations */
        @keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }
        @keyframes fadeInUp { from { opacity: 0; transform: translateY(30px); } to { opacity: 1; transform: translateY(0); } }
        @keyframes glow { from { text-shadow: 0 0 10px #00ff41; } to { text-shadow: 0 0 20px #00ff41, 0 0 30px #00ff41; } }
        @keyframes pulse { 0%,100% { transform: scale(1); opacity: 1; } 50% { transform: scale(1.1); opacity: 0.7; } }

        /* THEMED SCROLLBARS */
        .modal-content,
        .carousel-wrapper {
            scrollbar-width: thin;
            scrollbar-color: #00ff41 #001a00;
        }
        .modal-content::-webkit-scrollbar,
        .carousel-wrapper::-webkit-scrollbar { width: 10px; height: 10px; }
        .modal-content::-webkit-scrollbar-track,
        .carousel-wrapper::-webkit-scrollbar-track {
            background: #001a00; border-radius: 8px; box-shadow: inset 0 0 8px rgba(0,255,65,0.15);
        }
        .modal-content::-webkit-scrollbar-thumb,
        .carousel-wrapper::-webkit-scrollbar-thumb {
            background: #00ff41; border-radius: 8px; border: 2px solid #001a00; box-shadow: inset 0 0 12px rgba(0,255,65,0.5);
        }
        .modal-content::-webkit-scrollbar-thumb:hover,
        .carousel-wrapper::-webkit-scrollbar-thumb:hover {
            background: #00d638; box-shadow: inset 0 0 14px rgba(0,255,65,0.7);
        }
        
        /* Floating orbs animation */
        .floating-orb {
            position: fixed;
            border-radius: 50%;
            background: radial-gradient(circle, rgba(0,255,65,0.3), transparent);
            pointer-events: none;
            z-index: 0;
            animation: floatOrb 20s infinite ease-in-out;
        }
        
        @keyframes floatOrb {
            0%, 100% { transform: translate(0, 0) scale(1); }
            33% { transform: translate(100px, -100px) scale(1.2); }
            66% { transform: translate(-100px, 100px) scale(0.8); }
        }
        
        /* Text glitch effect */
        .glitch {
            position: relative;
            display: inline-block;
        }
        
        .glitch::before,
        .glitch::after {
            content: attr(data-text);
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            opacity: 0;
        }
        
        .glitch:hover::before {
            animation: glitch-1 0.3s infinite;
            color: #ff00ff;
            z-index: -1;
        }
        
        .glitch:hover::after {
            animation: glitch-2 0.3s infinite;
            color: #00ffff;
            z-index: -2;
        }
        
        @keyframes glitch-1 {
            0%, 100% { transform: translate(0); opacity: 0.7; }
            25% { transform: translate(-2px, 2px); }
            50% { transform: translate(2px, -2px); }
            75% { transform: translate(-2px, -2px); }
        }
        
        @keyframes glitch-2 {
            0%, 100% { transform: translate(0); opacity: 0.7; }
            25% { transform: translate(2px, -2px); }
            50% { transform: translate(-2px, 2px); }
            75% { transform: translate(2px, 2px); }
        }
        
        /* Holographic effect */
        .holographic {
            position: relative;
            background: linear-gradient(45deg, #00ff41, #00d638, #00ff41, #00d638);
            background-size: 400% 400%;
            animation: holographicShift 3s ease infinite;
        }
        
        @keyframes holographicShift {
            0%, 100% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
        }
    </style>
</head>
<body>
    <canvas class="matrix-bg" id="matrix"></canvas>

    <nav>
        <div class="nav-container">
            <div class="logo glitch" data-text="&lt;/DEV&gt;">&lt;/DEV&gt;</div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#certificates">Certificates</a></li>
                <li><a href="#experience">Experience</a></li>
                <li><a href="#projects">Projects</a></li>
            </ul>
        </div>
    </nav>

    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Russel James Fernandez</h1>
            <p class="subtitle">Web Developer & IT Specialist</p>
            <a href="#about" class="cta-button">Initialize Connection &gt;&gt;</a>
        </div>
    </section>

    <section id="about" class="section">
        <h2>About Me</h2>
        <div class="about-content">
            <img src="fernandez.jpg" alt="Russel James Fernandez" class="profile-image">
            <div class="about-text">
                <p>
        Hi! I'm <strong>Russel James Fernandez</strong>, a <strong>4th-year BSIT student at Pamantasan ng Lungsod ng Maynila</strong>.
        I build clean, responsive web experiences and love crafting UI/UX that feels effortless.
        Beyond design, I'm practicing backend development and sharpening my problem-solving through projects.
      </p>
      <br>
      <p>
        When I'm not coding, you'll catch me <strong>reading law books</strong>, <strong>creating web designs</strong>,
        exploring <strong>UI/UX</strong>, <strong>practicing backend</strong>, and relaxing with a <strong>mobile game</strong>.
        I'm working toward a unique path—<strong>to become both a lawyer and an IT professional</strong>—so I can bridge
        technology and the law to create secure, inclusive digital spaces.
      </p>
      <br>
      <p><em>"I stand here today because someone believed in me, and I owe it to the children to believe in them. Khop khun khap."</em></p>
            </div>
        </div>
    </section>

    <section id="skills" class="section">
        <h2>Technical Arsenal</h2>
        <div class="skills-grid">
            <div class="skill-card">
                <h3>Frontend Development</h3>
                <p>React, HTML5, CSS3, JavaScript</p>
                <div class="skill-progress"><div class="progress-bar" data-width="90%"></div></div>
            </div>
            <div class="skill-card">
                <h3>Backend Development</h3>
                <p>PHP, MySQL</p>
                <div class="skill-progress"><div class="progress-bar" data-width="85%"></div></div>
            </div>
            <div class="skill-card">
                <h3>Web UI/UX Design</h3>
                <p>Figma, Flutter, Canva</p>
                <div class="skill-progress"><div class="progress-bar" data-width="80%"></div></div>
            </div>
        </div>
    </section>

    <section id="certificates" class="section">
        <h2>Certifications</h2>
        <div class="cert-grid">
            <div class="cert-card">
                <h3>Introduction to IT Acquisition</h3>
                <p class="cert-issuer">University of the Philippines System • 2024</p>
                <p class="cert-description">Comprehensive training on IT procurement processes and strategic acquisition management</p>
            </div>
            <div class="cert-card">
                <h3>AI in Business Analytics</h3>
                <p class="cert-issuer">Ateneo De Manila University • 2024</p>
                <p class="cert-description">The Future of Business Planning and Decision-Making using AI technologies</p>
            </div>
            <div class="cert-card">
                <h3>AI-Powered Future</h3>
                <p class="cert-issuer">DICT Regional Office V, Legazpi City • 2024</p>
                <p class="cert-description">Mastering Prompt Engineering in Generative AI for practical applications</p>
            </div>
            <div class="cert-card">
                <h3>AI Literacy for Students</h3>
                <p class="cert-issuer">Tagpros Education • 2024</p>
                <p class="cert-description">Critical Thinking and Creativity in the age of artificial intelligence</p>
            </div>
            <div class="cert-card">
                <h3>Building Web Solutions Workshop</h3>
                <p class="cert-issuer">Google Developer Group • 2024</p>
                <p class="cert-description">Using Gemini and Firebase Studio for modern web development</p>
            </div>
            <div class="cert-card">
                <h3>Kwentuhang Cybersecurity</h3>
                <p class="cert-issuer">Philippine Institute of Cyber Security Professionals • 2024</p>
                <p class="cert-description">Building True Cyber Resilience in organizations and systems</p>
            </div>
        </div>
    </section>

    <section id="experience" class="section">
        <h2>Experience & Education</h2>
        <div class="timeline">
            <div class="timeline-item">
                <div class="timeline-content">
                    <h3>Amazon Web Services Cloud Club – Haribon (AWSCC Haribon)</h3>
                    <p class="position">IoT & Robotics Team | Volunteer</p>
                    <p class="period">2024 – Present</p>
                    <ul>
                        <li>Strengthens technical expertise by developing innovative IoT and software solutions using AWS technologies</li>
                        <li>Collaborate with peers to design and deploy cloud-integrated robotics systems</li>
                    </ul>
                </div>
                <div class="timeline-dot"></div>
            </div>
            
            <div class="timeline-item">
                <div class="timeline-content">
                    <h3>Microsoft Student Community – PLM</h3>
                    <p class="position">Lead Writer & Head of Publication</p>
                    <p class="period">2024 – 2025</p>
                    <ul>
                        <li>Supervised newsletters, editorial content, and social media releases for Microsoft-related initiatives and campaigns</li>
                    </ul>
                </div>
                <div class="timeline-dot"></div>
            </div>
            
            <div class="timeline-item">
                <div class="timeline-content">
                    <h3>Google Developer Student Clubs (GDSC – PLM)</h3>
                    <p class="position">Technology Department | Mobile Developer</p>
                    <p class="period">2024 – Present</p>
                    <ul>
                        <li>Develops and maintains mobile applications aligned with GDSC projects and community goals</li>
                        <li>Collaborates with developers and designers to implement innovative technology-driven solutions</li>
                    </ul>
                </div>
                <div class="timeline-dot"></div>
            </div>
            
            <div class="timeline-item">
                <div class="timeline-content">
                    <h3>Pamantasan ng Lungsod ng Maynila</h3>
                    <p class="position">Bachelor of Science in Information Technology</p>
                    <p class="period">2022 – 2026</p>
                </div>
                <div class="timeline-dot"></div>
            </div>
            
            <div class="timeline-item">
                <div class="timeline-content">
                    <h3>Golden Success College Manila</h3>
                    <p class="position">Senior High School - Humanities and Social Sciences</p>
                    <p class="period">2020 – 2022</p>
                    <p>Salutatorian | With Honors</p>
                </div>
                <div class="timeline-dot"></div>
            </div>
            
            <div class="timeline-item">
                <div class="timeline-content">
                    <h3>Cayetano Arellano High School</h3>
                    <p class="position">Junior High School</p>
                    <p class="period">2016 – 2020</p>
                    <p>6th Honorable Mention | With High Honor</p>
                </div>
                <div class="timeline-dot"></div>
            </div>
            
            <div class="timeline-item">
                <div class="timeline-content">
                    <h3>Antonio Regidor Elementary School</h3>
                    <p class="position">Primary Education</p>
                    <p class="period">2010 – 2016</p>
                    <p>7th Top</p>
                </div>
                <div class="timeline-dot"></div>
            </div>
        </div>
    </section>

    <section id="projects" class="section">
        <h2>Featured Projects</h2>
        <div class="projects-grid">
            <!-- Museo ng Pag asa -->
            <div class="project-card" data-project="securevault">
                <div class="project-image">
                    <img src="museotb.png" alt="Museo ng Pag asa thumbnail">
                </div>
                <div class="project-info">
                    <h3>Museo ng Pag asa</h3>
                    <p>A streamlined web platform for booking timed-entry visits, organizing group reservations, and sending email/SMS reminders so guests arrive on schedule. The admin web dashboard centralizes capacity control, slot scheduling, blackout dates, and approval of special requests, with tools for tracking attendance and accommodating limited walk-ins. Designed for smooth visitor flow and minimal staff workload.</p>
                    <div class="project-tech">
                        <span class="tech-tag">HTML5</span><span class="tech-tag">CSS3</span><span class="tech-tag">JScript</span><span class="tech-tag">PHP</span>
                    </div>
                </div>
            </div>

            <!-- Puscydog -->
            <div class="project-card" data-project="cloudmonitor">
                <div class="project-image">
                    <img src="puscydogtb.png" alt="Puscydog thumbnail">
                </div>
                <div class="project-info">
                    <h3>Puscydog</h3>
                    <p>PusCyDog is an IoT-powered vending machine that swaps clear PET bottles for measured dog or cat food. A Raspberry Pi validates and weighs bottles, then converts total weight into food grams using admin-set rates. A web-based admin dashboard handles pricing updates, live status (inventory, bin full), transaction logs, and maintenance alerts for remote management.</p>
                    <div class="project-tech">
                        <span class="tech-tag">MySQL</span><span class="tech-tag">PHP</span><span class="tech-tag">HTML5 and CSS3</span><span class="tech-tag">JScript</span>
                    </div>
                </div>
            </div>

            <!-- HIVoice -->
            <div class="project-card" data-project="devops">
                <div class="project-image">
                    <img src="hivoicetb.png" alt="HIVoice thumbnail">
                </div>
                <div class="project-info">
                    <h3>HIVoice</h3>
                    <p>HIVOICE is a web-based support and education platform on HIV that guides users with clear, stigma-free info, a friendly chatbot, self-test kit and care-kit requests, and clinic resources. An admin web dashboard lets staff manage content (Basics/Prevention /Testing/Treatment), edit the self-test form, approve requests, schedule announcements, and track user notifications—keeping everything updated and coordinated in one place.</p>
                    <div class="project-tech">
                       <span class="tech-tag">HTML5 and CSS3</span><span class="tech-tag">JScript</span><span class="tech-tag">PHP</span><span class="tech-tag">MySQL</span><span class="tech-tag">Security Hash</span><span class="tech-tag">API's</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Project Modals -->
    <div id="modal-securevault" class="modal">
        <div class="modal-content">
            <button class="modal-close">&times;</button>
            <div class="modal-header">
                <h2>Museo ng Pag asa</h2>
                <p>Timed-entry booking platform with group reservations and reminders. Admin dashboard centralizes capacity control, slot scheduling, blackout dates, and approvals for smooth visitor flow.</p>
                <div class="modal-tech">
                    <span class="tech-tag">HTML5</span>
                    <span class="tech-tag">CSS3</span>
                    <span class="tech-tag">JavaScript</span>
                    <span class="tech-tag">PHP</span>
                </div>
            </div>

            <div class="carousel-container">
                <div class="carousel-wrapper">
                    <div class="carousel-slide active"><img src="m1.png" alt="Museo screenshot 1"></div>
                    <div class="carousel-slide"><img src="m2.png" alt="Museo screenshot 2"></div>
                    <div class="carousel-slide"><img src="m3.png" alt="Museo screenshot 3"></div>
                    <div class="carousel-slide"><img src="m4.png" alt="Museo screenshot 4"></div>
                    <div class="carousel-slide"><img src="m5.png" alt="Museo screenshot 5"></div>
                </div>
                <button class="carousel-nav carousel-prev">‹</button>
                <button class="carousel-nav carousel-next">›</button>
            </div>
            <div class="carousel-indicators">
                <div class="carousel-dot active" data-slide="0"></div>
                <div class="carousel-dot" data-slide="1"></div>
                <div class="carousel-dot" data-slide="2"></div>
                <div class="carousel-dot" data-slide="3"></div>
                <div class="carousel-dot" data-slide="4"></div>
            </div>
        </div>
    </div>

    <div id="modal-cloudmonitor" class="modal">
        <div class="modal-content">
            <button class="modal-close">&times;</button>
            <div class="modal-header">
                <h2>Puscydog</h2>
                <p>IoT vending that swaps PET bottles for pet food. Raspberry Pi validates and weighs bottles; admin console sets conversion rates, monitors inventory/bin status, reviews logs, and triggers maintenance alerts.</p>
                <div class="modal-tech">
                    <span class="tech-tag">MySQL</span>
                    <span class="tech-tag">PHP</span>
                    <span class="tech-tag">HTML5</span>
                    <span class="tech-tag">CSS3</span>
                    <span class="tech-tag">JavaScript</span>
                    <span class="tech-tag">API's</span>
                </div>
            </div>

            <div class="carousel-container">
                <div class="carousel-wrapper">
                    <div class="carousel-slide active"><img src="p1.png" alt="Puscydog screenshot 1"></div>
                    <div class="carousel-slide"><img src="p2.png" alt="Puscydog screenshot 2"></div>
                    <div class="carousel-slide"><img src="p3.png" alt="Puscydog screenshot 3"></div>
                    <div class="carousel-slide"><img src="p4.png" alt="Puscydog screenshot 4"></div>
                    <div class="carousel-slide"><img src="p5.png" alt="Puscydog screenshot 5"></div>
                    <div class="carousel-slide">
                        <video src="pv1.mp4" controls muted playsinline preload="metadata"></video>
                    </div>
                </div>
                <button class="carousel-nav carousel-prev">‹</button>
                <button class="carousel-nav carousel-next">›</button>
            </div>
            <div class="carousel-indicators">
                <div class="carousel-dot active" data-slide="0"></div>
                <div class="carousel-dot" data-slide="1"></div>
                <div class="carousel-dot" data-slide="2"></div>
                <div class="carousel-dot" data-slide="3"></div>
                <div class="carousel-dot" data-slide="4"></div>
                <div class="carousel-dot" data-slide="5"></div>
            </div>
        </div>
    </div>

    <div id="modal-devops" class="modal">
        <div class="modal-content">
            <button class="modal-close">&times;</button>
            <div class="modal-header">
                <h2>HIVoice</h2>
                <p>Stigma-free HIV education with chatbot assistance, self-test and care-kit requests, and clinic resources. Admin dashboard manages content, approvals, announcements, and notifications.</p>
                <div class="modal-tech">
                    <span class="tech-tag">HTML5 and CSS3</span>
                    <span class="tech-tag">JavaScript</span>
                    <span class="tech-tag">PHP</span>
                    <span class="tech-tag">MySQL</span>
                    <span class="tech-tag">Security Hash</span>
                    <span class="tech-tag">API's</span>
                </div>
            </div>

            <div class="carousel-container">
                <div class="carousel-wrapper">
                    <div class="carousel-slide active"><img src="h1.png" alt="HIVoice screenshot 1"></div>
                    <div class="carousel-slide"><img src="h2.png" alt="HIVoice screenshot 2"></div>
                    <div class="carousel-slide"><img src="h3.png" alt="HIVoice screenshot 3"></div>
                    <div class="carousel-slide"><img src="h4.png" alt="HIVoice screenshot 4"></div>
                    <div class="carousel-slide"><img src="h5.png" alt="HIVoice screenshot 5"></div>
                    <div class="carousel-slide"><img src="h6.png" alt="HIVoice screenshot 6"></div>
                    <div class="carousel-slide"><img src="h7.png" alt="HIVoice screenshot 7"></div>
                    <div class="carousel-slide"><img src="h8.png" alt="HIVoice screenshot 8"></div>
                    <div class="carousel-slide"><img src="h9.png" alt="HIVoice screenshot 9"></div>
                    <div class="carousel-slide"><img src="h10.png" alt="HIVoice screenshot 10"></div>
                    <div class="carousel-slide"><img src="h11.png" alt="HIVoice screenshot 11"></div>
                </div>
                <button class="carousel-nav carousel-prev">‹</button>
                <button class="carousel-nav carousel-next">›</button>
            </div>
            <div class="carousel-indicators">
                <div class="carousel-dot active" data-slide="0"></div>
                <div class="carousel-dot" data-slide="1"></div>
                <div class="carousel-dot" data-slide="2"></div>
                <div class="carousel-dot" data-slide="3"></div>
                <div class="carousel-dot" data-slide="4"></div>
                <div class="carousel-dot" data-slide="5"></div>
                <div class="carousel-dot" data-slide="6"></div>
                <div class="carousel-dot" data-slide="7"></div>
                <div class="carousel-dot" data-slide="8"></div>
                <div class="carousel-dot" data-slide="9"></div>
                <div class="carousel-dot" data-slide="10"></div>
            </div>
        </div>
    </div>

    <footer>
        <div class="social-links">
            <a href="https://mail.google.com/mail/?view=cm&fs=1&to=fernandezrusseljames27@gmail.com"
               target="_blank" rel="noopener noreferrer"
               aria-label="Compose email to fernandezrusseljames27@gmail.com" title="Compose Email">✉</a>
            <a href="https://www.facebook.com/russeljames.fernandez/">ⓕ</a>
            <a href="https://www.instagram.com/enigmatically_james/">🅾</a>
            <a href="https://x.com/rjdumplingszx">𝕏</a>
        </div>
        <p>&copy; 2025 Russel James Fernandez. All rights reserved. | Built with passion and caffeine ☕</p>
    </footer>

    <script>
        // Matrix rain effect
        function initMatrix() {
            const canvas = document.getElementById('matrix');
            const ctx = canvas.getContext('2d');
            canvas.width = window.innerWidth; canvas.height = window.innerHeight;

            const chars = '01アイウエオカキクケコサシスセソタチツテトナニヌネノハヒフヘホマミムメモヤユヨラリルレロワヲン';
            const charArray = chars.split('');
            const fontSize = 14; const columns = canvas.width / fontSize;
            const drops = Array.from({length: Math.floor(columns)}, () => 1);

            function draw() {
                ctx.fillStyle = 'rgba(0, 0, 0, 0.05)'; ctx.fillRect(0, 0, canvas.width, canvas.height);
                ctx.fillStyle = '#00ff41'; ctx.font = fontSize + 'px monospace';
                for (let i = 0; i < drops.length; i++) {
                    const text = charArray[Math.floor(Math.random() * charArray.length)];
                    ctx.fillText(text, i * fontSize, drops[i] * fontSize);
                    if (drops[i] * fontSize > canvas.height && Math.random() > 0.975) drops[i] = 0;
                    drops[i]++;
                }
            }
            setInterval(draw, 33);
        }
        initMatrix();

        // Resize handler
        window.addEventListener('resize', () => {
            const canvas = document.getElementById('matrix');
            canvas.width = window.innerWidth; canvas.height = window.innerHeight;
        });

        // Smooth scrolling
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) target.scrollIntoView({ behavior: 'smooth', block: 'start' });
            });
        });

        // Intersection Observer for animations
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                    if (entry.target.id === 'skills') {
                        setTimeout(() => {
                            document.querySelectorAll('.progress-bar').forEach(bar => {
                                bar.style.width = bar.dataset.width;
                            });
                        }, 500);
                    }
                }
            });
        }, { threshold: 0.1 });
        document.querySelectorAll('.section').forEach(section => observer.observe(section));

        // Hover tilt on cards
        document.querySelectorAll('.skill-card, .cert-card, .project-card').forEach(card => {
            card.addEventListener('mouseenter', function(){ 
                this.style.transform = 'translateY(-15px) rotateX(5deg) scale(1.02)'; 
            });
            card.addEventListener('mouseleave', function(){ 
                this.style.transform = 'translateY(0) rotateX(0deg) scale(1)'; 
            });
            
            // Advanced mouse tracking for glow effect
            card.addEventListener('mousemove', function(e) {
                const rect = this.getBoundingClientRect();
                const x = ((e.clientX - rect.left) / rect.width) * 100;
                const y = ((e.clientY - rect.top) / rect.height) * 100;
                this.style.setProperty('--mouse-x', x + '%');
                this.style.setProperty('--mouse-y', y + '%');
            });
        });

        // Subtitle typing effect
        setTimeout(() => {
            const subtitle = document.querySelector('.hero .subtitle');
            const text = subtitle.textContent; subtitle.textContent = ''; subtitle.style.opacity = '1';
            let i = 0;
            const typeInterval = setInterval(() => {
                subtitle.textContent += text[i]; i++;
                if (i >= text.length) clearInterval(typeInterval);
            }, 100);
        }, 4000);

        // Floating particles
        function createParticle() {
            const particle = document.createElement('div');
            particle.style.cssText = `
                position: fixed; width: 2px; height: 2px; background: #00ff41; pointer-events: none;
                z-index: -1; border-radius: 50%; box-shadow: 0 0 6px #00ff41;
            `;
            particle.style.left = Math.random() * window.innerWidth + 'px';
            particle.style.top = window.innerHeight + 'px';
            document.body.appendChild(particle);
            const animationDuration = Math.random() * 3000 + 2000;
            particle.animate([
                { transform: 'translateY(0px)', opacity: 0 },
                { transform: 'translateY(-100px)', opacity: 1 },
                { transform: `translateY(-${window.innerHeight + 100}px)`, opacity: 0 }
            ], { duration: animationDuration, easing: 'linear' }).onfinish = () => particle.remove();
        }
        setInterval(createParticle, 500);

        // Hero H1 typewriter with keyboard click sound
        (function () {
            const titleEl = document.querySelector('.hero h1');
            if (!titleEl) return;

            const fullText = titleEl.textContent.trim();
            titleEl.textContent = '';

            const delayBeforeStart = 1000;
            const perCharMs = 80;
            const skipSoundFor = new Set([' ', '\n', '\t']);

            // Web Audio
            let audioCtx;
            function ensureAudioCtx() {
                if (!audioCtx) audioCtx = new (window.AudioContext || window.webkitAudioContext)();
                if (audioCtx.state === 'suspended') audioCtx.resume();
            }
            function keyClick() {
                if (!audioCtx) return;
                const osc = audioCtx.createOscillator();
                const gain = audioCtx.createGain();
                osc.frequency.value = 650 + Math.random() * 120;
                gain.gain.setValueAtTime(0.0001, audioCtx.currentTime);
                gain.gain.exponentialRampToValueAtTime(0.3, audioCtx.currentTime + 0.005);
                gain.gain.exponentialRampToValueAtTime(0.0001, audioCtx.currentTime + 0.04);
                osc.connect(gain).connect(audioCtx.destination);
                osc.start();
                osc.stop(audioCtx.currentTime + 0.05);
            }

            ['pointerdown','keydown'].forEach(ev =>
                window.addEventListener(ev, ensureAudioCtx, { once: true })
            );

            setTimeout(() => {
                ensureAudioCtx();
                let i = 0;
                const timer = setInterval(() => {
                    titleEl.textContent += fullText[i];
                    if (!skipSoundFor.has(fullText[i])) keyClick();
                    i++;
                    if (i >= fullText.length) clearInterval(timer);
                }, perCharMs);
            }, delayBeforeStart);
        })();

        // Modal and Carousel System
        class ProjectModal {
            constructor() {
                this.currentModal = null;
                this.currentSlide = 0;
                this.autoSlideTimer = null;
                this.init();
            }

            init() {
                document.querySelectorAll('.project-card').forEach(card => {
                    card.addEventListener('click', () => {
                        const projectId = card.dataset.project;
                        this.openModal(projectId);
                    });
                });

                document.querySelectorAll('.modal-close').forEach(closeBtn => {
                    closeBtn.addEventListener('click', () => this.closeModal());
                });

                document.querySelectorAll('.modal').forEach(modal => {
                    modal.addEventListener('click', (e) => {
                        if (e.target === modal) this.closeModal();
                    });
                });

                document.querySelectorAll('.carousel-prev').forEach(btn => {
                    btn.addEventListener('click', () => this.prevSlide());
                });

                document.querySelectorAll('.carousel-next').forEach(btn => {
                    btn.addEventListener('click', () => this.nextSlide());
                });

                document.querySelectorAll('.carousel-dot').forEach(dot => {
                    dot.addEventListener('click', () => {
                        const slideIndex = parseInt(dot.dataset.slide);
                        this.goToSlide(slideIndex);
                    });
                });

                document.addEventListener('keydown', (e) => {
                    if (!this.currentModal) return;
                    if (e.key === 'Escape') this.closeModal();
                    if (e.key === 'ArrowLeft') this.prevSlide();
                    if (e.key === 'ArrowRight') this.nextSlide();
                });
            }

            openModal(projectId) {
                const modal = document.getElementById(`modal-${projectId}`);
                if (!modal) return;

                this.currentModal = modal;
                this.currentSlide = 0;
                this.updateCarousel();

                modal.classList.add('active');
                document.body.style.overflow = 'hidden';

                const content = modal.querySelector('.modal-content');
                content.style.transform = 'scale(0.8) translateY(50px)';
                content.style.opacity = '0';
                setTimeout(() => {
                    content.style.transition = 'all 0.5s cubic-bezier(0.34, 1.56, 0.64, 1)';
                    content.style.transform = 'scale(1) translateY(0)';
                    content.style.opacity = '1';
                }, 50);
            }

            closeModal() {
                if (!this.currentModal) return;

                this.currentModal.querySelectorAll('video').forEach(v => {
                    try { v.pause(); v.currentTime = 0; } catch(_) {}
                });

                const content = this.currentModal.querySelector('.modal-content');
                content.style.transform = 'scale(0.8) translateY(50px)';
                content.style.opacity = '0';
                setTimeout(() => {
                    this.currentModal.classList.remove('active');
                    document.body.style.overflow = '';
                    this.currentModal = null;
                    this.stopAutoSlide();
                }, 300);
            }

            nextSlide() {
                if (!this.currentModal) return;
                const slides = this.currentModal.querySelectorAll('.carousel-slide');
                this.currentSlide = (this.currentSlide + 1) % slides.length;
                this.updateCarousel();
            }

            prevSlide() {
                if (!this.currentModal) return;
                const slides = this.currentModal.querySelectorAll('.carousel-slide');
                this.currentSlide = (this.currentSlide - 1 + slides.length) % slides.length;
                this.updateCarousel();
            }

            goToSlide(index) {
                if (!this.currentModal) return;
                this.currentSlide = index;
                this.updateCarousel();
            }

            updateCarousel() {
                if (!this.currentModal) return;
                const slides = this.currentModal.querySelectorAll('.carousel-slide');
                const dots = this.currentModal.querySelectorAll('.carousel-dot');

                slides.forEach((s, i) => {
                    const isActive = i === this.currentSlide;
                    s.classList.toggle('active', isActive);

                    const vid = s.querySelector('video');
                    if (vid) {
                        try {
                            if (isActive) { vid.play().catch(()=>{}); }
                            else { vid.pause(); }
                        } catch(_) {}
                    }
                });

                dots.forEach((d, i) => d.classList.toggle('active', i === this.currentSlide));
            }

            startAutoSlide() { }
            stopAutoSlide() {
                if (this.autoSlideTimer) clearInterval(this.autoSlideTimer);
                this.autoSlideTimer = null;
            }
            resetAutoSlide() { }
        }

        document.addEventListener('DOMContentLoaded', () => { new ProjectModal(); });

        // Enhanced project card hover effects
        document.querySelectorAll('.project-card').forEach(card => {
            card.addEventListener('mouseenter', function() {
                this.style.transform = 'translateY(-20px) rotateX(10deg) scale(1.03)';
                this.style.boxShadow = '0 30px 60px rgba(0, 255, 65, 0.5), 0 0 100px rgba(0, 255, 65, 0.3)';
                const icon = this.querySelector('.project-image');
                icon.style.transform = 'scale(1.1) translateZ(20px)';
            });
            card.addEventListener('mouseleave', function() {
                this.style.transform = 'translateY(0) rotateX(0deg) scale(1)';
                this.style.boxShadow = '';
                const icon = this.querySelector('.project-image');
                icon.style.transform = 'scale(1) translateZ(0)';
            });
            
            // 3D tilt effect based on mouse position
            card.addEventListener('mousemove', function(e) {
                const rect = this.getBoundingClientRect();
                const x = e.clientX - rect.left;
                const y = e.clientY - rect.top;
                const centerX = rect.width / 2;
                const centerY = rect.height / 2;
                const rotateX = ((y - centerY) / centerY) * -10;
                const rotateY = ((x - centerX) / centerX) * 10;
                
                this.style.transform = `translateY(-20px) rotateX(${rotateX}deg) rotateY(${rotateY}deg) scale(1.03)`;
            });
        });
        
        // Parallax scrolling effect
        window.addEventListener('scroll', () => {
            const scrolled = window.pageYOffset;
            const parallaxElements = document.querySelectorAll('.hero-content, .matrix-bg');
            parallaxElements.forEach(el => {
                const speed = el.classList.contains('hero-content') ? 0.5 : 0.3;
                el.style.transform = `translateY(${scrolled * speed}px)`;
            });
        });
        
        // Magnetic button effect
        document.querySelectorAll('.cta-button, .modal-link').forEach(btn => {
            btn.addEventListener('mousemove', function(e) {
                const rect = this.getBoundingClientRect();
                const x = e.clientX - rect.left - rect.width / 2;
                const y = e.clientY - rect.top - rect.height / 2;
                const distance = Math.sqrt(x * x + y * y);
                const maxDistance = 100;
                
                if (distance < maxDistance) {
                    const pull = 1 - (distance / maxDistance);
                    this.style.transform = `translate(${x * pull * 0.3}px, ${y * pull * 0.3}px) scale(${1 + pull * 0.1})`;
                }
            });
            
            btn.addEventListener('mouseleave', function() {
                this.style.transform = 'translate(0, 0) scale(1)';
            });
        });
        
        // Text reveal on scroll with stagger
        const observerOptions = {
            threshold: 0.2,
            rootMargin: '0px 0px -100px 0px'
        };
        
        const textObserver = new IntersectionObserver((entries) => {
            entries.forEach((entry, index) => {
                if (entry.isIntersecting) {
                    setTimeout(() => {
                        entry.target.style.opacity = '1';
                        entry.target.style.transform = 'translateY(0)';
                    }, index * 100);
                }
            });
        }, observerOptions);
        
        document.querySelectorAll('.about-text p, .timeline-item, .skill-card h3').forEach(el => {
            el.style.opacity = '0';
            el.style.transform = 'translateY(30px)';
            el.style.transition = 'all 0.8s cubic-bezier(0.34, 1.56, 0.64, 1)';
            textObserver.observe(el);
        });
        
        // Create floating orbs
        function createFloatingOrbs() {
            for (let i = 0; i < 5; i++) {
                const orb = document.createElement('div');
                orb.classList.add('floating-orb');
                orb.style.width = `${Math.random() * 200 + 100}px`;
                orb.style.height = orb.style.width;
                orb.style.left = `${Math.random() * 100}%`;
                orb.style.top = `${Math.random() * 100}%`;
                orb.style.animationDelay = `${Math.random() * 5}s`;
                orb.style.animationDuration = `${Math.random() * 10 + 15}s`;
                document.body.appendChild(orb);
            }
        }
        createFloatingOrbs();
        
        // Navbar hide on scroll down, show on scroll up
        let lastScrollTop = 0;
        const navbar = document.querySelector('nav');
        
        window.addEventListener('scroll', () => {
            const scrollTop = window.pageYOffset || document.documentElement.scrollTop;
            
            if (scrollTop > lastScrollTop && scrollTop > 100) {
                // Scrolling down
                navbar.classList.add('nav-hidden');
            } else {
                // Scrolling up
                navbar.classList.remove('nav-hidden');
            }
            
            lastScrollTop = scrollTop <= 0 ? 0 : scrollTop;
        }, false);
        
        // Certificate cards stagger animation
        const certObserver = new IntersectionObserver((entries) => {
            entries.forEach((entry, index) => {
                if (entry.isIntersecting) {
                    setTimeout(() => {
                        entry.target.style.opacity = '1';
                        entry.target.style.transform = 'translateY(0) scale(1)';
                    }, index * 150);
                }
            });
        }, { threshold: 0.1 });
        
        document.querySelectorAll('.cert-card').forEach(card => {
            card.style.opacity = '0';
            card.style.transform = 'translateY(50px) scale(0.9)';
            card.style.transition = 'all 0.8s cubic-bezier(0.34, 1.56, 0.64, 1)';
            certObserver.observe(card);
        });
        
        // Ripple effect on click
        document.querySelectorAll('.project-card, .skill-card, .cert-card').forEach(card => {
            card.addEventListener('click', function(e) {
                const ripple = document.createElement('div');
                ripple.style.cssText = `
                    position: absolute;
                    border-radius: 50%;
                    background: rgba(0, 255, 65, 0.5);
                    width: 0;
                    height: 0;
                    pointer-events: none;
                `;
                
                const rect = this.getBoundingClientRect();
                const x = e.clientX - rect.left;
                const y = e.clientY - rect.top;
                
                ripple.style.left = x + 'px';
                ripple.style.top = y + 'px';
                
                this.style.position = 'relative';
                this.style.overflow = 'hidden';
                this.appendChild(ripple);
                
                ripple.animate([
                    { width: '0px', height: '0px', opacity: 1 },
                    { width: '500px', height: '500px', opacity: 0, transform: 'translate(-250px, -250px)' }
                ], {
                    duration: 600,
                    easing: 'ease-out'
                }).onfinish = () => ripple.remove();
            });
        });
        
        // Dynamic cursor effect
        const cursor = document.createElement('div');
        cursor.style.cssText = `
            position: fixed;
            width: 20px;
            height: 20px;
            border: 2px solid #00ff41;
            border-radius: 50%;
            pointer-events: none;
            z-index: 9999;
            transition: transform 0.1s ease;
            display: none;
        `;
        document.body.appendChild(cursor);
        
        const cursorGlow = document.createElement('div');
        cursorGlow.style.cssText = `
            position: fixed;
            width: 8px;
            height: 8px;
            background: #00ff41;
            border-radius: 50%;
            pointer-events: none;
            z-index: 9999;
            box-shadow: 0 0 10px #00ff41;
            display: none;
        `;
        document.body.appendChild(cursorGlow);
        
        document.addEventListener('mousemove', (e) => {
            cursor.style.display = 'block';
            cursorGlow.style.display = 'block';
            cursor.style.left = e.clientX + 'px';
            cursor.style.top = e.clientY + 'px';
            cursorGlow.style.left = (e.clientX + 6) + 'px';
            cursorGlow.style.top = (e.clientY + 6) + 'px';
        });
        
        document.querySelectorAll('a, button, .project-card, .skill-card, .cert-card').forEach(el => {
            el.addEventListener('mouseenter', () => {
                cursor.style.transform = 'scale(1.5)';
                cursor.style.borderColor = '#fff';
                cursorGlow.style.background = '#fff';
            });
            el.addEventListener('mouseleave', () => {
                cursor.style.transform = 'scale(1)';
                cursor.style.borderColor = '#00ff41';
                cursorGlow.style.background = '#00ff41';
            });
        });
        
        // Section number counter animation
        function animateCounter(element, target, duration = 2000) {
            let start = 0;
            const increment = target / (duration / 16);
            
            const timer = setInterval(() => {
                start += increment;
                if (start >= target) {
                    element.textContent = Math.floor(target);
                    clearInterval(timer);
                } else {
                    element.textContent = Math.floor(start);
                }
            }, 16);
        }
        
        // Tech stack wave animation
        document.querySelectorAll('.tech-tag').forEach((tag, index) => {
            tag.style.animation = `fadeInUp 0.5s ease ${index * 0.1}s both`;
        });
        
        // Random code snippets floating effect
        function createCodeSnippet() {
            const snippets = ['{ }', '< >', '( )', '[ ]', '/* */', '// ', '=> ', ':: '];
            const snippet = document.createElement('div');
            snippet.textContent = snippets[Math.floor(Math.random() * snippets.length)];
            snippet.style.cssText = `
                position: fixed;
                color: rgba(0, 255, 65, 0.3);
                font-family: 'Courier New', monospace;
                font-size: ${Math.random() * 20 + 10}px;
                pointer-events: none;
                z-index: 0;
            `;
            snippet.style.left = Math.random() * window.innerWidth + 'px';
            snippet.style.top = window.innerHeight + 'px';
            document.body.appendChild(snippet);
            
            const duration = Math.random() * 5000 + 5000;
            snippet.animate([
                { transform: 'translateY(0) rotate(0deg)', opacity: 0 },
                { transform: 'translateY(-50px) rotate(45deg)', opacity: 0.6 },
                { transform: `translateY(-${window.innerHeight + 100}px) rotate(${Math.random() * 360}deg)`, opacity: 0 }
            ], {
                duration: duration,
                easing: 'linear'
            }).onfinish = () => snippet.remove();
        }
        
        setInterval(createCodeSnippet, 2000);
        
        // Smooth reveal for timeline items
        const timelineObserver = new IntersectionObserver((entries) => {
            entries.forEach((entry) => {
                if (entry.isIntersecting) {
                    entry.target.style.animation = 'slideIn 0.8s ease forwards';
                }
            });
        }, { threshold: 0.2 });
        
        document.querySelectorAll('.timeline-item').forEach(item => {
            timelineObserver.observe(item);
        });
    </script>
</body>
</html>
