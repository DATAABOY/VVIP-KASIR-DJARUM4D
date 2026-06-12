<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>RUMUS WD FLOP KASIR DJARUM4D</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.carousel.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.theme.default.min.css">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Outfit','Segoe UI',sans-serif;
}

:root{
    --cyan:#00f6ff;
    --blue:#008cff;
    --purple:#9b5cff;
    --pink:#ff38d1;
    --gold:#ffd36a;
    --dark:#030712;
    --glass:rgba(5,10,25,.58);
    --line:rgba(0,246,255,.32);
}

html{
    scroll-behavior:smooth;
}

body{
    min-height:100vh;
    color:#fff;
    padding:38px 18px 42px;
    display:flex;
    flex-direction:column;
    align-items:center;
    overflow-x:hidden;
    background:#020617;
}

.video-bg{
    position:fixed;
    inset:0;
    width:100%;
    height:100%;
    object-fit:cover;
    z-index:-5;
    filter:saturate(1.35) contrast(1.06) brightness(1.02);
}

body::before{
    content:"";
    position:fixed;
    inset:0;
    z-index:-4;
    background:
        radial-gradient(circle at 14% 14%, rgba(0,246,255,.46), transparent 36%),
        radial-gradient(circle at 86% 9%, rgba(155,92,255,.38), transparent 31%),
        radial-gradient(circle at 50% 98%, rgba(255,56,209,.25), transparent 44%),
        linear-gradient(180deg, rgba(2,6,23,.16), rgba(2,6,23,.66));
    pointer-events:none;
}

body::after{
    content:"";
    position:fixed;
    inset:0;
    z-index:-3;
    background-image:
        linear-gradient(rgba(255,255,255,.045) 1px, transparent 1px),
        linear-gradient(90deg, rgba(255,255,255,.045) 1px, transparent 1px);
    background-size:54px 54px;
    mask-image:linear-gradient(to bottom, rgba(0,0,0,.7), transparent 88%);
    pointer-events:none;
}

.btn-fluid{
    position:fixed;
    top:20px;
    left:20px;
    z-index:1000;
    display:inline-flex;
    align-items:center;
    gap:8px;
    padding:12px 20px;
    color:#fff;
    text-decoration:none;
    font-size:14px;
    font-weight:800;
    letter-spacing:.4px;
    border:1px solid rgba(255,255,255,.22);
    border-radius:999px;
    background:linear-gradient(135deg, rgba(0,246,255,.20), rgba(155,92,255,.26));
    box-shadow:0 0 22px rgba(0,246,255,.18), inset 0 0 18px rgba(255,255,255,.08);
    backdrop-filter:blur(12px);
    -webkit-backdrop-filter:blur(12px);
    transition:.3s ease;
}

.btn-fluid:hover{
    transform:translateY(-2px) scale(1.03);
    border-color:rgba(0,246,255,.7);
    box-shadow:0 0 28px rgba(0,246,255,.36), 0 10px 25px rgba(0,0,0,.35);
}

.container{
    width:100%;
    max-width:1080px;
    margin-top:22px;
    padding:28px;
    position:relative;
    overflow:hidden;
    border-radius:30px;
    background:linear-gradient(145deg, rgba(7,18,42,.70), rgba(16,35,72,.52));
    border:1px solid rgba(126,242,255,.44);
    box-shadow:
        0 28px 80px rgba(0,0,0,.46),
        0 0 42px rgba(0,246,255,.24),
        inset 0 1px 0 rgba(255,255,255,.22);
    backdrop-filter:blur(14px) saturate(135%);
    -webkit-backdrop-filter:blur(14px) saturate(135%);
}

.container::before{
    content:"";
    position:absolute;
    inset:-2px;
    background:
        linear-gradient(120deg, transparent 0%, rgba(0,246,255,.20) 22%, transparent 45%, rgba(255,56,209,.16) 70%, transparent 100%);
    opacity:.9;
    pointer-events:none;
}

.container::after{
    content:"";
    position:absolute;
    width:260px;
    height:260px;
    right:-110px;
    top:-110px;
    border-radius:50%;
    background:radial-gradient(circle, rgba(0,246,255,.28), transparent 65%);
    pointer-events:none;
}

.logo-container,
h2,
.form-group,
.btn-group,
.output-section{
    position:relative;
    z-index:2;
}

.logo-container{
    display:flex;
    justify-content:center;
    margin-bottom:18px;
}

