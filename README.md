<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Muhammad - Full Stack MERN Developer</title>
    <style>
        /* --- General Page Styles --- */
        body {
            margin: 0;
            padding: 0;
            background-color: #111116; /* Dark Background */
            color: #e0e0e0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vh;
        }

        .container {
            width: 100%;
            max-width: 800px; /* Limits width on big screens */
            padding: 20px;
            text-align: center;
            box-sizing: border-box;
        }

        /* Typography */
        h1 { color: #f4d03f; margin-bottom: 10px; font-size: 2.5rem; }
        h2, h3 { color: #61dafb; border-bottom: 2px solid #333; padding-bottom: 10px; margin-top: 30px; }
        p { line-height: 1.6; font-size: 1.1rem; }
        b { color: #f4d03f; }
        
        /* Links & Badges */
        a { text-decoration: none; transition: transform 0.2s; display: inline-block; }
        a:hover { transform: scale(1.1); }
        .badges img { margin: 5px; height: 28px; }

        /* HR Line */
        hr { border: 0; height: 1px; background: #333; margin: 30px 0; }

        /* --- SVG Animation Container --- */
        .scene-container {
            width: 100%;
            max-width: 500px;
            height: auto;
            margin: 20px auto;
            position: relative;
        }

        svg {
            width: 100%;
            height: auto;
            overflow: visible;
        }

        /* --- Animation Keyframes (Same as before) --- */
        @keyframes float { 0%, 100% { transform: translateY(0); } 50% { transform: translateY(-5px); } }
        @keyframes headBob { 0%, 100% { transform: rotate(0deg); } 50% { transform: rotate(2deg) translateY(2px); } }
        @keyframes blink { 0%, 96%, 100% { transform: scaleY(1); } 98% { transform: scaleY(0.1); } }
        @keyframes tap { 0%, 100% { transform: rotate(0deg); } 50% { transform: rotate(-5deg); } }
        @keyframes bubbleFloat { 0%, 100% { transform: translateY(0); } 50% { transform: translateY(-8px); } }
        @keyframes glow { 0%, 100% { opacity: 0.6; } 50% { opacity: 1; } }

        /* Applying Animations */
        .char-body { animation: float 4s ease-in-out infinite; }
        .char-head { transform-origin: center bottom; animation: headBob 5s ease-in-out infinite; }
        .eye { transform-origin: center; animation: blink 4s infinite; }
        .hand { transform-origin: bottom right; animation: tap 2s ease-in-out infinite; }
        .code-bubble { animation: bubbleFloat 3s ease-in-out infinite; }
        .logo-glow { animation: glow 2s infinite; }

        /* Specific text alignments */
        .text-left { text-align: left; display: inline-block; width: 100%; }
        .contribution-item { background: #1a1a21; padding: 15px; border-radius: 8px; margin-bottom: 10px; text-align: left; border-left: 4px solid #f4d03f; }

    </style>
</head>
<body>

    <div class="container">
        
        <h1>⚡ HI, I'M MUHAMMAD! ⚡</h1>

        <a href="https://git.io/typing-svg">
            <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=25&pause=1000&color=F53D7F&center=true&vCenter=true&width=550&lines=FULL+STACK+MERN+DEVELOPER;AGENTIC+AI+ENGINEER;PYTHON+%26+GEN+AI+EXPERT;BUILDING+INTELLIGENT+APPS" alt="Typing SVG" style="max-width: 100%;" />
        </a>

        <br><br>

        <div class="scene-container">
            <svg viewBox="0 0 500 400" xmlns="http://www.w3.org/2000/svg">
                <path d="M100,200 Q150,100 250,120 Q350,140 400,200 Q450,300 350,350 Q250,380 150,350 Q50,300 100,200" fill="#2c2c34" opacity="0.5"/>
                <g class="char-body">
                    <path d="M180,350 L180,280 Q180,250 210,240 L290,240 Q320,250 320,280 L320,350 Z" fill="#f4d03f"/> 
                    <path d="M220,240 L280,240 L280,280 L220,280 Z" fill="#5dade2"/> 
                    <g class="char-head">
                        <rect x="235" y="220" width="30" height="25" fill="#f5cba7"/>
                        <ellipse cx="250" cy="190" rx="45" ry="50" fill="#f5cba7"/>
                        <circle cx="208" cy="190" r="10" fill="#f5cba7"/>
                        <circle cx="292" cy="190" r="10" fill="#f5cba7"/>
                        <path d="M200,180 Q250,120 300,180 Q305,150 290,140 Q250,100 210,140 Q190,150 200,180" fill="#1a1a1a"/>
                        <path d="M240,140 Q260,120 280,145" fill="none" stroke="#2c3e50" stroke-width="2"/>
                        <g class="eye">
                            <circle cx="235" cy="190" r="4" fill="#1a1a1a"/>
                            <circle cx="265" cy="190" r="4" fill="#1a1a1a"/>
                        </g>
                        <path d="M245,215 Q250,210 255,215" fill="none" stroke="#c0392b" stroke-width="2" stroke-linecap="round"/>
                        <ellipse cx="230" cy="205" rx="5" ry="3" fill="#e74c3c" opacity="0.2"/>
                        <ellipse cx="270" cy="205" rx="5" ry="3" fill="#e74c3c" opacity="0.2"/>
                    </g>
                    <g class="hand">
                        <path d="M260,240 Q280,210 290,230 L280,260 Z" fill="#f5cba7" stroke="#e6b0aa" stroke-width="1
