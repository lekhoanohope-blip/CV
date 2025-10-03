<!doctype html>
<html lang="vi">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>CV — Lập trình viên (Sinh viên năm nhất)</title>
  <style>
    :root{
      --accent:#2563eb;
      --muted:#6b7280;
      --bg:#f9fafb;
      --card:#ffffff;
      --sidebar:#eff6ff;
      --text:#0f172a;
      --maxw:960px;
      --radius:12px;
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    body{background:var(--bg);color:var(--text);margin:20px;display:flex;justify-content:center}
    .cv{width:100%;max-width:var(--maxw);display:grid;grid-template-columns:300px 1fr;gap:20px}
    .card{background:var(--card);border-radius:var(--radius);box-shadow:0 6px 18px rgba(12,18,36,0.06);overflow:hidden}

    /* SIDEBAR */
    .sidebar{background:var(--sidebar);padding:24px}
    .avatar{width:70px;height:70px;border-radius:12px;background:linear-gradient(135deg,var(--accent),#60a5fa);display:flex;align-items:center;justify-content:center;font-weight:700;color:white;margin-bottom:14px}
    .title{font-size:18px;font-weight:700;margin-bottom:6px}
    .role{color:var(--muted);font-size:13px;margin-bottom:18px}
    .contact{font-size:14px;margin-bottom:18px}
    .contact div{display:flex;gap:8px;align-items:center;margin-bottom:6px}
    .section-title{font-size:13px;color:var(--muted);text-transform:uppercase;letter-spacing:0.08em;margin-top:12px;margin-bottom:8px}
    .pill{display:inline-block;background:white;padding:6px 8px;border-radius:8px;font-size:13px;margin:4px 4px 0 0;box-shadow:0 1px 0 rgba(15,23,42,0.04)}
    .skill-list{display:flex;flex-wrap:wrap}

    /* MAIN */
    .main{padding:24px}
    .objective{margin-bottom:18px}
    .section{margin-bottom:18px}
    .bullets{margin:8px 0 0 18px}

    /* footer */
    .print-note{font-size:12px;color:var(--muted);margin-top:12px}

    @media (max-width:860px){
      .cv{grid-template-columns:1fr}
      .sidebar{display:flex;gap:18px;align-items:flex-start}
      .avatar{width:60px;height:60px}
    }
  </style>
</head>
<body>
  <div class="cv">
    <aside class="card sidebar">
      <div class="avatar">SV</div>
      <div>
        <div class="title">Trần Minh D</div>
        <div class="role">Sinh viên năm nhất CNTT</div>
      </div>

      <div class="section-title">Thông tin</div>
      <div class="contact">
        <div>📞 0912345678</div>
        <div>✉ tranminhd@example.com</div>
        <div>📍 Quận 9, TP HCM</div>
      </div>

      <div class="section-title">Kỹ năng cơ bản</div>
      <div class="skill-list">
        <span class="pill">HTML & CSS cơ bản</span>
        <span class="pill">Python cơ bản</span>
        <span class="pill">Tin học văn phòng</span>
        <span class="pill">Kỹ năng thuyết trình</span>
      </div>

      <div class="section-title">Sở thích</div>
      <div class="pill">Học lập trình online</div>
      <div class="pill">Xem video công nghệ</div>
      <div class="pill">Thể thao</div>
    </aside>

    <main class="card main">
      <section class="objective">
        <h2 style="margin:0 0 6px 0">Mục tiêu học tập & nghề nghiệp</h2>
        <p style="margin:0;color:var(--muted)">Sinh viên năm nhất ngành Công nghệ Thông tin, yêu thích lập trình và phát triển phần mềm. Tôi mong muốn học hỏi thêm kiến thức thực tế, tham gia dự án nhỏ, nâng cao kỹ năng và định hướng trở thành lập trình viên web trong tương lai.</p>
      </section>

      <section class="section">
        <h3 style="margin:0 0 8px 0">Học vấn</h3>
        <div class="edu-item">
          <div class="company">Đại học Công nghệ Thông tin TP.HCM</div>
          <div class="meta">2024 - nay (năm 1)</div>
          <ul class="bullets">
            <li>Chuyên ngành: Khoa học máy tính</li>
            <li>Các môn đã học: Lập trình căn bản (Python, C), Toán rời rạc</li>
          </ul>
        </div>
      </section>

      <section class="section">
        <h3 style="margin:0 0 8px 0">Hoạt động</h3>
        <div class="edu-item">
          <div class="company">CLB Lập trình viên trẻ</div>
          <div class="meta">2024 - nay</div>
          <ul class="bullets">
            <li>Tham gia workshop về Python và Web cơ bản.</li>
            <li>Kết nối với anh chị khóa trên để học hỏi kinh nghiệm.</li>
          </ul>
        </div>
      </section>

      <section class="section">
        <h3 style="margin:0 0 8px 0">Dự án cá nhân nhỏ</h3>
        <ul class="bullets">
          <li>Website giới thiệu bản thân đơn giản bằng HTML & CSS (2024).</li>
          <li>Mini game đoán số bằng Python (2024).</li>
        </ul>
      </section>

      <div class="print-note">© Mẫu CV — Sinh viên năm nhất CNTT</div>
    </main>
  </div>
</body>
</html>
