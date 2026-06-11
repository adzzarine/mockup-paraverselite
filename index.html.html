<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Paraportal — Portal Kebijakan SDM</title>
<style>
  :root {
    --navy: #1B3A5C;
    --teal: #0D7377;
    --teal-l: #14A085;
    --amber: #E67E22;
    --red: #C0392B;
    --slate: #4A5568;
    --slate-l: #718096;
    --bg: #F4F7FA;
    --card: #FFFFFF;
    --border: #D0DCE8;
    --tag-bg: #EBF4FB;
  }
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body { font-family: 'Segoe UI', Arial, sans-serif; background: var(--bg); color: #1A1A1A; min-height: 100vh; }

  /* ─── TOP BAR ─── */
  .topbar {
    background: var(--navy);
    color: white;
    padding: 0 32px;
    height: 56px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    position: sticky;
    top: 0;
    z-index: 100;
    box-shadow: 0 2px 8px rgba(0,0,0,.25);
  }
  .topbar-brand { display: flex; align-items: center; gap: 12px; }
  .topbar-logo {
    width: 32px; height: 32px; border-radius: 8px;
    background: var(--teal); display: flex; align-items: center; justify-content: center;
    font-weight: 800; font-size: 14px; color: white; letter-spacing: -0.5px;
  }
  .topbar-title { font-size: 18px; font-weight: 700; letter-spacing: 0.5px; }
  .topbar-sub { font-size: 12px; color: #A8D4E6; margin-left: 4px; }
  .topbar-meta { font-size: 12px; color: #7BA8C0; }

  /* ─── LAYOUT ─── */
  .layout { display: flex; min-height: calc(100vh - 56px); }

  /* ─── SIDEBAR ─── */
  .sidebar {
    width: 280px; min-width: 280px;
    background: white;
    border-right: 1px solid var(--border);
    padding: 20px 0;
    position: sticky;
    top: 56px;
    height: calc(100vh - 56px);
    overflow-y: auto;
  }
  .sidebar-section { margin-bottom: 24px; }
  .sidebar-label {
    font-size: 10px; font-weight: 700; color: var(--slate-l);
    letter-spacing: 1.2px; text-transform: uppercase;
    padding: 0 20px 8px;
  }
  .filter-btn {
    display: flex; align-items: center; gap: 10px;
    width: 100%; padding: 9px 20px;
    border: none; background: none; cursor: pointer;
    font-size: 13.5px; color: var(--slate);
    text-align: left; transition: all .15s;
    border-left: 3px solid transparent;
  }
  .filter-btn:hover { background: #F0F6FA; color: var(--navy); }
  .filter-btn.active { background: #EBF4FB; color: var(--teal); border-left-color: var(--teal); font-weight: 600; }
  .filter-btn .icon { font-size: 16px; min-width: 20px; }
  .filter-count {
    margin-left: auto; background: var(--border);
    font-size: 11px; font-weight: 600; color: var(--slate);
    padding: 1px 7px; border-radius: 20px;
  }
  .filter-btn.active .filter-count { background: var(--teal); color: white; }
  .sidebar-divider { border: none; border-top: 1px solid var(--border); margin: 4px 0; }

  /* ─── MAIN ─── */
  .main { flex: 1; padding: 28px 32px; overflow-y: auto; }

  /* ─── SEARCH ─── */
  .search-bar {
    display: flex; align-items: center; gap: 12px;
    background: white; border: 1.5px solid var(--border);
    border-radius: 10px; padding: 0 16px;
    margin-bottom: 24px;
    box-shadow: 0 1px 4px rgba(0,0,0,.06);
    transition: border-color .2s;
  }
  .search-bar:focus-within { border-color: var(--teal); box-shadow: 0 0 0 3px rgba(13,115,119,.1); }
  .search-bar svg { color: var(--slate-l); min-width: 18px; }
  .search-bar input {
    flex: 1; border: none; outline: none;
    font-size: 14px; padding: 13px 0; background: none; color: #1A1A1A;
  }
  .search-bar input::placeholder { color: var(--slate-l); }
  .search-clear {
    border: none; background: none; cursor: pointer;
    color: var(--slate-l); padding: 4px; border-radius: 4px; display: none;
    font-size: 18px; line-height: 1;
  }
  .search-clear.visible { display: block; }

  /* ─── RESULTS HEADER ─── */
  .results-header {
    display: flex; align-items: center; justify-content: space-between;
    margin-bottom: 16px;
  }
  .results-count { font-size: 14px; color: var(--slate); }
  .results-count strong { color: var(--navy); font-weight: 700; }
  .view-toggle { display: flex; gap: 4px; }
  .view-btn {
    border: 1px solid var(--border); background: white; border-radius: 6px;
    padding: 6px 10px; cursor: pointer; color: var(--slate-l);
    transition: all .15s; font-size: 14px;
  }
  .view-btn.active { background: var(--navy); color: white; border-color: var(--navy); }

  /* ─── LIFECYCLE BANNER ─── */
  .lifecycle-nav {
    display: flex; gap: 8px; margin-bottom: 20px; flex-wrap: wrap;
  }
  .lc-chip {
    display: flex; align-items: center; gap: 6px;
    padding: 7px 16px; border-radius: 24px; cursor: pointer;
    border: 1.5px solid var(--border); background: white;
    font-size: 13px; font-weight: 500; color: var(--slate);
    transition: all .15s;
  }
  .lc-chip:hover { border-color: var(--teal); color: var(--teal); }
  .lc-chip.active { border-color: transparent; color: white; font-weight: 600; }
  .lc-chip[data-lc="all"].active { background: var(--navy); }
  .lc-chip[data-lc="rekrutmen"].active { background: #2E6DA4; }
  .lc-chip[data-lc="onboarding"].active { background: var(--teal); }
  .lc-chip[data-lc="harian"].active { background: #1E7E34; }
  .lc-chip[data-lc="offboarding"].active { background: #6B2C8D; }

  /* ─── CARD GRID ─── */
  .card-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(340px, 1fr)); gap: 16px; }
  .card-list .card-grid { grid-template-columns: 1fr; }

  /* ─── CARD ─── */
  .card {
    background: white; border-radius: 10px;
    border: 1px solid var(--border);
    padding: 20px;
    cursor: pointer;
    transition: all .18s;
    position: relative;
    overflow: hidden;
  }
  .card:hover { box-shadow: 0 4px 16px rgba(0,0,0,.1); border-color: var(--teal); transform: translateY(-1px); }
  .card::before {
    content: ''; position: absolute; left: 0; top: 0; bottom: 0;
    width: 4px;
  }
  .card[data-lc="rekrutmen"]::before { background: #2E6DA4; }
  .card[data-lc="onboarding"]::before { background: var(--teal); }
  .card[data-lc="harian"]::before { background: #1E7E34; }
  .card[data-lc="offboarding"]::before { background: #6B2C8D; }
  .card-header { display: flex; align-items: flex-start; gap: 12px; margin-bottom: 12px; }
  .card-icon {
    width: 36px; height: 36px; border-radius: 8px;
    display: flex; align-items: center; justify-content: center;
    font-size: 18px; min-width: 36px;
  }
  .card-icon.rekrutmen { background: #E8F0F8; }
  .card-icon.onboarding { background: #E0F4F5; }
  .card-icon.harian { background: #E8F5EA; }
  .card-icon.offboarding { background: #F0EBF8; }
  .card-title-wrap { flex: 1; }
  .card-title { font-size: 14.5px; font-weight: 600; color: var(--navy); line-height: 1.35; margin-bottom: 4px; }
  .card-docid { font-size: 11px; color: var(--slate-l); font-family: monospace; }
  .card-body { font-size: 13px; color: var(--slate); line-height: 1.6; margin-bottom: 14px; }
  .card-tags { display: flex; flex-wrap: wrap; gap: 6px; margin-bottom: 14px; }
  .tag {
    font-size: 11px; font-weight: 500; padding: 3px 9px;
    border-radius: 20px; background: var(--tag-bg); color: var(--teal);
    border: 1px solid #C5E2F0;
  }
  .tag.area { background: #FFF3E0; color: #E67E22; border-color: #F5CBA7; }
  .tag.type { background: #F3EEF9; color: #6B2C8D; border-color: #D7BEF5; }
  .card-footer {
    display: flex; align-items: center; justify-content: space-between;
    border-top: 1px solid var(--border); padding-top: 12px;
  }
  .card-pic { font-size: 12px; color: var(--slate-l); }
  .card-pic strong { color: var(--slate); }
  .card-action {
    font-size: 12px; color: var(--teal); font-weight: 600;
    display: flex; align-items: center; gap: 4px;
    border: none; background: none; cursor: pointer; padding: 4px 8px;
    border-radius: 6px; transition: background .15s;
  }
  .card-action:hover { background: #E0F4F5; }

  /* ─── EMPTY ─── */
  .empty { text-align: center; padding: 80px 20px; color: var(--slate-l); }
  .empty-icon { font-size: 48px; margin-bottom: 16px; }
  .empty h3 { font-size: 18px; color: var(--slate); margin-bottom: 8px; }
  .empty p { font-size: 14px; }

  /* ─── MODAL ─── */
  .modal-overlay {
    display: none; position: fixed; inset: 0;
    background: rgba(0,0,0,.45); z-index: 200;
    align-items: flex-start; justify-content: center;
    padding: 40px 20px; overflow-y: auto;
  }
  .modal-overlay.open { display: flex; }
  .modal {
    background: white; border-radius: 14px; width: 100%; max-width: 760px;
    box-shadow: 0 20px 60px rgba(0,0,0,.25);
    animation: slideUp .2s ease;
  }
  @keyframes slideUp { from { opacity:0; transform:translateY(20px) } to { opacity:1; transform:translateY(0) } }
  .modal-header {
    padding: 28px 32px 20px;
    border-bottom: 1px solid var(--border);
    display: flex; gap: 16px; align-items: flex-start;
  }
  .modal-close {
    margin-left: auto; border: none; background: none; cursor: pointer;
    font-size: 22px; color: var(--slate-l); padding: 4px; border-radius: 6px;
    line-height: 1; transition: all .15s;
  }
  .modal-close:hover { background: var(--bg); color: var(--navy); }
  .modal-body { padding: 24px 32px; }
  .modal-section { margin-bottom: 24px; }
  .modal-section-title {
    font-size: 12px; font-weight: 700; color: var(--slate-l);
    letter-spacing: 1px; text-transform: uppercase; margin-bottom: 10px;
  }
  .modal-meta-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; margin-bottom: 20px; }
  .meta-item { background: var(--bg); border-radius: 8px; padding: 10px 14px; }
  .meta-key { font-size: 11px; color: var(--slate-l); margin-bottom: 3px; }
  .meta-val { font-size: 13px; font-weight: 600; color: var(--navy); }
  .modal-content { font-size: 14px; color: var(--slate); line-height: 1.75; }
  .modal-content ul { padding-left: 20px; }
  .modal-content li { margin-bottom: 6px; }
  .modal-content h4 { font-size: 13px; color: var(--navy); font-weight: 700; margin: 16px 0 8px; }
  .modal-content table { width: 100%; border-collapse: collapse; margin: 12px 0; font-size: 13px; }
  .modal-content th { background: var(--navy); color: white; padding: 8px 12px; text-align: left; font-size: 12px; }
  .modal-content td { padding: 8px 12px; border-bottom: 1px solid var(--border); }
  .modal-content tr:nth-child(even) td { background: var(--bg); }
  .modal-content .info-box {
    background: #EBF4FB; border-left: 4px solid var(--teal);
    padding: 12px 16px; border-radius: 0 8px 8px 0; margin: 12px 0;
    font-size: 13px;
  }
  .modal-content .warn-box {
    background: #FFF3E0; border-left: 4px solid var(--amber);
    padding: 12px 16px; border-radius: 0 8px 8px 0; margin: 12px 0;
    font-size: 13px;
  }
  .modal-tags { display: flex; flex-wrap: wrap; gap: 8px; margin-top: 16px; }
  .modal-links { display: flex; flex-direction: column; gap: 8px; }
  .modal-link {
    display: flex; align-items: center; gap: 8px;
    background: var(--bg); border-radius: 8px; padding: 10px 14px;
    text-decoration: none; color: var(--teal); font-size: 13px; font-weight: 500;
    border: 1px solid var(--border); transition: all .15s;
  }
  .modal-link:hover { background: #E0F4F5; border-color: var(--teal); }
  .modal-footer {
    padding: 16px 32px;
    border-top: 1px solid var(--border);
    display: flex; align-items: center; justify-content: space-between;
    background: var(--bg); border-radius: 0 0 14px 14px;
  }
  .modal-pic-info { font-size: 13px; color: var(--slate); }
  .modal-pic-info strong { color: var(--navy); }

  /* ─── SCROLLBAR ─── */
  ::-webkit-scrollbar { width: 6px; height: 6px; }
  ::-webkit-scrollbar-track { background: transparent; }
  ::-webkit-scrollbar-thumb { background: var(--border); border-radius: 3px; }
  ::-webkit-scrollbar-thumb:hover { background: var(--slate-l); }

  /* ─── HIGHLIGHT ─── */
  mark { background: #FFF3CD; border-radius: 2px; padding: 0 2px; }

  @media (max-width: 900px) {
    .sidebar { display: none; }
    .main { padding: 16px; }
    .card-grid { grid-template-columns: 1fr; }
    .modal-meta-grid { grid-template-columns: 1fr; }
  }
</style>
</head>
<body>

<!-- TOP BAR -->
<div class="topbar">
  <div class="topbar-brand">
    <div class="topbar-logo">P</div>
    <div>
      <span class="topbar-title">PARAPORTAL</span>
      <span class="topbar-sub">Panduan Kebijakan SDM</span>
    </div>
  </div>
  <div class="topbar-meta">PT Paragon Technology and Innovation &nbsp;|&nbsp; Updated Mei 2026</div>
</div>

<div class="layout">

<!-- SIDEBAR -->
<aside class="sidebar">
  <div class="sidebar-section">
    <div class="sidebar-label">Topik / Kategori</div>
    <button class="filter-btn active" data-topic="all" onclick="setTopic('all')">
      <span class="icon">🏠</span> Semua Konten <span class="filter-count" id="cnt-all">0</span>
    </button>
    <hr class="sidebar-divider">
    <button class="filter-btn" data-topic="waktu-kerja" onclick="setTopic('waktu-kerja')">
      <span class="icon">⏰</span> Waktu Kerja &amp; Presensi <span class="filter-count" id="cnt-waktu-kerja">0</span>
    </button>
    <button class="filter-btn" data-topic="cuti" onclick="setTopic('cuti')">
      <span class="icon">🏖️</span> Cuti &amp; Izin <span class="filter-count" id="cnt-cuti">0</span>
    </button>
    <button class="filter-btn" data-topic="perjalanan-dinas" onclick="setTopic('perjalanan-dinas')">
      <span class="icon">✈️</span> Perjalanan Dinas <span class="filter-count" id="cnt-perjalanan-dinas">0</span>
    </button>
    <button class="filter-btn" data-topic="kompensasi" onclick="setTopic('kompensasi')">
      <span class="icon">💰</span> Kompensasi &amp; Gaji <span class="filter-count" id="cnt-kompensasi">0</span>
    </button>
    <button class="filter-btn" data-topic="asuransi" onclick="setTopic('asuransi')">
      <span class="icon">🏥</span> Asuransi &amp; BPJS <span class="filter-count" id="cnt-asuransi">0</span>
    </button>
    <button class="filter-btn" data-topic="benefit" onclick="setTopic('benefit')">
      <span class="icon">🎁</span> Benefit &amp; Klaim <span class="filter-count" id="cnt-benefit">0</span>
    </button>
    <button class="filter-btn" data-topic="fasilitas" onclick="setTopic('fasilitas')">
      <span class="icon">🏢</span> Fasilitas Perusahaan <span class="filter-count" id="cnt-fasilitas">0</span>
    </button>
    <button class="filter-btn" data-topic="rekrutmen" onclick="setTopic('rekrutmen')">
      <span class="icon">🔍</span> Rekrutmen <span class="filter-count" id="cnt-rekrutmen">0</span>
    </button>
    <button class="filter-btn" data-topic="perjanjian-kerja" onclick="setTopic('perjanjian-kerja')">
      <span class="icon">📄</span> Perjanjian Kerja <span class="filter-count" id="cnt-perjanjian-kerja">0</span>
    </button>
    <button class="filter-btn" data-topic="pengembangan" onclick="setTopic('pengembangan')">
      <span class="icon">📈</span> Pengembangan &amp; Rotasi <span class="filter-count" id="cnt-pengembangan">0</span>
    </button>
    <button class="filter-btn" data-topic="er" onclick="setTopic('er')">
      <span class="icon">🤝</span> Employee Relations <span class="filter-count" id="cnt-er">0</span>
    </button>
    <button class="filter-btn" data-topic="onboarding" onclick="setTopic('onboarding')">
      <span class="icon">👋</span> Onboarding <span class="filter-count" id="cnt-onboarding">0</span>
    </button>
    <button class="filter-btn" data-topic="offboarding" onclick="setTopic('offboarding')">
      <span class="icon">🚪</span> Offboarding &amp; Pensiun <span class="filter-count" id="cnt-offboarding">0</span>
    </button>
    <button class="filter-btn" data-topic="surat" onclick="setTopic('surat')">
      <span class="icon">✉️</span> Surat &amp; Dokumen <span class="filter-count" id="cnt-surat">0</span>
    </button>
    <button class="filter-btn" data-topic="mess" onclick="setTopic('mess')">
      <span class="icon">🏠</span> Mess / Asrama <span class="filter-count" id="cnt-mess">0</span>
    </button>
  </div>
</aside>

<!-- MAIN CONTENT -->
<main class="main">

  <!-- SEARCH -->
  <div class="search-bar">
    <svg width="18" height="18" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><circle cx="11" cy="11" r="8"/><path d="m21 21-4.35-4.35"/></svg>
    <input type="text" id="searchInput" placeholder="Cari kebijakan, benefit, cuti, perjalanan dinas…" oninput="onSearch(this.value)">
    <button class="search-clear" id="searchClear" onclick="clearSearch()">×</button>
  </div>

  <!-- LIFECYCLE FILTER -->
  <div class="lifecycle-nav">
    <div class="lc-chip active" data-lc="all" onclick="setLifecycle('all')">🔵 Semua</div>
    <div class="lc-chip" data-lc="rekrutmen" onclick="setLifecycle('rekrutmen')">🔍 Rekrutmen</div>
    <div class="lc-chip" data-lc="onboarding" onclick="setLifecycle('onboarding')">👋 Onboarding</div>
    <div class="lc-chip" data-lc="harian" onclick="setLifecycle('harian')">💼 Pekerjaan Harian</div>
    <div class="lc-chip" data-lc="offboarding" onclick="setLifecycle('offboarding')">🚪 Offboarding</div>
  </div>

  <!-- RESULTS HEADER -->
  <div class="results-header">
    <div class="results-count">Menampilkan <strong id="resultCount">0</strong> konten</div>
    <div class="view-toggle">
      <button class="view-btn active" id="gridBtn" onclick="setView('grid')" title="Grid">⊞</button>
      <button class="view-btn" id="listBtn" onclick="setView('list')" title="List">☰</button>
    </div>
  </div>

  <!-- CARDS -->
  <div id="cardContainer" class="card-grid"></div>
  <div id="emptyState" class="empty" style="display:none">
    <div class="empty-icon">🔎</div>
    <h3>Konten tidak ditemukan</h3>
    <p>Coba kata kunci lain atau ubah filter yang dipilih.</p>
  </div>

</main>
</div>

<!-- MODAL -->
<div class="modal-overlay" id="modalOverlay" onclick="closeModal(event)">
  <div class="modal" id="modalBox">
    <div class="modal-header">
      <div class="card-icon" id="mIcon" style="width:44px;height:44px;border-radius:10px;font-size:22px"></div>
      <div style="flex:1">
        <div id="mDocId" style="font-size:11px;color:var(--slate-l);font-family:monospace;margin-bottom:6px"></div>
        <div id="mTitle" style="font-size:18px;font-weight:700;color:var(--navy);line-height:1.3"></div>
      </div>
      <button class="modal-close" onclick="closeModalBtn()">×</button>
    </div>
    <div class="modal-body">
      <div class="modal-meta-grid">
        <div class="meta-item"><div class="meta-key">Siklus Hidup</div><div class="meta-val" id="mLc"></div></div>
        <div class="meta-item"><div class="meta-key">Subkategori</div><div class="meta-val" id="mSubcat"></div></div>
        <div class="meta-item"><div class="meta-key">Ruang Lingkup</div><div class="meta-val" id="mScope" style="font-size:12px;font-weight:500"></div></div>
        <div class="meta-item"><div class="meta-key">Terakhir Diperbarui</div><div class="meta-val" id="mDate"></div></div>
      </div>
      <div class="modal-section">
        <div class="modal-section-title">Isi Kebijakan</div>
        <div class="modal-content" id="mContent"></div>
      </div>
      <div class="modal-section" id="mLinksSection">
        <div class="modal-section-title">Tautan &amp; Dokumen</div>
        <div class="modal-links" id="mLinks"></div>
      </div>
      <div class="modal-section">
        <div class="modal-section-title">Tag &amp; Klasifikasi</div>
        <div class="modal-tags" id="mTags"></div>
      </div>
    </div>
    <div class="modal-footer">
      <div class="modal-pic-info">PIC: <strong id="mPic"></strong> &nbsp;|&nbsp; <span id="mEmail" style="color:var(--teal)"></span></div>
      <span id="mUpdated" style="font-size:12px;color:var(--slate-l)"></span>
    </div>
  </div>
</div>

<script>
// ══════════════════════════════════════════════════════════════════
// DATA — All Paraportal content extracted from Paraportal Lite v2.0
// ══════════════════════════════════════════════════════════════════
const DATA = [
  {
    id: 1, docId: "HRS-WK-001", icon: "⏰",
    title: "Ketentuan Jam Kerja",
    lc: "harian", topics: ["waktu-kerja"],
    subcat: "Waktu Kerja & Presensi",
    scope: "Seluruh Personel Paragon (HO, DC, Plant)",
    date: "28 Mei 2026",
    pic: "Farah Naila", email: "farah.nzulfa@paracorpgroup.com",
    summary: "Jadwal jam kerja resmi untuk seluruh area (HO, DC, Plant), ketentuan WFH/WFO, dan batas pengisian presensi.",
    tags: ["HO", "DC", "Plant", "WFH", "WFO", "Presensi"],
    links: [{ label: "Panduan GreatDay & Sunfish", url: "https://bit.ly/PanduanESS" }],
    content: `
<h4>Jadwal Jam Kerja</h4>
<table><tr><th>Area</th><th>Hari</th><th>Jam Kerja</th></tr>
<tr><td>Head Office</td><td>Senin – Kamis</td><td>07.30 – 17.00</td></tr>
<tr><td>Head Office</td><td>Jumat</td><td>07.30 – 16.15</td></tr>
<tr><td>DC – Officer ke atas</td><td>Senin – Kamis</td><td>07.30 – 17.00</td></tr>
<tr><td>DC – Officer ke atas</td><td>Jumat</td><td>07.30 – 16.15</td></tr>
<tr><td>DC – Officer ke atas</td><td>Sabtu</td><td>08.00 – 12.15 (lembur wajib, libur 1×/bulan)</td></tr>
<tr><td>DC – Operasional</td><td>Senin – Jumat</td><td>08.00 – 16.30</td></tr>
<tr><td>DC – Operasional</td><td>Sabtu</td><td>08.00 – 12.15</td></tr>
<tr><td>Plant</td><td>Senin – Kamis</td><td>06.55 – 16.00</td></tr>
<tr><td>Plant</td><td>Jumat</td><td>06.55 – 16.30</td></tr>
</table>
<div class="info-box">Presensi diisi melalui Sunfish (sf.dataon.com) atau aplikasi GreatDay. Jam kerja saat WFH dan WFO <strong>tetap sama</strong>. Periode payroll: tanggal 16–15. Batas pengisian presensi: setiap tanggal 17 atau 18 per bulan.</div>
<h4>WFH & WFO</h4>
<ul>
<li>WFO: bekerja penuh di kantor sesuai jam kerja, termasuk visit/shooting/meeting eksternal.</li>
<li>WFO Lapangan: khusus operasional DC yang bekerja di lapangan (Store Leader, Merchandiser, Activation Staff).</li>
<li>Pengisian Additional Status WFH/WFO dilakukan di GreatDay atau Sunfish dan terintegrasi dengan perhitungan payroll.</li>
</ul>`
  },
  {
    id: 2, docId: "HRS-WK-002", icon: "🌙",
    title: "Ketentuan Lembur (Excessive Hour)",
    lc: "harian", topics: ["waktu-kerja"],
    subcat: "Waktu Kerja & Presensi",
    scope: "Seluruh Personel Paragon (Operasional s.d. Executive)",
    date: "28 Mei 2026",
    pic: "Farah Naila", email: "farah.nzulfa@paracorpgroup.com",
    summary: "Ketentuan pengajuan lembur untuk posisi Operasional, Officer, dan Executive, termasuk lembur wajib DC Sabtu.",
    tags: ["Lembur", "HO", "DC", "Plant", "Operasional", "Officer", "Executive"],
    links: [],
    content: `
<ul>
<li>Lembur merupakan kesepakatan antara Personel dan atasan, kecuali kondisi darurat.</li>
<li>Diajukan setelah jam kerja berakhir melalui GreatDay atau Sunfish.</li>
<li>Pengajuan dapat dilakukan dari H-7 hingga maksimal H+7 setelah lembur dilaksanakan.</li>
<li>Pengajuan yang disetujui melewati cut-off presensi masuk ke payroll bulan berikutnya.</li>
</ul>
<h4>Posisi Operasional</h4>
<ul>
<li>Hari kerja: minimal 1 jam; potongan istirahat 30 menit setelah pukul 18.00.</li>
<li>Hari libur: minimal 1 jam, tidak ada batas maksimal, tidak ada potongan istirahat.</li>
</ul>
<h4>Posisi Officer & Executive</h4>
<ul>
<li>Hari kerja: diajukan setelah bekerja minimal 2 jam; maksimal pengajuan 3 jam.</li>
<li>Hari libur: dari jam mulai bekerja sampai selesai; maksimal pengajuan 10 jam.</li>
</ul>
<h4>DC Sabtu</h4>
<div class="info-box">Lembur Sabtu pukul 08.00–12.15 bagi Personel DC bersifat wajib dan tidak perlu diajukan terpisah. Jika bekerja melebihi pukul 12.15, ajukan lembur mulai pukul 12.15.</div>
<div class="warn-box">Perjalanan antar lokasi kerja (HO ↔ Plant ↔ DC) tidak dihitung sebagai lembur.</div>`
  },
  {
    id: 3, docId: "HRS-CT-001", icon: "🏖️",
    title: "Cuti Tahunan",
    lc: "harian", topics: ["cuti"],
    subcat: "Cuti & Kehadiran",
    scope: "Seluruh Personel Paragon",
    date: "28 Mei 2026 (berlaku 1 Juli 2025 untuk masa kerja < 12 bln)",
    pic: "PIC HR Area", email: "",
    summary: "Hak cuti tahunan (12 hari), ketentuan masa berlaku, penggunaan, dan cara pengajuan melalui GreatDay/Sunfish.",
    tags: ["Cuti Tahunan", "HO", "DC", "Plant", "PKWT", "PKWTT"],
    links: [],
    content: `
<ul>
<li>Personel yang telah bekerja 12 bulan berturut-turut (dari PKWT 1) berhak atas <strong>12 hari kerja</strong> cuti tahunan.</li>
<li>Masa berlaku cuti: 12 bulan dan dapat diperpanjang 6 bulan.</li>
<li>Permohonan diajukan minimal 1 minggu sebelum pengambilan dengan persetujuan atasan.</li>
<li>Cuti yang tidak digunakan setelah masa berlaku akan gugur/hangus.</li>
<li>Bagi Personel yang berakhir masa kerja (resign, habis kontrak, pensiun), sisa cuti dapat diuangkan maksimal 12 hari.</li>
</ul>
<h4>Masa Kerja < 12 Bulan (berlaku 1 Juli 2025)</h4>
<ul>
<li>Hak cuti diberikan <strong>1 hari per bulan</strong>, terhitung sejak bulan pertama bekerja.</li>
<li>Masa berlaku cuti: 12 bulan sejak hak diperoleh, dapat diperpanjang hingga akhir Juni berikutnya.</li>
<li>Hak cuti tahun berikutnya diberikan setiap bulan Januari.</li>
</ul>
<h4>Khusus Operasional Plant</h4>
<ul>
<li>Cuti tahunan diisi ulang setiap bulan Januari.</li>
<li>Tidak diperkenankan cuti setengah hari atau advance leave.</li>
</ul>
<h4>Cara Pengajuan via HRIS</h4>
<ul>
<li><strong>Sunfish:</strong> Time and Attendance → Leave → Leave Request → klik Add (+) → isi form → Ajukan ke Approver.</li>
<li><strong>GreatDay:</strong> klik Ikon Cuti → +Permintaan Baru → isi form → Ajukan ke Approver.</li>
<li><strong>Pembatalan cuti:</strong> ajukan melalui Leave Cancellation Request di Sunfish atau GreatDay.</li>
</ul>`
  },
  {
    id: 4, docId: "HRS-CT-002", icon: "🎊",
    title: "Cuti Khusus",
    lc: "harian", topics: ["cuti"],
    subcat: "Cuti & Kehadiran",
    scope: "Seluruh Personel Paragon",
    date: "28 Mei 2026",
    pic: "PIC HR Area", email: "",
    summary: "Cuti melahirkan, keguguran, kematian, pernikahan, dan khitanan/baptis beserta durasi dan dokumen yang diperlukan.",
    tags: ["Cuti Khusus", "Melahirkan", "Kematian", "Pernikahan", "Khitan"],
    links: [],
    content: `
<ul>
<li>Permohonan diajukan minimal 7 hari sebelum tanggal pengambilan, kecuali cuti kematian.</li>
<li>Cuti khusus harus diambil secara berturut-turut; dengan persetujuan atasan, dapat diambil paling lambat 1 minggu setelah kejadian.</li>
</ul>
<table>
<tr><th>Jenis Cuti Khusus</th><th>Durasi</th><th>Lampiran</th></tr>
<tr><td>Melahirkan (Personel wanita)</td><td>3 bulan kalender (1,5 bln sebelum + 1,5 bln sesudah)</td><td>Surat Keterangan Dokter</td></tr>
<tr><td>Keguguran (Personel wanita)</td><td>Sesuai SKD, maks. 1,5 bulan</td><td>Surat Keterangan Dokter</td></tr>
<tr><td>Istri melahirkan/keguguran (Personel pria)</td><td>2 hari</td><td>Surat Keterangan Dokter</td></tr>
<tr><td>Kematian keluarga inti (suami/istri/anak/orang tua/mertua/kakek/nenek/kakak/adik)</td><td>2 hari</td><td>Surat kematian</td></tr>
<tr><td>Kematian keluarga dalam satu rumah</td><td>1 hari</td><td>Surat kematian</td></tr>
<tr><td>Pernikahan Personel</td><td>3 hari</td><td>Undangan pernikahan</td></tr>
<tr><td>Pernikahan anak Personel</td><td>2 hari</td><td>Undangan + KK</td></tr>
<tr><td>Khitanan/pembaptisan anak Personel</td><td>2 hari</td><td>Surat pendaftaran/keterangan</td></tr>
</table>`
  },
  {
    id: 5, docId: "HRS-CT-003", icon: "⏸️",
    title: "Cuti di Luar Tanggungan (Unpaid Leave)",
    lc: "harian", topics: ["cuti"],
    subcat: "Cuti & Kehadiran",
    scope: "Seluruh Personel Paragon",
    date: "28 Mei 2026",
    pic: "PIC Payroll Area", email: "",
    summary: "Ketentuan cuti tanpa upah, batas maksimal pengambilan, dan syarat pengajuan untuk keperluan penting.",
    tags: ["Cuti", "Unpaid Leave", "Tanpa Upah"],
    links: [],
    content: `
<ul>
<li>Dapat diajukan ketika Advance Leave sudah habis digunakan.</li>
<li>Untuk keperluan penting yang tidak dapat ditunda: maksimum <strong>5 hari kerja</strong> berturut-turut.</li>
<li>Personel dengan masa kerja minimal 1 tahun dapat mengajukan izin tanpa upah hingga <strong>30 hari kalender</strong>. Permohonan diajukan tertulis minimal 1 bulan sebelumnya.</li>
<li>Selama cuti di luar tanggungan, Personel tidak mendapatkan upah sesuai durasi pengambilan.</li>
</ul>
<div class="info-box">PIC Payroll: Officer & Executive — Sari Nuryatini | Operasional HO & DC — Dia Primasari | Operator Plant — Suci Rosita | Operasional Plant — Rika Andriyani Putri</div>`
  },
  {
    id: 6, docId: "HRS-CT-004", icon: "⏩",
    title: "Advance Leave",
    lc: "harian", topics: ["cuti"],
    subcat: "Cuti & Kehadiran",
    scope: "Seluruh Personel Paragon",
    date: "28 Mei 2026",
    pic: "PIC HR Area", email: "",
    summary: "Pengambilan jatah cuti lebih awal bagi Personel yang belum memiliki atau sudah menghabiskan cuti tahunan.",
    tags: ["Cuti", "Advance Leave"],
    links: [],
    content: `
<ul>
<li>Advance Leave adalah pengambilan jatah cuti lebih awal. Maksimal pengambilan: <strong>6 hari</strong>.</li>
<li>Ajukan melalui GreatDay atau Sunfish.</li>
<li>Pilih jenis cuti: Cuti Tahunan atau Cuti Besar (bagi Personel di tahun ke-7, ke-8, dan kelipatannya).</li>
<li>Sistem akan otomatis menghitung pengurangan jatah cuti tahun berikutnya.</li>
</ul>
<div class="warn-box">Personel Operator dan Operasional Plant tidak diperkenankan mengajukan Advance Leave.</div>`
  },
  {
    id: 7, docId: "HRS-CT-005", icon: "🌟",
    title: "Tambahan Istirahat Tahunan (Cuti Besar)",
    lc: "harian", topics: ["cuti"],
    subcat: "Cuti & Kehadiran",
    scope: "Personel Tetap Paragon (masa kerja 6 tahun berturut-turut)",
    date: "28 Mei 2026",
    pic: "PIC HR Area", email: "",
    summary: "Hak cuti besar bagi karyawan tetap setelah 6 tahun masa kerja berturut-turut.",
    tags: ["Cuti Besar", "PKWTT", "Tenure 6 Tahun"],
    links: [],
    content: `
<ul>
<li>Diberikan kepada Karyawan Tetap setelah <strong>6 tahun bekerja berturut-turut</strong> (dan pada setiap kelipatannya).</li>
<li>Tambahan Istirahat Tahunan akan <strong>menggugurkan Cuti Tahunan</strong> pada tahun tersebut.</li>
<li>Apabila tidak digunakan setelah masa berlaku habis, hak ini akan gugur/hangus dan tidak dapat diuangkan.</li>
</ul>`
  },
  {
    id: 8, docId: "HRS-CT-001b", icon: "🤒",
    title: "Izin Sakit",
    lc: "harian", topics: ["cuti"],
    subcat: "Cuti & Kehadiran",
    scope: "Seluruh Personel Paragon",
    date: "28 Mei 2026",
    pic: "PIC HR Area", email: "",
    summary: "Ketentuan izin sakit dengan dan tanpa Surat Keterangan Dokter (SKD).",
    tags: ["Izin Sakit", "SKD", "Operasional", "Plant"],
    links: [],
    content: `
<ul>
<li>Izin sakit diajukan sesuai Surat Keterangan Dokter (SKD).</li>
<li>Tanpa SKD: ajukan dengan jenis Cuti Tahunan, atau Cuti di Luar Tanggungan jika jatah cuti habis.</li>
<li>Khusus Operator & Operasional Plant tanpa SKD: dapat mengajukan izin sakit yang memotong cuti tahunan secara otomatis.</li>
<li>Personel sakit saat bekerja: dapat pulang lebih awal dengan izin atasan atau SKD, lalu ajukan izin sakit di hari berikutnya.</li>
</ul>
<div class="warn-box">SKD dari Telemedicine tidak diperbolehkan. Gunakan surat dari dokter fisik/RS rekanan.</div>`
  },
  {
    id: 9, docId: "HRS-PD-001", icon: "✈️",
    title: "Perjalanan Dinas (Business Trip)",
    lc: "harian", topics: ["perjalanan-dinas"],
    subcat: "Dukungan Kerja",
    scope: "Seluruh Personel Paragon",
    date: "28 Mei 2026",
    pic: "Halimah Nur Rizkiyati", email: "halimah.nurr@paracorpgroup.com",
    summary: "Alur pengajuan perjadin individu & group, standar biaya transportasi/hotel/uang makan DN dan LN, dan daftar travel agent.",
    tags: ["Perjadin", "Dalam Negeri", "Luar Negeri", "Paratrip", "HO", "DC", "Plant"],
    links: [
      { label: "Panduan Visa Guidebook", url: "https://bit.ly/VisaGuidebook" },
      { label: "Antavaya Travel", url: "https://paragon.antavaya.com/" },
      { label: "Dwidaya Travel", url: "https://paragoncorp.resvoyage.com/" },
    ],
    content: `
<ul>
<li>Biaya perjadin adalah pengeluaran bisnis, bukan tunjangan pribadi.</li>
<li>Jarak minimal: <strong>50 km</strong> dari area kerja penempatan/coverage area.</li>
<li>Lama perjadin maksimal: <strong>14 hari</strong>.</li>
</ul>
<h4>Alur Pengajuan (Individu)</h4>
<ul>
<li>Ajukan via Paratrip minimal <strong>7 hari</strong> sebelum keberangkatan DN atau <strong>14 hari</strong> untuk LN.</li>
<li>Disetujui atasan; perjadin LN memerlukan approval EVP/VP.</li>
<li>Dapatkan kode unik → gunakan saat memesan melalui travel agent.</li>
<li>Uang saku & uang makan diproses oleh Account Payable (AP).</li>
</ul>
<h4>Biaya Perjadin Dalam Negeri</h4>
<table>
<tr><th>Komponen</th><th>Ketentuan</th></tr>
<tr><td>Pesawat</td><td>Kelas Ekonomi</td></tr>
<tr><td>Kereta Api</td><td>Kelas Eksekutif</td></tr>
<tr><td>Hotel</td><td>Maks. Rp 500.000/malam (bintang 2)</td></tr>
<tr><td>Uang Makan</td><td>Rp 80.000/malam</td></tr>
<tr><td>Uang Saku</td><td>Rp 85.000/malam</td></tr>
</table>
<h4>Kelas Penerbangan Internasional</h4>
<table>
<tr><th>Durasi</th><th>Kelas</th></tr>
<tr><td>&lt; 3 jam</td><td>Ekonomi</td></tr>
<tr><td>3 – &lt; 6 jam</td><td>Ekonomi Premium (extra legroom)</td></tr>
<tr><td>6 – &lt; 8 jam (overnight)</td><td>Bisnis (maks. 4× harga ekonomi)</td></tr>
<tr><td>≥ 8 jam</td><td>Bisnis (maks. 4× harga ekonomi)</td></tr>
</table>
<h4>Biaya Perjadin Luar Negeri</h4>
<table>
<tr><th>Area</th><th>Hotel</th><th>Uang Makan</th><th>Uang Saku</th></tr>
<tr><td>Area 1 (Singapura, Jepang, Korea, China, UEA, AS, Eropa, dll.)</td><td>Maks. Rp 2.500.000</td><td>Rp 550.000</td><td>Rp 200.000</td></tr>
<tr><td>Area 2 (Selain Area 1)</td><td>Maks. Rp 2.000.000</td><td>Rp 400.000</td><td>Rp 200.000</td></tr>
</table>`
  },
  {
    id: 10, docId: "HRS-CB-001", icon: "💵",
    title: "Uang Kompensasi PKWT",
    lc: "offboarding", topics: ["kompensasi", "offboarding"],
    subcat: "Penghargaan Finansial / Offboarding",
    scope: "Seluruh Personel PKWT Paragon",
    date: "28 Mei 2026",
    pic: "Sari Nuryatini / Dia Primasari / Rika Andriyani",
    email: "sari.nuryatini@paracorpgroup.com",
    summary: "Dasar hukum dan ketentuan pemberian uang kompensasi bagi Personel PKWT saat kontrak berakhir.",
    tags: ["PKWT", "Kompensasi", "Offboarding", "UU Ketenagakerjaan"],
    links: [],
    content: `
<ul>
<li>Berdasarkan UU No. 11 Tahun 2020 dan PP No. 35 Tahun 2021, Perusahaan wajib memberikan Uang Kompensasi kepada Pekerja PKWT yang masa kerjanya minimal <strong>1 bulan</strong> secara terus-menerus.</li>
<li>Uang Kompensasi diberikan pada saat PKWT berakhir.</li>
</ul>
<div class="warn-box">Uang Kompensasi <strong>tidak diberikan</strong> apabila: (1) masa kerja kurang dari 1 bulan, (2) PKWT berakhir karena meninggal dunia/putusan pengadilan/keadaan tertentu dalam perjanjian, (3) pekerja adalah TKA, atau (4) Personel tidak menyelesaikan periode kontrak.</div>`
  },
  {
    id: 11, docId: "HRS-CB-002", icon: "📋",
    title: "Slip Gaji & Payroll FAQ",
    lc: "harian", topics: ["kompensasi"],
    subcat: "Penghargaan Finansial",
    scope: "Seluruh Personel Paragon",
    date: "28 Mei 2026",
    pic: "Sari Nuryatini / Dia Primasari / Rika Andriyani",
    email: "sari.nuryatini@paracorpgroup.com",
    summary: "Akses slip gaji melalui Sunfish dan GreatDay, FAQ payroll, komponen gaji, dan informasi BPJS di slip gaji.",
    tags: ["Gaji", "Slip Gaji", "Payroll", "Sunfish", "GreatDay"],
    links: [],
    content: `
<p>Akses slip gaji melalui Web Sunfish (sf.dataon.com) atau Aplikasi GreatDay (menu Payslip).</p>
<h4>FAQ Payroll</h4>
<table>
<tr><th>Pertanyaan</th><th>Jawaban</th></tr>
<tr><td>Komponen transport tidak muncul?</td><td>Transport ditentukan jumlah WFO. Periksa input WFO/WFH di Sunfish.</td></tr>
<tr><td>Gaji pokok tidak sesuai offering?</td><td>Periode presensi dihitung 16–15. Jika bergabung setelah tanggal 15, gaji pertama dihitung prorata.</td></tr>
<tr><td>Klaim Sunfish masuk ke komponen apa?</td><td>Kacamata → EyeWellness Assistance | HP → PhonePlus Assistance | Lainnya → Reimbursement.</td></tr>
<tr><td>Nomor BPJS TK/Kesehatan di mana?</td><td>Pada slip gaji yang diunduh melalui aplikasi GreatDay.</td></tr>
</table>`
  },
  {
    id: 12, docId: "HRS-CB-007", icon: "🧾",
    title: "Bukti Potong PPh 21",
    lc: "harian", topics: ["kompensasi"],
    subcat: "Penghargaan Finansial",
    scope: "Personel yang memiliki NPWP",
    date: "28 Mei 2026",
    pic: "Eka Karunia", email: "eka.karunia@paracorpgroup.com",
    summary: "Cara mengakses Bukti Potong PPh 21 dan kewajiban pelaporan SPT Tahunan melalui Coretax.",
    tags: ["Pajak", "PPh 21", "SPT", "NPWP"],
    links: [],
    content: `
<ul>
<li>Akses melalui GreatDay (menu Payslip) atau Sunfish (menu Payslip → My Tax Form).</li>
<li>Personel wajib melaporkan SPT PPh Pribadi Tahunan secara mandiri. Batas pelaporan: <strong>31 Maret</strong> setiap tahun.</li>
<li>Bukti pelaporan dapat diunduh secara mandiri melalui Coretax.</li>
</ul>`
  },
  {
    id: 13, docId: "HRS-CB-003", icon: "🏥",
    title: "Asuransi Kesehatan Admedika",
    lc: "onboarding", topics: ["asuransi"],
    subcat: "Asuransi & Kesehatan",
    scope: "Personel Tetap Paragon dan Anggota Keluarga",
    date: "28 Mei 2026",
    pic: "Evi Febriani", email: "evi.febriani@paracorpgroup.com",
    summary: "Manfaat asuransi Admedika untuk Personel dan keluarga: rawat inap, rawat jalan, maternitas, gigi, dan klaim reimbursement.",
    tags: ["Admedika", "Asuransi", "Rawat Inap", "Rawat Jalan", "Maternitas", "PKWTT"],
    links: [{ label: "Pemutakhiran Data & Pendaftaran Benefit", url: "https://bit.ly/PendaftaranBenefit-Paragon" }],
    content: `
<ul>
<li>Periode renewal: 15 Agustus 2025 – 14 Agustus 2026.</li>
<li><strong>Manfaat Personel:</strong> Rawat inap, rawat jalan, gigi dasar, maternitas, kecelakaan, reimbursement santunan melahirkan BPJS, penyakit kritis, telemedicine (Good Doctor & Alodokter).</li>
<li><strong>Manfaat Keluarga:</strong> Rawat inap, rawat jalan, gigi dasar, maternitas, reimbursement santunan melahirkan BPJS, penyakit kritis, telemedicine.</li>
</ul>
<h4>Cara Klaim Reimbursement</h4>
<ul>
<li>Klaim ≤ Rp 2.000.000: ajukan via e-claim di aplikasi MyAdMedika (tanpa kirim dokumen asli).</li>
<li>Klaim > Rp 2.000.000: kirimkan dokumen asli ke PIC HR area masing-masing.</li>
<li>Masa berlaku klaim: maksimal <strong>60 hari</strong> dari tanggal kuitansi.</li>
</ul>
<h4>Imunisasi yang Dijamin</h4>
<ul>
<li>Anak (maks. usia 5 tahun): BCG, DPT, Polio, Campak, Hepatitis B, Typhoid, Varisella, HIB, PCV, Rotavirus, Influenza, MMR, Hepatitis A.</li>
<li>Dewasa (Personel & pasangan): Influenza dan HPV (Cervix).</li>
</ul>
<h4>Pendaftaran Anggota Keluarga</h4>
<p>Ajukan melalui tautan Pemutakhiran Data. Lampirkan KK/buku nikah (pasangan) atau KK/akta lahir (anak).</p>`
  },
  {
    id: 14, docId: "HRS-CB-003a", icon: "🧠",
    title: "Layanan Kesehatan Mental",
    lc: "harian", topics: ["asuransi"],
    subcat: "Kesehatan & Perlindungan",
    scope: "Personel Aktif Paragon",
    date: "15 September 2025",
    pic: "Evi Febriani", email: "evi.febriani@paracorpgroup.com",
    summary: "Akses konsultasi dokter perusahaan dan rujukan psikiater RS rekanan Admedika.",
    tags: ["Kesehatan Mental", "Konsultasi", "Psikiater", "Admedika"],
    links: [{ label: "Daftar Konsultasi Dokter Perusahaan", url: "https://bit.ly/telekonsultasipti" }],
    content: `
<ul>
<li>Personel mendaftar sesi konsultasi ke dokter perusahaan melalui <a href="https://bit.ly/telekonsultasipti" target="_blank">bit.ly/telekonsultasipti</a>.</li>
<li>Jadwal konsultasi tersedia pada hari Selasa, Rabu, atau Jumat.</li>
<li>Dokter memberikan saran atau surat rujukan ke Psikiater jika diperlukan.</li>
<li>Personel yang dirujuk dapat mengunjungi RS rekanan Admedika dengan surat rujukan.</li>
</ul>
<div class="info-box">Kerahasiaan data dan detail permasalahan hanya disimpan oleh dokter perusahaan dan Psikiater, sesuai kode etik profesi.</div>`
  },
  {
    id: 15, docId: "HRS-CB-003b", icon: "🤰",
    title: "Asuransi Maternitas Admedika",
    lc: "harian", topics: ["asuransi"],
    subcat: "Kesehatan & Perlindungan",
    scope: "Personel wanita (sudah menikah) dan Istri Personel Pria Karyawan Tetap",
    date: "28 Mei 2026",
    pic: "Evi Febriani", email: "evi.febriani@paracorpgroup.com",
    summary: "Manfaat maternitas asuransi Admedika: persalinan, keguguran, perawatan sebelum/sesudah melahirkan.",
    tags: ["Maternitas", "Melahirkan", "Keguguran", "Admedika", "PKWTT"],
    links: [],
    content: `
<ul>
<li>Persalinan normal oleh dokter/bidan, operasi caesar, keguguran/kuretase dengan alasan medis.</li>
<li>Perawatan sebelum dan sesudah melahirkan (termasuk periksa kehamilan oleh bidan/dokter spesialis).</li>
<li>Manfaat sesudah melahirkan berlaku maks. <strong>40 hari</strong> setelah persalinan atau <strong>21 hari</strong> setelah keguguran.</li>
<li>Berlaku untuk: Personel wanita yang sudah menikah (karyawan tetap) dan istri Personel pria karyawan tetap (maks. usia 45 tahun).</li>
</ul>`
  },
  {
    id: 16, docId: "HRS-CB-004", icon: "💊",
    title: "BPJS Kesehatan",
    lc: "onboarding", topics: ["asuransi"],
    subcat: "Asuransi & Kesehatan",
    scope: "Seluruh Personel Paragon",
    date: "28 Mei 2026",
    pic: "Uul Maria Ulfah", email: "uul.mulfah@paracorpgroup.com",
    summary: "Iuran, prosedur pendaftaran keluarga, mutasi BPJS, dan pindah faskes.",
    tags: ["BPJS", "Kesehatan", "JKN"],
    links: [{ label: "Daftar Anggota Keluarga BPJS", url: "http://bit.ly/daftarasuransi" }],
    content: `
<ul>
<li>Iuran: <strong>1% Pekerja</strong> dan <strong>4% Perusahaan</strong> (dari upah yang dilaporkan).</li>
<li>Pendaftaran anggota keluarga: berikan KTP/KK ke HR atau daftar di <a href="http://bit.ly/daftarasuransi">bit.ly/daftarasuransi</a>. Maks. 3 anak ditanggung perusahaan.</li>
<li>Mutasi BPJS mandiri ke Perusahaan: lampirkan kartu BPJS, KTP, KK, dan bukti bayar tagihan bulan terakhir (syarat: tidak ada tunggakan).</li>
<li>Batas pengajuan pendaftaran/mutasi: setiap tanggal <strong>14</strong> per bulan.</li>
<li>Pindah faskes: lakukan secara mandiri melalui aplikasi JKN Mobile.</li>
</ul>`
  },
  {
    id: 17, docId: "HRS-CB-005", icon: "🛡️",
    title: "BPJS Ketenagakerjaan",
    lc: "onboarding", topics: ["asuransi"],
    subcat: "Asuransi & Kesehatan",
    scope: "Seluruh Personel Paragon",
    date: "28 Mei 2026",
    pic: "Evi Febriani", email: "evi.febriani@paracorpgroup.com",
    summary: "Program JKK, JKM, JHT, dan JP: manfaat, iuran, dan ketentuan pencairan.",
    tags: ["BPJS", "JKK", "JKM", "JHT", "JP", "Ketenagakerjaan"],
    links: [],
    content: `
<table>
<tr><th>Program</th><th>Manfaat Utama</th><th>Iuran</th></tr>
<tr><td>JKK</td><td>Perlindungan kecelakaan kerja, termasuk perjalanan rumah-kantor & penyakit akibat kerja.</td><td>Ditanggung Perusahaan</td></tr>
<tr><td>JKM</td><td>Uang tunai ahli waris Rp 42 juta, santunan berkala 24 bulan, biaya pemakaman Rp 10 juta, beasiswa 2 anak maks. Rp 174 juta.</td><td>Ditanggung Perusahaan</td></tr>
<tr><td>JHT</td><td>Akumulasi iuran + hasil pengembangan. Cek saldo via aplikasi JMO.</td><td>2% Pekerja + 3,7% Perusahaan</td></tr>
<tr><td>JP</td><td>Dibayar bulanan saat pensiun, cacat total tetap, atau kepada ahli waris.</td><td>1% Pekerja + 2% Perusahaan</td></tr>
</table>
<div class="warn-box">Saldo BPJS Ketenagakerjaan tidak dapat dicairkan selama Personel masih aktif bekerja.</div>`
  },
  {
    id: 18, docId: "HRS-CB-006a", icon: "🎓",
    title: "Beasiswa Anak",
    lc: "harian", topics: ["benefit"],
    subcat: "Implementasi Manfaat",
    scope: "Personel dengan masa kerja min. 1 tahun (dari PKWT 1), jenjang TK–PTN",
    date: "28 Mei 2026",
    pic: "Yuyun Haryuni", email: "yuyun.haryuni@paracorpgroup.com",
    summary: "Uang pangkal, SPP bulanan, dan UKT PTN untuk anak Personel: plafon, syarat, dan cara pengajuan via Sunfish.",
    tags: ["Beasiswa", "Anak", "Pendidikan", "UKT", "SPP"],
    links: [],
    content: `
<h4>Uang Pangkal</h4>
<ul>
<li>Diberikan saat anak memasuki semester ganjil jenjang pendidikan baru (tidak bisa backdated).</li>
<li>Plafon: TK Rp 1.000.000 | SD Rp 1.250.000 | SMP Rp 2.200.000 | SMA Rp 3.500.000 | PTN Rp 5.000.000/semester.</li>
<li>Berkas: KK, surat keterangan sekolah jenjang baru, kuitansi asli.</li>
</ul>
<h4>SPP Bulanan</h4>
<ul>
<li>Berlaku TK–SMA untuk karyawan tetap atau PKWT min. 1 tahun.</li>
<li>Plafon: TK Rp 85.000 | SD Rp 95.000 | SMP Rp 125.000 | SMA Rp 350.000/bulan.</li>
<li>Bonus nilai: rata-rata >80 tambah Rp 200.000/semester; rata-rata >90 tambah Rp 300.000/semester.</li>
<li>Berkas: KK dan rapor semester sebelumnya.</li>
</ul>
<h4>Uang Kuliah Tunggal (UKT)</h4>
<ul>
<li>Untuk anak di PTN dengan IPK minimal 2,75.</li>
<li>Plafon: Rp 5.000.000/semester.</li>
</ul>
<div class="info-box">Pengajuan melalui Sunfish (ESS Beasiswa). Cut-off: 15 Juni (semester ganjil) dan 15 Desember (semester genap).</div>`
  },
  {
    id: 19, docId: "HRS-CB-006b", icon: "💍",
    title: "Hadiah Pernikahan",
    lc: "harian", topics: ["benefit"],
    subcat: "Implementasi Manfaat",
    scope: "Personel dengan masa kerja min. 1 tahun",
    date: "28 Mei 2026",
    pic: "Maya Mufhida (Karangan Bunga)", email: "maya.mufhida@paracorpgroup.com",
    summary: "Hadiah uang dan karangan bunga bagi Personel atau anak Personel yang menikah.",
    tags: ["Pernikahan", "Life Event", "Hadiah"],
    links: [],
    content: `
<table>
<tr><th>Manfaat</th><th>Nominal</th><th>Cara Pengajuan</th></tr>
<tr><td>Karangan Bunga (Personel/Anak)</td><td>—</td><td>Ajukan maks. H-7 melalui surel ke PIC. Tanpa syarat min. masa kerja.</td></tr>
<tr><td>Hadiah Pernikahan Personel</td><td>Rp 1.000.000</td><td>Melalui Sunfish, paling lambat 3 bulan setelah pernikahan.</td></tr>
<tr><td>Hadiah Pernikahan Anak Personel</td><td>Rp 500.000 (maks. 3 anak)</td><td>Melalui Sunfish, paling lambat 3 bulan setelah pernikahan.</td></tr>
</table>`
  },
  {
    id: 20, docId: "HRS-CB-006c", icon: "🕯️",
    title: "Santunan Duka Cita",
    lc: "harian", topics: ["benefit"],
    subcat: "Implementasi Manfaat",
    scope: "Personel dengan masa kerja min. 1 tahun",
    date: "28 Mei 2026",
    pic: "PIC HR Area", email: "",
    summary: "Santunan uang dan karangan bunga duka cita bagi Personel atau anggota keluarga yang meninggal dunia.",
    tags: ["Duka Cita", "Santunan", "Kematian", "Life Event"],
    links: [],
    content: `
<table>
<tr><th>Kondisi</th><th>Nominal Santunan</th></tr>
<tr><td>Personel meninggal dunia</td><td>Rp 2.000.000</td></tr>
<tr><td>Suami/istri/anak kandung/angkat (dalam KK)</td><td>Rp 1.000.000</td></tr>
<tr><td>Orang tua kandung/angkat (dalam KK)</td><td>Rp 1.000.000</td></tr>
<tr><td>Janin usia ≥ 7 bulan meninggal</td><td>Rp 500.000</td></tr>
</table>
<ul>
<li>Karangan bunga diberikan tanpa syarat minimal masa kerja.</li>
<li>Berkas: fotokopi KK dan surat keterangan kematian.</li>
<li>Pengajuan santunan: melalui Sunfish. Karangan bunga: hubungi PIC HR terkait.</li>
</ul>`
  },
  {
    id: 21, docId: "HRS-CB-006d", icon: "👓",
    title: "Klaim Kacamata",
    lc: "harian", topics: ["benefit"],
    subcat: "Implementasi Manfaat",
    scope: "Karyawan Tetap Paragon",
    date: "28 Mei 2026",
    pic: "Farah Naila", email: "farah.nzulfa@paracorpgroup.com",
    summary: "Klaim kacamata/lensa kontak untuk karyawan tetap: plafon, frekuensi, dan cara pengajuan via Sunfish.",
    tags: ["Kacamata", "Benefit", "PKWTT"],
    links: [],
    content: `
<ul>
<li>Kacamata lengkap (frame + lensa): dapat diklaim setiap <strong>2 tahun</strong> sekali.</li>
<li>Lensa saja: dapat diklaim setiap <strong>1 tahun</strong> sekali. Refill setiap 16 Agustus.</li>
<li>Plafon kacamata lengkap: 100% dari plafon | Lensa progresif/bifokus: maks. 50% | Lensa single vision: maks. 25%.</li>
<li>Nominal plafon tersedia di Sunfish masing-masing Personel.</li>
<li>Pengajuan: Sunfish, lampirkan nota, kuitansi, dan hasil refraksi. Maks. 6 bulan dari tanggal nota.</li>
<li>Lensa kontak dapat diklaim. Kacamata anti-radiasi <strong>tidak dapat diklaim</strong>.</li>
</ul>`
  },
  {
    id: 22, docId: "HRS-CB-006e", icon: "📘",
    title: "Penggantian Biaya Paspor",
    lc: "harian", topics: ["benefit", "perjalanan-dinas"],
    subcat: "Implementasi Manfaat",
    scope: "Personel yang melakukan perjalanan dinas luar negeri",
    date: "28 Mei 2026",
    pic: "Halimah Nur Rizkiyati", email: "halimah.nurr@paracorpgroup.com",
    summary: "Penggantian biaya pembuatan/perpanjangan paspor untuk keperluan perjalanan dinas luar negeri, plafon Rp 650.000.",
    tags: ["Paspor", "Perjadin LN", "Reimbursement"],
    links: [],
    content: `
<ul>
<li>Perusahaan mengganti biaya paspor (baru maupun perpanjangan) untuk keperluan perjalanan dinas LN.</li>
<li>Plafon: maksimal <strong>Rp 650.000</strong> per pengajuan (termasuk e-paspor).</li>
<li>Proses pembuatan dilakukan secara mandiri oleh Personel.</li>
<li>Biaya percepatan pembuatan paspor <strong>tidak ditanggung</strong>.</li>
<li>Berkas klaim: kuitansi/invoice + bukti pembayaran paspor, persetujuan atasan, screenshot tanggal keberangkatan dari Paratrip.</li>
<li>Pengajuan: melalui Sunfish.</li>
</ul>`
  },
  {
    id: 23, docId: "HRS-CB-006f", icon: "👶",
    title: "Klaim Melahirkan/Keguguran (Non-Asuransi)",
    lc: "harian", topics: ["benefit"],
    subcat: "Implementasi Manfaat",
    scope: "Istri Personel Pria PKWT (masa kerja min. 1 tahun)",
    date: "28 Mei 2026",
    pic: "PIC HR Area", email: "",
    summary: "Klaim biaya melahirkan/keguguran non-asuransi untuk istri Personel pria PKWT dengan masa kerja > 1 tahun.",
    tags: ["Melahirkan", "Keguguran", "Non-Asuransi", "PKWT", "Life Event"],
    links: [],
    content: `
<ul>
<li>Berlaku untuk istri Personel pria berstatus PKWT dengan masa kerja lebih dari <strong>1 tahun</strong>.</li>
<li>Berkas: KK/buku nikah, surat keterangan melahirkan/keguguran (termasuk jenis persalinan), kuitansi asli (jika tidak menggunakan BPJS).</li>
<li>Pengajuan: melalui Sunfish.</li>
</ul>`
  },
  {
    id: 24, docId: "HRS-CB-006g", icon: "🩺",
    title: "Klaim Periksa Kehamilan (Non-Asuransi)",
    lc: "harian", topics: ["benefit"],
    subcat: "Implementasi Manfaat",
    scope: "Istri Personel PKWT (masa kerja min. 1 tahun)",
    date: "28 Mei 2026",
    pic: "PIC HR Area", email: "",
    summary: "Fasilitas reimbursement pemeriksaan kehamilan bulanan selama 9 bulan untuk istri Personel PKWT.",
    tags: ["Kehamilan", "Pemeriksaan", "Non-Asuransi", "PKWT", "Life Event"],
    links: [],
    content: `
<ul>
<li>Difasilitasi untuk kontrol setiap bulan selama <strong>9 bulan</strong> masa kehamilan.</li>
<li>Berlaku untuk istri Personel PKWT dengan masa kerja minimal 1 tahun.</li>
<li>Berkas: KK/buku nikah dan kuitansi asli.</li>
<li>Pengajuan: melalui Sunfish. Kuitansi asli dikirimkan ke HO Paragon 3 c.u. Karina Permata.</li>
</ul>`
  },
  {
    id: 25, docId: "HRS-CB-006h", icon: "🌿",
    title: "Beasiswa CSR (Pensiun/Meninggal)",
    lc: "harian", topics: ["benefit"],
    subcat: "Apresiasi & Penghargaan",
    scope: "Anak Personel yang Pensiun atau Meninggal (jenjang TK–PTN)",
    date: "28 Mei 2026",
    pic: "HR CSR", email: "",
    summary: "Bantuan beasiswa CSR untuk anak Personel yang pensiun atau meninggal dunia saat masih bekerja.",
    tags: ["CSR", "Beasiswa", "Pensiun", "Kematian"],
    links: [],
    content: `
<ul>
<li>Bantuan diberikan kepada anak Personel yang masih berusia sekolah (jenjang TK hingga PTN).</li>
<li>Bantuan diberikan <strong>2 kali setahun</strong>, setiap awal semester.</li>
</ul>`
  },
  {
    id: 26, docId: "HRS-FA-001", icon: "📱",
    title: "Telepon Seluler (Inventaris Kantor)",
    lc: "harian", topics: ["fasilitas"],
    subcat: "Dukungan Kerja",
    scope: "Personel Level Officer ke atas",
    date: "28 Mei 2026",
    pic: "Farah Naila / Ari Putra Utama", email: "farah.nzulfa@paracorpgroup.com",
    summary: "Ketentuan klaim, plafon, dan kepemilikan telepon seluler inventaris kantor untuk Officer ke atas.",
    tags: ["HP", "Telepon", "Inventaris", "Officer", "Executive", "Head"],
    links: [],
    content: `
<table>
<tr><th>Level</th><th>Plafon Klaim Pertama</th><th>Plafon Pembaruan (3 Tahun)</th></tr>
<tr><td>Officer & Executive</td><td>Rp 2.450.000</td><td>Rp 4.000.000</td></tr>
<tr><td>Head & Group Head</td><td>Rp 2.950.000</td><td>Rp 5.500.000</td></tr>
</table>
<ul>
<li>Selama 3 tahun pertama, status telepon adalah milik perusahaan.</li>
<li>Setelah 3 tahun, kepemilikan beralih penuh kepada Personel.</li>
<li>Jika Personel berhenti sebelum 3 tahun: pemotongan prorata dari gaji terakhir sesuai nilai klaim.</li>
</ul>`
  },
  {
    id: 27, docId: "HRS-FA-002", icon: "📡",
    title: "XL Prioritas (Paket Korporat)",
    lc: "harian", topics: ["fasilitas"],
    subcat: "Dukungan Kerja",
    scope: "Personel Level Officer ke atas – Seluruh Area",
    date: "28 Mei 2026",
    pic: "Maya Mufhida (HO & DC) / Farras Septianto (Plant)",
    email: "maya.mufhida@paracorpgroup.com",
    summary: "Pilihan paket XL Pascabayar korporat, cara pendaftaran, dan mekanisme pemotongan dari tunjangan komunikasi.",
    tags: ["XL", "Komunikasi", "Officer", "Paket Korporat"],
    links: [{ label: "Daftar XL HO & DC", url: "http://bit.ly/xlparagon" }],
    content: `
<table>
<tr><th>Paket</th><th>Kuota</th><th>Ke XL</th><th>Ke Operator Lain</th><th>Potongan/Bulan</th></tr>
<tr><td>XL BIZ STARTER</td><td>10 GB</td><td>Unlimited</td><td>Free 30 mnt + 50 SMS</td><td>Rp 40.000</td></tr>
<tr><td>XL BIZ</td><td>22 GB</td><td>Unlimited</td><td>Free 50 mnt + 50 SMS</td><td>Rp 90.000</td></tr>
<tr><td>XL PRIO SILVER</td><td>20 GB</td><td>Unlimited</td><td>Free 100 mnt + 100 SMS</td><td>Rp 100.000</td></tr>
</table>
<ul>
<li>Bersifat opsional. Kartu yang tidak digunakan wajib dikembalikan ke PIC HR.</li>
<li>Biaya dipotong dari tunjangan komunikasi sesuai pilihan paket.</li>
<li>Paket aktif dalam 1×24 jam setelah diproses XL.</li>
</ul>`
  },
  {
    id: 28, docId: "HRS-FA-003", icon: "🪪",
    title: "ID Card & Access Card",
    lc: "onboarding", topics: ["fasilitas"],
    subcat: "Fasilitas Perusahaan",
    scope: "Seluruh Personel Aktif Paragon Corp",
    date: "1 Juni 2023",
    pic: "Diana Monica / Karina Permata Sari", email: "diana.monica@paracorpgroup.com",
    summary: "Fungsi, biaya penggantian ID Card dan Access Card, dan cara pengajuan jika hilang atau rusak.",
    tags: ["ID Card", "Access Card", "E-Money"],
    links: [
      { label: "Pengajuan ID Card (Semua Area)", url: "https://bit.ly/IDCard-Paragon" },
      { label: "Pengajuan Access Card (HO & Plant)", url: "https://bit.ly/AccessCard-Paragon" },
      { label: "Cetak Ulang Kartu Asuransi", url: "https://bit.ly/RePrint-KartuAsuransi" }
    ],
    content: `
<p>ID Card berfungsi sebagai tanda pengenal, akses pintu (door access), dan uang elektronik (e-money).</p>
<h4>Biaya Penggantian (Hilang/Rusak)</h4>
<table>
<tr><th>Item</th><th>Biaya</th></tr>
<tr><td>E-money ID Card</td><td>Rp 60.000</td></tr>
<tr><td>Card Holder + Tali Lanyard</td><td>Rp 40.000</td></tr>
<tr><td>1 Set Lengkap</td><td>Rp 100.000</td></tr>
</table>
<div class="warn-box">Biaya penggantian tidak dibayar tunai, melainkan diperhitungkan sebagai pengurangan komponen gaji.</div>`
  },
  {
    id: 29, docId: "HRS-FA-004", icon: "👔",
    title: "Seragam Kerja",
    lc: "onboarding", topics: ["fasilitas"],
    subcat: "Fasilitas Perusahaan",
    scope: "Seluruh Personel Paragon (min. masa kerja 6 bulan)",
    date: "28 Mei 2026",
    pic: "Rika Andriyani", email: "rika.aputri@paracorpgroup.com",
    summary: "Ketentuan penggunaan dan pembaruan seragam kerja untuk HO, DC, dan Plant.",
    tags: ["Seragam", "HO", "DC", "Plant"],
    links: [{ label: "Pengajuan Pembaruan Seragam", url: "https://bit.ly/SeragamKorporatParagon" }],
    content: `
<table>
<tr><th>Area</th><th>Ketentuan</th></tr>
<tr><td>Head Office</td><td>Sesuai ketentuan area HO yang berlaku.</td></tr>
<tr><td>Distribution Center</td><td>Sesuai ketentuan area DC yang berlaku.</td></tr>
<tr><td>Plant</td><td>Senin & Kamis: seragam korporat | Selasa: seragam denim | Rabu: pakaian bebas | Jumat: disarankan batik.</td></tr>
</table>
<ul>
<li>Diberikan setelah minimal 6 bulan masa kerja.</li>
<li>Penukaran seragam korporat hanya dapat dilakukan satu kali pada saat pertama kali mendapatkan seragam.</li>
<li>Pembaruan seragam setiap <strong>2 tahun</strong> sekali.</li>
</ul>`
  },
  {
    id: 30, docId: "HRS-FA-005a", icon: "🚗",
    title: "Kendaraan Operasional (Vendor MPM)",
    lc: "harian", topics: ["fasilitas"],
    subcat: "Dukungan Kerja",
    scope: "Personel yang min. 70% jam kerjanya di lapangan",
    date: "28 Mei 2026",
    pic: "M. Fadil", email: "mfadil@paracorpgroup.com",
    summary: "Peminjaman kendaraan operasional bagi Personel yang mayoritas bekerja di lapangan.",
    tags: ["Mobil", "Operasional", "Lapangan", "MPM"],
    links: [{ label: "Pendaftaran Kendaraan HO", url: "https://bit.ly/kendaraanPTI" }],
    content: `
<ul>
<li>Kendaraan dipinjamkan kepada Personel yang >70% aktivitas kerjanya berada di lapangan.</li>
<li>Pengajuan kendaraan baru: HRBP mengirimkan surel ke tim WPM HO (format: nama, posisi, NIP, direktorat, SIM).</li>
<li>Jika terjadi kerusakan: kirimkan kronologi ke email FM HO dan hubungi CS MPM: <strong>0813-8150-0068</strong>.</li>
</ul>`
  },
  {
    id: 31, docId: "HRS-FA-005b/c", icon: "🚕",
    title: "Grab Corporate & Voucher Taksi",
    lc: "harian", topics: ["fasilitas"],
    subcat: "Dukungan Kerja",
    scope: "Personel HO",
    date: "28 Mei 2026",
    pic: "Maya Mufhida", email: "maya.mufhida@paracorpgroup.com",
    summary: "Penggunaan Grab Corporate dan voucher taksi untuk mobilitas kerja Personel HO.",
    tags: ["Grab", "Taksi", "HO", "Mobilitas"],
    links: [],
    content: `
<h4>Grab Corporate</h4>
<ul>
<li>Digunakan untuk mobilisasi kerja ke lokasi non-penempatan (perjadin, meeting eksternal, workshop).</li>
<li>Kode Grab diberikan setiap akhir bulan untuk penggunaan bulan berikutnya.</li>
<li>Isi keterangan trip description: dari mana → ke mana (nama kegiatan).</li>
</ul>
<h4>Voucher Taksi</h4>
<ul>
<li>Berlaku bagi karyawan HO yang tidak memperoleh Grab Corporate atau membutuhkan mobilitas pukul 00.00–05.00.</li>
<li>Laporan penggunaan dilakukan pada bulan yang sama: lampirkan potongan voucher kecil, struk taksi, struk tol (jika ada).</li>
</ul>`
  },
  {
    id: 32, docId: "HRS-FA-006", icon: "🛍️",
    title: "Diskon Karyawan Parastore",
    lc: "harian", topics: ["benefit", "fasilitas"],
    subcat: "Implementasi Manfaat",
    scope: "Seluruh Personel Paragon",
    date: "28 Mei 2026",
    pic: "HR Comm", email: "",
    summary: "Diskon 25% untuk pembelian produk di Parastore Online dan Independent Store seluruh Indonesia.",
    tags: ["Diskon", "Parastore", "Benefit"],
    links: [{ label: "Parastore Online", url: "https://parastore.pti-cosmetics.com/" }],
    content: `
<ul>
<li>Diskon <strong>25%</strong> berlaku di Parastore Online dan Independent Store seluruh Indonesia.</li>
<li>Online: pastikan diskon sudah teraplikasikan saat checkout. Biaya pengiriman ditanggung pribadi.</li>
<li>Offline: sebutkan nama karyawan Paragon kepada kasir di Independent Store.</li>
</ul>`
  },
  {
    id: 33, docId: "HRS-FA-007", icon: "🎀",
    title: "Free Product",
    lc: "harian", topics: ["benefit", "fasilitas"],
    subcat: "Implementasi Manfaat",
    scope: "Seluruh Personel Paragon/Parama/Paragita (min. masa kerja 3 bulan)",
    date: "28 Mei 2026",
    pic: "PIC HR Area", email: "",
    summary: "Program pembagian produk gratis 3 kali setahun (setiap 4 bulan) untuk seluruh Paragonian.",
    tags: ["Free Product", "Benefit", "3rd Party"],
    links: [],
    content: `
<ul>
<li>Dibagikan <strong>3 kali</strong> dalam setahun (setiap 4 bulan sekali).</li>
<li>Periode: Mei (cut-off 31 Jan) | September (cut-off 31 Mei) | Januari tahun berikutnya (cut-off 30 Sep).</li>
<li>Third Party hanya mendapatkan free product pada periode Januari.</li>
<li>Tidak berlaku untuk Personel yang sudah tidak aktif pada jadwal distribusi.</li>
<li>Personel WFH menanggung biaya pengiriman secara mandiri.</li>
</ul>`
  },
  {
    id: 34, docId: "HRS-DU-007", icon: "💻",
    title: "Perangkat Hilang atau Dicuri",
    lc: "harian", topics: ["fasilitas"],
    subcat: "Dukungan Kerja",
    scope: "Seluruh Personel Paragon",
    date: "28 Mei 2026",
    pic: "IT/POSS Service Desk", email: "",
    summary: "Langkah-langkah yang harus dilakukan jika perangkat kantor (HP/laptop) hilang atau dicuri.",
    tags: ["Laptop", "HP", "Inventaris", "Keamanan"],
    links: [{ label: "Keamanan Akun Microsoft", url: "https://mysignins.microsoft.com/security-info" }],
    content: `
<ul>
<li>Laporkan ke POSS/Service Desk sesegera mungkin (model, nomor seri, lokasi & waktu kejadian).</li>
<li>Ganti kata sandi untuk semua akun yang diakses dari perangkat.</li>
<li>Hubungi penyedia layanan seluler untuk menonaktifkan kartu SIM.</li>
<li>Gunakan fitur remote wipe/lock jika tersedia ('Find My iPhone' atau 'Android Device Manager').</li>
<li>Pulihkan data dari backup jika ada.</li>
<li>Laporkan ke polisi jika dicuri; berikan salinan laporan ke HR Tech dan atasan.</li>
</ul>`
  },
  {
    id: 35, docId: "HRS-WR-001", icon: "🕌",
    title: "Wisata Rohani",
    lc: "harian", topics: ["benefit"],
    subcat: "Apresiasi & Penghargaan",
    scope: "Personel Paragon/Parama/Paragita (masa kerja min. 7 tahun)",
    date: "28 Mei 2026",
    pic: "Yauma / HR SSC", email: "",
    summary: "Perjalanan ke tanah suci sesuai agama dan kepercayaan sebagai apresiasi 7 tahun pengabdian.",
    tags: ["Wisata Rohani", "Umroh", "Benefit", "Tenure 7 Tahun"],
    links: [],
    content: `
<ul>
<li>Diberikan secara otomatis bagi Personel yang telah mencapai masa kerja <strong>7 tahun</strong>.</li>
<li>Tujuan wisata rohani disesuaikan dengan agama masing-masing Personel.</li>
</ul>
<h4>Fasilitas Umroh (contoh)</h4>
<ul>
<li>Tiket pesawat PP Jakarta–Jeddah, transportasi selama ibadah, hotel di Mekkah & Madinah.</li>
<li>Makan selama umroh, visa, perlengkapan umroh, asuransi, air zam-zam.</li>
<li>Uang saku SAR senilai Rp 1.000.000 (dibagikan saat manasik).</li>
<li>Durasi: 10 hari (1 hari manasik + 9 hari perjalanan). <strong>Tidak memotong jatah cuti.</strong></li>
</ul>`
  },
  {
    id: 36, docId: "HRS-MS-001", icon: "🏠",
    title: "Mess / Asrama Head Office",
    lc: "harian", topics: ["mess", "fasilitas"],
    subcat: "Dukungan Kerja",
    scope: "Personel dengan penempatan Head Office",
    date: "28 Mei 2026",
    pic: "Elfa Nuriyana", email: "elfa.nuriyana@paracorpgroup.com",
    summary: "Ketentuan mess single, mess couple, dan mess singgah untuk Personel HO.",
    tags: ["Mess", "Asrama", "HO"],
    links: [],
    content: `
<table>
<tr><th>Jenis Mess</th><th>Untuk</th><th>Ketentuan</th></tr>
<tr><td>Mess Single</td><td>Paragonian dengan penempatan HO</td><td>Wajib mengisi statement letter. Biaya kontribusi dipotong dari gaji.</td></tr>
<tr><td>Mess Couple</td><td>Personel sudah menikah (maks. 6 tahun) atau berencana menikah (maks. 3 bulan)</td><td>Masa tinggal 3 tahun. Ada waiting list. Konfirmasi dalam 1 minggu setelah dipanggil.</td></tr>
<tr><td>Mess Singgah</td><td>Paragonian non-HO yang perjadin ke HO</td><td>Pengajuan maks. H-7 melalui surel ke Elfa Nuriyana.</td></tr>
</table>
<div class="info-box">Fasilitas: kasur, bantal, sprei, meja kerja, kursi, lemari, AC, kamar mandi, dapur, ruang bersama, wifi.</div>
<p>Exit mess: kirim surel ke PIC dengan subject "Exit Mess – Nama Lengkap". Konfirmasi tidak ada barang tertinggal dan kunci telah dikembalikan.</p>`
  },
  {
    id: 37, docId: "HRS-MS-002", icon: "🏭",
    title: "Mess / Asrama Plant",
    lc: "harian", topics: ["mess", "fasilitas"],
    subcat: "Dukungan Kerja",
    scope: "Karyawan Plant yang berdomisili >35 km dari lokasi kerja (Level Officer ke atas)",
    date: "28 Mei 2026",
    pic: "Anisa Hasbiya", email: "anisa.hasbiya@paracorpgroup.com",
    summary: "Ketentuan mess karyawan Plant beserta fasilitas dan alur keluar mess.",
    tags: ["Mess", "Asrama", "Plant"],
    links: [],
    content: `
<ul>
<li>Diperuntukkan bagi karyawan Plant yang berdomisili lebih dari 35 km dari lokasi kerja (Level Officer ke atas).</li>
<li>Fasilitas: kasur, bantal, sprei, meja kerja, kursi, lemari, AC, kamar mandi, dapur, ruang bersama, housekeeping, laundry, wifi.</li>
<li>Mess diberikan bagi Personel dengan tingkat okupansi minimal 50% dalam sebulan.</li>
</ul>
<p><strong>Alur Keluar Mess Plant:</strong> Kirim surel ke Hasbiya & Ilyos. Informasikan tanggal keluar, nama penghuni, dan nomor kamar. Pembersihan kamar dilakukan sebelum keluar.</p>`
  },
  {
    id: 38, docId: "HRS-AL-001", icon: "🔄",
    title: "Rotasi",
    lc: "harian", topics: ["pengembangan"],
    subcat: "Pembelajaran & Pengembangan",
    scope: "Seluruh Personel Paragon",
    date: "28 Mei 2026",
    pic: "Tim People Development", email: "",
    summary: "Ketentuan rotasi jabatan: pengajuan, tanggal efektif, dan alur persetujuan oleh Tim People Development.",
    tags: ["Rotasi", "Pengembangan", "Career"],
    links: [],
    content: `
<ul>
<li>Rotasi adalah perpindahan Personel dari satu jabatan ke jabatan lain di level yang sama.</li>
<li>Pengajuan dilakukan paling lambat <strong>tanggal 1</strong> setiap bulan oleh Department Head atau setara.</li>
<li>Tanggal efektif rotasi menyesuaikan cut-off presensi untuk periode bulan berikutnya.</li>
<li>Setelah disetujui Tim People Development: BGP mengajukan perubahan melalui tautan HRIS, kemudian HRS menerbitkan SK Rotasi.</li>
</ul>`
  },
  {
    id: 39, docId: "HRS-AL-002", icon: "⬆️",
    title: "Expanded Role",
    lc: "harian", topics: ["pengembangan"],
    subcat: "Pembelajaran & Pengembangan",
    scope: "Seluruh Personel Paragon yang memenuhi syarat",
    date: "28 Mei 2026",
    pic: "Tim People Development", email: "",
    summary: "Syarat dan ketentuan Expanded Role (promosi satu tingkat) bagi Personel yang memenuhi kriteria.",
    tags: ["Expanded Role", "Promosi", "Career", "Pengembangan"],
    links: [],
    content: `
<h4>Syarat Expanded Role</h4>
<ul>
<li>Masa kerja minimal <strong>1,5 tahun</strong> setelah lulus program.</li>
<li>Kinerja memenuhi ekspektasi perusahaan.</li>
<li>Sudah bekerja di posisi saat ini minimal <strong>1 tahun</strong> sejak Expanded Role terakhir.</li>
<li>Dalam kondisi normal, hanya dapat di-Expanded Role satu tingkat di atas jabatan saat ini.</li>
</ul>`
  },
  {
    id: 40, docId: "HRS-AL-003", icon: "📦",
    title: "Relokasi & Biaya Pindahan",
    lc: "harian", topics: ["pengembangan", "benefit"],
    subcat: "Mobilitas & Relokasi",
    scope: "Personel yang melakukan rotasi atau pindah area kerja",
    date: "28 Mei 2026",
    pic: "Tim HR Rewards", email: "",
    summary: "Plafon biaya pindahan, biaya pindah sekolah anak, dan ketentuan kos/mess DC bagi Personel yang direlokasi.",
    tags: ["Relokasi", "Pindahan", "DC", "Plant", "Anak"],
    links: [],
    content: `
<h4>Biaya Pindahan (Delivery of Goods)</h4>
<ul>
<li>Single: <strong>Rp 1.000.000</strong></li>
<li>Menikah: <strong>Rp 5.000.000</strong></li>
<li>Biaya pengiriman 1 kendaraan: sesuai kuitansi aktual.</li>
<li>Pengajuan: melalui Panjer Aplikasi CASH menggunakan anggaran departemen masing-masing.</li>
</ul>
<h4>Biaya Pindah Sekolah Anak</h4>
<table>
<tr><th>Jenjang</th><th>Plafon</th></tr>
<tr><td>TK</td><td>Rp 5.000.000</td></tr>
<tr><td>SD</td><td>Rp 10.000.000</td></tr>
<tr><td>SMP</td><td>Rp 10.000.000</td></tr>
<tr><td>SMA</td><td>Rp 10.000.000</td></tr>
</table>
<h4>Kos dan Mess Area DC</h4>
<p>Personel yang ditempatkan di luar homebase difasilitasi kos atau mess dengan sistem reimbursement sesuai plafon area.</p>`
  },
  {
    id: 41, docId: "HRS-ER-001", icon: "💬",
    title: "HR Dialog 2.0",
    lc: "harian", topics: ["er"],
    subcat: "Komunitas & Keterlibatan",
    scope: "Paragonian Level Operator hingga Officer ke atas",
    date: "28 Mei 2026",
    pic: "Feby Nirwana", email: "feby.nirwana@paracorpgroup.com",
    summary: "Sesi konsultasi one-on-one dengan konselor HR untuk topik pekerjaan maupun personal.",
    tags: ["HR Dialog", "Konsultasi", "Well-being"],
    links: [{ label: "Daftar HR Dialog", url: "https://bit.ly/hrdialog-new" }],
    content: `
<p>HR Dialog adalah sesi konsultasi tatap muka (one-on-one) bagi Paragonian yang ingin berkonsultasi atau menyampaikan aspirasi.</p>
<h4>Topik yang Dapat Dibahas</h4>
<ul>
<li><strong>Pekerjaan:</strong> hubungan dengan rekan kerja, performance & pengembangan diri, kebijakan perusahaan, kasus kekerasan/diskriminasi/pelecehan.</li>
<li><strong>Personal:</strong> masalah keluarga, kesehatan fisik maupun mental.</li>
</ul>
<div class="info-box">Cara mendaftar: isi form di <a href="https://bit.ly/hrdialog-new" target="_blank">bit.ly/hrdialog-new</a>. PIC akan memilihkan konselor yang tepat dan menghubungi dalam 1 minggu.</div>`
  },
  {
    id: 42, docId: "HRS-ER-002", icon: "⚖️",
    title: "Ketentuan Sanksi Pelanggaran",
    lc: "harian", topics: ["er"],
    subcat: "Komunitas & Keterlibatan",
    scope: "Seluruh Personel Paragon",
    date: "28 Mei 2026",
    pic: "Lydia Febriani", email: "lydia.febriani@paracorpgroup.com",
    summary: "Jenis sanksi (lisan, SP1-SP3, PHK) dan ketentuan pemberlakuan berdasarkan jenis dan bobot pelanggaran.",
    tags: ["Sanksi", "SP", "PHK", "Pelanggaran"],
    links: [],
    content: `
<table>
<tr><th>Jenis Sanksi</th><th>Ketentuan</th></tr>
<tr><td>Sanksi Lisan (Teguran)</td><td>Diberikan untuk pelanggaran ringan pertama kali.</td></tr>
<tr><td>Surat Peringatan (SP1, SP2, SP3)</td><td>Diberikan secara bertahap. Jika masih dalam masa berlaku SP dan melakukan pelanggaran baru, dapat diberikan SP lebih tinggi meskipun bobotnya lebih rendah.</td></tr>
<tr><td>PHK</td><td>Diberlakukan pada pelanggaran berat atau setelah SP3.</td></tr>
</table>
<div class="info-box">SP tidak berpengaruh terhadap gaji. Yang berhak mengeluarkan SP adalah IR atau HR terkait.</div>`
  },
  {
    id: 43, docId: "HRS-ER-003", icon: "⚽",
    title: "Komunitas Olahraga Paragon",
    lc: "harian", topics: ["er"],
    subcat: "Komunitas & Keterlibatan",
    scope: "Seluruh Paragonian (semua area)",
    date: "28 Mei 2026",
    pic: "Feby Nirwana", email: "feby.nirwana@paracorpgroup.com",
    summary: "13 komunitas olahraga untuk Paragonian HO dan cara bergabung.",
    tags: ["Komunitas", "Olahraga", "Engagement"],
    links: [{ label: "Komunitas Olahraga HO", url: "https://bit.ly/ParagonClub-HO" }],
    content: `
<ul>
<li>Tersedia <strong>13 komunitas olahraga</strong> untuk Paragonian Head Office.</li>
<li>Cara bergabung: <a href="https://bit.ly/ParagonClub-HO" target="_blank">bit.ly/ParagonClub-HO</a> → pilih komunitas → ajukan permintaan bergabung.</li>
<li>Komunitas olahraga Plant & Area: hubungi HRBP DC area masing-masing.</li>
</ul>`
  },
  {
    id: 44, docId: "HRS-ER-004", icon: "🏆",
    title: "Paragonian Excellence Award (PEA)",
    lc: "harian", topics: ["er", "benefit"],
    subcat: "Komunitas & Keterlibatan",
    scope: "Seluruh Paragonian Operasional",
    date: "28 Mei 2026",
    pic: "Feby Nirwana", email: "feby.nirwana@paracorpgroup.com",
    summary: "PEA Excellence Attendance: apresiasi kehadiran penuh selama satu tahun untuk Paragonian Operasional.",
    tags: ["PEA", "Kehadiran", "Apresiasi", "Award"],
    links: [],
    content: `
<p>PEA Kategori <strong>Excellence Attendance</strong> adalah apresiasi bagi Paragonian Operasional yang menjaga kehadirannya selama satu tahun periode penilaian.</p>
<h4>Cuti yang MENGGUGURKAN PEA</h4>
<ul>
<li>Cuti dengan Surat Keterangan Dokter (SKD)</li>
<li>Cuti tahunan karena sakit</li>
<li>Cuti di luar tanggungan (Unpaid Leave)</li>
</ul>
<h4>Cuti yang TIDAK Menggugurkan PEA</h4>
<ul>
<li>Cuti tahunan untuk keperluan pribadi (bukan sakit)</li>
<li>Cuti Khusus (menikah, khitanan, dan sejenisnya)</li>
</ul>`
  },
  {
    id: 45, docId: "HRS-DU-006", icon: "🔒",
    title: "Penanganan Kasus Industrial",
    lc: "harian", topics: ["er"],
    subcat: "Komunitas & Keterlibatan",
    scope: "Seluruh Personel Paragon",
    date: "28 Mei 2026",
    pic: "Lydia Febriani", email: "lydia.febriani@paracorpgroup.com",
    summary: "Alur pelaporan dan penanganan kasus industrial/pelanggaran oleh tim IR.",
    tags: ["IR", "Kasus", "Pelanggaran", "Industial"],
    links: [],
    content: `
<ul>
<li>Pelapor menyampaikan laporan pelanggaran kepada BGP/HRBP DC disertai bukti dan fakta yang kuat.</li>
<li>BGP/HRBP DC melaporkan kepada tim Industrial Relations (IR) untuk diproses.</li>
<li>IR membuat Pendapat IR dan mendiskusikannya bersama BGP/HRBP DC, pelapor, dan/atau atasan.</li>
<li>Atasan menyampaikan keputusan akhir kepada Personel yang bersangkutan.</li>
</ul>`
  },
  {
    id: 46, docId: "HRS-RK-001", icon: "🎓",
    title: "Rekrutmen Fresh Graduate",
    lc: "rekrutmen", topics: ["rekrutmen"],
    subcat: "Proses Rekrutmen",
    scope: "Kandidat Fresh Graduate (masa kerja < 2 tahun)",
    date: "28 Mei 2026",
    pic: "Tim TABP", email: "",
    summary: "Tahapan rekrutmen Fresh Graduate (MT, PLDP, Operasional) dan ketentuan jeda mendaftar ulang jika tidak lolos.",
    tags: ["Rekrutmen", "Fresh Graduate", "MT", "PLDP"],
    links: [{ label: "Info Lowongan", url: "https://career.paragon-innovation.com/" }],
    content: `
<h4>Tahapan Rekrutmen Fresh Graduate</h4>
<ul>
<li>Seleksi Administrasi</li>
<li>Online Assessment</li>
<li>Wawancara HR atau Psikolog</li>
<li>Wawancara User</li>
<li>MCU & Offering</li>
</ul>
<h4>Ketentuan Jeda Mendaftar Ulang</h4>
<table>
<tr><th>Kondisi</th><th>Jeda</th></tr>
<tr><td>Tidak lolos tes awal/psikotes</td><td>6 bulan</td></tr>
<tr><td>Tidak lolos wawancara psikolog/HR</td><td>6 bulan</td></tr>
<tr><td>Tidak lolos wawancara User</td><td>12 bulan</td></tr>
<tr><td>Tidak lolos wawancara BOD/Excomm</td><td>Tidak diperkenankan mendaftar kembali</td></tr>
</table>`
  },
  {
    id: 47, docId: "HRS-RK-002", icon: "👨‍💼",
    title: "Rekrutmen Experienced Hire",
    lc: "rekrutmen", topics: ["rekrutmen"],
    subcat: "Proses Rekrutmen",
    scope: "Kandidat dengan pengalaman kerja min. 2 tahun",
    date: "28 Mei 2026",
    pic: "Tim TABP", email: "",
    summary: "Tahapan rekrutmen Experienced Hire dan informasi kanal lowongan.",
    tags: ["Rekrutmen", "Experienced Hire"],
    links: [{ label: "Info Lowongan Experienced", url: "https://career.paragon-innovation.com/" }],
    content: `
<h4>Tahapan Rekrutmen Experienced Hire</h4>
<ul>
<li>Sourcing & Screening oleh TABP</li>
<li>Online Test</li>
<li>Online Assessment</li>
<li>Wawancara User</li>
<li>Wawancara Psikolog</li>
<li>Wawancara Excomm</li>
<li>Wawancara Excomm Family (untuk Executive above)</li>
<li>MCU & Offering</li>
<li>Pre-Joining (untuk Sr. Executive above)</li>
</ul>`
  },
  {
    id: 48, docId: "HRS-RK-003", icon: "👥",
    title: "Program Referral",
    lc: "rekrutmen", topics: ["rekrutmen"],
    subcat: "Referral",
    scope: "Seluruh Paragonian aktif",
    date: "28 Mei 2026",
    pic: "Tim Talent Acquisition / Ajeng Zilvana", email: "r.azraini@paracorpgroup.com",
    summary: "Ketentuan program referral Fresh Graduate dan Experienced Hire untuk Paragonian aktif.",
    tags: ["Referral", "Rekrutmen"],
    links: [],
    content: `
<ul>
<li>Form Referral tersedia bagi seluruh Paragonian aktif untuk merekomendasikan kandidat bergabung dengan Paragon.</li>
<li>Tracking referral dapat dipantau melalui tautan Tracking Referral resmi.</li>
</ul>
<table>
<tr><th>Kategori</th><th>Ketentuan</th></tr>
<tr><td>Fresh Graduate</td><td>Kandidat dengan masa kerja < 2 tahun (termasuk program MT, PLDP, Operasional)</td></tr>
<tr><td>Experienced Hire</td><td>Kandidat dengan pengalaman kerja > 2 tahun</td></tr>
</table>`
  },
  {
    id: 49, docId: "HRS-RK-004", icon: "🏢",
    title: "Internal Hiring",
    lc: "rekrutmen", topics: ["rekrutmen"],
    subcat: "Internal Hiring",
    scope: "Paragonian dengan masa kerja min. 2 tahun",
    date: "28 Mei 2026",
    pic: "Tim Talent Acquisition", email: "",
    summary: "Proses seleksi internal untuk mengisi posisi tertentu: pendaftaran, tahapan, dan ketentuan lintas perusahaan.",
    tags: ["Internal Hiring", "Rekrutmen", "Career"],
    links: [],
    content: `
<ul>
<li>Internal Hiring adalah proses seleksi Personel internal untuk mengisi posisi tertentu.</li>
<li>Pendaftaran melalui formulir yang dipublikasikan secara resmi oleh Tim Talent Acquisition.</li>
<li>Tahapan: Seleksi Administratif → Wawancara User.</li>
<li>Tidak perlu meminta persetujuan atasan terlebih dahulu untuk mendaftar; koordinasi dilakukan secara paralel setelah proses rekrutmen selesai.</li>
<li>Pendaftaran lintas perusahaan (misalnya dari Parama ke Paragon) diperbolehkan sepanjang memenuhi persyaratan yang tertera.</li>
</ul>`
  },
  {
    id: 50, docId: "HRS-RK-005", icon: "📋",
    title: "Non-Employee (Konsultan, 3rd Party, Internship)",
    lc: "rekrutmen", topics: ["rekrutmen", "perjanjian-kerja"],
    subcat: "Jenis Kepegawaian",
    scope: "User yang membutuhkan tenaga non-employee",
    date: "28 Mei 2026",
    pic: "Rika Andriyani / Ajeng Zilvana", email: "r.azraini@paracorpgroup.com",
    summary: "Jenis non-employee (Konsultan, 3rd Party, Internship, PKL, Harian) dan alur pengajuan kontrak.",
    tags: ["Konsultan", "3rd Party", "Internship", "PKL", "Non-Karyawan"],
    links: [{ label: "Pengajuan Non-Employee", url: "https://tinyurl.com/nem-peopleverse" }],
    content: `
<h4>Jenis Non-Employee</h4>
<ul>
<li><strong>Konsultan:</strong> Persetujuan VP/EVP dan BGP wajib. Pengajuan sebelum mulai bekerja. Penggajian setiap tanggal 23.</li>
<li><strong>Third Party:</strong> Onboarding setiap tanggal 1 & 16. Pengajuan min. 2 minggu sebelum onboarding.</li>
<li><strong>Internship Regular:</strong> Onboarding setiap tanggal 21. Periode 3–6 bulan. Pengajuan min. 2 minggu sebelumnya.</li>
<li><strong>PKL (Pelajar SMK):</strong> Onboarding setiap tanggal 21. PIC: Ajeng.</li>
<li><strong>Harian:</strong> Periode 1 bulan (maks. 20 hari kerja). Perpanjangan maks. 2 kali. Pengajuan maks. 7 hari sebelum tanggal 1 atau 16.</li>
</ul>
<div class="info-box">Dokumen individu: KTP, NPWP, CV, dokumen kompetensi. Dokumen PT: NIB/SIUP, dokumen pajak, akun bank. SPK dikirimkan maks. 5 hari kerja setelah data lengkap.</div>`
  },
  {
    id: 51, docId: "HRS-PK-001", icon: "📝",
    title: "Perjanjian Kerja (PKWT & PKWTT)",
    lc: "onboarding", topics: ["perjanjian-kerja"],
    subcat: "Kebijakan Korporat",
    scope: "Seluruh Personel Paragon",
    date: "28 Mei 2026",
    pic: "Evi Febriani", email: "evi.febriani@paracorpgroup.com",
    summary: "Ketentuan PKWT, PKWTT, pemberitahuan habis kontrak, dan SPK pihak eksternal.",
    tags: ["PKWT", "PKWTT", "Kontrak", "Perjanjian Kerja"],
    links: [],
    content: `
<ul>
<li>Setiap Personel wajib menandatangani PKWT atau PKWTT.</li>
<li>HR akan menginformasikan habis kontrak kepada atasan <strong>1 bulan</strong> sebelumnya.</li>
<li>Personel yang tidak menerima informasi perpanjangan: masa kerjanya berakhir otomatis sesuai tanggal kontrak.</li>
<li>Personel yang menerima informasi perpanjangan: akan dikirimkan PKWT baru selambat-lambatnya di hari terakhir bekerja.</li>
<li>SPK PKWT yang sudah ditandatangani dikembalikan ke HR maksimal <strong>7 hari</strong> dari tanggal awal kontrak.</li>
</ul>`
  },
  {
    id: 52, docId: "HRS-PK-002", icon: "⭐",
    title: "Pengangkatan Karyawan Tetap",
    lc: "onboarding", topics: ["perjanjian-kerja"],
    subcat: "Kebijakan Korporat",
    scope: "Personel yang memenuhi syarat pengangkatan",
    date: "28 Mei 2026",
    pic: "Evi Febriani", email: "evi.febriani@paracorpgroup.com",
    summary: "Alur pengangkatan karyawan tetap untuk Officer ke atas dan Operasional Plant.",
    tags: ["Karyawan Tetap", "PKWTT", "Pengangkatan"],
    links: [],
    content: `
<h4>Officer ke Atas</h4>
<ul>
<li>HRS mengirimkan reminder kepada atasan mengenai konfirmasi akhir masa PKWT.</li>
<li>Atasan mengisi form evaluasi kinerja Personel.</li>
<li>Pengangkatan harus disetujui Dept. Head/Div. Head dan Direktur/Excomm dari direktorat terkait.</li>
<li>Apabila disetujui, HRS menerbitkan dan mengirimkan SK Karyawan Tetap ke Personel.</li>
</ul>
<h4>Operasional Plant</h4>
<ul>
<li>HRS mengirimkan reminder (masa PKWT: 36 bulan → pengangkatan pada bulan ke-60).</li>
<li>Atasan mengisi tautan evaluasi kontrak → meminta persetujuan minimal level Department Head.</li>
<li>HR Plant menjadwalkan asesmen jika semua parameter terpenuhi.</li>
<li>HR Plant meminta persetujuan Site Director, HR Area & DC Excellence Director, serta EVP & CAO.</li>
<li>HR Plant menyerahkan SK ke Personel dan atasan pada akhir masa PKWT (bulan ke-60).</li>
</ul>`
  },
  {
    id: 53, docId: "HRS-SK-001", icon: "📄",
    title: "Surat Keterangan Kerja (SKK)",
    lc: "harian", topics: ["surat"],
    subcat: "Dukungan Kerja",
    scope: "Seluruh Personel Paragon",
    date: "28 Mei 2026",
    pic: "Evi Febriani", email: "evi.febriani@paracorpgroup.com",
    summary: "Cara pengajuan SKK softfile dan hardfile, serta konfirmasi bank untuk keperluan KPR/kredit.",
    tags: ["SKK", "Surat", "KPR", "Kredit"],
    links: [
      { label: "Pengajuan SKK HO & DC", url: "https://bit.ly/SKK-Paragon" },
      { label: "Pengajuan SKK Plant", url: "https://bit.ly/skkplant" }
    ],
    content: `
<ul>
<li><strong>SKK Softfile</strong> (dikirim ke email kantor): selesai di hari pengajuan (H+0).</li>
<li><strong>SKK Hardfile</strong> (tanda tangan basah): SLA 2 hari kerja.</li>
<li><strong>Konfirmasi Bank</strong> (KPR, Kredit Usaha Mikro, dll.): HO & DC → Diana Monica | Plant → Rika Andriyani.</li>
<li>Khusus Operator & Operasional Plant yang mengajukan pinjaman/KPR ke bank: minimal masa kerja <strong>1 tahun</strong>.</li>
</ul>`
  },
  {
    id: 54, docId: "HRS-SK-002", icon: "✈️",
    title: "Visa & Surat Sponsor",
    lc: "harian", topics: ["surat", "perjalanan-dinas"],
    subcat: "Dukungan Kerja",
    scope: "Personel yang melakukan perjalanan dinas luar negeri",
    date: "28 Mei 2026",
    pic: "Halimah Nur Rizkiyati", email: "halimah.nurr@paracorpgroup.com",
    summary: "Proses pengajuan visa (mandiri atau via vendor), surat sponsor, dan lead time per negara.",
    tags: ["Visa", "Surat Sponsor", "Perjadin LN"],
    links: [
      { label: "Pengajuan Surat Sponsor", url: "https://bit.ly/SponsorLetterParagon" },
      { label: "Visa Guidebook", url: "https://bit.ly/VisaGuidebook" }
    ],
    content: `
<ul>
<li>HR menyediakan 2 opsi: <strong>pengajuan visa mandiri</strong> (online) atau <strong>via vendor rekanan SSC</strong>.</li>
<li>Untuk pengajuan mandiri: tetap informasikan ke tim HR sebelum tanggal keberangkatan (format: nama, nomor HP, negara tujuan, tanggal, approval EVP, softcopy paspor).</li>
<li>Surat sponsor visa: isi formulir di <a href="https://bit.ly/SponsorLetterParagon" target="_blank">bit.ly/SponsorLetterParagon</a>.</li>
</ul>
<h4>Lead Time Visa (sebagian)</h4>
<table>
<tr><th>Negara</th><th>Aman</th><th>Waspada</th></tr>
<tr><td>Amerika Serikat</td><td>≥ 3 bulan</td><td>1–3 bulan</td></tr>
<tr><td>Uni Eropa (Schengen)</td><td>≥ 3 bulan</td><td>1–2 bulan</td></tr>
<tr><td>Jepang / Korea</td><td>≥ 1 bulan</td><td>3 minggu – 1 bulan</td></tr>
</table>`
  },
  {
    id: 55, docId: "HRS-SK-003", icon: "💳",
    title: "Kartu Nama Personel",
    lc: "harian", topics: ["surat"],
    subcat: "Dukungan Kerja",
    scope: "Seluruh Personel Paragon",
    date: "28 Mei 2026",
    pic: "Halimah Nur Rizkiyati", email: "halimah.nurr@paracorpgroup.com",
    summary: "Cara pengajuan pembuatan kartu nama melalui surel ke PIC.",
    tags: ["Kartu Nama", "Atribut"],
    links: [],
    content: `
<ul>
<li>Kirim surel ke halimah.nurr@paracorpgroup.com dengan subject: <strong>'Request Kartu Nama'</strong>.</li>
<li>Informasi yang diperlukan: Nama Lengkap, Posisi, Nomor HP, Email, Area Kerja (sebutkan lokasi spesifik untuk Plant/DC), lampiran persetujuan atasan.</li>
<li>Satuan pemesanan: 1 box = 50 lembar.</li>
</ul>`
  },
  {
    id: 56, docId: "HRS-ON-001", icon: "👋",
    title: "Onboarding Karyawan Baru",
    lc: "onboarding", topics: ["onboarding"],
    subcat: "Kebijakan Onboarding",
    scope: "Karyawan Baru Paragon",
    date: "28 Mei 2026",
    pic: "Evi Febriani", email: "evi.febriani@paracorpgroup.com",
    summary: "Materi onboarding, daftar PIC, dan platform yang digunakan untuk karyawan baru bergabung.",
    tags: ["Onboarding", "Karyawan Baru"],
    links: [{ label: "Materi Onboarding HR", url: "https://bit.ly/MateriOnboardingHR" }],
    content: `
<ul>
<li>Akses materi onboarding: <a href="https://bit.ly/MateriOnboardingHR" target="_blank">bit.ly/MateriOnboardingHR</a></li>
<li>Materi: Welcoming Paragon dari HR, Welcoming dari IT, Panduan GreatDay, Sharing Session, Induksi Paragon University.</li>
</ul>
<h4>Daftar PIC Onboarding</h4>
<table>
<tr><th>Bidang</th><th>PIC</th></tr>
<tr><td>HR Operasional & Akses Akun</td><td>Evi Febriani</td></tr>
<tr><td>HRIS (GreatDay & Sunfish)</td><td>Farah Naila</td></tr>
<tr><td>Starter Kit, XL, & Asuransi</td><td>Diana Monica</td></tr>
<tr><td>Laptop & IT</td><td>Rachmi Adewi</td></tr>
<tr><td>Induksi Paragon University</td><td>Fitriyanti HR</td></tr>
</table>`
  },
  {
    id: 57, docId: "HRS-ON-003", icon: "💻",
    title: "FAQ GreatDay & Sunfish",
    lc: "onboarding", topics: ["onboarding", "waktu-kerja"],
    subcat: "Layanan Sistem",
    scope: "Seluruh Personel Paragon",
    date: "28 Mei 2026",
    pic: "Farah Naila", email: "farah.nzulfa@paracorpgroup.com",
    summary: "Panduan login, troubleshooting, dan pertanyaan umum seputar sistem HRIS GreatDay dan Sunfish.",
    tags: ["GreatDay", "Sunfish", "HRIS", "FAQ"],
    links: [{ label: "Panduan ESS", url: "https://bit.ly/PanduanESS" }],
    content: `
<table>
<tr><th>Pertanyaan</th><th>Jawaban</th></tr>
<tr><td>Tidak bisa login Sunfish?</td><td>Alamat web: sf.dataon.com | Account: paragon | Username: NIP. Lupa password: klik Forgot Password → masukkan email korporat.</td></tr>
<tr><td>Superior di Sunfish tidak sesuai?</td><td>Ajukan ke PIC Sunfish/GreatDay untuk penyesuaian.</td></tr>
<tr><td>Pilihan reimbursement tidak muncul?</td><td>Ajukan ke PIC Area untuk penyesuaian konfigurasi akun.</td></tr>
<tr><td>Pengajuan cuti tidak bisa disubmit?</td><td>Periksa periode reimbursement dan jenis lampiran yang disertakan.</td></tr>
<tr><td>Data Sunfish sama dengan GreatDay?</td><td>Ya, keduanya terintegrasi dan menampilkan data yang sama.</td></tr>
</table>`
  },
  {
    id: 58, docId: "HRS-DU-001", icon: "📋",
    title: "Pembaruan Data Diri",
    lc: "onboarding", topics: ["onboarding", "benefit"],
    subcat: "Layanan Sistem",
    scope: "Seluruh Personel Paragon",
    date: "28 Mei 2026",
    pic: "Diana Monica / Evi Febriani", email: "diana.monica@paracorpgroup.com",
    summary: "Data yang perlu diperbarui dan cara pembaruan untuk memastikan benefit terdaftar dengan benar.",
    tags: ["Data Diri", "Pembaruan", "Benefit", "Administrasi"],
    links: [{ label: "Pemutakhiran Data & Pendaftaran Benefit", url: "https://bit.ly/PendaftaranBenefit-Paragon" }],
    content: `
<p>Pembaruan data diri penting sebagai acuan pendaftaran benefit (asuransi, BPJS, beasiswa anak, status pajak).</p>
<ul>
<li>Data yang perlu diperbarui: alamat, status pernikahan, kartu keluarga, kelahiran anak, nomor telepon, kontak darurat.</li>
<li>Pembaruan melalui: <a href="https://bit.ly/PendaftaranBenefit-Paragon" target="_blank">bit.ly/PendaftaranBenefit-Paragon</a></li>
</ul>`
  },
  {
    id: 59, docId: "HRS-OB-001", icon: "🚪",
    title: "Pengunduran Diri (Resign)",
    lc: "offboarding", topics: ["offboarding"],
    subcat: "Pengunduran Diri",
    scope: "Seluruh Personel Paragon",
    date: "28 Mei 2026",
    pic: "Evi Febriani (HO) / HRBP DC / Uul Maria Ulfah (Plant)",
    email: "evi.febriani@paracorpgroup.com",
    summary: "Alur resign, ketentuan one month notice, pengembalian inventaris, dan penerbitan paklaring.",
    tags: ["Resign", "Offboarding", "Paklaring", "Inventaris"],
    links: [
      { label: "Template Surat Resign Plant", url: "https://bit.ly/SuratResignParagon" },
      { label: "Offboarding Clearance", url: "https://bit.ly/DaftarAkses_ParagonCorp" }
    ],
    content: `
<ul>
<li>Pengunduran diri diajukan minimal <strong>30 hari kalender</strong> sebelum tanggal efektif (one month notice).</li>
<li>Kirimkan surat pengunduran diri (format bebas; khusus Plant gunakan template) mencantumkan tanggal efektif resign dan persetujuan atasan ke surel PIC Offboarding.</li>
<li>Serah terima posisi dilakukan selambat-lambatnya <strong>2 pekan</strong> sebelum hari terakhir bekerja.</li>
<li>Seluruh inventaris dan berkas exit dikembalikan paling lambat hari terakhir pukul 15.00 (khusus Operasional Plant: Senin terdekat).</li>
</ul>
<h4>Paklaring</h4>
<ul>
<li>Diterbitkan otomatis setelah PM Exit diajukan dan verifikasi administrasi selesai.</li>
<li>Diterbitkan paling lambat <strong>2 minggu</strong> setelah verifikasi dokumen exit dan pengembalian aset.</li>
<li>Dikirimkan dalam bentuk softcopy PDF ke email pribadi Personel.</li>
</ul>`
  },
  {
    id: 60, docId: "HRS-OB-002", icon: "🌅",
    title: "Pensiun",
    lc: "offboarding", topics: ["offboarding"],
    subcat: "Pensiun",
    scope: "Personel Paragon yang mencapai usia pensiun (55 tahun)",
    date: "28 Mei 2026",
    pic: "HRS", email: "",
    summary: "Ketentuan usia pensiun 55 tahun, hak yang diterima, dan program persiapan pensiun.",
    tags: ["Pensiun", "Offboarding", "JHT", "JP"],
    links: [],
    content: `
<ul>
<li>Usia pensiun di PT Paragon Technology and Innovation: <strong>55 tahun</strong>.</li>
</ul>
<h4>Hak yang Diterima</h4>
<ul>
<li>Uang pesangon sesuai ketentuan perundang-undangan yang berlaku.</li>
<li>Uang penghargaan masa kerja.</li>
<li>Penggantian hak sesuai Pasal 167 UU No. 13 Tahun 2003.</li>
<li>Pencairan JHT dan Jaminan Pensiun dari BPJS Ketenagakerjaan.</li>
</ul>
<h4>Program Persiapan Pensiun</h4>
<ul>
<li>Peserta pensiun mengikuti Training Masa Persiapan Pensiun oleh Paragon University & HRS.</li>
<li>Pensiun Ceremony diselenggarakan sebagai bentuk apresiasi atas pengabdian Personel.</li>
</ul>`
  },
];

// ══════════════════════════════════════════════════════════════════
// STATE
// ══════════════════════════════════════════════════════════════════
let activeTopic = 'all';
let activeLc = 'all';
let searchQuery = '';
let viewMode = 'grid';

// ══════════════════════════════════════════════════════════════════
// FILTER LOGIC
// ══════════════════════════════════════════════════════════════════
function getFiltered() {
  return DATA.filter(d => {
    const matchTopic = activeTopic === 'all' || d.topics.includes(activeTopic);
    const matchLc    = activeLc === 'all' || d.lc === activeLc;
    const q = searchQuery.toLowerCase();
    const matchSearch = !q || [d.title, d.summary, d.subcat, d.docId, ...d.tags, d.pic].join(' ').toLowerCase().includes(q);
    return matchTopic && matchLc && matchSearch;
  });
}

function countTopic(t) {
  return DATA.filter(d => {
    const matchLc = activeLc === 'all' || d.lc === activeLc;
    const matchT  = t === 'all' || d.topics.includes(t);
    return matchLc && matchT;
  }).length;
}

// ══════════════════════════════════════════════════════════════════
// RENDER
// ══════════════════════════════════════════════════════════════════
const LC_LABELS = { rekrutmen: '🔍 Rekrutmen', onboarding: '👋 Onboarding', harian: '💼 Pekerjaan Harian', offboarding: '🚪 Offboarding' };

function highlight(text) {
  if (!searchQuery) return text;
  const regex = new RegExp(`(${searchQuery.replace(/[.*+?^${}()|[\]\\]/g,'\\$&')})`, 'gi');
  return text.replace(regex, '<mark>$1</mark>');
}

function renderCards() {
  const filtered = getFiltered();
  const container = document.getElementById('cardContainer');
  const empty = document.getElementById('emptyState');
  document.getElementById('resultCount').textContent = filtered.length;

  if (!filtered.length) {
    container.innerHTML = '';
    empty.style.display = 'block';
    return;
  }
  empty.style.display = 'none';

  container.innerHTML = filtered.map(d => `
    <div class="card" data-lc="${d.lc}" onclick="openModal(${d.id})">
      <div class="card-header">
        <div class="card-icon ${d.lc}">${d.icon}</div>
        <div class="card-title-wrap">
          <div class="card-title">${highlight(d.title)}</div>
          <div class="card-docid">${d.docId}</div>
        </div>
      </div>
      <div class="card-body">${highlight(d.summary)}</div>
      <div class="card-tags">
        <span class="tag type">${LC_LABELS[d.lc] || d.lc}</span>
        ${d.tags.slice(0,3).map(t => `<span class="tag">${highlight(t)}</span>`).join('')}
      </div>
      <div class="card-footer">
        <div class="card-pic">PIC: <strong>${d.pic.split('/')[0].trim()}</strong></div>
        <button class="card-action">Lihat Detail →</button>
      </div>
    </div>
  `).join('');
}

function updateCounts() {
  const topics = ['all','waktu-kerja','cuti','perjalanan-dinas','kompensasi','asuransi','benefit','fasilitas','rekrutmen','perjanjian-kerja','pengembangan','er','onboarding','offboarding','surat','mess'];
  topics.forEach(t => {
    const el = document.getElementById('cnt-' + t);
    if (el) el.textContent = countTopic(t);
  });
}

// ══════════════════════════════════════════════════════════════════
// ACTIONS
// ══════════════════════════════════════════════════════════════════
function setTopic(t) {
  activeTopic = t;
  document.querySelectorAll('.filter-btn').forEach(b => b.classList.toggle('active', b.dataset.topic === t));
  renderCards();
}

function setLifecycle(lc) {
  activeLc = lc;
  document.querySelectorAll('.lc-chip').forEach(c => c.classList.toggle('active', c.dataset.lc === lc));
  updateCounts();
  renderCards();
}

function onSearch(val) {
  searchQuery = val.trim();
  document.getElementById('searchClear').classList.toggle('visible', !!searchQuery);
  renderCards();
}

function clearSearch() {
  document.getElementById('searchInput').value = '';
  onSearch('');
}

function setView(mode) {
  viewMode = mode;
  const container = document.getElementById('cardContainer');
  container.classList.toggle('card-list', mode === 'list');
  document.getElementById('gridBtn').classList.toggle('active', mode === 'grid');
  document.getElementById('listBtn').classList.toggle('active', mode === 'list');
}

// ══════════════════════════════════════════════════════════════════
// MODAL
// ══════════════════════════════════════════════════════════════════
function openModal(id) {
  const d = DATA.find(x => x.id === id);
  if (!d) return;

  document.getElementById('mIcon').textContent = d.icon;
  document.getElementById('mIcon').className = `card-icon ${d.lc}`;
  document.getElementById('mDocId').textContent = d.docId;
  document.getElementById('mTitle').textContent = d.title;
  document.getElementById('mLc').textContent = LC_LABELS[d.lc] || d.lc;
  document.getElementById('mSubcat').textContent = d.subcat;
  document.getElementById('mScope').textContent = d.scope;
  document.getElementById('mDate').textContent = d.date;
  document.getElementById('mContent').innerHTML = d.content;
  document.getElementById('mPic').textContent = d.pic;
  document.getElementById('mEmail').textContent = d.email;
  document.getElementById('mUpdated').textContent = 'Diperbarui: ' + d.date;

  const tagsEl = document.getElementById('mTags');
  tagsEl.innerHTML = [
    `<span class="tag type">${LC_LABELS[d.lc]}</span>`,
    `<span class="tag type">${d.subcat}</span>`,
    ...d.tags.map(t => `<span class="tag">${t}</span>`)
  ].join('');

  const linksEl = document.getElementById('mLinks');
  const linksSection = document.getElementById('mLinksSection');
  if (d.links && d.links.length) {
    linksSection.style.display = 'block';
    linksEl.innerHTML = d.links.map(l =>
      `<a href="${l.url}" class="modal-link" target="_blank" rel="noopener">🔗 ${l.label}</a>`
    ).join('');
  } else {
    linksSection.style.display = 'none';
  }

  document.getElementById('modalOverlay').classList.add('open');
  document.body.style.overflow = 'hidden';
}

function closeModal(e) {
  if (e.target === document.getElementById('modalOverlay')) closeModalBtn();
}

function closeModalBtn() {
  document.getElementById('modalOverlay').classList.remove('open');
  document.body.style.overflow = '';
}

document.addEventListener('keydown', e => { if (e.key === 'Escape') closeModalBtn(); });

// ══════════════════════════════════════════════════════════════════
// INIT
// ══════════════════════════════════════════════════════════════════
updateCounts();
renderCards();
</script>
</body>
</html>