.logo-container img{
    max-width:100%;
    max-height:96px;
    filter:drop-shadow(0 0 15px rgba(0,246,255,.72)) drop-shadow(0 0 28px rgba(155,92,255,.38));
}

h2{
    text-align:center;
    margin-bottom:26px;
    font-size:clamp(23px, 3.3vw, 38px);
    font-weight:900;
    letter-spacing:1.5px;
    line-height:1.15;
    text-transform:uppercase;
    color:#fff;
    text-shadow:0 0 10px rgba(255,255,255,.6), 0 0 28px rgba(0,246,255,.62);
}

h2 span{
    display:inline-block;
    padding:10px 18px;
    border-radius:999px;
    border:1px solid rgba(0,246,255,.22);
    background:rgba(255,255,255,.06);
}

.form-group{
    margin-bottom:22px;
}

label{
    display:flex;
    align-items:center;
    gap:8px;
    margin-bottom:10px;
    font-size:13px;
    font-weight:900;
    letter-spacing:1px;
    text-transform:uppercase;
    color:#eafcff;
    text-shadow:0 0 12px rgba(0,246,255,.45);
}

textarea{
    width:100%;
    min-height:150px;
    resize:vertical;
    border-radius:20px;
    padding:18px;
    color:#fff;
    font-size:15px;
    line-height:1.6;
    outline:none;
    border:1px solid rgba(0,246,255,.32);
    background:rgba(4,14,34,.58);
    box-shadow:inset 0 0 20px rgba(0,0,0,.58), 0 0 20px rgba(0,246,255,.10);
    transition:.28s ease;
}

textarea::placeholder{
    color:rgba(231,245,255,.58);
}

textarea:focus{
    border-color:rgba(0,246,255,.95);
    box-shadow:inset 0 0 18px rgba(0,0,0,.58), 0 0 28px rgba(0,246,255,.34);
    background:rgba(5,18,44,.72);
}

.btn-group{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:16px;
    margin-bottom:28px;
}

button{
    border:0;
    cursor:pointer;
    border-radius:16px;
    padding:16px 18px;
    color:#fff;
    font-size:14px;
    font-weight:900;
    letter-spacing:1px;
    text-transform:uppercase;
    transition:.28s ease;
    position:relative;
    overflow:hidden;
}

button::before{
    content:"";
    position:absolute;
    inset:0;
    transform:translateX(-120%) skewX(-20deg);
    background:linear-gradient(90deg, transparent, rgba(255,255,255,.30), transparent);
    transition:.55s ease;
}

button:hover::before{
    transform:translateX(120%) skewX(-20deg);
}

button:active{
    transform:scale(.97);
}

