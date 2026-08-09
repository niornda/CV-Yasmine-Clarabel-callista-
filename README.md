<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV Yasmine Clarabel Callista</title>

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            background: #ddd;
            font-family: Arial, sans-serif;
            color: #222;
        }

        .cv {
            width: 900px;
            margin: 40px auto;
            background: white;
            display: grid;
            grid-template-columns: 38% 62%;
            min-height: 1100px;
            box-shadow: 0 0 15px #aaa;
        }

        /* BAGIAN KIRI */
        .left {
            background: #d8d8d8;
            padding: 45px 40px;
        }

        .profile {
            text-align: center;
        }

        .profile img {
            width: 170px;
            height: 170px;
            object-fit: cover;
            border-radius: 50%;
            border: 5px solid #153cff;
        }

        .name {
            font-size: 30px;
            font-weight: bold;
            margin: 25px 0;
        }

        .description {
            text-align: justify;
            line-height: 1.8;
            margin-bottom: 45px;
        }

        .section {
            margin-bottom: 40px;
        }

        .section-title {
            font-size: 23px;
            font-weight: bold;
            border-bottom: 3px solid #222;
            padding-bottom: 8px;
            margin-bottom: 20px;
            position: relative;
        }

        .section-title::before {
            content: "";
            position: absolute;
            width: 18px;
            height: 18px;
            background: #111;
            left: -20px;
            bottom: -10px;
        }

        .contact p {
            margin: 18px 0;
            font-size: 16px;
        }

        .skills ol {
            padding-left: 25px;
            line-height: 2;
        }

        /* BAGIAN KANAN */
        .right {
            padding: 45px 45px;
        }

        .right-section {
            margin-bottom: 40px;
        }

        .right-title {
            font-size: 24px;
            font-weight: bold;
            border-bottom: 3px solid #222;
            padding-bottom: 8px;
            margin-bottom: 25px;
            position: relative;
        }

        .right-title::before {
            content: "";
            position: absolute;
            width: 18px;
            height: 18px;
            background: #111;
            left: -20px;
            bottom: -10px;
        }

        .data p {
            margin: 0 0 20px;
            line-height: 1.5;
        }

        .data strong {
            display: block;
            font-size: 17px;
        }

        .education,
        .experience {
            margin-bottom: 25px;
        }

        .year {
            font-weight: normal;
            font-size: 17px;
            margin-bottom: 5px;
        }

        .school,
        .company {
            font-weight: bold;
            font-size: 17px;
            line-height: 1.5;
        }

        @media (max-width: 950px) {
            .cv {
                width: 95%;
            }
        }

        @media (max-width: 700px) {
            .cv {
                grid-template-columns: 1fr;
            }

            .left,
            .right {
                padding: 30px;
            }
        }
    </style>
</head>

<body>

<div class="cv">

    <!-- KIRI -->
    <div class="left">

        <div class="profile">
            <!-- Ganti foto dengan foto kamu -->
            <img src=" " alt="Foto Profil">

            <div class="name">
                YASMINE CLARABEL<br>CALLISTA
            </div>
        </div>

        <p class="description">
            Perkenalkan saya siswi dari kelas X-I
            yang ingin mencoba hal baru dan menambah pengalaman.
            Saya termasuk anak yang mudah  beradaptasi dengan orang baru
            serta bisa bekerja sama dengan baik. 
            Alasan saya ingin mengikuti organisasi untuk belajar lebih bertanggung jawab,
            mengembangkan kemampuan serta
            menambah wawasan dan relasi yabg luas.
        </p>

        <div class="section contact">
            <div class="section-title">KONTAK</div>

            <p>📧 yasmineclarabel13@gmail.com</p>
            <p>📱 0812 5934 6298</p>
            <p>◎ @rabellee_</p>
        </div>

        <div class="section skills">
            <div class="section-title">KEMAMPUAN</div>

            <ol>
                <li>Mampu bekerja sama atau bersosialisasi</li>
                <li>Orang yang disiplin</li>
                <li>Orang yang bertanggung jawab</li>
                <li>Dll.</li>
            </ol>
        </div>

    </div>


    <!-- KANAN -->
    <div class="right">

        <div class="right-section">
            <div class="right-title">DATA DIRI</div>

            <div class="data">
                <p>
                    Nama lengkap :
                    <strong>YASMINE CLARABEL CALLISTA</strong>
                </p>

                <p>
                    Tempat, Tgl Lahir :
                    <strong>Malang, 13 Februari 2011</strong>
                </p>

                <p>
                    Jenis Kelamin :
                    <strong>Perempuan</strong>
                </p>

                <p>
                    Alamat :
                    <strong>Green Living Residence, Blok I No. 11A, Gadang, Kec. Sukun, Kota Malang, Jawa Timur, [65149]</strong>
                </p>
            </div>
        </div>


        <div class="right-section">
            <div class="right-title">RIWAYAT PENDIDIKAN</div>

            <div class="education">
                <div class="year">2017 - 2023</div>
                <div class="school">
                    MIN 2 KOTA MALANG
                </div>
            </div>

            <div class="education">
                <div class="year">2023 - 2026</div>
                <div class="school">
                    SMP NEGERI 19 MALANG
                </div>
            </div>

            <div class="education">
                <div class="year">2026</div>
                <div class="school">
                    SMA NEGRI 5 MALANG
                </div>
            </div>
        </div>


        <div class="right-section">
            <div class="right-title">PENGALAMAN</div>

            <div class="experience">
                <div class="company">
                  Membuat Infoice Bisnis Keluarga
                </div>
            </div>

            <div class="experience">
                <div class="company">
                    Bisa Membuat Laporan Keuangan
                </div>
            </div>
        </div>

    </div>

</div>

</body>
</html>
