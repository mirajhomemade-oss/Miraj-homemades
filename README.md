# Miraj-homemades
<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Miraj Homemade - शुद्ध देशी घी और खांड के चने के लड्डू</title>
    <style>
        *, *::before, *::after {
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #faf6f0;
            color: #3e342f;
            line-height: 1.6;
        }

        /* Top Notification Bar */
        .promo-bar {
            background-color: #7a1d1d;
            color: #ffffff;
            text-align: center;
            padding: 8px 10px;
            font-size: 14px;
            font-weight: bold;
            letter-spacing: 1px;
        }

        /* Header / Brand Area */
        header {
            background-color: #ffffff;
            text-align: center;
            padding: 30px 15px;
            border-bottom: 3px solid #d4af37;
        }

        .brand-logo {
            font-size: 32px;
            font-weight: 800;
            color: #7a1d1d;
            margin: 0;
            letter-spacing: 1.5px;
            text-transform: uppercase;
        }

        .brand-tagline {
            font-size: 16px;
            font-style: italic;
            color: #b58924;
            margin: 5px 0 0 0;
            font-weight: 600;
        }

        /* Hero Banner Section */
        .hero {
            background-color: #f3ede2;
            text-align: center;
            padding: 60px 20px;
            border-bottom: 1px solid #e3dac9;
        }

        .hero h1 {
            color: #7a1d1d;
            font-size: 28px;
            margin: 0 0 15px 0;
        }

        .hero p {
            font-size: 18px;
            max-width: 600px;
            margin: 0 auto 25px auto;
            color: #5c4f46;
        }

        .cta-btn {
            display: inline-block;
            background-color: #25d366;
            color: white;
            text-decoration: none;
            padding: 15px 30px;
            font-size: 18px;
            font-weight: bold;
            border-radius: 50px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.15);
            transition: background 0.3s ease;
        }

        .cta-btn:hover {
            background-color: #128c7e;
        }

        /* Content Container */
        .container {
            max-width: 800px;
            margin: 40px auto;
            padding: 0 20px;
        }

        /* Main Sections Layout */
        .section-title {
            text-align: center;
            color: #7a1d1d;
            font-size: 24px;
            margin-bottom: 30px;
            position: relative;
            padding-bottom: 10px;
        }

        .section-title::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 60px;
            height: 3px;
            background-color: #d4af37;
        }

        /* Sticker Presentation Area */
        .sticker-gallery {
            text-align: center;
            margin-bottom: 40px;
            background: #ffffff;
            padding: 20px;
            border-radius: 8px;
            border: 1px solid #e3dac9;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
        }
        
        .sticker-placeholder {
            display: inline-block;
            width: 260px;
            background: #fffdf9;
            border: 2px solid #d4af37;
            border-radius: 8px;
            padding: 15px;
            margin: 15px;
            vertical-align: top;
            box-shadow: 0 4px 8px rgba(0,0,0,0.05);
        }
        
        .sticker-round {
            border-radius: 50%;
            width: 220px;
            height: 220px;
            margin: 0 auto 15px auto;
            border: 4px double #7a1d1d;
            background: #7a1d1d;
            color: white;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 10px;
        }
        
        .sticker-square {
            width: 220px;
            height: 220px;
            margin: 0 auto 15px auto;
            border: 3px solid #b58924;
            background: #fffbe6;
            color: #3e342f;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 10px;
        }

        .about-box {
            background-color: #ffffff;
            padding: 30px;
            border-radius: 8px;
            border: 1px solid #e3dac9;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
            text-align: center;
            margin-bottom: 40px;
        }

        /* Pricing Table Styling */
        .price-table {
            width: 100%;
            background-color: #ffffff;
            border-collapse: collapse;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
            border: 1px solid #e3dac9;
            margin-bottom: 25px;
        }

        .price-table th {
            background-color: #7a1d1d;
            color: #ffffff;
            padding: 15px;
            font-size: 16px;
            text-align: center;
        }

        .price-table td {
            padding: 15px;
            text-align: center;
            border-bottom: 1px solid #f3ede2;
            font-size: 16px;
        }

        .price-table tr:last-child td {
            border-bottom: none;
        }

        .price-table tr:nth-child(even) {
            background-color: #fefcf9;
        }

        /* Order Info Note Cards */
        .info-grid {
            display: table;
            width: 100%;
            margin-bottom: 40px;
        }

        .info-card {
            display: table-cell;
            width: 50%;
            background-color: #fff8ee;
            border: 1px solid #f1e3ce;
            padding: 20px;
            border-radius: 8px;
            vertical-align: top;
        }

        .info-card:first-child {
            border-right: none;
            border-top-right-radius: 0;
            border-bottom-right-radius: 0;
        }

        .info-card:last-child {
            border-top-left-radius: 0;
            border-bottom-left-radius: 0;
        }

        .info-card h4 {
            margin: 0 0 10px 0;
            color: #b58924;
            font-size: 16px;
        }

        .info-card p {
            margin: 0;
            font-size: 14px;
            color: #5c4f46;
        }

        /* Benefits Grid alternative using standard table layout */
        .benefits-table {
            width: 100%;
            border-collapse: separate;
            border-spacing: 0 15px;
            margin-bottom: 40px;
        }

        .benefit-row {
            background-color: #ffffff;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
            border: 1px solid #e3dac9;
        }

        .benefit-icon-cell {
            width: 70px;
            text-align: center;
            vertical-align: top;
            padding: 20px;
            font-size: 35px;
            background-color: #fefcf9;
            border-top-left-radius: 8px;
            border-bottom-left-radius: 8px;
            border-right: 1px solid #f3ede2;
        }

        .benefit-content-cell {
            padding: 20px;
            vertical-align: top;
            border-top-right-radius: 8px;
            border-bottom-right-radius: 8px;
        }

        .benefit-title {
            font-size: 18px;
            font-weight: bold;
            color: #7a1d1d;
            margin: 0 0 5px 0;
        }

        .benefit-desc {
            font-size: 14px;
            color: #5c4f46;
            margin: 0;
        }

        /* Product Details / Specifications Card */
        .details-card {
            background: linear-gradient(135deg, #7a1d1d 0%, #4a1010 100%);
            color: #ffffff;
            padding: 35px 30px;
            border-radius: 12px;
            margin-bottom: 40px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }

        .details-card h3 {
            color: #d4af37;
            margin-top: 0;
            font-size: 22px;
            text-align: center;
            margin-bottom: 20px;
        }

        .details-list {
            list-style: none;
            padding: 0;
            margin: 0;
        }

        .details-list li {
            padding: 10px 0;
            border-bottom: 1px solid rgba(255,255,255,0.1);
            font-size: 15px;
        }

        .details-list li:last-child {
            border-bottom: none;
        }

        .details-list strong {
            color: #d4af37;
        }

        /* Contact and Footer */
        .contact-box {
            background-color: #ffffff;
            padding: 30px;
            border-radius: 8px;
            border: 2px dashed #b58924;
            text-align: center;
            margin-bottom: 40px;
        }

        .contact-info {
            font-size: 18px;
            margin: 15px 0;
            color: #3e342f;
        }

        footer {
            background-color: #3e342f;
            color: #f3ede2;
            text-align: center;
            padding: 25px 15px;
            font-size: 14px;
            border-top: 5px solid #d4af37;
        }

        footer p {
            margin: 5px 0;
        }

        /* Mobile adaptation */
        @media (max-width: 600px) {
            .benefit-icon-cell {
                display: block;
                width: 100%;
                text-align: left;
                padding: 15px 20px 5px 20px;
                border-right: none;
            }
            .benefit-content-cell {
                display: block;
                width: 100%;
                padding: 5px 20px 20px 20px;
            }
            .info-grid, .info-card {
                display: block;
                width: 100%;
            }
            .info-card:first-child {
                border-right: 1px solid #f1e3ce;
                border-bottom: none;
                border-radius: 8px 8px 0 0;
            }
            .info-card:last-child {
                border-radius: 0 0 8px 8px;
            }
        }
    </style>
</head>
<body>

    <!-- Top Promotion -->
    <div class="promo-bar">
        🌸 शुद्धता और स्वाद का अनोखा संगम - 100% होममेड 🌸
    </div>

    <!-- Header Brand Section -->
    <header>
        <h1 class="brand-logo">MIRAJ HOMEMADE</h1>
        <div class="brand-tagline">Taste of Mother's Love</div>
    </header>

    <!-- Main Hero Banner -->
    <div class="hero">
        <h1>माँ के हाथों का स्वाद, संपूर्ण शुद्धता के साथ!</h1>
        <p>शुद्ध देशी घी, खांड और प्रीमियम ड्राई फ्रूट्स (काजू, बादाम, मगज) से बने पारंपरिक चने के स्पेशल लड्डू।</p>
        <a href="https://wa.me/919416750587?text=Hi,%20mujhe%20Miraj%20Homemade%20Ladoo%20ka%20price%20list%20dekhkar%20order%20krna%20hai" class="cta-btn" target="_blank">
            📲 WhatsApp पर ऑर्डर करें
        </a>
    </div>

    <!-- Main Website Container -->
    <div class="container">
        
        <!-- Our Packaging & Brand Sticker Showcase -->
        <h2 class="section-title">हमारी शुद्धता की पहचान (Our Branding)</h2>
        <div class="sticker-gallery">
            <p style="margin-top:0; color:#5c4f46; font-size:15px;">हमारे डिब्बों और जार पर आपको शुद्धता के भरोसे के साथ यह आकर्षक स्टिकर मिलते हैं:</p>
            
            <!-- Round Sticker Model -->
            <div class="sticker-placeholder">
                <div class="sticker-round">
                    <span style="font-size:10px; opacity:0.9;">🌸 शुद्धता और स्वाद का संगम 🌸</span>
                    <strong style="font-size:18px; margin:5px 0; letter-spacing:1px;">MIRAJ</strong>
                    <strong style="font-size:16px; margin-bottom:5px; letter-spacing:1.5px;">HOMEMADE</strong>
                    <span style="font-size:9px; opacity:0.85; text-align:center;">देशी घी के चने के लड्डू</span>
                    <span style="font-size:9px; margin-top:8px; color:#d4af37;">★ 100% शुद्ध ★</span>
                </div>
                <strong style="color:#7a1d1d; font-size:15px;">क्लासिक राउंड स्टिकर</strong>
                <p style="font-size:12px; margin:5px 0 0 0; color:#5c4f46;">जार के ढक्कन और गोल डिब्बों के लिए बेहतरीन पारंपरिक लुक।</p>
            </div>

            <!-- Square Sticker Model -->
            <div class="sticker-placeholder">
                <div class="sticker-square">
                    <strong style="font-size:16px; color:#7a1d1d; margin-bottom:2px;">MIRAJ HOMEMADE</strong>
                    <span style="font-size:10px; font-style:italic; color:#b58924; margin-bottom:10px;">Taste of Mother's Love</span>
                    <div style="background:#7a1d1d; color:white; font-size:11px; padding:3px 8px; border-radius:4px; margin-bottom:8px;">
                        चने के स्पेशल लड्डू
                    </div>
                    <span style="font-size:9px; color:#5c4f46; text-align:center;">• शुद्ध देशी घी और खांड से निर्मित<br>• प्रीमियम ड्राई फ्रूट्स भरपूर</span>
                </div>
                <strong style="color:#7a1d1d; font-size:15px;">आधुनिक चौकोर स्टिकर</strong>
                <p style="font-size:12px; margin:5px 0 0 0; color:#5c4f46;">डिब्बे के सामने के हिस्से के लिए एक साफ और प्रीमियम मॉडर्न डिजाइन।</p>
            </div>
        </div>

        <!-- Pricing & Ordering Section -->
        <h2 class="section-title">वजन और मूल्य सूची (Price List)</h2>
        
        <table class="price-table">
            <thead>
                <tr>
                    <th>लड्डू का वजन (Weight)</th>
                    <th>कीमत (Price)</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td><strong>250 ग्राम (250gm)</strong></td>
                    <td>₹200</td>
                </tr>
                <tr>
                    <td><strong>500 ग्राम (500gm)</strong></td>
                    <td>₹380</td>
                </tr>
                <tr>
                    <td><strong>1 किलोग्राम (1kg)</strong></td>
                    <td><strong>₹700</strong></td>
                </tr>
            </tbody>
        </table>

        <!-- Order Information Delivery & Payment -->
        <div class="info-grid">
            <div class="info-card">
                <h4>📦 पूरे भारत में डिलीवरी (Pan India)</h4>
                <p>हमारा हर आदेश फ्रेश तैयार किया जाता है, इसलिए आपको <strong>एडवांस ऑर्डर</strong> करना होगा। ऑर्डर बुक होने के बाद <strong>5 से 7 दिन के अंदर</strong> पूरे भारत में आप तक डिलीवर कर दिया जाएगा। (डिलीवरी चार्ज बेहद सामान्य रहेगा)।</p>
            </div>
            <div class="info-card">
                <h4>💳 सुरक्षित और आसान पेमेंट</h4>
                <p>ऑर्डर की पुष्टि के लिए आपको सिर्फ <strong>50% एडवांस पेमेंट</strong> करनी होगी। बाकी बची हुई 50% पेमेंट आप <strong>डि理वरी मिलने के बाद (After Delivery)</strong> आसानी से कर सकते हैं।</p>
            </div>
        </div>
        
        <!-- About Us Section -->
        <h2 class="section-title">हमारे बारे में (Our Story)</h2>
        <div class="about-box">
            <p style="margin:0; font-size: 16px; color: #5c4f46;">
                <strong>MIRAJ HOMEMADE</strong> की शुरुआत मेरी माँ के हाथों के पारंपरिक स्वाद और शुद्धता को हर घर तक पहुँचाने के लिए हुई है। हम सिवानी (हरियाणा) में पूरी स्वच्छता और प्रीमियम क्वालिटी के साथ इन लड्डुओं को तैयार करते हैं। इसमें बाज़ार की मिठाइयों की तरह कोई मिलावट नहीं होती, बल्कि माँ का प्यार और सेहत का ख्याल होता है।
            </p>
        </div>

        <!-- Benefits Section -->
        <h2 class="section-title">हमारे लड्डू खाने के बेहतरीन फायदे</h2>
        
        <table class="benefits-table">
            <!-- Benefit 1 -->
            <tr class="benefit-row">
                <td class="benefit-icon-cell">💪</td>
                <td class="benefit-content-cell">
                    <div class="benefit-title">भरपूर ऊर्जा (Energy Boost)</div>
                    <div class="benefit-desc">भुने चने और ड्राई फ्रूट्स प्रोटीन और गुड फैट्स का बेस्ट सोर्स हैं, जो दिनभर की सुस्ती और शारीरिक कमजोरी को दूर करते हैं।</div>
                </td>
            </tr>
            <!-- Benefit 2 -->
            <tr class="benefit-row">
                <td class="benefit-icon-cell">🍃</td>
                <td class="benefit-content-cell">
                    <div class="benefit-title">सफेद चीनी से मुक्ति (No Refined Sugar)</div>
                    <div class="benefit-desc">हम हानिकारक चीनी की जगह पारंपरिक देसी खांड का उपयोग करते हैं, जो सेहत के लिए पूरी तरह सुरक्षित और पचाने में आसान है।</div>
                </td>
            </tr>
            <!-- Benefit 3 -->
            <tr class="benefit-row">
                <td class="benefit-icon-cell">🦴</td>
                <td class="benefit-content-cell">
                    <div class="benefit-title">हड्डियों और जोड़ों की मजबूती</div>
                    <div class="benefit-desc">शुद्ध देशी घी जोड़ों में चिकनाई (Lubrication) बनाए रखता है और हड्डियों को अंदर से मजबूत बनाता है।</div>
                </td>
            </tr>
            <!-- Benefit 4 -->
            <tr class="benefit-row">
                <td class="benefit-icon-cell">🧠</td>
                <td class="benefit-content-cell">
                    <div class="benefit-title">दिमाग और याददाश्त के लिए उत्तम</div>
                    <div class="benefit-desc">लड्डू में शामिल प्रीमियम बादाम और मगज के बीज (Melon Seeds) मानसिक विकास और याददाश्त तेज करने में मदद करते हैं।</div>
                </td>
            </tr>
            <!-- Benefit 5 -->
            <tr class="benefit-row">
                <td class="benefit-icon-cell">🌱</td>
                <td class="benefit-content-cell">
                    <div class="benefit-title">100% केमिकल मुक्त (No Artificial Colors)</div>
                    <div class="benefit-desc">हमारे किसी भी उत्पाद में कोई आर्टिफिशियल... कलर, फ्लेवर या प्रिजर्वेटिव नहीं मिलाया जाता। यह बच्चों और बुजुर्गों के लिए पूरी तरह पौष्टिक है।</div>
                </td>
            </tr>
        </table>

        <!-- Product Details -->
        <div class="details-card">
            <h3>उत्पाद की विशेषताएँ (Product Specifications)</h3>
            <ul class="details-list">
                <li><strong>मुख्य सामग्री:</strong> भुना हुआ चना, शुद्ध देशी घी, पारंपरिक खांड, काजू, बादाम, मगज के बीज।</li>
                <li><strong>शुद्धता गारंटी:</strong> 100% घर पर निर्मित (Homemade), कोई केमिकल या प्रिजर्वेटिव नहीं।</li>
                <li><strong>उपयुक्तता:</strong> हर उम्र के लोगों के लिए स्वास्थ्यवर्धक और स्वादिष्ट।</li>
                <li><strong>पैकिंग साइज:</strong> 250 ग्राम, 500 ग्राम और 1 किलोग्राम के पैक उपलब्ध।</li>
            </ul>
        </div>

        <!-- Ordering and Contact Section -->
        <h2 class="section-title">अभी संपर्क और आदेश करें</h2>
        <div class="contact-box">
            <p style="font-size: 16px; margin-top:0; color:#5c4f46;">ताज़ा और शुद्ध लड्डू घर बैठे मंगवाने के लिए नीचे दिए नंबर पर कॉल या व्हाट्सएप करें:</p>
            <div class="contact-info">📞 <strong>फ़ोन नंबर:</strong> 9416750587</div>
            <div class="contact-info">📍 <strong>पता:</strong> ढाणी धीरज, सिवानी (हरियाणा) - 127046</div>
            <p style="margin-bottom:0; margin-top:20px;">
                <a href="https://wa.me/919416750587?text=Hi,%20mujhe%20Miraj%20Homemade%20Ladoo%20order%20krna%20hai" class="cta-btn" style="background-color:#075E54; font-size:16px; padding:10px 20px;">
                    💬 डायरेक्ट व्हाट्सएप मेसेज भेजें
                </a>
            </p>
        </div>

    </div>

    <!-- Website Footer -->
    <footer>
        <p>© 2026 MIRAJ HOMEMADE. All Rights Reserved.</p>
        <p>स्वाद माँ के हाथों का, भरोसा शुद्धता का।</p>
    </footer>

</body>
</html>
