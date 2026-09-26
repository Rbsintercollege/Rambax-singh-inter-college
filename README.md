<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Rambax Singh Inter College (Residential/Hostel) - Bithara, Aliganj</title>
  
  <!-- DPS Mathura Road typography: Cinzel (Institutional Headings) & Outfit / Poppins (Clean Modern UI) -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@600;700;800;900&family=Outfit:wght@300;400;500;600;700&display=swap" rel="stylesheet" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />

  <style>
    :root {
      --primary: #004d25;       /* DPS Deep Heritage Green */
      --primary-dark: #003319;  /* Dark Forest Top Bar */
      --secondary: #d4af37;     /* DPS Institutional Gold */
      --secondary-light: #fef8e7;
      --text-dark: #222222;
      --text-muted: #555555;
      --light-bg: #f4f6f5;
      --card-shadow: 0 4px 20px rgba(0, 77, 37, 0.08);
      --font-heading: 'Cinzel', serif;
      --font-body: 'Outfit', sans-serif;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: var(--light-bg);
      color: var(--text-dark);
      font-family: var(--font-body);
      font-size: 15px;
      line-height: 1.6;
    }

    /* Top Utility Bar */
    .top-bar {
      background: var(--primary-dark);
      color: #ffffff;
      padding: 7px 30px;
      font-size: 13px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      letter-spacing: 0.3px;
      border-bottom: 1px solid rgba(212, 175, 55, 0.3);
    }
    .top-bar i {
      color: var(--secondary);
      margin-right: 5px;
    }
    .top-bar a {
      color: #fff;
      text-decoration: none;
      margin-left: 18px;
      font-weight: 500;
      transition: color 0.2s;
    }
    .top-bar a:hover {
      color: var(--secondary);
    }

    /* Header */
    header {
      background: #ffffff;
      padding: 16px 40px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      border-bottom: 4px solid var(--secondary);
    }
    .logo-container {
      display: flex;
      align-items: center;
      gap: 18px;
    }
    .school-logo-img {
      width: 80px;
      height: 80px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid var(--secondary);
      box-shadow: 0 4px 10px rgba(0,0,0,0.15);
    }
    .school-title h1 {
      font-family: var(--font-heading);
      font-size: 26px;
      color: var(--primary);
      text-transform: uppercase;
      font-weight: 800;
      letter-spacing: 1px;
      line-height: 1.2;
    }
    .school-title p {
      font-size: 13.5px;
      color: var(--text-muted);
      margin-top: 4px;
      font-weight: 500;
      letter-spacing: 0.4px;
    }

    /* Navigation Bar */
    nav {
      background: var(--primary);
      display: flex;
      justify-content: center;
      gap: 10px;
      position: sticky;
      top: 0;
      z-index: 999;
      box-shadow: 0 3px 10px rgba(0,0,0,0.15);
    }
    nav a {
      color: #ffffff;
      text-decoration: none;
      padding: 14px 22px;
      font-weight: 600;
      font-size: 14px;
      text-transform: uppercase;
      letter-spacing: 0.8px;
      transition: all 0.3s;
      display: flex;
      align-items: center;
      gap: 8px;
    }
    nav a:hover, nav a.active {
      background: var(--secondary);
      color: var(--primary-dark);
    }

    /* Photo Scrolling Carousel (Continuous Marquee) */
    .scroller-section {
      background: #002210;
      padding: 16px 0;
      overflow: hidden;
      white-space: nowrap;
      position: relative;
      border-bottom: 3px solid var(--secondary);
    }
    .scroller-track {
      display: inline-flex;
      gap: 16px;
      animation: scrollPhotos 30s linear infinite;
    }
    .scroller-track:hover {
      animation-play-state: paused;
    }
    .scroller-track img {
      height: 220px;
      width: 320px;
      object-fit: cover;
      border-radius: 6px;
      border: 2px solid var(--secondary);
      box-shadow: 0 5px 12px rgba(0,0,0,0.5);
    }
    @keyframes scrollPhotos {
      from { transform: translateX(0); }
      to { transform: translateX(-50%); }
    }

    .container {
      max-width: 1200px;
      margin: 35px auto;
      padding: 0 20px;
    }

    /* Grid Sections */
    .grid-2 {
      display: grid;
      grid-template-columns: 2fr 1fr;
      gap: 30px;
    }

    .card {
      background: #ffffff;
      border-radius: 8px;
      padding: 28px;
      box-shadow: var(--card-shadow);
      border-top: 4px solid var(--primary);
      margin-bottom: 25px;
    }
    .card h2 {
      font-family: var(--font-heading);
      color: var(--primary);
      font-size: 21px;
      margin-bottom: 16px;
      border-bottom: 2px solid #eef2ef;
      padding-bottom: 10px;
      display: flex;
      align-items: center;
      gap: 12px;
      letter-spacing: 0.5px;
    }

    /* Leadership Cards */
    .profile-card {
      text-align: center;
    }
    .profile-card img {
      width: 145px;
      height: 145px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid var(--secondary);
      margin-bottom: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }
    .profile-card h3 {
      font-family: var(--font-heading);
      color: var(--primary);
      font-size: 19px;
      letter-spacing: 0.5px;
    }
    .profile-card p.badge {
      display: inline-block;
      background: var(--secondary);
      color: var(--primary-dark);
      padding: 4px 14px;
      border-radius: 20px;
      font-size: 12.5px;
      font-weight: 700;
      margin: 6px 0;
      letter-spacing: 0.5px;
    }

    /* Form Styles */
    .form-group {
      margin-bottom: 16px;
      position: relative;
    }
    .form-group label {
      display: block;
      font-size: 13.5px;
      font-weight: 600;
      margin-bottom: 6px;
      color: #333;
    }
    .form-group input, .form-group select, .form-group textarea {
      width: 100%;
      padding: 11px 12px;
      border: 1px solid #ccc;
      border-radius: 5px;
      outline: none;
      font-family: var(--font-body);
      font-size: 14px;
    }
    .form-group input:focus, .form-group select:focus, .form-group textarea:focus {
      border-color: var(--primary);
      box-shadow: 0 0 0 2px rgba(0,77,37,0.15);
    }

    /* Password Input Wrapper with Show/Hide */
    .password-wrapper {
      position: relative;
      display: flex;
      align-items: center;
    }
    .password-wrapper input {
      padding-right: 42px;
    }
    .password-toggle {
      position: absolute;
      right: 12px;
      cursor: pointer;
      color: #777;
      font-size: 16px;
      transition: color 0.2s;
      user-select: none;
    }
    .password-toggle:hover {
      color: var(--primary);
    }

    .btn {
      background: var(--primary);
      color: #fff;
      border: none;
      padding: 11px 22px;
      font-family: var(--font-body);
      font-size: 14px;
      font-weight: 600;
      letter-spacing: 0.5px;
      border-radius: 5px;
      cursor: pointer;
      transition: 0.3s;
    }
    .btn:hover {
      background: var(--secondary);
      color: var(--primary-dark);
    }

    /* Modal / Admin Popup */
    .modal {
      display: none;
      position: fixed;
      inset: 0;
      background: rgba(0,0,0,0.75);
      z-index: 1000;
      justify-content: center;
      align-items: center;
    }
    .modal-content {
      background: #ffffff;
      width: 92%;
      max-width: 950px;
      max-height: 90vh;
      overflow-y: auto;
      border-radius: 8px;
      padding: 30px;
      position: relative;
      box-shadow: 0 10px 30px rgba(0,0,0,0.3);
    }
    .close-btn {
      position: absolute;
      right: 22px;
      top: 18px;
      font-size: 26px;
      cursor: pointer;
      color: #666;
    }

    /* Marksheet Layout */
    .marksheet-box {
      border: 3px double var(--primary);
      padding: 25px;
      background: #ffffff;
      margin-top: 25px;
    }
    .marksheet-header {
      text-align: center;
      border-bottom: 2px solid var(--secondary);
      padding-bottom: 12px;
      margin-bottom: 16px;
    }
    .marksheet-header img {
      width: 70px;
      height: 70px;
      border-radius: 50%;
      margin-bottom: 6px;
    }
    .marksheet-header h2 {
      font-family: var(--font-heading);
      font-size: 22px;
      color: var(--primary);
      margin-bottom: 3px;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 15px;
      font-size: 13.5px;
    }
    table, th, td {
      border: 1px solid #dcdcdc;
    }
    th, td {
      padding: 9px;
      text-align: center;
    }
    th {
      background: var(--primary);
      color: #ffffff;
      font-weight: 600;
    }

    /* Footer */
    footer {
      background: var(--primary-dark);
      color: #e0e0e0;
      text-align: center;
      padding: 24px;
      margin-top: 45px;
      border-top: 3px solid var(--secondary);
      font-size: 13.5px;
    }

    @media (max-width: 768px) {
      .grid-2 { grid-template-columns: 1fr; }
      header { flex-direction: column; text-align: center; gap: 15px; }
      .school-title h1 { font-size: 21px; }
      nav { flex-wrap: wrap; }
    }
  </style>