.btn-submit{
    background:linear-gradient(135deg, #00c8ff, #7c3cff 55%, #ff38d1);
    box-shadow:0 12px 28px rgba(0,140,255,.28), 0 0 22px rgba(255,56,209,.18);
}

.btn-submit:hover{
    transform:translateY(-3px);
    box-shadow:0 18px 40px rgba(0,140,255,.38), 0 0 30px rgba(255,56,209,.28);
}

.btn-reset{
    background:linear-gradient(135deg, rgba(255,255,255,.10), rgba(255,255,255,.04));
    border:1px solid rgba(255,255,255,.18);
    box-shadow:inset 0 0 18px rgba(255,255,255,.05);
}

.btn-reset:hover{
    transform:translateY(-3px);
    border-color:rgba(0,246,255,.58);
    box-shadow:0 0 24px rgba(0,246,255,.16), inset 0 0 18px rgba(255,255,255,.07);
}

.output-section{
    padding-top:22px;
    border-top:1px solid rgba(0,246,255,.20);
}

.output-header{
    display:flex;
    justify-content:space-between;
    align-items:center;
    gap:14px;
    margin-bottom:14px;
}

.output-title{
    font-size:18px;
    font-weight:900;
    color:#fff;
    letter-spacing:.6px;
}

.btn-copy-all{
    width:auto;
    flex:none;
    padding:12px 18px;
    color:#03101f;
    background:linear-gradient(135deg, #71fff7, #00bfff);
    box-shadow:0 0 22px rgba(0,246,255,.25);
}

.btn-copy-all:hover{
    transform:translateY(-2px);
    box-shadow:0 0 30px rgba(0,246,255,.45);
}

.table-container{
    width:100%;
    overflow-x:auto;
    border-radius:20px;
    border:1px solid rgba(0,246,255,.30);
    background:rgba(4,14,34,.52);
    box-shadow:0 18px 40px rgba(0,0,0,.40), inset 0 0 20px rgba(0,246,255,.06);
}

table{
    width:100%;
    min-width:780px;
    border-collapse:collapse;
}

th{
    padding:16px 18px;
    text-align:left;
    color:#00111d;
    font-size:12px;
    font-weight:900;
    text-transform:uppercase;
    letter-spacing:1px;
    background:linear-gradient(180deg, #9fffff, #00d5ff);
    border-bottom:1px solid rgba(0,0,0,.30);
}

td{
    padding:15px 18px;
    color:#fff;
    font-size:14px;
    font-weight:600;
    border-bottom:1px solid rgba(0,246,255,.12);
    text-shadow:0 1px 2px rgba(0,0,0,.65);
}

tr:nth-child(odd) td{ background:rgba(255,255,255,.035); }
tr:nth-child(even) td{ background:rgba(0,246,255,.035); }
tr:hover td{ background:rgba(0,246,255,.13); }

.glow-amount{
    color:var(--gold);
    font-weight:900;
    text-shadow:0 0 10px rgba(255,211,106,.75), 0 0 18px rgba(255,56,209,.25);
}

.empty-message{
    text-align:center;
    padding:34px;
    color:rgba(234,252,255,.70);
    font-style:italic;
}

#latest-results.margin-top-15{
    width:100%;
    max-width:1080px;
    margin-top:26px;
    padding:24px 16px 18px !important;
    border-radius:28px !important;
    background:linear-gradient(145deg, rgba(7,18,42,.62), rgba(18,39,78,.44)) !important;
    border:1px solid rgba(0,246,255,.26) !important;
    box-shadow:0 22px 55px rgba(0,0,0,.50), 0 0 28px rgba(0,246,255,.13) !important;
    backdrop-filter:blur(14px);
    -webkit-backdrop-filter:blur(14px);
}

#latest-results::before{
    content:"LIST CUCI MATA";
    display:block;
    text-align:center;
    margin-bottom:16px;
    font-size:13px;
    font-weight:900;
    letter-spacing:2px;
    color:#bffcff;
    text-shadow:0 0 14px rgba(0,246,255,.50);
}

#latest-results .owl-carousel .item.slides{
    min-height:205px;
    display:flex !important;
    align-items:center !important;
    justify-content:center !important;
    padding:18px !important;
    border-radius:28px !important;
    background:linear-gradient(145deg, rgba(255,255,255,.08), rgba(255,255,255,.025)) !important;
    border:1px solid rgba(255,255,255,.12) !important;
    box-shadow:inset 0 0 18px rgba(255,255,255,.04), 0 12px 28px rgba(0,0,0,.26) !important;
    transition:.32s ease !important;
}

#latest-results .owl-carousel .item.slides:hover{
    transform:translateY(-8px) scale(1.02) !important;
    border-color:rgba(0,246,255,.70) !important;
    box-shadow:0 16px 38px rgba(0,246,255,.20), inset 0 0 22px rgba(0,246,255,.08) !important;
}

#latest-results .owl-carousel .item.slides img.w-100{
    width:148px !important;
    height:148px !important;
    object-fit:cover !important;
    border-radius:50% !important;
    border:3px solid rgba(0,246,255,.82) !important;
    box-shadow:0 0 18px rgba(0,246,255,.70), 0 0 30px rgba(155,92,255,.22) !important;
    background:#000 !important;
    transition:.32s ease !important;
}

#latest-results .owl-carousel .item.slides:hover img.w-100{
    transform:scale(1.08) rotate(2deg) !important;
}

.owl-theme .owl-dots{
    margin-top:18px !important;
}
.owl-theme .owl-dots .owl-dot span{
    width:9px !important;
    height:9px !important;
    background:rgba(255,255,255,.28) !important;
    transition:.28s ease !important;
}
.owl-theme .owl-dots .owl-dot.active span{
    width:28px !important;
    background:var(--cyan) !important;
    box-shadow:0 0 12px var(--cyan) !important;
}

.modal-overlay{
    position:fixed;
    inset:0;
    display:flex;
    align-items:center;
    justify-content:center;
    padding:22px;
    background:rgba(0,0,0,.58);
    z-index:9999;
    opacity:0;
    visibility:hidden;
    transition:.30s ease;
    perspective:1000px;
    backdrop-filter:blur(8px);
    -webkit-backdrop-filter:blur(8px);
}

