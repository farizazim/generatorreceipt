<!DOCTYPE html>
<html lang="ms">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Generator Resit Lesen</title>
<style>
  :root{
    --navy:#0f2557;
    --navy-dark:#081633;
    --gold:#c9a24b;
    --bg:#eef1f6;
    --card:#ffffff;
    --border:#d9dee6;
    --text:#1f2937;
    --muted:#6b7280;
    --green:#1f8a4c;
  }
  *{box-sizing:border-box;}
  body{
    margin:0;
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    font-family:'Segoe UI', Arial, sans-serif;
    background:var(--bg);
    color:var(--text);
    padding:24px;
  }
  .wrap{
      width:min(100%, 980px);
      margin:0 auto;
      display:flex;
      flex-direction:column;
      align-items:center;
      gap:24px;
  }
  @media (max-width:800px){
    .wrap{grid-template-columns:1fr;}
  }
  h1{
    grid-column:1/-1;
    text-align:center;
    color:var(--navy);
    font-size:24px;
    margin-bottom:4px;
  }
  .subtitle{
    grid-column:1/-1;
    text-align:center;
    color:var(--muted);
    margin-top:-8px;
    margin-bottom:8px;
    font-size:14px;
  }
  .card{
    width:100%;
    max-width:430px;
    background:var(--card);
    border:1px solid var(--border);
    border-radius:12px;
    padding:20px;
    box-shadow:0 2px 8px rgba(15,37,87,0.06);
    justify-content:center;
    align-items:center;
  }
  .card h2{
    margin-top:0;
    font-size:16px;
    color:var(--navy);
    border-bottom:2px solid var(--gold);
    padding-bottom:8px;
  }
  .row{
    display:flex;
    align-items:center;
    justify-content:space-between;
    gap:10px;
    padding:10px 0;
    border-bottom:1px dashed var(--border);
  }
  .row:last-child{border-bottom:none;}
  .row label{
    display:flex;
    align-items:center;
    gap:8px;
    font-weight:600;
    cursor:pointer;
  }
  .row input[type="checkbox"]{
    width:18px;
    height:18px;
    accent-color:var(--navy);
    cursor:pointer;
  }
  .qty-box{
    display:flex;
    align-items:center;
    gap:6px;
  }
  .qty-box input[type="number"]{
    width:70px;
    padding:6px 8px;
    border:1px solid var(--border);
    border-radius:6px;
    text-align:center;
    font-size:14px;
  }
  .qty-box input[type="number"]:disabled{
    background:#f3f4f6;
    color:#aaa;
  }
  .field{
    margin-bottom:14px;
  }
  .field label{
    display:block;
    font-size:13px;
    color:var(--muted);
    margin-bottom:4px;
    font-weight:600;
  }
  .field input, .field select{
    width:100%;
    padding:9px 10px;
    border:1px solid var(--border);
    border-radius:6px;
    font-size:14px;
  }
  button.generate{
    width:100%;
    margin-top:8px;
    background:var(--navy);
    color:#fff;
    border:none;
    padding:12px;
    border-radius:8px;
    font-size:15px;
    font-weight:700;
    cursor:pointer;
    transition:background .15s;
  }
  button.generate:hover{background:var(--navy-dark);}
  .total-preview{
    text-align:right;
    font-weight:700;
    color:var(--navy);
    margin-top:6px;
    font-size:15px;
  }

  /* Receipt */
  #receiptCard{display:none;}
  .receipt{
    font-family:'Courier New', monospace;
    background:#fff;
    border:1px solid var(--border);
    border-radius:10px;
    padding:20px;
  }
  .receipt-header{
    text-align:center;
    border-bottom:2px dashed var(--navy);
    padding-bottom:12px;
    margin-bottom:12px;
  }
  .receipt-header h3{
    margin:0;
    color:var(--navy);
    letter-spacing:1px;
  }
  .receipt-header .rno{
    margin-top:6px;
    font-weight:700;
    color:var(--gold);
    background:var(--navy);
    display:inline-block;
    padding:4px 12px;
    border-radius:20px;
    font-size:13px;
  }
  .meta-line{
    display:flex;
    justify-content:space-between;
    font-size:13px;
    color:var(--muted);
    margin-bottom:3px;
  }
  table.items{
    width:100%;
    border-collapse:collapse;
    margin:14px 0;
    font-size:13px;
  }
  table.items th{
    text-align:left;
    border-bottom:1px solid var(--navy);
    padding:6px 4px;
    color:var(--navy);
  }
  table.items td{
    padding:6px 4px;
    border-bottom:1px dashed var(--border);
  }
  table.items td.num, table.items th.num{text-align:right;}
  .grand-total{
    display:flex;
    justify-content:space-between;
    font-size:16px;
    font-weight:700;
    color:var(--navy);
    border-top:2px dashed var(--navy);
    margin-top:10px;
    padding-top:10px;
  }
  .receipt-footer{
    text-align:center;
    margin-top:16px;
    font-size:12px;
    color:var(--muted);
    border-top:1px dashed var(--border);
    padding-top:10px;
  }
  .actions{
    display:flex;
    gap:10px;
    margin-top:14px;
  }
  .actions button{
    flex:1;
    padding:10px;
    border-radius:8px;
    border:none;
    font-weight:700;
    cursor:pointer;
    font-size:14px;
  }
  .btn-print{background:var(--gold); color:#3a2c05;}
  .btn-print:hover{filter:brightness(0.95);}
  .btn-new{background:#e5e7eb; color:#374151;}
  .btn-new:hover{background:#d1d5db;}
  .error{
    color:#c0392b;
    font-size:13px;
    margin-top:6px;
    display:none;
  }

  @media print{
    body *{visibility:hidden;}
    #receiptCard, #receiptCard *{visibility:visible;}
    #receiptCard{
      position:absolute;
      top:0; left:0; right:0;
      box-shadow:none;
      border:none;
    }
    .actions{display:none;}
  }
</style>
</head>
<body>

<div class="wrap">
  <h1>🧾 Generator Resit Lesen</h1>
  <p class="subtitle">Pilih jenis lesen, isi bilangan, dan resit akan dijana secara automatik</p>

  <!-- FORM -->
  <div class="card" id="formCard">
    <h2>Butiran Pelanggan</h2>
    <div class="field">
      <label>Nama Pelanggan</label>
      <input type="text" id="namaPelanggan" placeholder="Contoh: Ahmad bin Ali">
    </div>
    <div class="field">
      <label>No. Kad Pengenalan / Pendaftaran (pilihan)</label>
      <input type="text" id="icPelanggan" placeholder="Contoh: 900101-10-1234">
    </div>

    <h2>Pilih Lesen</h2>
    <div id="lesenList">
      <div class="row" data-harga="50">
        <label><input type="checkbox" class="chkLesen" data-harga="50"> Lesen RM50</label>
        <div class="qty-box">
          <button type="button" class="qtyMin" disabled>−</button>
          <input type="number" class="qtyInput" min="1" value="1" disabled>
          <button type="button" class="qtyPlus" disabled>+</button>
        </div>
      </div>
      <div class="row" data-harga="100">
        <label><input type="checkbox" class="chkLesen" data-harga="100"> Lesen RM100</label>
        <div class="qty-box">
          <button type="button" class="qtyMin" disabled>−</button>
          <input type="number" class="qtyInput" min="1" value="1" disabled>
          <button type="button" class="qtyPlus" disabled>+</button>
        </div>
      </div>
      <div class="row" data-harga="150">
        <label><input type="checkbox" class="chkLesen" data-harga="150"> Lesen RM150</label>
        <div class="qty-box">
          <button type="button" class="qtyMin" disabled>−</button>
          <input type="number" class="qtyInput" min="1" value="1" disabled>
          <button type="button" class="qtyPlus" disabled>+</button>
        </div>
      </div>
      <div class="row" data-harga="200">
        <label><input type="checkbox" class="chkLesen" data-harga="200"> Lesen RM200</label>
        <div class="qty-box">
          <button type="button" class="qtyMin" disabled>−</button>
          <input type="number" class="qtyInput" min="1" value="1" disabled>
          <button type="button" class="qtyPlus" disabled>+</button>
        </div>
      </div>
    </div>

    <div class="total-preview">Anggaran Jumlah: RM <span id="previewTotal">0.00</span></div>
    <p class="error" id="errMsg">Sila pilih sekurang-kurangnya satu jenis lesen.</p>

    <button class="generate" id="btnGenerate">Jana Resit</button>
  </div>

  <!-- RECEIPT -->
  <div class="card" id="receiptCard">
    <div class="receipt">
      <div class="receipt-header">
        <h3>RESIT RASMI LESEN</h3>
        <div class="rno" id="rNo">R-000000</div>
      </div>

      <div class="meta-line"><span>Tarikh</span><span id="rTarikh"></span></div>
      <div class="meta-line"><span>Masa</span><span id="rMasa"></span></div>
      <div class="meta-line"><span>Nama Pelanggan</span><span id="rNama"></span></div>
      <div class="meta-line" id="rIcLine"><span>No. K/P</span><span id="rIc"></span></div>

      <table class="items">
        <thead>
          <tr>
            <th>Jenis Lesen</th>
            <th class="num">Kuantiti</th>
            <th class="num">Jumlah (RM)</th>
          </tr>
        </thead>
        <tbody id="rItems"></tbody>
      </table>

      <div class="grand-total">
        <span>JUMLAH BESAR</span>
        <span id="rTotal">RM 0.00</span>
      </div>

      <div class="receipt-footer">
        Terima kasih atas pembayaran anda.<br>
        Sila simpan resit ini sebagai bukti pembayaran.
      </div>
    </div>

    <div class="actions">
      <button class="btn-print" id="btnPrint">🖨️ Cetak / Simpan PDF</button>
      <button class="btn-new" id="btnNew">➕ Resit Baharu</button>
    </div>
  </div>
</div>

<script>
  const rows = document.querySelectorAll('#lesenList .row');

  function updatePreview(){
    let total = 0;
    rows.forEach(row => {
      const chk = row.querySelector('.chkLesen');
      const qtyInput = row.querySelector('.qtyInput');
      if(chk.checked){
        const harga = parseFloat(chk.dataset.harga);
        const qty = parseInt(qtyInput.value) || 0;
        total += harga * qty;
      }
    });
    document.getElementById('previewTotal').textContent = total.toFixed(2);
  }

  rows.forEach(row => {
    const chk = row.querySelector('.chkLesen');
    const qtyInput = row.querySelector('.qtyInput');
    const qtyMin = row.querySelector('.qtyMin');
    const qtyPlus = row.querySelector('.qtyPlus');

    chk.addEventListener('change', () => {
      qtyInput.disabled = !chk.checked;
      qtyMin.disabled = !chk.checked;
      qtyPlus.disabled = !chk.checked;
      updatePreview();
    });

    qtyInput.addEventListener('input', () => {
      if(qtyInput.value === '' || parseInt(qtyInput.value) < 1){
        qtyInput.value = 1;
      }
      updatePreview();
    });

    qtyMin.addEventListener('click', () => {
      let v = parseInt(qtyInput.value) || 1;
      if(v > 1) qtyInput.value = v - 1;
      updatePreview();
    });

    qtyPlus.addEventListener('click', () => {
      let v = parseInt(qtyInput.value) || 1;
      qtyInput.value = v + 1;
      updatePreview();
    });
  });

  function generateReceiptNumber(){
    const now = new Date();
    const y = now.getFullYear();
    const m = String(now.getMonth()+1).padStart(2,'0');
    const d = String(now.getDate()).padStart(2,'0');
    //const rand = Math.floor(1000 + Math.random()*9000);

    let lastNumber = parseInt(localStorage.getItem('lastReceiptNumber')) || 5000;
    let newNumber = lastNumber + 1;

    localStorage.setItem('lastReceiptNumber', newNumber);

    return `R-${d}${m}${y}-${newNumber}`;
  }

  document.getElementById('btnGenerate').addEventListener('click', () => {
    const selected = [];
    rows.forEach(row => {
      const chk = row.querySelector('.chkLesen');
      const qtyInput = row.querySelector('.qtyInput');
      if(chk.checked){
        const harga = parseFloat(chk.dataset.harga);
        const qty = parseInt(qtyInput.value) || 1;
        selected.push({harga, qty, jumlah: harga*qty});
      }
    });

    const errMsg = document.getElementById('errMsg');
    if(selected.length === 0){
      errMsg.style.display = 'block';
      return;
    }
    errMsg.style.display = 'none';

    const nama = document.getElementById('namaPelanggan').value.trim() || '-';
    const ic = document.getElementById('icPelanggan').value.trim();

    // Isi resit
    document.getElementById('rNo').textContent = generateReceiptNumber();

    const now = new Date();
    document.getElementById('rTarikh').textContent = now.toLocaleDateString('ms-MY', {day:'2-digit', month:'long', year:'numeric'});
    document.getElementById('rMasa').textContent = now.toLocaleTimeString('ms-MY');
    document.getElementById('rNama').textContent = nama;

    if(ic){
      document.getElementById('rIcLine').style.display = 'flex';
      document.getElementById('rIc').textContent = ic;
    } else {
      document.getElementById('rIcLine').style.display = 'none';
    }

    const tbody = document.getElementById('rItems');
    tbody.innerHTML = '';
    let grandTotal = 0;
    selected.forEach(item => {
      grandTotal += item.jumlah;
      const tr = document.createElement('tr');
      tr.innerHTML = `
        <td>Lesen RM${item.harga}</td>
        <td class="num">${item.qty}</td>
        <td class="num">${item.jumlah.toFixed(2)}</td>
      `;
      tbody.appendChild(tr);
    });

    document.getElementById('rTotal').textContent = 'RM ' + grandTotal.toFixed(2);

    document.getElementById('formCard').style.display = 'none';
    document.getElementById('receiptCard').style.display = 'block';
  });

  document.getElementById('btnPrint').addEventListener('click', () => {
    window.print();
  });

  document.getElementById('btnNew').addEventListener('click', () => {
    document.getElementById('formCard').style.display = 'block';
    document.getElementById('receiptCard').style.display = 'none';
    document.getElementById('namaPelanggan').value = '';
    document.getElementById('icPelanggan').value = '';
    rows.forEach(row => {
      const chk = row.querySelector('.chkLesen');
      const qtyInput = row.querySelector('.qtyInput');
      chk.checked = false;
      qtyInput.value = 1;
      qtyInput.disabled = true;
      row.querySelector('.qtyMin').disabled = true;
      row.querySelector('.qtyPlus').disabled = true;
    });
    updatePreview();
  });
</script>

</body>
</html>
