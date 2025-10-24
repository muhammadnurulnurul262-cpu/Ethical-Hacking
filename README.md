# Ethical-Hacking
Educational mapping of ethical and harmful hacking concepts. If you find missing parts or errors, feel free to add, fix, or improve the material responsibly.


<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mind Map Ethical Hacking - Versi Berwarna</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            margin: 0;
            padding: 20px;
            color: #fff;
        }
        .mindmap {
            display: flex;
            flex-direction: column;
            align-items: center;
            animation: fadeIn 1s ease-in;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .center {
            background: linear-gradient(45deg, #ff6b6b, #feca57);
            color: white;
            padding: 30px;
            border-radius: 50%;
            text-align: center;
            font-size: 2em;
            font-weight: bold;
            margin-bottom: 30px;
            box-shadow: 0 10px 20px rgba(0,0,0,0.3);
            transition: transform 0.3s ease;
        }
        .center:hover {
            transform: scale(1.05);
        }
        .branches {
            display: flex;
            justify-content: space-around;
            width: 100%;
            max-width: 1000px;
            flex-wrap: wrap;
        }
        .branch {
            background: linear-gradient(45deg, #48cae4, #023e8a);
            color: white;
            padding: 20px;
            border-radius: 15px;
            text-align: center;
            width: 220px;
            margin: 15px;
            box-shadow: 0 8px 15px rgba(0,0,0,0.2);
            transition: all 0.3s ease;
        }
        .branch:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 25px rgba(0,0,0,0.3);
        }
        .sub-branches {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-top: 10px;
        }
        .sub-branch {
            background: linear-gradient(45deg, #f72585, #7209b7);
            color: white;
            padding: 12px;
            border-radius: 8px;
            text-align: center;
            width: 160px;
            margin: 8px 0;
            font-size: 0.9em;
            box-shadow: 0 5px 10px rgba(0,0,0,0.2);
            transition: all 0.3s ease;
        }
        .sub-branch:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 15px rgba(0,0,0,0.3);
        }
        h2 {
            margin-top: 0;
            font-size: 1.2em;
        }
        p {
            font-size: 0.9em;
            margin: 10px 0;
        }
        .warning {
            background: linear-gradient(45deg, #ff9f43, #ee5a24);
            color: white;
            padding: 15px;
            border-radius: 10px;
            text-align: center;
            max-width: 800px;
            margin: 30px auto;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="mindmap">
        <div class="center">
            Ethical Hacking<br>(Hacking Etis)
        </div>
        <div class="branches">
            <div class="branch">
                <h2>Definisi</h2>
                <p>Praktik menguji keamanan sistem dengan izin untuk mencegah serangan.</p>
                <div class="sub-branches">
                    <div class="sub-branch">Legal & Etis</div>
                    <div class="sub-branch">Dengan Izin</div>
                </div>
            </div>
            <div class="branch">
                <h2>Langkah-Langkah</h2>
                <p>Proses sistematis untuk pengujian.</p>
                <div class="sub-branches">
                    <div class="sub-branch">Reconnaissance</div>
                    <div class="sub-branch">Scanning</div>
                    <div class="sub-branch">Gaining Access</div>
                    <div class="sub-branch">Maintaining Access</div>
                    <div class="sub-branch">Covering Tracks</div>
                </div>
            </div>
            <div class="branch">
                <h2>Tools Populer</h2>
                <p>Alat yang digunakan dalam ethical hacking.</p>
                <div class="sub-branches">
                    <div class="sub-branch">Nmap</div>
                    <div class="sub-branch">Metasploit</div>
                    <div class="sub-branch">Wireshark</div>
                    <div class="sub-branch">Burp Suite</div>
                </div>
            </div>
            <div class="branch">
                <h2>Sertifikasi</h2>
                <p>Kualifikasi untuk menjadi ethical hacker.</p>
                <div class="sub-branches">
                    <div class="sub-branch">CEH (Certified Ethical Hacker)</div>
                    <div class="sub-branch">OSCP (Offensive Security)</div>
                    <div class="sub-branch">CompTIA Security+</div>
                </div>
            </div>
        </div>
    </div>
    <div class="warning">
        <strong>Peringatan:</strong> Ethical hacking hanya boleh dilakukan dengan izin tertulis dari pemilik sistem. Jangan gunakan pengetahuan ini untuk aktivitas ilegal. Pelajari lebih lanjut dari sumber terpercaya seperti EC-Council atau Offensive Security.
    </div>
</body>
</html>