.modal-overlay.show{
    opacity:1;
    visibility:visible;
}

.modal-container{
    width:min(860px, 92vw);
    display:flex;
    flex-direction:column;
    gap:16px;
    transform:rotateY(-82deg) scale(.92);
    opacity:.4;
    transition:.72s cubic-bezier(.68,-.55,.27,1.55);
}

.modal-overlay.show .modal-container{
    transform:rotateY(0deg) scale(1);
    opacity:1;
}

.image-wrapper{
    padding:7px;
    border-radius:24px;
    background:linear-gradient(135deg, var(--cyan), var(--purple), var(--pink));
    box-shadow:0 0 35px rgba(0,246,255,.45), 0 18px 50px rgba(0,0,0,.55);
}

.image-wrapper img{
    width:100%;
    display:block;
    border-radius:18px;
}

.btn-tutup{
    padding:17px 20px;
    color:#03101f;
    border-radius:16px;
    background:linear-gradient(135deg, #fff173, #00f6ff);
    box-shadow:0 0 26px rgba(0,246,255,.34);
}

.toast{
    display:none;
    position:fixed;
    right:24px;
    bottom:24px;
    z-index:10000;
    padding:16px 24px;
    color:#03101f;
    font-size:14px;
    font-weight:900;
    text-transform:uppercase;
    border-radius:16px;
    background:linear-gradient(135deg, #a8fff9, #00bfff);
    box-shadow:0 16px 40px rgba(0,246,255,.38);
    animation:toastIn .35s ease;
}

@keyframes toastIn{
    from{ transform:translateY(20px) scale(.94); opacity:0; }
    to{ transform:translateY(0) scale(1); opacity:1; }
}

@media(max-width:720px){
    body{ padding:82px 12px 28px; }
    .btn-fluid{ top:14px; left:14px; padding:10px 15px; font-size:12px; }
    .container{ padding:20px 14px; border-radius:22px; }
    .btn-group{ grid-template-columns:1fr; }
    .output-header{ flex-direction:column; align-items:stretch; }
    .btn-copy-all{ width:100%; }
    #latest-results .owl-carousel .item.slides img.w-100{ width:132px !important; height:132px !important; }
}
</style>
</head>
<body>

<video autoplay muted loop playsinline class="video-bg">
    <source src="https://v1.pinimg.com/videos/iht/expMp4/f8/14/43/f814434f043de965b47971a63e937b47_720w.mp4" type="video/mp4">
</video>

<a href="https://wzgaacs9-djarum4d.github.io/aboy/" class="btn-fluid">← Menu Utama</a>

<div id="modal" class="modal-overlay">
    <div class="modal-container" onclick="event.stopPropagation()">
        <div class="image-wrapper">
            <img src="https://i.postimg.cc/kMbTvBVW/1781090567626.gif" alt="Promosi">
        </div>
        <button class="btn-tutup" onclick="tutup()">KLIK DIMANA SAJA</button>
    </div>
</div>

<div class="container">
    <div class="logo-container">
        <img src="https://cdn.bunkerkiamat.com/djarum4d/images/logo/Djarum4d.gif" alt="Djarum4d Logo">
    </div>

    <h2><span>🌍 RUMUS WITHDRAW FLOP DJARUM4D 🌍</span></h2>

    <div class="form-group">
        <label for="inputData">⚡ Tempel Log Transaksi Mentah di Sini</label>
        <textarea id="inputData" placeholder="Tempel seluruh baris teks log di sini...
By : CS9 Aboy⚡"></textarea>
    </div>

    <div class="btn-group">
        <button class="btn-reset" onclick="resetInput()">Reset Input</button>
        <button class="btn-submit" onclick="submitData()">Submit Data</button>
    </div>

    <div class="output-section">
        <div class="output-header">
            <div class="output-title">Data Terurai Otomatis:</div>
            <button class="btn-copy-all" onclick="copyAllTableData()">Salin Semua Hasil Ekspor</button>
        </div>

        <div class="table-container">
            <table>
                <thead>
                    <tr>
                        <th style="width:15%;">WAKTU</th>
                        <th style="width:20%;">Used ID</th>
                        <th style="width:35%;">Tujuan Bank</th>
                        <th style="width:15%;"></th>
                        <th style="width:15%;">Jumlah</th>
                    </tr>
                </thead>
                <tbody id="tableBody">
                    <tr id="emptyRow">
                        <td colspan="5" class="empty-message">Setelah salin data silahkan reset input.</td>
                    </tr>
                </tbody>
            </table>
        </div>
    </div>
</div>

<div id="latest-results" class="margin-top-15">
    <div class="owl-carousel owl-theme gameicon">
        <div class="item slides" style="text-align:center"><img src="https://i.postimg.cc/fy54yXkn/image.jpg" class="w-100" alt="Game Icon"></div>
        <div class="item slides" style="text-align:center"><img src="https://i.postimg.cc/zXXZMdP5/download-(11).jpg" class="w-100" alt="Game Icon"></div>
        <div class="item slides" style="text-align:center"><img src="https://i.postimg.cc/15ChZpLw/download-(10).jpg" class="w-100" alt="Game Icon"></div>
        <div class="item slides" style="text-align:center"><img src="https://i.postimg.cc/9QD3XD25/download-(9).jpg" class="w-100" alt="Game Icon"></div>
        <div class="item slides" style="text-align:center"><img src="https://i.postimg.cc/HkRqrTWy/download-(8).jpg" class="w-100" alt="Game Icon"></div>
        <div class="item slides" style="text-align:center"><img src="https://i.postimg.cc/ydz2TnSr/download-(7).jpg" class="w-100" alt="Game Icon"></div>
        <div class="item slides" style="text-align:center"><img src="https://i.postimg.cc/qRXSDns1/download-(6).jpg" class="w-100" alt="Game Icon"></div>
        <div class="item slides" style="text-align:center"><img src="https://i.postimg.cc/prW7wTC6/download-(5).jpg" class="w-100" alt="Game Icon"></div>
        <div class="item slides" style="text-align:center"><img src="https://i.postimg.cc/qq1Y4TZ0/download-(4).jpg" class="w-100" alt="Game Icon"></div>
        <div class="item slides" style="text-align:center"><img src="https://i.postimg.cc/CM79jGLK/download-(3).jpg" class="w-100" alt="Game Icon"></div>
        <div class="item slides" style="text-align:center"><img src="https://i.postimg.cc/4NFM0X9h/download-(2).jpg" class="w-100" alt="Game Icon"></div>
        <div class="item slides" style="text-align:center"><img src="https://i.postimg.cc/pX17SPF7/download-(1).jpg" class="w-100" alt="Game Icon"></div>
        <div class="item slides" style="text-align:center"><img src="https://i.postimg.cc/DwJDkRrR/download.jpg" class="w-100" alt="Game Icon"></div>
    </div>
</div>

<div id="toastNotification" class="toast">Data Siap Ditempel ke Sheet!</div>

<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/owl.carousel.min.js"></script>

<script>
// Proteksi sederhana: klik kanan, Ctrl+U, dan F12
// Catatan: pesan dibuat lebih rapi agar tampilan tidak kasar.
document.addEventListener('contextmenu', e => e.preventDefault());
document.onkeydown = function(e){
    if((e.ctrlKey && e.keyCode === 85) || e.keyCode === 123){
        const message = `
            <html>
                <body style="background:#020617;color:#fff;display:flex;justify-content:center;align-items:center;height:100vh;font-family:Arial,sans-serif;text-align:center;">
                    <div style="padding:30px;border:1px solid #00f6ff;border-radius:22px;box-shadow:0 0 30px rgba(0,246,255,.35);">
                        <h1 style="font-size:3rem;margin:0;text-shadow:0 0 18px #00f6ff;">AKSES DITOLAK</h1>
                        <p style="opacity:.75;">Halaman ini dilindungi.</p>
                    </div>
                </body>
            </html>
        `;
        const win = window.open('', '_blank');
        if(win){
            win.document.write(message);
            win.document.close();
        }
        e.preventDefault();
        return false;
    }
};

const modal = document.getElementById('modal');
window.addEventListener('load', () => {
    setTimeout(() => modal.classList.add('show'), 500);
});
function tutup(){
    modal.classList.remove('show');
}
modal.addEventListener('click', event => {
    if(event.target === modal) tutup();
});

$(document).ready(function(){
    $('.owl-carousel.gameicon').owlCarousel({
        loop:true,
        margin:20,
        nav:false,
        dots:true,
        autoplay:true,
        autoplayTimeout:3500,
        smartSpeed:800,
        responsive:{
            0:{items:1},
            576:{items:2},
            992:{items:3},
            1200:{items:4}
        }
    });
});

function submitData(){
    const inputField = document.getElementById('inputData');
    const tableBody = document.getElementById('tableBody');
    const emptyRow = document.getElementById('emptyRow');

    let rawText = inputField.value.trim();

    if(rawText === ''){
        alert('Kolom data masih kosong! Silakan isi terlebih dahulu.');
        return;
    }

    if(emptyRow){ emptyRow.remove(); }

    const blocks = rawText.split('ACCEPT');
    let dataFound = false;

    blocks.forEach(block => {
        if(block.includes('Withdraw')){
            dataFound = true;

            const parts = block.split('Withdraw');
            const kiriWithdraw = parts[0].trim();
            const kananWithdraw = parts[1].trim();

            const timeMatch = kiriWithdraw.match(/\d{2}:\d{2}:\d{2}/);
            let waktu = '-';
            let userId = '-';

            if(timeMatch){
                waktu = timeMatch[0];
                const indexWaktu = kiriWithdraw.indexOf(waktu);
                userId = kiriWithdraw.substring(indexWaktu + waktu.length).trim();
            }

            const indexMinus = kananWithdraw.lastIndexOf('-');
            let tujuanBank = '-';
            let jumlah = '-';
            let kolomKosong = '';

            if(indexMinus !== -1){
                tujuanBank = kananWithdraw.substring(0, indexMinus).trim();
                jumlah = kananWithdraw.substring(indexMinus + 1).trim();
            }else{
                tujuanBank = kananWithdraw;
            }

            const newRow = document.createElement('tr');
            newRow.setAttribute('data-waktu', waktu);
            newRow.setAttribute('data-userid', userId);
            newRow.setAttribute('data-bank', tujuanBank);
            newRow.setAttribute('data-kosong', kolomKosong);
            newRow.setAttribute('data-jumlah', jumlah);

            newRow.innerHTML = `
                <td>${waktu}</td>
                <td>${userId}</td>
                <td>${tujuanBank}</td>
                <td>${kolomKosong}</td>
                <td class="glow-amount">${jumlah}</td>
            `;

            tableBody.insertBefore(newRow, tableBody.firstChild);
        }
    });

    if(!dataFound){
        alert("Format data tidak dikenali. Pastikan teks mengandung kata 'Withdraw' dan 'ACCEPT'.");
        if(!document.getElementById('emptyRow') && tableBody.children.length === 0){
            tableBody.innerHTML = `<tr id="emptyRow"><td colspan="5" class="empty-message">Setelah salin data silahkan reset input.</td></tr>`;
        }
        return;
    }

    inputField.value = '';
    inputField.focus();
}

function copyAllTableData(){
    const tableBody = document.getElementById('tableBody');
    const rows = tableBody.querySelectorAll('tr');

    if(rows.length === 0 || document.getElementById('emptyRow')){
        alert('Tidak ada data hasil ekspor yang bisa disalin!');
        return;
    }

    let linesToCopy = [];

    rows.forEach(row => {
        const waktu = row.getAttribute('data-waktu');
        const userId = row.getAttribute('data-userid');
        const bank = row.getAttribute('data-bank');
        const kosong = row.getAttribute('data-kosong');
        const jumlah = row.getAttribute('data-jumlah');

        if(waktu){
            linesToCopy.push(`${waktu}\t${userId}\t${bank}\t${kosong}\t${jumlah}`);
        }
    });

    const textToCopy = linesToCopy.join('\n');

    if(navigator.clipboard && window.isSecureContext){
        navigator.clipboard.writeText(textToCopy).then(showToast).catch(() => fallbackCopy(textToCopy));
    }else{
        fallbackCopy(textToCopy);
    }
}

function fallbackCopy(text){
    const temp = document.createElement('textarea');
    temp.value = text;
    temp.style.position = 'fixed';
    temp.style.left = '-9999px';
    document.body.appendChild(temp);
    temp.focus();
    temp.select();
    document.execCommand('copy');
    document.body.removeChild(temp);
    showToast();
}

function showToast(){
    const toast = document.getElementById('toastNotification');
    toast.style.display = 'block';
    setTimeout(() => {
        toast.style.display = 'none';
    }, 2500);
}

function resetInput(){
    const inputField = document.getElementById('inputData');
    const tableBody = document.getElementById('tableBody');

    inputField.value = '';
    tableBody.innerHTML = `
        <tr id="emptyRow">
            <td colspan="5" class="empty-message">Belum ada data yang dimasukkan.</td>
        </tr>
    `;
    inputField.focus();
}
</script>

</body>
</html>
