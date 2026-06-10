<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio Profesional | Adit Tama Septiara</title>
    <style>
        /* Pengaturan Dasar & Palet Warna */
        :root {
            --primary-color: #800000; /* Merah Maroon Formal */
            --secondary-color: #f4f4f4; /* Abu-abu Lembut */
            --text-color: #333333;
            --bg-color: #ffffff; /* Putih Bersih */
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            color: var(--text-color);
            background-color: var(--secondary-color);
        }

        /* Navigasi */
        header {
            background-color: var(--primary-color);
            color: white;
            padding: 1.5rem 0;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        header h1 {
            margin: 0;
            font-size: 2rem;
        }

        nav {
            margin-top: 10px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        /* Kontainer Utama */
        .container {
            width: 80%;
            max-width: 900px;
            margin: auto;
            overflow: hidden;
            padding: 20px;
        }

        /* Desain Bagian (Section) */
        section {
            background: var(--bg-color);
            padding: 30px;
            margin-bottom: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
        }

        h2 {
            color: var(--primary-color);
            border-bottom: 2px solid var(--secondary-color);
            padding-bottom: 10px;
        }

        /* Tombol Call-to-Action */
        .btn {
            display: inline-block;
            background: var(--primary-color);
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 15px;
            font-weight: bold;
        }

        .btn:hover {
            background: #5a0000;
        }

        /* Daftar Keahlian */
        .skills-container {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }

        .skill-badge {
            background: var(--secondary-color);
            padding: 8px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
            border: 1px solid #ddd;
        }

        /* Footer */
        footer {
            background-color: #222;
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-top: 20px;
        }

        footer a {
            color: #ffcccc;
            text-decoration: none;
        }
    </style>
</head>
<body>

    <header>
        <h1>Adit Tama Septiara</h1>
        <p>Lulusan Ilmu Komunikasi | Spesialis HR Admin & Konten Digital</p>
        <nav>
            <a href="#about">Tentang Saya</a>
            <a href="#skills">Keahlian</a>
            <a href="#experience">Pengalaman</a>
            <a href="#contact">Kontak</a>
        </nav>
    </header>

    <div class="container">
        
        <section id="about">
            <h2>Tentang Saya</h2>
            <p>Halo, nama saya Adit Tama Septiara. Saya adalah lulusan Ilmu Komunikasi dari Universitas Gunadarma dengan IPK 3.53/4.00. Saya memiliki pengalaman sebagai talenta Informasi Publik dan Layanan Masyarakat. Saya adalah individu yang antusias dan adaptif, dengan kemampuan komunikasi, kerja tim, dan multitasking yang kuat.</p>
            <a href="#" class="btn">Unduh Resume (PDF)</a>
        </section>

        <section id="skills">
            <h2>Keahlian & Perangkat Terkuasai</h2>
            <h3>Soft Skills & Hard Skills</h3>
            <div class="skills-container">
                <span class="skill-badge">Komunikasi Publik</span>
                <span class="skill-badge">Video Editing</span>
                <span class="skill-badge">Copywriting</span>
                <span class="skill-badge">Database Administration</span>
                <span class="skill-badge">Pemecahan Masalah</span>
                <span class="skill-badge">Manajemen Waktu</span>
            </div>
            
            <h3>Perangkat Lunak (Tools)</h3>
            <div class="skills-container">
                <span class="skill-badge">Google Workspace</span>
                <span class="skill-badge">Microsoft Office (Excel, Word)</span>
                <span class="skill-badge">Canva</span>
                <span class="skill-badge">Adobe Photoshop</span>
            </div>
        </section>

        <section id="experience">
            <h2>Pengalaman Kerja Profesional</h2>
            
            <div class="job">
                <h3>HR Admin - PT Setra Praba Perkasa</h3>
                <p><em>Magang Kementerian Ketenagakerjaan RI</em></p>
                <ul>
                    <li>Mengelola administrasi BPJS Ketenagakerjaan dan Kesehatan untuk lebih dari 100 karyawan.</li>
                    <li>Memantau kontrak kerja, perpanjangan kontrak, dan pemrosesan akhir kontrak menggunakan spreadsheet dan sistem HRMS.</li>
                    <li>Mengoordinasikan akurasi data dan kelengkapan dokumen karyawan di 100+ area kerja.</li>
                </ul>
            </div>

            <div class="job">
                <h3>Talent Content - Kantor Walikota Jakarta Timur</h3>
                <p><em>Magang Pemerintah Daerah</em></p>
                <ul>
                    <li>Membantu penyampaian informasi publik dan kampanye positif pemerintah lokal melalui media sosial.</li>
                    <li>Membuat kampanye video Instagram Reels yang berhasil meraih lebih dari 26.000 tayangan.</li>
                </ul>
            </div>
        </section>

    </div>

    <footer id="contact">
        <h2>Mari Berkolaborasi</h2>
        <p>Email: <a href="mailto:adhitthama010902@gmail.com">adhitthama010902@gmail.com</a></p>
        <p>Instagram: @adtthma</p>
        <p>&copy; 2026 Adit Tama Septiara. All Rights Reserved.</p>
    </footer>

</body>
</html># Portofolio
Portofolio 
