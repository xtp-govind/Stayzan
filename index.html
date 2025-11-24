<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Game Page</title>
    <link rel="manifest" href="manifest.json">
    <!-- Font Awesome CDN -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        /* CSS Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0 0 80px 0; /* Only bottom padding for navigation */
            background: #f0f2f5; /* Lighter background for better contrast */
            min-height: 100vh;
            color: #333;
            -webkit-user-select: none;
           -moz-user-select: none;    /* Firefox */
           -ms-user-select: none;     /* IE/Edge */
           user-select: none;  
            
        }

        .container {
            width: 100%;
            max-width: 100%;
            margin: 0;
            background: white;
            min-height: calc(100vh - 80px);
        }

        /* --- MODIFIED HEADER SECTION --- */
        .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 20px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            box-shadow: 0 4px 12px rgba(0,0,0,0.15);
            flex-wrap: wrap; /* Allows items to wrap on smaller screens */
            gap: 15px;
        }

        .balance-section {
            display: flex;
            align-items: center;
            gap: 15px;
        }

        .balance-info .label {
            font-size: 0.8em;
            margin-bottom: 2px;
            opacity: 0.9;
            font-weight: 300;
        }

        .balance-info .amount {
            font-size: 1.8em;
            font-weight: 700;
        }
        
        .balance-info .user-id {
            font-size: 0.75em;
            opacity: 0.8;
            margin-top: 2px;
        }

        .reload-icon {
            cursor: pointer;
            font-size: 1.2em;
            padding: 10px;
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.15);
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .reload-icon:hover {
            background: rgba(255, 255, 255, 0.3);
            transform: rotate(180deg);
        }

        .reload-icon.spinning {
            animation: spin 1s linear infinite;
        }

        @keyframes spin {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }

        .actions-section {
            display: flex;
            gap: 10px;
        }

        .actions-section button {
            display: flex;
            align-items: center;
            gap: 8px;
            padding: 10px 20px;
            border: none;
            border-radius: 25px;
            font-size: 0.9em;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
            text-transform: uppercase;
            letter-spacing: 0.5px;
            color: white;
        }

        .recharge-btn {
            background: linear-gradient(135deg, #28a745 0%, #218838 100%);
            box-shadow: 0 4px 15px rgba(40, 167, 69, 0.3);
        }

        .withdraw-btn {
            background: linear-gradient(135deg, #ffc107 0%, #e0a800 100%);
            box-shadow: 0 4px 15px rgba(255, 193, 7, 0.3);
        }

        .actions-section button:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 20px rgba(0,0,0,0.2);
        }
        /* --- END OF MODIFIED HEADER SECTION --- */


        /* Rewards Section */
        .rewards-section {
            display: flex;
            justify-content: space-around;
            padding: 20px;
            gap: 15px;
            background: #f8f9fa;
        }

        .reward-button {
            display: flex;
            flex-direction: column;
            align-items: center;
            cursor: pointer;
            padding: 20px;
            border-radius: 15px;
            background: white;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease;
            flex: 1;
            border: 2px solid transparent;
        }

        .reward-button:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.15);
            border-color: #667eea;
        }

        .reward-button .icon {
            width: 60px;
            height: 60px;
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            margin-bottom: 10px;
            font-size: 1.8em;
            color: white;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
        }

        .task-reward .icon {
            background: linear-gradient(135deg, #ff9800 0%, #f57c00 100%);
        }

        .check-in .icon {
            background: linear-gradient(135deg, #4caf50 0%, #388e3c 100%);
        }

        .reward-button .text {
            font-size: 0.9em;
            font-weight: 600;
            color: #333;
        }

        /* Ad Slider Section */
        .ad-slider-section {
            padding: 20px;
            background: white;
        }

        .slider-container {
            position: relative;
            width: 100%;
            height: 150px;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
        }

        .slider-wrapper {
            display: flex;
            width: 500%;
            height: 100%;
            transition: transform 0.5s ease-in-out;
        }

        .slide {
            width: 20%;
            height: 100%;
            position: relative;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 1.2em;
            font-weight: bold;
        }

        .slide:nth-child(1) {
            background: linear-gradient(135deg, #ff9a9e 0%, #fecfef 100%);
        }

        .slide:nth-child(2) {
            background: linear-gradient(135deg, #a8edea 0%, #fed6e3 100%);
        }

        .slide:nth-child(3) {
            background: linear-gradient(135deg, #ffecd2 0%, #fcb69f 100%);
        }

        .slide:nth-child(4) {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }

        .slide:nth-child(5) {
            background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
        }

        .slide img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .slide-content {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            text-align: center;
            z-index: 2;
        }

        .dots-container {
            display: flex;
            justify-content: center;
            margin-top: 15px;
            gap: 8px;
        }

        .dot {
            width: 12px;
            height: 12px;
            border-radius: 50%;
            background: #ddd;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .dot.active {
            background: #667eea;
            transform: scale(1.2);
        }

        .dot:hover {
            background: #999;
        }

/* Tutorial Section */
.tutorial-section {
    padding: 20px;
    background: #f8f9fa;
}

.tutorial-list {
    display: flex;
    flex-direction: column;
    gap: 12px;
}

.tutorial-item {
    display: flex;
    align-items: center;
    padding: 15px;
    background: white;
    border-radius: 12px;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.07);
    text-decoration: none;
    color: #333;
    transition: all 0.3s ease;
}

.tutorial-item:hover {
    transform: translateY(-3px) scale(1.02);
    box-shadow: 0 8px 25px rgba(0, 0, 0, 0.1);
    color: #667eea;
}

.tutorial-item .icon {
    font-size: 1.3em;
    color: #667eea;
    margin-right: 15px;
    width: 25px;
    text-align: center;
}

.tutorial-item .text {
    flex-grow: 1; /* Takes up available space */
    font-weight: 600;
    font-size: 0.95em;
}

.tutorial-item .arrow {
    font-size: 0.9em;
    color: #aaa;
    transition: color 0.3s ease;
}

.tutorial-item:hover .arrow {
    color: #667eea;
}

/* Coming Soon style */
.coming-soon {
    position: relative;
    cursor: not-allowed; /* Click disable feel */
    overflow: hidden;
}

.coming-soon::after {
    content: "Coming Soon";
    position: absolute;
    bottom: 60px;
    left: 50%;
    transform: translateX(-50%);
    background: rgba(0, 0, 0, 0.7);
    color: #fff;
    font-size: 14px;
    padding: 3px 8px;
    border-radius: 6px;
    pointer-events: none;
}

/* Blur effect on image */
.coming-soon img {
    filter: grayscale(80%) blur(1px);
    opacity: 0.8;
}

        /* Bottom Navigation */
        .bottom-nav {
            position: fixed;
            bottom: 0;
            left: 0;
            right: 0;
            background: white;
            border-top: 1px solid #e9ecef;
            padding: 10px 0;
            z-index: 1000;
            box-shadow: 0 -2px 10px rgba(0, 0, 0, 0.1);
        }

        .nav-container {
            display: flex;
            justify-content: space-around;
            align-items: center;
            max-width: 100%;
        }

        .nav-item {
            display: flex;
            flex-direction: column;
            align-items: center;
            cursor: pointer;
            padding: 8px 12px;
            border-radius: 10px;
            transition: all 0.3s ease;
            text-decoration: none;
            color: #666;
            min-width: 60px;
        }

        .nav-item:hover {
            background: #f8f9fa;
            color: #667eea;
            transform: translateY(-2px);
        }

        .nav-item.active {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            box-shadow: 0 4px 15px rgba(102, 126, 234, 0.3);
        }

        .nav-item i {
            font-size: 1.3em;
            margin-bottom: 4px;
        }

        .nav-item .nav-text {
            font-size: 0.75em;
            font-weight: 600;
        }

        /* Success message */
        .success-message {
            position: fixed;
            top: 20px;
            right: 20px;
            background: linear-gradient(135deg, #28a745 0%, #20c997 100%);
            color: white;
            padding: 12px 18px;
            border-radius: 10px;
            transform: translateX(120%);
            transition: transform 0.4s ease-in-out;
            z-index: 1000;
            font-size: 0.9em;
            box-shadow: 0 4px 15px rgba(40, 167, 69, 0.3);
        }

        .success-message.show {
            transform: translateX(0);
        }

        /* Loading state */
        .loading {
            opacity: 0.6;
            pointer-events: none;
        }

        /* Responsive */
        @media (max-width: 480px) {
            .header {
                flex-direction: column;
                align-items: stretch; /* Stretch items to full width */
            }
            
            .actions-section {
                justify-content: space-between; /* Distribute buttons evenly */
            }
            
            .actions-section button {
                flex-grow: 1; /* Allow buttons to grow */
                justify-content: center;
            }

            .rewards-section, .ad-slider-section, .games-section {
                padding: 15px;
            }

            .slider-container {
                height: 120px;
            }
        }
        
/* --- START: CLEAN & MODERN POPUP STYLES --- */
/* Overlay */
.popup-overlay {
    position: fixed;
    top: 0; left: 0;
    width: 100%; height: 100%;
    background: rgba(0, 0, 0, 0.55);
    z-index: 2000;
    display: flex;
    justify-content: center;
    align-items: center;
    opacity: 0; visibility: hidden;
    transition: opacity 0.3s ease, visibility 0.3s ease;
}
.popup-overlay.show {
    opacity: 1;
    visibility: visible;
}

/* Popup Content */
.popup-content {
    position: relative;
    background: #fff;
    width: 90%;
    max-width: 360px;
    text-align: center;
    border-radius: 18px;
    padding: 28px 22px;
    box-shadow: 0 12px 40px rgba(0, 0, 0, 0.12);
    transform: scale(0.92);
    opacity: 0;
    transition: transform 0.35s cubic-bezier(0.175, 0.885, 0.32, 1.275), opacity 0.3s ease;
}
.popup-overlay.show .popup-content {
    transform: scale(1);
    opacity: 1;
}

/* Close Button */
.popup-close-btn {
    position: absolute;
    top: 14px; right: 14px;
    width: 32px; height: 32px;
    background: #f4f4f4;
    border-radius: 50%;
    display: flex; justify-content: center; align-items: center;
    font-size: 1.2em;
    color: #777;
    cursor: pointer;
    transition: background-color 0.2s, color 0.2s, transform 0.2s;
}
.popup-close-btn:hover {
    background-color: #e2e2e2;
    color: #222;
    transform: scale(1.1);
}

/* Title + Subtitle */
.popup-title {
    font-size: 1.7em;
    font-weight: 700;
    margin-bottom: 6px;
    color: #2c3e50;
}
.popup-subtitle {
    font-size: 0.9em;
    color: #666;
    margin-bottom: 18px;
}

/* Text */
.popup-text {
    font-size: 1em;
    color: #444;
    margin-bottom: 15px;
    line-height: 1.45;
}

/* Buttons */
.popup-link {
    display: flex; align-items: center; justify-content: center;
    gap: 10px;
    background: #3498db;
    color: #fff;
    padding: 13px 18px;
    border-radius: 12px;
    text-decoration: none;
    font-weight: 600;
    font-size: 1em;
    margin-top: 10px;
    transition: all 0.25s ease;
    box-shadow: 0 4px 15px rgba(52, 152, 219, 0.25);
}
.popup-link:last-of-type {
    background: #2ecc71;
    box-shadow: 0 4px 15px rgba(46, 204, 113, 0.25);
}
.popup-link:hover {
    transform: translateY(-3px);
    box-shadow: 0 6px 22px rgba(0,0,0,0.15);
}
.popup-link i {
    font-size: 1.15em;
}

.highlight {
    background: linear-gradient(45deg, #27ae60, #2ecc71);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    font-weight: 700;
}

/* --- START: IMPROVED SLIDE-UP OVERLAY STYLES --- */

/* बैकग्राउंड ओवरले */
.overlay-container {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.6); /* थोड़ा और गहरा बैकग्राउंड */
    z-index: 3000;
    display: flex;
    justify-content: center;
    align-items: flex-end;
    opacity: 0;
    visibility: hidden;
    transition: opacity 0.4s ease, visibility 0.4s ease;
}

.overlay-container.show {
    opacity: 1;
    visibility: visible;
}

/* मुख्य पैनल */
.overlay-panel {
    background: #ffffff;
    width: 100%;
    max-height: 85vh;
    border-top-left-radius: 24px; /* ज्यादा कर्व कॉर्नर */
    border-top-right-radius: 24px;
    box-shadow: 0 -10px 40px rgba(0, 0, 0, 0.2);
    display: flex;
    flex-direction: column;
    transform: translateY(100%);
    transition: transform 0.4s cubic-bezier(0.4, 0, 0.2, 1); /* स्मूथ प्रोफेशनल एनीमेशन */
}

.overlay-container.show .overlay-panel {
    transform: translateY(0);
}

/* पैनल का हेडर */
.overlay-header {
    position: relative; /* ग्रैब हैंडल के लिए */
    padding: 20px 20px 15px 20px;
    text-align: center; /* टाइटल को सेंटर में रखें */
    border-bottom: 1px solid #f0f0f0;
    flex-shrink: 0;
}

/* ग्रैब हैंडल (पैनल के ऊपर छोटी लाइन) */
.overlay-header::before {
    content: '';
    position: absolute;
    top: 8px;
    left: 50%;
    transform: translateX(-50%);
    width: 40px;
    height: 4px;
    background-color: #dcdcdc;
    border-radius: 2px;
}

/* टाइटल */
.overlay-title {
    font-size: 1.25em;
    font-weight: 700;
    color: #2c3e50; /* गहरा, सॉफ्ट रंग */
    margin-top: 10px; /* ग्रैब हैंडल के लिए जगह */
}

/* क्लोज बटन */
.overlay-close-btn {
    position: absolute;
    top: 16px;
    right: 16px;
    background: #f1f3f5;
    border: none;
    width: 34px;
    height: 34px;
    border-radius: 50%;
    font-size: 1.6em;
    color: #868e96;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    line-height: 1;
    transition: all 0.2s ease;
}

.overlay-close-btn:hover {
    background: #e9ecef;
    color: #495057;
    transform: rotate(90deg); /* घूमने वाला इफ़ेक्ट */
}

/* कंटेंट एरिया */
.overlay-content {
    padding: 10px 20px 20px 20px;
    overflow-y: auto;
    line-height: 1.7;
    color: #495057;
}

/* सब-हेडिंग (h4) */
.overlay-content h4 {
    display: flex;
    align-items: center;
    font-size: 1.1em;
    color: #34495e;
    margin-top: 20px;
    margin-bottom: 10px;
}

.overlay-content h4 .fas {
    margin-right: 10px;
    color: #667eea;
}

.overlay-content p {
    margin-bottom: 15px;
    padding-left: 32px; /* आइकॉन के साथ अलाइन करने के लिए */
}

/* --- START: UPDATED TWO-LINE LIST STYLES --- */

/* लिस्ट स्टाइल */
.overlay-content ul {
    list-style: none;
    padding-left: 0;
    margin-bottom: 15px;
}

.overlay-content ul li {
    display: flex; /* आइकॉन और कंटेंट को अगल-बगल रखें */
    align-items: flex-start; /* ऊपर से अलाइन करें */
    margin-bottom: 20px; /* आइटम्स के बीच ज्यादा स्पेस */
}

.overlay-content ul li .fas {
    width: 20px;
    margin-right: 15px; /* आइकॉन और कंटेंट के बीच स्पेस */
    color: #27ae60;
    text-align: center;
    flex-shrink: 0;
    margin-top: 5px; /* आइकॉन को थोड़ा नीचे करें */
    font-size: 1.1em;
}

/* कंटेंट का कंटेनर (टाइटल + डिटेल) */
.overlay-content .li-content {
    display: flex;
    flex-direction: column; /* टाइटल और डिटेल को ऊपर-नीचे रखें */
}

/* लिस्ट का टाइटल (ऊपर की लाइन) */
.overlay-content .li-title {
    font-weight: 700; /* बोल्ड */
    font-size: 1em;
    color: #34495e;
    margin-bottom: 3px; /* टाइटल और डिटेल के बीच हल्का स्पेस */
}

/* लिस्ट की डिटेल (नीचे की लाइन) */
.overlay-content .li-detail {
    font-size: 0.9em;
    color: #7f8c8d; /* हल्का रंग */
    line-height: 1.5;
}

/* हाईलाइट बॉक्स के अंदर की लिस्ट के लिए */
.highlight-box ul li .fas {
    color: #667eea;
}

.highlight-box ul li .li-title {
    color: #555;
}

.highlight-box ul li .li-detail {
    color: #666;
}

/* --- END: UPDATED TWO-LINE LIST STYLES --- */


/* खास जानकारी वाला बॉक्स */
.highlight-box {
    background-color: #f8f9fa;
    border-left: 4px solid #667eea;
    padding: 15px 20px;
    margin: 20px 0;
    border-radius: 8px;
}

.highlight-box p {
    padding-left: 0;
    font-weight: 600;
    color: #333;
    margin-bottom: 10px;
}

.highlight-box ul li .fas {
    color: #667eea; /* बॉक्स के अंदर आइकॉन का रंग बदलें */
}

/* --- END: IMPROVED SLIDE-UP OVERLAY STYLES --- */
/* --- IMPROVED SECTION TITLE STYLE --- */

.section-title {
    display: flex; /* आइकॉन और टेक्स्ट को एक लाइन में लाने के लिए */
    align-items: center; /* वर्टिकली सेंटर में करने के लिए */
    justify-content: center; /* हॉरिजॉन्टली सेंटर में करने के लिए */
    font-size: 1.3em; /* फॉन्ट साइज थोड़ा बड़ा करें */
    font-weight: 700; /* फॉन्ट को बोल्ड करें */
    color: #34495e; /* गहरा, सॉफ्ट रंग */
    margin-bottom: 20px; /* नीचे थोड़ा ज्यादा स्पेस */
    padding: 10px 0; /* ऊपर-नीचे पैडिंग */
    background-color: #f8f9fa; /* हल्का बैकग्राउंड कलर (अगर सेक्शन का रंग अलग है) */
    border-bottom: 1px solid #e9ecef; /* नीचे एक हल्की लाइन */
    border-top: 1px solid #e9ecef; /* ऊपर भी एक हल्की लाइन */
}

.section-title i.fas {
    margin-right: 12px; /* आइकॉन और टेक्स्ट के बीच स्पेस */
    font-size: 0.9em; /* आइकॉन को टेक्स्ट के सापेक्ष थोड़ा छोटा करें */
    color: #667eea; /* आइकॉन को एक आकर्षक रंग दें */
}

/* --- START: JOIN TELEGRAM POPUP STYLES (NO BLUR) --- */
.popup-overlay-no-blur {
    position: fixed;
    top: 0; left: 0;
    width: 100%; height: 100%;
    background: rgba(0, 0, 0, 0.6); /* सिर्फ गहरा बैकग्राउंड, कोई ब्लर नहीं */
    z-index: 9999;
    display: flex;
    justify-content: center;
    align-items: center;
    opacity: 0; visibility: hidden;
    transition: opacity 0.3s ease, visibility 0.3s ease;
}
.popup-overlay-no-blur.show {
    opacity: 1;
    visibility: visible;
}

.popup-overlay-no-blur .popup-content {
    position: relative;
    background: #fff;
    width: 90%;
    max-width: 380px;
    text-align: center;
    border-radius: 18px;
    padding: 30px 25px;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.15);
    transform: scale(0.9);
    opacity: 0;
    transition: transform 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275), opacity 0.3s ease;
}
.popup-overlay-no-blur.show .popup-content {
    transform: scale(1);
    opacity: 1;
}

.popup-overlay-no-blur .popup-close-btn {
    position: absolute;
    top: 12px; right: 12px;
    width: 30px; height: 30px;
    background: #f1f1f1;
    border-radius: 50%;
    display: flex; justify-content: center; align-items: center;
    font-size: 1.2em;
    color: #888;
    cursor: pointer;
    transition: all 0.2s;
}
.popup-overlay-no-blur .popup-close-btn:hover {
    background-color: #e7e7e7;
    color: #333;
    transform: scale(1.1);
}

.popup-overlay-no-blur .popup-title {
    font-size: 1.8em;
    font-weight: 700;
    margin-bottom: 8px;
    color: #333;
}
.popup-overlay-no-blur .popup-subtitle {
    font-size: 1em;
    color: #777;
    margin-bottom: 20px;
}

.popup-overlay-no-blur .popup-text {
    font-size: 1em;
    color: #555;
    margin-bottom: 25px;
    line-height: 1.5;
}

.popup-overlay-no-blur .popup-link {
    display: flex; align-items: center; justify-content: center;
    gap: 12px;
    background: #0088cc;
    color: #fff;
    padding: 14px 20px;
    border-radius: 12px;
    text-decoration: none;
    font-weight: 600;
    font-size: 1.05em;
    margin-top: 12px;
    transition: all 0.25s ease;
    box-shadow: 0 4px 15px rgba(0, 136, 204, 0.2);
}
.popup-overlay-no-blur .popup-link:last-of-type {
    background: #27ae60;
    box-shadow: 0 4px 15px rgba(39, 174, 96, 0.25);
}
.popup-overlay-no-blur .popup-link:hover {
    transform: translateY(-3px);
    box-shadow: 0 6px 20px rgba(0,0,0,0.1);
}
.popup-overlay-no-blur .popup-link i {
    font-size: 1.2em;
}

.popup-overlay-no-blur .highlight {
    font-weight: 700;
    color: #27ae60;
}
/* --- END: JOIN TELEGRAM POPUP STYLES --- */

/* --- नया: लाइव इवेंट सेक्शन का स्टाइल --- */
.live-event-section {
    padding: 20px;
    background: white;
    margin-top: -20px; /* Ad Slider और इसके बीच का गैप कम करने के लिए */
    cursor: pointer;
}


.live-event-header {
    display: flex;
    align-items: center;
    font-weight: 600;
    color: #e74c3c; /* लाल रंग */
    margin-bottom: 15px;
    font-size: 1em;
}

.live-dot {
    width: 10px;
    height: 10px;
    background-color: #e74c3c;
    border-radius: 50%;
    margin-right: 10px;
    animation: pulse 1.5s infinite;
}

@keyframes pulse {
    0% { box-shadow: 0 0 0 0 rgba(231, 76, 60, 0.7); }
    70% { box-shadow: 0 0 0 10px rgba(231, 76, 60, 0); }
    100% { box-shadow: 0 0 0 0 rgba(231, 76, 60, 0); }
}

.live-event-slider-container {
    position: relative;
    width: 100%;
    height: 300px; /* आप ऊंचाई बदल सकते हैं */
    border-radius: 15px;
    overflow: hidden;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
}

.live-event-slider-wrapper {
    display: flex;
    height: 100%;
    transition: transform 0.5s ease-in-out;
}

.live-event-slide {
    min-width: 100%; /* स्लाइड को पूरी चौड़ाई दें */
    height: 100%;
}

.live-event-slide img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.live-event-dots-container {
    display: flex;
    justify-content: center;
    margin-top: 15px;
    gap: 8px;
}

/* --- START: PREMIUM ACTION POPUP STYLES --- */
.premium-overlay {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.65); /* थोड़ा और गहरा बैकग्राउंड */
    z-index: 4000;
    display: flex;
    justify-content: center;
    align-items: flex-end;
    opacity: 0;
    visibility: hidden;
    transition: opacity 0.3s ease, visibility 0.3s ease;
}

.premium-overlay.show {
    opacity: 1;
    visibility: visible;
}

.premium-panel {
    background: #f0f2f5; /* पैनल का बैकग्राउंड */
    width: 100%;
    border-top-left-radius: 24px;
    border-top-right-radius: 24px;
    padding: 10px 10px 20px 10px; /* ऊपर कम, नीचे ज़्यादा पैडिंग */
    transform: translateY(100%);
    transition: transform 0.35s cubic-bezier(0.4, 0, 0.2, 1);
}

.premium-overlay.show .premium-panel {
    transform: translateY(0);
}

.premium-panel-title {
    text-align: center;
    font-size: 1.1em;
    font-weight: 700;
    color: #333;
    padding: 10px 0 20px 0;
}

.premium-button {
    display: flex;
    align-items: center;
    width: 100%;
    padding: 15px;
    border: none;
    background: #ffffff;
    border-radius: 16px; /* ज़्यादा गोल किनारे */
    margin-bottom: 12px;
    cursor: pointer;
    text-align: left;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.05);
    position: relative;
    overflow: hidden; /* बैज के लिए */
}

.premium-button:active {
    transform: scale(0.98);
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.08);
}

