<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VOID Utilities 5.0 - VOID Tools</title>
    <link rel="stylesheet" href="../css/style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <nav class="navbar">
        <div class="nav-brand">
            <i class="fas fa-terminal"></i> VOID Tools
        </div>
        <ul class="nav-links">
            <li><a href="../index.html">Home</a></li>
            <li><a href="../index.html#tools">Tools</a></li>
            <li><a href="../index.html#about">About</a></li>
            <li><a href="../index.html#contact">Contact</a></li>
        </ul>
        <div class="hamburger">
            <i class="fas fa-bars"></i>
        </div>
    </nav>

    <div class="detail-page">
        <a href="../index.html#tools" class="back-link">
            <i class="fas fa-arrow-left"></i> Back to Tools
        </a>
        
        <h1><i class="fas fa-tools"></i> VOID Utilities 5.0</h1>
        <p class="subtitle">30+ system utilities for system info, network tools, and security</p>
        
        <div class="detail-section">
            <h2>Overview</h2>
            <p>VOID Utilities 5.0 is a comprehensive system utilities dashboard with 30+ tools organized into categories. Inspired by Arch Linux, macOS, and Pop!_OS, this multi-page tkinter application provides system information, network tools, security utilities, and more.</p>
        </div>
        
        <div class="detail-section">
            <h2>Features</h2>
            <ul class="feature-list">
                <li><strong>System Section:</strong> Neofetch, System Info, CPU Detail, GPU Info, Battery, Disk Usage, Mount Points</li>
                <li><strong>Network Section:</strong> Network Info, Ping Test, DNS Lookup, Port Scanner, Speed Test</li>
                <li><strong>Security Section:</strong> Password Strength Checker, File Hash Checker, Encrypt/Decrypt (Fernet)</li>
                <li><strong>Tools Section:</strong> Process Viewer, System Monitor, Services, Screenshot, Calculator</li>
                <li><strong>Utilities Section:</strong> File Explorer, Environment Variables, User Info, Clipboard, Notes, Color Picker</li>
                <li><strong>Admin Section:</strong> Log Viewer (with live tail), Terminal Dashboard, Windows Updates, Matrix Animation</li>
                <li><strong>Activity Monitor:</strong> Foreground window tracking, system metrics, network connections, disk I/O, services, file changes, timeline</li>
                <li><strong>Red Book:</strong> Personal diary with rich text and image support</li>
            </ul>
        </div>
        
        <div class="detail-section">
            <h2>Requirements</h2>
            <div class="requirement-box">
                <h3><i class="fas fa-info-circle"></i> System Requirements</h3>
                <ul class="feature-list">
                    <li>Python 3.x installed</li>
                    <li>Windows operating system</li>
                    <li>psutil for system monitoring</li>
                    <li>Pillow for screenshots and image handling</li>
                    <li>cryptography for encryption/decryption</li>
                </ul>
            </div>
        </div>
        
        <div class="detail-section">
            <h2>Installation</h2>
            <p>1. Download the void5.0 folder</p>
            <p>2. Install dependencies:</p>
            <div class="code-block">pip install psutil pillow cryptography</div>
            <p>3. Run the application:</p>
            <div class="code-block">python void.py</div>
            <p>Or use the batch file:</p>
            <div class="code-block">run.bat</div>
        </div>
        
        <div class="detail-section">
            <h2>Usage</h2>
            <ul class="feature-list">
                <li>Navigate using the sidebar menu</li>
                <li>Each page has its own controls and refresh buttons</li>
                <li>Use the Activity Monitor for real-time system tracking</li>
                <li>The Red Book feature allows personal note-taking with rich text</li>
            </ul>
        </div>
        
        <a href="#" class="download-btn">
            <i class="fas fa-download"></i> Download VOID Utilities 5.0
        </a>
    </div>

    <footer>
        <p>&copy; 2026 VOID Tools. All rights reserved.</p>
        <p>Free and open source software.</p>
    </footer>

    <script src="../js/config.js"></script>
    <script src="../js/main.js"></script>
    <script>document.querySelector('.download-btn').href = VOID_CONFIG.downloads.utilities;</script>
</body>
</html>
