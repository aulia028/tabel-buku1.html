# tabel-buku1.html
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Tabel Buku</title>
  <style>
    :root { color-scheme: light dark; }
    body {
      font-family: system-ui, -apple-system, "Segoe UI", Roboto, Arial, sans-serif;
      margin: 0; padding: 32px; background: Canvas; color: CanvasText;
    }
    .container { max-width: 900px; margin: 0 auto; }
    h1 { font-size: 1.25rem; margin: 0 0 16px; }
    .table-wrap { overflow-x: auto; border-radius: 12px; border: 1px solid GrayText; }
    table { width: 100%; border-collapse: collapse; min-width: 520px; }
    thead th {
      text-align: left; padding: 12px 14px; font-weight: 600; background: color-mix(in oklab, Canvas 90%, CanvasText 10%);
      position: sticky; top: 0;
    }
    tbody td { padding: 12px 14px; border-top: 1px solid color-mix(in oklab, CanvasText 20%, transparent); }
    tbody tr:nth-child(even) td { background: color-mix(in oklab, Canvas 96%, CanvasText 4%); }
    .num { text-align: center; white-space: nowrap; }
    .harga { text-align: right; white-space: nowrap; font-variant-numeric: tabular-nums; }
    caption {
      caption-side: bottom; text-align: left; padding: 10px 2px; color: GrayText; font-size: .9rem;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Daftar Buku</h1>

    <div class="table-wrap">
      <table>
        <thead>
          <tr>
            <th>Judul Buku</th>
            <th class="num">Nomor Buku</th>
            <th class="harga">Harga</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Algoritma & Struktur Data</td>
            <td class="num">B-001</td>
            <td class="harga">Rp 95.000</td>
          </tr>
          <tr>
            <td>Pemrograman Web Dasar</td>
            <td class="num">B-002</td>
            <td class="harga">Rp 120.000</td>
          </tr>
          <tr>
            <td>Sistem Basis Data</td>
            <td class="num">B-003</td>
            <td class="harga">Rp 110.000</td>
          </tr>
          <tr>
            <td>Jaringan Komputer</td>
            <td class="num">B-004</td>
            <td class="harga">Rp 135.000</td>
          </tr>
          <tr>
            <td>Kecerdasan Buatan Pengantar</td>
            <td class="num">B-005</td>
            <td class="harga">Rp 150.000</td>
          </tr>
        </tbody>
        <caption>Contoh tabel buku. Ganti/ tambah baris pada bagian &lt;tbody&gt; sesuai kebutuhan.</caption>
      </table>
    </div>
  </div>
</body>
</html>
