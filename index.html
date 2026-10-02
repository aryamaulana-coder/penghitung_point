<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kalkulator Poin Free Fire - Fastour Epep</title>
    <!-- Bootstrap 5 CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- FontAwesome Icons -->
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
    <style>
        body {
            background-color: #0b0e14;
            color: #ffffff;
            font-family: 'Segoe UI', Roboto, sans-serif;
            min-height: 100vh;
            display: flex;
            align-items: center;
        }
        .card-custom {
            background-color: #161b26;
            border: 2px solid #2e3748;
            border-radius: 16px;
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.6);
        }
        .text-fire {
            color: #ff7700 !important;
            text-shadow: 0 0 10px rgba(255, 102, 0, 0.4);
        }
        .text-subtle-light {
            color: #cbd5e1 !important;
        }
        .text-bright-yellow {
            color: #ffdd00 !important;
        }
        .text-bright-green {
            color: #00ff88 !important;
        }
        .form-control-custom, .form-select-custom {
            background-color: #0d1117 !important;
            color: #ffffff !important;
            border: 1px solid #3b475c !important;
            font-weight: 600;
        }
        .form-control-custom:focus, .form-select-custom:focus {
            border-color: #ff6600 !important;
            box-shadow: 0 0 10px rgba(255, 102, 0, 0.5) !important;
        }
        .btn-fire {
            background: linear-gradient(135deg, #ff6600, #ff0000);
            color: #ffffff;
            border: none;
            font-weight: 700;
            letter-spacing: 0.5px;
            text-shadow: 0 1px 2px rgba(0,0,0,0.5);
            transition: all 0.2s ease-in-out;
        }
        .btn-fire:hover {
            background: linear-gradient(135deg, #ff771a, #e60000);
            color: #ffffff;
            box-shadow: 0 0 12px rgba(255, 102, 0, 0.6);
            transform: translateY(-1px);
        }
    </style>
</head>
<body>

<div class="container py-5">
    <div class="row justify-content-center">
        <div class="col-md-7 col-lg-6">
            <div class="card card-custom p-4 p-md-5">
                
                <!-- Header -->
                <div class="text-center mb-4">
                    <h2 class="fw-bold text-fire mb-2">
                        <i class="fa-solid fa-calculator me-2"></i>KALKULATOR POIN FF
                    </h2>
                    <p class="text-subtle-light mb-0 fs-6">Hitung otomatis total poin placement & kill sesuai standar sistem Free Fire Official.</p>
                </div>

                <!-- Form Kalkulator -->
                <form id="calcForm" onsubmit="event.preventDefault(); calculatePoints();">
                    <div class="mb-3">
                        <label class="form-label text-white fw-bold">Peringkat (Rank Placement)</label>
                        <select id="rank" class="form-select form-select-custom py-2 fs-6">
                            <option value="12">Rank 1 (#1 Booyah) — 12 Poin</option>
                            <option value="9">Rank 2 (#2) — 9 Poin</option>
                            <option value="8">Rank 3 (#3) — 8 Poin</option>
                            <option value="7">Rank 4 (#4) — 7 Poin</option>
                            <option value="6">Rank 5 (#5) — 6 Poin</option>
                            <option value="5">Rank 6 (#6) — 5 Poin</option>
                            <option value="4">Rank 7 (#7) — 4 Poin</option>
                            <option value="3">Rank 8 (#8) — 3 Poin</option>
                            <option value="2">Rank 9 (#9) — 2 Poin</option>
                            <option value="1">Rank 10 (#10) — 1 Poin</option>
                            <option value="0">Rank 11 - 12 — 0 Poin</option>
                        </select>
                    </div>

                    <div class="mb-4">
                        <label class="form-label text-white fw-bold">Jumlah Kill Tim</label>
                        <input type="number" id="kills" class="form-control form-control-custom py-2 fs-6" value="0" min="0" required placeholder="Masukkan total kill">
                    </div>

                    <div class="d-grid gap-2">
                        <button type="submit" class="btn btn-fire fw-bold py-2 fs-5">
                            <i class="fa-solid fa-bolt me-1"></i> Hitung Poin
                        </button>
                        <button type="button" onclick="resetForm()" class="btn btn-outline-secondary text-subtle-light border-secondary fw-bold py-2">
                            <i class="fa-solid fa-rotate-left me-1"></i> Reset
                        </button>
                    </div>
                </form>

                <!-- Box Hasil Hitungan -->
                <div id="resultBox" class="mt-4 p-4 rounded text-center d-none" style="background-color: #0d1117; border: 2px solid #ff6600;">
                    <h6 class="text-subtle-light fw-bold text-uppercase mb-3" style="letter-spacing: 1px;">Rincian Perhitungan</h6>
                    
                    <div class="row g-2 mb-3">
                        <div class="col-6">
                            <div class="p-2 rounded" style="background-color: #161b26; border: 1px solid #2e3748;">
                                <small class="text-subtle-light d-block">Placement Pts</small>
                                <span id="placePts" class="text-bright-yellow fw-bold fs-4">0</span>
                            </div>
                        </div>
                        <div class="col-6">
                            <div class="p-2 rounded" style="background-color: #161b26; border: 1px solid #2e3748;">
                                <small class="text-subtle-light d-block">Kill Pts</small>
                                <span id="killPts" class="text-danger fw-bold fs-4">0</span>
                            </div>
                        </div>
                    </div>

                    <div class="pt-2 border-top border-secondary">
                        <small class="text-subtle-light d-block text-uppercase fw-bold">Total Poin Akhir</small>
                        <h1 class="fw-bold text-bright-green display-4 mb-0" id="totalPts">0</h1>
                    </div>
                </div>

            </div>
        </div>
    </div>
</div>

<script>
function calculatePoints() {
    const placePts = parseInt(document.getElementById('rank').value) || 0;
    const kills = parseInt(document.getElementById('kills').value) || 0;
    const total = placePts + kills;

    document.getElementById('placePts').innerText = placePts;
    document.getElementById('killPts').innerText = kills;
    document.getElementById('totalPts').innerText = total;

    // Tampilkan box hasil
    document.getElementById('resultBox').classList.remove('d-none');
}

function resetForm() {
    document.getElementById('rank').value = "12";
    document.getElementById('kills').value = "0";
    document.getElementById('resultBox').classList.add('d-none');
}
</script>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>