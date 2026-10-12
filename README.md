<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Task Part 1 - Tables</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background-color: #f4f4f9;
            color: #333;
        }
        h2 {
            border-bottom: 2px solid #333;
            padding-bottom: 5px;
            margin-top: 40px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 30px;
            background-color: #fff;
        }
        th, td {
            border: 1px solid #999;
            padding: 8px 12px;
            text-align: center;
            font-size: 14px;
        }
        th {
            background-color: #e2e8f0;
        }
        .header-blue {
            background-color: #3b82f6;
            color: white;
        }
    </style>
</head>
<body>

    <h1>HTML Task Part 1 - Tables</h1>

    <!-- Grade A: Tabel Hasil Ujian -->
    <h2>Grade A</h2>
    <table>
        <thead>
            <tr>
                <th rowspan="2">No</th>
                <th rowspan="2">Nama</th>
                <th colspan="6">Hasil Ujian</th>
                <th rowspan="2">Keterangan</th>
            </tr>
            <tr>
                <th colspan="2">HTML</th>
                <th colspan="2">CSS</th>
                <th colspan="2">JavaScript</th>
            </tr>
            <tr>
                <th></th>
                <th></th>
                <th>Initial</th>
                <th>Final</th>
                <th>Initial</th>
                <th>Final</th>
                <th>Initial</th>
                <th>Final</th>
                <th></th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1</td>
                <td>Bili</td>
                <td>80</td>
                <td>90</td>
                <td>78</td>
                <td>85</td>
                <td>85</td>
                <td>90</td>
                <td>Lulus</td>
            </tr>
            <tr>
                <td>2</td>
                <td>Budi</td>
                <td>75</td>
                <td>90</td>
                <td>88</td>
                <td>90</td>
                <td>80</td>
                <td>85</td>
                <td>Lulus</td>
            </tr>
            <tr>
                <td>3</td>
                <td>Abde</td>
                <td>82</td>
                <td>89</td>
                <td>84</td>
                <td>87</td>
                <td>74</td>
                <td>90</td>
                <td>Lulus</td>
            </tr>
        </tbody>
    </table>

    <!-- Grade B: Laporan Mahasiswa -->
    <h2>Grade B</h2>
    <table>
        <thead>
            <tr>
                <th colspan="4" class="header-blue">Laporan Mahasiswa</th>
            </tr>
            <tr>
                <th colspan="2">Nama</th>
                <th colspan="2">Alamat</th>
            </tr>
            <tr>
                <th>Nama Depan</th>
                <th>Nama Belakang</th>
                <th>Jalan</th>
                <th>Kota</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Raka Gibran</td>
                <td>Buming</td>
                <td>Sudirman</td>
                <td>Bandung</td>
            </tr>
            <tr>
                <td colspan="4"><strong>Hasil Studi</strong></td>
            </tr>
            <tr>
                <td colspan="2"><strong>Mata Kuliah</strong></td>
                <td colspan="2"><strong>Nilai</strong></td>
            </tr>
            <tr>
                <td colspan="2">Matematika</td>
                <td colspan="2">A</td>
            </tr>
            <tr>
                <td colspan="2">Fisika</td>
                <td colspan="2">B</td>
            </tr>
            <tr>
                <td colspan="4"><strong>Catatan Tambahan</strong></td>
            </tr>
            <tr>
                <td colspan="4">Mahasiswa memiliki ketertarikan yang tinggi dalam kegiatan ekstrakurikuler.</td>
            </tr>
        </tbody>
    </table>

    <!-- Grade C: Jadwal Kuliah Basic -->
    <h2>Grade C</h2>
    <table>
        <thead>
            <tr class="header-blue">
                <th>Hari</th>
                <th>Waktu</th>
                <th>Mata Kuliah</th>
                <th>Dosen</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Senin</td>
                <td>08:00 - 10:00</td>
                <td>Kalkulus</td>
                <td>Prof. Ahmad</td>
            </tr>
            <tr>
                <td>Selasa</td>
                <td>09:00 - 11:00</td>
                <td>Algoritma dan Struktur Data</td>
                <td>Dr. Budi</td>
            </tr>
            <tr>
                <td>Rabu</td>
                <td>10:00 - 12:00</td>
                <td>Pemrograman Web</td>
                <td>Dr. Cindy</td>
            </tr>
            <tr>
                <td>Kamis</td>
                <td>08:00 - 10:00</td>
                <td>Jaringan Komputer</td>
                <td>Prof. Elsa</td>
            </tr>
            <tr>
                <td>Jumat</td>
                <td>13:00 - 15:00</td>
                <td>Basis Data</td>
                <td>Dr. Farhan</td>
            </tr>
        </tbody>
    </table>

</body>
</html>
