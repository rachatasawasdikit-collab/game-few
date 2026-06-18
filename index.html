<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ระบบยืม-คืนอุปกรณ์กายภาพบำบัด</title>
<style>
  :root {
    --blue-50: #E6F1FB;
    --blue-100: #B5D4F4;
    --blue-600: #185FA5;
    --blue-800: #0C447C;
    --blue-900: #042C53;
    --teal-50: #E1F5EE;
    --teal-600: #0F6E56;
    --teal-800: #085041;
    --green-50: #EAF3DE;
    --green-600: #3B6D11;
    --green-800: #27500A;
    --amber-50: #FAEEDA;
    --amber-600: #854F0B;
    --red-50: #FCEBEB;
    --red-600: #A32D2D;
    --gray-50: #F1EFE8;
    --gray-100: #D3D1C7;
    --gray-400: #888780;
    --gray-600: #5F5E5A;
    --gray-800: #444441;
  }

  * { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    font-family: 'Sarabun', 'Segoe UI', sans-serif;
    background: #f0f4f8;
    color: #1a2636;
    min-height: 100vh;
  }

  @import url('https://fonts.googleapis.com/css2?family=Sarabun:wght@300;400;500;600&display=swap');

  header {
    background: var(--blue-900);
    color: #fff;
    padding: 0;
    border-bottom: 3px solid var(--blue-600);
  }
  .header-inner {
    max-width: 1100px;
    margin: 0 auto;
    padding: 18px 32px;
    display: flex;
    align-items: center;
    gap: 20px;
  }
  .header-logo {
    width: 44px;
    height: 44px;
    background: var(--blue-600);
    border-radius: 8px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-shrink: 0;
  }
  .header-logo svg { width: 26px; height: 26px; stroke: #fff; fill: none; stroke-width: 1.8; }
  .header-title h1 { font-size: 18px; font-weight: 600; letter-spacing: 0.3px; }
  .header-title p { font-size: 13px; color: var(--blue-100); margin-top: 2px; font-weight: 300; }
  .header-badge {
    margin-left: auto;
    background: rgba(255,255,255,0.1);
    border: 1px solid rgba(255,255,255,0.2);
    padding: 6px 14px;
    border-radius: 20px;
    font-size: 12px;
    color: #cde;
  }

  .main { max-width: 1100px; margin: 0 auto; padding: 28px 32px; }

  .tabs {
    display: flex;
    gap: 0;
    background: #fff;
    border: 1px solid var(--gray-100);
    border-radius: 10px;
    overflow: hidden;
    margin-bottom: 28px;
    box-shadow: 0 1px 4px rgba(0,0,0,0.07);
  }
  .tab-btn {
    flex: 1;
    padding: 14px 20px;
    border: none;
    background: transparent;
    font-family: inherit;
    font-size: 14px;
    font-weight: 500;
    color: var(--gray-600);
    cursor: pointer;
    border-right: 1px solid var(--gray-100);
    transition: background 0.15s, color 0.15s;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 8px;
  }
  .tab-btn:last-child { border-right: none; }
  .tab-btn.active {
    background: var(--blue-50);
    color: var(--blue-800);
    font-weight: 600;
  }
  .tab-btn svg { width: 17px; height: 17px; stroke: currentColor; fill: none; stroke-width: 1.8; }

  .tab-panel { display: none; }
  .tab-panel.active { display: block; }

  .grid-2 { display: grid; grid-template-columns: 1fr 1fr; gap: 24px; }
  .grid-3 { display: grid; grid-template-columns: repeat(auto-fit, minmax(160px, 1fr)); gap: 16px; margin-bottom: 28px; }

  .stat-card {
    background: #fff;
    border: 1px solid var(--gray-100);
    border-radius: 10px;
    padding: 18px 20px;
    box-shadow: 0 1px 4px rgba(0,0,0,0.05);
  }
  .stat-label { font-size: 12px; color: var(--gray-600); margin-bottom: 6px; font-weight: 500; text-transform: uppercase; letter-spacing: 0.5px; }
  .stat-value { font-size: 28px; font-weight: 600; color: var(--blue-800); }
  .stat-sub { font-size: 12px; color: var(--gray-400); margin-top: 4px; }

  .card {
    background: #fff;
    border: 1px solid var(--gray-100);
    border-radius: 12px;
    padding: 24px;
    box-shadow: 0 1px 4px rgba(0,0,0,0.06);
  }
  .card-title {
    font-size: 15px;
    font-weight: 600;
    color: var(--blue-900);
    margin-bottom: 20px;
    padding-bottom: 12px;
    border-bottom: 1px solid var(--gray-100);
    display: flex;
    align-items: center;
    gap: 8px;
  }
  .card-title svg { width: 18px; height: 18px; stroke: var(--blue-600); fill: none; stroke-width: 1.8; }

  .form-group { margin-bottom: 16px; }
  .form-label { display: block; font-size: 13px; font-weight: 500; color: var(--gray-800); margin-bottom: 6px; }
  .form-label span.req { color: var(--red-600); margin-left: 2px; }
  .form-control {
    width: 100%;
    padding: 9px 12px;
    border: 1px solid var(--gray-100);
    border-radius: 7px;
    font-family: inherit;
    font-size: 14px;
    color: #1a2636;
    background: #fff;
    transition: border-color 0.15s, box-shadow 0.15s;
  }
  .form-control:focus {
    outline: none;
    border-color: var(--blue-600);
    box-shadow: 0 0 0 3px rgba(24,95,165,0.12);
  }
  select.form-control { cursor: pointer; }

  .equip-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
    gap: 14px;
    margin-bottom: 18px;
  }
  .equip-card {
    border: 2px solid var(--gray-100);
    border-radius: 10px;
    padding: 14px 16px;
    cursor: pointer;
    transition: border-color 0.15s, background 0.15s;
    background: #fff;
  }
  .equip-card:hover { border-color: var(--blue-600); background: var(--blue-50); }
  .equip-card.selected { border-color: var(--blue-600); background: var(--blue-50); }
  .equip-card.unavailable { opacity: 0.5; cursor: not-allowed; pointer-events: none; }
  .equip-name { font-size: 14px; font-weight: 600; color: var(--blue-900); margin-bottom: 4px; }
  .equip-id { font-size: 11px; color: var(--gray-400); margin-bottom: 8px; }
  .equip-status {
    display: inline-flex;
    align-items: center;
    gap: 5px;
    font-size: 11px;
    font-weight: 600;
    padding: 3px 9px;
    border-radius: 20px;
  }
  .equip-status.available { background: var(--green-50); color: var(--green-600); }
  .equip-status.borrowed { background: var(--amber-50); color: var(--amber-600); }
  .equip-status-dot { width: 6px; height: 6px; border-radius: 50%; background: currentColor; }

  .btn {
    padding: 10px 24px;
    border: none;
    border-radius: 7px;
    font-family: inherit;
    font-size: 14px;
    font-weight: 600;
    cursor: pointer;
    transition: opacity 0.15s, transform 0.1s;
    display: inline-flex;
    align-items: center;
    gap: 8px;
  }
  .btn:active { transform: scale(0.98); }
  .btn-primary { background: var(--blue-800); color: #fff; }
  .btn-primary:hover { background: var(--blue-900); }
  .btn-success { background: var(--teal-600); color: #fff; }
  .btn-success:hover { background: var(--teal-800); }
  .btn-sm { padding: 6px 14px; font-size: 12px; }
  .btn svg { width: 16px; height: 16px; stroke: currentColor; fill: none; stroke-width: 2; }

  table { width: 100%; border-collapse: collapse; font-size: 13px; }
  thead tr { background: var(--gray-50); }
  th { padding: 10px 14px; text-align: left; font-size: 11px; font-weight: 600; color: var(--gray-600); text-transform: uppercase; letter-spacing: 0.5px; border-bottom: 1px solid var(--gray-100); }
  td { padding: 11px 14px; border-bottom: 1px solid var(--gray-100); color: var(--gray-800); vertical-align: middle; }
  tr:last-child td { border-bottom: none; }
  tr:hover td { background: var(--blue-50); }

  .badge {
    display: inline-flex; align-items: center; gap: 4px;
    padding: 3px 9px; border-radius: 20px; font-size: 11px; font-weight: 600;
  }
  .badge-borrowed { background: var(--amber-50); color: var(--amber-600); }
  .badge-returned { background: var(--green-50); color: var(--green-600); }
  .badge-overdue { background: var(--red-50); color: var(--red-600); }

  .alert {
    padding: 12px 16px;
    border-radius: 8px;
    font-size: 13px;
    margin-bottom: 16px;
    display: flex;
    align-items: flex-start;
    gap: 10px;
  }
  .alert svg { width: 18px; height: 18px; stroke: currentColor; fill: none; stroke-width: 1.8; flex-shrink: 0; margin-top: 1px; }
  .alert-success { background: var(--green-50); color: var(--green-800); }
  .alert-error { background: var(--red-50); color: var(--red-600); }
  .alert-info { background: var(--blue-50); color: var(--blue-800); }

  .toast {
    position: fixed;
    bottom: 28px; right: 28px;
    background: var(--blue-900);
    color: #fff;
    padding: 14px 20px;
    border-radius: 10px;
    font-size: 14px;
    font-weight: 500;
    box-shadow: 0 4px 20px rgba(0,0,0,0.2);
    z-index: 999;
    transform: translateY(80px);
    opacity: 0;
    transition: transform 0.25s, opacity 0.25s;
    max-width: 320px;
  }
  .toast.show { transform: translateY(0); opacity: 1; }

  .divider { height: 1px; background: var(--gray-100); margin: 20px 0; }

  .sheet-url-section {
    background: var(--gray-50);
    border: 1px solid var(--gray-100);
    border-radius: 10px;
    padding: 18px 20px;
    margin-bottom: 20px;
  }
  .sheet-url-section label { font-size: 13px; font-weight: 600; color: var(--gray-800); display: block; margin-bottom: 8px; }
  .sheet-url-row { display: flex; gap: 10px; }
  .sheet-url-row .form-control { flex: 1; font-size: 12px; }
  .url-status { font-size: 12px; margin-top: 6px; color: var(--gray-400); }
  .url-status.connected { color: var(--green-600); font-weight: 600; }

  .selected-equip-info {
    background: var(--blue-50);
    border: 1px solid var(--blue-100);
    border-radius: 8px;
    padding: 12px 16px;
    margin-bottom: 16px;
    font-size: 13px;
    color: var(--blue-800);
  }

  .spinner {
    width: 18px; height: 18px;
    border: 2px solid rgba(255,255,255,0.3);
    border-top-color: #fff;
    border-radius: 50%;
    animation: spin 0.7s linear infinite;
    display: inline-block;
  }
  @keyframes spin { to { transform: rotate(360deg); } }

  .section-title {
    font-size: 13px;
    font-weight: 600;
    color: var(--gray-600);
    text-transform: uppercase;
    letter-spacing: 0.5px;
    margin-bottom: 12px;
  }

  .return-select { display: flex; align-items: center; gap: 10px; }
  .return-select input[type="checkbox"] { width: 16px; height: 16px; cursor: pointer; }

  @media (max-width: 700px) {
    .grid-2 { grid-template-columns: 1fr; }
    .header-inner { padding: 14px 18px; }
    .main { padding: 18px; }
    .header-badge { display: none; }
  }
</style>
</head>
<body>

<header>
  <div class="header-inner">
    <div class="header-logo">
      <svg viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2z"/><path d="M8 12h8M12 8v8"/></svg>
    </div>
    <div class="header-title">
      <h1>ระบบยืม-คืนอุปกรณ์กายภาพบำบัด</h1>
      <p>แผนกกายภาพบำบัด — โรงพยาบาล</p>
    </div>
    <div class="header-badge" id="sheetStatusBadge">ยังไม่เชื่อมต่อ Google Sheets</div>
  </div>
</header>

<div class="main">

  <div class="sheet-url-section">
    <label>Google Apps Script Web App URL (สำหรับส่งข้อมูลไป Google Sheets)</label>
    <div class="sheet-url-row">
      <input type="text" class="form-control" id="sheetUrl" placeholder="https://script.google.com/macros/s/..." />
      <button class="btn btn-primary btn-sm" onclick="saveSheetUrl()">
        <svg viewBox="0 0 24 24"><path d="M5 12l5 5L20 7"/></svg>
        บันทึก
      </button>
    </div>
    <div class="url-status" id="urlStatus">กรอก URL ของ Google Apps Script แล้วกดบันทึก</div>
  </div>

  <div class="grid-3">
    <div class="stat-card">
      <div class="stat-label">อุปกรณ์ทั้งหมด</div>
      <div class="stat-value" id="statTotal">0</div>
      <div class="stat-sub">รายการในระบบ</div>
    </div>
    <div class="stat-card">
      <div class="stat-label">พร้อมให้ยืม</div>
      <div class="stat-value" id="statAvail" style="color: var(--teal-600)">0</div>
      <div class="stat-sub">ชิ้น</div>
    </div>
    <div class="stat-card">
      <div class="stat-label">กำลังถูกยืม</div>
      <div class="stat-value" id="statBorrowed" style="color: var(--amber-600)">0</div>
      <div class="stat-sub">ชิ้น</div>
    </div>
    <div class="stat-card">
      <div class="stat-label">รายการวันนี้</div>
      <div class="stat-value" id="statToday" style="color: var(--blue-600)">0</div>
      <div class="stat-sub">รายการ</div>
    </div>
  </div>

  <div class="tabs">
    <button class="tab-btn active" onclick="switchTab('borrow')">
      <svg viewBox="0 0 24 24"><path d="M12 5v14M5 12l7-7 7 7"/></svg>
      ยืมอุปกรณ์
    </button>
    <button class="tab-btn" onclick="switchTab('return')">
      <svg viewBox="0 0 24 24"><path d="M12 19V5M5 12l7 7 7-7"/></svg>
      คืนอุปกรณ์
    </button>
    <button class="tab-btn" onclick="switchTab('history')">
      <svg viewBox="0 0 24 24"><circle cx="12" cy="12" r="10"/><path d="M12 6v6l4 2"/></svg>
      ประวัติการยืม
    </button>
    <button class="tab-btn" onclick="switchTab('manage')">
      <svg viewBox="0 0 24 24"><rect x="3" y="3" width="7" height="7"/><rect x="14" y="3" width="7" height="7"/><rect x="3" y="14" width="7" height="7"/><rect x="14" y="14" width="7" height="7"/></svg>
      จัดการอุปกรณ์
    </button>
  </div>

  <!-- TAB: ยืม -->
  <div class="tab-panel active" id="tab-borrow">
    <div class="grid-2">
      <div class="card">
        <div class="card-title">
          <svg viewBox="0 0 24 24"><path d="M4 6h16M4 12h8m-8 6h16"/></svg>
          เลือกอุปกรณ์ที่ต้องการยืม
        </div>
        <div class="section-title">อุปกรณ์ที่พร้อมให้ยืม</div>
        <div class="equip-grid" id="equipGrid"></div>
      </div>

      <div class="card">
        <div class="card-title">
          <svg viewBox="0 0 24 24"><path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"/><circle cx="12" cy="7" r="4"/></svg>
          ข้อมูลผู้ยืม
        </div>

        <div id="selectedEquipInfo" class="selected-equip-info" style="display:none"></div>

        <div class="form-group">
          <label class="form-label">ชื่อ-นามสกุลผู้ยืม <span class="req">*</span></label>
          <input type="text" class="form-control" id="borrowerName" placeholder="เช่น นายสมชาย ใจดี" />
        </div>
        <div class="form-group">
          <label class="form-label">แผนก / หน่วยงาน <span class="req">*</span></label>
          <input type="text" class="form-control" id="department" placeholder="เช่น หอผู้ป่วยใน 3" />
        </div>
        <div class="form-group">
          <label class="form-label">เบอร์โทรศัพท์ <span class="req">*</span></label>
          <input type="text" class="form-control" id="phone" placeholder="เช่น 0812345678" />
        </div>
        <div class="form-group">
          <label class="form-label">วันที่กำหนดคืน <span class="req">*</span></label>
          <input type="date" class="form-control" id="dueDate" />
        </div>
        <div class="form-group">
          <label class="form-label">หมายเหตุ</label>
          <textarea class="form-control" id="borrowNote" rows="2" placeholder="ข้อมูลเพิ่มเติม (ถ้ามี)"></textarea>
        </div>

        <div id="borrowFormMsg"></div>

        <button class="btn btn-primary" onclick="submitBorrow()" id="borrowBtn" style="width:100%; justify-content:center; margin-top:4px">
          <svg viewBox="0 0 24 24"><path d="M12 5v14M5 12l7-7 7 7"/></svg>
          ยืนยันการยืม
        </button>
      </div>
    </div>
  </div>

  <!-- TAB: คืน -->
  <div class="tab-panel" id="tab-return">
    <div class="card">
      <div class="card-title">
        <svg viewBox="0 0 24 24"><path d="M12 19V5M5 12l7 7 7-7"/></svg>
        บันทึกการคืนอุปกรณ์
      </div>
      <div class="section-title" style="margin-bottom:14px">เลือกรายการที่ต้องการคืน</div>
      <div id="returnList"></div>
      <div id="returnMsg"></div>
      <button class="btn btn-success" onclick="submitReturn()" id="returnBtn" style="margin-top:16px">
        <svg viewBox="0 0 24 24"><path d="M5 12l5 5L20 7"/></svg>
        ยืนยันการคืน
      </button>
    </div>
  </div>

  <!-- TAB: ประวัติ -->
  <div class="tab-panel" id="tab-history">
    <div class="card">
      <div class="card-title">
        <svg viewBox="0 0 24 24"><circle cx="12" cy="12" r="10"/><path d="M12 6v6l4 2"/></svg>
        ประวัติการยืม-คืน
      </div>
      <div style="display:flex; gap:12px; margin-bottom:16px; flex-wrap:wrap">
        <input type="text" class="form-control" id="searchHistory" style="max-width:260px" placeholder="ค้นหาชื่อผู้ยืม หรืออุปกรณ์" oninput="renderHistory()" />
        <select class="form-control" id="filterStatus" style="max-width:160px" onchange="renderHistory()">
          <option value="">ทุกสถานะ</option>
          <option value="BORROW">กำลังยืม</option>
          <option value="RETURN">คืนแล้ว</option>
        </select>
      </div>
      <div style="overflow-x:auto">
        <table>
          <thead>
            <tr>
              <th>รหัสรายการ</th>
              <th>วันที่ยืม</th>
              <th>อุปกรณ์</th>
              <th>ผู้ยืม</th>
              <th>แผนก</th>
              <th>กำหนดคืน</th>
              <th>สถานะ</th>
            </tr>
          </thead>
          <tbody id="historyTbody"></tbody>
        </table>
      </div>
      <div id="historyEmpty" style="text-align:center; padding:32px; color:var(--gray-400); font-size:14px; display:none">ยังไม่มีรายการในระบบ</div>
    </div>
  </div>

  <!-- TAB: จัดการ -->
  <div class="tab-panel" id="tab-manage">
    <div class="grid-2">
      <div class="card">
        <div class="card-title">
          <svg viewBox="0 0 24 24"><path d="M12 5v14M5 12h14"/></svg>
          เพิ่มอุปกรณ์ใหม่
        </div>
        <div class="form-group">
          <label class="form-label">รหัสอุปกรณ์ <span class="req">*</span></label>
          <input type="text" class="form-control" id="newEquipId" placeholder="เช่น PT-001" />
        </div>
        <div class="form-group">
          <label class="form-label">ชื่ออุปกรณ์ <span class="req">*</span></label>
          <input type="text" class="form-control" id="newEquipName" placeholder="เช่น เครื่อง TENS" />
        </div>
        <div class="form-group">
          <label class="form-label">ประเภทอุปกรณ์</label>
          <select class="form-control" id="newEquipCategory">
            <option value="electrotherapy">เครื่องกระตุ้นไฟฟ้า</option>
            <option value="exercise">อุปกรณ์ออกกำลังกาย</option>
            <option value="mobility">อุปกรณ์ช่วยเดิน</option>
            <option value="assessment">อุปกรณ์ประเมินผล</option>
            <option value="thermal">อุปกรณ์ความร้อน/เย็น</option>
            <option value="other">อื่น ๆ</option>
          </select>
        </div>
        <div class="form-group">
          <label class="form-label">หมายเหตุ</label>
          <input type="text" class="form-control" id="newEquipNote" placeholder="ข้อมูลเพิ่มเติม" />
        </div>
        <button class="btn btn-primary" onclick="addEquipment()" style="width:100%; justify-content:center">
          <svg viewBox="0 0 24 24"><path d="M12 5v14M5 12h14"/></svg>
          เพิ่มอุปกรณ์
        </button>
      </div>

      <div class="card">
        <div class="card-title">
          <svg viewBox="0 0 24 24"><path d="M4 6h16M4 12h16M4 18h16"/></svg>
          รายการอุปกรณ์ทั้งหมด
        </div>
        <div style="overflow-x:auto">
          <table id="equipTable">
            <thead>
              <tr>
                <th>รหัส</th>
                <th>ชื่ออุปกรณ์</th>
                <th>สถานะ</th>
                <th></th>
              </tr>
            </thead>
            <tbody id="equipTbody"></tbody>
          </table>
        </div>
      </div>
    </div>
  </div>

</div>

<div class="toast" id="toast"></div>

<script>
let equipments = [];
let transactions = [];
let selectedEquipId = null;
let sheetUrl = '';

const STORAGE_KEY_EQUIP = 'pt_equipments';
const STORAGE_KEY_TRANS = 'pt_transactions';
const STORAGE_KEY_URL = 'pt_sheet_url';

function loadData() {
  try {
    const eq = localStorage.getItem(STORAGE_KEY_EQUIP);
    const tr = localStorage.getItem(STORAGE_KEY_TRANS);
    const url = localStorage.getItem(STORAGE_KEY_URL);
    if (eq) equipments = JSON.parse(eq);
    if (tr) transactions = JSON.parse(tr);
    if (url) {
      sheetUrl = url;
      document.getElementById('sheetUrl').value = url;
      document.getElementById('urlStatus').textContent = 'เชื่อมต่อแล้ว: ' + url.substring(0, 60) + '...';
      document.getElementById('urlStatus').className = 'url-status connected';
      document.getElementById('sheetStatusBadge').textContent = 'เชื่อมต่อ Google Sheets แล้ว';
    }
  } catch(e) {}
  if (equipments.length === 0) loadDefaultEquipments();
}

function saveData() {
  try {
    localStorage.setItem(STORAGE_KEY_EQUIP, JSON.stringify(equipments));
    localStorage.setItem(STORAGE_KEY_TRANS, JSON.stringify(transactions));
  } catch(e) {}
}

function loadDefaultEquipments() {
  equipments = [
    { id: 'PT-001', name: 'เครื่อง TENS (กระตุ้นไฟฟ้า)', category: 'electrotherapy', status: 'available', note: '' },
    { id: 'PT-002', name: 'เครื่อง Ultrasound Therapy', category: 'electrotherapy', status: 'available', note: '' },
    { id: 'PT-003', name: 'เครื่อง Infrared Lamp', category: 'thermal', status: 'available', note: '' },
    { id: 'PT-004', name: 'ไม้เท้า 4 ขา (Quad Cane)', category: 'mobility', status: 'available', note: '' },
    { id: 'PT-005', name: 'Walker มาตรฐาน', category: 'mobility', status: 'available', note: '' },
    { id: 'PT-006', name: 'ไม้ค้ำยัน (Axillary Crutch)', category: 'mobility', status: 'available', note: '' },
    { id: 'PT-007', name: 'Theraband (ยางยืด Resistance Band)', category: 'exercise', status: 'available', note: '' },
    { id: 'PT-008', name: 'ลูกบอลกายภาพ (Exercise Ball)', category: 'exercise', status: 'available', note: '' },
    { id: 'PT-009', name: 'เครื่องวัดองศาข้อต่อ (Goniometer)', category: 'assessment', status: 'available', note: '' },
    { id: 'PT-010', name: 'เครื่อง Hot Pack / Cold Pack', category: 'thermal', status: 'available', note: '' },
    { id: 'PT-011', name: 'Tilt Table', category: 'exercise', status: 'available', note: '' },
    { id: 'PT-012', name: 'Balance Board', category: 'exercise', status: 'available', note: '' },
  ];
  saveData();
}

function saveSheetUrl() {
  const val = document.getElementById('sheetUrl').value.trim();
  if (!val) { showToast('กรุณากรอก URL ก่อน'); return; }
  sheetUrl = val;
  localStorage.setItem(STORAGE_KEY_URL, val);
  document.getElementById('urlStatus').textContent = 'เชื่อมต่อแล้ว: ' + val.substring(0, 60) + '...';
  document.getElementById('urlStatus').className = 'url-status connected';
  document.getElementById('sheetStatusBadge').textContent = 'เชื่อมต่อ Google Sheets แล้ว';
  showToast('บันทึก URL สำเร็จ');
}

function switchTab(name) {
  document.querySelectorAll('.tab-btn').forEach((btn, i) => {
    const ids = ['borrow','return','history','manage'];
    btn.classList.toggle('active', ids[i] === name);
  });
  document.querySelectorAll('.tab-panel').forEach(p => p.classList.remove('active'));
  document.getElementById('tab-' + name).classList.add('active');
  if (name === 'history') renderHistory();
  if (name === 'return') renderReturnList();
  if (name === 'manage') renderEquipTable();
}

function renderEquipGrid() {
  const grid = document.getElementById('equipGrid');
  const avail = equipments.filter(e => e.status === 'available');
  if (avail.length === 0) {
    grid.innerHTML = '<div style="color:var(--gray-400);font-size:13px;padding:12px 0">ไม่มีอุปกรณ์พร้อมให้ยืม</div>';
    return;
  }
  grid.innerHTML = avail.map(e => `
    <div class="equip-card${e.id === selectedEquipId ? ' selected' : ''}" onclick="selectEquip('${e.id}')">
      <div class="equip-name">${e.name}</div>
      <div class="equip-id">${e.id}</div>
      <span class="equip-status available"><span class="equip-status-dot"></span>พร้อมให้ยืม</span>
    </div>
  `).join('');
}

function selectEquip(id) {
  selectedEquipId = id;
  const eq = equipments.find(e => e.id === id);
  const info = document.getElementById('selectedEquipInfo');
  info.style.display = 'block';
  info.innerHTML = '<strong>อุปกรณ์ที่เลือก:</strong> ' + eq.name + ' <span style="color:var(--gray-400);font-size:12px">(' + eq.id + ')</span>';
  renderEquipGrid();
}

function updateStats() {
  const total = equipments.length;
  const avail = equipments.filter(e => e.status === 'available').length;
  const borrowed = equipments.filter(e => e.status === 'borrowed').length;
  const today = transactions.filter(t => {
    const d = new Date(t.timestamp);
    const n = new Date();
    return d.toDateString() === n.toDateString();
  }).length;
  document.getElementById('statTotal').textContent = total;
  document.getElementById('statAvail').textContent = avail;
  document.getElementById('statBorrowed').textContent = borrowed;
  document.getElementById('statToday').textContent = today;
}

function showMsg(elId, type, msg) {
  const el = document.getElementById(elId);
  if (!msg) { el.innerHTML = ''; return; }
  const icons = {
    success: '<path d="M5 12l5 5L20 7"/>',
    error: '<path d="M12 8v4m0 4h.01M10.29 3.86L1.82 18a2 2 0 001.71 3h16.94a2 2 0 001.71-3L13.71 3.86a2 2 0 00-3.42 0z"/>',
    info: '<circle cx="12" cy="12" r="10"/><path d="M12 8v4m0 4h.01"/>'
  };
  el.innerHTML = `<div class="alert alert-${type}"><svg viewBox="0 0 24 24">${icons[type]}</svg><span>${msg}</span></div>`;
}

function showToast(msg) {
  const t = document.getElementById('toast');
  t.textContent = msg;
  t.classList.add('show');
  setTimeout(() => t.classList.remove('show'), 3000);
}

async function sendToSheet(payload) {
  if (!sheetUrl) return { ok: false, reason: 'no-url' };
  try {
    const res = await fetch(sheetUrl, {
      method: 'POST',
      headers: { 'Content-Type': 'application/json' },
      body: JSON.stringify(payload),
      mode: 'no-cors'
    });
    return { ok: true };
  } catch(e) {
    return { ok: false, reason: e.message };
  }
}

function genTransId() {
  const now = new Date();
  const pad = n => String(n).padStart(2,'0');
  return `TR-${now.getFullYear()}${pad(now.getMonth()+1)}${pad(now.getDate())}${pad(now.getHours())}${pad(now.getMinutes())}${pad(now.getSeconds())}`;
}

async function submitBorrow() {
  showMsg('borrowFormMsg','','');
  const borrowerName = document.getElementById('borrowerName').value.trim();
  const department = document.getElementById('department').value.trim();
  const phone = document.getElementById('phone').value.trim();
  const dueDate = document.getElementById('dueDate').value;
  const note = document.getElementById('borrowNote').value.trim();

  if (!selectedEquipId) return showMsg('borrowFormMsg','error','กรุณาเลือกอุปกรณ์ที่ต้องการยืม');
  if (!borrowerName) return showMsg('borrowFormMsg','error','กรุณากรอกชื่อผู้ยืม');
  if (!department) return showMsg('borrowFormMsg','error','กรุณากรอกแผนก/หน่วยงาน');
  if (!phone) return showMsg('borrowFormMsg','error','กรุณากรอกเบอร์โทรศัพท์');
  if (!dueDate) return showMsg('borrowFormMsg','error','กรุณาระบุวันที่กำหนดคืน');

  const eq = equipments.find(e => e.id === selectedEquipId);
  const btn = document.getElementById('borrowBtn');
  btn.disabled = true;
  btn.innerHTML = '<span class="spinner"></span> กำลังบันทึก...';

  const transId = genTransId();
  const timestamp = new Date().toISOString();

  const trans = { transId, timestamp, equipId: selectedEquipId, equipName: eq.name, borrowerName, department, phone, dueDate, note, action: 'BORROW', returnedAt: null };
  transactions.unshift(trans);
  eq.status = 'borrowed';
  saveData();

  const payload = { action: 'WEB_BORROW', transId, equipId: selectedEquipId, equipName: eq.name, borrowerName, department, phone, dueDate, note, timestamp };
  const result = await sendToSheet(payload);

  updateStats();
  renderEquipGrid();

  let msgExtra = '';
  if (!sheetUrl) msgExtra = ' (ยังไม่ได้เชื่อมต่อ Google Sheets)';
  else msgExtra = ' — ส่งข้อมูลไป Google Sheets แล้ว';

  showMsg('borrowFormMsg','success', `บันทึกการยืมสำเร็จ รหัส: ${transId}${msgExtra}`);
  showToast('ยืม ' + eq.name + ' สำเร็จ');

  document.getElementById('borrowerName').value = '';
  document.getElementById('department').value = '';
  document.getElementById('phone').value = '';
  document.getElementById('dueDate').value = '';
  document.getElementById('borrowNote').value = '';
  selectedEquipId = null;
  document.getElementById('selectedEquipInfo').style.display = 'none';

  btn.disabled = false;
  btn.innerHTML = '<svg viewBox="0 0 24 24" width="16" height="16" stroke="currentColor" fill="none" stroke-width="2"><path d="M12 5v14M5 12l7-7 7 7"/></svg> ยืนยันการยืม';
}

function renderReturnList() {
  const borrowed = transactions.filter(t => t.action === 'BORROW' && !t.returnedAt);
  const el = document.getElementById('returnList');
  if (borrowed.length === 0) {
    el.innerHTML = '<div style="color:var(--gray-400);font-size:14px;padding:12px 0">ไม่มีรายการที่กำลังถูกยืมอยู่</div>';
    return;
  }
  el.innerHTML = `<div style="overflow-x:auto"><table><thead><tr>
    <th>เลือก</th><th>รหัสรายการ</th><th>วันที่ยืม</th><th>อุปกรณ์</th><th>ผู้ยืม</th><th>แผนก</th><th>กำหนดคืน</th>
  </tr></thead><tbody>` + borrowed.map(t => {
    const due = new Date(t.dueDate);
    const now = new Date();
    const overdue = due < now;
    return `<tr>
      <td><div class="return-select"><input type="checkbox" id="ret_${t.transId}" value="${t.transId}" /></div></td>
      <td style="font-family:monospace;font-size:12px">${t.transId}</td>
      <td>${new Date(t.timestamp).toLocaleDateString('th-TH')}</td>
      <td>${t.equipName}</td>
      <td>${t.borrowerName}</td>
      <td>${t.department || '-'}</td>
      <td><span class="badge ${overdue ? 'badge-overdue' : 'badge-borrowed'}">${t.dueDate}${overdue ? ' (เกินกำหนด)' : ''}</span></td>
    </tr>`;
  }).join('') + `</tbody></table></div>`;
}

async function submitReturn() {
  const checked = [...document.querySelectorAll('[id^="ret_"]:checked')].map(c => c.value);
  if (checked.length === 0) return showMsg('returnMsg','error','กรุณาเลือกรายการที่ต้องการคืน');

  const btn = document.getElementById('returnBtn');
  btn.disabled = true;
  btn.innerHTML = '<span class="spinner"></span> กำลังบันทึก...';
  showMsg('returnMsg','','');

  const now = new Date().toISOString();
  for (const transId of checked) {
    const trans = transactions.find(t => t.transId === transId);
    if (!trans) continue;
    trans.returnedAt = now;
    trans.action = 'RETURN';
    const eq = equipments.find(e => e.id === trans.equipId);
    if (eq) eq.status = 'available';

    const payload = { action: 'WEB_BORROW', transId: 'RET-' + genTransId(), equipId: trans.equipId, equipName: trans.equipName, borrowerName: trans.borrowerName, department: trans.department, phone: trans.phone, dueDate: trans.dueDate, note: 'คืนแล้ว (อ้างอิง: ' + transId + ')', timestamp: now };
    await sendToSheet(payload);
  }

  saveData();
  updateStats();
  renderReturnList();

  let msgExtra = sheetUrl ? ' — ส่งข้อมูลไป Google Sheets แล้ว' : ' (ยังไม่ได้เชื่อมต่อ Google Sheets)';
  showMsg('returnMsg','success', `บันทึกการคืน ${checked.length} รายการสำเร็จ${msgExtra}`);
  showToast(`คืนอุปกรณ์ ${checked.length} รายการสำเร็จ`);

  btn.disabled = false;
  btn.innerHTML = '<svg viewBox="0 0 24 24" width="16" height="16" stroke="currentColor" fill="none" stroke-width="2"><path d="M5 12l5 5L20 7"/></svg> ยืนยันการคืน';
}

function renderHistory() {
  const search = document.getElementById('searchHistory').value.toLowerCase();
  const filter = document.getElementById('filterStatus').value;
  let list = [...transactions];
  if (search) list = list.filter(t => t.borrowerName.toLowerCase().includes(search) || t.equipName.toLowerCase().includes(search) || t.transId.toLowerCase().includes(search));
  if (filter) list = list.filter(t => filter === 'BORROW' ? !t.returnedAt : t.returnedAt);

  const tbody = document.getElementById('historyTbody');
  const empty = document.getElementById('historyEmpty');
  if (list.length === 0) {
    tbody.innerHTML = '';
    empty.style.display = '';
    return;
  }
  empty.style.display = 'none';
  tbody.innerHTML = list.map(t => {
    const due = new Date(t.dueDate);
    const now = new Date();
    const overdue = !t.returnedAt && due < now;
    const badge = t.returnedAt ? 'badge-returned">คืนแล้ว' : (overdue ? 'badge-overdue">เกินกำหนด' : 'badge-borrowed">กำลังยืม');
    return `<tr>
      <td style="font-family:monospace;font-size:11px">${t.transId}</td>
      <td>${new Date(t.timestamp).toLocaleDateString('th-TH')}</td>
      <td>${t.equipName}</td>
      <td>${t.borrowerName}</td>
      <td>${t.department || '-'}</td>
      <td>${t.dueDate}</td>
      <td><span class="badge ${badge}</span></td>
    </tr>`;
  }).join('');
}

function renderEquipTable() {
  const tbody = document.getElementById('equipTbody');
  tbody.innerHTML = equipments.map(e => `
    <tr>
      <td style="font-family:monospace;font-size:12px">${e.id}</td>
      <td>${e.name}</td>
      <td><span class="equip-status ${e.status === 'available' ? 'available' : 'borrowed'}"><span class="equip-status-dot"></span>${e.status === 'available' ? 'พร้อมให้ยืม' : 'ถูกยืม'}</span></td>
      <td><button class="btn btn-sm" style="color:var(--red-600);border-color:var(--red-600)" onclick="deleteEquip('${e.id}')">ลบ</button></td>
    </tr>
  `).join('');
}

function addEquipment() {
  const id = document.getElementById('newEquipId').value.trim();
  const name = document.getElementById('newEquipName').value.trim();
  const category = document.getElementById('newEquipCategory').value;
  const note = document.getElementById('newEquipNote').value.trim();
  if (!id || !name) return showToast('กรุณากรอกรหัสและชื่ออุปกรณ์');
  if (equipments.find(e => e.id === id)) return showToast('รหัสอุปกรณ์ซ้ำกัน');
  equipments.push({ id, name, category, note, status: 'available' });
  saveData();
  updateStats();
  renderEquipTable();
  renderEquipGrid();
  document.getElementById('newEquipId').value = '';
  document.getElementById('newEquipName').value = '';
  document.getElementById('newEquipNote').value = '';
  showToast('เพิ่มอุปกรณ์สำเร็จ: ' + name);
}

function deleteEquip(id) {
  const eq = equipments.find(e => e.id === id);
  if (eq && eq.status === 'borrowed') return showToast('ไม่สามารถลบอุปกรณ์ที่กำลังถูกยืมอยู่');
  if (!confirm('ยืนยันการลบ ' + (eq ? eq.name : id) + ' ?')) return;
  equipments = equipments.filter(e => e.id !== id);
  saveData();
  updateStats();
  renderEquipTable();
  renderEquipGrid();
  showToast('ลบอุปกรณ์แล้ว');
}

// Set default due date = 3 days from now
function setDefaultDate() {
  const d = new Date();
  d.setDate(d.getDate() + 3);
  const iso = d.toISOString().split('T')[0];
  document.getElementById('dueDate').value = iso;
}

loadData();
setDefaultDate();
updateStats();
renderEquipGrid();
</script>
</body>
</html>
