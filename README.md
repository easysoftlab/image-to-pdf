<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image to PDF Converter | Free, Offline & Lossless</title>
    <meta name="description" content="Free online image to PDF converter. Convert JPG, PNG, HEIC, WebP, TIFF to PDF offline, lossless, batch merge, no watermark. Works on desktop, iPhone and Android.">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
        }
        body {
            background: #f8fafc;
            color: #1e293b;
            line-height: 1.6;
        }
        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 60px 24px;
        }
        .hero {
            text-align: center;
            margin-bottom: 60px;
        }
        .hero h1 {
            font-size: 2.8rem;
            font-weight: 700;
            margin-bottom: 16px;
            color: #0f172a;
        }
        .hero p {
            font-size: 1.2rem;
            color: #64748b;
            max-width: 720px;
            margin: 0 auto 32px;
        }
        .lang-switch {
            display: flex;
            justify-content: center;
            gap: 12px;
            margin-bottom: 40px;
        }
        .lang-btn {
            padding: 8px 20px;
            border: 1px solid #e2e8f0;
            background: white;
            border-radius: 8px;
            cursor: pointer;
            font-weight: 500;
            transition: all 0.2s;
        }
        .lang-btn.active {
            background: #2563eb;
            color: white;
            border-color: #2563eb;
        }
        .lang-section {
            display: none;
        }
        .lang-section.active {
            display: block;
        }
        .section-title {
            font-size: 1.6rem;
            font-weight: 700;
            margin-bottom: 24px;
            color: #0f172a;
        }
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            margin-bottom: 60px;
        }
        .feature-card {
            background: white;
            padding: 28px;
            border-radius: 12px;
            box-shadow: 0 1px 3px rgba(0,0,0,0.05);
            border: 1px solid #e2e8f0;
        }
        .feature-card h3 {
            font-size: 1.15rem;
            font-weight: 600;
            margin-bottom: 10px;
            color: #0f172a;
        }
        .feature-card p {
            color: #64748b;
            font-size: 0.95rem;
        }
        .formats-section, .settings-section {
            background: white;
            padding: 32px;
            border-radius: 12px;
            border: 1px solid #e2e8f0;
            margin-bottom: 40px;
        }
        .formats-list {
            display: flex;
            flex-wrap: wrap;
            gap: 12px;
            margin-top: 16px;
        }
        .format-tag {
            padding: 6px 14px;
            background: #eff6ff;
            color: #2563eb;
            border-radius: 20px;
            font-size: 0.9rem;
            font-weight: 500;
        }
        .settings-list {
            list-style: none;
            margin-top: 16px;
        }
        .settings-list li {
            padding: 8px 0;
            border-bottom: 1px solid #f1f5f9;
        }
        .settings-list li:last-child {
            border-bottom: none;
        }
        .download-section {
            background: linear-gradient(135deg, #1e40af 0%, #3b82f6 100%);
            color: white;
            padding: 48px;
            border-radius: 16px;
            text-align: center;
            margin-bottom: 60px;
        }
        .download-section h2 {
            font-size: 1.8rem;
            margin-bottom: 12px;
        }
        .download-section p {
            opacity: 0.9;
            margin-bottom: 32px;
        }
        .download-buttons {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            align-items: center;
        }
        .web-btn {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            padding: 14px 32px;
            background: white;
            color: #1e40af;
            text-decoration: none;
            border-radius: 10px;
            font-weight: 600;
            font-size: 1rem;
            transition: transform 0.2s;
        }
        .web-btn:hover {
            transform: translateY(-2px);
        }
        .store-badge {
            height: 52px;
            transition: transform 0.2s;
        }
        .store-badge:hover {
            transform: translateY(-2px);
        }
        .privacy-section {
            background: white;
            padding: 32px;
            border-radius: 12px;
            border: 1px solid #e2e8f0;
            margin-bottom: 40px;
        }
        .privacy-section h3 {
            margin-bottom: 12px;
            color: #0f172a;
        }
        .privacy-section p {
            color: #64748b;
        }
        .use-cases {
            margin-bottom: 60px;
        }
        .use-cases ul {
            list-style: none;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 12px;
        }
        .use-cases li {
            padding: 16px 20px;
            background: white;
            border-radius: 8px;
            border: 1px solid #e2e8f0;
        }
        footer {
            text-align: center;
            padding: 32px 24px;
            color: #94a3b8;
            font-size: 0.9rem;
            border-top: 1px solid #e2e8f0;
        }
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2rem;
            }
            .download-section {
                padding: 32px 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="hero">
            <h1>Image to PDF Converter</h1>
            <p>Free, offline, lossless image to PDF conversion with batch processing. No uploads, no watermarks, works on every device.</p>
            
            <div class="lang-switch">
                <button class="lang-btn active" onclick="switchLang('en')">English</button>
                <button class="lang-btn" onclick="switchLang('de')">Deutsch</button>
            </div>
        </div>

        <!-- English Version -->
        <div id="en" class="lang-section active">
            <h2 class="section-title">Key Features</h2>
            <div class="features-grid">
                <div class="feature-card">
                    <h3>100% Local & Offline</h3>
                    <p>All conversion runs directly in your browser. Your images are never uploaded to any server — maximum privacy and security.</p>
                </div>
                <div class="feature-card">
                    <h3>Lossless Image Quality</h3>
                    <p>Original JPG files are embedded losslessly. No compression, no quality loss, every pixel stays exactly as your original.</p>
                </div>
                <div class="feature-card">
                    <h3>Batch Conversion</h3>
                    <p>Add multiple images at once. Merge all images into one single PDF, or generate a separate PDF file for every image.</p>
                </div>
                <div class="feature-card">
                    <h3>Flexible Page Settings</h3>
                    <p>Choose A4 page size, auto orientation that matches your image, and adjustable margins for perfect layout.</p>
                </div>
                <div class="feature-card">
                    <h3>No Watermark & Free</h3>
                    <p>Completely free to use with no hidden costs, no file limits, no registration required and no watermarks on output files.</p>
                </div>
                <div class="feature-card">
                    <h3>Cross-Platform Support</h3>
                    <p>Works on Windows, macOS, Linux, iPhone and Android. No installation needed — just open the website in any modern browser.</p>
                </div>
            </div>

            <h2 class="section-title">Supported Image Formats</h2>
            <div class="formats-section">
                <p>Convert all common image formats to PDF in one tool:</p>
                <div class="formats-list">
                    <span class="format-tag">JPG / JPEG</span>
                    <span class="format-tag">PNG</span>
                    <span class="format-tag">WebP</span>
                    <span class="format-tag">TIFF / TIF</span>
                    <span class="format-tag">HEIC</span>
                    <span class="format-tag">BMP</span>
                    <span class="format-tag">GIF</span>
                </div>
            </div>

            <h2 class="section-title">Output & Conversion Settings</h2>
            <div class="settings-section">
                <ul class="settings-list">
                    <li><strong>Output mode:</strong> Merge into one PDF / Separate PDF per image</li>
                    <li><strong>Page size:</strong> A4 (210 × 297 mm), auto-fit image size</li>
                    <li><strong>Orientation:</strong> Auto (matches image aspect ratio)</li>
                    <li><strong>Margins:</strong> Normal (15 mm), customizable</li>
                    <li><strong>Image quality:</strong> Lossless (keep original quality)</li>
                    <li><strong>File name:</strong> Custom output file name</li>
                </ul>
            </div>

            <div class="download-section">
                <h2>Get Started — It's Free</h2>
                <p>Use the web version instantly, or install the desktop app from Microsoft Store.</p>
                <div class="download-buttons">
                    <a href="https://images-to-pdf-tool.pages.dev/" target="_blank" class="web-btn">
                        🌐 Open Free Web Version
                    </a>
                    <!-- Replace the href below with your actual Microsoft Store product link -->
                    <a href="https://www.microsoft.com/store/apps/" target="_blank" rel="noopener">
                        <img src="https://get.microsoft.com/images/en-us%20dark.svg" alt="Get it from Microsoft" class="store-badge">
                    </a>
                </div>
            </div>

            <h2 class="section-title">Use Cases</h2>
            <div class="use-cases">
                <ul>
                    <li>Convert photos and scans to PDF for archiving</li>
                    <li>Merge multiple screenshots into one document</li>
                    <li>Convert iPhone HEIC photos to PDF</li>
                    <li>Create PDF documents from image files</li>
                    <li>Batch convert large JPG files offline</li>
                    <li>Prepare documents for printing and sharing</li>
                </ul>
            </div>

            <div class="privacy-section">
                <h3>Privacy First — Your Images Stay On Your Device</h3>
                <p>This tool runs entirely in your web browser using client-side technology. No images, files or personal data are sent to any external server. Everything is processed locally on your device, so your files remain private and secure.</p>
            </div>
        </div>

        <!-- German Version -->
        <div id="de" class="lang-section">
            <h2 class="section-title">Hauptfunktionen</h2>
            <div class="features-grid">
                <div class="feature-card">
                    <h3>100 % lokal & offline</h3>
                    <p>Die gesamte Umwandlung läuft direkt in Ihrem Browser. Ihre Bilder werden niemals auf einen Server hochgeladen — maximaler Datenschutz und Sicherheit.</p>
                </div>
                <div class="feature-card">
                    <h3>Verlustlose Bildqualität</h3>
                    <p>Originale JPG-Dateien werden verlustfrei eingebettet. Keine Kompression, kein Qualitätsverlust, jedes Pixel bleibt exakt wie im Original.</p>
                </div>
                <div class="feature-card">
                    <h3>Stapelverarbeitung</h3>
                    <p>Fügen Sie mehrere Bilder gleichzeitig hinzu. Führen Sie alle Bilder zu einer einzigen PDF zusammen oder erstellen Sie für jedes Bild eine separate PDF-Datei.</p>
                </div>
                <div class="feature-card">
                    <h3>Flexible Seiteneinstellungen</h3>
                    <p>Wählen Sie das A4-Seitenformat, automatische Ausrichtung passend zu Ihrem Bild und anpassbare Ränder für ein perfektes Layout.</p>
                </div>
                <div class="feature-card">
                    <h3>Ohne Wasserzeichen & kostenlos</h3>
                    <p>Vollständig kostenlos nutzbar, ohne versteckte Kosten, ohne Dateilimits, ohne Registrierung und ohne Wasserzeichen in den Ausgabedateien.</p>
                </div>
                <div class="feature-card">
                    <h3>Plattformübergreifend</h3>
                    <p>Funktioniert unter Windows, macOS, Linux, iPhone und Android. Keine Installation erforderlich — öffnen Sie einfach die Website in einem modernen Browser.</p>
                </div>
            </div>

            <h2 class="section-title">Unterstützte Bildformate</h2>
            <div class="formats-section">
                <p>Wandeln Sie alle gängigen Bildformate in einem Tool in PDF um:</p>
                <div class="formats-list">
                    <span class="format-tag">JPG / JPEG</span>
                    <span class="format-tag">PNG</span>
                    <span class="format-tag">WebP</span>
                    <span class="format-tag">TIFF / TIF</span>
                    <span class="format-tag">HEIC</span>
                    <span class="format-tag">BMP</span>
                    <span class="format-tag">GIF</span>
                </div>
            </div>

            <h2 class="section-title">Ausgabe- & Umwandlungseinstellungen</h2>
            <div class="settings-section">
                <ul class="settings-list">
                    <li><strong>Ausgabemodus:</strong> Zusammenführen zu einer PDF / Separate PDF pro Bild</li>
                    <li><strong>Seitengröße:</strong> A4 (210 × 297 mm), automatische Anpassung an das Bild</li>
                    <li><strong>Ausrichtung:</strong> Automatisch (passend zum Bildseitenverhältnis)</li>
                    <li><strong>Ränder:</strong> Normal (15 mm), individuell anpassbar</li>
                    <li><strong>Bildqualität:</strong> Verlustlos (Originalqualität bleibt erhalten)</li>
                    <li><strong>Dateiname:</strong> Frei wählbarer Ausgabedateiname</li>
                </ul>
            </div>

            <div class="download-section">
                <h2>Jetzt starten — es ist kostenlos</h2>
                <p>Nutzen Sie die Web-Version sofort oder installieren Sie die Desktop-App aus dem Microsoft Store.</p>
                <div class="download-buttons">
                    <a href="https://images-to-pdf-tool.pages.dev/" target="_blank" class="web-btn">
                        🌐 Kostenlose Web-Version öffnen
                    </a>
                    <!-- Ersetzen Sie den href unten durch Ihren tatsächlichen Microsoft Store Link -->
                    <a href="https://www.microsoft.com/store/apps/" target="_blank" rel="noopener">
                        <img src="https://get.microsoft.com/images/de-de%20dark.svg" alt="Jetzt bei Microsoft erhalten" class="store-badge">
                    </a>
                </div>
            </div>

            <h2 class="section-title">Anwendungsfälle</h2>
            <div class="use-cases">
                <ul>
                    <li>Fotos und Scans zur Archivierung in PDF umwandeln</li>
                    <li>Mehrere Screenshots zu einem Dokument zusammenfügen</li>
                    <li>iPhone-HEIC-Fotos in PDF konvertieren</li>
                    <li>PDF-Dokumente aus Bilddateien erstellen</li>
                    <li>Stapelweise Umwandlung großer JPG-Dateien offline</li>
                    <li>Dokumente für Druck und Austausch vorbereiten</li>
                </ul>
            </div>

            <div class="privacy-section">
                <h3>Datenschutz an erster Stelle — Ihre Bilder bleiben auf Ihrem Gerät</h3>
                <p>Dieses Tool läuft vollständig in Ihrem Webbrowser mittels clientseitiger Technologie. Keine Bilder, Dateien oder personenbezogenen Daten werden an externe Server gesendet. Alles wird lokal auf Ihrem Gerät verarbeitet, sodass Ihre Dateien privat und sicher bleiben.</p>
            </div>
        </div>

        <footer>
            <p>Image to PDF Converter · Powered by HaiBo · All processing happens locally in your browser</p>
        </footer>
    </div>

    <script>
        function switchLang(lang) {
            document.querySelectorAll('.lang-section').forEach(el => el.classList.remove('active'));
            document.querySelectorAll('.lang-btn').forEach(el => el.classList.remove('active'));
            document.getElementById(lang).classList.add('active');
            event.target.classList.add('active');
            document.documentElement.lang = lang;
        }
    </script>
</body>
</html>
