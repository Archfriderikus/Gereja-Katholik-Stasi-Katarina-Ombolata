# Gereja-Katholik-Stasi-Katarina-Ombolata
Donasi Sound System Musik Gereja Stasi Katarina Ombolata 
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Donasi Sound System | Stasi Katarina Ombolata</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>Donasi Sound System Musik</h1>
    <h2>Gereja Stasi Santa Katarina Ombolata</h2>
</header>

<section class="content">
    <h3>Tujuan Donasi</h3>
    <p>
        Donasi ini bertujuan untuk pengadaan dan peningkatan
        <b>Sound System Musik Gereja</b> agar mendukung pelayanan liturgi
        dan koor dengan lebih baik.
    </p>

    <h3>Target Dana</h3>
    <div class="target">
        <p>Target: <b>Rp 25.000.000</b></p>
        <progress value="7500000" max="25000000"></progress>
        <p>Terkumpul: <b>Rp 7.500.000</b></p>
    </div>

    <h3>Cara Berdonasi</h3>
    <ul>
        <li>Transfer Bank: <b>BRI 1234xxxxxx</b></li>
        <li>Atas Nama: <b>Panitia Gereja Stasi Ombolata</b></li>
        <li>Konfirmasi ke Seksi Dana / Bendahara</li>
    </ul>

    <button onclick="showThanks()">Saya Sudah Berdonasi</button>
</section>

<footer>
    <p>© 2025 Gereja Stasi Santa Katarina Ombolata</p>
</footer>

<script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background: #f4f4f4;
    color: #333;
}

header {
    background: #5a2d82;
    color: white;
    padding: 20px;
    text-align: center;
}

.content {
    background: white;
    max-width: 800px;
    margin: 20px auto;
    padding: 20px;
    border-radius: 8px;
}

h3 {
    color: #5a2d82;
}

.target {
    background: #f0e6f7;
    padding: 15px;
    border-radius: 5px;
}

progress {
    width: 100%;
    height: 20px;
}

button {
    background: #5a2d82;
    color: white;
    border: none;
    padding: 12px 20px;
    margin-top: 15px;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background: #472261;
}

footer {
    text-align: center;
    padding: 15px;
    background: #ddd;
    margin-top: 30px;
}
function showThanks() {
    alert("Terima kasih atas partisipasi Anda. Tuhan memberkati 🙏");
}

