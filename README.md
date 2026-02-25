<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kangen Mantan HTS</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&family=Great+Vibes&display=swap" rel="stylesheet">
    <style>
        /* --- VARIABEL & RESET --- */
        :root {
            --pink-soft: #ff9a9e;
            --purple-soft: #fad0c4;
            --purple-dark: #a18cd1;
            --text-color: #4a4a4a;
            --white: #ffffff;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            /* Background Gradient Soft Pink ke Ungu */
            background: linear-gradient(135deg, #ff9a9e 0%, #fecfef 50%, #a18cd1 100%);
            font-family: 'Poppins', sans-serif;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        /* --- KARTU UTAMA --- */
        .container {
            background: rgba(255, 255, 255, 0.9);
            backdrop-filter: blur(10px);
            padding: 40px 30px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            text-align: center;
            max-width: 400px;
            width: 100%;
            animation: fadeIn 1s ease;
        }

        /* --- FOTO PROFIL --- */
        .profile-img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid var(--white);
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            margin-bottom: 20px;
            background-color: #ddd; /* Placeholder warna abu jika gambar belum ada */
        }

        /* --- TEKS JUDUL --- */
        h1 {
            font-family: 'Great Vibes', cursive;
            font-size: 3.5rem;
            color: var(--text-color);
            margin-bottom: 10px;
            line-height: 1;
        }

        h2 {
            font-size: 1rem;
            font-weight: 400;
            color: #666;
            margin-bottom: 30px;
            letter-spacing: 1px;
            text-transform: uppercase;
        }

        /* --- PESAN / QUOTE --- */
        .message-box {
            background: #fff0f3;
            padding: 20px;
            border-radius: 12px;
            margin-bottom: 30px;
            border-left: 4px solid var(--pink-soft);
        }

        .message-box p {
            font-size: 0.95rem;
            color: var(--text-color);
            line-height: 1.6;
            font-style: italic;
        }

        /* --- TOMBOL AKSI --- */
        .btn {
            display: inline-block;
            width: 100%;
            padding: 14px 0;
            margin-bottom: 15px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            transition: transform 0.2s, box-shadow 0.2s;
            cursor: pointer;
            border: none;
        }

        .btn-whatsapp {
            background-color: #25D366;
            color: white;
            box-shadow: 0 4px 10px rgba(37, 211, 102, 0.3);
        }

        .btn-instagram {
            background: linear-gradient(45deg, #f09433 0%, #e6683c 25%, #dc2743 50%, #cc2366 75%, #bc1888 100%);
            color: white;
            box-shadow: 0 4px 10px rgba(220, 39, 67, 0.3);
        }

        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 15px rgba(0,0,0,0.15);
        }

        /* --- FOOTER --- */
        .footer {
            margin-top: 30px;
            font-size: 0.8rem;
            color: #888;
        }

        /* --- ANIMASI --- */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

    </style>
</head>
<body>

    <div class="container">
        <!-- Ganti src dengan foto kalian (misal: foto bareng mantan) -->
        <!-- Jika tidak ada foto, hapus tag img dan ganti dengan div kosong atau emoji besar -->
        <img src="https://via.placeholder.com/150" alt="Foto Kita Dulu" class="profile-img">
        
        <h1>Kangen Mantan</h1>
        <h2>HTS</h2>

        <div class="message-box">
            <p>"Kadang, kita perlu melihat ke belakang untuk menghargai kenangan, meskipun semuanya telah berubah. Tetaplah positif dan semangat!"</p>
        </div>

        <!-- Ganti nomor WhatsApp di bawah ini dengan nomor tujuan (format: 628xxx) -->
        <a href="https://wa.me/6281234567890?text=Halo%20kangen%20nih" class="btn btn-whatsapp">
            Kirim Pesan via WhatsApp
        </a>
        
        <!-- Ganti link Instagram di bawah ini -->
        <a href="https://instagram.com/username_kamu" class="btn btn-instagram">
            Follow Instagram
        </a>

        <div class="footer">
            &copy; 2023 Kangen Mantan HTS
        </div>
    </div>

</body>
</html>
