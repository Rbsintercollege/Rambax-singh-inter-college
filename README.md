<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rambax Singh Inter College (RBS) | Bithara, Aliganj, Etah</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Rambax Singh Inter College & Residential Hostel | Bithara, Aliganj, Etah</title>
  
  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  
  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
  
  <!-- Google Fonts: Cinzel for Heritage, Inter for UI, Libre Barcode for Marksheet -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@600;700;800;900&family=Inter:wght@300;400;500;600;700;800;900&family=Libre+Barcode+39+Text&family=Playfair+Display:ital,wght@0,600;0,700;1,400&display=swap" rel="stylesheet">
  
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            brand: {
              navy: '#07172c',
              dark: '#040d1a',
              lightnavy: '#0e2648',
              gold: '#d4af37',
              golddark: '#b38f24',
              goldlight: '#f7f0d8',
              goldborder: '#e8c868',
              crimson: '#8a151b'
            }
          },
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
            serif: ['Cinzel', 'Georgia', 'serif'],
            heading: ['Playfair Display', 'serif'],
            barcode: ['"Libre Barcode 39 Text"', 'monospace']
          }
        }
      }
    }
  </script>

  <style>
    @media print {
      body * {
        visibility: hidden !important;
      }
      #printableMarksheet, #printableMarksheet * {
        visibility: visible !important;
      }
      #printableMarksheet {
        position: absolute !important;
        left: 0 !important;
        top: 0 !important;
        width: 100% !important;
        margin: 0 !important;
        padding: 18px !important;
        border: 4px double #07172c !important;
        box-shadow: none !important;
        background: #ffffff !important;
      }
      .no-print {
        display: none !important;
      }
    }

    .gold-gradient {
      background: linear-gradient(135deg, #f3d478 0%, #d4af37 50%, #9e7d17 100%);
    }
    .navy-gradient {
      background: linear-gradient(135deg, #040d1a 0%, #07172c 55%, #112d54 100%);
    }
    .badge-gradient {
      background: linear-gradient(135deg, #8a151b 0%, #07172c 100%);
    }

    /* Academic Marks Grid Border Stylings */
    .table-academic th, .table-academic td {
      border: 1px solid #1e293b;
      padding: 6px 8px;
    }

    /* Custom scrollbars */
    ::-webkit-scrollbar {
      width: 6px;
      height: 6px;
    }
    ::-webkit-scrollbar-track {
      background: #f1f5f9;
    }
    ::-webkit-scrollbar-thumb {
      background: #cbd5e1;
      border-radius: 4px;
    }
    ::-webkit-scrollbar-thumb:hover {
      background: #94a3b8;
    }
  </style>
</head>
<body class="bg-slate-50 text-slate-800 font-sans antialiased selection:bg-brand-gold selection:text-brand-navy min-h-screen flex flex-col">

  <!-- Floating Toast Message Container -->
  <div id="toastContainer" class="fixed top-5 right-5 z-[9999] flex flex-col space-y-2 pointer-events-none"></div>

  <div class="bg-brand-dark text-white text-xs md:text-sm py-2 px-4 border-b border-brand-gold/30">
    <div class="max-w-7xl mx-auto flex flex-col sm:flex-row items-center justify-between gap-2">
      <div class="flex items-center space-x-6 flex-wrap justify-center sm:justify-start">
        <a href="tel:6395052394" class="flex items-center space-x-1.5 hover:text-brand-gold transition">
          <i class="fa-solid fa-phone-volume text-brand-gold"></i>
          <span class="font-semibold">+91 6395052394</span>
        </a>
        <a href="mailto:rambaxsinghintercollege@gmail.com" class="flex items-center space-x-1.5 hover:text-brand-gold transition">
          <i class="fa-solid fa-envelope text-brand-gold"></i>
          <span>rambaxsinghintercollege@gmail.com</span>
        </a>
        <span class="hidden md:inline-flex items-center text-slate-300">
          <i class="fa-solid fa-hotel text-brand-gold mr-1.5"></i>
          Boys & Girls Residential Hostel Available
        </span>
      </div>
      <div class="flex items-center space-x-3 text-xs">
        <span class="bg-brand-gold/20 text-brand-gold px-2.5 py-0.5 rounded-full font-bold border border-brand-gold/30 uppercase tracking-wider">
          <i class="fa-solid fa-shield-halved mr-1"></i> UP Board Recognised
        </span>
        <button onclick="openLoginModal('admin')" class="hover:text-brand-gold transition underline font-semibold">Admin</button>
        <span class="text-slate-500">|</span>
        <button onclick="openLoginModal('staff')" class="hover:text-brand-gold transition underline font-semibold">Staff</button>
        <span class="text-slate-500">|</span>
        <button onclick="openLoginModal('student')" class="hover:text-brand-gold transition underline font-semibold">Student</button>
      </div>
    </div>
  </div>

  <header class="sticky top-0 z-50 bg-white/95 backdrop-blur shadow-md border-b border-slate-200">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-2.5 flex items-center justify-between">
      
      <!-- College Logo & Title -->
      <a href="#" onclick="showSection('public-home')" class="flex items-center space-x-3 group">
        <!-- SVG Crest Replica -->
        <div class="w-14 h-14 sm:w-16 sm:h-16 flex-shrink-0 transition-transform group-hover:scale-105 duration-200">
          <img src="rbslogo.jpeg" alt="RBS Inter College Emblem" class="w-full h-full object-contain rounded-full shadow-md border-2 border-brand-gold" onerror="this.outerHTML='<div class=\'w-full h-full rounded-full bg-brand-navy border-2 border-brand-gold flex items-center justify-center text-brand-gold font-bold font-serif\'>RBS</div>'">
        </div>
        <div>
          <div class="flex items-center space-x-2">
            <h1 class="text-base sm:text-xl font-black font-serif text-brand-navy tracking-tight uppercase leading-none">
              Rambax Singh Inter College
            </h1>
          </div>
          <p class="text-[11px] sm:text-xs font-bold text-amber-700 tracking-wider flex items-center gap-1 mt-0.5">
            <i class="fa-solid fa-bed text-brand-gold"></i> &amp; Residential Hostel Facility &bull; Bithara - Sarai Road, Aliganj, Etah
          </p>
        </div>
      </a>

      <!-- Desktop Nav -->
      <nav class="hidden lg:flex items-center space-x-6 text-sm font-semibold text-slate-700">
        <a href="#home" onclick="showSection('public-home')" class="hover:text-brand-navy transition py-1">Home</a>
        <a href="#gallery" onclick="scrollToElement('gallery-section')" class="hover:text-brand-navy transition py-1 flex items-center text-brand-navy font-bold">
          <i class="fa-solid fa-images text-brand-gold mr-1.5"></i> Campus Gallery
        </a>
        <a href="#hostel" onclick="scrollToElement('hostel-section')" class="hover:text-brand-navy transition py-1 flex items-center text-amber-900 font-bold">
          <i class="fa-solid fa-hotel text-brand-gold mr-1.5"></i> Hostel Life
        </a>
        <a href="#leadership" onclick="scrollToElement('leadership-section')" class="hover:text-brand-navy transition py-1">Leadership</a>
        <a href="#admissions" onclick="scrollToElement('admission-form-section')" class="hover:text-brand-navy transition py-1">Admissions</a>
        <a href="#contact" onclick="scrollToElement('contact-section')" class="hover:text-brand-navy transition py-1">Contact</a>
      </nav>

      <!-- Portals CTA -->
      <div class="hidden sm:flex items-center space-x-2">
        <button onclick="openLoginModal('student')" class="px-3.5 py-2 text-xs font-bold rounded-xl border border-brand-navy text-brand-navy hover:bg-brand-navy hover:text-white transition flex items-center space-x-1.5">
          <i class="fa-solid fa-graduation-cap"></i>
          <span>Student Portal</span>
        </button>
        <button onclick="openLoginModal('admin')" class="px-3.5 py-2 text-xs font-bold rounded-xl bg-brand-navy text-brand-gold hover:bg-brand-lightnavy shadow-sm transition border border-brand-gold/40 flex items-center space-x-1.5">
          <i class="fa-solid fa-shield-halved"></i>
          <span>Admin / Staff</span>
        </button>
      </div>

      <button onclick="toggleMobileNav()" class="lg:hidden p-2 rounded-lg text-slate-700 hover:bg-slate-100">
        <i class="fa-solid fa-bars text-xl"></i>
      </button>
    </div>

    <!-- Mobile Drawer -->
    <div id="mobileMenu" class="hidden lg:hidden bg-white border-b border-slate-200 px-4 pt-2 pb-4 space-y-2 text-sm font-medium">
      <a href="#home" onclick="showSection('public-home'); toggleMobileNav()" class="block py-2 px-3 rounded hover:bg-slate-100">Home</a>
      <a href="#gallery" onclick="scrollToElement('gallery-section'); toggleMobileNav()" class="block py-2 px-3 rounded hover:bg-slate-100 font-bold text-brand-navy">
        <i class="fa-solid fa-images mr-1 text-brand-gold"></i> School Photo Gallery
      </a>
      <a href="#hostel" onclick="scrollToElement('hostel-section'); toggleMobileNav()" class="block py-2 px-3 rounded hover:bg-slate-100 font-bold text-amber-800">
        <i class="fa-solid fa-hotel mr-1 text-brand-gold"></i> Residential Hostel Facilities
      </a>
      <a href="#leadership" onclick="scrollToElement('leadership-section'); toggleMobileNav()" class="block py-2 px-3 rounded hover:bg-slate-100">College Leadership</a>
      <a href="#admissions" onclick="scrollToElement('admission-form-section'); toggleMobileNav()" class="block py-2 px-3 rounded hover:bg-slate-100">Online Admission</a>
      <div class="pt-2 grid grid-cols-2 gap-2">
        <button onclick="openLoginModal('admin'); toggleMobileNav()" class="py-2 text-xs bg-brand-navy text-brand-gold rounded-lg font-bold">Admin Login</button>
        <button onclick="openLoginModal('student'); toggleMobileNav()" class="py-2 text-xs border border-brand-navy text-brand-navy rounded-lg font-bold">Student Portal</button>
      </div>
    </div>
  </header>

  <main id="mainPublicView" class="flex-grow">
    
    <!-- Hero Section with Real Campus Background Accent -->
    <section class="relative text-white overflow-hidden py-14 lg:py-20 border-b-4 border-brand-gold">
      <div class="absolute inset-0 z-0">
        <img src="rbs9.jpg" alt="RBS Campus Courtyard" class="w-full h-full object-cover object-center brightness-[0.22] contrast-[1.1]">
        <div class="absolute inset-0 bg-gradient-to-r from-brand-dark/95 via-brand-navy/90 to-brand-dark/95"></div>
      </div>
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
          
          <div class="lg:col-span-7 space-y-5 text-center lg:text-left">
            <div class="inline-flex items-center space-x-2 bg-brand-gold/20 border border-brand-gold/40 text-brand-gold text-xs uppercase tracking-widest px-3.5 py-1.5 rounded-full font-bold">
              <i class="fa-solid fa-hotel"></i>
              <span>UP Board Recognized &bull; Campus Residential Hostel</span>
            </div>
            
            <h1 class="text-3xl sm:text-5xl font-black font-serif leading-tight">
              Rambax Singh Inter College &amp; Residential Hostel
            </h1>
            
            <p class="text-slate-300 text-sm sm:text-base leading-relaxed">
              Fostering excellence in academics, moral values, and personality development at <strong>Bithara - Sarai Road, Aliganj, Etah</strong>. Complete boarding environment with 24x7 power backup, hygienic dining, regular exams, and active personal care under <strong>Director Avadhesh Singh</strong> and <strong>Manager Vishnu Kant</strong>.
            </p>

            <div class="flex flex-wrap gap-3 justify-center lg:justify-start pt-2">
              <button onclick="scrollToElement('admission-form-section')" class="px-6 py-3.5 gold-gradient text-brand-navy rounded-xl font-black text-sm tracking-wide shadow-lg hover:scale-105 transition transform flex items-center space-x-2">
                <i class="fa-solid fa-file-signature"></i>
                <span>College &amp; Hostel Admission 2025-26</span>
              </button>
              
              <button onclick="scrollToElement('gallery-section')" class="px-5 py-3.5 bg-white/10 hover:bg-white/20 border border-white/30 text-white rounded-xl font-bold text-sm transition flex items-center space-x-2 backdrop-blur">
                <i class="fa-solid fa-images text-brand-gold"></i>
                <span>Explore Campus Photos</span>
              </button>
            </div>

            <!-- Stats Bar -->
            <div class="grid grid-cols-3 gap-3 pt-5 border-t border-slate-700/60 max-w-lg mx-auto lg:mx-0 text-left">
              <div>
                <p class="text-2xl sm:text-3xl font-extrabold text-brand-gold">200+</p>
                <p class="text-xs text-slate-300 font-medium">Hostel Boarders</p>
              </div>
              <div>
                <p class="text-2xl sm:text-3xl font-extrabold text-brand-gold">100%</p>
                <p class="text-xs text-slate-300 font-medium">Board Exam Pass</p>
              </div>
              <div>
                <p class="text-2xl sm:text-3xl font-extrabold text-brand-gold">24x7</p>
                <p class="text-xs text-slate-300 font-medium">Power &amp; Supervision</p>
              </div>
            </div>
          </div>

          <!-- Hero Right Emblem & Real Campus Quick Glimpse -->
          <div class="lg:col-span-5 flex justify-center">
            <div class="w-full max-w-md bg-white/10 backdrop-blur-md border border-brand-gold/40 p-5 sm:p-6 rounded-3xl text-center shadow-2xl relative">
              <div class="relative mb-4 group cursor-pointer" onclick="openLightbox('rbs9.jpg', 'RBS Inter College Paved Campus & Greenery')">
                <img src="rbs9.jpg" alt="RBS Campus Courtyard" class="w-full h-48 object-cover rounded-2xl border-2 border-brand-gold/60 shadow-lg">
                <div class="absolute inset-0 bg-brand-navy/30 rounded-2xl flex items-center justify-center opacity-0 group-hover:opacity-100 transition duration-300">
                  <span class="bg-brand-navy/90 text-brand-gold text-xs px-3 py-1.5 rounded-full font-bold flex items-center gap-1.5 shadow">
                    <i class="fa-solid fa-magnifying-glass-plus"></i> View Courtyard
                  </span>
                </div>
                <div class="absolute top-2 left-2 w-12 h-12 rounded-full overflow-hidden border-2 border-brand-gold shadow-md">
                  <img src="rbslogo.jpeg" alt="Logo" class="w-full h-full object-cover">
                </div>
              </div>

              <h2 class="text-lg font-bold font-serif text-white">RAMBAX SINGH INTER COLLEGE</h2>
              <p class="text-xs text-brand-gold font-bold">&amp; RESIDENTIAL HOSTEL CAMPUS</p>
              <p class="text-[11px] text-slate-300 mt-1">Bithara - Sarai Road, Post Aliganj, Dist. Etah (U.P.)</p>

              <div class="mt-4 pt-3 border-t border-white/20 grid grid-cols-2 gap-3 text-left">
                <div class="bg-white/5 p-3 rounded-xl border border-white/10">
                  <p class="text-[10px] text-brand-gold uppercase font-bold">Director</p>
                  <p class="text-sm font-bold text-white mt-0.5">Avadhesh Singh</p>
                </div>
                <div class="bg-white/5 p-3 rounded-xl border border-white/10">
                  <p class="text-[10px] text-brand-gold uppercase font-bold">Manager</p>
                  <p class="text-sm font-bold text-white mt-0.5">Vishnu Kant</p>
                  <p class="text-[10px] text-slate-300">📞 6395052394</p>
                </div>
              </div>
            </div>
          </div>

        </div>
      </div>
    </section>

    <!-- Photo Gallery Showcase Section -->
    <section id="gallery-section" class="py-16 bg-slate-100 border-b border-slate-200">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        
        <div class="text-center max-w-3xl mx-auto mb-10">
          <span class="text-xs uppercase font-extrabold tracking-widest text-brand-gold bg-brand-navy px-3.5 py-1 rounded-full border border-brand-gold/30">
            <i class="fa-solid fa-camera-retro mr-1 text-brand-gold"></i> Live Moments &amp; Activities
          </span>
          <h2 class="text-3xl sm:text-4xl font-serif font-black text-brand-navy mt-3">
            Life At Rambax Singh Inter College &amp; Hostel
          </h2>
          <div class="w-20 h-1 bg-brand-gold mx-auto mt-3 rounded-full"></div>
          <p class="text-slate-600 text-xs sm:text-sm mt-2">
            Capturing classroom learning, national Republic Day celebrations, prize awards, cultural plays, and serene campus grounds.
          </p>

          <!-- Gallery Filter Buttons -->
          <div class="flex flex-wrap justify-center gap-2 mt-6">
            <button onclick="filterGallery('all')" class="gallery-filter-btn active-filter px-4 py-1.5 rounded-full text-xs font-bold transition bg-brand-navy text-white shadow">All Photos (10)</button>
            <button onclick="filterGallery('events')" class="gallery-filter-btn px-4 py-1.5 rounded-full text-xs font-bold transition bg-white text-slate-700 hover:bg-slate-200 border">Republic Day &amp; Celebrations</button>
            <button onclick="filterGallery('academics')" class="gallery-filter-btn px-4 py-1.5 rounded-full text-xs font-bold transition bg-white text-slate-700 hover:bg-slate-200 border">Classrooms &amp; Faculty</button>
            <button onclick="filterGallery('culture')" class="gallery-filter-btn px-4 py-1.5 rounded-full text-xs font-bold transition bg-white text-slate-700 hover:bg-slate-200 border">Cultural &amp; Krishna Leela</button>
            <button onclick="filterGallery('campus')" class="gallery-filter-btn px-4 py-1.5 rounded-full text-xs font-bold transition bg-white text-slate-700 hover:bg-slate-200 border">Campus &amp; Grounds</button>
          </div>
        </div>

        <!-- Dynamic Grid of 10 Real Images -->
        <div id="schoolGalleryGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-5">

          <!-- 1. Campus Courtyard -->
          <div class="gallery-card bg-white rounded-2xl overflow-hidden shadow-sm hover:shadow-xl transition-all duration-300 border border-slate-200 group flex flex-col" data-category="campus">
            <div class="relative overflow-hidden h-52 cursor-pointer" onclick="openLightbox('rbs9.jpg', 'School Campus & Paved Green Courtyard')">
              <img src="rbs9.jpg" alt="RBS Campus Courtyard" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
              <span class="absolute top-2.5 right-2.5 bg-brand-navy/85 text-brand-gold text-[10px] font-bold px-2 py-0.5 rounded-md backdrop-blur">
                Campus View
              </span>
              <div class="absolute inset-0 bg-brand-navy/30 opacity-0 group-hover:opacity-100 transition flex items-center justify-center">
                <i class="fa-solid fa-expand text-white text-xl bg-brand-navy/70 p-3 rounded-full"></i>
              </div>
            </div>
            <div class="p-3.5 flex-grow flex flex-col justify-between">
              <div>
                <h4 class="text-sm font-bold text-brand-navy font-serif">Paved Campus &amp; School Building</h4>
                <p class="text-[11px] text-slate-500 mt-0.5">Clean, airy and green school corridors in Bithara, Aliganj.</p>
              </div>
            </div>
          </div>

          <!-- 2. Republic Day Certificate Ceremony with Manager Vishnu Kant & Director -->
          <div class="gallery-card bg-white rounded-2xl overflow-hidden shadow-sm hover:shadow-xl transition-all duration-300 border border-slate-200 group flex flex-col" data-category="events">
            <div class="relative overflow-hidden h-52 cursor-pointer" onclick="openLightbox('rbs6.jpg', '26th January Republic Day Merit Award & Certificate Ceremony')">
              <img src="rbs6.jpg" alt="Republic Day Award Ceremony" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
              <span class="absolute top-2.5 right-2.5 bg-emerald-700 text-white text-[10px] font-bold px-2 py-0.5 rounded-md">
                Award Function
              </span>
              <div class="absolute inset-0 bg-brand-navy/30 opacity-0 group-hover:opacity-100 transition flex items-center justify-center">
                <i class="fa-solid fa-expand text-white text-xl bg-brand-navy/70 p-3 rounded-full"></i>
              </div>
            </div>
            <div class="p-3.5 flex-grow flex flex-col justify-between">
              <div>
                <h4 class="text-sm font-bold text-brand-navy font-serif">Merit Certificate Presentation</h4>
                <p class="text-[11px] text-slate-500 mt-0.5">Director Avadhesh Singh &amp; Manager Vishnu Kant honoring meritorious students.</p>
              </div>
            </div>
          </div>

          <!-- 3. Morning Republic Day Rally with Flag and Balloons -->
          <div class="gallery-card bg-white rounded-2xl overflow-hidden shadow-sm hover:shadow-xl transition-all duration-300 border border-slate-200 group flex flex-col" data-category="events">
            <div class="relative overflow-hidden h-52 cursor-pointer" onclick="openLightbox('rbs8.jpg', 'Morning Republic Day Rally & Tricolor Celebration')">
              <img src="rbs8.jpg" alt="Republic Day Rally" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
              <span class="absolute top-2.5 right-2.5 bg-amber-600 text-white text-[10px] font-bold px-2 py-0.5 rounded-md">
                Republic Day
              </span>
              <div class="absolute inset-0 bg-brand-navy/30 opacity-0 group-hover:opacity-100 transition flex items-center justify-center">
                <i class="fa-solid fa-expand text-white text-xl bg-brand-navy/70 p-3 rounded-full"></i>
              </div>
            </div>
            <div class="p-3.5 flex-grow flex flex-col justify-between">
              <div>
                <h4 class="text-sm font-bold text-brand-navy font-serif">Grand Tricolor Parade &amp; Rally</h4>
                <p class="text-[11px] text-slate-500 mt-0.5">Students marching with national flags and balloons in the courtyard.</p>
              </div>
            </div>
          </div>

          <!-- 4. Classroom Lecture & Teaching -->
          <div class="gallery-card bg-white rounded-2xl overflow-hidden shadow-sm hover:shadow-xl transition-all duration-300 border border-slate-200 group flex flex-col" data-category="academics">
            <div class="relative overflow-hidden h-52 cursor-pointer" onclick="openLightbox('rbs10.jpg', 'Interactive Classroom Session & Board Guidance')">
              <img src="rbs10.jpg" alt="Classroom Session" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
              <span class="absolute top-2.5 right-2.5 bg-blue-700 text-white text-[10px] font-bold px-2 py-0.5 rounded-md">
                Classroom Study
              </span>
              <div class="absolute inset-0 bg-brand-navy/30 opacity-0 group-hover:opacity-100 transition flex items-center justify-center">
                <i class="fa-solid fa-expand text-white text-xl bg-brand-navy/70 p-3 rounded-full"></i>
              </div>
            </div>
            <div class="p-3.5 flex-grow flex flex-col justify-between">
              <div>
                <h4 class="text-sm font-bold text-brand-navy font-serif">Daily Supervised Classroom Lecture</h4>
                <p class="text-[11px] text-slate-500 mt-0.5">Dedicated faculty conducting rigorous UP Board exam preparation.</p>
              </div>
            </div>
          </div>

          <!-- 5. Republic Day Stage Skit / Patriotic Presentation -->
          <div class="gallery-card bg-white rounded-2xl overflow-hidden shadow-sm hover:shadow-xl transition-all duration-300 border border-slate-200 group flex flex-col" data-category="culture">
            <div class="relative overflow-hidden h-52 cursor-pointer" onclick="openLightbox('rbs7.jpg', 'Republic Day Stage Performance by Students')">
              <img src="rbs7.jpg" alt="Republic Day Stage Show" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
              <span class="absolute top-2.5 right-2.5 bg-rose-700 text-white text-[10px] font-bold px-2 py-0.5 rounded-md">
                Stage Drama
              </span>
              <div class="absolute inset-0 bg-brand-navy/30 opacity-0 group-hover:opacity-100 transition flex items-center justify-center">
                <i class="fa-solid fa-expand text-white text-xl bg-brand-navy/70 p-3 rounded-full"></i>
              </div>
            </div>
            <div class="p-3.5 flex-grow flex flex-col justify-between">
              <div>
                <h4 class="text-sm font-bold text-brand-navy font-serif">Patriotic Stage Presentation</h4>
                <p class="text-[11px] text-slate-500 mt-0.5">Girls performing under the official Residential R.B.S. Inter College banner.</p>
              </div>
            </div>
          </div>

          <!-- 6. Krishna Leela Cultural Attire -->
          <div class="gallery-card bg-white rounded-2xl overflow-hidden shadow-sm hover:shadow-xl transition-all duration-300 border border-slate-200 group flex flex-col" data-category="culture">
            <div class="relative overflow-hidden h-52 cursor-pointer" onclick="openLightbox('rbs2.jpg', 'Krishna & Balram Fancy Dress Presentation')">
              <img src="rbs2.jpg" alt="Krishna Leela Attire" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
              <span class="absolute top-2.5 right-2.5 bg-amber-500 text-brand-navy text-[10px] font-bold px-2 py-0.5 rounded-md">
                Krishna Leela
              </span>
              <div class="absolute inset-0 bg-brand-navy/30 opacity-0 group-hover:opacity-100 transition flex items-center justify-center">
                <i class="fa-solid fa-expand text-white text-xl bg-brand-navy/70 p-3 rounded-full"></i>
              </div>
            </div>
            <div class="p-3.5 flex-grow flex flex-col justify-between">
              <div>
                <h4 class="text-sm font-bold text-brand-navy font-serif">Krishna &amp; Balram Fancy Dress</h4>
                <p class="text-[11px] text-slate-500 mt-0.5">Students in traditional yellow attire, mor-pankh crowns and flute.</p>
              </div>
            </div>
          </div>

          <!-- 7. Group Cultural Presentation -->
          <div class="gallery-card bg-white rounded-2xl overflow-hidden shadow-sm hover:shadow-xl transition-all duration-300 border border-slate-200 group flex flex-col" data-category="culture">
            <div class="relative overflow-hidden h-52 cursor-pointer" onclick="openLightbox('rbs3.jpg', 'Group Cultural Performance & Traditional Dress')">
              <img src="rbs3.jpg" alt="Cultural Group Dance" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
              <span class="absolute top-2.5 right-2.5 bg-pink-700 text-white text-[10px] font-bold px-2 py-0.5 rounded-md">
                Folk Attire
              </span>
              <div class="absolute inset-0 bg-brand-navy/30 opacity-0 group-hover:opacity-100 transition flex items-center justify-center">
                <i class="fa-solid fa-expand text-white text-xl bg-brand-navy/70 p-3 rounded-full"></i>
              </div>
            </div>
            <div class="p-3.5 flex-grow flex flex-col justify-between">
              <div>
                <h4 class="text-sm font-bold text-brand-navy font-serif">Janmashtami &amp; Folk Dance Group</h4>
                <p class="text-[11px] text-slate-500 mt-0.5">Children dressed in bright traditional lehengas and crowns for celebration.</p>
              </div>
            </div>
          </div>

          <!-- 8. Teachers Day Celebration & Cake Cutting -->
          <div class="gallery-card bg-white rounded-2xl overflow-hidden shadow-sm hover:shadow-xl transition-all duration-300 border border-slate-200 group flex flex-col" data-category="events">
            <div class="relative overflow-hidden h-52 cursor-pointer" onclick="openLightbox('rbs4.jpg', 'Teachers Day Classroom Cake Cutting Ceremony')">
              <img src="rbs4.jpg" alt="Teachers Day Cake Cutting" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
              <span class="absolute top-2.5 right-2.5 bg-purple-700 text-white text-[10px] font-bold px-2 py-0.5 rounded-md">
                Teachers' Day
              </span>
              <div class="absolute inset-0 bg-brand-navy/30 opacity-0 group-hover:opacity-100 transition flex items-center justify-center">
                <i class="fa-solid fa-expand text-white text-xl bg-brand-navy/70 p-3 rounded-full"></i>
              </div>
            </div>
            <div class="p-3.5 flex-grow flex flex-col justify-between">
              <div>
                <h4 class="text-sm font-bold text-brand-navy font-serif">Teachers' Day Joyous Celebration</h4>
                <p class="text-[11px] text-slate-500 mt-0.5">Faculty, elders and students gathering for the traditional cake cutting.</p>
              </div>
            </div>
          </div>

          <!-- 9. Management Room Celebration & Portraits -->
          <div class="gallery-card bg-white rounded-2xl overflow-hidden shadow-sm hover:shadow-xl transition-all duration-300 border border-slate-200 group flex flex-col" data-category="academics">
            <div class="relative overflow-hidden h-52 cursor-pointer" onclick="openLightbox('rbs5.jpg', 'Staff & Management Office Celebration')">
              <img src="rbs5.jpg" alt="Staff Management Office" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
              <span class="absolute top-2.5 right-2.5 bg-brand-navy text-brand-gold text-[10px] font-bold px-2 py-0.5 rounded-md">
                Staff Office
              </span>
              <div class="absolute inset-0 bg-brand-navy/30 opacity-0 group-hover:opacity-100 transition flex items-center justify-center">
                <i class="fa-solid fa-expand text-white text-xl bg-brand-navy/70 p-3 rounded-full"></i>
              </div>
            </div>
            <div class="p-3.5 flex-grow flex flex-col justify-between">
              <div>
                <h4 class="text-sm font-bold text-brand-navy font-serif">College Administrative Office</h4>
                <p class="text-[11px] text-slate-500 mt-0.5">Manager Vishnu Kant, Director, teachers and elders at the college chamber.</p>
              </div>
            </div>
          </div>

          <!-- 10. Student Academic Prize / Appreciation -->
          <div class="gallery-card bg-white rounded-2xl overflow-hidden shadow-sm hover:shadow-xl transition-all duration-300 border border-slate-200 group flex flex-col" data-category="academics">
            <div class="relative overflow-hidden h-52 cursor-pointer" onclick="openLightbox('rbs1.jpg', 'Faculty Awarding Meritorious Students in Class')">
              <img src="rbs1.jpg" alt="Prize Distribution" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
              <span class="absolute top-2.5 right-2.5 bg-emerald-700 text-white text-[10px] font-bold px-2 py-0.5 rounded-md">
                Student Prize
              </span>
              <div class="absolute inset-0 bg-brand-navy/30 opacity-0 group-hover:opacity-100 transition flex items-center justify-center">
                <i class="fa-solid fa-expand text-white text-xl bg-brand-navy/70 p-3 rounded-full"></i>
              </div>
            </div>
            <div class="p-3.5 flex-grow flex flex-col justify-between">
              <div>
                <h4 class="text-sm font-bold text-brand-navy font-serif">Student Encouragement Award</h4>
                <p class="text-[11px] text-slate-500 mt-0.5">Academic recognition and pen distribution for sincere class attendance.</p>
              </div>
            </div>
          </div>

        </div>

      </div>
    </section>

    <!-- Global Photo Lightbox Modal -->
    <div id="photoLightboxModal" class="fixed inset-0 z-[99999] bg-black/90 backdrop-blur-md hidden flex flex-col items-center justify-center p-4">
      <div class="relative max-w-4xl w-full max-h-[90vh] flex flex-col items-center">
        <button onclick="closeLightbox()" class="absolute -top-12 right-0 text-white hover:text-brand-gold text-2xl px-3 py-1">
          <i class="fa-solid fa-xmark"></i>
        </button>
        <img id="lightboxImage" src="" alt="Zoomed View" class="max-h-[75vh] w-auto max-w-full rounded-2xl border-2 border-brand-gold shadow-2xl object-contain">
        <p id="lightboxCaption" class="text-white text-center text-sm font-semibold mt-3 bg-brand-navy/80 px-4 py-2 rounded-xl border border-brand-gold/40"></p>
      </div>
    </div>

    <section id="hostel-section" class="py-16 bg-white border-b border-slate-200">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        
        <div class="text-center max-w-3xl mx-auto mb-12">
          <span class="text-xs uppercase font-extrabold tracking-widest text-brand-gold bg-brand-goldlight px-3 py-1 rounded-full border border-brand-gold/30">
            <i class="fa-solid fa-hotel mr-1"></i> Campus Boarding Facility
          </span>
          <h2 class="text-3xl sm:text-4xl font-serif font-black text-brand-navy mt-3">
            Residential Hostel at Rambax Singh Inter College
          </h2>
          <div class="w-20 h-1 bg-brand-gold mx-auto mt-3 rounded-full"></div>
          <p class="text-slate-600 text-sm sm:text-base mt-3">
            A safe, home-like environment fostering academic excellence, physical fitness, personal discipline, and focused preparation for competitive examinations.
          </p>
        </div>

        <!-- Hostel Key Feature Pillars -->
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
          <div class="bg-slate-50 border-2 border-slate-200 rounded-3xl p-6 hover:border-brand-gold transition shadow-sm">
            <div class="w-12 h-12 rounded-2xl bg-amber-100 text-amber-800 flex items-center justify-center text-xl mb-4 font-bold">
              <i class="fa-solid fa-utensils"></i>
            </div>
            <h3 class="text-lg font-bold font-serif text-brand-navy">Nutritious Mess &amp; Pure Water</h3>
            <p class="text-xs text-slate-600 mt-2 leading-relaxed">
              Four times fresh, hot vegetarian meals prepared under hygienic supervision. 100% RO purified drinking water and special wholesome diet for growing students.
            </p>
            <ul class="mt-4 space-y-1.5 text-xs text-slate-700 font-medium">
              <li><i class="fa-solid fa-check text-emerald-600 mr-1.5"></i> Daily Morning Milk &amp; Breakfast</li>
              <li><i class="fa-solid fa-check text-emerald-600 mr-1.5"></i> Wholesome Lunch &amp; Dinner Menu</li>
              <li><i class="fa-solid fa-check text-emerald-600 mr-1.5"></i> Clean Dining Hall Environment</li>
            </ul>
          </div>

          <div class="bg-slate-50 border-2 border-slate-200 rounded-3xl p-6 hover:border-brand-gold transition shadow-sm">
            <div class="w-12 h-12 rounded-2xl bg-blue-100 text-blue-800 flex items-center justify-center text-xl mb-4 font-bold">
              <i class="fa-solid fa-book-reader"></i>
            </div>
            <h3 class="text-lg font-bold font-serif text-brand-navy">Mandatory Supervised Self-Study</h3>
            <p class="text-xs text-slate-600 mt-2 leading-relaxed">
              Fixed morning and evening study sessions under the active supervision of resident teachers and wardens to clear student doubts daily.
            </p>
            <ul class="mt-4 space-y-1.5 text-xs text-slate-700 font-medium">
              <li><i class="fa-solid fa-check text-emerald-600 mr-1.5"></i> 2 Hours Morning Revision Routine</li>
              <li><i class="fa-solid fa-check text-emerald-600 mr-1.5"></i> Evening Faculty Doubt Clearance</li>
              <li><i class="fa-solid fa-check text-emerald-600 mr-1.5"></i> Strict No-Distraction Study Hall</li>
            </ul>
          </div>

          <div class="bg-slate-50 border-2 border-slate-200 rounded-3xl p-6 hover:border-brand-gold transition shadow-sm">
            <div class="w-12 h-12 rounded-2xl bg-emerald-100 text-emerald-800 flex items-center justify-center text-xl mb-4 font-bold">
              <i class="fa-solid fa-shield-virus"></i>
            </div>
            <h3 class="text-lg font-bold font-serif text-brand-navy">24x7 Security &amp; Medical Care</h3>
            <p class="text-xs text-slate-600 mt-2 leading-relaxed">
              Complete CCTV surveillance throughout corridors and entry gates. Full-time resident warden on premises and on-call medical doctors.
            </p>
            <ul class="mt-4 space-y-1.5 text-xs text-slate-700 font-medium">
              <li><i class="fa-solid fa-check text-emerald-600 mr-1.5"></i> 24-Hour Electricity with Generator Backup</li>
              <li><i class="fa-solid fa-check text-emerald-600 mr-1.5"></i> Dedicated Emergency Medical First-Aid</li>
              <li><i class="fa-solid fa-check text-emerald-600 mr-1.5"></i> Separate Safe Dormitories</li>
            </ul>
          </div>
        </div>

        <!-- Hostel Daily Routine Banner -->
        <div class="mt-10 bg-brand-navy text-white rounded-3xl p-6 sm:p-8 border border-brand-gold/40">
          <div class="flex flex-col lg:flex-row items-center justify-between gap-6">
            <div class="space-y-2 text-center lg:text-left">
              <span class="text-xs uppercase text-brand-gold font-bold tracking-wider">A Day in RBS Hostel</span>
              <h4 class="text-2xl font-serif font-black">Disciplined Routine for Outstanding Results</h4>
              <p class="text-xs sm:text-sm text-slate-300 max-w-2xl">
                5:30 AM Wake Up &amp; PT Yoga &bull; 7:30 AM Breakfast &bull; 8:30 AM to 2:00 PM Academic Classes &bull; 2:30 PM Lunch &bull; 4:30 PM Sports &bull; 6:30 PM to 9:30 PM Supervised Evening Study &bull; 10:00 PM Lights Out.
              </p>
            </div>
            <div class="flex-shrink-0">
              <button onclick="scrollToElement('admission-form-section')" class="px-6 py-3.5 gold-gradient text-brand-navy font-black text-xs uppercase tracking-wider rounded-xl shadow-lg hover:scale-105 transition">
                Book Hostel Seat Today
              </button>
            </div>
          </div>
        </div>

      </div>
    </section>

    <section id="leadership-section" class="py-16 bg-slate-50 border-b border-slate-200">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        
        <div class="text-center max-w-3xl mx-auto mb-12">
          <span class="text-xs uppercase font-extrabold tracking-widest text-brand-gold">Administrative Pillars</span>
          <h2 class="text-3xl sm:text-4xl font-serif font-black text-brand-navy mt-1">Our College &amp; Hostel Leadership</h2>
          <div class="w-20 h-1 bg-brand-gold mx-auto mt-2 rounded-full"></div>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
          
          <!-- Director Card -->
          <div class="bg-white border-2 border-slate-200 rounded-3xl p-6 sm:p-8 hover:border-brand-gold transition duration-300 relative shadow-sm">
            <div class="flex items-start space-x-4">
              <div class="w-16 h-16 rounded-2xl bg-brand-navy text-brand-gold flex items-center justify-center text-2xl font-serif font-black shadow flex-shrink-0 border-2 border-brand-gold">
                AS
              </div>
              <div>
                <span class="bg-brand-navy/10 text-brand-navy text-[11px] font-extrabold uppercase px-2.5 py-0.5 rounded-full">
                  Director
                </span>
                <h3 class="text-2xl font-bold font-serif text-brand-navy mt-1">Avadhesh Singh</h3>
                <p class="text-xs text-brand-gold font-bold uppercase tracking-wider">Director, Rambax Singh Inter College</p>
              </div>
            </div>

            <div class="mt-4 text-slate-600 text-xs sm:text-sm leading-relaxed border-t border-slate-200 pt-3 space-y-2">
              <p>
                "At Rambax Singh Inter College &amp; Hostel, we emphasize total personal character. Rural students need not travel to distant cities to receive world-class education and disciplined boarding amenities."
              </p>
              <p>
                "Our hostel and teaching faculties work hand-in-hand to guarantee exceptional academic outcomes in every board examination."
              </p>
            </div>

            <div class="mt-4 pt-3 border-t border-slate-200 flex justify-between text-xs font-semibold text-slate-500">
              <span>Bithara, Aliganj, Etah</span>
              <span class="text-brand-navy font-bold">Office of the Director</span>
            </div>
          </div>

          <!-- Manager Card -->
          <div class="bg-white border-2 border-slate-200 rounded-3xl p-6 sm:p-8 hover:border-brand-gold transition duration-300 relative shadow-sm">
            <div class="flex items-start space-x-4">
              <div class="w-16 h-16 rounded-2xl bg-brand-gold text-brand-navy flex items-center justify-center text-2xl font-serif font-black shadow flex-shrink-0 border-2 border-brand-navy">
                VK
              </div>
              <div>
                <span class="bg-amber-100 text-amber-900 text-[11px] font-extrabold uppercase px-2.5 py-0.5 rounded-full">
                  Manager &amp; Administrator
                </span>
                <h3 class="text-2xl font-bold font-serif text-brand-navy mt-1">Vishnu Kant</h3>
                <p class="text-xs text-brand-gold font-bold uppercase tracking-wider">Manager, Rambax Singh Inter College</p>
              </div>
            </div>

            <div class="mt-4 text-slate-600 text-xs sm:text-sm leading-relaxed border-t border-slate-200 pt-3 space-y-2">
              <p>
                "As Manager, my primary commitment is the daily safety, healthy nutrition, and academic progress of every child entrusted to our hostel and college."
              </p>
              <p>
                "Parents are welcome to call my personal contact anytime regarding admissions, marksheet verification, or hostel accommodation."
              </p>
            </div>

            <div class="mt-4 pt-3 border-t border-slate-200 flex flex-wrap items-center justify-between gap-2 text-xs font-semibold">
              <a href="tel:6395052394" class="text-brand-navy bg-slate-100 px-3 py-1 rounded-lg border border-slate-300 hover:text-brand-gold transition flex items-center space-x-1.5 font-bold">
                <i class="fa-solid fa-phone text-brand-gold"></i>
                <span>+91 6395052394</span>
              </a>
              <a href="mailto:rambaxsinghintercollege@gmail.com" class="text-slate-600 hover:text-brand-navy transition flex items-center space-x-1">
                <i class="fa-solid fa-envelope text-brand-gold"></i>
                <span>rambaxsinghintercollege@gmail.com</span>
              </a>
            </div>
          </div>

        </div>
      </div>
    </section>

    <section class="py-14 bg-white border-b border-slate-200">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center max-w-2xl mx-auto mb-10">
          <span class="text-xs uppercase font-extrabold tracking-widest text-amber-800">Holistic Growth</span>
          <h3 class="text-2xl sm:text-3xl font-serif font-black text-brand-navy mt-1">Academics &bull; Hostel &bull; Culture</h3>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
          <div class="rounded-2xl border border-slate-200 overflow-hidden bg-slate-50 shadow-sm flex flex-col">
            <img src="rbs10.jpg" alt="Classroom" class="h-44 w-full object-cover">
            <div class="p-4 flex-grow">
              <h4 class="font-serif font-bold text-brand-navy text-base">UP Board Curriculum</h4>
              <p class="text-xs text-slate-600 mt-1">Science &amp; Arts streams with continuous evaluations, tests, and individual doubt-clearing sessions.</p>
            </div>
          </div>

          <div class="rounded-2xl border border-slate-200 overflow-hidden bg-slate-50 shadow-sm flex flex-col">
            <img src="rbs7.jpg" alt="Cultural Events" class="h-44 w-full object-cover">
            <div class="p-4 flex-grow">
              <h4 class="font-serif font-bold text-brand-navy text-base">Patriotic &amp; Cultural Values</h4>
              <p class="text-xs text-slate-600 mt-1">Grand Republic Day ceremonies, Independence Day, Janmashtami, and ethical moral character building.</p>
            </div>
          </div>

          <div class="rounded-2xl border border-slate-200 overflow-hidden bg-slate-50 shadow-sm flex flex-col">
            <img src="rbs9.jpg" alt="Campus Courtyard" class="h-44 w-full object-cover">
            <div class="p-4 flex-grow">
              <h4 class="font-serif font-bold text-brand-navy text-base">Discipline &amp; Boarding Life</h4>
              <p class="text-xs text-slate-600 mt-1">Clean paved campus, open sports grounds, nutritious mess, and 24x7 residential hostel care.</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Admission Application Form Section -->
    <section id="admission-form-section" class="py-16 bg-slate-50 border-b border-slate-200">
      <div class="max-w-4xl mx-auto px-4 sm:px-6">
        <div class="text-center mb-8">
          <span class="text-xs uppercase font-extrabold tracking-widest text-brand-gold bg-brand-navy px-3 py-1 rounded-full">Admission Open 2025-26</span>
          <h3 class="text-2xl sm:text-3xl font-serif font-black text-brand-navy mt-2">Online Admission &amp; Hostel Registration</h3>
          <p class="text-xs sm:text-sm text-slate-600 mt-1">Fill out the official registration form. Applications directly sync with Manager Vishnu Kant's terminal.</p>
        </div>

        <form id="publicAdmissionForm" onsubmit="handlePublicAdmissionSubmit(event)" class="bg-white rounded-3xl p-6 sm:p-8 border border-slate-200 shadow-md space-y-4 text-xs">
          <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
            <div>
              <label class="block font-bold text-slate-700 uppercase mb-1">Student Full Name *</label>
              <input type="text" id="admFullName" required placeholder="Full Name" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 font-medium">
            </div>
            <div>
              <label class="block font-bold text-slate-700 uppercase mb-1">Father's Name *</label>
              <input type="text" id="admFatherName" required placeholder="Father Name" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 font-medium">
            </div>
          </div>

          <div class="grid grid-cols-1 sm:grid-cols-3 gap-4">
            <div>
              <label class="block font-bold text-slate-700 uppercase mb-1">Mother's Name</label>
              <input type="text" id="admMotherName" placeholder="Mother Name" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 font-medium">
            </div>
            <div>
              <label class="block font-bold text-slate-700 uppercase mb-1">Date of Birth *</label>
              <input type="date" id="admDob" required class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 font-medium">
            </div>
            <div>
              <label class="block font-bold text-slate-700 uppercase mb-1">Applying For Class *</label>
              <select id="admClass" required class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 font-medium bg-white">
                <option value="Class 10th">Class 10th (High School)</option>
                <option value="Class 12th Science">Class 12th (Science Stream)</option>
                <option value="Class 12th Arts">Class 12th (Arts Stream)</option>
                <option value="Class 9th">Class 9th</option>
                <option value="Class 11th Science">Class 11th (Science)</option>
                <option value="Class 11th Arts">Class 11th (Arts)</option>
              </select>
            </div>
          </div>

          <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
            <div>
              <label class="block font-bold text-slate-700 uppercase mb-1">Hostel Accommodation Needed? *</label>
              <select id="admHostelReq" required class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 font-medium bg-white">
                <option value="Yes - Hostel Required">Yes - Residential Hostel Required</option>
                <option value="No - Day Scholar">No - Day Scholar (Local Student)</option>
              </select>
            </div>
            <div>
              <label class="block font-bold text-slate-700 uppercase mb-1">Parent Mobile / WhatsApp *</label>
              <input type="tel" id="admPhone" required placeholder="10-digit mobile number" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 font-medium">
            </div>
          </div>

          <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
            <div>
              <label class="block font-bold text-slate-700 uppercase mb-1">Previous School &amp; Marks %</label>
              <input type="text" id="admPrevSchool" placeholder="e.g. Previous School (80%)" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 font-medium">
            </div>
            <div>
              <label class="block font-bold text-slate-700 uppercase mb-1">Village / Town Address *</label>
              <input type="text" id="admAddress" required placeholder="Bithara, Aliganj, Etah" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 font-medium">
            </div>
          </div>

          <div class="pt-2 text-right">
            <button type="submit" class="px-6 py-3 gold-gradient text-brand-navy font-black text-xs uppercase tracking-wider rounded-xl shadow hover:scale-105 transition">
              Submit Application
            </button>
          </div>
        </form>
      </div>
    </section>

    <footer id="contact-section" class="bg-brand-dark text-white py-12 border-t border-brand-gold/30">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8 pb-8 border-b border-slate-800">
          <div>
            <h4 class="font-serif font-black text-lg text-white">Rambax Singh Inter College</h4>
            <p class="text-xs text-brand-gold font-bold mt-1">&amp; Residential Hostel Facility</p>
            <p class="text-xs text-slate-400 mt-2">Affiliated with UP Board. Quality education and disciplined residential boarding in Bithara, Aliganj, Etah.</p>
          </div>
          <div>
            <h5 class="text-xs font-bold uppercase tracking-wider text-brand-gold mb-3">College Leadership</h5>
            <ul class="space-y-1.5 text-xs text-slate-300">
              <li><strong>Director:</strong> Avadhesh Singh</li>
              <li><strong>Manager:</strong> Vishnu Kant</li>
              <li><strong>Phone:</strong> +91 6395052394</li>
              <li><strong>Email:</strong> rambaxsinghintercollege@gmail.com</li>
            </ul>
          </div>
          <div>
            <h5 class="text-xs font-bold uppercase tracking-wider text-brand-gold mb-3">Campus Address</h5>
            <p class="text-xs text-slate-300 leading-relaxed">
              Bithara - Sarai Road, Post Aliganj,<br>
              District Etah, Uttar Pradesh - 207247<br>
              Helpline: 6395052394
            </p>
          </div>
        </div>
        <div class="pt-6 flex flex-col sm:flex-row items-center justify-between text-xs text-slate-500 gap-2">
          <p>&copy; 2025 Rambax Singh Inter College &amp; Residential Hostel. All Rights Reserved.</p>
          <div class="flex space-x-4">
            <button onclick="openLoginModal('admin')" class="hover:text-brand-gold">Admin Portal</button>
            <button onclick="openLoginModal('staff')" class="hover:text-brand-gold">Staff Portal</button>
            <button onclick="openLoginModal('student')" class="hover:text-brand-gold">Student Portal</button>
          </div>
        </div>
      </div>
    </footer>

  </main>

  <div id="loginModal" class="fixed inset-0 z-50 bg-black/75 backdrop-blur-sm hidden flex items-center justify-center p-4">
    <div class="bg-white rounded-3xl max-w-md w-full overflow-hidden shadow-2xl border-2 border-brand-gold/50">
      
      <div class="navy-gradient p-5 text-white text-center relative">
        <button onclick="closeLoginModal()" class="absolute right-4 top-4 text-slate-300 hover:text-white text-lg">
          <i class="fa-solid fa-xmark"></i>
        </button>
        <div class="w-12 h-12 mx-auto mb-2">
          <svg viewBox="0 0 400 400" class="w-full h-full" xmlns="http://www.w3.org/2000/svg">
            <circle cx="200" cy="200" r="192" fill="#07172c" stroke="#d4af37" stroke-width="8" />
            <text x="200" y="210" font-family="'Cinzel', serif" font-size="95" font-weight="900" fill="#d4af37" text-anchor="middle">RBS</text>
          </svg>
        </div>
        <h3 class="text-lg font-bold font-serif text-white">Campus Portal Authentication</h3>
        <p class="text-xs text-brand-gold">Rambax Singh Inter College &amp; Hostel</p>
      </div>

      <!-- Role Tabs -->
      <div class="grid grid-cols-3 bg-slate-100 p-1.5 border-b border-slate-200 text-xs font-bold">
        <button id="roleTabAdmin" onclick="switchLoginRole('admin')" class="py-2 rounded-xl transition bg-white text-brand-navy shadow-sm">
          <i class="fa-solid fa-shield-halved block text-sm mb-1 text-brand-gold"></i> Admin
        </button>
        <button id="roleTabStaff" onclick="switchLoginRole('staff')" class="py-2 rounded-xl transition text-slate-600 hover:text-brand-navy">
          <i class="fa-solid fa-chalkboard-user block text-sm mb-1"></i> Staff
        </button>
        <button id="roleTabStudent" onclick="switchLoginRole('student')" class="py-2 rounded-xl transition text-slate-600 hover:text-brand-navy">
          <i class="fa-solid fa-user-graduate block text-sm mb-1"></i> Student
        </button>
      </div>

      <!-- Clean Login Form WITHOUT any suggestion buttons or demo fill shortcuts -->
      <form id="portalLoginForm" onsubmit="handlePortalLogin(event)" class="p-6 space-y-4">
        
        <div>
          <label id="loginIdentifierLabel" class="block text-xs font-bold text-slate-700 uppercase tracking-wider mb-1">
            Admin Email Address
          </label>
          <div class="relative">
            <i id="loginIdentifierIcon" class="fa-solid fa-envelope absolute left-3.5 top-3.5 text-slate-400 text-sm"></i>
            <input type="text" id="loginIdentifier" required placeholder="Enter Email / Username" class="w-full pl-10 pr-3.5 py-2.5 rounded-xl border border-slate-300 focus:outline-none focus:ring-2 focus:ring-brand-gold text-sm font-medium">
          </div>
        </div>

        <div>
          <div class="flex items-center justify-between mb-1">
            <label class="block text-xs font-bold text-slate-700 uppercase tracking-wider">
              Password
            </label>
          </div>
          <div class="relative">
            <i class="fa-solid fa-lock absolute left-3.5 top-3.5 text-slate-400 text-sm"></i>
            <input type="password" id="loginPassword" required placeholder="Enter password" class="w-full pl-10 pr-10 py-2.5 rounded-xl border border-slate-300 focus:outline-none focus:ring-2 focus:ring-brand-gold text-sm font-medium">
            <!-- Show/Hide Password Eye Toggle -->
            <button type="button" onclick="togglePasswordVisibility('loginPassword', 'loginPassToggleIcon')" class="absolute right-3.5 top-3 text-slate-400 hover:text-brand-navy focus:outline-none">
              <i id="loginPassToggleIcon" class="fa-regular fa-eye"></i>
            </button>
          </div>
        </div>

        <div id="loginFeedback" class="text-xs text-red-600 font-semibold hidden"></div>

        <button type="submit" class="w-full py-3 gold-gradient text-brand-navy rounded-xl font-black text-xs uppercase tracking-wider shadow-md hover:scale-[1.01] transition transform flex items-center justify-center space-x-2">
          <i class="fa-solid fa-arrow-right-to-bracket"></i>
          <span id="loginSubmitBtnText">Authenticate &amp; Enter</span>
        </button>

        <p class="text-[11px] text-center text-slate-500 pt-2 border-t border-slate-100">
          Strict Access Control: Staff and Students must be granted access by Admin to log in.
        </p>
      </form>
    </div>
  </div>

  <section id="adminDashboardView" class="hidden flex-grow bg-slate-100 min-h-screen">
    
    <header class="bg-brand-navy text-white px-4 sm:px-6 py-3 border-b-2 border-brand-gold flex items-center justify-between">
      <div class="flex items-center space-x-3">
        <div class="w-10 h-10">
          <svg viewBox="0 0 400 400" class="w-full h-full" xmlns="http://www.w3.org/2000/svg">
            <circle cx="200" cy="200" r="192" fill="#07172c" stroke="#d4af37" stroke-width="10" />
            <text x="200" y="215" font-family="'Cinzel', serif" font-size="90" font-weight="900" fill="#d4af37" text-anchor="middle">RBS</text>
          </svg>
        </div>
        <div>
          <h2 class="text-sm sm:text-base font-bold font-serif leading-tight">RBS Admin Control Panel</h2>
          <p class="text-xs text-brand-gold">Manager: Vishnu Kant &bull; Director: Avadhesh Singh &bull; Hostel Warden Unit</p>
        </div>
      </div>

      <div class="flex items-center space-x-3">
        <button onclick="logoutPortal()" class="px-3 py-1.5 bg-red-600 hover:bg-red-700 text-white rounded-lg text-xs font-bold transition flex items-center space-x-1.5">
          <i class="fa-solid fa-power-off"></i>
          <span>Logout</span>
        </button>
      </div>
    </header>

    <!-- Admin Navigation Tabs -->
    <div class="bg-white border-b border-slate-200 shadow-sm sticky top-0 z-20">
      <div class="max-w-7xl mx-auto px-4 flex space-x-2 sm:space-x-4 overflow-x-auto py-2 text-xs sm:text-sm font-bold">
        <button onclick="switchAdminTab('inquiries')" id="adminTabBtnInquiries" class="admin-tab-btn px-4 py-2 rounded-xl bg-brand-navy text-white transition flex items-center space-x-2 flex-shrink-0">
          <i class="fa-solid fa-inbox text-brand-gold"></i>
          <span>Online Inquiries</span>
          <span id="badgeInquiryCount" class="bg-brand-gold text-brand-navy text-[10px] font-black px-1.5 py-0.5 rounded-full">0</span>
        </button>
        <button onclick="switchAdminTab('students')" id="adminTabBtnStudents" class="admin-tab-btn px-4 py-2 rounded-xl text-slate-600 hover:text-brand-navy hover:bg-slate-100 transition flex items-center space-x-2 flex-shrink-0">
          <i class="fa-solid fa-user-graduate"></i>
          <span>Students &amp; Hostellers</span>
        </button>
        <button onclick="switchAdminTab('staff')" id="adminTabBtnStaff" class="admin-tab-btn px-4 py-2 rounded-xl text-slate-600 hover:text-brand-navy hover:bg-slate-100 transition flex items-center space-x-2 flex-shrink-0">
          <i class="fa-solid fa-chalkboard-user"></i>
          <span>Staff Accounts &amp; Passwords</span>
        </button>
        <button onclick="switchAdminTab('marksheets')" id="adminTabBtnMarksheets" class="admin-tab-btn px-4 py-2 rounded-xl text-slate-600 hover:text-brand-navy hover:bg-slate-100 transition flex items-center space-x-2 flex-shrink-0">
          <i class="fa-solid fa-certificate text-brand-gold"></i>
          <span>Professional Marksheet Hub</span>
        </button>
      </div>
    </div>

    <div class="max-w-7xl mx-auto p-4 sm:p-6">
      
      <!-- Inquiries Tab -->
      <div id="adminTabInquiries" class="space-y-4">
        <div class="flex flex-col sm:flex-row justify-between items-start sm:items-center gap-4 bg-white p-4 rounded-2xl border border-slate-200 shadow-sm">
          <div>
            <h3 class="text-lg font-bold font-serif text-brand-navy">Admissions &amp; Hostel Inquiries</h3>
            <p class="text-xs text-slate-500">Live applications received from the public website.</p>
          </div>
          <div class="flex items-center space-x-2 w-full sm:w-auto">
            <input type="text" id="searchInquiryInput" oninput="filterInquiries()" placeholder="Search by name, phone, class..." class="px-3.5 py-2 rounded-xl border border-slate-300 text-xs w-full sm:w-64 focus:outline-none focus:ring-2 focus:ring-brand-gold">
          </div>
        </div>

        <div class="bg-white rounded-2xl border border-slate-200 shadow-sm overflow-hidden">
          <div class="overflow-x-auto">
            <table class="w-full text-left text-xs sm:text-sm">
              <thead class="bg-slate-50 text-slate-600 uppercase text-[11px] border-b">
                <tr>
                  <th class="py-3 px-3">Date</th>
                  <th class="py-3 px-3">Student Name</th>
                  <th class="py-3 px-3">Father Name</th>
                  <th class="py-3 px-3">Class</th>
                  <th class="py-3 px-3">Hostel Option</th>
                  <th class="py-3 px-3">Phone</th>
                  <th class="py-3 px-3">Status</th>
                  <th class="py-3 px-3 text-right">Actions</th>
                </tr>
              </thead>
              <tbody id="inquiriesTableBody" class="divide-y divide-slate-100 font-medium"></tbody>
            </table>
          </div>
        </div>
      </div>

      <!-- Students Tab with Password Reset and Hostel Tag -->
      <div id="adminTabStudents" class="hidden space-y-4">
        <div class="flex flex-col sm:flex-row justify-between items-start sm:items-center gap-4 bg-white p-4 rounded-2xl border border-slate-200 shadow-sm">
          <div>
            <h3 class="text-lg font-bold font-serif text-brand-navy">Students &amp; Hostellers Master Terminal</h3>
            <p class="text-xs text-slate-500">Manage credentials, change passwords, and toggle Day Scholar / Hosteller status.</p>
          </div>
          <button onclick="openAddStudentModal()" class="px-4 py-2 gold-gradient text-brand-navy rounded-xl font-bold text-xs shadow hover:scale-105 transition flex items-center space-x-1.5">
            <i class="fa-solid fa-user-plus"></i>
            <span>Register New Student</span>
          </button>
        </div>

        <div class="bg-white rounded-2xl border border-slate-200 shadow-sm overflow-hidden">
          <div class="overflow-x-auto">
            <table class="w-full text-left text-xs sm:text-sm">
              <thead class="bg-slate-50 text-slate-600 uppercase text-[11px] border-b">
                <tr>
                  <th class="py-3 px-3">Roll No</th>
                  <th class="py-3 px-3">Student Name</th>
                  <th class="py-3 px-3">Class</th>
                  <th class="py-3 px-3">Hostel Status</th>
                  <th class="py-3 px-3">Password</th>
                  <th class="py-3 px-3">Login Access</th>
                  <th class="py-3 px-3 text-right">Actions</th>
                </tr>
              </thead>
              <tbody id="studentsTableBody" class="divide-y divide-slate-100 font-medium"></tbody>
            </table>
          </div>
        </div>
      </div>

      <!-- Staff Tab with Password Reset Functionality -->
      <div id="adminTabStaff" class="hidden space-y-4">
        <div class="flex flex-col sm:flex-row justify-between items-start sm:items-center gap-4 bg-white p-4 rounded-2xl border border-slate-200 shadow-sm">
          <div>
            <h3 class="text-lg font-bold font-serif text-brand-navy">Staff &amp; Faculty Accounts Management</h3>
            <p class="text-xs text-slate-500">Add instructors, grant terminal permissions, and update teacher passwords.</p>
          </div>
          <button onclick="openAddStaffModal()" class="px-4 py-2 bg-brand-navy text-brand-gold rounded-xl font-bold text-xs shadow hover:bg-brand-lightnavy transition flex items-center space-x-1.5">
            <i class="fa-solid fa-chalkboard-user"></i>
            <span>Add New Staff</span>
          </button>
        </div>

        <div class="bg-white rounded-2xl border border-slate-200 shadow-sm overflow-hidden">
          <div class="overflow-x-auto">
            <table class="w-full text-left text-xs sm:text-sm">
              <thead class="bg-slate-50 text-slate-600 uppercase text-[11px] border-b">
                <tr>
                  <th class="py-3 px-3">Staff Name</th>
                  <th class="py-3 px-3">Role / Subject</th>
                  <th class="py-3 px-3">Email (Login ID)</th>
                  <th class="py-3 px-3">Current Password</th>
                  <th class="py-3 px-3">Access Status</th>
                  <th class="py-3 px-3 text-right">Actions</th>
                </tr>
              </thead>
              <tbody id="staffTableBody" class="divide-y divide-slate-100 font-medium"></tbody>
            </table>
          </div>
        </div>
      </div>

      <!-- Marksheet Tab -->
      <div id="adminTabMarksheets" class="hidden space-y-4">
        <div class="flex flex-col sm:flex-row justify-between items-start sm:items-center gap-4 bg-white p-4 rounded-2xl border border-slate-200 shadow-sm">
          <div>
            <h3 class="text-lg font-bold font-serif text-brand-navy">State Board Official Marksheets Registry</h3>
            <p class="text-xs text-slate-500">Generate high-grade official marksheets with Theory &amp; Practical breakdowns.</p>
          </div>
          <button onclick="openCreateMarksheetModal()" class="px-4 py-2 gold-gradient text-brand-navy rounded-xl font-black text-xs shadow hover:scale-105 transition flex items-center space-x-1.5">
            <i class="fa-solid fa-file-circle-plus"></i>
            <span>Generate Official Marksheet</span>
          </button>
        </div>

        <div class="bg-white rounded-2xl border border-slate-200 shadow-sm overflow-hidden">
          <div class="overflow-x-auto">
            <table class="w-full text-left text-xs sm:text-sm">
              <thead class="bg-slate-50 text-slate-600 uppercase text-[11px] border-b">
                <tr>
                  <th class="py-3 px-3">Roll No</th>
                  <th class="py-3 px-3">Candidate Name</th>
                  <th class="py-3 px-3">Class &amp; Stream</th>
                  <th class="py-3 px-3">Hosteller?</th>
                  <th class="py-3 px-3">Exam Type</th>
                  <th class="py-3 px-3">Total Marks</th>
                  <th class="py-3 px-3">Result / Division</th>
                  <th class="py-3 px-3 text-right">Actions</th>
                </tr>
              </thead>
              <tbody id="marksheetsTableBody" class="divide-y divide-slate-100 font-medium"></tbody>
            </table>
          </div>
        </div>
      </div>

    </div>
  </section>

  <section id="staffDashboardView" class="hidden flex-grow bg-slate-100 min-h-screen">
    <header class="bg-brand-lightnavy text-white px-4 sm:px-6 py-3 border-b-2 border-brand-gold flex items-center justify-between">
      <div class="flex items-center space-x-3">
        <div class="w-10 h-10 bg-brand-gold rounded-xl flex items-center justify-center text-brand-navy font-bold text-lg">
          <i class="fa-solid fa-chalkboard-user"></i>
        </div>
        <div>
          <h2 class="text-sm sm:text-base font-bold font-serif leading-tight" id="staffGreetingName">Staff Faculty Dashboard</h2>
          <p class="text-xs text-brand-gold">RBS Inter College &amp; Residential Hostel &bull; Academic Staff Desk</p>
        </div>
      </div>
      <button onclick="logoutPortal()" class="px-3 py-1.5 bg-red-600 hover:bg-red-700 text-white rounded-lg text-xs font-bold transition">
        Logout
      </button>
    </header>

    <div class="max-w-7xl mx-auto p-4 sm:p-6 space-y-4">
      <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
        <div class="bg-white p-4 rounded-2xl border border-slate-200 shadow-sm flex items-center space-x-3">
          <div class="w-10 h-10 rounded-xl bg-blue-100 text-blue-700 flex items-center justify-center text-lg">
            <i class="fa-solid fa-users"></i>
          </div>
          <div>
            <p class="text-xs text-slate-500 font-bold uppercase">Total Students</p>
            <p class="text-xl font-black text-brand-navy" id="staffTotalStudentsCount">0</p>
          </div>
        </div>
        <div class="bg-white p-4 rounded-2xl border border-slate-200 shadow-sm flex items-center space-x-3">
          <div class="w-10 h-10 rounded-xl bg-amber-100 text-amber-700 flex items-center justify-center text-lg">
            <i class="fa-solid fa-bed"></i>
          </div>
          <div>
            <p class="text-xs text-slate-500 font-bold uppercase">Hostel Boarders</p>
            <p class="text-xl font-black text-brand-navy" id="staffHostellerCount">0</p>
          </div>
        </div>
        <div class="bg-white p-4 rounded-2xl border border-slate-200 shadow-sm flex items-center justify-between">
          <div>
            <p class="text-xs text-slate-500 font-bold uppercase">Official Marksheet</p>
            <p class="text-xs text-slate-600">Draft or finalize student scores</p>
          </div>
          <button onclick="openCreateMarksheetModal()" class="px-3 py-2 gold-gradient text-brand-navy font-black rounded-xl text-xs shadow">
            + Generate
          </button>
        </div>
      </div>

      <div class="bg-white rounded-2xl border border-slate-200 shadow-sm p-4">
        <div class="flex justify-between items-center mb-3">
          <h3 class="text-base font-bold font-serif text-brand-navy">Assigned Students &amp; Hostel Boarders</h3>
          <span class="text-xs text-slate-500">Roll Registry</span>
        </div>
        <div class="overflow-x-auto">
          <table class="w-full text-left text-xs sm:text-sm">
            <thead class="bg-slate-50 text-slate-600 uppercase text-[11px] border-b">
              <tr>
                <th class="py-2.5 px-3">Roll No</th>
                <th class="py-2.5 px-3">Student Name</th>
                <th class="py-2.5 px-3">Class</th>
                <th class="py-2.5 px-3">Hosteller / Day Scholar</th>
                <th class="py-2.5 px-3">Guardian Contact</th>
                <th class="py-2.5 px-3 text-right">Marksheet Status</th>
              </tr>
            </thead>
            <tbody id="staffStudentsTableBody" class="divide-y divide-slate-100 font-medium"></tbody>
          </table>
        </div>
      </div>
    </div>
  </section>

  <section id="studentDashboardView" class="hidden flex-grow bg-slate-100 min-h-screen">
    <header class="bg-brand-navy text-white px-4 sm:px-6 py-3 border-b-2 border-brand-gold flex items-center justify-between">
      <div class="flex items-center space-x-3">
        <div class="w-10 h-10 bg-brand-gold rounded-full flex items-center justify-center text-brand-navy font-black text-lg">
          <i class="fa-solid fa-graduation-cap"></i>
        </div>
        <div>
          <h2 class="text-sm sm:text-base font-bold font-serif leading-tight">Student Academic &amp; Hostel Portal</h2>
          <p class="text-xs text-brand-gold">Rambax Singh Inter College &amp; Residential Hostel</p>
        </div>
      </div>
      <button onclick="logoutPortal()" class="px-3 py-1.5 bg-red-600 hover:bg-red-700 text-white rounded-lg text-xs font-bold transition">
        Logout
      </button>
    </header>

    <div class="max-w-5xl mx-auto p-4 sm:p-6 space-y-6">
      
      <!-- Student Profile Card Banner -->
      <div class="bg-white rounded-3xl border border-slate-200 p-6 shadow-sm flex flex-col md:flex-row items-center justify-between gap-6">
        <div class="flex items-center space-x-4">
          <div class="w-20 h-20 rounded-2xl bg-brand-navy text-brand-gold border-2 border-brand-gold flex items-center justify-center text-3xl font-serif font-black flex-shrink-0">
            <span id="studentAvatarInitials">ST</span>
          </div>
          <div>
            <div class="flex items-center space-x-2">
              <h3 class="text-2xl font-bold font-serif text-brand-navy" id="studentProfileName">Student Name</h3>
              <span id="studentHostelBadge" class="bg-amber-100 text-amber-800 text-[10px] font-black px-2 py-0.5 rounded-full uppercase">
                Hostel Resident
              </span>
            </div>
            <p class="text-sm font-semibold text-slate-600 mt-0.5">
              Roll No: <span id="studentProfileRoll" class="text-brand-navy font-bold">--</span> &bull; 
              Class: <span id="studentProfileClass" class="text-brand-gold font-bold">--</span>
            </p>
            <p class="text-xs text-slate-500 mt-1">
              <i class="fa-solid fa-location-dot text-brand-gold mr-1"></i> Bithara, Aliganj, Etah (U.P.)
            </p>
          </div>
        </div>

        <button onclick="downloadStudentMarksheet()" id="downloadMarksheetBtn" class="px-5 py-2.5 gold-gradient text-brand-navy rounded-xl font-black text-xs shadow hover:scale-105 transition flex items-center space-x-2">
          <i class="fa-solid fa-print"></i>
          <span>Print Official Marksheet</span>
        </button>
      </div>

      <!-- Marksheet Container -->
      <div id="studentMarksheetContainer" class="bg-white rounded-3xl border border-slate-200 p-6 shadow-sm"></div>

    </div>
  </section>

  <div id="passwordResetModal" class="fixed inset-0 z-50 bg-black/75 backdrop-blur-sm hidden flex items-center justify-center p-4">
    <div class="bg-white rounded-3xl max-w-sm w-full overflow-hidden shadow-2xl border-2 border-brand-gold/50">
      <div class="navy-gradient p-4 text-white flex justify-between items-center">
        <div>
          <h3 class="text-sm font-bold font-serif">Change Login Password</h3>
          <p class="text-[11px] text-brand-gold" id="pwdResetTargetName">Updating Credentials</p>
        </div>
        <button onclick="closePasswordResetModal()" class="text-slate-300 hover:text-white"><i class="fa-solid fa-xmark"></i></button>
      </div>
      <form id="pwdResetForm" onsubmit="handleConfirmPasswordReset(event)" class="p-5 space-y-3 text-xs">
        <input type="hidden" id="pwdResetType" value="">
        <input type="hidden" id="pwdResetId" value="">
        <div>
          <label class="block font-bold text-slate-700 uppercase mb-1">Set New Password *</label>
          <div class="relative">
            <input type="password" id="newResetPasswordVal" required minlength="4" placeholder="Enter new strong password" class="w-full pl-3 pr-9 py-2 border rounded-xl font-medium focus:ring-2 focus:ring-brand-gold">
            <button type="button" onclick="togglePasswordVisibility('newResetPasswordVal', 'resetPassIcon')" class="absolute right-3 top-2.5 text-slate-400">
              <i id="resetPassIcon" class="fa-regular fa-eye"></i>
            </button>
          </div>
        </div>
        <div class="pt-2 flex justify-end space-x-2">
          <button type="button" onclick="closePasswordResetModal()" class="px-3.5 py-1.5 border rounded-xl font-semibold">Cancel</button>
          <button type="submit" class="px-4 py-1.5 gold-gradient text-brand-navy font-black rounded-xl shadow">Update Password</button>
        </div>
      </form>
    </div>
  </div>

  <div id="addStudentModal" class="fixed inset-0 z-50 bg-black/75 backdrop-blur-sm hidden flex items-center justify-center p-4">
    <div class="bg-white rounded-3xl max-w-md w-full overflow-hidden shadow-2xl border-2 border-brand-gold/50">
      <div class="navy-gradient p-4 text-white flex justify-between items-center">
        <h3 class="text-sm font-bold font-serif">Register Student / Hosteller</h3>
        <button onclick="closeAddStudentModal()" class="text-slate-300 hover:text-white"><i class="fa-solid fa-xmark"></i></button>
      </div>
      <form id="addStudentForm" onsubmit="handleSaveNewStudent(event)" class="p-5 space-y-3 text-xs">
        <div>
          <label class="block font-bold text-slate-700 uppercase mb-1">Full Name *</label>
          <input type="text" id="newStdName" required placeholder="e.g. Rahul Sharma" class="w-full px-3 py-2 border rounded-xl font-medium">
        </div>
        <div class="grid grid-cols-2 gap-3">
          <div>
            <label class="block font-bold text-slate-700 uppercase mb-1">Roll / Student ID *</label>
            <input type="text" id="newStdRoll" required placeholder="RBS-2025-01" class="w-full px-3 py-2 border rounded-xl font-medium">
          </div>
          <div>
            <label class="block font-bold text-slate-700 uppercase mb-1">Class *</label>
            <select id="newStdClass" required class="w-full px-3 py-2 border rounded-xl font-medium bg-white">
              <option value="Class 10th">Class 10th (High School)</option>
              <option value="Class 12th Science">Class 12th (Science)</option>
              <option value="Class 12th Arts">Class 12th (Arts)</option>
              <option value="Class 9th">Class 9th</option>
              <option value="Class 11th Science">Class 11th (Science)</option>
              <option value="Class 11th Arts">Class 11th (Arts)</option>
            </select>
          </div>
        </div>
        <div class="grid grid-cols-2 gap-3">
          <div>
            <label class="block font-bold text-slate-700 uppercase mb-1">Hostel Status *</label>
            <select id="newStdHostel" required class="w-full px-3 py-2 border rounded-xl font-medium bg-white">
              <option value="Hosteller">Hosteller (Resident)</option>
              <option value="Day Scholar">Day Scholar</option>
            </select>
          </div>
          <div>
            <label class="block font-bold text-slate-700 uppercase mb-1">Guardian Mobile</label>
            <input type="tel" id="newStdPhone" placeholder="Mobile" class="w-full px-3 py-2 border rounded-xl font-medium">
          </div>
        </div>
        <div>
          <label class="block font-bold text-slate-700 uppercase mb-1">Father's Name</label>
          <input type="text" id="newStdFather" placeholder="Father name" class="w-full px-3 py-2 border rounded-xl font-medium">
        </div>
        <div>
          <label class="block font-bold text-slate-700 uppercase mb-1">Portal Password *</label>
          <div class="relative">
            <input type="password" id="newStdPass" required placeholder="Create student password" class="w-full pl-3 pr-9 py-2 border rounded-xl font-medium">
            <button type="button" onclick="togglePasswordVisibility('newStdPass', 'newStdPassIcon')" class="absolute right-3 top-2.5 text-slate-400">
              <i id="newStdPassIcon" class="fa-regular fa-eye"></i>
            </button>
          </div>
        </div>
        <div>
          <label class="block font-bold text-slate-700 uppercase mb-1">Portal Access</label>
          <select id="newStdStatus" class="w-full px-3 py-2 border rounded-xl font-medium bg-white">
            <option value="Active">Active (Permitted Login)</option>
            <option value="Disabled">Disabled</option>
          </select>
        </div>
        <div class="pt-2 flex justify-end space-x-2">
          <button type="button" onclick="closeAddStudentModal()" class="px-3.5 py-1.5 border rounded-xl">Cancel</button>
          <button type="submit" class="px-4 py-1.5 gold-gradient text-brand-navy font-bold rounded-xl shadow">Save Student</button>
        </div>
      </form>
    </div>
  </div>

  <div id="addStaffModal" class="fixed inset-0 z-50 bg-black/75 backdrop-blur-sm hidden flex items-center justify-center p-4">
    <div class="bg-white rounded-3xl max-w-md w-full overflow-hidden shadow-2xl border-2 border-brand-gold/50">
      <div class="navy-gradient p-4 text-white flex justify-between items-center">
        <h3 class="text-sm font-bold font-serif">Add Staff Member &amp; Terminal Login</h3>
        <button onclick="closeAddStaffModal()" class="text-slate-300 hover:text-white"><i class="fa-solid fa-xmark"></i></button>
      </div>
      <form id="addStaffForm" onsubmit="handleSaveNewStaff(event)" class="p-5 space-y-3 text-xs">
        <div>
          <label class="block font-bold text-slate-700 uppercase mb-1">Teacher / Staff Full Name *</label>
          <input type="text" id="newStaffName" required placeholder="e.g. Ramesh Chandra" class="w-full px-3 py-2 border rounded-xl font-medium">
        </div>
        <div>
          <label class="block font-bold text-slate-700 uppercase mb-1">Designation &amp; Subject *</label>
          <input type="text" id="newStaffRole" required placeholder="e.g. Senior Lecturer - Physics / Hostel Warden" class="w-full px-3 py-2 border rounded-xl font-medium">
        </div>
        <div>
          <label class="block font-bold text-slate-700 uppercase mb-1">Staff Login Email *</label>
          <input type="email" id="newStaffEmail" required placeholder="staff.ramesh@rbs.edu" class="w-full px-3 py-2 border rounded-xl font-medium">
        </div>
        <div>
          <label class="block font-bold text-slate-700 uppercase mb-1">Staff Password *</label>
          <div class="relative">
            <input type="password" id="newStaffPass" required placeholder="Create password" class="w-full pl-3 pr-9 py-2 border rounded-xl font-medium">
            <button type="button" onclick="togglePasswordVisibility('newStaffPass', 'newStaffPassIcon')" class="absolute right-3 top-2.5 text-slate-400">
              <i id="newStaffPassIcon" class="fa-regular fa-eye"></i>
            </button>
          </div>
        </div>
        <div>
          <label class="block font-bold text-slate-700 uppercase mb-1">Account Permission</label>
          <select id="newStaffStatus" class="w-full px-3 py-2 border rounded-xl font-medium bg-white">
            <option value="Active">Active (Permitted Login)</option>
            <option value="Suspended">Suspended</option>
          </select>
        </div>
        <div class="pt-2 flex justify-end space-x-2">
          <button type="button" onclick="closeAddStaffModal()" class="px-3.5 py-1.5 border rounded-xl">Cancel</button>
          <button type="submit" class="px-4 py-1.5 bg-brand-navy text-brand-gold font-bold rounded-xl shadow">Create Account</button>
        </div>
      </form>
    </div>
  </div>

  <div id="marksheetModal" class="fixed inset-0 z-50 bg-black/75 backdrop-blur-sm hidden flex items-center justify-center p-4 overflow-y-auto">
    <div class="bg-white rounded-3xl max-w-2xl w-full my-6 overflow-hidden shadow-2xl border-2 border-brand-gold/50">
      
      <div class="navy-gradient p-4 text-white flex justify-between items-center">
        <div>
          <h3 class="text-base font-bold font-serif">State-Board Official Marksheet Generator</h3>
          <p class="text-xs text-brand-gold">RBS Inter College Examination &amp; Evaluation Branch</p>
        </div>
        <button onclick="closeMarksheetModal()" class="text-slate-300 hover:text-white text-lg">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>

      <form id="marksheetForm" onsubmit="handleSaveMarksheet(event)" class="p-5 space-y-3.5 text-xs">
        
        <div class="grid grid-cols-1 sm:grid-cols-3 gap-3">
          <div class="sm:col-span-2">
            <label class="block font-bold text-slate-700 uppercase mb-1">Select Registered Student *</label>
            <select id="mkStudentSelect" onchange="autoFillMarksheetStudentDetails()" required class="w-full px-3 py-2 border rounded-xl font-medium bg-white focus:ring-2 focus:ring-brand-gold">
              <option value="">-- Choose Registered Student --</option>
            </select>
          </div>
          <div>
            <label class="block font-bold text-slate-700 uppercase mb-1">Academic Session</label>
            <input type="text" id="mkSession" value="2024-2025" required class="w-full px-3 py-2 border rounded-xl font-medium">
          </div>
        </div>

        <div class="grid grid-cols-3 gap-3">
          <div>
            <label class="block font-bold text-slate-700 uppercase mb-1">Roll Number</label>
            <input type="text" id="mkRollNo" readonly class="w-full px-3 py-2 bg-slate-100 border rounded-xl font-bold">
          </div>
          <div>
            <label class="block font-bold text-slate-700 uppercase mb-1">Class / Section</label>
            <input type="text" id="mkClass" readonly class="w-full px-3 py-2 bg-slate-100 border rounded-xl font-bold">
          </div>
          <div>
            <label class="block font-bold text-slate-700 uppercase mb-1">Examination Term</label>
            <select id="mkExamType" class="w-full px-3 py-2 border rounded-xl font-medium bg-white">
              <option value="ANNUAL BOARD EVALUATION">Annual Board Examination</option>
              <option value="PRE-BOARD EXAMINATION">Pre-Board Examination</option>
              <option value="HALF YEARLY EVALUATION">Half Yearly Examination</option>
            </select>
          </div>
        </div>

        <!-- Subject Rows: Theory + Practical -->
        <div class="border border-slate-300 rounded-xl p-3 bg-slate-50 space-y-2">
          <div class="grid grid-cols-12 gap-2 font-bold text-slate-600 uppercase text-[10px] pb-1 border-b">
            <div class="col-span-4">Subject</div>
            <div class="col-span-4 text-center">Theory (Max 70 / 100)</div>
            <div class="col-span-4 text-center">Practical (Max 30)</div>
          </div>

          <div class="grid grid-cols-12 gap-2 items-center">
            <div class="col-span-4 font-bold text-brand-navy">General Hindi</div>
            <div class="col-span-4"><input type="number" id="th_hindi" min="0" max="100" value="88" oninput="calculateAdvancedMarks()" class="w-full px-2 py-1 border rounded text-center"></div>
            <div class="col-span-4"><input type="number" id="pr_hindi" min="0" max="0" value="0" readonly class="w-full px-2 py-1 bg-slate-200 border rounded text-center text-slate-400"></div>
          </div>

          <div class="grid grid-cols-12 gap-2 items-center">
            <div class="col-span-4 font-bold text-brand-navy">General English</div>
            <div class="col-span-4"><input type="number" id="th_english" min="0" max="100" value="82" oninput="calculateAdvancedMarks()" class="w-full px-2 py-1 border rounded text-center"></div>
            <div class="col-span-4"><input type="number" id="pr_english" min="0" max="0" value="0" readonly class="w-full px-2 py-1 bg-slate-200 border rounded text-center text-slate-400"></div>
          </div>

          <div class="grid grid-cols-12 gap-2 items-center">
            <div class="col-span-4 font-bold text-brand-navy">Physics / Science</div>
            <div class="col-span-4"><input type="number" id="th_physics" min="0" max="70" value="62" oninput="calculateAdvancedMarks()" class="w-full px-2 py-1 border rounded text-center"></div>
            <div class="col-span-4"><input type="number" id="pr_physics" min="0" max="30" value="28" oninput="calculateAdvancedMarks()" class="w-full px-2 py-1 border rounded text-center"></div>
          </div>

          <div class="grid grid-cols-12 gap-2 items-center">
            <div class="col-span-4 font-bold text-brand-navy">Chemistry / Social Sci</div>
            <div class="col-span-4"><input type="number" id="th_chem" min="0" max="70" value="58" oninput="calculateAdvancedMarks()" class="w-full px-2 py-1 border rounded text-center"></div>
            <div class="col-span-4"><input type="number" id="pr_chem" min="0" max="30" value="29" oninput="calculateAdvancedMarks()" class="w-full px-2 py-1 border rounded text-center"></div>
          </div>

          <div class="grid grid-cols-12 gap-2 items-center">
            <div class="col-span-4 font-bold text-brand-navy">Mathematics / Biology</div>
            <div class="col-span-4"><input type="number" id="th_math" min="0" max="100" value="92" oninput="calculateAdvancedMarks()" class="w-full px-2 py-1 border rounded text-center"></div>
            <div class="col-span-4"><input type="number" id="pr_math" min="0" max="0" value="0" readonly class="w-full px-2 py-1 bg-slate-200 border rounded text-center text-slate-400"></div>
          </div>
        </div>

        <!-- Calculated Summary Strip -->
        <div class="bg-brand-goldlight p-3 rounded-xl border border-brand-gold flex justify-between items-center text-xs">
          <div>
            <p class="text-slate-600 font-medium">Total Obtained:</p>
            <p class="text-base font-black text-brand-navy"><span id="advTotalObtained">439</span> / 500</p>
          </div>
          <div>
            <p class="text-slate-600 font-medium">Percentage:</p>
            <p class="text-base font-black text-brand-navy"><span id="advPercentage">87.80</span>%</p>
          </div>
          <div>
            <p class="text-slate-600 font-medium">Result &amp; Division:</p>
            <p class="text-sm font-black text-emerald-700" id="advDivision">1st Div with Honors</p>
          </div>
        </div>

        <div class="flex justify-end space-x-2 pt-1">
          <button type="button" onclick="closeMarksheetModal()" class="px-4 py-2 border rounded-xl font-semibold">Cancel</button>
          <button type="submit" class="px-5 py-2 gold-gradient text-brand-navy font-black rounded-xl shadow">Save &amp; Generate Transcript</button>
        </div>
      </form>
    </div>
  </div>

  <div id="marksheetPreviewModal" class="fixed inset-0 z-50 bg-black/80 backdrop-blur-sm hidden flex items-center justify-center p-2 sm:p-4 overflow-y-auto">
    <div class="bg-white rounded-2xl max-w-4xl w-full my-6 p-4 sm:p-6 shadow-2xl relative border-4 border-brand-navy">
      
      <!-- Top Action Bar (hidden on print) -->
      <div class="no-print flex justify-between items-center mb-3 pb-2 border-b border-slate-200">
        <span class="text-xs font-bold uppercase text-brand-navy flex items-center">
          <i class="fa-solid fa-stamp text-brand-gold mr-1.5"></i> UP Board Standard High School &amp; Intermediate Marksheet
        </span>
        <div class="flex items-center space-x-2">
          <button onclick="window.print()" class="px-4 py-2 bg-brand-navy text-brand-gold rounded-lg font-bold text-xs flex items-center space-x-1.5 shadow">
            <i class="fa-solid fa-print"></i>
            <span>Print Official Marksheet</span>
          </button>
          <button onclick="closeMarksheetPreviewModal()" class="p-2 text-slate-400 hover:text-slate-700 text-lg">
            <i class="fa-solid fa-xmark"></i>
          </button>
        </div>
      </div>

      <!-- Printable Marksheet Body -->
      <div id="printableMarksheet" class="p-5 sm:p-8 bg-[#fffefb] border-4 border-brand-navy relative text-brand-navy shadow-inner">
        
        <!-- Watermark Background -->
        <div class="absolute inset-0 flex items-center justify-center opacity-[0.04] pointer-events-none">
          <svg viewBox="0 0 400 400" class="w-96 h-96" xmlns="http://www.w3.org/2000/svg">
            <circle cx="200" cy="200" r="190" fill="#07172c" />
          </svg>
        </div>

        <!-- Academic Header -->
        <div class="text-center border-b-2 border-brand-navy pb-3 relative z-10">
          <div class="flex items-center justify-between mb-1">
            <!-- Left Barcode -->
            <div class="text-left font-mono text-[9px] text-slate-600 hidden sm:block">
              <span class="font-barcode text-2xl leading-none">RBS-2025-UPBOARD</span><br>
              SERIAL NO: <strong id="pvSerialNo">RBS/2025/8921</strong>
            </div>

            <!-- College Emblem -->
            <div class="w-16 h-16 mx-auto">
              <svg viewBox="0 0 400 400" class="w-full h-full" xmlns="http://www.w3.org/2000/svg">
                <circle cx="200" cy="200" r="192" fill="#07172c" stroke="#d4af37" stroke-width="8" />
                <text x="200" y="80" font-family="'Cinzel', serif" font-size="28" font-weight="900" fill="#d4af37" text-anchor="middle">RBS INTER COLLEGE</text>
                <text x="200" y="340" font-family="'Cinzel', serif" font-size="24" font-weight="800" fill="#d4af37" text-anchor="middle">BITHARA ALIGANJ ETAH</text>
                <text x="200" y="200" font-family="'Cinzel', serif" font-size="82" font-weight="900" fill="#d4af37" text-anchor="middle">RBS</text>
              </svg>
            </div>

            <!-- Right Affiliation Code -->
            <div class="text-right text-[10px] text-slate-600 hidden sm:block">
              U-DISE CODE: <strong>09190104802</strong><br>
              COLLEGE CODE: <strong>ETAH-2072</strong>
            </div>
          </div>

          <h2 class="text-2xl sm:text-3xl font-black font-serif tracking-wide text-brand-navy uppercase leading-tight">
            RAMBAX SINGH INTER COLLEGE
          </h2>
          <p class="text-xs font-bold text-amber-900 tracking-wider">
            &amp; RESIDENTIAL HOSTEL CAMPUS &bull; BITHARA, ALIGANJ, ETAH (U.P.) - 207247
          </p>
          <p class="text-[10px] text-slate-600 mt-0.5">
            Recognised by the Board of High School &amp; Intermediate Education, Uttar Pradesh
          </p>

          <div class="mt-2 inline-block bg-brand-navy text-brand-gold px-5 py-1 rounded text-xs font-black uppercase tracking-widest border border-brand-gold">
            STATEMENT OF MARKS &bull; <span id="pvExamHeader">ANNUAL BOARD EVALUATION</span> (SESSION: <span id="pvSession">2024-2025</span>)
          </div>
        </div>

        <!-- Candidate Information Grid -->
        <div class="grid grid-cols-2 sm:grid-cols-4 gap-2 py-3 text-xs border-b border-slate-400 relative z-10">
          <div>
            <p class="text-[10px] text-slate-500 uppercase font-bold">Candidate Name</p>
            <p class="font-black text-brand-navy uppercase text-sm" id="pvStudentName">--</p>
          </div>
          <div>
            <p class="text-[10px] text-slate-500 uppercase font-bold">Roll Number</p>
            <p class="font-mono font-black text-brand-navy text-sm" id="pvRollNo">--</p>
          </div>
          <div>
            <p class="text-[10px] text-slate-500 uppercase font-bold">Father's Name</p>
            <p class="font-bold text-slate-800 uppercase" id="pvFatherName">--</p>
          </div>
          <div>
            <p class="text-[10px] text-slate-500 uppercase font-bold">Hostel / Day Scholar</p>
            <p class="font-bold text-amber-800 uppercase" id="pvHostelStatus">Hosteller</p>
          </div>
          <div>
            <p class="text-[10px] text-slate-500 uppercase font-bold">Class &amp; Stream</p>
            <p class="font-bold text-brand-navy" id="pvClass">--</p>
          </div>
          <div>
            <p class="text-[10px] text-slate-500 uppercase font-bold">Registration / SR No</p>
            <p class="font-bold font-mono text-slate-700" id="pvSrNo">RBS-REG-9421</p>
          </div>
          <div>
            <p class="text-[10px] text-slate-500 uppercase font-bold">Date of Birth</p>
            <p class="font-bold text-slate-700" id="pvDob">15/07/2008</p>
          </div>
          <div>
            <p class="text-[10px] text-slate-500 uppercase font-bold">Enrollment Status</p>
            <p class="font-bold text-emerald-700">REGULAR / VERIFIED</p>
          </div>
        </div>

        <!-- Academic Subjects Table -->
        <div class="py-3 relative z-10">
          <table class="w-full text-xs table-academic border-collapse border border-brand-navy text-left">
            <thead class="bg-brand-navy text-white uppercase text-[10px] tracking-wider text-center">
              <tr>
                <th rowspan="2" class="p-1 border border-brand-navy w-10">S.N.</th>
                <th rowspan="2" class="p-1 border border-brand-navy text-left">Subject Description</th>
                <th colspan="3" class="p-1 border border-brand-navy">Marks Scheme</th>
                <th colspan="3" class="p-1 border border-brand-navy">Marks Obtained</th>
                <th rowspan="2" class="p-1 border border-brand-navy w-16">Grade</th>
              </tr>
              <tr>
                <th class="p-1 border border-brand-navy text-[9px]">Max Th</th>
                <th class="p-1 border border-brand-navy text-[9px]">Max Pr</th>
                <th class="p-1 border border-brand-navy text-[9px]">Total</th>
                <th class="p-1 border border-brand-navy text-[9px]">Theory</th>
                <th class="p-1 border border-brand-navy text-[9px]">Practical</th>
                <th class="p-1 border border-brand-navy text-[9px] font-bold">Obt Total</th>
              </tr>
            </thead>
            <tbody id="pvMarksTableBody" class="font-medium divide-y divide-slate-300"></tbody>
            <tfoot class="bg-slate-100 font-bold border-t-2 border-brand-navy">
              <tr>
                <td colspan="4" class="p-1.5 border border-brand-navy text-right uppercase text-[11px]">Grand Total:</td>
                <td class="p-1.5 border border-brand-navy text-center" id="pvMaxTotal">500</td>
                <td colspan="2" class="p-1.5 border border-brand-navy text-right uppercase text-[10px]">Obtained:</td>
                <td class="p-1.5 border border-brand-navy text-center text-sm font-black text-brand-navy" id="pvObtainedTotal">--</td>
                <td class="p-1.5 border border-brand-navy text-center font-black" id="pvFinalGrade">--</td>
              </tr>
            </tfoot>
          </table>
        </div>

        <!-- Result Box -->
        <div class="grid grid-cols-3 gap-2 py-2.5 bg-brand-goldlight border border-brand-gold text-xs font-bold text-center rounded relative z-10 mb-6">
          <div>PERCENTAGE: <span id="pvPercentage" class="text-brand-navy text-sm font-black">--%</span></div>
          <div>RESULT: <span id="pvResultStatus" class="text-emerald-800 text-sm font-black">PASSED</span></div>
          <div>DIVISION: <span id="pvDivision" class="text-brand-navy text-sm font-black">1st Division</span></div>
        </div>

        <!-- Signatures & Authority -->
        <div class="pt-6 flex justify-between items-end relative z-10 text-center text-xs">
          <div>
            <div class="w-28 border-b border-dashed border-slate-700 mb-1 mx-auto"></div>
            <p class="font-bold text-slate-800">Class Incharge</p>
            <p class="text-[9px] text-slate-500">Evaluation Officer</p>
          </div>
          <div>
            <!-- College Stamp Graphic -->
            <div class="w-24 h-24 mx-auto mb-1 rounded-full border-2 border-dashed border-brand-gold flex flex-col items-center justify-center text-[8px] text-brand-gold font-bold rotate-[-6deg] bg-amber-50/50">
              <span>* OFFICIAL SEAL *</span>
              <strong class="text-[9px] text-brand-navy">RBS INTER COLLEGE</strong>
              <span>BITHARA (ETAH)</span>
            </div>
            <p class="font-black text-brand-navy">Vishnu Kant</p>
            <p class="text-[10px] text-slate-600 font-semibold">Manager (6395052394)</p>
          </div>
          <div>
            <div class="w-28 border-b border-dashed border-slate-700 mb-1 mx-auto"></div>
            <p class="font-black text-brand-navy">Avadhesh Singh</p>
            <p class="text-[10px] text-slate-600 font-semibold">Director &bull; Administration</p>
          </div>
        </div>

      </div>

    </div>
  </div>

  <script>
    const ADMIN_CREDENTIALS = {
      email: "rambaxsinghintercollege@gmail.com",
      password: "vishnukant@207247"
    };

    function filterGallery(category) {
      const cards = document.querySelectorAll('.gallery-card');
      const buttons = document.querySelectorAll('.gallery-filter-btn');

      buttons.forEach(b => {
        b.classList.remove('bg-brand-navy', 'text-white', 'shadow');
        b.classList.add('bg-white', 'text-slate-700');
      });

      if (event && event.currentTarget) {
        event.currentTarget.classList.add('bg-brand-navy', 'text-white', 'shadow');
        event.currentTarget.classList.remove('bg-white', 'text-slate-700');
      }

      cards.forEach(card => {
        if (category === 'all' || card.getAttribute('data-category') === category) {
          card.classList.remove('hidden');
        } else {
          card.classList.add('hidden');
        }
      });
    }

    function openLightbox(imgSrc, caption) {
      const modal = document.getElementById('photoLightboxModal');
      const img = document.getElementById('lightboxImage');
      const cap = document.getElementById('lightboxCaption');
      if (modal && img) {
        img.src = imgSrc;
        cap.textContent = caption || 'RBS Inter College & Hostel';
        modal.classList.remove('hidden');
      }
    }

    function closeLightbox() {
      const modal = document.getElementById('photoLightboxModal');
      if (modal) modal.classList.add('hidden');
    }

    const SEED_STAFF = [
      {
        id: "STF-101",
        name: "Shyam Sundar Sharma",
        role: "Senior Lecturer - Physics & Hostel Warden",
        email: "shyam.rbs@gmail.com",
        password: "staff@101",
        status: "Active"
      },
      {
        id: "STF-102",
        name: "Dharmveer Sisodiya",
        role: "Lecturer - Mathematics & Cultural Incharge",
        email: "dharmveer.rbs@gmail.com",
        password: "staff@102",
        status: "Active"
      }
    ];

    const SEED_STUDENTS = [
      {
        roll: "RBS-1001",
        name: "Aditya Verma",
        father: "Rajendra Verma",
        mother: "Sunita Verma",
        dob: "2008-04-12",
        class: "Class 12th Science",
        hostel: "Hosteller",
        phone: "9876543210",
        password: "student@1001",
        status: "Active"
      },
      {
        roll: "RBS-1002",
        name: "Pooja Shakya",
        father: "Mahesh Shakya",
        mother: "Kamlesh Shakya",
        dob: "2009-08-20",
        class: "Class 10th",
        hostel: "Day Scholar",
        phone: "9411223344",
        password: "student@1002",
        status: "Active"
      },
      {
        roll: "RBS-1003",
        name: "Shivam Rajput",
        father: "Gopal Rajput",
        mother: "Rekha Devi",
        dob: "2008-01-10",
        class: "Class 12th Arts",
        hostel: "Hosteller",
        phone: "9123456780",
        password: "student@1003",
        status: "Active"
      }
    ];

    const SEED_INQUIRIES = [
      {
        id: "INQ-901",
        date: "2025-05-10",
        fullName: "Rahul Kumar",
        fatherName: "Sunil Kumar",
        motherName: "Kamlesh Devi",
        dob: "2008-07-15",
        className: "Class 11th Science",
        hostelReq: "Yes - Hostel Required",
        phone: "9837123456",
        prevSchool: "UP Board (82%)",
        address: "Village Bithara, Post Aliganj, Etah",
        status: "Approved"
      },
      {
        id: "INQ-902",
        date: "2025-05-12",
        fullName: "Anjali Chauhan",
        fatherName: "Virendra Chauhan",
        motherName: "Suman Chauhan",
        dob: "2009-03-22",
        className: "Class 10th",
        hostelReq: "No - Day Scholar",
        phone: "9456789123",
        prevSchool: "RBS Junior Wing (79%)",
        address: "Aliganj Road, Etah",
        status: "Pending"
      }
    ];

    const SEED_MARKSHEETS = [
      {
        id: "MK-1001",
        roll: "RBS-1001",
        name: "Aditya Verma",
        father: "Rajendra Verma",
        class: "Class 12th Science",
        hostel: "Hosteller",
        session: "2024-2025",
        examType: "ANNUAL BOARD EVALUATION",
        subjects: [
          { name: "General Hindi", maxTh: 100, maxPr: 0, obtTh: 88, obtPr: 0, total: 88, grade: "A+" },
          { name: "General English", maxTh: 100, maxPr: 0, obtTh: 82, obtPr: 0, total: 82, grade: "A" },
          { name: "Physics", maxTh: 70, maxPr: 30, obtTh: 62, obtPr: 28, total: 90, grade: "A+" },
          { name: "Chemistry", maxTh: 70, maxPr: 30, obtTh: 58, obtPr: 29, total: 87, grade: "A+" },
          { name: "Mathematics", maxTh: 100, maxPr: 0, obtTh: 92, obtPr: 0, total: 92, grade: "A+" }
        ],
        totalMax: 500,
        totalObtained: 439,
        percentage: "87.80",
        division: "1st Division with Honors",
        result: "PASSED"
      }
    ];

    function getStoredData(key, fallback) {
      try {
        const val = localStorage.getItem('rbs_v2_' + key);
        return val ? JSON.parse(val) : fallback;
      } catch (e) {
        return fallback;
      }
    }

    function saveStoredData(key, value) {
      try {
        localStorage.setItem('rbs_v2_' + key, JSON.stringify(value));
      } catch (e) {
        console.error(e);
      }
    }

    let state = {
      currentUser: null,
      currentLoginRole: 'admin',
      inquiries: getStoredData('inquiries', SEED_INQUIRIES),
      students: getStoredData('students', SEED_STUDENTS),
      staff: getStoredData('staff', SEED_STAFF),
      marksheets: getStoredData('marksheets', SEED_MARKSHEETS)
    };

    function showToast(message, type = 'success') {
      const container = document.getElementById('toastContainer');
      const toast = document.createElement('div');
      
      const bgColors = {
        success: 'bg-emerald-800 border-emerald-600 text-white',
        error: 'bg-red-800 border-red-600 text-white',
        info: 'bg-brand-navy border-brand-gold text-white'
      };

      const icon = type === 'success' ? 'fa-circle-check' : (type === 'error' ? 'fa-circle-exclamation' : 'fa-bell');

      toast.className = `pointer-events-auto flex items-center space-x-2.5 px-4 py-3 rounded-xl border shadow-xl text-xs font-semibold transform transition-all duration-300 translate-y-2 opacity-0 ${bgColors[type] || bgColors.info}`;
      toast.innerHTML = `<i class="fa-solid ${icon} text-brand-gold"></i> <span>${message}</span>`;
      
      container.appendChild(toast);

      requestAnimationFrame(() => {
        toast.classList.remove('translate-y-2', 'opacity-0');
      });

      setTimeout(() => {
        toast.classList.add('opacity-0', 'translate-y-2');
        setTimeout(() => toast.remove(), 300);
      }, 3500);
    }

    function togglePasswordVisibility(inputId, iconId) {
      const input = document.getElementById(inputId);
      const icon = document.getElementById(iconId);
      if (!input) return;
      if (input.type === 'password') {
        input.type = 'text';
        if (icon) {
          icon.classList.remove('fa-eye');
          icon.classList.add('fa-eye-slash');
        }
      } else {
        input.type = 'password';
        if (icon) {
          icon.classList.remove('fa-eye-slash');
          icon.classList.add('fa-eye');
        }
      }
    }

    function scrollToElement(id) {
      const el = document.getElementById(id);
      if (el) el.scrollIntoView({ behavior: 'smooth' });
    }

    function toggleMobileNav() {
      const menu = document.getElementById('mobileMenu');
      if (menu) menu.classList.toggle('hidden');
    }

    function showSection(section) {
      const views = ['mainPublicView', 'adminDashboardView', 'staffDashboardView', 'studentDashboardView'];
      views.forEach(v => {
        const el = document.getElementById(v);
        if (el) el.classList.add('hidden');
      });

      if (section === 'public-home') {
        document.getElementById('mainPublicView').classList.remove('hidden');
        window.scrollTo({ top: 0, behavior: 'smooth' });
      } else if (section === 'admin') {
        document.getElementById('adminDashboardView').classList.remove('hidden');
        renderAdminDashboard();
      } else if (section === 'staff') {
        document.getElementById('staffDashboardView').classList.remove('hidden');
        renderStaffDashboard();
      } else if (section === 'student') {
        document.getElementById('studentDashboardView').classList.remove('hidden');
        renderStudentDashboard();
      }
    }

    function openLoginModal(role = 'admin') {
      document.getElementById('loginModal').classList.remove('hidden');
      switchLoginRole(role);
    }

    function closeLoginModal() {
      document.getElementById('loginModal').classList.add('hidden');
      document.getElementById('loginFeedback').classList.add('hidden');
      document.getElementById('portalLoginForm').reset();
    }

    function switchLoginRole(role) {
      state.currentLoginRole = role;
      
      const tabAdmin = document.getElementById('roleTabAdmin');
      const tabStaff = document.getElementById('roleTabStaff');
      const tabStudent = document.getElementById('roleTabStudent');
      const label = document.getElementById('loginIdentifierLabel');
      const icon = document.getElementById('loginIdentifierIcon');
      const input = document.getElementById('loginIdentifier');
      const pass = document.getElementById('loginPassword');
      const submitText = document.getElementById('loginSubmitBtnText');

      // Clear any previous values - strictly NO suggested demo logins
      input.value = "";
      pass.value = "";

      [tabAdmin, tabStaff, tabStudent].forEach(t => {
        if (t) t.className = "py-2 rounded-xl transition text-slate-600 hover:text-brand-navy";
      });

      if (role === 'admin') {
        tabAdmin.className = "py-2 rounded-xl transition bg-white text-brand-navy shadow-sm font-bold";
        label.textContent = "Admin Email Address";
        icon.className = "fa-solid fa-envelope absolute left-3.5 top-3.5 text-slate-400 text-sm";
        input.placeholder = "rambaxsinghintercollege@gmail.com";
        submitText.textContent = "Login to Admin Terminal";
      } else if (role === 'staff') {
        tabStaff.className = "py-2 rounded-xl transition bg-white text-brand-navy shadow-sm font-bold";
        label.textContent = "Staff Email / Username";
        icon.className = "fa-solid fa-chalkboard-user absolute left-3.5 top-3.5 text-slate-400 text-sm";
        input.placeholder = "Enter staff email";
        submitText.textContent = "Login to Staff Terminal";
      } else if (role === 'student') {
        tabStudent.className = "py-2 rounded-xl transition bg-white text-brand-navy shadow-sm font-bold";
        label.textContent = "Student Roll No / ID";
        icon.className = "fa-solid fa-id-card absolute left-3.5 top-3.5 text-slate-400 text-sm";
        input.placeholder = "e.g. RBS-1001";
        submitText.textContent = "Login to Student Portal";
      }
    }

    function handlePortalLogin(e) {
      e.preventDefault();
      const identifier = document.getElementById('loginIdentifier').value.trim();
      const password = document.getElementById('loginPassword').value;
      const feedback = document.getElementById('loginFeedback');
      feedback.classList.add('hidden');

      if (state.currentLoginRole === 'admin') {
        if (identifier.toLowerCase() === ADMIN_CREDENTIALS.email.toLowerCase() && password === ADMIN_CREDENTIALS.password) {
          state.currentUser = { role: 'admin', name: 'Vishnu Kant (Manager)' };
          closeLoginModal();
          showToast('Welcome Manager Vishnu Kant! Terminal unlocked.', 'success');
          showSection('admin');
          return;
        } else {
          feedback.textContent = "Invalid Admin credentials.";
          feedback.classList.remove('hidden');
          return;
        }
      }

      if (state.currentLoginRole === 'staff') {
        const staffMember = state.staff.find(s => s.email.toLowerCase() === identifier.toLowerCase() && s.password === password);
        if (!staffMember) {
          feedback.textContent = "Staff account not found or password incorrect.";
          feedback.classList.remove('hidden');
          return;
        }
        if (staffMember.status !== 'Active') {
          feedback.textContent = "Staff account has been suspended by Admin.";
          feedback.classList.remove('hidden');
          return;
        }
        state.currentUser = { role: 'staff', data: staffMember };
        closeLoginModal();
        showToast(`Welcome Professor ${staffMember.name}!`, 'success');
        showSection('staff');
        return;
      }

      if (state.currentLoginRole === 'student') {
        const student = state.students.find(s => 
          (s.roll.toLowerCase() === identifier.toLowerCase() || (s.phone && s.phone === identifier)) && 
          s.password === password
        );
        if (!student) {
          feedback.textContent = "Invalid Roll No / ID or incorrect password.";
          feedback.classList.remove('hidden');
          return;
        }
        if (student.status !== 'Active') {
          feedback.textContent = "Portal access is disabled for this roll. Contact college office.";
          feedback.classList.remove('hidden');
          return;
        }
        state.currentUser = { role: 'student', data: student };
        closeLoginModal();
        showToast(`Welcome ${student.name}! Marksheet loaded.`, 'success');
        showSection('student');
        return;
      }
    }

    function logoutPortal() {
      state.currentUser = null;
      showToast('Logged out securely.', 'info');
      showSection('public-home');
    }

    function handlePublicAdmissionSubmit(e) {
      e.preventDefault();
      const inq = {
        id: "INQ-" + Date.now().toString().slice(-4),
        date: new Date().toISOString().split('T')[0],
        fullName: document.getElementById('admFullName').value.trim(),
        fatherName: document.getElementById('admFatherName').value.trim(),
        motherName: document.getElementById('admMotherName').value.trim() || 'N/A',
        dob: document.getElementById('admDob').value,
        className: document.getElementById('admClass').value,
        hostelReq: document.getElementById('admHostelReq').value,
        phone: document.getElementById('admPhone').value.trim(),
        prevSchool: document.getElementById('admPrevSchool').value.trim() || 'N/A',
        address: document.getElementById('admAddress').value.trim(),
        status: "Pending"
      };

      state.inquiries.unshift(inq);
      saveStoredData('inquiries', state.inquiries);
      document.getElementById('publicAdmissionForm').reset();
      showToast('Application submitted! Manager Vishnu Kant has received the admission request.', 'success');
      updateInquiryBadge();
    }

    function switchAdminTab(tabName) {
      const tabs = ['inquiries', 'students', 'staff', 'marksheets'];
      tabs.forEach(t => {
        const content = document.getElementById('adminTab' + t.charAt(0).toUpperCase() + t.slice(1));
        const btn = document.getElementById('adminTabBtn' + t.charAt(0).toUpperCase() + t.slice(1));
        if (content) content.classList.add('hidden');
        if (btn) btn.className = "admin-tab-btn px-4 py-2 rounded-xl text-slate-600 hover:text-brand-navy hover:bg-slate-100 transition flex items-center space-x-2 flex-shrink-0";
      });

      const activeContent = document.getElementById('adminTab' + tabName.charAt(0).toUpperCase() + tabName.slice(1));
      const activeBtn = document.getElementById('adminTabBtn' + tabName.charAt(0).toUpperCase() + tabName.slice(1));
      if (activeContent) activeContent.classList.remove('hidden');
      if (activeBtn) activeBtn.className = "admin-tab-btn px-4 py-2 rounded-xl bg-brand-navy text-white transition flex items-center space-x-2 flex-shrink-0";

      if (tabName === 'inquiries') renderInquiriesTable();
      if (tabName === 'students') renderStudentsTable();
      if (tabName === 'staff') renderStaffTable();
      if (tabName === 'marksheets') renderMarksheetsTable();
    }

    function renderAdminDashboard() {
      updateInquiryBadge();
      renderInquiriesTable();
      renderStudentsTable();
      renderStaffTable();
      renderMarksheetsTable();
    }

    function updateInquiryBadge() {
      const badge = document.getElementById('badgeInquiryCount');
      if (badge) badge.textContent = state.inquiries.length;
    }

    function renderInquiriesTable(list = state.inquiries) {
      const tbody = document.getElementById('inquiriesTableBody');
      if (!tbody) return;
      tbody.innerHTML = '';
      updateInquiryBadge();

      list.forEach(inq => {
        const tr = document.createElement('tr');
        tr.className = "hover:bg-slate-50";
        tr.innerHTML = `
          <td class="py-2.5 px-3 text-slate-500 whitespace-nowrap">${inq.date}</td>
          <td class="py-2.5 px-3 font-bold text-brand-navy">${escapeHTML(inq.fullName)}</td>
          <td class="py-2.5 px-3">${escapeHTML(inq.fatherName)}</td>
          <td class="py-2.5 px-3"><span class="bg-blue-50 text-blue-800 px-2 py-0.5 rounded font-bold text-xs">${inq.className}</span></td>
          <td class="py-2.5 px-3"><span class="bg-amber-50 text-amber-900 border border-amber-200 px-2 py-0.5 rounded font-bold text-[11px]">${inq.hostelReq}</span></td>
          <td class="py-2.5 px-3 font-mono">${inq.phone}</td>
          <td class="py-2.5 px-3">
            <span class="px-2 py-0.5 rounded text-[10px] font-bold ${inq.status === 'Approved' ? 'bg-emerald-100 text-emerald-800' : 'bg-amber-100 text-amber-800'}">
              ${inq.status}
            </span>
          </td>
          <td class="py-2.5 px-3 text-right space-x-1 whitespace-nowrap">
            <button onclick="approveInquiry('${inq.id}')" class="px-2 py-1 bg-emerald-600 text-white rounded text-xs font-bold" title="Approve">
              <i class="fa-solid fa-check"></i>
            </button>
            <button onclick="deleteInquiry('${inq.id}')" class="px-2 py-1 bg-red-600 text-white rounded text-xs font-bold" title="Delete">
              <i class="fa-solid fa-trash"></i>
            </button>
          </td>
        `;
        tbody.appendChild(tr);
      });
    }

    function filterInquiries() {
      const q = document.getElementById('searchInquiryInput').value.toLowerCase();
      const filtered = state.inquiries.filter(i => 
        i.fullName.toLowerCase().includes(q) ||
        i.fatherName.toLowerCase().includes(q) ||
        i.phone.includes(q) ||
        i.className.toLowerCase().includes(q)
      );
      renderInquiriesTable(filtered);
    }

    function approveInquiry(id) {
      const inq = state.inquiries.find(i => i.id === id);
      if (!inq) return;
      inq.status = 'Approved';
      saveStoredData('inquiries', state.inquiries);
      renderInquiriesTable();
      showToast(`Inquiry for ${inq.fullName} marked as Approved!`, 'success');
    }

    function deleteInquiry(id) {
      state.inquiries = state.inquiries.filter(i => i.id !== id);
      saveStoredData('inquiries', state.inquiries);
      renderInquiriesTable();
      showToast('Inquiry deleted.', 'info');
    }

    function renderStudentsTable() {
      const tbody = document.getElementById('studentsTableBody');
      if (!tbody) return;
      tbody.innerHTML = '';

      state.students.forEach(std => {
        const tr = document.createElement('tr');
        tr.className = "hover:bg-slate-50";
        tr.innerHTML = `
          <td class="py-2.5 px-3 font-mono font-bold text-brand-navy">${std.roll}</td>
          <td class="py-2.5 px-3 font-bold">${escapeHTML(std.name)}</td>
          <td class="py-2.5 px-3">${std.class}</td>
          <td class="py-2.5 px-3">
            <button onclick="toggleStudentHostel('${std.roll}')" class="px-2 py-0.5 rounded font-bold text-xs ${std.hostel === 'Hosteller' ? 'bg-amber-100 text-amber-900 border border-amber-300' : 'bg-slate-100 text-slate-700'}">
              <i class="fa-solid fa-bed mr-1 text-xs"></i>${std.hostel || 'Day Scholar'}
            </button>
          </td>
          <td class="py-2.5 px-3">
            <span class="font-mono text-xs bg-slate-100 px-2 py-1 rounded text-brand-navy font-bold">${std.password}</span>
          </td>
          <td class="py-2.5 px-3">
            <button onclick="toggleStudentAccess('${std.roll}')" class="px-2 py-0.5 rounded text-[10px] font-bold ${std.status === 'Active' ? 'bg-emerald-100 text-emerald-800' : 'bg-red-100 text-red-800'}">
              ${std.status}
            </button>
          </td>
          <td class="py-2.5 px-3 text-right space-x-1 whitespace-nowrap">
            <button onclick="openPasswordReset('student', '${std.roll}', '${escapeHTML(std.name)}')" class="px-2 py-1 bg-amber-600 hover:bg-amber-700 text-white rounded text-xs font-bold" title="Change Password">
              <i class="fa-solid fa-key mr-1"></i> Pass
            </button>
            <button onclick="deleteStudent('${std.roll}')" class="px-2 py-1 bg-red-100 hover:bg-red-200 text-red-700 rounded text-xs font-bold">
              <i class="fa-solid fa-trash"></i>
            </button>
          </td>
        `;
        tbody.appendChild(tr);
      });
    }

    function toggleStudentHostel(roll) {
      const std = state.students.find(s => s.roll === roll);
      if (!std) return;
      std.hostel = (std.hostel === 'Hosteller') ? 'Day Scholar' : 'Hosteller';
      saveStoredData('students', state.students);
      renderStudentsTable();
      showToast(`${std.name} hostel status updated to ${std.hostel}`, 'info');
    }

    function toggleStudentAccess(roll) {
      const std = state.students.find(s => s.roll === roll);
      if (!std) return;
      std.status = (std.status === 'Active') ? 'Disabled' : 'Active';
      saveStoredData('students', state.students);
      renderStudentsTable();
      showToast(`Student portal access for ${std.name} is now ${std.status}`, 'info');
    }

    function deleteStudent(roll) {
      state.students = state.students.filter(s => s.roll !== roll);
      saveStoredData('students', state.students);
      renderStudentsTable();
      showToast('Student deleted from terminal.', 'info');
    }

    function renderStaffTable() {
      const tbody = document.getElementById('staffTableBody');
      if (!tbody) return;
      tbody.innerHTML = '';

      state.staff.forEach(stf => {
        const tr = document.createElement('tr');
        tr.className = "hover:bg-slate-50";
        tr.innerHTML = `
          <td class="py-2.5 px-3 font-bold text-brand-navy">${escapeHTML(stf.name)}</td>
          <td class="py-2.5 px-3"><span class="bg-amber-50 text-amber-900 border border-amber-200 px-2 py-0.5 rounded font-medium text-xs">${stf.role}</span></td>
          <td class="py-2.5 px-3 font-mono text-xs">${stf.email}</td>
          <td class="py-2.5 px-3">
            <span class="font-mono text-xs bg-slate-100 px-2 py-1 rounded text-brand-navy font-bold">${stf.password}</span>
          </td>
          <td class="py-2.5 px-3">
            <button onclick="toggleStaffAccess('${stf.id}')" class="px-2 py-0.5 rounded text-[10px] font-bold ${stf.status === 'Active' ? 'bg-emerald-100 text-emerald-800' : 'bg-red-100 text-red-800'}">
              ${stf.status}
            </button>
          </td>
          <td class="py-2.5 px-3 text-right space-x-1 whitespace-nowrap">
            <button onclick="openPasswordReset('staff', '${stf.id}', '${escapeHTML(stf.name)}')" class="px-2 py-1 bg-amber-600 hover:bg-amber-700 text-white rounded text-xs font-bold" title="Change Password">
              <i class="fa-solid fa-key mr-1"></i> Pass
            </button>
            <button onclick="deleteStaff('${stf.id}')" class="px-2 py-1 bg-red-100 hover:bg-red-200 text-red-700 rounded text-xs font-bold">
              <i class="fa-solid fa-trash"></i>
            </button>
          </td>
        `;
        tbody.appendChild(tr);
      });
    }

    function toggleStaffAccess(id) {
      const stf = state.staff.find(s => s.id === id);
      if (!stf) return;
      stf.status = (stf.status === 'Active') ? 'Suspended' : 'Active';
      saveStoredData('staff', state.staff);
      renderStaffTable();
      showToast(`Staff access for ${stf.name} updated to ${stf.status}`, 'info');
    }

    function deleteStaff(id) {
      state.staff = state.staff.filter(s => s.id !== id);
      saveStoredData('staff', state.staff);
      renderStaffTable();
      showToast('Staff member deleted.', 'info');
    }

    function openPasswordReset(type, id, name) {
      document.getElementById('pwdResetType').value = type;
      document.getElementById('pwdResetId').value = id;
      document.getElementById('pwdResetTargetName').textContent = `Target: ${name} (${type.toUpperCase()})`;
      document.getElementById('newResetPasswordVal').value = '';
      document.getElementById('passwordResetModal').classList.remove('hidden');
    }

    function closePasswordResetModal() {
      document.getElementById('passwordResetModal').classList.add('hidden');
      document.getElementById('pwdResetForm').reset();
    }

    function handleConfirmPasswordReset(e) {
      e.preventDefault();
      const type = document.getElementById('pwdResetType').value;
      const id = document.getElementById('pwdResetId').value;
      const newPass = document.getElementById('newResetPasswordVal').value.trim();

      if (type === 'staff') {
        const member = state.staff.find(s => s.id === id);
        if (member) {
          member.password = newPass;
          saveStoredData('staff', state.staff);
          renderStaffTable();
          showToast(`Staff password for ${member.name} updated successfully!`, 'success');
        }
      } else if (type === 'student') {
        const std = state.students.find(s => s.roll === id);
        if (std) {
          std.password = newPass;
          saveStoredData('students', state.students);
          renderStudentsTable();
          showToast(`Student password for Roll ${std.roll} (${std.name}) updated!`, 'success');
        }
      }

      closePasswordResetModal();
    }

    function openAddStudentModal() {
      document.getElementById('addStudentModal').classList.remove('hidden');
    }
    function closeAddStudentModal() {
      document.getElementById('addStudentModal').classList.add('hidden');
      document.getElementById('addStudentForm').reset();
    }

    function handleSaveNewStudent(e) {
      e.preventDefault();
      const roll = document.getElementById('newStdRoll').value.trim();
      if (state.students.some(s => s.roll.toLowerCase() === roll.toLowerCase())) {
        showToast('Roll number already exists!', 'error');
        return;
      }

      const newStudent = {
        roll: roll,
        name: document.getElementById('newStdName').value.trim(),
        class: document.getElementById('newStdClass').value,
        hostel: document.getElementById('newStdHostel').value,
        phone: document.getElementById('newStdPhone').value.trim(),
        father: document.getElementById('newStdFather').value.trim() || 'Parent',
        mother: 'Parent',
        dob: '2008-01-01',
        password: document.getElementById('newStdPass').value,
        status: document.getElementById('newStdStatus').value
      };

      state.students.push(newStudent);
      saveStoredData('students', state.students);
      closeAddStudentModal();
      renderStudentsTable();
      showToast(`Student ${newStudent.name} registered with portal access!`, 'success');
    }

    function openAddStaffModal() {
      document.getElementById('addStaffModal').classList.remove('hidden');
    }
    function closeAddStaffModal() {
      document.getElementById('addStaffModal').classList.add('hidden');
      document.getElementById('addStaffForm').reset();
    }

    function handleSaveNewStaff(e) {
      e.preventDefault();
      const email = document.getElementById('newStaffEmail').value.trim();
      if (state.staff.some(s => s.email.toLowerCase() === email.toLowerCase())) {
        showToast('Email address already exists!', 'error');
        return;
      }

      const newStaff = {
        id: "STF-" + Date.now().toString().slice(-4),
        name: document.getElementById('newStaffName').value.trim(),
        role: document.getElementById('newStaffRole').value.trim(),
        email: email,
        password: document.getElementById('newStaffPass').value,
        status: document.getElementById('newStaffStatus').value
      };

      state.staff.push(newStaff);
      saveStoredData('staff', state.staff);
      closeAddStaffModal();
      renderStaffTable();
      showToast(`Staff member ${newStaff.name} created!`, 'success');
    }

    function renderMarksheetsTable() {
      const tbody = document.getElementById('marksheetsTableBody');
      if (!tbody) return;
      tbody.innerHTML = '';

      state.marksheets.forEach(mk => {
        const tr = document.createElement('tr');
        tr.className = "hover:bg-slate-50";
        tr.innerHTML = `
          <td class="py-2.5 px-3 font-mono font-bold text-brand-navy">${mk.roll}</td>
          <td class="py-2.5 px-3 font-bold">${escapeHTML(mk.name)}</td>
          <td class="py-2.5 px-3">${mk.class}</td>
          <td class="py-2.5 px-3"><span class="bg-amber-100 text-amber-900 px-2 py-0.5 rounded font-bold text-xs">${mk.hostel || 'Hosteller'}</span></td>
          <td class="py-2.5 px-3 text-xs text-slate-500">${mk.examType || 'ANNUAL'}</td>
          <td class="py-2.5 px-3 font-bold">${mk.totalObtained} / ${mk.totalMax}</td>
          <td class="py-2.5 px-3 font-black text-brand-navy">${mk.percentage}% (${mk.division})</td>
          <td class="py-2.5 px-3 text-right space-x-1 whitespace-nowrap">
            <button onclick="previewMarksheet('${mk.roll}')" class="px-2.5 py-1 bg-brand-navy hover:bg-brand-lightnavy text-brand-gold rounded text-xs font-bold">
              <i class="fa-solid fa-stamp mr-1"></i> View / Print
            </button>
            <button onclick="deleteMarksheet('${mk.roll}')" class="px-2 py-1 bg-red-100 hover:bg-red-200 text-red-700 rounded text-xs font-bold">
              <i class="fa-solid fa-trash"></i>
            </button>
          </td>
        `;
        tbody.appendChild(tr);
      });
    }

    function openCreateMarksheetModal() {
      const select = document.getElementById('mkStudentSelect');
      select.innerHTML = '<option value="">-- Choose Registered Student --</option>';
      state.students.forEach(std => {
        select.innerHTML += `<option value="${std.roll}">${std.name} (${std.roll} - ${std.class} - ${std.hostel || 'Hosteller'})</option>`;
      });

      document.getElementById('marksheetModal').classList.remove('hidden');
      calculateAdvancedMarks();
    }

    function closeMarksheetModal() {
      document.getElementById('marksheetModal').classList.add('hidden');
      document.getElementById('marksheetForm').reset();
    }

    function autoFillMarksheetStudentDetails() {
      const roll = document.getElementById('mkStudentSelect').value;
      const std = state.students.find(s => s.roll === roll);
      if (std) {
        document.getElementById('mkRollNo').value = std.roll;
        document.getElementById('mkClass').value = std.class;
      } else {
        document.getElementById('mkRollNo').value = '';
        document.getElementById('mkClass').value = '';
      }
    }

    function calculateAdvancedMarks() {
      const thHindi = Number(document.getElementById('th_hindi').value) || 0;
      const thEng = Number(document.getElementById('th_english').value) || 0;
      const thPhy = Number(document.getElementById('th_physics').value) || 0;
      const prPhy = Number(document.getElementById('pr_physics').value) || 0;
      const thChem = Number(document.getElementById('th_chem').value) || 0;
      const prChem = Number(document.getElementById('pr_chem').value) || 0;
      const thMath = Number(document.getElementById('th_math').value) || 0;

      const total = thHindi + thEng + thPhy + prPhy + thChem + prChem + thMath;
      const pct = ((total / 500) * 100).toFixed(2);

      let div = "3rd Division";
      if (pct >= 75) div = "1st Division with Honors";
      else if (pct >= 60) div = "1st Division";
      else if (pct >= 45) div = "2nd Division";

      document.getElementById('advTotalObtained').textContent = total;
      document.getElementById('advPercentage').textContent = pct;
      document.getElementById('advDivision').textContent = div;
    }

    function handleSaveMarksheet(e) {
      e.preventDefault();
      const roll = document.getElementById('mkRollNo').value;
      if (!roll) {
        showToast('Please select a student first!', 'error');
        return;
      }

      const std = state.students.find(s => s.roll === roll);
      const thHindi = Number(document.getElementById('th_hindi').value) || 0;
      const thEng = Number(document.getElementById('th_english').value) || 0;
      const thPhy = Number(document.getElementById('th_physics').value) || 0;
      const prPhy = Number(document.getElementById('pr_physics').value) || 0;
      const thChem = Number(document.getElementById('th_chem').value) || 0;
      const prChem = Number(document.getElementById('pr_chem').value) || 0;
      const thMath = Number(document.getElementById('th_math').value) || 0;

      const totalObtained = thHindi + thEng + thPhy + prPhy + thChem + prChem + thMath;
      const percentage = ((totalObtained / 500) * 100).toFixed(2);

      let division = "1st Division";
      if (percentage >= 75) division = "1st Division with Honors";
      else if (percentage < 60 && percentage >= 45) division = "2nd Division";
      else if (percentage < 45) division = "3rd Division";

      const subjects = [
        { name: "General Hindi", maxTh: 100, maxPr: 0, obtTh: thHindi, obtPr: 0, total: thHindi, grade: getGrade(thHindi) },
        { name: "General English", maxTh: 100, maxPr: 0, obtTh: thEng, obtPr: 0, total: thEng, grade: getGrade(thEng) },
        { name: "Physics", maxTh: 70, maxPr: 30, obtTh: thPhy, obtPr: prPhy, total: thPhy + prPhy, grade: getGrade(thPhy + prPhy) },
        { name: "Chemistry", maxTh: 70, maxPr: 30, obtTh: thChem, obtPr: prChem, total: thChem + prChem, grade: getGrade(thChem + prChem) },
        { name: "Mathematics / Biology", maxTh: 100, maxPr: 0, obtTh: thMath, obtPr: 0, total: thMath, grade: getGrade(thMath) }
      ];

      const newMarksheet = {
        id: "MK-" + roll,
        roll: roll,
        name: std ? std.name : "Candidate",
        father: std ? std.father : "Parent",
        mother: std ? std.mother : "Parent",
        dob: std ? std.dob : "2008-01-01",
        hostel: std ? std.hostel : "Hosteller",
        class: std ? std.class : document.getElementById('mkClass').value,
        session: document.getElementById('mkSession').value,
        examType: document.getElementById('mkExamType').value,
        subjects: subjects,
        totalMax: 500,
        totalObtained: totalObtained,
        percentage: percentage,
        division: division,
        result: percentage >= 33 ? "PASSED" : "FAILED"
      };

      state.marksheets = state.marksheets.filter(m => m.roll !== roll);
      state.marksheets.push(newMarksheet);
      saveStoredData('marksheets', state.marksheets);

      closeMarksheetModal();
      renderMarksheetsTable();
      showToast(`State Board Marksheet for ${newMarksheet.name} generated!`, 'success');
      previewMarksheet(roll);
    }

    function getGrade(score) {
      if (score >= 85) return 'A+';
      if (score >= 70) return 'A';
      if (score >= 55) return 'B+';
      if (score >= 40) return 'B';
      if (score >= 33) return 'C';
      return 'D';
    }

    function deleteMarksheet(roll) {
      state.marksheets = state.marksheets.filter(m => m.roll !== roll);
      saveStoredData('marksheets', state.marksheets);
      renderMarksheetsTable();
      showToast('Marksheet record removed.', 'info');
    }

    function previewMarksheet(roll) {
      const mk = state.marksheets.find(m => m.roll === roll);
      if (!mk) {
        showToast('Marksheet record not found!', 'error');
        return;
      }

      document.getElementById('pvSession').textContent = mk.session;
      document.getElementById('pvExamHeader').textContent = mk.examType || 'ANNUAL BOARD EVALUATION';
      document.getElementById('pvStudentName').textContent = mk.name;
      document.getElementById('pvFatherName').textContent = mk.father;
      document.getElementById('pvRollNo').textContent = mk.roll;
      document.getElementById('pvClass').textContent = mk.class;
      document.getElementById('pvHostelStatus').textContent = mk.hostel || 'Hosteller';
      document.getElementById('pvDob').textContent = mk.dob || '15/07/2008';
      document.getElementById('pvSerialNo').textContent = 'RBS/' + mk.session.split('-')[0] + '/' + Math.floor(1000 + Math.random() * 9000);

      document.getElementById('pvMaxTotal').textContent = mk.totalMax;
      document.getElementById('pvObtainedTotal').textContent = mk.totalObtained;
      document.getElementById('pvPercentage').textContent = mk.percentage + "%";
      document.getElementById('pvResultStatus').textContent = mk.result;
      document.getElementById('pvDivision').textContent = mk.division;
      document.getElementById('pvFinalGrade').textContent = getGrade(Math.round(mk.percentage));

      const tbody = document.getElementById('pvMarksTableBody');
      tbody.innerHTML = '';

      mk.subjects.forEach((sub, i) => {
        const tr = document.createElement('tr');
        tr.className = "hover:bg-slate-50";
        tr.innerHTML = `
          <td class="p-1 border border-brand-navy text-center">${i + 1}</td>
          <td class="p-1 border border-brand-navy font-bold">${sub.name}</td>
          <td class="p-1 border border-brand-navy text-center">${sub.maxTh}</td>
          <td class="p-1 border border-brand-navy text-center">${sub.maxPr}</td>
          <td class="p-1 border border-brand-navy text-center font-semibold">${sub.maxTh + sub.maxPr}</td>
          <td class="p-1 border border-brand-navy text-center font-bold">${sub.obtTh}</td>
          <td class="p-1 border border-brand-navy text-center font-bold">${sub.obtPr > 0 ? sub.obtPr : '-'}</td>
          <td class="p-1 border border-brand-navy text-center font-black text-brand-navy">${sub.total}</td>
          <td class="p-1 border border-brand-navy text-center font-black text-brand-navy">${sub.grade}</td>
        `;
        tbody.appendChild(tr);
      });

      document.getElementById('marksheetPreviewModal').classList.remove('hidden');
    }

    function closeMarksheetPreviewModal() {
      document.getElementById('marksheetPreviewModal').classList.add('hidden');
    }

    function renderStaffDashboard() {
      const user = state.currentUser;
      if (!user || user.role !== 'staff') return;

      document.getElementById('staffGreetingName').textContent = `Welcome, ${user.data.name}`;
      document.getElementById('staffTotalStudentsCount').textContent = state.students.length;
      document.getElementById('staffHostellerCount').textContent = state.students.filter(s => s.hostel === 'Hosteller').length;

      const tbody = document.getElementById('staffStudentsTableBody');
      tbody.innerHTML = '';

      state.students.forEach(std => {
        const hasMarksheet = state.marksheets.some(m => m.roll === std.roll);
        const tr = document.createElement('tr');
        tr.className = "hover:bg-slate-50";
        tr.innerHTML = `
          <td class="py-2.5 px-3 font-mono font-bold">${std.roll}</td>
          <td class="py-2.5 px-3 font-bold">${escapeHTML(std.name)}</td>
          <td class="py-2.5 px-3">${std.class}</td>
          <td class="py-2.5 px-3"><span class="bg-amber-100 text-amber-900 px-2 py-0.5 rounded text-xs font-bold">${std.hostel || 'Hosteller'}</span></td>
          <td class="py-2.5 px-3 font-mono">${std.phone || 'N/A'}</td>
          <td class="py-2.5 px-3 text-right">
            ${hasMarksheet 
              ? `<button onclick="previewMarksheet('${std.roll}')" class="px-2.5 py-1 bg-emerald-100 text-emerald-800 rounded font-bold text-xs"><i class="fa-solid fa-stamp mr-1"></i> View Marksheet</button>`
              : `<button onclick="openCreateMarksheetModal()" class="px-2.5 py-1 bg-brand-gold/20 text-brand-navy rounded font-bold text-xs">+ Input Marks</button>`}
          </td>
        `;
        tbody.appendChild(tr);
      });
    }

    function renderStudentDashboard() {
      const user = state.currentUser;
      if (!user || user.role !== 'student') return;

      const std = user.data;
      document.getElementById('studentProfileName').textContent = std.name;
      document.getElementById('studentProfileRoll').textContent = std.roll;
      document.getElementById('studentProfileClass').textContent = std.class;
      document.getElementById('studentHostelBadge').textContent = std.hostel || 'Hostel Resident';

      const initials = std.name.split(' ').map(n => n[0]).join('').toUpperCase().slice(0, 2);
      document.getElementById('studentAvatarInitials').textContent = initials;

      const marksheetContainer = document.getElementById('studentMarksheetContainer');
      const marksheet = state.marksheets.find(m => m.roll === std.roll);

      if (marksheet) {
        marksheetContainer.innerHTML = `
          <div class="flex flex-col sm:flex-row justify-between items-start sm:items-center gap-4 border-b pb-4 mb-4">
            <div>
              <span class="text-[10px] bg-emerald-100 text-emerald-800 font-black px-2 py-0.5 rounded-full uppercase">Official State-Board Record</span>
              <h3 class="text-xl font-bold font-serif text-brand-navy mt-1">${marksheet.examType || 'Annual Examination'} (${marksheet.session})</h3>
              <p class="text-xs text-slate-500">Certified by Manager Vishnu Kant &amp; Director Avadhesh Singh</p>
            </div>
            <button onclick="previewMarksheet('${marksheet.roll}')" class="px-4 py-2 bg-brand-navy text-brand-gold rounded-xl font-bold text-xs shadow hover:scale-105 transition flex items-center space-x-1.5">
              <i class="fa-solid fa-stamp"></i>
              <span>View Full State Marksheet</span>
            </button>
          </div>

          <div class="grid grid-cols-2 sm:grid-cols-4 gap-3 text-center my-4">
            <div class="bg-slate-50 p-3 rounded-xl border">
              <p class="text-xs text-slate-500">Total Marks</p>
              <p class="text-lg font-black text-brand-navy">${marksheet.totalObtained} / ${marksheet.totalMax}</p>
            </div>
            <div class="bg-slate-50 p-3 rounded-xl border">
              <p class="text-xs text-slate-500">Percentage</p>
              <p class="text-lg font-black text-emerald-700">${marksheet.percentage}%</p>
            </div>
            <div class="bg-slate-50 p-3 rounded-xl border">
              <p class="text-xs text-slate-500">Division</p>
              <p class="text-sm font-black text-brand-navy mt-1">${marksheet.division}</p>
            </div>
            <div class="bg-slate-50 p-3 rounded-xl border">
              <p class="text-xs text-slate-500">Status</p>
              <p class="text-sm font-black text-emerald-600 mt-1 uppercase">${marksheet.result}</p>
            </div>
          </div>
        `;
      } else {
        marksheetContainer.innerHTML = `
          <div class="text-center py-10 space-y-2">
            <div class="w-12 h-12 mx-auto rounded-full bg-amber-50 text-amber-600 flex items-center justify-center text-xl">
              <i class="fa-solid fa-hourglass-half"></i>
            </div>
            <h4 class="text-base font-bold text-slate-800">Official Marksheet in Preparation</h4>
            <p class="text-xs text-slate-500 max-w-sm mx-auto">
              Your examination marks are being verified by the evaluation branch. Contact Manager Vishnu Kant for updates.
            </p>
          </div>
        `;
      }
    }

    function downloadStudentMarksheet() {
      if (!state.currentUser || state.currentUser.role !== 'student') return;
      const roll = state.currentUser.data.roll;
      const mk = state.marksheets.find(m => m.roll === roll);
      if (mk) {
        previewMarksheet(roll);
        setTimeout(() => window.print(), 350);
      } else {
        showToast('Official marksheet has not been uploaded yet.', 'info');
      }
    }

    function escapeHTML(str) {
      if (!str) return '';
      return String(str)
        .replace(/&/g, '&amp;')
        .replace(/</g, '&lt;')
        .replace(/>/g, '&gt;')
        .replace(/"/g, '&quot;')
        .replace(/'/g, '&#039;');
    }

    window.addEventListener('DOMContentLoaded', () => {
      showSection('public-home');
    });
  </script>
</body>
</html>
                extend: {
                    colors: {
                        rbsNavy: '#051329',
                        rbsNavyDark: '#030b18',
                        rbsNavyCard: '#0a1d3d',
                        rbsGold: '#d4af37',
                        rbsGoldLight: '#fde68a',
                        rbsGoldDark: '#997b19',
                        rbsAccent: '#1e3a8a'
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        serif: ['Cinzel', 'Georgia', 'serif'],
                        formal: ['Merriweather', 'serif']
                    }
                }
            }
        }
    </script>
    <!-- Google Fonts & FontAwesome -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@600;700;800;900&family=Inter:wght@300;400;500;600;700;800&family=Merriweather:wght@400;700;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <style>
        .gold-gradient-text {
            background: linear-gradient(135deg, #fff3b0 0%, #d4af37 50%, #aa820a 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .gold-glow {
            box-shadow: 0 0 25px rgba(212, 175, 55, 0.25);
        }
        .custom-scroll::-webkit-scrollbar {
            width: 6px;
            height: 6px;
        }
        .custom-scroll::-webkit-scrollbar-thumb {
            background: #d4af37;
            border-radius: 9999px;
        }
        .custom-scroll::-webkit-scrollbar-track {
            background: #030b18;
        }

        /* 
           STRICT EXACT SINGLE A4 PAGE PRINT OPTIMIZATION
           Guarantees 100% that only 1 page prints without overflow or cut-off
        */
        @media print {
            @page {
                size: A4 portrait;
                margin: 0 !important;
            }
            html, body {
                width: 210mm !important;
                height: 297mm !important;
                margin: 0 !important;
                padding: 0 !important;
                background: #ffffff !important;
                color: #000000 !important;
                -webkit-print-color-adjust: exact !important;
                print-color-adjust: exact !important;
                overflow: hidden !important;
            }
            body * {
                visibility: hidden !important;
            }
            #printableMarksheetWrapper, #printableMarksheetWrapper * {
                visibility: visible !important;
            }
            #printableMarksheetWrapper {
                position: absolute !important;
                left: 0 !important;
                top: 0 !important;
                width: 210mm !important;
                height: 297mm !important;
                max-height: 297mm !important;
                margin: 0 !important;
                padding: 7mm 8mm !important;
                box-sizing: border-box !important;
                page-break-after: avoid !important;
                page-break-before: avoid !important;
                page-break-inside: avoid !important;
                background: #ffffff !important;
                display: flex !important;
                flex-direction: column !important;
                justify-content: space-between !important;
            }
            .no-print {
                display: none !important;
            }
        }
    </style>
</head>
<body class="bg-rbsNavyDark text-slate-100 font-sans antialiased selection:bg-rbsGold selection:text-rbsNavy min-h-screen flex flex-col custom-scroll">

    <!-- Top Emergency & Helpline Bar -->
    <div class="bg-gradient-to-r from-rbsNavyDark via-rbsNavy to-rbsNavyDark border-b border-amber-500/20 text-xs py-2 px-4 sm:px-8">
        <div class="max-w-7xl mx-auto flex flex-wrap items-center justify-between gap-3">
            <div class="flex items-center gap-4 flex-wrap text-slate-300">
                <span class="flex items-center gap-1.5 text-amber-300 font-semibold">
                    <i class="fa-solid fa-map-pin text-rbsGold animate-bounce"></i> Bithara, Aliganj (Etah - 207247) UP
                </span>
                <a href="tel:6395052394" class="hover:text-amber-300 transition flex items-center gap-1 font-mono">
                    <i class="fa-solid fa-phone text-rbsGold"></i> +91 6395052394
                </a>
                <span class="hidden md:inline text-slate-600">|</span>
                <span class="hidden md:flex items-center gap-1.5 text-slate-300">
                    <i class="fa-solid fa-user-tie text-rbsGold"></i> Manager: <strong class="text-amber-300">Vishnu Kant</strong>
                </span>
                <span class="hidden lg:flex items-center gap-1.5 text-slate-300">
                    <i class="fa-solid fa-graduation-cap text-rbsGold"></i> Director: <strong class="text-white">Avadhesh Singh</strong>
                </span>
            </div>
            <div class="flex items-center gap-3">
                <span class="px-2.5 py-0.5 rounded-full text-[11px] font-bold bg-amber-500/20 text-amber-300 border border-amber-500/40">
                    <i class="fa-solid fa-hotel text-xs mr-1"></i> Co-Ed Hostel Campus
                </span>
                <button onclick="openAdminModal()" class="bg-gradient-to-r from-amber-400 via-rbsGold to-amber-600 hover:from-amber-300 hover:to-amber-500 text-rbsNavy font-black px-3.5 py-1 rounded-lg text-xs shadow-md transition-all active:scale-95 flex items-center gap-1.5">
                    <i class="fa-solid fa-lock"></i> Staff Login
                </button>
            </div>
        </div>
    </div>

    <header class="bg-rbsNavy/95 backdrop-blur-md border-b border-amber-500/30 sticky top-0 z-40 px-4 sm:px-8 py-3.5 shadow-2xl">
        <div class="max-w-7xl mx-auto flex items-center justify-between">
            <!-- Brand Logo and Titles -->
            <a href="#" class="flex items-center gap-3.5 group">
                <!-- SVG Crest Matching Uploaded RBS Emblem -->
                <div class="w-14 h-14 sm:w-16 sm:h-16 flex-shrink-0 relative">
                    <svg class="w-full h-full drop-shadow-[0_0_15px_rgba(212,175,55,0.4)] transition-transform group-hover:scale-105" viewBox="0 0 200 200" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <circle cx="100" cy="100" r="96" fill="#051329" stroke="#d4af37" stroke-width="4.5"/>
                        <circle cx="100" cy="100" r="88" stroke="#d4af37" stroke-width="1.8" stroke-dasharray="3 3"/>
                        <circle cx="100" cy="100" r="69" stroke="#d4af37" stroke-width="2.5"/>
                        <path id="crestTopNav" d="M 30,100 A 70,70 0 1,1 170,100" fill="none"/>
                        <text font-family="'Cinzel', Georgia, serif" font-size="16.5" font-weight="900" fill="#fde68a" letter-spacing="3.5">
                            <textPath href="#crestTopNav" startOffset="50%" text-anchor="middle">RBS INTER COLLEGE</textPath>
                        </text>
                        <path id="crestBottomNav" d="M 170,100 A 70,70 0 0,1 30,100" fill="none"/>
                        <text font-family="'Cinzel', Georgia, serif" font-size="14.5" font-weight="800" fill="#fde68a" letter-spacing="3">
                            <textPath href="#crestBottomNav" startOffset="50%" text-anchor="middle">BITHARA ALIGANJ ETAH</textPath>
                        </text>
                        <text x="100" y="94" font-family="'Cinzel', Georgia, serif" font-size="37" font-weight="900" fill="#d4af37" text-anchor="middle">RBS</text>
                        <g transform="translate(73, 104) scale(0.9)" stroke="#d4af37" stroke-width="2.2" fill="none" stroke-linejoin="round">
                            <path d="M30 25 C18 20 5 21 0 25 L0 5 C5 1 18 0 30 5 Z" fill="#0a1d3d"/>
                            <path d="M30 25 C42 20 55 21 60 25 L60 5 C55 1 42 0 30 5 Z" fill="#0a1d3d"/>
                            <line x1="30" y1="5" x2="30" y2="25"/>
                        </g>
                        <!-- Laurel Wreaths -->
                        <path d="M 48,90 C 45,110 52,130 68,142" stroke="#d4af37" stroke-width="2.5" fill="none"/>
                        <path d="M 152,90 C 155,110 148,130 132,142" stroke="#d4af37" stroke-width="2.5" fill="none"/>
                    </svg>
                </div>
                <div>
                    <span class="text-[10px] uppercase font-bold tracking-widest text-amber-300/90 block">
                        U.P. Board & CBSE Pattern Recognized
                    </span>
                    <h1 class="text-xl sm:text-2xl font-serif font-black tracking-wide gold-gradient-text uppercase leading-none drop-shadow">
                        RAMBAX SINGH INTER COLLEGE
                    </h1>
                    <p class="text-[11px] text-slate-300 font-medium mt-0.5">
                        Bithara, Aliganj (Etah - 207247) &bull; Co-Ed Residential Campus
                    </p>
                </div>
            </a>

            <!-- Desktop Nav Menu -->
            <div class="hidden lg:flex items-center gap-7">
                <a href="#about" class="text-sm font-semibold text-slate-200 hover:text-rbsGold transition">About Us</a>
                <a href="#leadership" class="text-sm font-semibold text-slate-200 hover:text-rbsGold transition">Leadership</a>
                <a href="#hostel" class="text-sm font-semibold text-amber-300 hover:text-white transition flex items-center gap-1.5">
                    <i class="fa-solid fa-hotel text-rbsGold"></i> Hostel Wing
                </a>
                <a href="#admissions" class="bg-gradient-to-r from-amber-400 via-rbsGold to-amber-600 hover:from-amber-300 hover:to-amber-500 text-rbsNavy font-black px-5 py-2.5 rounded-xl text-sm shadow-lg shadow-amber-500/20 transition transform hover:-translate-y-0.5 flex items-center gap-2">
                    <i class="fa-solid fa-file-signature"></i> Online Admission
                </a>
            </div>

            <!-- Mobile Menu Button -->
            <div class="flex items-center gap-2 lg:hidden">
                <a href="#admissions" class="bg-amber-400 text-rbsNavy font-bold px-3 py-1.5 rounded-lg text-xs">
                    Apply
                </a>
                <button onclick="toggleMobileNav()" class="p-2 text-slate-300 hover:text-amber-400 text-lg">
                    <i class="fa-solid fa-bars" id="mobileNavIcon"></i>
                </button>
            </div>
        </div>

        <!-- Mobile Drawer -->
        <div id="mobileDrawer" class="hidden lg:hidden pt-4 pb-2 border-t border-slate-800 mt-3 space-y-2">
            <a href="#about" onclick="toggleMobileNav()" class="block px-3 py-2 rounded text-slate-200 hover:bg-rbsNavyCard text-sm font-medium">About College</a>
            <a href="#leadership" onclick="toggleMobileNav()" class="block px-3 py-2 rounded text-slate-200 hover:bg-rbsNavyCard text-sm font-medium">Manager & Director</a>
            <a href="#hostel" onclick="toggleMobileNav()" class="block px-3 py-2 rounded text-amber-300 hover:bg-rbsNavyCard text-sm font-medium"><i class="fa-solid fa-hotel mr-2"></i> Residential Hostel</a>
            <a href="#admissions" onclick="toggleMobileNav()" class="block px-3 py-2 rounded bg-amber-400/20 text-amber-300 text-sm font-bold">Online Admission 2026-27</a>
            <button onclick="openAdminModal(); toggleMobileNav()" class="w-full text-left px-3 py-2.5 rounded bg-rbsNavyCard text-amber-400 text-sm font-bold flex items-center justify-between">
                <span><i class="fa-solid fa-stamp mr-2"></i> Admin & Marksheet Portal</span>
                <i class="fa-solid fa-chevron-right text-xs"></i>
            </button>
        </div>
    </header>

    <main class="flex-grow">
        <!-- Hero Section -->
        <section class="relative min-h-[580px] lg:min-h-[640px] flex items-center justify-center py-20 px-4 sm:px-6 overflow-hidden">
            <div class="absolute inset-0 bg-gradient-to-b from-rbsNavy via-rbsNavyDark to-rbsNavyDark opacity-95"></div>
            <div class="absolute inset-0 opacity-15 bg-[radial-gradient(#d4af37_1px,transparent_1px)] [background-size:24px_24px]"></div>

            <div class="relative max-w-6xl mx-auto text-center z-10">
                <div class="inline-flex items-center gap-2 px-4 py-1.5 rounded-full bg-amber-400/10 border border-amber-400/30 text-amber-300 text-xs sm:text-sm font-medium mb-6">
                    <i class="fa-solid fa-crown text-amber-400"></i>
                    <span>Premises & Residential Hostel at Bithara (Aliganj, Etah 207247)</span>
                </div>

                <!-- Highlighted College Name -->
                <div class="mb-4">
                    <h1 class="text-3xl sm:text-5xl md:text-6xl lg:text-7xl font-serif font-black tracking-wide uppercase drop-shadow-[0_10px_25px_rgba(0,0,0,0.9)]">
                        <span class="gold-gradient-text block">RAMBAX SINGH</span>
                        <span class="text-white drop-shadow-md">INTER COLLEGE</span>
                    </h1>
                    <div class="flex items-center justify-center gap-3 mt-3">
                        <span class="h-0.5 w-12 sm:w-28 bg-gradient-to-r from-transparent to-amber-400"></span>
                        <span class="text-sm sm:text-2xl font-bold text-amber-300 tracking-widest font-serif uppercase">
                            Bithara, Aliganj (Etah - 207247)
                        </span>
                        <span class="h-0.5 w-12 sm:w-28 bg-gradient-to-l from-transparent to-amber-400"></span>
                    </div>
                </div>

                <p class="max-w-3xl mx-auto text-slate-300 text-sm sm:text-lg md:text-xl font-normal leading-relaxed mt-5 mb-8">
                    An institution committed to academic brilliance, moral virtues, science and computer labs, and high-discipline residential living under the vision of <strong class="text-amber-300">Manager Vishnu Kant</strong> and <strong class="text-white">Director Avadhesh Singh</strong>.
                </p>

                <div class="flex flex-wrap items-center justify-center gap-4 sm:gap-6">
                    <a href="#admissions" class="bg-gradient-to-r from-amber-400 via-rbsGold to-amber-600 hover:from-amber-300 hover:to-amber-500 text-rbsNavy font-black px-8 py-4 rounded-2xl shadow-xl shadow-amber-500/25 transition transform hover:-translate-y-1 text-base flex items-center gap-3">
                        <i class="fa-solid fa-file-pen text-lg"></i>
                        <span>Online Admission Form (2026-27)</span>
                    </a>

                    <a href="#hostel" class="bg-rbsNavyCard/80 hover:bg-rbsNavyCard border border-amber-400/40 text-slate-100 font-bold px-7 py-4 rounded-2xl shadow-lg transition transform hover:-translate-y-1 text-base flex items-center gap-3 backdrop-blur-md">
                        <i class="fa-solid fa-hotel text-amber-400 text-lg"></i>
                        <span>Explore Residential Hostel</span>
                    </a>

                    <button onclick="openAdminModal()" class="bg-slate-900/90 hover:bg-slate-800 border border-slate-700 text-amber-300 font-semibold px-6 py-4 rounded-2xl transition text-base flex items-center gap-2">
                        <i class="fa-solid fa-lock text-sm"></i>
                        <span>Admin & Marksheet Desk</span>
                    </button>
                </div>
            </div>
        </section>

        <!-- Leadership Profiles (Manager Vishnu Kant with Photo & Director Avadhesh Singh) -->
        <section id="leadership" class="py-16 px-4 sm:px-8 bg-rbsNavy border-y border-amber-500/20">
            <div class="max-w-6xl mx-auto">
                <div class="text-center mb-12">
                    <span class="text-amber-400 text-xs font-bold uppercase tracking-wider bg-amber-400/10 px-3 py-1 rounded-full border border-amber-400/30">
                        Patrons & Administration
                    </span>
                    <h2 class="text-3xl sm:text-4xl font-serif font-black text-white mt-3">
                        College Management Board
                    </h2>
                    <p class="text-slate-300 text-sm sm:text-base max-w-2xl mx-auto mt-2">
                        Directing Rambax Singh Inter College towards academic pre-eminence, digital competence, and sound character building.
                    </p>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                    <!-- Manager Profile: Vishnu Kant -->
                    <div class="bg-gradient-to-br from-rbsNavyCard via-rbsNavy to-[#061429] p-6 sm:p-8 rounded-3xl border-2 border-amber-500/40 shadow-2xl relative overflow-hidden transition-all duration-300 hover:-translate-y-1 hover:border-amber-400">
                        <div class="absolute top-0 right-0 bg-gradient-to-l from-amber-500 to-amber-600 text-rbsNavy text-xs font-black px-4 py-1.5 rounded-bl-2xl uppercase tracking-wider">
                            College Manager
                        </div>
                        <div class="flex flex-col sm:flex-row items-center gap-6">
                            <!-- Official Photo of Manager Vishnu Kant with fallback -->
                            <div class="relative w-36 h-36 rounded-2xl ring-4 ring-amber-400/80 p-1 flex-shrink-0 bg-slate-900 shadow-2xl overflow-hidden">
                                <img src="vishnu kant.jpg" alt="Manager Vishnu Kant" 
                                    onerror="this.onerror=null; this.src='https://placehold.co/300x300/0a1d3d/d4af37?text=Manager+Vishnu+Kant';"
                                    class="w-full h-full object-cover object-top rounded-xl hover:scale-105 transition-transform duration-300">
                                <div class="absolute bottom-1 right-1 bg-amber-400 text-rbsNavy text-[10px] font-black px-2 py-0.5 rounded shadow">
                                    MANAGER
                                </div>
                            </div>
                            <div class="text-center sm:text-left flex-1">
                                <h3 class="text-2xl font-serif font-black text-white">Vishnu Kant</h3>
                                <p class="text-amber-400 font-bold text-sm">Hon'ble Manager & Executive Head</p>
                                <p class="text-slate-300 text-xs sm:text-sm mt-3 leading-relaxed">
                                    "Our prime vision is to provide high-standard education, modern digital pedagogy, and a secure hostel campus to empower students across Bithara, Aliganj, and the entire district of Etah."
                                </p>
                                <div class="mt-4 pt-3 border-t border-slate-700/80 flex flex-wrap items-center justify-center sm:justify-start gap-4 text-xs">
                                    <a href="tel:6395052394" class="text-amber-300 hover:text-white font-mono font-bold flex items-center gap-1.5 transition">
                                        <i class="fa-solid fa-phone-volume text-amber-400"></i> +91 6395052394
                                    </a>
                                    <span class="text-slate-400"><i class="fa-solid fa-shield-halved text-amber-400 mr-1"></i> Executive Desk</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Director Profile: Avadhesh Singh -->
                    <div class="bg-gradient-to-br from-rbsNavyCard via-rbsNavy to-[#061429] p-6 sm:p-8 rounded-3xl border-2 border-amber-500/40 shadow-2xl relative overflow-hidden transition-all duration-300 hover:-translate-y-1 hover:border-amber-400">
                        <div class="absolute top-0 right-0 bg-gradient-to-l from-amber-500 to-amber-600 text-rbsNavy text-xs font-black px-4 py-1.5 rounded-bl-2xl uppercase tracking-wider">
                            College Director
                        </div>
                        <div class="flex flex-col sm:flex-row items-center gap-6">
                            <div class="relative w-36 h-36 rounded-2xl ring-4 ring-amber-400/80 p-1 flex-shrink-0 bg-slate-900 shadow-2xl flex items-center justify-center text-5xl text-amber-400">
                                <i class="fa-solid fa-chalkboard-user"></i>
                                <div class="absolute bottom-1 right-1 bg-amber-400 text-rbsNavy text-[10px] font-black px-2 py-0.5 rounded shadow">
                                    DIRECTOR
                                </div>
                            </div>
                            <div class="text-center sm:text-left flex-1">
                                <h3 class="text-2xl font-serif font-black text-white">Avadhesh Singh</h3>
                                <p class="text-amber-400 font-bold text-sm">Hon'ble Director & Academic Dean</p>
                                <p class="text-slate-300 text-xs sm:text-sm mt-3 leading-relaxed">
                                    "We blend academic rigor with cultural ethics, physical sports, and science labs. Our institution is dedicated to building self-reliant scholars who secure top board exam ranks."
                                </p>
                                <div class="mt-4 pt-3 border-t border-slate-700/80 flex flex-wrap items-center justify-center sm:justify-start gap-4 text-xs text-slate-300">
                                    <span class="flex items-center gap-1.5"><i class="fa-solid fa-location-dot text-amber-400"></i> Bithara Campus, Aliganj</span>
                                    <span class="flex items-center gap-1.5"><i class="fa-solid fa-award text-amber-400"></i> Academic Excellence</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Residential Hostel Wing Showcase -->
        <section id="hostel" class="py-16 px-4 sm:px-8 bg-rbsNavyDark relative overflow-hidden">
            <div class="max-w-7xl mx-auto">
                <div class="flex flex-col lg:flex-row items-center gap-10">
                    <div class="lg:w-1/2">
                        <span class="px-3 py-1 rounded-full text-xs font-bold uppercase tracking-wider bg-amber-500/20 text-rbsGold border border-amber-500/30">
                            Residential Campus
                        </span>
                        <h2 class="text-3xl sm:text-4xl font-serif font-black text-white mt-3 leading-snug">
                            Safe & Disciplined <span class="gold-gradient-text">Hostel Facility</span>
                        </h2>
                        <p class="text-slate-300 text-sm sm:text-base mt-4 leading-relaxed">
                            Rambax Singh Inter College offers separate, fully-supervised residential hostel wings for boys and girls. Students from rural areas and distant towns get a peaceful, undistracted study environment with 24x7 security, nutritious dining, and daily remedial tutoring.
                        </p>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 mt-6">
                            <div class="flex items-start gap-3 p-3.5 rounded-xl bg-rbsNavyCard/70 border border-slate-700/70">
                                <div class="w-10 h-10 rounded-lg bg-amber-500/20 text-rbsGold flex items-center justify-center flex-shrink-0 text-lg">
                                    <i class="fa-solid fa-utensils"></i>
                                </div>
                                <div>
                                    <h4 class="font-bold text-white text-sm">Hygienic Mess & RO Water</h4>
                                    <p class="text-xs text-slate-300 mt-0.5">Four fresh, wholesome meals prepared in clean kitchens daily.</p>
                                </div>
                            </div>

                            <div class="flex items-start gap-3 p-3.5 rounded-xl bg-rbsNavyCard/70 border border-slate-700/70">
                                <div class="w-10 h-10 rounded-lg bg-amber-500/20 text-rbsGold flex items-center justify-center flex-shrink-0 text-lg">
                                    <i class="fa-solid fa-shield-halved"></i>
                                </div>
                                <div>
                                    <h4 class="font-bold text-white text-sm">24x7 Guarded Security & CCTV</h4>
                                    <p class="text-xs text-slate-300 mt-0.5">Strict warden vigilance, boundary protection, and visitor registers.</p>
                                </div>
                            </div>

                            <div class="flex items-start gap-3 p-3.5 rounded-xl bg-rbsNavyCard/70 border border-slate-700/70">
                                <div class="w-10 h-10 rounded-lg bg-amber-500/20 text-rbsGold flex items-center justify-center flex-shrink-0 text-lg">
                                    <i class="fa-solid fa-chalkboard-user"></i>
                                </div>
                                <div>
                                    <h4 class="font-bold text-white text-sm">Supervised Evening Coaching</h4>
                                    <p class="text-xs text-slate-300 mt-0.5">Mandatory quiet study hours under the guidance of resident subject teachers.</p>
                                </div>
                            </div>

                            <div class="flex items-start gap-3 p-3.5 rounded-xl bg-rbsNavyCard/70 border border-slate-700/70">
                                <div class="w-10 h-10 rounded-lg bg-amber-500/20 text-rbsGold flex items-center justify-center flex-shrink-0 text-lg">
                                    <i class="fa-solid fa-notes-medical"></i>
                                </div>
                                <div>
                                    <h4 class="font-bold text-white text-sm">First Aid & Doctor on Call</h4>
                                    <p class="text-xs text-slate-300 mt-0.5">Prompt medical care and periodic health examinations.</p>
                                </div>
                            </div>
                        </div>

                        <div class="mt-8 flex flex-wrap gap-4">
                            <a href="#admissions" class="bg-amber-400 hover:bg-amber-300 text-rbsNavy font-black px-6 py-3 rounded-xl text-sm transition">
                                Apply For Hostel Seat
                            </a>
                            <a href="tel:6395052394" class="inline-flex items-center gap-2 text-amber-300 hover:text-white px-5 py-3 rounded-xl border border-amber-400/40 text-sm">
                                <i class="fa-solid fa-phone"></i> Inquire Hostel: 6395052394
                            </a>
                        </div>
                    </div>

                    <!-- Daily Routine Schedule Card -->
                    <div class="lg:w-1/2 w-full">
                        <div class="bg-gradient-to-tr from-rbsNavy via-rbsNavyCard to-rbsNavy p-6 sm:p-8 rounded-3xl border border-amber-400/40 shadow-2xl">
                            <div class="flex items-center justify-between pb-4 border-b border-amber-400/20">
                                <div>
                                    <h3 class="text-xl font-bold text-white flex items-center gap-2">
                                        <i class="fa-solid fa-building-columns text-rbsGold"></i> RBS Residential Wing
                                    </h3>
                                    <p class="text-xs text-amber-300">Bithara, Aliganj Campus</p>
                                </div>
                                <span class="bg-emerald-500/20 text-emerald-300 border border-emerald-500/40 text-xs px-3 py-1 rounded-full font-bold">
                                    Hostel Seats Open
                                </span>
                            </div>

                            <div class="mt-6 space-y-3.5">
                                <div class="flex items-center justify-between p-3 rounded-xl bg-rbsNavyDark/80 border border-slate-700/80">
                                    <span class="text-sm text-slate-300"><i class="fa-solid fa-sun text-amber-400 mr-2"></i> Wakeup, Yoga & Physical Training</span>
                                    <span class="text-xs font-mono text-amber-300">05:30 AM - 06:30 AM</span>
                                </div>
                                <div class="flex items-center justify-between p-3 rounded-xl bg-rbsNavyDark/80 border border-slate-700/80">
                                    <span class="text-sm text-slate-300"><i class="fa-solid fa-school text-amber-400 mr-2"></i> Regular College Classes</span>
                                    <span class="text-xs font-mono text-amber-300">08:00 AM - 02:00 PM</span>
                                </div>
                                <div class="flex items-center justify-between p-3 rounded-xl bg-rbsNavyDark/80 border border-slate-700/80">
                                    <span class="text-sm text-slate-300"><i class="fa-solid fa-futbol text-amber-400 mr-2"></i> Sports, Football & Games</span>
                                    <span class="text-xs font-mono text-amber-300">04:30 PM - 05:45 PM</span>
                                </div>
                                <div class="flex items-center justify-between p-3 rounded-xl bg-rbsNavyDark/80 border border-slate-700/80">
                                    <span class="text-sm text-slate-300"><i class="fa-solid fa-book-open-reader text-amber-400 mr-2"></i> Supervised Night Study Hall</span>
                                    <span class="text-xs font-mono text-amber-300">06:30 PM - 09:30 PM</span>
                                </div>
                            </div>

                            <div class="mt-6 p-4 rounded-xl bg-amber-500/10 border border-amber-400/30 text-center">
                                <p class="text-xs text-amber-200">
                                    <i class="fa-solid fa-circle-check text-amber-400 mr-1.5"></i> Special mentorship for 10th & 12th Board students to secure 90%+ marks.
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Online Admission Section -->
        <section id="admissions" class="py-16 px-4 sm:px-8 bg-gradient-to-b from-rbsNavy to-rbsNavyDark border-t border-amber-500/20">
            <div class="max-w-5xl mx-auto">
                <div class="text-center mb-10">
                    <span class="px-3.5 py-1 rounded-full text-xs font-extrabold uppercase bg-amber-500/20 text-rbsGold border border-amber-500/30">
                        Session 2026-2027 Registration
                    </span>
                    <h2 class="text-3xl sm:text-4xl font-serif font-black text-white mt-3">
                        Online Student Admission Form
                    </h2>
                    <p class="text-slate-300 text-sm max-w-xl mx-auto mt-2">
                        Enter student details. Applications immediately sync to Manager Vishnu Kant's administrative dashboard.
                    </p>
                </div>

                <div class="bg-rbsNavyCard/90 backdrop-blur-md rounded-3xl p-6 sm:p-10 border-2 border-amber-500/35 shadow-2xl relative">
                    <form id="admissionForm" onsubmit="handleAdmissionSubmit(event)" class="space-y-6">
                        <div class="grid grid-cols-1 md:grid-cols-3 gap-5">
                            <div>
                                <label class="block text-xs font-bold uppercase tracking-wider text-amber-300 mb-1.5">
                                    Student Full Name *
                                </label>
                                <div class="relative">
                                    <i class="fa-solid fa-user absolute left-3.5 top-3.5 text-slate-400 text-sm"></i>
                                    <input type="text" id="admStudentName" required placeholder="e.g. Rahul Sharma"
                                        class="w-full pl-10 pr-4 py-2.5 bg-slate-900/90 border border-slate-700 rounded-xl text-white text-sm focus:border-rbsGold focus:ring-1 focus:ring-rbsGold outline-none transition">
                                </div>
                            </div>

                            <div>
                                <label class="block text-xs font-bold uppercase tracking-wider text-amber-300 mb-1.5">
                                    Father's Name *
                                </label>
                                <div class="relative">
                                    <i class="fa-solid fa-user-shield absolute left-3.5 top-3.5 text-slate-400 text-sm"></i>
                                    <input type="text" id="admFatherName" required placeholder="e.g. Shri Rajesh Sharma"
                                        class="w-full pl-10 pr-4 py-2.5 bg-slate-900/90 border border-slate-700 rounded-xl text-white text-sm focus:border-rbsGold outline-none transition">
                                </div>
                            </div>

                            <div>
                                <label class="block text-xs font-bold uppercase tracking-wider text-amber-300 mb-1.5">
                                    Mother's Name *
                                </label>
                                <div class="relative">
                                    <i class="fa-solid fa-person-dress absolute left-3.5 top-3.5 text-slate-400 text-sm"></i>
                                    <input type="text" id="admMotherName" required placeholder="e.g. Smt. Sunita Devi"
                                        class="w-full pl-10 pr-4 py-2.5 bg-slate-900/90 border border-slate-700 rounded-xl text-white text-sm focus:border-rbsGold outline-none transition">
                                </div>
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-4 gap-5">
                            <div>
                                <label class="block text-xs font-bold uppercase tracking-wider text-amber-300 mb-1.5">
                                    Class Applying For *
                                </label>
                                <select id="admClass" required class="w-full px-3 py-2.5 bg-slate-900/90 border border-slate-700 rounded-xl text-white text-sm focus:border-rbsGold outline-none transition">
                                    <option value="">Select Class</option>
                                    <option value="Class 6th">Class 6th</option>
                                    <option value="Class 7th">Class 7th</option>
                                    <option value="Class 8th">Class 8th</option>
                                    <option value="Class 9th (UP Board)">Class 9th (UP Board)</option>
                                    <option value="Class 10th (High School)">Class 10th (High School)</option>
                                    <option value="Class 11th (Science Stream)">Class 11th (Science Stream)</option>
                                    <option value="Class 11th (Arts Stream)">Class 11th (Arts Stream)</option>
                                    <option value="Class 11th (Commerce)">Class 11th (Commerce)</option>
                                    <option value="Class 12th (Science Stream)">Class 12th (Science Stream)</option>
                                    <option value="Class 12th (Arts Stream)">Class 12th (Arts Stream)</option>
                                </select>
                            </div>

                            <div>
                                <label class="block text-xs font-bold uppercase tracking-wider text-amber-300 mb-1.5">
                                    Date of Birth *
                                </label>
                                <input type="date" id="admDob" required
                                    class="w-full px-3 py-2.5 bg-slate-900/90 border border-slate-700 rounded-xl text-white text-sm focus:border-rbsGold outline-none transition">
                            </div>

                            <div>
                                <label class="block text-xs font-bold uppercase tracking-wider text-amber-300 mb-1.5">
                                    Gender *
                                </label>
                                <select id="admGender" required class="w-full px-3 py-2.5 bg-slate-900/90 border border-slate-700 rounded-xl text-white text-sm focus:border-rbsGold outline-none transition">
                                    <option value="Male">Male</option>
                                    <option value="Female">Female</option>
                                    <option value="Other">Other</option>
                                </select>
                            </div>

                            <div>
                                <label class="block text-xs font-bold uppercase tracking-wider text-amber-300 mb-1.5">
                                    Hostel Facility Needed? *
                                </label>
                                <select id="admHostel" required class="w-full px-3 py-2.5 bg-amber-500/10 border border-amber-400/40 rounded-xl text-amber-300 text-sm font-semibold focus:border-rbsGold outline-none transition">
                                    <option value="Yes - Hostel Required">Yes - Need Hostel Accommodation</option>
                                    <option value="No - Day Scholar">No - Day Scholar (Local Daily)</option>
                                </select>
                            </div>
                        </div>

                        <div class="grid grid-cols-1 md:grid-cols-2 gap-5">
                            <div>
                                <label class="block text-xs font-bold uppercase tracking-wider text-amber-300 mb-1.5">
                                    Active Mobile / WhatsApp *
                                </label>
                                <div class="relative">
                                    <i class="fa-solid fa-phone absolute left-3.5 top-3.5 text-slate-400 text-sm"></i>
                                    <input type="tel" id="admPhone" required pattern="[0-9]{10}" placeholder="10-digit mobile number"
                                        class="w-full pl-10 pr-4 py-2.5 bg-slate-900/90 border border-slate-700 rounded-xl text-white text-sm focus:border-rbsGold outline-none transition">
                                </div>
                            </div>

                            <div>
                                <label class="block text-xs font-bold uppercase tracking-wider text-amber-300 mb-1.5">
                                    Previous School & Score
                                </label>
                                <div class="relative">
                                    <i class="fa-solid fa-school-flag absolute left-3.5 top-3.5 text-slate-400 text-sm"></i>
                                    <input type="text" id="admPreviousSchool" placeholder="e.g. Middle School Aliganj (83%)"
                                        class="w-full pl-10 pr-4 py-2.5 bg-slate-900/90 border border-slate-700 rounded-xl text-white text-sm focus:border-rbsGold outline-none transition">
                                </div>
                            </div>
                        </div>

                        <div>
                            <label class="block text-xs font-bold uppercase tracking-wider text-amber-300 mb-1.5">
                                Full Address (Village / Town, Post, Tehsil, District, PIN) *
                            </label>
                            <div class="relative">
                                <i class="fa-solid fa-map-location-dot absolute left-3.5 top-3.5 text-slate-400 text-sm"></i>
                                <textarea id="admAddress" rows="2" required placeholder="e.g. Village Bithara, Tehsil Aliganj, Dist Etah - 207247"
                                    class="w-full pl-10 pr-4 py-2.5 bg-slate-900/90 border border-slate-700 rounded-xl text-white text-sm focus:border-rbsGold outline-none transition"></textarea>
                            </div>
                        </div>

                        <div class="flex flex-col sm:flex-row items-center justify-between gap-4 pt-2">
                            <p class="text-xs text-slate-400 flex items-center gap-1.5">
                                <i class="fa-solid fa-lock text-emerald-400"></i> Encrypted application directly routed to college records.
                            </p>
                            <button type="submit" class="w-full sm:w-auto bg-gradient-to-r from-amber-400 via-rbsGold to-amber-600 hover:from-amber-300 hover:to-amber-500 text-rbsNavy font-black px-8 py-3.5 rounded-xl shadow-lg shadow-amber-500/30 transition transform active:scale-95 flex items-center justify-center gap-2">
                                <i class="fa-solid fa-paper-plane"></i>
                                <span>Submit Admission Application</span>
                            </button>
                        </div>
                    </form>
                </div>
            </div>
        </section>

        <!-- College Address and Contact Strip -->
        <section class="py-12 px-4 sm:px-8 bg-rbsNavyDark border-t border-slate-800">
            <div class="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-3 gap-6 text-center sm:text-left">
                <div class="p-6 rounded-2xl bg-rbsNavyCard/40 border border-amber-400/20">
                    <div class="w-12 h-12 rounded-xl bg-amber-500/20 text-amber-400 flex items-center justify-center text-xl mx-auto sm:mx-0 mb-3">
                        <i class="fa-solid fa-location-dot"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white">College Location</h3>
                    <p class="text-slate-300 text-sm mt-1">Rambax Singh Inter College</p>
                    <p class="text-amber-300 text-sm font-semibold">Bithara, Aliganj (Etah) UP</p>
                    <p class="text-slate-400 text-xs mt-1">PIN Code: 207247</p>
                </div>

                <div class="p-6 rounded-2xl bg-rbsNavyCard/40 border border-amber-400/20">
                    <div class="w-12 h-12 rounded-xl bg-amber-500/20 text-amber-400 flex items-center justify-center text-xl mx-auto sm:mx-0 mb-3">
                        <i class="fa-solid fa-phone-volume"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white">Direct Helpline</h3>
                    <p class="text-slate-300 text-sm mt-1">Manager: Vishnu Kant</p>
                    <a href="tel:6395052394" class="text-amber-300 hover:underline text-base font-bold font-mono block mt-1">+91 6395052394</a>
                    <p class="text-slate-400 text-xs mt-1">Director: Avadhesh Singh</p>
                </div>

                <div class="p-6 rounded-2xl bg-rbsNavyCard/40 border border-amber-400/20">
                    <div class="w-12 h-12 rounded-xl bg-amber-500/20 text-amber-400 flex items-center justify-center text-xl mx-auto sm:mx-0 mb-3">
                        <i class="fa-solid fa-envelope-open-text"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white">Official Correspondence</h3>
                    <a href="mailto:rambaxsinghintercollege@gmail.com" class="text-amber-300 hover:underline text-sm break-all font-medium block mt-1">
                        rambaxsinghintercollege@gmail.com
                    </a>
                    <p class="text-slate-400 text-xs mt-2">Affiliation: UP Board & CBSE Pattern with Co-Ed Hostel</p>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-rbsNavy border-t border-amber-500/20 py-8 px-4 sm:px-8 text-xs text-slate-400">
        <div class="max-w-7xl mx-auto flex flex-col md:flex-row items-center justify-between gap-4 text-center md:text-left">
            <div>
                <p class="font-bold text-slate-200 text-sm uppercase">
                    RAMBAX SINGH INTER COLLEGE &bull; BITHARA, ALIGANJ (ETAH - 207247)
                </p>
                <p class="mt-0.5 text-slate-400">
                    Manager: Vishnu Kant (+91 6395052394) &bull; Director: Avadhesh Singh &bull; Co-Ed Residential Campus
                </p>
            </div>
            <div class="flex items-center gap-4">
                <button onclick="openAdminModal()" class="text-amber-400 hover:text-amber-300 font-bold underline flex items-center gap-1">
                    <i class="fa-solid fa-lock text-xs"></i> Admin Portal
                </button>
                <span class="text-slate-600">|</span>
                <span>&copy; 2026 Rambax Singh Inter College</span>
            </div>
        </div>
    </footer>

    <!-- Admin Login Modal -->
    <div id="adminLoginModal" class="fixed inset-0 z-50 flex items-center justify-center p-4 bg-black/85 backdrop-blur-sm hidden">
        <div class="bg-gradient-to-b from-[#0c2347] via-rbsNavy to-rbsNavyDark border-2 border-amber-500/50 rounded-3xl max-w-md w-full p-6 sm:p-8 shadow-2xl relative text-left">
            <button onclick="closeAdminModal()" class="absolute top-4 right-4 text-slate-400 hover:text-white text-lg w-8 h-8 rounded-full bg-slate-800/80 flex items-center justify-center">
                <i class="fa-solid fa-xmark"></i>
            </button>

            <div class="text-center mb-6">
                <div class="w-16 h-16 mx-auto mb-3 rounded-full bg-amber-500/20 border border-amber-400/40 flex items-center justify-center text-amber-400 text-2xl shadow-inner">
                    <i class="fa-solid fa-shield-halved"></i>
                </div>
                <h3 class="text-2xl font-serif font-black text-white">Administrative Portal</h3>
                <p class="text-xs text-amber-300 mt-1">Rambax Singh Inter College &bull; Staff Authentication</p>
            </div>

            <!-- Auto-Fill Shortcut -->
            <div class="mb-5 p-3 rounded-xl bg-amber-500/10 border border-amber-500/30 text-xs text-amber-200 flex items-center justify-between">
                <span><i class="fa-solid fa-key mr-1 text-amber-400"></i> Authorized Credentials</span>
                <button type="button" onclick="fillAdminCredentials()" class="bg-amber-400 hover:bg-amber-300 text-rbsNavy font-black px-2.5 py-1 rounded text-[11px] shadow">
                    Auto-Fill
                </button>
            </div>

            <form id="adminLoginForm" onsubmit="handleAdminLogin(event)" class="space-y-4">
                <div>
                    <label class="block text-xs font-bold uppercase tracking-wider text-slate-300 mb-1">
                        Admin Email
                    </label>
                    <div class="relative">
                        <i class="fa-solid fa-envelope absolute left-3.5 top-3.5 text-slate-400 text-sm"></i>
                        <input type="email" id="adminEmailInput" required placeholder="rambaxsinghintercollege@gmail.com"
                            class="w-full pl-10 pr-4 py-2.5 bg-slate-900/90 border border-slate-700 rounded-xl text-white text-sm focus:border-rbsGold outline-none">
                    </div>
                </div>

                <div>
                    <label class="block text-xs font-bold uppercase tracking-wider text-slate-300 mb-1">
                        Admin Password
                    </label>
                    <div class="relative">
                        <i class="fa-solid fa-lock absolute left-3.5 top-3.5 text-slate-400 text-sm"></i>
                        <input type="password" id="adminPasswordInput" required placeholder="vishnukant@207247"
                            class="w-full pl-10 pr-10 py-2.5 bg-slate-900/90 border border-slate-700 rounded-xl text-white text-sm focus:border-rbsGold outline-none">
                        <button type="button" onclick="togglePasswordVisibility()" class="absolute right-3.5 top-3 text-slate-400 hover:text-white text-sm">
                            <i class="fa-solid fa-eye" id="pwdEyeIcon"></i>
                        </button>
                    </div>
                </div>

                <div id="loginErrorMsg" class="hidden text-xs text-red-400 font-medium bg-red-950/60 p-2.5 rounded-lg border border-red-500/30">
                    Invalid Admin Email or Password! Please verify.
                </div>

                <button type="submit" class="w-full bg-gradient-to-r from-amber-400 via-rbsGold to-amber-600 hover:from-amber-300 hover:to-amber-500 text-rbsNavy font-extrabold py-3 rounded-xl shadow-lg transition mt-2 flex items-center justify-center gap-2">
                    <i class="fa-solid fa-right-to-bracket"></i>
                    <span>Log In to Dashboard</span>
                </button>
            </form>
        </div>
    </div>

    <!-- Full-Screen Admin Dashboard -->
    <div id="adminDashboardModal" class="fixed inset-0 z-50 bg-rbsNavyDark text-slate-100 hidden overflow-y-auto">
        <!-- Dashboard Top Navigation -->
        <div class="sticky top-0 z-20 bg-rbsNavy border-b border-amber-500/30 px-4 sm:px-8 py-3 flex flex-wrap items-center justify-between gap-4 shadow-xl">
            <div class="flex items-center gap-3">
                <div class="w-10 h-10 rounded-full bg-amber-400 text-rbsNavy flex items-center justify-center font-black text-sm">
                    RBS
                </div>
                <div>
                    <h2 class="text-base sm:text-lg font-bold text-white flex items-center gap-2">
                        <span>Admin Control Suite</span>
                        <span class="text-xs bg-emerald-500/20 text-emerald-400 border border-emerald-500/40 px-2 py-0.5 rounded-md font-semibold">Manager Portal</span>
                    </h2>
                    <p class="text-xs text-amber-300">Manager: Vishnu Kant &bull; Contact: +91 6395052394</p>
                </div>
            </div>

            <!-- Tab Switchers -->
            <div class="flex items-center gap-2 bg-slate-900/90 p-1 rounded-xl border border-slate-700">
                <button onclick="switchAdminTab('admissionsTab')" id="tabBtnAdmissions" class="px-4 py-1.5 rounded-lg text-xs sm:text-sm font-bold bg-amber-400 text-rbsNavy transition flex items-center gap-2">
                    <i class="fa-solid fa-users"></i>
                    <span>Admissions (<span id="admissionsBadgeCount">0</span>)</span>
                </button>
                <button onclick="switchAdminTab('marksheetTab')" id="tabBtnMarksheet" class="px-4 py-1.5 rounded-lg text-xs sm:text-sm font-bold text-slate-300 hover:text-white transition flex items-center gap-2">
                    <i class="fa-solid fa-stamp"></i>
                    <span>Marksheet Generator</span>
                </button>
            </div>

            <div class="flex items-center gap-3">
                <button onclick="logoutAdmin()" class="bg-red-500/20 hover:bg-red-500/40 text-red-300 border border-red-500/40 px-3.5 py-1.5 rounded-xl text-xs font-bold transition flex items-center gap-1.5">
                    <i class="fa-solid fa-power-off"></i>
                    <span>Logout</span>
                </button>
            </div>
        </div>

        <div class="max-w-7xl mx-auto p-4 sm:p-6 lg:p-8">
            <!-- TAB 1: Online Admissions Table -->
            <div id="admissionsTab" class="space-y-6">
                <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-4 bg-rbsNavyCard/80 p-5 rounded-2xl border border-amber-500/20">
                    <div>
                        <h3 class="text-xl font-bold text-white flex items-center gap-2">
                            <i class="fa-solid fa-user-graduate text-amber-400"></i>
                            <span>Online Admission Registrations</span>
                        </h3>
                        <p class="text-xs text-slate-400 mt-0.5">Real-time student applications submitted through the public website.</p>
                    </div>

                    <div class="flex flex-wrap items-center gap-3">
                        <div class="relative">
                            <i class="fa-solid fa-magnifying-glass absolute left-3 top-2.5 text-slate-400 text-xs"></i>
                            <input type="text" id="admissionSearchInput" onkeyup="filterAdmissionsTable()" placeholder="Search by student or phone..."
                                class="pl-8 pr-3 py-1.5 rounded-lg bg-slate-900 border border-slate-700 text-xs text-white focus:border-amber-400 outline-none">
                        </div>
                        <button onclick="seedSampleAdmission()" class="text-xs bg-slate-800 hover:bg-slate-700 text-amber-300 px-3 py-1.5 rounded-lg border border-slate-700">
                            + Demo Student
                        </button>
                        <button onclick="clearAllAdmissions()" class="text-xs bg-red-900/40 hover:bg-red-900 text-red-300 px-3 py-1.5 rounded-lg border border-red-700/50">
                            Clear All
                        </button>
                    </div>
                </div>

                <div class="bg-rbsNavyCard/50 rounded-2xl border border-slate-800 overflow-hidden shadow-xl">
                    <div class="overflow-x-auto">
                        <table class="w-full text-left text-xs sm:text-sm">
                            <thead class="bg-[#07172e] text-amber-300 font-bold uppercase text-[11px] tracking-wider border-b border-slate-800">
                                <tr>
                                    <th class="py-3 px-4"># Token</th>
                                    <th class="py-3 px-4">Student & Parents</th>
                                    <th class="py-3 px-4">Class</th>
                                    <th class="py-3 px-4">Hostel?</th>
                                    <th class="py-3 px-4">Mobile & Address</th>
                                    <th class="py-3 px-4">Date</th>
                                    <th class="py-3 px-4 text-right">Actions</th>
                                </tr>
                            </thead>
                            <tbody id="admissionsTableBody" class="divide-y divide-slate-800 text-slate-200">
                                <!-- Rendered dynamically -->
                            </tbody>
                        </table>
                    </div>
                    <div id="noAdmissionsState" class="py-12 text-center hidden">
                        <i class="fa-regular fa-folder-open text-slate-600 text-4xl mb-3"></i>
                        <p class="text-slate-400 text-sm">No applications registered yet.</p>
                    </div>
                </div>
            </div>

            <!-- TAB 2: Marksheet Generator Engine -->
            <div id="marksheetTab" class="hidden space-y-6">
                <div class="bg-gradient-to-r from-rbsNavy via-rbsNavyCard to-rbsNavy p-5 rounded-2xl border border-amber-500/30 flex flex-col md:flex-row items-start md:items-center justify-between gap-4">
                    <div>
                        <h3 class="text-xl font-bold text-white flex items-center gap-2">
                            <i class="fa-solid fa-stamp text-amber-400"></i>
                            <span>Official Marksheet & Academic Report Card Studio</span>
                        </h3>
                        <p class="text-xs text-amber-200/90 mt-1">
                            Generates a strict Board-pattern single-page A4 transcript with RBS seal watermark and 4 official signatures.
                        </p>
                    </div>
                    <div class="flex flex-wrap items-center gap-3">
                        <button onclick="populateSampleMarksheet()" class="bg-slate-900 hover:bg-slate-800 text-amber-300 border border-amber-500/30 text-xs font-bold px-3 py-2 rounded-xl">
                            <i class="fa-solid fa-wand-magic-sparkles mr-1"></i> Load Demo Marks
                        </button>
                        <button onclick="generateAndShowMarksheet()" class="bg-gradient-to-r from-amber-400 to-amber-600 text-rbsNavy font-black text-xs sm:text-sm px-5 py-2 rounded-xl shadow-lg hover:from-amber-300">
                            <i class="fa-solid fa-file-invoice mr-1"></i> Preview 1-Page Marksheet
                        </button>
                    </div>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6">
                    <!-- Left: Form for Student Particulars and Marks -->
                    <div class="lg:col-span-8 bg-rbsNavyCard/80 p-6 rounded-2xl border border-slate-800 space-y-6 shadow-xl">
                        <h4 class="text-sm font-bold uppercase tracking-wider text-amber-400 border-b border-slate-800 pb-2 flex items-center gap-2">
                            <i class="fa-solid fa-id-card"></i> 1. Student Identification & Session Details
                        </h4>

                        <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-4">
                            <div>
                                <label class="block text-xs font-bold text-slate-300 mb-1">Student Full Name *</label>
                                <input type="text" id="msStudentName" placeholder="e.g. Vikas Kumar" value="Vikas Kumar"
                                    class="w-full px-3 py-2 bg-slate-900 border border-slate-700 rounded-lg text-white text-xs sm:text-sm focus:border-amber-400 outline-none">
                            </div>

                            <div>
                                <label class="block text-xs font-bold text-slate-300 mb-1">Father's Name *</label>
                                <input type="text" id="msFatherName" placeholder="e.g. Shri Prem Singh" value="Shri Prem Singh"
                                    class="w-full px-3 py-2 bg-slate-900 border border-slate-700 rounded-lg text-white text-xs sm:text-sm focus:border-amber-400 outline-none">
                            </div>

                            <div>
                                <label class="block text-xs font-bold text-slate-300 mb-1">Mother's Name *</label>
                                <input type="text" id="msMotherName" placeholder="e.g. Smt. Pushpa Devi" value="Smt. Pushpa Devi"
                                    class="w-full px-3 py-2 bg-slate-900 border border-slate-700 rounded-lg text-white text-xs sm:text-sm focus:border-amber-400 outline-none">
                            </div>

                            <div>
                                <label class="block text-xs font-bold text-slate-300 mb-1">Roll Number *</label>
                                <input type="text" id="msRollNo" placeholder="e.g. 20261048" value="20261048"
                                    class="w-full px-3 py-2 bg-slate-900 border border-slate-700 rounded-lg text-white text-xs sm:text-sm font-mono focus:border-amber-400 outline-none">
                            </div>

                            <div>
                                <label class="block text-xs font-bold text-slate-300 mb-1">Class & Section *</label>
                                <select id="msClass" class="w-full px-3 py-2 bg-slate-900 border border-slate-700 rounded-lg text-white text-xs sm:text-sm focus:border-amber-400 outline-none">
                                    <option value="Class 10th (High School) - Sec A">Class 10th (High School) - Sec A</option>
                                    <option value="Class 12th (Intermediate Science)">Class 12th (Intermediate Science)</option>
                                    <option value="Class 12th (Intermediate Arts)">Class 12th (Intermediate Arts)</option>
                                    <option value="Class 11th (Science Stream)">Class 11th (Science Stream)</option>
                                    <option value="Class 9th (Standard)">Class 9th (Standard)</option>
                                    <option value="Class 8th (Junior High)">Class 8th (Junior High)</option>
                                    <option value="Class 7th">Class 7th</option>
                                    <option value="Class 6th">Class 6th</option>
                                </select>
                            </div>

                            <div>
                                <label class="block text-xs font-bold text-slate-300 mb-1">Academic Session *</label>
                                <input type="text" id="msSession" value="2025-2026"
                                    class="w-full px-3 py-2 bg-slate-900 border border-slate-700 rounded-lg text-white text-xs sm:text-sm focus:border-amber-400 outline-none">
                            </div>

                            <div>
                                <label class="block text-xs font-bold text-slate-300 mb-1">Date of Birth</label>
                                <input type="date" id="msDob" value="2009-08-15"
                                    class="w-full px-3 py-2 bg-slate-900 border border-slate-700 rounded-lg text-white text-xs sm:text-sm focus:border-amber-400 outline-none">
                            </div>

                            <div class="sm:col-span-2">
                                <label class="block text-xs font-bold text-slate-300 mb-1">Address / Village *</label>
                                <input type="text" id="msAddress" value="Village Bithara, Post Aliganj, Etah - 207247"
                                    class="w-full px-3 py-2 bg-slate-900 border border-slate-700 rounded-lg text-white text-xs sm:text-sm focus:border-amber-400 outline-none">
                            </div>
                        </div>

                        <!-- Subject Marks Entry Table with Add/Remove option -->
                        <div class="pt-4">
                            <div class="flex items-center justify-between border-b border-slate-800 pb-2 mb-3">
                                <h4 class="text-sm font-bold uppercase tracking-wider text-amber-400 flex items-center gap-2">
                                    <i class="fa-solid fa-table-list"></i> 2. Subject Scores (Auto-Calculating)
                                </h4>
                                <button onclick="addNewSubjectRow()" class="text-xs bg-amber-500/20 text-amber-300 border border-amber-400/40 px-2.5 py-1 rounded-lg hover:bg-amber-500/30">
                                    <i class="fa-solid fa-plus mr-1"></i> Add Subject
                                </button>
                            </div>

                            <div class="overflow-x-auto">
                                <table class="w-full text-left text-xs sm:text-sm">
                                    <thead class="bg-slate-900 text-amber-300 uppercase text-[11px]">
                                        <tr>
                                            <th class="py-2.5 px-3">Subject Name</th>
                                            <th class="py-2.5 px-3 w-24">Max Marks</th>
                                            <th class="py-2.5 px-3 w-24">Theory</th>
                                            <th class="py-2.5 px-3 w-24">Practical / Viva</th>
                                            <th class="py-2.5 px-3 w-20 text-right">Total</th>
                                            <th class="py-2.5 px-3 w-16 text-center">Grade</th>
                                            <th class="py-2.5 px-3 w-12 text-center">Action</th>
                                        </tr>
                                    </thead>
                                    <tbody id="subjectRowsContainer" class="divide-y divide-slate-800">
                                        <!-- Dynamically generated rows -->
                                    </tbody>
                                </table>
                            </div>
                        </div>
                    </div>

                    <!-- Right Column: Auto-Calculated Stats -->
                    <div class="lg:col-span-4 space-y-5">
                        <div class="bg-gradient-to-br from-rbsNavyCard to-rbsNavyDark p-6 rounded-2xl border-2 border-amber-500/40 shadow-2xl relative overflow-hidden">
                            <h4 class="text-xs font-bold uppercase tracking-widest text-amber-400 mb-4 flex items-center gap-2">
                                <i class="fa-solid fa-calculator"></i> Real-time Calculation Summary
                            </h4>

                            <div class="space-y-4">
                                <div class="flex items-center justify-between p-3 rounded-xl bg-slate-900/60 border border-slate-700/60">
                                    <span class="text-xs text-slate-300">Grand Maximum Marks:</span>
                                    <span id="calcMaxMarks" class="text-base font-bold text-white font-mono">600</span>
                                </div>

                                <div class="flex items-center justify-between p-3 rounded-xl bg-slate-900/60 border border-slate-700/60">
                                    <span class="text-xs text-slate-300">Total Marks Obtained:</span>
                                    <span id="calcObtainedMarks" class="text-xl font-black text-amber-400 font-mono">512</span>
                                </div>

                                <div class="flex items-center justify-between p-3 rounded-xl bg-slate-900/60 border border-slate-700/60">
                                    <span class="text-xs text-slate-300">Final Percentage (%):</span>
                                    <span id="calcPercentage" class="text-xl font-black text-emerald-400 font-mono">85.33%</span>
                                </div>

                                <div class="flex items-center justify-between p-3 rounded-xl bg-slate-900/60 border border-slate-700/60">
                                    <span class="text-xs text-slate-300">Overall Grade:</span>
                                    <span id="calcGrade" class="text-base font-extrabold px-3 py-0.5 rounded-full bg-amber-400 text-rbsNavy font-mono">A2</span>
                                </div>

                                <div class="flex items-center justify-between p-3 rounded-xl bg-slate-900/60 border border-slate-700/60">
                                    <span class="text-xs text-slate-300">Division:</span>
                                    <span id="calcDivision" class="text-sm font-bold text-amber-300">FIRST DIVISION</span>
                                </div>

                                <div class="flex items-center justify-between p-3 rounded-xl bg-slate-900/60 border border-slate-700/60">
                                    <span class="text-xs text-slate-300">Academic Status:</span>
                                    <span id="calcResult" class="text-sm font-bold text-emerald-300 uppercase tracking-wider">PASSED (FIRST DIV)</span>
                                </div>
                            </div>

                            <div class="mt-6 pt-4 border-t border-amber-500/20">
                                <button onclick="generateAndShowMarksheet()" class="w-full bg-gradient-to-r from-amber-400 via-rbsGold to-amber-600 hover:from-amber-300 text-rbsNavy font-black py-3 rounded-xl shadow-lg transition flex items-center justify-center gap-2">
                                    <i class="fa-solid fa-eye text-lg"></i>
                                    <span>Preview & Print Single-Page Sheet</span>
                                </button>
                            </div>
                        </div>

                        <!-- 4 Official Signatories Overview -->
                        <div class="bg-rbsNavyCard/70 p-5 rounded-2xl border border-slate-800 text-xs text-slate-300 space-y-2">
                            <h5 class="font-bold text-amber-300 mb-2 flex items-center gap-1.5">
                                <i class="fa-solid fa-file-signature"></i> 4 Authorized Marksheet Signatures
                            </h5>
                            <div class="grid grid-cols-2 gap-2 text-[11px]">
                                <div class="p-2 bg-slate-900/60 rounded border border-slate-800">
                                    <span class="text-slate-400 block">Signatory 1:</span>
                                    <strong class="text-white">Class Teacher</strong>
                                </div>
                                <div class="p-2 bg-slate-900/60 rounded border border-slate-800">
                                    <span class="text-slate-400 block">Signatory 2:</span>
                                    <strong class="text-white">Parent / Guardian</strong>
                                </div>
                                <div class="p-2 bg-slate-900/60 rounded border border-slate-800">
                                    <span class="text-slate-400 block">Signatory 3:</span>
                                    <strong class="text-amber-400">Manager: Vishnu Kant</strong>
                                </div>
                                <div class="p-2 bg-slate-900/60 rounded border border-slate-800">
                                    <span class="text-slate-400 block">Signatory 4:</span>
                                    <strong class="text-white">Principal & Seal</strong>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Official Marksheet Modal Container -->
    <div id="printableCertificateModal" class="fixed inset-0 z-50 bg-black/85 backdrop-blur-md hidden overflow-y-auto p-2 sm:p-4 flex flex-col items-center">
        <!-- Floating toolbar -->
        <div class="w-full max-w-[210mm] flex items-center justify-between bg-slate-900 border border-amber-500/40 px-4 py-2.5 rounded-xl mb-3 text-white shadow-2xl no-print">
            <div class="flex items-center gap-2">
                <span class="w-2.5 h-2.5 rounded-full bg-emerald-400 animate-pulse"></span>
                <span class="text-xs sm:text-sm font-bold text-amber-300">Exact 1-Page A4 Sheet Marksheet</span>
            </div>
            <div class="flex items-center gap-3">
                <button onclick="printSingleMarksheet()" class="bg-emerald-600 hover:bg-emerald-500 text-white font-bold px-4 py-1.5 rounded-lg text-xs sm:text-sm shadow flex items-center gap-2 transition">
                    <i class="fa-solid fa-print"></i>
                    <span>Print 1 Single Page</span>
                </button>
                <button onclick="closeCertificateModal()" class="bg-slate-800 hover:bg-slate-700 text-slate-300 font-bold px-3 py-1.5 rounded-lg text-xs sm:text-sm transition">
                    Close
                </button>
            </div>
        </div>

        <!-- 
            PHYSICAL A4 CONTAINER
            Calibrated strictly to 210mm x 297mm with no-overflow flex layout 
        -->
        <div id="printableMarksheetWrapper" class="w-full max-w-[210mm] bg-white text-slate-900 p-5 rounded-lg shadow-2xl border-4 border-double border-[#051329] relative overflow-hidden select-text text-black">
            
            <!-- Exact Centered Large RBS Crest Watermark with Subtle Opacity -->
            <div class="absolute inset-0 flex items-center justify-center opacity-[0.06] pointer-events-none z-0">
                <div class="w-[150mm] h-[150mm]">
                    <svg class="w-full h-full" viewBox="0 0 200 200" fill="none">
                        <circle cx="100" cy="100" r="96" fill="#000" stroke="#000" stroke-width="4"/>
                        <circle cx="100" cy="100" r="88" stroke="#000" stroke-width="1.8" stroke-dasharray="3 3"/>
                        <circle cx="100" cy="100" r="69" stroke="#000" stroke-width="2.5"/>
                        <path id="watermarkTop" d="M 30,100 A 70,70 0 1,1 170,100" fill="none"/>
                        <text font-family="'Cinzel', Georgia, serif" font-size="16.5" font-weight="900" fill="#000" letter-spacing="3.5">
                            <textPath href="#watermarkTop" startOffset="50%" text-anchor="middle">RBS INTER COLLEGE</textPath>
                        </text>
                        <path id="watermarkBottom" d="M 170,100 A 70,70 0 0,1 30,100" fill="none"/>
                        <text font-family="'Cinzel', Georgia, serif" font-size="14.5" font-weight="800" fill="#000" letter-spacing="3">
                            <textPath href="#watermarkBottom" startOffset="50%" text-anchor="middle">BITHARA ALIGANJ ETAH</textPath>
                        </text>
                        <text x="100" y="94" font-family="'Cinzel', Georgia, serif" font-size="37" font-weight="900" fill="#000" text-anchor="middle">RBS</text>
                        <g transform="translate(73, 104) scale(0.9)" stroke="#000" stroke-width="2.2" fill="none">
                            <path d="M30 25 C18 20 5 21 0 25 L0 5 C5 1 18 0 30 5 Z"/>
                            <path d="M30 25 C42 20 55 21 60 25 L60 5 C55 1 42 0 30 5 Z"/>
                            <line x1="30" y1="5" x2="30" y2="25"/>
                        </g>
                    </svg>
                </div>
            </div>

            <!-- Inner Compact Content Flow -->
            <div class="relative z-10 flex flex-col justify-between h-full">
                
                <!-- TOP HEADER -->
                <div>
                    <!-- School Header -->
                    <div class="border-b-2 border-[#051329] pb-2 flex items-center justify-between gap-3">
                        <!-- Left Official Logo -->
                        <div class="w-16 h-16 sm:w-20 sm:h-20 flex-shrink-0">
                            <svg class="w-full h-full" viewBox="0 0 200 200" fill="none">
                                <circle cx="100" cy="100" r="96" fill="#051329" stroke="#d4af37" stroke-width="4.5"/>
                                <circle cx="100" cy="100" r="88" stroke="#d4af37" stroke-width="1.8" stroke-dasharray="3 3"/>
                                <circle cx="100" cy="100" r="69" stroke="#d4af37" stroke-width="2.5"/>
                                <path id="certTopArc" d="M 30,100 A 70,70 0 1,1 170,100" fill="none"/>
                                <text font-family="'Cinzel', Georgia, serif" font-size="16.5" font-weight="900" fill="#fde68a" letter-spacing="3.5">
                                    <textPath href="#certTopArc" startOffset="50%" text-anchor="middle">RBS INTER COLLEGE</textPath>
                                </text>
                                <path id="certBottomArc" d="M 170,100 A 70,70 0 0,1 30,100" fill="none"/>
                                <text font-family="'Cinzel', Georgia, serif" font-size="14.5" font-weight="800" fill="#fde68a" letter-spacing="3">
                                    <textPath href="#certBottomArc" startOffset="50%" text-anchor="middle">BITHARA ALIGANJ ETAH</textPath>
                                </text>
                                <text x="100" y="94" font-family="'Cinzel', Georgia, serif" font-size="37" font-weight="900" fill="#d4af37" text-anchor="middle">RBS</text>
                                <g transform="translate(73, 104) scale(0.9)" stroke="#d4af37" stroke-width="2.2" fill="none">
                                    <path d="M30 25 C18 20 5 21 0 25 L0 5 C5 1 18 0 30 5 Z" fill="#0a1d3d"/>
                                    <path d="M30 25 C42 20 55 21 60 25 L60 5 C55 1 42 0 30 5 Z" fill="#0a1d3d"/>
                                    <line x1="30" y1="5" x2="30" y2="25"/>
                                </g>
                                <path d="M 48,90 C 45,110 52,130 68,142" stroke="#d4af37" stroke-width="2.5" fill="none"/>
                                <path d="M 152,90 C 155,110 148,130 132,142" stroke="#d4af37" stroke-width="2.5" fill="none"/>
                            </svg>
                        </div>

                        <!-- Center Title Banner -->
                        <div class="text-center flex-1">
                            <span class="text-[9px] uppercase tracking-wider font-extrabold text-[#051329] border border-[#051329] px-2 py-0.5 rounded">
                                U.P. Board & CBSE Pattern &bull; Govt. Recognized Secondary Institution & Hostel
                            </span>
                            <h1 class="text-xl sm:text-2xl font-serif font-black tracking-wide text-[#051329] mt-0.5 uppercase leading-none">
                                RAMBAX SINGH INTER COLLEGE
                            </h1>
                            <p class="text-[11px] font-bold text-slate-800">
                                Bithara, Aliganj, Dist. Etah (Uttar Pradesh) - PIN: 207247
                            </p>
                            <p class="text-[9.5px] text-slate-600">
                                Helpline: +91 6395052394 &bull; Email: rambaxsinghintercollege@gmail.com
                            </p>
                            <div class="mt-1 inline-block bg-[#051329] text-white font-serif font-bold text-[11px] uppercase tracking-wider px-5 py-0.5 rounded">
                                Annual Academic Statement of Marks (Report Card)
                            </div>
                        </div>

                        <!-- Right Serial / Session -->
                        <div class="text-right flex flex-col items-end flex-shrink-0 text-[9.5px] font-mono">
                            <span class="font-bold text-[#051329]">SR. NO: <span id="certSrNo">RBS-2026-1048</span></span>
                            <span>DATE: <span id="certDate">27/09/2026</span></span>
                            <span class="mt-1 border border-slate-400 px-1 py-0.5 font-bold text-[8.5px] bg-slate-50">
                                OFFICIAL COPY
                            </span>
                        </div>
                    </div>

                    <!-- Student Information Grid -->
                    <div class="mt-2 border border-[#051329] rounded p-2 bg-slate-50/70 text-[10.5px]">
                        <div class="grid grid-cols-2 md:grid-cols-4 gap-y-1.5 gap-x-3">
                            <div>
                                <span class="block text-[8.5px] text-slate-500 font-bold uppercase">Student Name:</span>
                                <span id="certStudentName" class="font-bold text-black uppercase">VIKAS KUMAR</span>
                            </div>
                            <div>
                                <span class="block text-[8.5px] text-slate-500 font-bold uppercase">Roll Number:</span>
                                <span id="certRollNo" class="font-bold text-[#051329] font-mono">20261048</span>
                            </div>
                            <div>
                                <span class="block text-[8.5px] text-slate-500 font-bold uppercase">Father's Name:</span>
                                <span id="certFatherName" class="font-bold text-slate-800 uppercase">SHRI PREM SINGH</span>
                            </div>
                            <div>
                                <span class="block text-[8.5px] text-slate-500 font-bold uppercase">Mother's Name:</span>
                                <span id="certMotherName" class="font-bold text-slate-800 uppercase">SMT. PUSHPA DEVI</span>
                            </div>
                            <div>
                                <span class="block text-[8.5px] text-slate-500 font-bold uppercase">Class & Section:</span>
                                <span id="certClass" class="font-bold text-slate-800">Class 10th (High School)</span>
                            </div>
                            <div>
                                <span class="block text-[8.5px] text-slate-500 font-bold uppercase">Academic Session:</span>
                                <span id="certSession" class="font-bold text-slate-800 font-mono">2025-2026</span>
                            </div>
                            <div>
                                <span class="block text-[8.5px] text-slate-500 font-bold uppercase">Date of Birth:</span>
                                <span id="certDob" class="font-bold text-slate-800">15/08/2009</span>
                            </div>
                            <div>
                                <span class="block text-[8.5px] text-slate-500 font-bold uppercase">Address:</span>
                                <span id="certAddress" class="font-semibold text-slate-800 truncate block">Bithara, Aliganj, Etah 207247</span>
                            </div>
                        </div>
                    </div>

                    <!-- Marks Table -->
                    <div class="mt-2">
                        <table class="w-full text-left text-[10px] border border-slate-400">
                            <thead class="bg-[#051329] text-white uppercase text-[9.5px]">
                                <tr>
                                    <th class="py-1.5 px-2 border border-slate-400 text-center w-8">#</th>
                                    <th class="py-1.5 px-2 border border-slate-400">Subject Name</th>
                                    <th class="py-1.5 px-2 border border-slate-400 text-center w-16">Max</th>
                                    <th class="py-1.5 px-2 border border-slate-400 text-center w-16">Theory</th>
                                    <th class="py-1.5 px-2 border border-slate-400 text-center w-16">Prac/Viva</th>
                                    <th class="py-1.5 px-2 border border-slate-400 text-center w-20">Total</th>
                                    <th class="py-1.5 px-2 border border-slate-400 text-center w-14">Grade</th>
                                    <th class="py-1.5 px-2 border border-slate-400 text-center w-20">Remarks</th>
                                </tr>
                            </thead>
                            <tbody id="certMarksTableBody" class="text-slate-900 divide-y divide-slate-300">
                                <!-- Populated dynamically -->
                            </tbody>
                            <tfoot class="bg-slate-100 font-bold text-black border-t-2 border-[#051329]">
                                <tr>
                                    <td colspan="2" class="py-1.5 px-2 text-right uppercase border border-slate-400">Grand Total:</td>
                                    <td id="certFooterMax" class="py-1.5 px-2 text-center border border-slate-400 font-mono">600</td>
                                    <td colspan="2" class="py-1.5 px-2 text-right border border-slate-400 text-[9px] text-slate-600">Total Marks Obtained:</td>
                                    <td id="certFooterObt" class="py-1.5 px-2 text-center border border-slate-400 text-xs font-black text-[#051329] font-mono">512</td>
                                    <td id="certFooterGrade" class="py-1.5 px-2 text-center border border-slate-400 font-black text-emerald-800">A2</td>
                                    <td class="py-1.5 px-2 text-center border border-slate-400 text-[8.5px] font-bold text-emerald-700">EXCELLENT</td>
                                </tr>
                            </tfoot>
                        </table>
                    </div>

                    <!-- Auto Calculation Results Bar -->
                    <div class="mt-2 grid grid-cols-3 gap-2 border-2 border-[#051329] p-2 rounded bg-amber-50/70 text-[10.5px]">
                        <div class="flex items-center gap-1.5">
                            <span class="text-slate-600 font-bold uppercase text-[9px]">Percentage:</span>
                            <span id="certSummaryPercentage" class="text-base font-black text-[#051329]">85.33%</span>
                        </div>
                        <div class="flex items-center gap-1.5 justify-center">
                            <span class="text-slate-600 font-bold uppercase text-[9px]">Division:</span>
                            <span id="certSummaryDivision" class="font-bold text-black">FIRST DIVISION</span>
                        </div>
                        <div class="flex items-center gap-1.5 justify-end">
                            <span class="text-slate-600 font-bold uppercase text-[9px]">Status:</span>
                            <span id="certSummaryResult" class="font-black text-emerald-700 uppercase">PASSED (PASSED)</span>
                        </div>
                    </div>
                </div>

                <!-- BOTTOM SIGNATURE SECTION (Class Teacher, Parent, Manager Vishnu Kant, Principal & Seal) -->
                <div class="pt-3">
                    <div class="grid grid-cols-4 gap-2 text-center">
                        <!-- 1. Class Teacher -->
                        <div class="flex flex-col items-center justify-end">
                            <div class="h-6 flex items-end italic text-slate-500 text-[9.5px]">Verified</div>
                            <div class="w-full border-t border-dashed border-slate-600 pt-1 font-bold text-slate-800 uppercase text-[9.5px]">
                                Class Teacher<br><span class="text-[8px] text-slate-500 font-normal">Signature</span>
                            </div>
                        </div>

                        <!-- 2. Parents / Guardian -->
                        <div class="flex flex-col items-center justify-end">
                            <div class="h-6 flex items-end italic text-slate-500 text-[9.5px]">Acknowledged</div>
                            <div class="w-full border-t border-dashed border-slate-600 pt-1 font-bold text-slate-800 uppercase text-[9.5px]">
                                Parent / Guardian<br><span class="text-[8px] text-slate-500 font-normal">Signature</span>
                            </div>
                        </div>

                        <!-- 3. Manager Vishnu Kant -->
                        <div class="flex flex-col items-center justify-end">
                            <div class="h-6 flex items-end font-serif font-bold text-[#051329] text-[11px]">Vishnu Kant</div>
                            <div class="w-full border-t border-dashed border-slate-600 pt-1 font-bold text-[#051329] uppercase text-[9.5px]">
                                Vishnu Kant<br><span class="text-[8px] text-slate-600 font-semibold">Hon'ble Manager</span>
                            </div>
                        </div>

                        <!-- 4. Principal & Stamp -->
                        <div class="flex flex-col items-center justify-end">
                            <div class="h-6 flex items-end">
                                <span class="text-[8px] font-bold text-emerald-800 border border-emerald-700 px-1 py-0.2 rounded bg-emerald-50">
                                    SEAL & APPROVED
                                </span>
                            </div>
                            <div class="w-full border-t border-dashed border-slate-600 pt-1 font-bold text-slate-800 uppercase text-[9.5px]">
                                Principal Signature<br><span class="text-[8px] text-slate-500 font-normal">With College Seal</span>
                            </div>
                        </div>
                    </div>

                    <!-- Footer Micro Notice -->
                    <div class="mt-2 pt-1 border-t border-slate-300 text-center text-[7.5px] text-slate-500">
                        Official academic transcript issued by Rambax Singh Inter College, Bithara, Aliganj (Etah 207247) UP. Any unauthorized alteration renders this marksheet null and void.
                    </div>
                </div>

            </div>
        </div>
    </div>

    <!-- Toast Notification -->
    <div id="toastNotification" class="fixed bottom-6 right-6 z-50 bg-rbsNavy border-2 border-amber-400 text-white px-5 py-3 rounded-2xl shadow-2xl flex items-center gap-3 transform translate-y-32 opacity-0 transition-all duration-300 max-w-md no-print">
        <div id="toastIcon" class="text-amber-400 text-xl">
            <i class="fa-solid fa-circle-check"></i>
        </div>
        <div>
            <div id="toastTitle" class="font-bold text-sm text-amber-300">Notification</div>
            <div id="toastMessage" class="text-xs text-slate-200">Action completed successfully.</div>
        </div>
    </div>

    <script>
        // Default subjects configured for UP Board / Secondary Curriculum
        let subjectsList = [
            { name: 'General Hindi (सामान्य हिन्दी)', max: 100, theory: 70, practical: 18, remarks: 'Good' },
            { name: 'English (अंग्रेजी)', max: 100, theory: 68, practical: 20, remarks: 'Good' },
            { name: 'Mathematics (गणित)', max: 100, theory: 65, practical: 20, remarks: 'Good' },
            { name: 'Science / Physics (विज्ञान / भौतिक)', max: 100, theory: 62, practical: 28, remarks: 'Excellent' },
            { name: 'Social Science / Chemistry (सामाजिक / रसायन)', max: 100, theory: 69, practical: 19, remarks: 'Good' },
            { name: 'Drawing / Computer / Bio (चित्रकला / कम्प्यूटर)', max: 100, theory: 66, practical: 27, remarks: 'Excellent' }
        ];

        let admissionsList = [];

        window.addEventListener('DOMContentLoaded', () => {
            loadAdmissions();
            renderSubjectRows();
            recalculateMarksheet();
        });

        function toggleMobileNav() {
            const menu = document.getElementById('mobileDrawer');
            menu.classList.toggle('hidden');
        }

        function showToast(title, message, isSuccess = true) {
            const toast = document.getElementById('toastNotification');
            const toastTitle = document.getElementById('toastTitle');
            const toastMessage = document.getElementById('toastMessage');
            const toastIcon = document.getElementById('toastIcon');

            toastTitle.innerText = title;
            toastMessage.innerText = message;
            
            if (isSuccess) {
                toastIcon.innerHTML = '<i class="fa-solid fa-circle-check text-emerald-400"></i>';
                toast.classList.remove('border-red-400');
                toast.classList.add('border-amber-400');
            } else {
                toastIcon.innerHTML = '<i class="fa-solid fa-circle-exclamation text-red-400"></i>';
                toast.classList.remove('border-amber-400');
                toast.classList.add('border-red-400');
            }

            toast.classList.remove('translate-y-32', 'opacity-0');
            setTimeout(() => {
                toast.classList.add('translate-y-32', 'opacity-0');
            }, 3500);
        }

        // ================= ADMISSION LOGIC =================
        function handleAdmissionSubmit(e) {
            e.preventDefault();

            const tokenNumber = 'RBS-' + Math.floor(100000 + Math.random() * 900000);
            const newApplicant = {
                id: Date.now(),
                token: tokenNumber,
                name: document.getElementById('admStudentName').value.trim(),
                fatherName: document.getElementById('admFatherName').value.trim(),
                motherName: document.getElementById('admMotherName').value.trim(),
                classApplied: document.getElementById('admClass').value,
                dob: document.getElementById('admDob').value,
                gender: document.getElementById('admGender').value,
                hostel: document.getElementById('admHostel').value,
                phone: document.getElementById('admPhone').value.trim(),
                previousSchool: document.getElementById('admPreviousSchool').value.trim(),
                address: document.getElementById('admAddress').value.trim(),
                date: new Date().toLocaleDateString('en-IN', { day: '2-digit', month: 'short', year: 'numeric' })
            };

            admissionsList.unshift(newApplicant);
            saveAdmissions();
            renderAdmissionsTable();

            document.getElementById('admissionForm').reset();

            showToast(
                'Admission Submitted!',
                `Application Token: ${tokenNumber}. Forwarded to Manager Vishnu Kant.`,
                true
            );
        }

        function loadAdmissions() {
            const saved = localStorage.getItem('rbs_admissions_db');
            if (saved) {
                try {
                    admissionsList = JSON.parse(saved);
                } catch (err) {
                    admissionsList = [];
                }
            }

            if (!admissionsList || admissionsList.length === 0) {
                seedSampleAdmission(false);
            }
            renderAdmissionsTable();
        }

        function saveAdmissions() {
            localStorage.setItem('rbs_admissions_db', JSON.stringify(admissionsList));
            updateAdmissionsBadge();
        }

        function updateAdmissionsBadge() {
            const badge = document.getElementById('admissionsBadgeCount');
            if (badge) badge.innerText = admissionsList.length;
        }

        function seedSampleAdmission(notify = true) {
            const sample = {
                id: Date.now(),
                token: 'RBS-749214',
                name: 'Shivam Pratap Singh',
                fatherName: 'Ranveer Singh',
                motherName: 'Sarita Devi',
                classApplied: 'Class 10th (High School)',
                dob: '2010-04-12',
                gender: 'Male',
                hostel: 'Yes - Hostel Required',
                phone: '9837123450',
                previousSchool: 'Adarsh Vidya Mandir (82%)',
                address: 'Village Bithara, Aliganj, Etah 207247',
                date: '27 Sep 2026'
            };

            admissionsList.unshift(sample);
            saveAdmissions();
            renderAdmissionsTable();

            if (notify) {
                showToast('Sample Student Added', 'Demo record added to table.', true);
            }
        }

        function clearAllAdmissions() {
            if (window.confirm("Are you sure you want to clear all admissions?")) {
                admissionsList = [];
                saveAdmissions();
                renderAdmissionsTable();
                showToast('Cleared', 'All records cleared.', true);
            }
        }

        function renderAdmissionsTable(list = admissionsList) {
            const tbody = document.getElementById('admissionsTableBody');
            const emptyState = document.getElementById('noAdmissionsState');
            updateAdmissionsBadge();

            if (!tbody) return;

            if (list.length === 0) {
                tbody.innerHTML = '';
                emptyState.classList.remove('hidden');
                return;
            }

            emptyState.classList.add('hidden');
            tbody.innerHTML = list.map((item) => `
                <tr class="hover:bg-slate-800/50 transition">
                    <td class="py-3 px-4 font-mono font-bold text-amber-300">
                        ${item.token}
                    </td>
                    <td class="py-3 px-4">
                        <div class="font-bold text-white">${item.name}</div>
                        <div class="text-[11px] text-slate-400">Father: ${item.fatherName}</div>
                    </td>
                    <td class="py-3 px-4">
                        <span class="px-2 py-0.5 rounded bg-blue-900/60 text-blue-200 border border-blue-700/50 text-xs font-semibold">
                            ${item.classApplied}
                        </span>
                    </td>
                    <td class="py-3 px-4">
                        ${item.hostel.includes('Yes') 
                            ? `<span class="px-2 py-0.5 rounded bg-amber-500/20 text-amber-300 border border-amber-500/40 text-xs font-bold"><i class="fa-solid fa-bed mr-1"></i> Hostel</span>`
                            : `<span class="text-slate-400 text-xs">Day Scholar</span>`
                        }
                    </td>
                    <td class="py-3 px-4">
                        <div class="font-mono text-xs text-amber-200">${item.phone}</div>
                        <div class="text-[11px] text-slate-400 truncate max-w-xs" title="${item.address}">${item.address}</div>
                    </td>
                    <td class="py-3 px-4 text-xs text-slate-400 font-mono">
                        ${item.date}
                    </td>
                    <td class="py-3 px-4 text-right">
                        <div class="flex items-center justify-end gap-1.5">
                            <button onclick="createMarksheetFromAdmission('${item.id}')" title="Generate Marksheet"
                                class="bg-amber-400 hover:bg-amber-300 text-rbsNavy font-bold px-2 py-1 rounded text-xs transition">
                                <i class="fa-solid fa-stamp"></i> Marksheet
                            </button>
                            <button onclick="deleteAdmission('${item.id}')" title="Delete"
                                class="text-slate-400 hover:text-red-400 p-1 text-xs">
                                <i class="fa-solid fa-trash-can"></i>
                            </button>
                        </div>
                    </td>
                </tr>
            `).join('');
        }

        function filterAdmissionsTable() {
            const query = document.getElementById('admissionSearchInput').value.toLowerCase().trim();
            const filtered = admissionsList.filter(item => 
                item.name.toLowerCase().includes(query) ||
                item.fatherName.toLowerCase().includes(query) ||
                item.phone.includes(query) ||
                item.token.toLowerCase().includes(query)
            );
            renderAdmissionsTable(filtered);
        }

        function deleteAdmission(id) {
            admissionsList = admissionsList.filter(item => item.id != id);
            saveAdmissions();
            renderAdmissionsTable();
            showToast('Deleted', 'Entry removed from record.', true);
        }

        function createMarksheetFromAdmission(id) {
            const student = admissionsList.find(item => item.id == id);
            if (!student) return;

            switchAdminTab('marksheetTab');

            document.getElementById('msStudentName').value = student.name;
            document.getElementById('msFatherName').value = student.fatherName;
            document.getElementById('msMotherName').value = student.motherName || 'Smt. Devi';
            document.getElementById('msRollNo').value = '2026' + String(Math.floor(1000 + Math.random() * 9000));
            document.getElementById('msAddress').value = student.address || 'Bithara, Aliganj, Etah';
            if (student.dob) document.getElementById('msDob').value = student.dob;

            recalculateMarksheet();
            showToast('Student Synced', `Loaded ${student.name} into Marksheet Engine!`, true);
        }

        // ================= AUTHENTICATION =================
        const REQUIRED_EMAIL = "rambaxsinghintercollege@gmail.com";
        const REQUIRED_PASS = "vishnukant@207247";

        function openAdminModal() {
            if (sessionStorage.getItem('rbs_admin_logged') === 'true') {
                document.getElementById('adminDashboardModal').classList.remove('hidden');
            } else {
                document.getElementById('adminLoginModal').classList.remove('hidden');
            }
        }

        function closeAdminModal() {
            document.getElementById('adminLoginModal').classList.add('hidden');
        }

        function fillAdminCredentials() {
            document.getElementById('adminEmailInput').value = REQUIRED_EMAIL;
            document.getElementById('adminPasswordInput').value = REQUIRED_PASS;
            showToast('Credentials Filled', 'Email and password entered.', true);
        }

        function togglePasswordVisibility() {
            const pwd = document.getElementById('adminPasswordInput');
            const icon = document.getElementById('pwdEyeIcon');
            if (pwd.type === 'password') {
                pwd.type = 'text';
                icon.classList.remove('fa-eye');
                icon.classList.add('fa-eye-slash');
            } else {
                pwd.type = 'password';
                icon.classList.remove('fa-eye-slash');
                icon.classList.add('fa-eye');
            }
        }

        function handleAdminLogin(e) {
            e.preventDefault();
            const email = document.getElementById('adminEmailInput').value.trim();
            const pass = document.getElementById('adminPasswordInput').value.trim();
            const errBox = document.getElementById('loginErrorMsg');

            if (email === REQUIRED_EMAIL && pass === REQUIRED_PASS) {
                errBox.classList.add('hidden');
                sessionStorage.setItem('rbs_admin_logged', 'true');
                closeAdminModal();
                document.getElementById('adminDashboardModal').classList.remove('hidden');
                showToast('Welcome Manager Vishnu Kant!', 'Admin Control Suite Unlocked.', true);
            } else {
                errBox.classList.remove('hidden');
                showToast('Login Failed', 'Incorrect username or password!', false);
            }
        }

        function logoutAdmin() {
            sessionStorage.removeItem('rbs_admin_logged');
            document.getElementById('adminDashboardModal').classList.add('hidden');
            showToast('Logged Out', 'Admin session terminated safely.', true);
        }

        function switchAdminTab(tabName) {
            const admTab = document.getElementById('admissionsTab');
            const markTab = document.getElementById('marksheetTab');
            const btnAdm = document.getElementById('tabBtnAdmissions');
            const btnMark = document.getElementById('tabBtnMarksheet');

            if (tabName === 'admissionsTab') {
                admTab.classList.remove('hidden');
                markTab.classList.add('hidden');
                btnAdm.className = 'px-4 py-1.5 rounded-lg text-xs sm:text-sm font-bold bg-amber-400 text-rbsNavy transition flex items-center gap-2';
                btnMark.className = 'px-4 py-1.5 rounded-lg text-xs sm:text-sm font-bold text-slate-300 hover:text-white transition flex items-center gap-2';
            } else {
                admTab.classList.add('hidden');
                markTab.classList.remove('hidden');
                btnMark.className = 'px-4 py-1.5 rounded-lg text-xs sm:text-sm font-bold bg-amber-400 text-rbsNavy transition flex items-center gap-2';
                btnAdm.className = 'px-4 py-1.5 rounded-lg text-xs sm:text-sm font-bold text-slate-300 hover:text-white transition flex items-center gap-2';
            }
        }

        // ================= MARKSHEET COMPUTATIONS =================
        function renderSubjectRows() {
            const container = document.getElementById('subjectRowsContainer');
            if (!container) return;

            container.innerHTML = subjectsList.map((sub, i) => `
                <tr class="hover:bg-slate-800/40 transition">
                    <td class="py-2 px-3">
                        <input type="text" id="sub_name_${i}" value="${sub.name}" 
                            class="w-full bg-slate-900/90 border border-slate-700 rounded px-2 py-1 text-white text-xs font-semibold focus:border-amber-400 outline-none">
                    </td>
                    <td class="py-2 px-3">
                        <input type="number" id="sub_max_${i}" value="${sub.max}" min="1" max="200" oninput="recalculateMarksheet()"
                            class="w-full bg-slate-900/90 border border-slate-700 rounded px-2 py-1 text-white text-xs font-mono focus:border-amber-400 outline-none text-center">
                    </td>
                    <td class="py-2 px-3">
                        <input type="number" id="sub_theory_${i}" value="${sub.theory}" min="0" max="100" oninput="recalculateMarksheet()"
                            class="w-full bg-slate-900/90 border border-slate-700 rounded px-2 py-1 text-white text-xs font-mono focus:border-amber-400 outline-none text-center">
                    </td>
                    <td class="py-2 px-3">
                        <input type="number" id="sub_prac_${i}" value="${sub.practical}" min="0" max="100" oninput="recalculateMarksheet()"
                            class="w-full bg-slate-900/90 border border-slate-700 rounded px-2 py-1 text-white text-xs font-mono focus:border-amber-400 outline-none text-center">
                    </td>
                    <td class="py-2 px-3 text-right">
                        <span id="sub_total_display_${i}" class="font-bold text-amber-300 font-mono text-sm">88</span>
                    </td>
                    <td class="py-2 px-3 text-center">
                        <span id="sub_grade_display_${i}" class="font-bold px-2 py-0.5 rounded text-xs bg-slate-800 text-emerald-400 font-mono">A2</span>
                    </td>
                    <td class="py-2 px-3 text-center">
                        <button onclick="removeSubjectRow(${i})" class="text-slate-500 hover:text-red-400 text-xs">
                            <i class="fa-solid fa-trash-can"></i>
                        </button>
                    </td>
                </tr>
            `).join('');
        }

        function addNewSubjectRow() {
            subjectsList.push({ name: 'New Subject', max: 100, theory: 70, practical: 20, remarks: 'Good' });
            renderSubjectRows();
            recalculateMarksheet();
        }

        function removeSubjectRow(index) {
            if (subjectsList.length <= 1) {
                showToast('Action Denied', 'At least 1 subject is required.', false);
                return;
            }
            subjectsList.splice(index, 1);
            renderSubjectRows();
            recalculateMarksheet();
        }

        function calculateGradeLetter(percentage) {
            if (percentage >= 91) return 'A1';
            if (percentage >= 81) return 'A2';
            if (percentage >= 71) return 'B1';
            if (percentage >= 61) return 'B2';
            if (percentage >= 51) return 'C1';
            if (percentage >= 41) return 'C2';
            if (percentage >= 33) return 'D';
            return 'E (Needs Improvement)';
        }

        function recalculateMarksheet() {
            let totalMax = 0;
            let totalObtained = 0;
            let hasCompartment = false;

            subjectsList.forEach((_, i) => {
                const maxEl = document.getElementById(`sub_max_${i}`);
                const theoryEl = document.getElementById(`sub_theory_${i}`);
                const pracEl = document.getElementById(`sub_prac_${i}`);
                const totalDisplay = document.getElementById(`sub_total_display_${i}`);
                const gradeDisplay = document.getElementById(`sub_grade_display_${i}`);

                if (!maxEl || !theoryEl || !pracEl) return;

                const max = parseFloat(maxEl.value) || 100;
                const theory = parseFloat(theoryEl.value) || 0;
                const prac = parseFloat(pracEl.value) || 0;
                const rowTotal = theory + prac;
                const rowPercent = (rowTotal / max) * 100;

                totalMax += max;
                totalObtained += rowTotal;

                if (rowPercent < 33) hasCompartment = true;

                if (totalDisplay) totalDisplay.innerText = rowTotal;
                if (gradeDisplay) {
                    const grade = calculateGradeLetter(rowPercent);
                    gradeDisplay.innerText = grade;
                    if (grade === 'A1' || grade === 'A2') {
                        gradeDisplay.className = 'font-bold px-2 py-0.5 rounded text-xs bg-emerald-950 text-emerald-300 font-mono';
                    } else if (grade.startsWith('E')) {
                        gradeDisplay.className = 'font-bold px-2 py-0.5 rounded text-xs bg-red-950 text-red-300 font-mono';
                    } else {
                        gradeDisplay.className = 'font-bold px-2 py-0.5 rounded text-xs bg-amber-950 text-amber-300 font-mono';
                    }
                }
            });

            const overallPercent = totalMax > 0 ? ((totalObtained / totalMax) * 100).toFixed(2) : 0;
            const overallGrade = calculateGradeLetter(overallPercent);

            let division = "FIRST DIVISION";
            let resultText = "PASSED (FIRST DIVISION)";
            if (hasCompartment) {
                division = "COMPARTMENT";
                resultText = "COMPARTMENT / RE-EXAM";
            } else if (overallPercent >= 75) {
                division = "DISTINCTION / 1ST DIV";
                resultText = "PASSED WITH DISTINCTION";
            } else if (overallPercent >= 60) {
                division = "FIRST DIVISION";
                resultText = "PASSED (FIRST DIVISION)";
            } else if (overallPercent >= 45) {
                division = "SECOND DIVISION";
                resultText = "PASSED (SECOND DIVISION)";
            } else if (overallPercent >= 33) {
                division = "THIRD DIVISION";
                resultText = "PASSED (THIRD DIVISION)";
            } else {
                division = "ESSENTIAL REPEAT";
                resultText = "FAILED / ESSENTIAL REPEAT";
            }

            document.getElementById('calcMaxMarks').innerText = totalMax;
            document.getElementById('calcObtainedMarks').innerText = totalObtained;
            document.getElementById('calcPercentage').innerText = overallPercent + '%';
            document.getElementById('calcGrade').innerText = overallGrade;
            document.getElementById('calcDivision').innerText = division;
            
            const calcResEl = document.getElementById('calcResult');
            calcResEl.innerText = resultText;
            if (resultText.includes('DISTINCTION') || resultText.includes('FIRST')) {
                calcResEl.className = 'text-sm font-bold text-emerald-300 uppercase tracking-wider';
            } else if (resultText.includes('COMPARTMENT') || resultText.includes('FAILED')) {
                calcResEl.className = 'text-sm font-bold text-red-400 uppercase tracking-wider';
            } else {
                calcResEl.className = 'text-sm font-bold text-amber-300 uppercase tracking-wider';
            }
        }

        function populateSampleMarksheet() {
            document.getElementById('msStudentName').value = "Aman Rathore";
            document.getElementById('msFatherName').value = "Shri Dharmendra Rathore";
            document.getElementById('msMotherName').value = "Smt. Shanti Devi";
            document.getElementById('msRollNo').value = "20268819";
            document.getElementById('msAddress').value = "Village Bithara (Aliganj) Etah - 207247";

            const sampleMarks = [
                { t: 74, p: 19 },
                { t: 71, p: 20 },
                { t: 78, p: 19 },
                { t: 68, p: 29 },
                { t: 72, p: 20 },
                { t: 75, p: 20 }
            ];

            sampleMarks.forEach((m, idx) => {
                const tEl = document.getElementById(`sub_theory_${idx}`);
                const pEl = document.getElementById(`sub_prac_${idx}`);
                if (tEl) tEl.value = m.t;
                if (pEl) pEl.value = m.p;
            });

            recalculateMarksheet();
            showToast('Sample Loaded', 'Loaded Aman Rathore marks.', true);
        }

        // ================= SHOW OFFICIAL PRINTABLE CERTIFICATE =================
        function generateAndShowMarksheet() {
            recalculateMarksheet();

            const sName = document.getElementById('msStudentName').value.trim() || 'STUDENT NAME';
            const fName = document.getElementById('msFatherName').value.trim() || 'FATHER NAME';
            const mName = document.getElementById('msMotherName').value.trim() || 'MOTHER NAME';
            const roll = document.getElementById('msRollNo').value.trim() || '20260001';
            const cls = document.getElementById('msClass').value;
            const session = document.getElementById('msSession').value;
            const dob = document.getElementById('msDob').value;
            const addr = document.getElementById('msAddress').value;

            document.getElementById('certStudentName').innerText = sName.toUpperCase();
            document.getElementById('certFatherName').innerText = fName.toUpperCase();
            document.getElementById('certMotherName').innerText = mName.toUpperCase();
            document.getElementById('certRollNo').innerText = roll;
            document.getElementById('certClass').innerText = cls;
            document.getElementById('certSession').innerText = session;
            document.getElementById('certAddress').innerText = addr;
            document.getElementById('certSrNo').innerText = 'RBS-' + roll;
            document.getElementById('certDate').innerText = new Date().toLocaleDateString('en-GB');

            if (dob) {
                const [y, m, d] = dob.split('-');
                document.getElementById('certDob').innerText = `${d}/${m}/${y}`;
            }

            const certTbody = document.getElementById('certMarksTableBody');
            let rowsHtml = '';
            let grandMax = 0;
            let grandObt = 0;

            subjectsList.forEach((_, i) => {
                const name = document.getElementById(`sub_name_${i}`).value;
                const max = parseFloat(document.getElementById(`sub_max_${i}`).value) || 100;
                const theory = parseFloat(document.getElementById(`sub_theory_${i}`).value) || 0;
                const prac = parseFloat(document.getElementById(`sub_prac_${i}`).value) || 0;
                const total = theory + prac;
                const pct = (total / max) * 100;
                const grade = calculateGradeLetter(pct);
                const remark = pct >= 75 ? 'DISTINCTION' : (pct >= 60 ? 'VERY GOOD' : (pct >= 45 ? 'SATISFACTORY' : 'PASS'));

                grandMax += max;
                grandObt += total;

                rowsHtml += `
                    <tr class="hover:bg-slate-50 transition">
                        <td class="py-1 px-2 border border-slate-400 text-center font-mono font-bold">${i + 1}</td>
                        <td class="py-1 px-2 border border-slate-400 font-semibold">${name}</td>
                        <td class="py-1 px-2 border border-slate-400 text-center font-mono">${max}</td>
                        <td class="py-1 px-2 border border-slate-400 text-center font-mono">${theory}</td>
                        <td class="py-1 px-2 border border-slate-400 text-center font-mono">${prac}</td>
                        <td class="py-1 px-2 border border-slate-400 text-center font-mono font-bold text-[#051329]">${total}</td>
                        <td class="py-1 px-2 border border-slate-400 text-center font-bold text-slate-800">${grade}</td>
                        <td class="py-1 px-2 border border-slate-400 text-center text-[8.5px] font-semibold text-slate-600">${remark}</td>
                    </tr>
                `;
            });

            certTbody.innerHTML = rowsHtml;

            const overallPct = ((grandObt / grandMax) * 100).toFixed(2);
            document.getElementById('certFooterMax').innerText = grandMax;
            document.getElementById('certFooterObt').innerText = grandObt;
            document.getElementById('certFooterGrade').innerText = calculateGradeLetter(overallPct);
            document.getElementById('certSummaryPercentage').innerText = overallPct + '%';

            let division = "FIRST DIVISION";
            let resStatus = "PASSED (PASSED)";
            if (overallPct < 33) {
                division = "ESSENTIAL REPEAT";
                resStatus = "NEEDS RE-APPEAR";
            } else if (overallPct < 45) {
                division = "THIRD DIVISION";
                resStatus = "PASSED";
            } else if (overallPct < 60) {
                division = "SECOND DIVISION";
                resStatus = "PASSED";
            } else if (overallPct >= 75) {
                division = "FIRST DIVISION (WITH HONORS)";
                resStatus = "PASSED (DISTINCTION)";
            }

            document.getElementById('certSummaryDivision').innerText = division.toUpperCase();
            document.getElementById('certSummaryResult').innerText = resStatus;

            document.getElementById('printableCertificateModal').classList.remove('hidden');
        }

        function closeCertificateModal() {
            document.getElementById('printableCertificateModal').classList.add('hidden');
        }

        function printSingleMarksheet() {
            window.print();
        }
    </script>
</body>
</html>