</head>
<body>

  <!-- Top Contact Details -->
  <div class="top-bar">
    <div>
      <i class="fa fa-phone"></i> +91 6395052394 &nbsp;|&nbsp; 
      <i class="fa fa-map-marker-alt"></i> Bithara (Aliganj, Etah - 207247)
    </div>
    <div>
      <a href="javascript:void(0)" onclick="openAdminModal()"><i class="fa fa-user-shield"></i> Admin Portal Login</a>
    </div>
  </div>

  <!-- Header -->
  <header>
    <div class="logo-container">
      <img src="image_a7609a.jpg" alt="RBS Logo" class="school-logo-img" />
      <div class="school-title">
        <h1>Rambax Singh Inter College</h1>
        <p>Residential / Hostel Facility Available | Bithara, Aliganj (Etah)</p>
      </div>
    </div>
    <div>
      <button class="btn" onclick="document.getElementById('admission-sec').scrollIntoView({behavior:'smooth'})">
        <i class="fa fa-user-plus"></i> Online Admission
      </button>
    </div>
  </header>

  <!-- Navbar -->
  <nav>
    <a href="#" class="active"><i class="fa fa-home"></i> Home</a>
    <a href="#about"><i class="fa fa-info-circle"></i> About College</a>
    <a href="#leadership"><i class="fa fa-users"></i> Administration</a>
    <a href="#admission-sec"><i class="fa fa-file-signature"></i> Admission Form</a>
    <a href="javascript:void(0)" onclick="openAdminModal()"><i class="fa fa-lock"></i> Portal Login</a>
  </nav>

  <!-- Auto Scrolling Photo Slider -->
  <div class="scroller-section">
    <div class="scroller-track">
      <!-- Uploaded School Photos -->
      <img src="rbs5.jpeg" alt="Campus View" />
      <img src="rbs4.jpeg" alt="Annual Gathering" />
      <img src="rbs6.jpeg" alt="Award Ceremony" />
      <img src="rbs7.jpeg" alt="Classroom" />
      <img src="rbs8.jpeg" alt="Republic Day" />
      <img src="rbs9.jpeg" alt="Staff and Founder" />
      <img src="rbs10.jpeg" alt="Cultural Program" />
      <img src="rbs11.jpeg" alt="Drama Activity" />
      <img src="rbs12.jpeg" alt="Student Prize" />
      <!-- Duplicate Set for Smooth Infinite Scroll -->
      <img src="rbs5.jpeg" alt="Campus View" />
      <img src="rbs4.jpeg" alt="Annual Gathering" />
      <img src="rbs6.jpeg" alt="Award Ceremony" />
      <img src="rbs7.jpeg" alt="Classroom" />
      <img src="rbs8.jpeg" alt="Republic Day" />
    </div>
  </div>

  <!-- Main Content -->
  <div class="container">
    <div class="grid-2">
      <!-- Left Column: About & Form -->
      <div>
        <div class="card" id="about">
          <h2><i class="fa fa-university"></i> Welcome to Rambax Singh Inter College</h2>
          <p>Hamara vidyalaya chhatron ko uchch koti ki shiksha, anushasan aur sarvangeen vikas pradan karne ke liye pratibaddh hai. Vidyalaya me chhatron ke rahne ke liye uttam <b>Hostel / Residential suvidha</b> uplabdh hai.</p>
          <br>
          <ul style="margin-left: 20px; line-height: 1.8;">
            <li>Director <b>Avadhesh Singh</b> ke kushala nirdeshan me sanchalit</li>
            <li>Utkrisht Shikshak aur Shaikshik Vatavaran</li>
            <li>Surakshit Hostel aur Poushtik Bhojan Suvidha</li>
            <li>Khel-kood aur Sanskritik Karyakram</li>
            <li>Adhyan hetu computer lab aur pustakalaya</li>
          </ul>
        </div>

        <!-- Online Admission Form -->
        <div class="card" id="admission-sec">
          <h2><i class="fa fa-edit"></i> Online Admission Form</h2>
          <form id="onlineForm" onsubmit="handleFormSubmit(event)">
            <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 15px;">
              <div class="form-group">
                <label>Student Full Name *</label>
                <input type="text" id="form_name" required placeholder="Chhatra ka naam" />
              </div>
              <div class="form-group">
                <label>Father's Name *</label>
                <input type="text" id="form_father" required placeholder="Pita ka naam" />
              </div>
            </div>
            <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 15px;">
              <div class="form-group">
                <label>Class for Admission *</label>
                <select id="form_class" required>
                  <option value="">Select Class</option>
                  <option value="6th">Class 6th</option>
                  <option value="7th">Class 7th</option>
                  <option value="8th">Class 8th</option>
                  <option value="9th">Class 9th</option>
                  <option value="10th">Class 10th</option>
                  <option value="11th">Class 11th</option>
                  <option value="12th">Class 12th</option>
                </select>
              </div>
              <div class="form-group">
                <label>Mobile Number *</label>
                <input type="tel" id="form_mobile" required placeholder="Mobile no." />
              </div>
            </div>
            <div class="form-group">
              <label>Hostel Suvidha Chahiye?</label>
              <select id="form_hostel">
                <option value="Ha (Yes)">Ha (Hostel Requisite)</option>
                <option value="Nahi (Day Scholar)">Nahi (Day Scholar)</option>
              </select>
            </div>
            <div class="form-group">
              <label>Complete Address *</label>
              <textarea id="form_address" rows="3" required placeholder="Gaon / Shehar, Pincode"></textarea>
            </div>
            <button type="submit" class="btn"><i class="fa fa-paper-plane"></i> Form Submit Karein</button>
          </form>
        </div>
      </div>

      <!-- Right Column: Leadership Desk (Director & Manager) -->
      <div id="leadership">
        <!-- Director Card -->
        <div class="card profile-card">
          <h2><i class="fa fa-award"></i> Director's Desk</h2>
          <div style="width: 120px; height: 120px; border-radius: 50%; background: #eaf1ed; margin: 0 auto 12px; display: flex; align-items: center; justify-content: center; border: 3px solid var(--secondary);">
            <i class="fa fa-user-tie" style="font-size: 55px; color: var(--primary);"></i>
          </div>
          <h3>Avadhesh Singh</h3>
          <p class="badge">Director</p>
          <p style="font-size: 13.5px; color: #555; margin-top: 8px;">
            "Vidya se hi samaj me samman aur parivartan aata hai. Hamara prayas har vidyarthi ke sunehre bhavishya ka nirman karna hai."
          </p>
        </div>

        <!-- Manager Card -->
        <div class="card profile-card">
          <h2><i class="fa fa-user"></i> Manager Profile</h2>
          <img src="vishnu kant.jpg" alt="Manager Vishnu Kant" />
          <h3>Vishnu Kant</h3>
          <p class="badge">School Manager</p>
          <p style="font-size: 13.5px; color: #555; margin-top: 8px;">
            "Shiksha hi safalta ki kunji hai. Hamara uddeshya har bachche ko sahi margdarshan aur anushasan pradan karna hai."
          </p>
          <div style="margin-top: 15px; border-top: 1px solid #eee; padding-top: 12px; font-size: 13.5px;">
            <p><b>Sampark:</b> +91 6395052394</p>
            <p><b>Address:</b> Bithara, Aliganj (Etah)</p>
          </div>
        </div>

        <div class="card">
          <h2><i class="fa fa-hotel"></i> Hostel Highlights</h2>
          <p style="font-size: 13.5px; color: #555; line-height: 1.6;">
            Hamare yahan dur-daraj ke chhatron ke liye hostel suvidha uplabdh hai jisme shuddh peyjal, 24x7 bijli aur suraksha ka pura prabandh hai.
          </p>
        </div>
      </div>
    </div>
  </div>

  <!-- Admin Modal (Login & Dashboard) -->
  <div class="modal" id="adminModal">
    <div class="modal-content">
      <span class="close-btn" onclick="closeAdminModal()">&times;</span>
      
      <!-- Login View -->
      <div id="loginView">
        <h2 style="font-family: var(--font-heading); color: var(--primary); margin-bottom: 18px;">
          <i class="fa fa-lock"></i> Admin Portal Login
        </h2>
        <div class="form-group">
          <label>Email Address</label>
          <input type="email" id="adminUser" placeholder="Enter registered admin email" autocomplete="off" />
        </div>
        <div class="form-group">
          <label>Password</label>
          <div class="password-wrapper">
            <input type="password" id="adminPass" placeholder="Enter password" autocomplete="off" />
            <i class="fa fa-eye password-toggle" id="togglePasswordIcon" onclick="togglePasswordVisibility()" title="Show/Hide Password"></i>
          </div>
        </div>
        <button class="btn" onclick="handleAdminLogin()"><i class="fa fa-sign-in-alt"></i> Login</button>
      </div>

      <!-- Dashboard View -->
      <div id="dashboardView" style="display: none;">
        <div style="display: flex; justify-content: space-between; align-items: center; border-bottom: 2px solid var(--secondary); padding-bottom: 10px;">
          <h2 style="font-family: var(--font-heading); color: var(--primary);"><i class="fa fa-tachometer-alt"></i> Admin Control Panel</h2>
          <button class="btn" style="background: #777;" onclick="handleLogout()">Logout</button>
        </div>

        <!-- Section 1: Submitted Online Forms -->
        <h3 style="margin-top: 25px; color: var(--primary);"><i class="fa fa-users"></i> Online Admission Form Entries</h3>
        <table id="applicationsTable">
          <thead>
            <tr>
              <th>Date</th>
              <th>Student Name</th>
              <th>Father Name</th>
              <th>Class</th>
              <th>Contact</th>
              <th>Hostel</th>
              <th>Address</th>
            </tr>
          </thead>
          <tbody id="appTbody">
            <tr>
              <td colspan="7">Abhi tak koi form nahi aaya hai.</td>
            </tr>
          </tbody>
        </table>

        <!-- Section 2: Instant Marksheet Auto Calculation Generator -->
        <h3 style="margin-top: 30px; color: var(--primary);"><i class="fa fa-calculator"></i> Automatic Marksheet Generator</h3>
        <div style="display: grid; grid-template-columns: repeat(4, 1fr); gap: 10px; margin-top: 15px;">
          <div>
            <label style="font-size: 12.5px; font-weight: 600;">Student Name</label>
            <input type="text" id="ms_name" placeholder="Student Name" style="width: 100%; padding: 7px;" />
          </div>
          <div>
            <label style="font-size: 12.5px; font-weight: 600;">Father's Name</label>
            <input type="text" id="ms_father" placeholder="Father's Name" style="width: 100%; padding: 7px;" />
          </div>
          <div>
            <label style="font-size: 12.5px; font-weight: 600;">Roll Number</label>
            <input type="text" id="ms_roll" placeholder="Roll No" style="width: 100%; padding: 7px;" />
          </div>
          <div>
            <label style="font-size: 12.5px; font-weight: 600;">Address</label>
            <input type="text" id="ms_address" placeholder="Address" style="width: 100%; padding: 7px;" />
          </div>
        </div>

        <!-- Marks Input -->
        <div style="display: grid; grid-template-columns: repeat(5, 1fr); gap: 10px; margin-top: 15px;">
          <div>
            <label style="font-size: 12px;">Hindi (100)</label>
            <input type="number" id="m_hindi" value="75" max="100" style="width:100%; padding: 6px;" />
          </div>
          <div>
            <label style="font-size: 12px;">English (100)</label>
            <input type="number" id="m_eng" value="70" max="100" style="width:100%; padding: 6px;" />
          </div>
          <div>
            <label style="font-size: 12px;">Maths (100)</label>
            <input type="number" id="m_math" value="85" max="100" style="width:100%; padding: 6px;" />
          </div>
          <div>
            <label style="font-size: 12px;">Science (100)</label>
            <input type="number" id="m_sci" value="80" max="100" style="width:100%; padding: 6px;" />
          </div>
          <div>
            <label style="font-size: 12px;">Social Sci (100)</label>
            <input type="number" id="m_sst" value="78" max="100" style="width:100%; padding: 6px;" />
          </div>
        </div>

        <button class="btn" style="margin-top: 15px;" onclick="generateAutoMarksheet()"><i class="fa fa-magic"></i> Generate & Calculate Marksheet</button>

        <!-- Printable Marksheet Container -->
        <div id="marksheetPrintArea" style="display: none;" class="marksheet-box">
          <div class="marksheet-header">
            <img src="image_a7609a.jpg" alt="RBS Crest" />
            <h2>RAMBAX SINGH INTER COLLEGE</h2>
            <p>Bithara, Aliganj (Etah - 207247) | Residential Hostel School</p>
            <h4 style="margin-top: 5px; color: var(--secondary); text-decoration: underline;">ANNUAL EXAMINATION REPORT CARD</h4>
          </div>

          <div style="display: flex; justify-content: space-between; font-size: 14px; margin-bottom: 10px;">
            <div>
              <p><b>Student Name:</b> <span id="out_name"></span></p>
              <p><b>Father's Name:</b> <span id="out_father"></span></p>
            </div>
            <div>
              <p><b>Roll Number:</b> <span id="out_roll"></span></p>
              <p><b>Address:</b> <span id="out_address"></span></p>
            </div>
          </div>

          <table>
            <thead>
              <tr>
                <th>Subject</th>
                <th>Maximum Marks</th>
                <th>Marks Obtained</th>
              </tr>
            </thead>
            <tbody id="out_table_body"></tbody>
            <tfoot>
              <tr style="font-weight: bold; background: #fafafa;">
                <td>Total</td>
                <td>500</td>
                <td id="out_total"></td>
              </tr>
            </tfoot>
          </table>

          <div style="display: flex; justify-content: space-between; margin-top: 15px; font-weight: bold; font-size: 15px;">
            <div>Percentage: <span id="out_percent" style="color: var(--primary);"></span></div>
            <div>Result: <span id="out_status" style="color: green;">PASS</span></div>
            <div>Grade: <span id="out_grade" style="color: var(--secondary);"></span></div>
          </div>

          <div style="display: flex; justify-content: space-between; margin-top: 40px; font-size: 13px; text-align: center;">
            <div>
              <div style="border-top: 1px dashed #333; width: 140px; margin-bottom: 4px;"></div>
              Class Teacher Sign
            </div>
            <div>
              <div style="border-top: 1px dashed #333; width: 160px; margin-bottom: 4px;"></div>
              Manager (Vishnu Kant)
            </div>
            <div>
              <div style="border-top: 1px dashed #333; width: 160px; margin-bottom: 4px;"></div>
              Director (Avadhesh Singh)
            </div>
          </div>

          <button class="btn" style="margin-top: 20px;" onclick="window.print()"><i class="fa fa-print"></i> Print Marksheet</button>
        </div>

      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer>
    <p><b>Rambax Singh Inter College</b> - Bithara (Aliganj, Etah 207247)</p>
    <p>Director: Avadhesh Singh &nbsp;|&nbsp; Manager: Vishnu Kant &nbsp;|&nbsp; Contact: +91 6395052394</p>
    <p style="margin-top: 8px; font-size: 11px;">Design style inspired by DPS Mathura Road.</p>
  </footer>

  <!-- Logic Scripts -->
  <script>
    let applications = [];

    function handleFormSubmit(e) {
      e.preventDefault();
      const newEntry = {
        date: new Date().toLocaleDateString(),
        name: document.getElementById('form_name').value,
        father: document.getElementById('form_father').value,
        className: document.getElementById('form_class').value,
        mobile: document.getElementById('form_mobile').value,
        hostel: document.getElementById('form_hostel').value,
        address: document.getElementById('form_address').value
      };
      
      applications.push(newEntry);
      alert('Aapka online form safaltapurvak jama kar liya gaya hai!');
      document.getElementById('onlineForm').reset();
      updateAdminTable();
    }

    function updateAdminTable() {
      const tbody = document.getElementById('appTbody');
      if (applications.length === 0) {
        tbody.innerHTML = '<tr><td colspan="7">Abhi tak koi form nahi aaya hai.</td></tr>';
        return;
      }
      tbody.innerHTML = '';
      applications.forEach(app => {
        tbody.innerHTML += `
          <tr>
            <td>${app.date}</td>
            <td><b>${app.name}</b></td>
            <td>${app.father}</td>
            <td>${app.className}</td>
            <td>${app.mobile}</td>
            <td>${app.hostel}</td>
            <td>${app.address}</td>
          </tr>
        `;
      });
    }

    function openAdminModal() {
      document.getElementById('adminModal').style.display = 'flex';
    }
    function closeAdminModal() {
      document.getElementById('adminModal').style.display = 'none';
      document.getElementById('adminUser').value = '';
      document.getElementById('adminPass').value = '';
    }

    // Toggle Show/Hide Password
    function togglePasswordVisibility() {
      const passInput = document.getElementById('adminPass');
      const toggleIcon = document.getElementById('togglePasswordIcon');
      if (passInput.type === 'password') {
        passInput.type = 'text';
        toggleIcon.classList.remove('fa-eye');
        toggleIcon.classList.add('fa-eye-slash');
      } else {
        passInput.type = 'password';
        toggleIcon.classList.remove('fa-eye-slash');
        toggleIcon.classList.add('fa-eye');
      }
    }

    // Strict Admin Credentials Checking (No Hints)
    function handleAdminLogin() {
      const u = document.getElementById('adminUser').value.trim();
      const p = document.getElementById('adminPass').value;
      
      if (u === 'rambaxsinghintercollege@gmail.com' && p === 'vishnukant@207247') {
        document.getElementById('loginView').style.display = 'none';
        document.getElementById('dashboardView').style.display = 'block';
        updateAdminTable();
      } else {
        alert('Galat Login Credentials!');
      }
    }

    function handleLogout() {
      document.getElementById('dashboardView').style.display = 'none';
      document.getElementById('loginView').style.display = 'block';
      document.getElementById('adminUser').value = '';
      document.getElementById('adminPass').value = '';
      closeAdminModal();
    }

    function generateAutoMarksheet() {
      const name = document.getElementById('ms_name').value || "Student Name";
      const father = document.getElementById('ms_father').value || "Father Name";
      const roll = document.getElementById('ms_roll').value || "101";
      const address = document.getElementById('ms_address').value || "Bithara, Aliganj";

      const h = parseFloat(document.getElementById('m_hindi').value) || 0;
      const e = parseFloat(document.getElementById('m_eng').value) || 0;
      const m = parseFloat(document.getElementById('m_math').value) || 0;
      const s = parseFloat(document.getElementById('m_sci').value) || 0;
      const ss = parseFloat(document.getElementById('m_sst').value) || 0;

      const total = h + e + m + s + ss;
      const percentage = (total / 5).toFixed(2);

      let grade = "C";
      if (percentage >= 80) grade = "A+";
      else if (percentage >= 60) grade = "A";
      else if (percentage >= 45) grade = "B";

      document.getElementById('out_name').innerText = name;
      document.getElementById('out_father').innerText = father;
      document.getElementById('out_roll').innerText = roll;
      document.getElementById('out_address').innerText = address;

      document.getElementById('out_table_body').innerHTML = `
        <tr><td>Hindi</td><td>100</td><td>${h}</td></tr>
        <tr><td>English</td><td>100</td><td>${e}</td></tr>
        <tr><td>Mathematics</td><td>100</td><td>${m}</td></tr>
        <tr><td>Science</td><td>100</td><td>${s}</td></tr>
        <tr><td>Social Science</td><td>100</td><td>${ss}</td></tr>
      `;

      document.getElementById('out_total').innerText = total;
      document.getElementById('out_percent').innerText = percentage + "%";
      document.getElementById('out_grade').innerText = grade;
      document.getElementById('out_status').innerText = (h >= 33 && e >= 33 && m >= 33 && s >= 33 && ss >= 33) ? "PASS" : "NEEDS IMPROVEMENT";
      document.getElementById('out_status').style.color = (percentage >= 33) ? "green" : "red";

      document.getElementById('marksheetPrintArea').style.display = 'block';
    }
  </script>
</body>
</html>