.premium-button-icon {
    width: 50px;
    height: 50px;
    border-radius: 12px;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-right: 15px;
    flex-shrink: 0;
}

.premium-button-icon i {
    font-size: 1.5em; /* बड़े आइकन */
    color: #ffffff;
}

/* अलग-अलग बटनों के लिए रंग */
.icon-recharge { background: linear-gradient(135deg, #28a745, #218838); }
.icon-p2p-buy { background: linear-gradient(135deg, #17a2b8, #138496); }
.icon-withdraw { background: linear-gradient(135deg, #ffc107, #e0a800); }
.icon-p2p-sell { background: linear-gradient(135deg, #dc3545, #c82333); }


.premium-button-text {
    display: flex;
    flex-direction: column;
}

.button-title {
    font-size: 1.1em;
    font-weight: 700;
    color: #2c3e50;
}

.button-subtitle {
    font-size: 0.85em;
    color: #7f8c8d;
}

.premium-new-badge {
    position: absolute;
    top: -1px;
    right: -1px;
    background: #e74c3c;
    color: white;
    font-size: 0.7em;
    font-weight: bold;
    padding: 12px 12px 12px 12px;
    border-bottom-left-radius: 15px;
    border-top-right-radius: 16px;
    text-transform: uppercase;
}

.premium-new-badge i {
    font-size: 0.8em;
    transform: rotate(0deg);
}
/* --- END: PREMIUM ACTION POPUP STYLES --- */


    </style>
</head>
<body>

    <div class="container">
        <!-- Header Section -->
        <div class="header">
            <div class="balance-section">
                <div class="balance-info">
                    <div class="label">Balance</div>
                    <div class="amount">₹<span id="balance">0.00</span></div>
                    <div class="user-id">ID: <span id="unique_id">XYZ</span></div>
                </div>
                <div class="reload-icon" onclick="refreshBalance()" title="Refresh Balance">
                    <i class="fas fa-sync-alt"></i>
                </div>
            </div>
            <div class="actions-section">
                <button class="recharge-btn" onclick="handleRecharge()">
                    <i class="fas fa-plus"></i> Recharge
                </button>
                <button class="withdraw-btn" onclick="handleWithdraw()">
                    <i class="fas fa-minus"></i> Withdraw
                </button>
            </div>
        </div>

        <!-- Rewards Section -->
        <div class="rewards-section">
            <div class="reward-button task-reward"  onclick='location.href ="task_rewards"'>
                <div class="icon">
                    <i class="fas fa-gift"></i>
                </div>
                <div class="text">Task reward</div>
            </div>
            <div class="reward-button check-in" onclick='location.href ="invite.php"'>
                 <div class="icon">
              <i class="fas fa-users"></i>
            </div>
             <div class="text">Refer</div> 
</div>

          
        </div>

        <!-- Ad Slider Section -->
        <div class="ad-slider-section">
            <div class="slider-container">
                <div class="slider-wrapper" id="sliderWrapper">
                    <div class="slide">
                        <div class="slide-content">
                            <h3>🎉 Welcome Bonus!</h3>
                            <p>Get ₹10 on first deposit</p>
                        </div>
                    </div>
                    <div class="slide">
                        <div class="slide-content">
                            <h3>📊 Trade & Earn</h3>
                            <p>Daily orders available</p>
                        </div>
                    </div>
                    <div class="slide">
                        <div class="slide-content">
                            <h3>💰 Return Offer</h3>
                            <p>Up to 20% return daily</p>
                        </div>
                    </div>
                    <div class="slide">
                        <div class="slide-content">
                            <h3>🏆 VIP Program</h3>
                            <p>Exclusive rewards for VIP</p>
                        </div>
                    </div>
                    <div class="slide">
                        <div class="slide-content">
                            <h3>🎁 Refer & Earn</h3>
                            <p>₹50 for each successfull referral</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="dots-container">
                <span class="dot active" onclick="currentSlide(1)"></span>
                <span class="dot" onclick="currentSlide(2)"></span>
                <span class="dot" onclick="currentSlide(3)"></span>
                <span class="dot" onclick="currentSlide(4)"></span>
                <span class="dot" onclick="currentSlide(5)"></span>
            </div>
        </div>

<!-- नया: लाइव इवेंट सेक्शन -->
<div class="live-event-section" onclick="location.href='event.php'">
    <div class="live-event-header">
        <span class="live-dot"></span>
        Live Event: 01-10-25 to 15-10-25
    </div>
    <div class="live-event-slider-container">
        <div class="live-event-slider-wrapper" id="liveEventSliderWrapper">
            <!-- यहाँ इवेंट के पोस्टर आएंगे -->
            <div class="live-event-slide"><img src="https://stayzan.com/logo/1.jpg" alt="Event Poster 1"></div>
            <div class="live-event-slide"><img src="https://stayzan.com/logo/2.jpg" alt="Event Poster 2"></div>
            <div class="live-event-slide"><img src="https://stayzan.com/logo/3.jpg" alt="Event Poster 3"></div>
            <div class="live-event-slide"><img src="https://stayzan.com/logo/4.jpg" alt="Event Poster 4"></div>
            <div class="live-event-slide"><img src="https://stayzan.com/logo/5.jpg" alt="Event Poster 5"></div>
        </div>
    </div>
    <div class="live-event-dots-container" id="liveEventDotsContainer">
        <!-- डॉट्स यहाँ JavaScript से बनेंगे -->
    </div>
</div>

<!-- Tutorial Section -->
<div class="tutorial-section">
<div class="section-title">
    <i class="fas fa-book-open"></i> Guides & Tutorials
</div>

    <div class="tutorial-list">
        <!-- हर आइटम अब जावास्क्रिप्ट फंक्शन `openTutorial` को कॉल करेगा -->
        <div class="tutorial-item" onclick="openTutorial('how-to-buy')">
            <i class="fas fa-shopping-cart icon"></i>
            <span class="text">How to Buy Order</span>
            <i class="fas fa-chevron-right arrow"></i>
        </div>
        <div class="tutorial-item" onclick="openTutorial('what-is-stayzan')">
            <i class="fas fa-info-circle icon"></i>
            <span class="text">What is Stayzan?</span>
            <i class="fas fa-chevron-right arrow"></i>
        </div>
        <div class="tutorial-item" onclick="openTutorial('what-is-lee-coin')">
            <i class="fas fa-coins icon"></i>
            <span class="text">What is Lee Coin?</span>
            <i class="fas fa-chevron-right arrow"></i>
        </div>
        <div class="tutorial-item" onclick="openTutorial('other-guides')">
            <i class="fas fa-question-circle icon"></i>
            <span class="text">Other Guides</span>
            <i class="fas fa-chevron-right arrow"></i>
        </div>
    </div>
</div>



    </div>

    <!-- Bottom Navigation Bar -->
    <div class="bottom-nav">
        <div class="nav-container">
            <div class="nav-item active" onclick="navigateTo('home')">
                <i class="fas fa-home"></i>
                <div class="nav-text">Home</div>
            </div>
            <div class="nav-item" onclick="navigateTo('order')">
                <i class="fas fa-list-alt"></i>
                <div class="nav-text">Order</div>
            </div>

<div class="nav-item" onclick="navigateTo('team')">
    <i class="fas fa-users"></i> <!-- टीम के लिए आइकॉन -->
    <div class="nav-text">Team</div>
</div>


            <div class="nav-item" onclick="navigateTo('profile')">
                <i class="fas fa-user"></i>
                <div class="nav-text">My</div>
            </div>
        </div>
    </div>

    <!-- Success Message -->
    <div id="successMessage" class="success-message">
        Balance updated successfully!
    </div>


<!-- START: SLIDE-UP OVERLAY PANEL -->
<div id="tutorialOverlay" class="overlay-container">
    <div class="overlay-panel">
        <div class="overlay-header">
            <h3 id="overlayTitle" class="overlay-title">Tutorial Title</h3>
            <button class="overlay-close-btn" onclick="closeTutorial()">&times;</button>
        </div>
        <div id="overlayContent" class="overlay-content">
            <!-- यहाँ ट्यूटोरियल का कंटेंट जावास्क्रिप्ट से डाला जाएगा -->
            <p>Loading content...</p>
        </div>
    </div>
</div>
<!-- END: SLIDE-UP OVERLAY PANEL -->

<!-- START: JOIN TELEGRAM POPUP -->
<div id="joinPopup" class="popup-overlay-no-blur">
    <div class="popup-content">
        <div class="popup-close-btn" onclick="closeJoinPopup()">&times;</div>
        <h2 class="popup-title">Join Us!</h2>
        <p class="popup-subtitle">For the latest updates and premium orders.</p>
        
        <p class="popup-text">
            For daily premium orders and all important information, join our <span class="highlight">Telegram Channel</span>.
        </p>

        <a href="#" id="telegramGroupLink" class="popup-link" target="_blank">
            <i class="fab fa-telegram-plane"></i> Join Telegram Group
        </a>
        <a href="#" id="premiumChannelLink" class="popup-link" target="_blank">
            <i class="fas fa-star"></i> Join Premium Channel
        </a>
    </div>
</div>
<!-- END: JOIN TELEGRAM POPUP -->
<!-- START: PREMIUM RECHARGE POPUP -->
<div id="rechargeOptionsOverlay" class="premium-overlay" onclick="closeOptionsOverlay(event)">
    <div class="premium-panel">
        <h3 class="premium-panel-title">Recharge Options</h3>
        
        <!-- Centralized Recharge Button -->
        <button class="premium-button" onclick="location.href='recharge.php'">
            <div class="premium-button-icon icon-recharge">
                <i class="fas fa-wallet"></i>
            </div>
            <div class="premium-button-text">
                <span class="button-title">Centralized Recharge</span>
                <span class="button-subtitle">Fast & Secure UPI Payments</span>
            </div>
        </button>

        <!-- P2P Buy Button -->
        <button class="premium-button" onclick="location.href='p2p2.php'">
            <div class="premium-button-icon icon-p2p-buy">
                <i class="fas fa-users"></i>
            </div>
            <div class="premium-button-text">
                <span class="button-title">P2P Buy</span>
                <span class="button-subtitle">Buy directly from other users</span>
            </div>
            <div class="premium-new-badge">
                <i class="fas fa-star"></i>
            </div>
        </button>

    </div>
</div>
<!-- END: PREMIUM RECHARGE POPUP -->

<!-- START: PREMIUM WITHDRAWAL POPUP -->
<div id="withdrawalOptionsOverlay" class="premium-overlay" onclick="closeOptionsOverlay(event)">
    <div class="premium-panel">
        <h3 class="premium-panel-title">Withdrawal Options</h3>

        <!-- Centralized Withdrawal Button -->
        <button class="premium-button" onclick="location.href='withdrawal.php'">
            <div class="premium-button-icon icon-withdraw">
                <i class="fas fa-university"></i>
            </div>
            <div class="premium-button-text">
                <span class="button-title">Centralized Withdrawal</span>
                <span class="button-subtitle">Direct to your bank account</span>
            </div>
        </button>

        <!-- P2P Sell Button -->
        <button class="premium-button" onclick="location.href='p2p2.php'">
            <div class="premium-button-icon icon-p2p-sell">
                <i class="fas fa-people-arrows"></i>
            </div>
            <div class="premium-button-text">
                <span class="button-title">P2P Sell</span>
                <span class="button-subtitle">Sell directly to other users</span>
            </div>
            <div class="premium-new-badge">
                <i class="fas fa-star"></i>
            </div>
        </button>

    </div>
</div>
<!-- END: PREMIUM WITHDRAWAL POPUP -->

    <script>
        
let currentSlideIndex = 0;
const totalSlides = 5;

// नया कोड
let liveEventCurrentIndex = 0;
let liveEventTotalSlides = 5; // आपके द्वारा दी गई 5 तस्वीरों के आधार पर



        // Page load पर user data load करें
        document.addEventListener("DOMContentLoaded", function() {
            loadUserData();
            startAutoSlider();
            setupLiveEventSlider();
        });

// एक ग्लोबल वैरिएबल यह ट्रैक करने के लिए कि क्या डेटा पहले से लोड हो रहा है
let isFetching = false;


function loadUserData() {
    if (isFetching) {
        console.log("Already fetching data. Please wait.");
        return;
    }

    isFetching = true;

    const balanceElement = document.getElementById('balance');
    const userIdElement = document.getElementById('unique_id');
    const reloadIcon = document.querySelector('.reload-icon i');

    if (!balanceElement || !userIdElement || !reloadIcon) {
        console.error("Error: Required HTML elements not found.");
        isFetching = false; // स्थिति को रीसेट करें
        return;
    }

    // 3. आइकन को घुमाना शुरू करें
    reloadIcon.classList.add('fa-spin');

    // 4. दो प्रॉमिस बनाएं: एक डेटा लाने के लिए, दूसरा 1 सेकंड के टाइमर के लिए
    const fetchDataPromise = fetch('fetch_login_user.php').then(response => {
        if (!response.ok) {
            if (response.status === 401) {
                window.location.href = 'login.php';
            }
            throw new Error(`Network response was not ok. Status: ${response.status}`);
        }
        return response.json();
    });

    const timerPromise = new Promise(resolve => setTimeout(resolve, 1000)); // 1000ms = 1 सेकंड

    Promise.all([fetchDataPromise, timerPromise])
        .then(([data]) => { // परिणाम में केवल डेटा प्रॉमिस का डेटा लें
            if (data && data.status === 'success') {
                balanceElement.innerText = data.data.balance;
                userIdElement.innerText = data.data.unique_id;
            } else {
                console.error('Error from server:', data.message || 'Unknown server error');
                balanceElement.innerText = 'Error';
                userIdElement.innerText = 'N/A';
            }
        })
        .catch(error => {
            console.error('There was a problem with the fetch operation:', error);
            balanceElement.innerText = 'Error';
            userIdElement.innerText = 'N/A';
        })
        .finally(() => {
            // 6. सब कुछ खत्म होने के बाद, आइकन को घुमाना बंद करें और स्थिति को रीसेट करें
            reloadIcon.classList.remove('fa-spin');
            isFetching = false;
        });
}

// refreshBalance फंक्शन को बदलने की आवश्यकता नहीं है, यह वैसे ही काम करेगा
function refreshBalance() {
    loadUserData();
    setTimeout(() => {
        showSuccessMessage("Balance updated successfully!");
    }, 1000); // इसे थोड़ा बढ़ा दें ताकि यह स्पिन खत्म होने के बाद दिखे
}

// showSuccessMessage फंक्शन को भी बदलने की आवश्यकता नहीं है
function showSuccessMessage(text = "Operation successful!") {
    const message = document.getElementById('successMessage');
    message.textContent = text;
    message.classList.add('show');
    setTimeout(() => {
        message.classList.remove('show');
    }, 1000);
}



        // Slider Functions
        function currentSlide(n) {
            showSlide(currentSlideIndex = n - 1);
        }

        function showSlide(n) {
            const slider = document.getElementById('sliderWrapper');
            const dots = document.querySelectorAll('.dot');
            
            if (n >= totalSlides) currentSlideIndex = 0;
            if (n < 0) currentSlideIndex = totalSlides - 1;
            
            slider.style.transform = `translateX(-${currentSlideIndex * 20}%)`;
            
            // Update dots
            dots.forEach(dot => dot.classList.remove('active'));
            dots[currentSlideIndex].classList.add('active');
        }

        function nextSlide() {
            currentSlideIndex++;
            showSlide(currentSlideIndex);
        }

        function startAutoSlider() {
            setInterval(nextSlide, 4000); // Change slide every 4 seconds
        }

// नया फंक्शन
function setupLiveEventSlider() {
    const sliderWrapper = document.getElementById('liveEventSliderWrapper');
    const dotsContainer = document.getElementById('liveEventDotsContainer');
    if (!sliderWrapper || !dotsContainer) return;

    // डॉट्स बनाएं
    for (let i = 0; i < liveEventTotalSlides; i++) {
        const dot = document.createElement('span');
        dot.classList.add('dot');
        if (i === 0) dot.classList.add('active');
        // डॉट्स पर क्लिक करने का लॉजिक यहाँ नहीं जोड़ रहे क्योंकि पूरा सेक्शन क्लिकेबल है
        dotsContainer.appendChild(dot);
    }

    const dots = dotsContainer.querySelectorAll('.dot');

    function showLiveEventSlide(index) {
        if (index >= liveEventTotalSlides) liveEventCurrentIndex = 0;
        if (index < 0) liveEventCurrentIndex = liveEventTotalSlides - 1;
        
        sliderWrapper.style.transform = `translateX(-${liveEventCurrentIndex * 100}%)`;
        
        dots.forEach(dot => dot.classList.remove('active'));
        dots[liveEventCurrentIndex].classList.add('active');
    }

    // ऑटो-स्लाइड शुरू करें
    setInterval(() => {
        liveEventCurrentIndex++;
        showLiveEventSlide(liveEventCurrentIndex);
    }, 4000); // यह हर 3 सेकंड में बदलेगा
}


        // Bottom navigation function
        function navigateTo(page) {
            // Active state update
            document.querySelectorAll('.nav-item').forEach(item => {
                item.classList.remove('active');
            });
            event.currentTarget.classList.add('active');
            
            // Page redirection
            switch(page) {
                case 'home':
                    window.location.href = 'index.php';
                    break;
                case 'order':
                    window.location.href = 'order.php';
                    break;
                case 'team':
                    window.location.href = 'myteam.php';
                    break;
                case 'profile':
                    window.location.href = 'profile.php';
                    break;
            }
        }

        // Other button functions
        function handleRecharge() {
            document.getElementById('rechargeOptionsOverlay').classList.add('show');
        }

        function handleWithdraw() {
            document.getElementById('withdrawalOptionsOverlay').classList.add('show');
        }

          // Function to close any options overlay
        function closeOptionsOverlay(event) {
            // यदि क्लिक किया गया तत्व ओवरले है (पैनल नहीं), तो बंद करें
            if (event.target.classList.contains('premium-overlay')) {
                event.target.classList.remove('show');
            }
        }


        function handleTaskReward() {
            window.location.href = 'task_rewards.php';
        }

    

        // Touch events for mobile slider
        let startX = 0;
        let endX = 0;

        document.querySelector('.slider-container').addEventListener('touchstart', function(e) {
            startX = e.touches[0].clientX;
        });

        document.querySelector('.slider-container').addEventListener('touchend', function(e) {
            endX = e.changedTouches[0].clientX;
            handleSwipe();
        });

        function handleSwipe() {
            const threshold = 50;
            const diff = startX - endX;
            
            if (Math.abs(diff) > threshold) {
                if (diff > 0) {
                    // Swipe left - next slide
                    currentSlideIndex++;
                } else {
                    // Swipe right - previous slide
                    currentSlideIndex--;
                }
                showSlide(currentSlideIndex);
            }
        }
        

// --- START: UPDATED JAVASCRIPT ---

// --- START: UPDATED JAVASCRIPT FOR TWO-LINE LAYOUT ---

const tutorialData = {
    'how-to-buy': {
        title: 'How to Buy an Order',
        content: `
            <p>Buying an order is very simple. Just follow these steps:</p>
            <h4><i class="fas fa-shoe-prints"></i>Steps to Purchase</h4>
            <p>Follow the guide below to successfully place your order.</p>
            
            <div class="highlight-box">
                <p><strong><i class="fas fa-info-circle"></i> Please Note:</strong></p>
                <ul>
                    <li>
                        <i class="fas fa-arrow-down"></i>
                        <div class="li-content">
                            <span class="li-title">Minimum Order</span>
                            <span class="li-detail">The smallest order you can place is <strong>200 Lee Coin</strong>.</span>
                        </div>
                    </li>
                    <li>
                        <i class="fas fa-arrow-up"></i>
                        <div class="li-content">
                            <span class="li-title">Highest Order</span>
                            <span class="li-detail">The largest order you can place is <strong>100,000 Lee Coin</strong>.</span>
                        </div>
                    </li>
                    <li>
                        <i class="fas fa-equals"></i>
                        <div class="li-content">
                            <span class="li-title">Value</span>
                            <span class="li-detail">1 Lee Coin is equal to <strong>₹1</strong>.</span>
                        </div>
                    </li>
                </ul>
            </div>
        `
    },
    'what-is-stayzan': {
        title: 'Why Choose Stayzan?',
        content: `
            <p>Stayzan is a platform where you can earn easily. Here are our key advantages:</p>
            <ul>
                <li>
                    <i class="fas fa-id-card-alt"></i>
                    <div class="li-content">
                        <span class="li-title">No KYC Needed</span>
                        <span class="li-detail">You don't need to provide any identity verification.</span>
                    </div>
                </li>
                <li>
                    <i class="fas fa-university"></i>
                    <div class="li-content">
                        <span class="li-title">No Bank Information</span>
                        <span class="li-detail">No need to give bank card or NetBanking details.</span>
                    </div>
                </li>
                <li>
                    <i class="fas fa-user-plus"></i>
                    <div class="li-content">
                        <span class="li-title">No Need to Add Beneficiaries</span>
                        <span class="li-detail">Freely transfer funds without adding contacts.</span>
                    </div>
                </li>
                <li>
                    <i class="fas fa-child"></i>
                    <div class="li-content">
                        <span class="li-title">No Age Limit</span>
                        <span class="li-detail">Anyone of any age can use the platform.</span>
                    </div>
                </li>
                <li>
                    <i class="fas fa-infinity"></i>
                    <div class="li-content">
                        <span class="li-title">No Amount or Card Limits</span>
                        <span class="li-detail">Transact any amount with no restrictions.</span>
                    </div>
                </li>
                <li>
                    <i class="fas fa-hand-holding-usd"></i>
                    <div class="li-content">
                        <span class="li-title">Lifetime Earnings</span>
                        <span class="li-detail">Get a 0.4% rebate from your subordinates for life.</span>
                    </div>
                </li>
                <li>
                    <i class="fas fa-exchange-alt"></i>
                    <div class="li-content">
                        <span class="li-title">Instant Fund Transfer</span>
                        <span class="li-detail">Transfer funds between your own cards at will.</span>
                    </div>
                </li>
            </ul>
        `
    },

    'what-is-lee-coin': {
        title: 'How Do You Earn?',
        content: `
            <p>Earning on Stayzan is straightforward and profitable.</p>
            <h4><i class="fas fa-shopping-cart"></i> Earn by "Buying"</h4>
            <p>Through the "Buy" process, you will get a <strong>2.5% to 5.5% profit</strong> for each transaction.</p>
            
            <h4><i class="fas fa-money-bill-wave"></i> How to Withdraw?</h4>
            <p>You can then withdraw your profit to your bank card by opening the <strong>UPI Sell switch</strong>.</p>
            
            <h4><i class="fas fa-rocket"></i> How to Start?</h4>
            <p>You can start with a very small "buy" amount and repeat it many times a day. By doing this, your daily income can become very considerable.</p>
        `
    },
    'other-guides': {
        title: 'Other Guides',
        content: `
            <p>Here you can find information about other features of our platform.</p>
            <h4><i class="fas fa-wallet"></i> Withdrawing Money</h4>
            <p>To withdraw your earnings, go to the 'Withdraw' section, enter the amount, and choose your preferred withdrawal method.</p>
            <h4><i class="fas fa-headset"></i> Customer Support</h4>
            <p>If you face any issues, our customer support team is available 24/7. You can contact us via the 'Support' section in your profile.</p>
        `
    }
};

// ... (बाकी का जावास्क्रिप्ट कोड वैसा ही रहेगा)


const overlay = document.getElementById('tutorialOverlay');
const overlayTitle = document.getElementById('overlayTitle');
const overlayContent = document.getElementById('overlayContent');

// ओवरले खोलने का फंक्शन
function openTutorial(tutorialKey) {
    if (tutorialData[tutorialKey]) {
        const data = tutorialData[tutorialKey];
        overlayTitle.innerText = data.title;
        overlayContent.innerHTML = data.content;
        overlay.classList.add('show');
        document.body.style.overflow = 'hidden'; // बैकग्राउंड को स्क्रॉल होने से रोकें
    }
}

// ओवरले बंद करने का फंक्शन
function closeTutorial() {
    overlay.classList.remove('show');
    document.body.style.overflow = 'auto'; // बैकग्राउंड स्क्रॉलिंग वापस चालू करें
}

// अगर यूजर ओवरले के बाहर (काले हिस्से पर) क्लिक करे तो भी बंद हो जाए
overlay.addEventListener('click', function(event) {
    if (event.target === overlay) {
        closeTutorial();
    }
});

// --- END: SLIDE-UP PANEL JAVASCRIPT what-is-lee-coin        
  
document.addEventListener("contextmenu", function(e) {
    e.preventDefault();
  });

  // Disable copy shortcut (Ctrl+C)
  document.addEventListener("copy", function(e) {
    e.preventDefault();
  });      
  
// --- START: UPDATED TELEGRAM JOIN POPUP SCRIPT ---

document.addEventListener("DOMContentLoaded", function() {
    // अपने टेलीग्राम लिंक यहाँ डालें
    const telegramGroupLink = 'https://t.me/officialStayzan'; // <--- अपना ग्रुप लिंक यहाँ डालें
    const premiumChannelLink = 'https://t.me/inviteorder_bot'; // <--- अपना चैनल लिंक यहाँ डालें

    const joinPopup = document.getElementById('joinPopup');
    const telegramGroupBtn = document.getElementById('telegramGroupLink');
    const premiumChannelBtn = document.getElementById('premiumChannelLink');

// पॉपअप खोलने का फंक्शन
    window.openJoinPopup = function() {
        if (!joinPopup) return;
        
        // लिंक सेट करें
        telegramGroupBtn.href = telegramGroupLink;
        premiumChannelBtn.href = premiumChannelLink;
        
        // पॉपअप दिखाएँ
        joinPopup.classList.add('show');
        document.body.style.overflow = 'hidden'; // बैकग्राउंड स्क्रॉलिंग रोकें
    }

    // पॉपअप बंद करने का फंक्शन
    window.closeJoinPopup = function() {
        if (!joinPopup) return;
        
        joinPopup.classList.remove('show');
        document.body.style.overflow = 'auto';
        
        sessionStorage.setItem('popupClosed', 'true');
    }


    if (joinPopup) {
        joinPopup.addEventListener('click', function(event) {

            if (event.target === joinPopup) {
                closeJoinPopup();
            }
        });
    }

    if (sessionStorage.getItem('popupClosed') !== 'true') {
        setTimeout(openJoinPopup, 500); // 0.5 सेकंड का इंतज़ार
    }
});

// --- END: UPDATED TELEGRAM JOIN POPUP SCRIPT ---


</script>

</body>
</html>
