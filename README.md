<!DOCTYPE html>
<html lang="hi" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>RAM BAX SINGH INTER COLLEGE | Bithara, Aliganj (Etah - 207247)</title>

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- Google Fonts: Cinzel Decorative, Plus Jakarta Sans, Tiro Devanagari Hindi -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@700;800;900&family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&family=Tiro+Devanagari+Hindi&display=swap" rel="stylesheet">
  
  <!-- Font Awesome 6 Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" />

  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            rbs: {
              navy: '#06162d',
              navyLight: '#0d284f',
              gold: '#d4af37',
              goldLight: '#f6e27a',
              goldDark: '#aa820a',
              emerald: '#064e3b',
              emeraldLight: '#047857',
              cream: '#fdfbf7'
            }
          },
          fontFamily: {
            title: ['Cinzel', 'serif'],
            sans: ['"Plus Jakarta Sans"', 'sans-serif'],
            hindi: ['"Tiro Devanagari Hindi"', 'serif']
          },
          boxShadow: {
            'glow-gold': '0 0 25px rgba(212, 175, 55, 0.45)'
          }
        }
      }
    }
  </script>

  <style>
    @media print {
      body * { visibility: hidden !important; }
      #printableReportCard, #printableReportCard * { visibility: visible !important; }
      #printableReportCard {
        position: absolute !important;
        left: 0 !important;
        top: 0 !important;
        width: 100% !important;
        margin: 0 !important;
        padding: 24px !important;
        background: #ffffff !important;
        box-shadow: none !important;
        border: 4px double #06162d !important;
      }
      .no-print { display: none !important; }
    }

    .hero-title-shadow {
      text-shadow: 0 2px 4px rgba(0, 0, 0, 0.9), 0 0 20px rgba(246, 226, 122, 0.7), 0 0 35px rgba(212, 175, 55, 0.5);
    }

    .watermark-seal {
      background-image: url('image_a45465.jpg');
      background-repeat: no-repeat;
      background-position: center;
      background-size: 320px;
    }

    @keyframes marqueeMove {
      0% { transform: translateX(100%); }
      100% { transform: translateX(-100%); }
    }
    .ticker-scroll {
      display: inline-block;
      white-space: nowrap;
      animation: marqueeMove 32s linear infinite;
    }
    .ticker-scroll:hover {
      animation-play-state: paused;
    }

    @keyframes slideProgressBar {
      0% { width: 0%; }
      100% { width: 100%; }
    }
    .animate-progress-fill {
      animation: slideProgressBar 4.5s linear infinite;
    }
  </style>
</head>

<body class="bg-slate-50 text-slate-800 font-sans antialiased selection:bg-rbs-gold selection:text-rbs-navy min-h-screen flex flex-col">

  <!-- TOP HELPLINE & STATS STRIP -->
  <div class="bg-rbs-navy text-white text-xs border-b border-rbs-gold/30 py-2 px-4 sticky top-0 z-50 shadow-md">
    <div class="max-w-7xl mx-auto flex flex-wrap justify-between items-center gap-3">
      <div class="flex items-center gap-4 flex-wrap">
        <span class="inline-flex items-center gap-1.5 text-rbs-goldLight font-bold">
          <i class="fa-solid fa-graduation-cap"></i> U.P. Board Recognized &bull; Class 1st to 12th
        </span>
        <span class="hidden md:inline text-slate-500">|</span>
        <span class="inline-flex items-center gap-1.5 text-emerald-300 font-semibold">
          <i class="fa-solid fa-bed"></i> Residential Hostel Facility Available
        </span>
        <span class="hidden lg:inline text-slate-500">|</span>
        <span class="text-slate-300 hidden sm:inline">
          <i class="fa-solid fa-location-dot text-rbs-gold mr-1"></i> Bithara (Aliganj, Etah - 207247)
        </span>
      </div>

      <div class="flex items-center gap-3 text-xs">
        <a href="tel:6395052394" class="text-white hover:text-rbs-goldLight font-bold transition flex items-center gap-1">
          <i class="fa-solid fa-phone-volume text-rbs-gold"></i> Helpline: <span class="tracking-wide">6395052394</span>
        </a>
        <span class="text-slate-500">|</span>
        <button onclick="openAdminModal()" class="bg-gradient-to-r from-rbs-goldDark to-rbs-gold hover:from-rbs-gold hover:to-rbs-goldLight text-rbs-navy font-black px-3 py-1 rounded shadow transition flex items-center gap-1.5">
          <i class="fa-solid fa-shield-halved"></i> Admin Portal
        </button>
      </div>
    </div>
  </div>

  <!-- INSTITUTIONAL DPS-STYLE BRANDING BAR -->
  <header class="bg-white border-b-4 border-rbs-gold shadow-lg sticky top-8 z-40">
    <div class="max-w-7xl mx-auto px-4 py-3 sm:py-4 flex flex-col md:flex-row justify-between items-center gap-4">
      
      <!-- Logo + School Name Highlight -->
      <a href="#" class="flex items-center gap-3 sm:gap-5 group text-center md:text-left">
        <div class="relative shrink-0">
          <div class="w-20 h-20 sm:w-24 sm:h-24 rounded-full p-1 bg-gradient-to-tr from-rbs-goldDark via-rbs-goldLight to-rbs-gold shadow-glow-gold">
            <img 
              src="image_a45465.jpg" 
              alt="Ram Bax Singh Inter College Emblem" 
              class="w-full h-full object-contain rounded-full bg-rbs-navy p-0.5 transition-transform group-hover:scale-105 duration-300"
              onerror="this.onerror=null; this.src='https://placehold.co/200x200/06162d/d4af37?text=RBS+LOGO';"
            />
          </div>
          <span class="absolute -bottom-1 -right-1 bg-emerald-600 text-white text-[9px] font-extrabold uppercase px-2 py-0.5 rounded-full border border-white shadow">
            Est. 2005
          </span>
        </div>

        <div>
          <!-- Highlighting Badge -->
          <div class="inline-flex items-center gap-2 bg-gradient-to-r from-rbs-navy via-rbs-navyLight to-rbs-navy text-rbs-goldLight text-[10px] sm:text-xs font-black uppercase px-3 py-1 rounded-full border border-rbs-gold/60 shadow-sm mb-1">
            <i class="fa-solid fa-star text-rbs-gold"></i>
            <span>Premier Residential Institution &bull; U.P. Board Recognized</span>
          </div>

          <!-- Highlighted High-Impact Name -->
          <h1 class="font-title font-black text-2xl sm:text-3xl lg:text-4xl text-rbs-navy tracking-tight uppercase leading-none drop-shadow-sm">
            RAM BAX SINGH INTER COLLEGE
          </h1>

          <div class="flex flex-wrap items-center justify-center md:justify-start gap-2 mt-1.5 text-xs sm:text-sm font-semibold">
            <span class="text-emerald-800 uppercase tracking-wider font-extrabold">R.B.S. INTER COLLEGE</span>
            <span class="text-slate-300">•</span>
            <span class="text-slate-600">Class 1st to 12th (Arts & Science)</span>
            <span class="text-slate-300 hidden sm:inline">•</span>
            <span class="text-amber-700 font-bold hidden sm:inline">Residential Hostel</span>
          </div>

          <p class="text-[11px] sm:text-xs text-slate-500 font-medium mt-0.5">
            <i class="fa-solid fa-map-pin text-rbs-goldDark mr-1"></i> Bithara - Sarai Road, Aliganj, Dist. Etah (U.P.) - 207247
          </p>
        </div>
      </a>

      <!-- Quick Actions -->
      <div class="flex items-center gap-2.5 shrink-0">
        <a href="#admission-form-sec" class="bg-gradient-to-r from-emerald-700 to-emerald-800 hover:from-emerald-800 hover:to-emerald-900 text-white font-extrabold px-4 sm:px-5 py-2.5 rounded-xl text-xs sm:text-sm shadow-md hover:shadow-lg transition flex items-center gap-2 border border-emerald-500/50">
          <i class="fa-solid fa-file-pen text-rbs-goldLight"></i>
          <span>Admission 2026-27</span>
        </a>
        <a href="https://wa.me/916395052394?text=Namaste%20Manager%20Vishnu%20Kant%20Ji,%20Ram%20Bax%20Singh%20Inter%20College%20me%20admission%20aur%20hostel%20ki%20jankari%20chahiye." target="_blank" class="bg-emerald-500 hover:bg-emerald-600 text-white font-bold px-3.5 py-2.5 rounded-xl text-xs sm:text-sm shadow transition flex items-center gap-1.5">
          <i class="fa-brands fa-whatsapp text-lg"></i>
          <span class="hidden sm:inline">WhatsApp</span>
        </a>
      </div>
    </div>

    <!-- Navigation Strip -->
    <nav class="bg-rbs-navy text-white text-xs font-bold uppercase tracking-wider border-t border-rbs-gold/30">
      <div class="max-w-7xl mx-auto px-4 flex items-center justify-between overflow-x-auto whitespace-nowrap">
        <div class="flex items-center space-x-1 py-1">
          <a href="#carousel-section" class="px-3.5 py-2 rounded hover:bg-rbs-gold hover:text-rbs-navy transition flex items-center gap-1.5 text-rbs-goldLight">
            <i class="fa-solid fa-house"></i> Home
          </a>
          <a href="#leadership-desk" class="px-3.5 py-2 rounded hover:bg-rbs-gold hover:text-rbs-navy transition flex items-center gap-1.5">
            <i class="fa-solid fa-users-line"></i> Leadership Desk
          </a>
          <a href="#classes-section" class="px-3.5 py-2 rounded hover:bg-rbs-gold hover:text-rbs-navy transition flex items-center gap-1.5">
            <i class="fa-solid fa-book-open"></i> Class 1st to 12th
          </a>
          <a href="#hostel-section" class="px-3.5 py-2 rounded hover:bg-rbs-gold hover:text-rbs-navy transition flex items-center gap-1.5">
            <i class="fa-solid fa-hotel"></i> Hostel Facility
          </a>
          <a href="#admission-form-sec" class="px-3.5 py-2 rounded hover:bg-rbs-gold hover:text-rbs-navy transition flex items-center gap-1.5 text-rbs-goldLight">
            <i class="fa-solid fa-user-plus"></i> Online Admission
          </a>
          <a href="#contact-footer" class="px-3.5 py-2 rounded hover:bg-rbs-gold hover:text-rbs-navy transition flex items-center gap-1.5">
            <i class="fa-solid fa-address-book"></i> Contact
          </a>
        </div>
        <div class="hidden lg:flex items-center gap-2 text-slate-300 text-xs py-1">
          <i class="fa-solid fa-shield-heart text-rbs-gold"></i>
          <span>Residential Boarding & Discipline</span>
        </div>
      </div>
    </nav>
  </header>

  <!-- FLASH TICKER -->
  <div class="bg-gradient-to-r from-amber-500 via-amber-400 to-amber-500 text-rbs-navy font-bold text-xs py-1.5 px-4 shadow-sm border-b border-amber-600 flex items-center overflow-hidden">
    <div class="max-w-7xl mx-auto w-full flex items-center">
      <span class="bg-rbs-navy text-rbs-goldLight px-3 py-0.5 rounded text-[11px] font-black uppercase shrink-0 flex items-center gap-1.5 mr-3 shadow">
        <i class="fa-solid fa-bell animate-bounce"></i> Notice
      </span>
      <div class="overflow-hidden w-full relative">
        <div class="ticker-scroll">
          🌟 <strong>Admissions Open 2026-27:</strong> Ram Bax Singh Inter College (Class 1 to 12) &bull;
          🏠 <strong>Residential Hostel Available:</strong> 24x7 security, RO drinking water, power generator backup & wholesome vegetarian mess &bull;
          🥇 <strong>Merit Awards:</strong> Congratulations to all students awarded in Republic Day & Annual felicitation ceremonies &bull;
          📞 <strong>Manager Helpline:</strong> Contact Manager <strong>Mr. Vishnu Kant</strong> at <strong>+91 6395052394</strong>.
        </div>
      </div>
    </div>
  </div>

  <!-- HERO SLIDER SECTION (DPS-STYLE AUTO SLIDER WITH ALL REAL CAMPUS PHOTOS) -->
  <section id="carousel-section" class="relative bg-rbs-navy overflow-hidden">
    <div class="relative w-full h-[380px] sm:h-[480px] md:h-[580px] lg:h-[620px] select-none" id="dpsSlider">
      
      <!-- Slide Items Container -->
      <div id="slidesContainer" class="relative w-full h-full">
        
        <!-- Slide 1: Courtyard Campus (rbs5.jpeg) -->
        <div class="slide absolute inset-0 transition-opacity duration-1000 ease-in-out opacity-100 z-20">
          <img src="rbs5.jpeg" alt="Ram Bax Singh Inter College Courtyard" class="w-full h-full object-cover" onerror="this.onerror=null; this.src='https://placehold.co/1400x700/06162d/ffffff?text=RBS+Campus+Courtyard';" />
          <div class="absolute inset-0 bg-gradient-to-t from-rbs-navy via-rbs-navy/40 to-transparent"></div>
          <div class="absolute bottom-10 left-6 sm:left-14 right-6 sm:right-14 text-white max-w-3xl">
            <span class="bg-rbs-gold text-rbs-navy font-black text-xs uppercase px-3 py-1 rounded-md shadow">Lush Green Campus</span>
            <h2 class="font-title text-2xl sm:text-4xl lg:text-5xl font-extrabold mt-2 text-white hero-title-shadow">
              Ram Bax Singh Inter College, Bithara
            </h2>
            <p class="text-xs sm:text-base text-slate-200 mt-2 font-medium">
              Spacious classrooms, tree-lined courtyards, paved pathways, and serene environment for Class 1st to 12th education.
            </p>
          </div>
        </div>

        <!-- Slide 2: Assembly & Tricolor Rally (rbs4.jpeg) -->
        <div class="slide absolute inset-0 transition-opacity duration-1000 ease-in-out opacity-0 z-10">
          <img src="rbs4.jpeg" alt="Morning Assembly & National Pride" class="w-full h-full object-cover" onerror="this.onerror=null; this.src='https://placehold.co/1400x700/06162d/ffffff?text=Morning+Assembly';" />
          <div class="absolute inset-0 bg-gradient-to-t from-rbs-navy via-rbs-navy/40 to-transparent"></div>
          <div class="absolute bottom-10 left-6 sm:left-14 right-6 sm:right-14 text-white max-w-3xl">
            <span class="bg-red-600 text-white font-black text-xs uppercase px-3 py-1 rounded-md shadow">Patriotic Spirit</span>
            <h2 class="font-title text-2xl sm:text-4xl lg:text-5xl font-extrabold mt-2 text-white hero-title-shadow">
              Morning Assembly & Character Building
            </h2>
            <p class="text-xs sm:text-base text-slate-200 mt-2 font-medium">
              Daily prayer gatherings, patriotic celebrations, and disciplined moral culture for all students.
            </p>
          </div>
        </div>

        <!-- Slide 3: Classroom Mentorship (rbs12.jpeg) -->
        <div class="slide absolute inset-0 transition-opacity duration-1000 ease-in-out opacity-0 z-10">
          <img src="rbs12.jpeg" alt="Manager Vishnu Kant In Class" class="w-full h-full object-cover" onerror="this.onerror=null; this.src='https://placehold.co/1400x700/06162d/ffffff?text=Academic+Mentorship';" />
          <div class="absolute inset-0 bg-gradient-to-t from-rbs-navy via-rbs-navy/40 to-transparent"></div>
          <div class="absolute bottom-10 left-6 sm:left-14 right-6 sm:right-14 text-white max-w-3xl">
            <span class="bg-amber-500 text-rbs-navy font-black text-xs uppercase px-3 py-1 rounded-md shadow">Academic Excellence</span>
            <h2 class="font-title text-2xl sm:text-4xl lg:text-5xl font-extrabold mt-2 text-white hero-title-shadow">
              Personal Attention & Student Encouragement
            </h2>
            <p class="text-xs sm:text-base text-slate-200 mt-2 font-medium">
              Manager Vishnu Kant and teachers directly interact and motivate students in every classroom.
            </p>
          </div>
        </div>

        <!-- Slide 4: Cultural Celebration (rbs10.jpeg) -->
        <div class="slide absolute inset-0 transition-opacity duration-1000 ease-in-out opacity-0 z-10">
          <img src="rbs10.jpeg" alt="Cultural Dance & Drama" class="w-full h-full object-cover" onerror="this.onerror=null; this.src='https://placehold.co/1400x700/06162d/ffffff?text=Cultural+Utsav';" />
          <div class="absolute inset-0 bg-gradient-to-t from-rbs-navy via-rbs-navy/40 to-transparent"></div>
          <div class="absolute bottom-10 left-6 sm:left-14 right-6 sm:right-14 text-white max-w-3xl">
            <span class="bg-purple-600 text-white font-black text-xs uppercase px-3 py-1 rounded-md shadow">Cultural Heritage</span>
            <h2 class="font-title text-2xl sm:text-4xl lg:text-5xl font-extrabold mt-2 text-white hero-title-shadow">
              Sanskritik Utsav & Drama Presentations
            </h2>
            <p class="text-xs sm:text-base text-slate-200 mt-2 font-medium">
              Encouraging students to participate in performing arts, historical plays, and national festivities.
            </p>
          </div>
        </div>

        <!-- Slide 5: Merit Honors (rbs8.jpeg) -->
        <div class="slide absolute inset-0 transition-opacity duration-1000 ease-in-out opacity-0 z-10">
          <img src="rbs8.jpeg" alt="Republic Day Merit Certificates" class="w-full h-full object-cover" onerror="this.onerror=null; this.src='https://placehold.co/1400x700/06162d/ffffff?text=Merit+Certificates';" />
          <div class="absolute inset-0 bg-gradient-to-t from-rbs-navy via-rbs-navy/40 to-transparent"></div>
          <div class="absolute bottom-10 left-6 sm:left-14 right-6 sm:right-14 text-white max-w-3xl">
            <span class="bg-emerald-600 text-white font-black text-xs uppercase px-3 py-1 rounded-md shadow">Merit & Recognition</span>
            <h2 class="font-title text-2xl sm:text-4xl lg:text-5xl font-extrabold mt-2 text-white hero-title-shadow">
              Annual Pratibha Samman & Awards
            </h2>
            <p class="text-xs sm:text-base text-slate-200 mt-2 font-medium">
              Felicitation ceremonies recognizing top scorers in board examinations and co-curriculars.
            </p>
          </div>
        </div>

        <!-- Slide 6: Senior Board Lecture (rbs7.jpeg) -->
        <div class="slide absolute inset-0 transition-opacity duration-1000 ease-in-out opacity-0 z-10">
          <img src="rbs7.jpeg" alt="Interactive Classroom" class="w-full h-full object-cover" onerror="this.onerror=null; this.src='https://placehold.co/1400x700/06162d/ffffff?text=Senior+Classes';" />
          <div class="absolute inset-0 bg-gradient-to-t from-rbs-navy via-rbs-navy/40 to-transparent"></div>
          <div class="absolute bottom-10 left-6 sm:left-14 right-6 sm:right-14 text-white max-w-3xl">
            <span class="bg-blue-600 text-white font-black text-xs uppercase px-3 py-1 rounded-md shadow">High School & Intermediate</span>
            <h2 class="font-title text-2xl sm:text-4xl lg:text-5xl font-extrabold mt-2 text-white hero-title-shadow">
              Focused Board Exam Preparation
            </h2>
            <p class="text-xs sm:text-base text-slate-200 mt-2 font-medium">
              Experienced teachers delivering daily structured concept lectures for Class 10th & 12th students.
            </p>
          </div>
        </div>

      </div>

      <!-- Navigation Arrows -->
      <button onclick="prevSlide()" aria-label="Previous slide" class="absolute top-1/2 left-4 -translate-y-1/2 z-30 bg-black/40 hover:bg-rbs-gold text-white hover:text-rbs-navy w-11 h-11 rounded-full flex items-center justify-center transition shadow-lg border border-white/20">
        <i class="fa-solid fa-chevron-left text-sm"></i>
      </button>
      <button onclick="nextSlide()" aria-label="Next slide" class="absolute top-1/2 right-4 -translate-y-1/2 z-30 bg-black/40 hover:bg-rbs-gold text-white hover:text-rbs-navy w-11 h-11 rounded-full flex items-center justify-center transition shadow-lg border border-white/20">
        <i class="fa-solid fa-chevron-right text-sm"></i>
      </button>

      <!-- Carousel Progress Bar & Controls -->
      <div class="absolute bottom-3 inset-x-0 z-30 flex items-center justify-between px-6 sm:px-14">
        <!-- Dots Container -->
        <div id="sliderDotsContainer" class="flex items-center space-x-2"></div>

        <!-- Play / Pause Button -->
        <button id="playPauseBtn" onclick="toggleSliderPlay()" class="bg-black/50 hover:bg-black/80 text-white text-xs px-3 py-1 rounded-full border border-white/20 flex items-center gap-1.5 transition">
          <i class="fa-solid fa-pause text-[10px]"></i>
          <span>Auto</span>
        </button>
      </div>

      <!-- Linear Progress Line -->
      <div class="absolute top-0 inset-x-0 h-1 bg-white/20 z-30">
        <div id="sliderProgressBar" class="h-full bg-gradient-to-r from-rbs-gold via-rbs-goldLight to-rbs-gold animate-progress-fill"></div>
      </div>
    </div>
  </section>

  <!-- LEADERSHIP & EXECUTIVE DESK -->
  <section id="leadership-desk" class="py-16 bg-white border-b border-slate-200">
    <div class="max-w-7xl mx-auto px-4">
      
      <div class="text-center max-w-3xl mx-auto mb-12">
        <span class="bg-amber-100 text-rbs-goldDark text-xs font-black uppercase px-3.5 py-1 rounded-full border border-amber-300">
          Executive Leadership & Patronage
        </span>
        <h2 class="font-title text-3xl sm:text-4xl font-extrabold text-rbs-navy mt-2.5">
          From the Director & Manager's Desk
        </h2>
        <div class="w-24 h-1.5 bg-gradient-to-r from-rbs-goldDark via-rbs-gold to-rbs-goldLight mx-auto mt-3 rounded-full"></div>
      </div>

      <!-- Dual Leadership Cards: Director & Manager -->
      <div class="grid md:grid-cols-2 gap-8 mb-10">
        
        <!-- Leader 1: Director Avadhesh Singh -->
        <div class="bg-gradient-to-br from-slate-50 via-amber-50/20 to-white rounded-3xl p-6 sm:p-8 border-2 border-rbs-gold/40 shadow-lg flex flex-col justify-between">
          <div>
            <div class="flex items-center gap-4 mb-4">
              <div class="w-16 h-16 rounded-full bg-rbs-navy p-1 border-2 border-rbs-gold shrink-0 flex items-center justify-center text-rbs-goldLight shadow-md">
                <i class="fa-solid fa-user-tie text-2xl"></i>
              </div>
              <div>
                <span class="bg-emerald-100 text-emerald-800 text-[10px] font-black uppercase px-2.5 py-0.5 rounded-full border border-emerald-300">
                  Patron & Director
                </span>
                <h3 class="font-title text-xl sm:text-2xl font-black text-rbs-navy mt-1">Shri Avadhesh Singh</h3>
                <p class="text-xs font-bold text-amber-800 uppercase tracking-wide">Director (Nideshak)</p>
              </div>
            </div>
            <p class="text-slate-600 text-xs sm:text-sm leading-relaxed mb-4">
              "Hamara uddeshya gramin kshetr ke chhatra-chhatraon ko rashtriya star ki unchi shiksha aur sanskar dena hai taaki wo har kshetra me aage badhein aur vidyalaya v parivar ka naam roshan karein."
            </p>
          </div>
          <div class="pt-4 border-t border-slate-200 flex items-center justify-between text-xs text-slate-500 font-medium">
            <span><i class="fa-solid fa-school text-rbs-gold mr-1.5"></i> RBS Inter College, Bithara</span>
            <span class="text-emerald-700 font-bold"><i class="fa-solid fa-circle-check mr-1"></i> Executive Directorship</span>
          </div>
        </div>

        <!-- Leader 2: Manager Vishnu Kant -->
        <div class="bg-gradient-to-br from-slate-50 via-blue-50/20 to-white rounded-3xl p-6 sm:p-8 border-2 border-rbs-navy/20 shadow-lg flex flex-col justify-between">
          <div>
            <div class="flex items-center gap-4 mb-4">
              <div class="w-16 h-16 rounded-full overflow-hidden border-2 border-rbs-gold shrink-0 shadow-md">
                <img 
                  src="vishnu kant_2.jpg" 
                  alt="Manager Vishnu Kant" 
                  class="w-full h-full object-cover object-top"
                  onerror="this.onerror=null; this.src='https://placehold.co/200x200/06162d/d4af37?text=Vishnu+Kant';"
                />
              </div>
              <div>
                <span class="bg-rbs-navy text-rbs-goldLight text-[10px] font-black uppercase px-2.5 py-0.5 rounded-full border border-rbs-gold">
                  Manager & Administrator
                </span>
                <h3 class="font-title text-xl sm:text-2xl font-black text-rbs-navy mt-1">Shri Vishnu Kant</h3>
                <p class="text-xs font-bold text-amber-800 uppercase tracking-wide">Manager (Prabandhak)</p>
              </div>
            </div>
            <p class="text-slate-600 text-xs sm:text-sm leading-relaxed mb-4">
              "Chhatron ke sarvangin vikas hetu Class 1st se 12th tak smart learning, board preparation aur door-draj ke bacchon ke liye disciplined 24x7 residential hostel suvidha hamari prathmikta hai."
            </p>
          </div>
          <div class="pt-4 border-t border-slate-200 flex flex-wrap items-center justify-between gap-2 text-xs">
            <a href="tel:6395052394" class="text-rbs-navy font-bold hover:text-amber-800 inline-flex items-center gap-1.5">
              <i class="fa-solid fa-phone text-rbs-gold"></i> Helpline: 6395052394
            </a>
            <a href="https://wa.me/916395052394" target="_blank" class="text-emerald-700 font-bold hover:underline inline-flex items-center gap-1">
              <i class="fa-brands fa-whatsapp text-sm"></i> WhatsApp Helpline
            </a>
          </div>
        </div>

      </div>

      <!-- Institutional Highlights -->
      <div class="grid grid-cols-2 sm:grid-cols-4 gap-4 pt-2">
        <div class="bg-slate-50 p-4 rounded-2xl border border-slate-200 text-center shadow-sm">
          <i class="fa-solid fa-chalkboard-user text-rbs-navy text-2xl mb-1.5"></i>
          <h4 class="text-xs font-bold text-slate-800">Class 1 to 12</h4>
          <p class="text-[10px] text-slate-500">Comprehensive Primary to Inter</p>
        </div>
        <div class="bg-slate-50 p-4 rounded-2xl border border-slate-200 text-center shadow-sm">
          <i class="fa-solid fa-bed text-emerald-600 text-2xl mb-1.5"></i>
          <h4 class="text-xs font-bold text-slate-800">Hostel Facility</h4>
          <p class="text-[10px] text-slate-500">Safe Residential Campus</p>
        </div>
        <div class="bg-slate-50 p-4 rounded-2xl border border-slate-200 text-center shadow-sm">
          <i class="fa-solid fa-award text-amber-500 text-2xl mb-1.5"></i>
          <h4 class="text-xs font-bold text-slate-800">U.P. Board</h4>
          <p class="text-[10px] text-slate-500">Recognized & Accredited</p>
        </div>
        <div class="bg-slate-50 p-4 rounded-2xl border border-slate-200 text-center shadow-sm">
          <i class="fa-solid fa-microscope text-blue-600 text-2xl mb-1.5"></i>
          <h4 class="text-xs font-bold text-slate-800">Science & Arts Labs</h4>
          <p class="text-[10px] text-slate-500">Modern Practical Wings</p>
        </div>
      </div>

    </div>
  </section>

  <!-- CLASS 1 TO 12TH ACADEMIC WINGS -->
  <section id="classes-section" class="py-16 bg-slate-100 border-b border-slate-200">
    <div class="max-w-7xl mx-auto px-4">
      <div class="text-center max-w-3xl mx-auto mb-12">
        <span class="bg-emerald-100 text-emerald-800 text-xs font-black uppercase px-3.5 py-1 rounded-full border border-emerald-300">
          Curriculum & Academic Wings
        </span>
        <h2 class="font-title text-3xl font-extrabold text-rbs-navy mt-2.5">
          Class 1st to 12th Comprehensive Education
        </h2>
        <p class="text-xs sm:text-sm text-slate-600 mt-2">
          Structured learning stages designed to build foundational skills, analytical thinking, and high board exam scores.
        </p>
        <div class="w-20 h-1 bg-rbs-gold mx-auto mt-3 rounded-full"></div>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <!-- Wing 1: Primary Section -->
        <div class="bg-white rounded-2xl p-6 shadow-md border border-slate-200 hover:shadow-xl transition-all">
          <div class="w-12 h-12 rounded-xl bg-amber-100 text-amber-800 flex items-center justify-center text-xl mb-4 font-bold">
            <i class="fa-solid fa-shapes"></i>
          </div>
          <span class="text-xs font-bold text-amber-700 uppercase tracking-wider">Foundation Stage</span>
          <h3 class="font-title text-lg font-bold text-rbs-navy mt-1">Primary Wing (Class 1 to 5)</h3>
          <p class="text-xs text-slate-600 mt-2 leading-relaxed">
            Strong foundation in Hindi, English, Mathematics, General Knowledge, and arts. Focus on neat handwriting, mental arithmetic, and moral discipline.
          </p>
          <ul class="mt-4 space-y-1.5 text-xs text-slate-700">
            <li><i class="fa-solid fa-circle-check text-emerald-600 mr-1.5"></i> Activity-based interactive learning</li>
            <li><i class="fa-solid fa-circle-check text-emerald-600 mr-1.5"></i> Individual student care and guidance</li>
            <li><i class="fa-solid fa-circle-check text-emerald-600 mr-1.5"></i> Regular parent-teacher interactions</li>
          </ul>
        </div>

        <!-- Wing 2: Middle & High School -->
        <div class="bg-white rounded-2xl p-6 shadow-md border-2 border-rbs-gold/50 hover:shadow-xl transition-all relative">
          <span class="absolute top-4 right-4 bg-rbs-navy text-rbs-goldLight text-[10px] font-black uppercase px-2.5 py-0.5 rounded shadow">
            Core Board Focus
          </span>
          <div class="w-12 h-12 rounded-xl bg-blue-100 text-rbs-navy flex items-center justify-center text-xl mb-4 font-bold">
            <i class="fa-solid fa-book-bookmark"></i>
          </div>
          <span class="text-xs font-bold text-blue-700 uppercase tracking-wider">Secondary Stage</span>
          <h3 class="font-title text-lg font-bold text-rbs-navy mt-1">Class 6th to 10th (High School)</h3>
          <p class="text-xs text-slate-600 mt-2 leading-relaxed">
            Comprehensive syllabus coverage for U.P. Board High School exams with Science (Physics, Chemistry, Biology), Math, Social Science, Hindi & English.
          </p>
          <ul class="mt-4 space-y-1.5 text-xs text-slate-700">
            <li><i class="fa-solid fa-circle-check text-emerald-600 mr-1.5"></i> Periodic test series & question bank solving</li>
            <li><i class="fa-solid fa-circle-check text-emerald-600 mr-1.5"></i> Practical science demonstration classes</li>
            <li><i class="fa-solid fa-circle-check text-emerald-600 mr-1.5"></i> Remedial classes for slow learners</li>
          </ul>
        </div>

        <!-- Wing 3: Intermediate College -->
        <div class="bg-white rounded-2xl p-6 shadow-md border border-slate-200 hover:shadow-xl transition-all">
          <div class="w-12 h-12 rounded-xl bg-emerald-100 text-emerald-800 flex items-center justify-center text-xl mb-4 font-bold">
            <i class="fa-solid fa-atom"></i>
          </div>
          <span class="text-xs font-bold text-emerald-700 uppercase tracking-wider">Senior Secondary</span>
          <h3 class="font-title text-lg font-bold text-rbs-navy mt-1">Class 11th & 12th (Inter College)</h3>
          <p class="text-xs text-slate-600 mt-2 leading-relaxed">
            Specialized streams in <strong>Science (PCM / PCB)</strong> and <strong>Humanities / Arts</strong> with practical labs, board guidance, and competitive exam readiness.
          </p>
          <ul class="mt-4 space-y-1.5 text-xs text-slate-700">
            <li><i class="fa-solid fa-circle-check text-emerald-600 mr-1.5"></i> Science stream (Physics, Chem, Biology, Math)</li>
            <li><i class="fa-solid fa-circle-check text-emerald-600 mr-1.5"></i> Arts stream (History, Civics, Geography, Hindi, Eng)</li>
            <li><i class="fa-solid fa-circle-check text-emerald-600 mr-1.5"></i> Board exam mock assessments</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- HOSTEL & RESIDENTIAL FACILITIES -->
  <section id="hostel-section" class="py-16 bg-gradient-to-br from-rbs-navy via-rbs-navyLight to-slate-900 text-white relative overflow-hidden">
    <div class="max-w-7xl mx-auto px-4 relative z-10">
      
      <div class="text-center max-w-3xl mx-auto mb-12">
        <span class="bg-emerald-500/20 text-emerald-300 text-xs font-bold uppercase px-3 py-1 rounded-full border border-emerald-500/40">
          Boarding & Residential Living
        </span>
        <h2 class="font-title text-3xl sm:text-4xl font-extrabold text-white mt-2">
          RBS Residential Hostel Facility
        </h2>
        <p class="text-xs sm:text-sm text-slate-300 mt-2">
          Secure, disciplined, and comfortable boarding environment tailored for focused academic study.
        </p>
        <div class="w-20 h-1 bg-rbs-gold mx-auto mt-3 rounded-full"></div>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
        <div class="bg-white/10 rounded-2xl p-6 border border-white/10 backdrop-blur-sm hover:border-rbs-gold transition">
          <div class="w-12 h-12 rounded-xl bg-rbs-gold/20 text-rbs-goldLight flex items-center justify-center text-xl mb-4 font-bold">
            <i class="fa-solid fa-shield-halved"></i>
          </div>
          <h4 class="font-bold text-base text-white">24x7 Security & Wardens</h4>
          <p class="text-xs text-slate-300 mt-2 leading-relaxed">
            High boundary walls, CCTV surveillance, and resident faculty wardens ensuring complete safety and discipline at all times.
          </p>
        </div>

        <div class="bg-white/10 rounded-2xl p-6 border border-white/10 backdrop-blur-sm hover:border-rbs-gold transition">
          <div class="w-12 h-12 rounded-xl bg-rbs-gold/20 text-rbs-goldLight flex items-center justify-center text-xl mb-4 font-bold">
            <i class="fa-solid fa-utensils"></i>
          </div>
          <h4 class="font-bold text-base text-white">Hygienic Mess & RO Water</h4>
          <p class="text-xs text-slate-300 mt-2 leading-relaxed">
            Freshly prepared, balanced vegetarian meals three times daily plus evening snacks, with certified RO drinking water systems.
          </p>
        </div>

        <div class="bg-white/10 rounded-2xl p-6 border border-white/10 backdrop-blur-sm hover:border-rbs-gold transition">
          <div class="w-12 h-12 rounded-xl bg-rbs-gold/20 text-rbs-goldLight flex items-center justify-center text-xl mb-4 font-bold">
            <i class="fa-solid fa-clock"></i>
          </div>
          <h4 class="font-bold text-base text-white">Supervised Self-Study Hours</h4>
          <p class="text-xs text-slate-300 mt-2 leading-relaxed">
            Dedicated 3-hour evening study hall supervised by subject teachers to resolve homework doubts and complete daily revision.
          </p>
        </div>

        <div class="bg-white/10 rounded-2xl p-6 border border-white/10 backdrop-blur-sm hover:border-rbs-gold transition">
          <div class="w-12 h-12 rounded-xl bg-rbs-gold/20 text-rbs-goldLight flex items-center justify-center text-xl mb-4 font-bold">
            <i class="fa-solid fa-bolt"></i>
          </div>
          <h4 class="font-bold text-base text-white">Power Backup & Medical</h4>
          <p class="text-xs text-slate-300 mt-2 leading-relaxed">
            Generator and inverter backup ensuring uninterrupted lighting and fans, along with emergency first-aid and medical care.
          </p>
        </div>
      </div>

      <!-- Quick Hostel Booking Card -->
      <div class="mt-10 bg-white/5 border border-rbs-gold/40 rounded-3xl p-6 sm:p-8 flex flex-col md:flex-row items-center justify-between gap-6 shadow-2xl">
        <div class="space-y-1 text-center md:text-left">
          <span class="text-xs font-black text-rbs-gold uppercase tracking-wider">Hostel Admissions Open</span>
          <h3 class="font-title text-xl sm:text-2xl font-bold text-white">Reserve a Hostel Seat for Session 2026-27</h3>
          <p class="text-xs text-slate-300">Limited seats available. Selection on academic interview and guardian verification.</p>
        </div>
        <div class="flex items-center gap-3 shrink-0">
          <a href="tel:6395052394" class="bg-rbs-gold hover:bg-rbs-goldLight text-rbs-navy font-black px-6 py-3 rounded-xl text-xs sm:text-sm shadow-lg transition">
            <i class="fa-solid fa-phone mr-1.5"></i> Call Hostel Desk: 6395052394
          </a>
        </div>
      </div>
    </div>
  </section>

  <!-- ONLINE ADMISSION REGISTRATION FORM -->
  <section id="admission-form-sec" class="py-16 bg-slate-50 border-b border-slate-200">
    <div class="max-w-4xl mx-auto px-4">
      <div class="text-center max-w-2xl mx-auto mb-10">
        <span class="bg-rbs-navy text-rbs-goldLight text-xs font-black uppercase px-3 py-1 rounded-full border border-rbs-gold">
          Session 2026 - 2027 Admissions
        </span>
        <h2 class="font-title text-3xl font-extrabold text-rbs-navy mt-2">
          Online Student Admission Form
        </h2>
        <p class="text-xs sm:text-sm text-slate-600 mt-1">
          Apply online for Class 1st to 12th. Forms are immediately accessible in the Admin Dashboard.
        </p>
        <div class="w-16 h-1 bg-rbs-gold mx-auto mt-2.5 rounded-full"></div>
      </div>

      <div class="bg-white border-2 border-rbs-gold/30 rounded-3xl p-6 sm:p-10 shadow-2xl relative">
        <form id="onlineAdmissionForm" onsubmit="handleAdmissionSubmit(event)" class="space-y-5">
          
          <div class="border-b pb-3 flex items-center justify-between">
            <h3 class="text-sm font-bold text-rbs-navy flex items-center gap-2 uppercase tracking-wide">
              <i class="fa-solid fa-address-card text-rbs-goldDark"></i> Student & Guardian Information
            </h3>
            <span class="text-xs text-slate-500 font-medium">* Required fields</span>
          </div>

          <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-4">
            <!-- Student Name -->
            <div>
              <label class="block text-xs font-bold text-slate-700 uppercase mb-1">Student Full Name *</label>
              <input type="text" id="admStudentName" required placeholder="e.g. Aman Pratap Singh" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 focus:outline-none focus:ring-2 focus:ring-rbs-navy text-sm" />
            </div>

            <!-- Father's Name -->
            <div>
              <label class="block text-xs font-bold text-slate-700 uppercase mb-1">Father's Name *</label>
              <input type="text" id="admFatherName" required placeholder="e.g. Mr. Rajendra Singh" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 focus:outline-none focus:ring-2 focus:ring-rbs-navy text-sm" />
            </div>

            <!-- Mother's Name -->
            <div>
              <label class="block text-xs font-bold text-slate-700 uppercase mb-1">Mother's Name</label>
              <input type="text" id="admMotherName" placeholder="e.g. Mrs. Sunita Devi" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 focus:outline-none focus:ring-2 focus:ring-rbs-navy text-sm" />
            </div>

            <!-- Class Selection -->
            <div>
              <label class="block text-xs font-bold text-slate-700 uppercase mb-1">Seeking Admission in Class *</label>
              <select id="admClass" required class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 focus:outline-none focus:ring-2 focus:ring-rbs-navy text-sm font-semibold">
                <option value="">-- Select Class --</option>
                <option value="Class 1st">Class 1st</option>
                <option value="Class 2nd">Class 2nd</option>
                <option value="Class 3rd">Class 3rd</option>
                <option value="Class 4th">Class 4th</option>
                <option value="Class 5th">Class 5th</option>
                <option value="Class 6th">Class 6th</option>
                <option value="Class 7th">Class 7th</option>
                <option value="Class 8th">Class 8th</option>
                <option value="Class 9th">Class 9th</option>
                <option value="Class 10th (High School)">Class 10th (High School)</option>
                <option value="Class 11th (Science PCM/PCB)">Class 11th (Science Stream)</option>
                <option value="Class 11th (Arts)">Class 11th (Arts Stream)</option>
                <option value="Class 12th (Science PCM/PCB)">Class 12th (Science Stream)</option>
                <option value="Class 12th (Arts)">Class 12th (Arts Stream)</option>
              </select>
            </div>

            <!-- Date of Birth -->
            <div>
              <label class="block text-xs font-bold text-slate-700 uppercase mb-1">Date of Birth *</label>
              <input type="date" id="admDOB" required class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 focus:outline-none focus:ring-2 focus:ring-rbs-navy text-sm" />
            </div>

            <!-- Contact Number -->
            <div>
              <label class="block text-xs font-bold text-slate-700 uppercase mb-1">Guardian Mobile No. *</label>
              <input type="tel" id="admMobile" required pattern="[0-9]{10}" placeholder="10-digit Mobile" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 focus:outline-none focus:ring-2 focus:ring-rbs-navy text-sm" />
            </div>

            <!-- Hostel Option -->
            <div class="sm:col-span-2 md:col-span-1">
              <label class="block text-xs font-bold text-amber-900 uppercase mb-1">Hostel Accommodation *</label>
              <select id="admHostel" required class="w-full px-3.5 py-2.5 rounded-xl border-2 border-rbs-gold focus:outline-none focus:ring-2 focus:ring-rbs-navy bg-amber-50 text-sm font-bold text-amber-950">
                <option value="Yes - Hostel Required">Yes - Need Hostel / Boarding</option>
                <option value="No - Day Scholar" selected>No - Day Scholar</option>
              </select>
            </div>

            <!-- Previous School -->
            <div class="sm:col-span-2 md:col-span-2">
              <label class="block text-xs font-bold text-slate-700 uppercase mb-1">Previous School & Last Class Score (%)</label>
              <input type="text" id="admPrevSchool" placeholder="e.g. Previous School Aliganj (82%)" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 focus:outline-none focus:ring-2 focus:ring-rbs-navy text-sm" />
            </div>
          </div>

          <!-- Full Address -->
          <div>
            <label class="block text-xs font-bold text-slate-700 uppercase mb-1">Full Village / Town Address (With Pincode) *</label>
            <textarea id="admAddress" required rows="2" placeholder="e.g. Village Bithara, Post Sarai, Tehsil Aliganj, Etah - 207247" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 focus:outline-none focus:ring-2 focus:ring-rbs-navy text-sm"></textarea>
          </div>

          <!-- Submission Button -->
          <div class="pt-2 flex flex-col sm:flex-row items-center justify-between gap-4">
            <p class="text-xs text-slate-500">
              Submitted details are encrypted and securely synchronized with the college admin portal.
            </p>
            <button type="submit" class="w-full sm:w-auto bg-rbs-navy hover:bg-rbs-navyLight text-rbs-goldLight font-extrabold px-8 py-3.5 rounded-xl shadow-lg transition flex items-center justify-center gap-2 border border-rbs-gold/40">
              <i class="fa-solid fa-paper-plane text-rbs-gold"></i> Submit Admission Form
            </button>
          </div>
        </form>

        <!-- Dynamic Success Receipt -->
        <div id="admSuccessReceipt" class="hidden mt-6 bg-gradient-to-r from-amber-50 via-emerald-50 to-white border-2 border-emerald-500 rounded-2xl p-5 text-slate-800 shadow-md">
          <div class="flex items-start gap-4">
            <img src="image_a45465.jpg" alt="RBS Logo" class="w-14 h-14 rounded-full border-2 border-rbs-gold shadow shrink-0 bg-white" />
            <div class="flex-1">
              <div class="flex flex-wrap items-center justify-between gap-2">
                <h4 class="font-title text-base font-bold text-rbs-navy">Application Registered Successfully!</h4>
                <span class="font-mono text-xs bg-white px-2.5 py-1 rounded border border-emerald-300 font-extrabold text-emerald-800" id="receiptRegId">RBS-2026-000</span>
              </div>
              <p class="text-xs text-slate-600 mt-1" id="receiptSummaryText"></p>
              
              <div class="mt-4 flex flex-wrap gap-2.5">
                <button onclick="window.print()" class="bg-rbs-navy hover:bg-rbs-navyLight text-white text-xs px-4 py-2 rounded-lg font-bold flex items-center gap-1.5 shadow">
                  <i class="fa-solid fa-print text-rbs-gold"></i> Print Slip
                </button>
                <a href="tel:6395052394" class="bg-emerald-600 hover:bg-emerald-700 text-white text-xs px-4 py-2 rounded-lg font-bold flex items-center gap-1.5 shadow">
                  <i class="fa-solid fa-phone"></i> Call Manager: 6395052394
                </a>
              </div>
            </div>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- FOOTER SECTION -->
  <footer id="contact-footer" class="bg-rbs-navy text-slate-300 pt-14 pb-8 border-t-4 border-rbs-gold">
    <div class="max-w-7xl mx-auto px-4 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 mb-10 text-xs">
      
      <!-- Col 1: Identity -->
      <div>
        <div class="flex items-center gap-3 mb-3">
          <img src="image_a45465.jpg" alt="RBS Seal" class="w-12 h-12 rounded-full border border-rbs-gold bg-white p-0.5 shadow" />
          <div>
            <h4 class="font-title font-bold text-white text-sm">RAM BAX SINGH INTER COLLEGE</h4>
            <p class="text-[11px] text-rbs-goldLight">R.B.S. Inter College &bull; Bithara</p>
          </div>
        </div>
        <p class="text-slate-400 leading-relaxed">
          Premier educational institution recognized by U.P. Board providing quality education from Class 1st to 12th, high-tech science laboratories, and round-the-clock hostel facilities in Aliganj, Etah.
        </p>
      </div>

      <!-- Col 2: Institutional Particulars -->
      <div>
        <h4 class="font-title font-bold text-white mb-3 text-xs uppercase tracking-wider text-rbs-goldLight border-b border-white/10 pb-1.5">
          Institution Details
        </h4>
        <ul class="space-y-2 text-slate-300">
          <li><strong>School Name:</strong> RAM BAX SINGH INTER COLLEGE (R.B.S.)</li>
          <li><strong>Affiliation:</strong> U.P. Board (Secondary & Intermediate)</li>
          <li><strong>Director:</strong> Shri Avadhesh Singh</li>
          <li><strong>Manager:</strong> Shri Vishnu Kant</li>
          <li><strong>Helpline:</strong> <a href="tel:6395052394" class="text-rbs-gold hover:underline font-bold">6395052394</a></li>
          <li><strong>Location:</strong> Bithara (Aliganj, Etah - 207247, U.P.)</li>
        </ul>
      </div>

      <!-- Col 3: Quick Navigation -->
      <div>
        <h4 class="font-title font-bold text-white mb-3 text-xs uppercase tracking-wider text-rbs-goldLight border-b border-white/10 pb-1.5">
          Campus Features
        </h4>
        <ul class="space-y-1.5 text-slate-300">
          <li>&bull; Residential Hostel for Boys & Girls</li>
          <li>&bull; Monitored Night Prep Study Halls</li>
          <li>&bull; Physics, Chemistry, Biology & IT Labs</li>
          <li>&bull; Sports Ground & Annual Republic Day Parades</li>
          <li>&bull; Transport & Day-Boarding Available</li>
        </ul>
      </div>

      <!-- Col 4: Admin Login Portal -->
      <div class="bg-white/5 p-5 rounded-2xl border border-rbs-gold/30">
        <h4 class="font-bold text-white text-xs uppercase tracking-wider mb-1.5 flex items-center gap-1.5">
          <i class="fa-solid fa-lock text-rbs-gold"></i> Staff & Admin Access
        </h4>
        <p class="text-slate-400 text-[11px] mb-3">
          Manage admission forms and generate autocalculated marksheets for students.
        </p>
        <button onclick="openAdminModal()" class="w-full bg-gradient-to-r from-rbs-gold to-rbs-goldLight hover:from-rbs-goldLight hover:to-rbs-gold text-rbs-navy font-black text-xs py-2.5 rounded-xl shadow flex items-center justify-center gap-1.5 transition">
          <i class="fa-solid fa-gauge"></i> Open Admin Portal
        </button>
      </div>

    </div>

    <div class="max-w-7xl mx-auto px-4 pt-6 border-t border-white/10 text-center text-xs text-slate-400 flex flex-col sm:flex-row justify-between items-center gap-3">
      <p>&copy; 2026 RAM BAX SINGH INTER COLLEGE, Bithara (Aliganj, Etah - 207247). All Rights Reserved.</p>
      <p class="text-rbs-goldLight font-bold">Director: Avadhesh Singh &bull; Manager: Vishnu Kant (+91 6395052394)</p>
    </div>
  </footer>

  <!-- ADMIN AUTHENTICATION MODAL -->
  <div id="adminAuthModal" class="fixed inset-0 bg-black/80 backdrop-blur-sm z-50 flex items-center justify-center p-4 hidden">
    <div class="bg-white rounded-3xl max-w-md w-full p-6 sm:p-8 shadow-2xl border-4 border-rbs-navy relative animate-fade-in">
      <button onclick="closeAdminModal()" aria-label="Close modal" class="absolute top-4 right-4 text-slate-400 hover:text-slate-700 text-lg">
        <i class="fa-solid fa-xmark"></i>
      </button>

      <div class="text-center mb-6">
        <img src="image_a45465.jpg" alt="RBS Seal" class="w-16 h-16 rounded-full border-2 border-rbs-gold mx-auto mb-2 bg-rbs-navy p-0.5 shadow" />
        <h3 class="font-title text-xl font-bold text-rbs-navy">RBS Admin Workspace</h3>
        <p class="text-xs text-slate-500">Ram Bax Singh Inter College &bull; Bithara</p>
      </div>

      <form onsubmit="handleAdminLogin(event)" class="space-y-4 text-xs">
        <div>
          <label class="block font-bold text-slate-700 uppercase mb-1">Admin Email / ID</label>
          <input 
            type="email" 
            id="adminEmailInput" 
            required 
            placeholder="rambaxsinghintercollege@gmail.com" 
            class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 focus:outline-none focus:ring-2 focus:ring-rbs-navy text-xs sm:text-sm font-medium" 
          />
        </div>
        <div>
          <label class="block font-bold text-slate-700 uppercase mb-1">Password</label>
          <input 
            type="password" 
            id="adminPassInput" 
            required 
            placeholder="vishnukant@207247" 
            class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 focus:outline-none focus:ring-2 focus:ring-rbs-navy text-xs sm:text-sm" 
          />
        </div>

        <!-- Quick 1-click test credential helper -->
        <div class="bg-slate-50 p-2.5 rounded-xl border border-slate-200 flex items-center justify-between">
          <span class="text-slate-600">Testing credentials?</span>
          <button type="button" onclick="autoFillAdminCredentials()" class="text-amber-800 font-bold hover:underline">
            Auto-Fill Credentials
          </button>
        </div>

        <div id="adminAuthError" class="hidden p-2.5 rounded-xl bg-red-50 border border-red-200 text-red-600 font-bold text-xs">
          Invalid credentials! Please use registered email and password.
        </div>

        <div class="pt-2 flex gap-3">
          <button type="button" onclick="closeAdminModal()" class="w-1/2 py-2.5 border border-slate-300 rounded-xl font-semibold text-slate-700 hover:bg-slate-100">
            Cancel
          </button>
          <button type="submit" class="w-1/2 bg-rbs-navy hover:bg-rbs-navyLight text-rbs-goldLight font-extrabold py-2.5 rounded-xl shadow border border-rbs-gold/40">
            Sign In
          </button>
        </div>
      </form>
    </div>
  </div>

  <!-- ADMIN MANAGEMENT FULL WORKSPACE MODAL -->
  <div id="adminWorkspaceModal" class="fixed inset-0 bg-slate-900/90 backdrop-blur-md z-50 flex overflow-y-auto hidden">
    <div class="bg-slate-100 min-h-screen w-full flex flex-col">
      
      <!-- Admin Workspace Header Bar -->
      <header class="bg-rbs-navy text-white px-6 py-4 flex flex-wrap justify-between items-center gap-4 border-b-2 border-rbs-gold sticky top-0 z-30">
        <div class="flex items-center gap-3">
          <img src="image_a45465.jpg" alt="RBS Seal" class="w-10 h-10 rounded-full border border-rbs-gold bg-white p-0.5" />
          <div>
            <h2 class="font-title text-base sm:text-lg font-bold">RAM BAX SINGH INTER COLLEGE &bull; ADMIN CONTROL</h2>
            <p class="text-[11px] text-rbs-goldLight">Director: Avadhesh Singh | Manager: Vishnu Kant | ID: rambaxsinghintercollege@gmail.com</p>
          </div>
        </div>

        <div class="flex items-center gap-2.5">
          <button onclick="switchAdminTab('admissions')" id="tabBtnAdmissions" class="px-3.5 py-1.5 rounded-xl text-xs font-black bg-rbs-gold text-rbs-navy shadow transition">
            <i class="fa-solid fa-inbox mr-1"></i> Admissions (<span id="adminInquiryCounter">0</span>)
          </button>
          <button onclick="switchAdminTab('marksheet')" id="tabBtnMarksheet" class="px-3.5 py-1.5 rounded-xl text-xs font-bold bg-white/10 hover:bg-white/20 text-white transition">
            <i class="fa-solid fa-award mr-1"></i> Marksheet Studio
          </button>
          <button onclick="logoutAdmin()" class="bg-rose-600 hover:bg-rose-700 text-white text-xs font-bold px-3 py-1.5 rounded-xl transition shadow ml-2">
            Logout
          </button>
          <button onclick="closeAdminWorkspace()" class="text-slate-400 hover:text-white p-1 ml-1 text-lg">
            <i class="fa-solid fa-xmark"></i>
          </button>
        </div>
      </header>

      <!-- TAB 1: ADMISSION INQUIRIES WORKSPACE -->
      <div id="tabWorkspaceAdmissions" class="p-6 max-w-7xl mx-auto w-full flex-1 space-y-4">
        <div class="bg-white p-4 rounded-2xl shadow-sm border border-slate-200 flex flex-col sm:flex-row justify-between items-center gap-4">
          <div>
            <h3 class="font-title text-lg font-bold text-rbs-navy">Online Admission Inquiries (Class 1 to 12)</h3>
            <p class="text-xs text-slate-500">Live records filled by parents and students via the online portal.</p>
          </div>
          <div class="flex items-center gap-2 w-full sm:w-auto">
            <input type="text" id="adminSearchInquiry" oninput="filterAdmissionsLive()" placeholder="Search name / mobile / class..." class="px-3 py-2 border rounded-xl text-xs w-full sm:w-64 focus:outline-none focus:ring-1 focus:ring-rbs-navy" />
            <button onclick="exportAdmissionsCSV()" class="bg-emerald-600 hover:bg-emerald-700 text-white text-xs font-bold px-3.5 py-2 rounded-xl transition flex items-center gap-1.5 shrink-0 shadow">
              <i class="fa-solid fa-file-csv"></i> Export CSV
            </button>
            <button onclick="clearAllAdmissions()" class="bg-rose-50 text-rose-700 hover:bg-rose-100 text-xs font-bold px-3 py-2 rounded-xl transition border border-rose-200 shrink-0">
              Clear All
            </button>
          </div>
        </div>

        <div class="bg-white rounded-2xl border border-slate-200 shadow-sm overflow-hidden">
          <div class="overflow-x-auto">
            <table class="w-full text-left text-xs">
              <thead class="bg-slate-50 text-slate-700 uppercase font-bold border-b text-[11px]">
                <tr>
                  <th class="p-3">Ref ID</th>
                  <th class="p-3">Student Name</th>
                  <th class="p-3">Father's Name</th>
                  <th class="p-3">Class</th>
                  <th class="p-3">Mobile No.</th>
                  <th class="p-3">Hostel</th>
                  <th class="p-3">Address</th>
                  <th class="p-3">Date</th>
                  <th class="p-3 text-right">Actions</th>
                </tr>
              </thead>
              <tbody id="admissionsTableBody" class="divide-y divide-slate-100 font-medium">
                <!-- Dynamically rendered -->
              </tbody>
            </table>
          </div>
          <div id="noInquiriesNotice" class="hidden p-10 text-center text-slate-400 text-xs font-semibold">
            No admission inquiries registered yet.
          </div>
        </div>
      </div>

      <!-- TAB 2: MARKSHEET STUDIO (AUTOCALCULATION & OFFICIAL PRINT) -->
      <div id="tabWorkspaceMarksheet" class="p-6 max-w-7xl mx-auto w-full flex-1 hidden space-y-6">
        <div class="grid lg:grid-cols-12 gap-6">
          
          <!-- Column 1: Input & Configuration Parameters -->
          <div class="lg:col-span-5 bg-white p-5 rounded-2xl border border-slate-200 shadow-sm space-y-4">
            <div class="border-b pb-3 flex items-center justify-between">
              <div>
                <h3 class="font-title text-base font-bold text-rbs-navy">Student Marksheet Entry</h3>
                <p class="text-xs text-slate-500">Auto-calculates grand totals, percentages, grades and division.</p>
              </div>
              <button onclick="loadSampleMarksheetData()" class="bg-amber-100 hover:bg-amber-200 text-amber-900 text-xs font-bold px-3 py-1 rounded-lg transition">
                Load Sample
              </button>
            </div>

            <!-- Student Metadata -->
            <div class="space-y-3 text-xs">
              <div class="grid grid-cols-2 gap-2.5">
                <div>
                  <label class="block font-bold text-slate-700 uppercase mb-1">Student Name *</label>
                  <input type="text" id="msInputName" oninput="renderMarksheetLive()" placeholder="e.g. Aman Pratap Singh" value="Aman Pratap Singh" class="w-full px-3 py-2 border rounded-xl" />
                </div>
                <div>
                  <label class="block font-bold text-slate-700 uppercase mb-1">Father's Name *</label>
                  <input type="text" id="msInputFather" oninput="renderMarksheetLive()" placeholder="e.g. Mr. Rajendra Singh" value="Mr. Rajendra Singh" class="w-full px-3 py-2 border rounded-xl" />
                </div>
              </div>

              <div class="grid grid-cols-3 gap-2.5">
                <div>
                  <label class="block font-bold text-slate-700 uppercase mb-1">Roll Number *</label>
                  <input type="text" id="msInputRoll" oninput="renderMarksheetLive()" placeholder="e.g. RBS-2026101" value="RBS-2026101" class="w-full px-3 py-2 border rounded-xl font-mono font-bold" />
                </div>
                <div>
                  <label class="block font-bold text-slate-700 uppercase mb-1">Class *</label>
                  <select id="msInputClass" onchange="renderMarksheetLive()" class="w-full px-2 py-2 border rounded-xl font-semibold">
                    <option value="Class 1st">Class 1st</option>
                    <option value="Class 2nd">Class 2nd</option>
                    <option value="Class 3rd">Class 3rd</option>
                    <option value="Class 4th">Class 4th</option>
                    <option value="Class 5th">Class 5th</option>
                    <option value="Class 6th">Class 6th</option>
                    <option value="Class 7th">Class 7th</option>
                    <option value="Class 8th">Class 8th</option>
                    <option value="Class 9th">Class 9th</option>
                    <option value="Class 10th (High School Board)" selected>Class 10th (High School)</option>
                    <option value="Class 11th (Science)">Class 11th (Science)</option>
                    <option value="Class 11th (Arts)">Class 11th (Arts)</option>
                    <option value="Class 12th (Science)">Class 12th (Science)</option>
                    <option value="Class 12th (Arts)">Class 12th (Arts)</option>
                  </select>
                </div>
                <div>
                  <label class="block font-bold text-slate-700 uppercase mb-1">Session</label>
                  <input type="text" id="msInputSession" oninput="renderMarksheetLive()" value="2025-2026" class="w-full px-3 py-2 border rounded-xl" />
                </div>
              </div>

              <div>
                <label class="block font-bold text-slate-700 uppercase mb-1">Student Village / Address *</label>
                <input type="text" id="msInputAddress" oninput="renderMarksheetLive()" value="Bithara (Aliganj, Etah - 207247)" class="w-full px-3 py-2 border rounded-xl" />
              </div>

              <div class="grid grid-cols-2 gap-2.5">
                <div>
                  <label class="block font-bold text-slate-700 uppercase mb-1">Residential Status</label>
                  <select id="msInputHostel" onchange="renderMarksheetLive()" class="w-full px-3 py-2 border rounded-xl font-bold text-rbs-navy">
                    <option value="Hostel Resident (Campus Block A)">Hostel Resident</option>
                    <option value="Day Scholar" selected>Day Scholar</option>
                  </select>
                </div>
                <div>
                  <label class="block font-bold text-slate-700 uppercase mb-1">Examination Term</label>
                  <select id="msInputTerm" onchange="renderMarksheetLive()" class="w-full px-3 py-2 border rounded-xl">
                    <option value="ANNUAL EXAMINATION 2025-2026">ANNUAL EXAMINATION</option>
                    <option value="HALF-YEARLY ASSESSMENT">HALF-YEARLY</option>
                    <option value="PRE-BOARD EXAMINATION">PRE-BOARD</option>
                  </select>
                </div>
              </div>

              <!-- Subject Marks Entry Inputs -->
              <div class="border-t pt-3">
                <div class="flex items-center justify-between mb-2">
                  <span class="font-bold text-slate-800 uppercase tracking-wider text-[11px]">Subject Marks (Max 100 Each)</span>
                  <span class="text-[10px] text-slate-400">Passing Mark: 33</span>
                </div>
                
                <div class="space-y-1.5 max-h-56 overflow-y-auto pr-1">
                  <div class="flex items-center justify-between gap-2 bg-slate-50 p-2 rounded-xl border">
                    <span class="font-bold text-slate-700 w-36 truncate">1. Hindi (General)</span>
                    <div class="flex items-center gap-1">
                      <input type="number" id="subScore1" min="0" max="100" value="86" oninput="renderMarksheetLive()" class="w-16 px-2 py-1 text-center font-bold border rounded-lg" />
                      <span class="text-[10px] text-slate-400">/100</span>
                    </div>
                  </div>

                  <div class="flex items-center justify-between gap-2 bg-slate-50 p-2 rounded-xl border">
                    <span class="font-bold text-slate-700 w-36 truncate">2. English Special</span>
                    <div class="flex items-center gap-1">
                      <input type="number" id="subScore2" min="0" max="100" value="79" oninput="renderMarksheetLive()" class="w-16 px-2 py-1 text-center font-bold border rounded-lg" />
                      <span class="text-[10px] text-slate-400">/100</span>
                    </div>
                  </div>

                  <div class="flex items-center justify-between gap-2 bg-slate-50 p-2 rounded-xl border">
                    <span class="font-bold text-slate-700 w-36 truncate">3. Mathematics</span>
                    <div class="flex items-center gap-1">
                      <input type="number" id="subScore3" min="0" max="100" value="94" oninput="renderMarksheetLive()" class="w-16 px-2 py-1 text-center font-bold border rounded-lg" />
                      <span class="text-[10px] text-slate-400">/100</span>
                    </div>
                  </div>

                  <div class="flex items-center justify-between gap-2 bg-slate-50 p-2 rounded-xl border">
                    <span class="font-bold text-slate-700 w-36 truncate">4. Science (Theory+Prac)</span>
                    <div class="flex items-center gap-1">
                      <input type="number" id="subScore4" min="0" max="100" value="91" oninput="renderMarksheetLive()" class="w-16 px-2 py-1 text-center font-bold border rounded-lg" />
                      <span class="text-[10px] text-slate-400">/100</span>
                    </div>
                  </div>

                  <div class="flex items-center justify-between gap-2 bg-slate-50 p-2 rounded-xl border">
                    <span class="font-bold text-slate-700 w-36 truncate">5. Social Science</span>
                    <div class="flex items-center gap-1">
                      <input type="number" id="subScore5" min="0" max="100" value="84" oninput="renderMarksheetLive()" class="w-16 px-2 py-1 text-center font-bold border rounded-lg" />
                      <span class="text-[10px] text-slate-400">/100</span>
                    </div>
                  </div>

                  <div class="flex items-center justify-between gap-2 bg-slate-50 p-2 rounded-xl border">
                    <span class="font-bold text-slate-700 w-36 truncate">6. Sanskrit / Art / IT</span>
                    <div class="flex items-center gap-1">
                      <input type="number" id="subScore6" min="0" max="100" value="96" oninput="renderMarksheetLive()" class="w-16 px-2 py-1 text-center font-bold border rounded-lg" />
                      <span class="text-[10px] text-slate-400">/100</span>
                    </div>
                  </div>
                </div>
              </div>

              <!-- Action Bar -->
              <div class="pt-2">
                <button onclick="printOfficialMarksheet()" class="w-full bg-emerald-600 hover:bg-emerald-700 text-white font-extrabold py-3 rounded-xl transition text-xs shadow-lg flex items-center justify-center gap-2">
                  <i class="fa-solid fa-print"></i> Print Official Institutional Marksheet
                </button>
              </div>
            </div>
          </div>

          <!-- Column 2: Official Printable Marksheet Certificate Preview -->
          <div class="lg:col-span-7">
            <div id="printableReportCard" class="bg-white border-4 border-double border-rbs-navy p-6 sm:p-8 rounded-2xl shadow-xl watermark-seal relative text-slate-900">
              
              <!-- Certificate Institutional Header -->
              <div class="flex items-center justify-between border-b-2 border-rbs-gold pb-4 gap-4">
                <img src="image_a45465.jpg" alt="RBS Official Seal" class="w-18 h-18 sm:w-22 sm:h-22 rounded-full border-2 border-rbs-gold bg-rbs-navy p-1 shadow shrink-0" />
                <div class="text-center flex-1">
                  <span class="text-[10px] font-black uppercase tracking-widest text-amber-700">Official Certificate of Academic Evaluation</span>
                  <h1 class="font-title font-black text-xl sm:text-2xl lg:text-3xl text-rbs-navy tracking-tight uppercase leading-tight">
                    RAM BAX SINGH INTER COLLEGE
                  </h1>
                  <p class="text-xs font-bold text-rbs-goldDark uppercase">Bithara (Aliganj, Etah - 207247, U.P.)</p>
                  <p class="text-[10px] text-slate-500 font-semibold uppercase tracking-wider">Recognized by Board of High School & Intermediate Education, U.P.</p>
                  
                  <div class="mt-2 inline-block bg-rbs-navy text-rbs-goldLight text-[11px] font-bold px-4 py-0.5 rounded-full uppercase tracking-wider border border-rbs-gold">
                    <span id="cardTermTitle">ANNUAL EXAMINATION 2025-2026</span>
                  </div>
                </div>
                <div class="w-20 text-center shrink-0">
                  <span class="text-[9px] block text-slate-400 font-mono">SERIAL NO.</span>
                  <span id="cardSerialNo" class="text-xs font-mono font-bold text-rbs-navy">RBS-2026-904</span>
                </div>
              </div>

              <!-- Student Profile Table -->
              <div class="my-4 bg-slate-50/90 p-3.5 rounded-xl border border-slate-200 text-xs grid grid-cols-2 sm:grid-cols-3 gap-2.5">
                <div><span class="text-slate-500 block text-[10px]">STUDENT NAME:</span> <strong id="cardName" class="font-bold text-rbs-navy uppercase">Aman Pratap Singh</strong></div>
                <div><span class="text-slate-500 block text-[10px]">FATHER'S NAME:</span> <strong id="cardFather" class="font-bold text-slate-800">Mr. Rajendra Singh</strong></div>
                <div><span class="text-slate-500 block text-[10px]">ROLL NUMBER:</span> <strong id="cardRoll" class="font-mono font-bold text-amber-800">RBS-2026101</strong></div>
                <div><span class="text-slate-500 block text-[10px]">CLASS / COURSE:</span> <strong id="cardClass" class="font-bold text-slate-800">Class 10th (High School)</strong></div>
                <div><span class="text-slate-500 block text-[10px]">RESIDENTIAL STATUS:</span> <strong id="cardHostel" class="font-semibold text-emerald-800">Day Scholar</strong></div>
                <div><span class="text-slate-500 block text-[10px]">VILLAGE / ADDRESS:</span> <span id="cardAddress" class="font-medium text-slate-700">Bithara (Aliganj)</span></div>
              </div>

              <!-- Evaluated Scores Table -->
              <table class="w-full text-xs text-left border-collapse border border-slate-300">
                <thead class="bg-rbs-navy text-white text-center text-[11px] uppercase">
                  <tr>
                    <th class="p-2 border border-slate-300 w-12">S.No.</th>
                    <th class="p-2 border border-slate-300 text-left">Subject Description</th>
                    <th class="p-2 border border-slate-300 w-20">Max Marks</th>
                    <th class="p-2 border border-slate-300 w-20">Min Pass</th>
                    <th class="p-2 border border-slate-300 w-24">Marks Obtained</th>
                    <th class="p-2 border border-slate-300 w-20">Grade</th>
                  </tr>
                </thead>
                <tbody id="cardMarksTableBody" class="text-center font-medium divide-y">
                  <!-- Injected via JavaScript -->
                </tbody>
                <tfoot class="bg-amber-50/90 font-bold text-center text-xs">
                  <tr>
                    <td colspan="2" class="p-2 border border-slate-300 text-right font-serif">GRAND TOTAL:</td>
                    <td class="p-2 border border-slate-300" id="cardMaxTotal">600</td>
                    <td class="p-2 border border-slate-300">198</td>
                    <td class="p-2 border border-slate-300 text-sm font-black text-rbs-navy" id="cardGrandObtained">530</td>
                    <td class="p-2 border border-slate-300 text-amber-800 font-extrabold" id="cardOverallGrade">A+</td>
                  </tr>
                </tfoot>
              </table>

              <!-- Metrics Evaluation Strip -->
              <div class="mt-4 p-3 bg-slate-50 border border-slate-200 rounded-xl grid grid-cols-3 gap-2 text-center text-xs">
                <div>
                  <span class="text-slate-500 block text-[10px] uppercase">Percentage</span>
                  <span id="cardPercentage" class="font-extrabold text-base text-rbs-navy">88.33%</span>
                </div>
                <div>
                  <span class="text-slate-500 block text-[10px] uppercase">Result Status</span>
                  <span id="cardResultStatus" class="font-extrabold text-base text-emerald-700">PASSED</span>
                </div>
                <div>
                  <span class="text-slate-500 block text-[10px] uppercase">Division Awarded</span>
                  <span id="cardDivision" class="font-extrabold text-base text-amber-800">FIRST (1st) WITH HONORS</span>
                </div>
              </div>

              <!-- Signatures Row: Class Teacher, Manager Vishnu Kant, Director Avadhesh Singh -->
              <div class="mt-8 pt-6 grid grid-cols-3 text-center text-[11px] font-semibold text-slate-700 items-end">
                <div>
                  <div class="h-6"></div>
                  <div class="border-t border-slate-400 pt-1 font-medium">Class Teacher</div>
                </div>
                <div>
                  <div class="h-6 font-title font-bold text-rbs-navy">Vishnu Kant</div>
                  <div class="border-t border-slate-400 pt-1 font-bold text-rbs-navy">Manager (Prabandhak)</div>
                </div>
                <div>
                  <div class="h-6 font-title font-bold text-emerald-900">Avadhesh Singh</div>
                  <div class="border-t border-slate-400 pt-1 font-bold text-emerald-900">Director (Nideshak)</div>
                </div>
              </div>

            </div>
          </div>

        </div>
      </div>

    </div>
  </div>

  <script>
    // Strict Admin Credentials
    const ADMIN_CREDENTIALS = {
      email: 'rambaxsinghintercollege@gmail.com',
      pass: 'vishnukant@207247'
    };

    // Preloaded Demo Admission Applications
    const defaultAdmissionsList = [
      {
        id: 'RBS-ADM-108',
        studentName: 'Aman Pratap Singh',
        fatherName: 'Mr. Rajendra Singh',
        motherName: 'Mrs. Kamlesh Devi',
        classApply: 'Class 10th (High School)',
        dob: '2010-04-12',
        mobile: '9837102938',
        hostel: 'Yes - Hostel Required',
        address: 'Bithara, Aliganj, Etah - 207247',
        prevSchool: 'RBS High School (86.2%)',
        date: '2026-09-24'
      },
      {
        id: 'RBS-ADM-109',
        studentName: 'Km. Sarita Kumari',
        fatherName: 'Mr. Awadhesh Kumar',
        motherName: 'Mrs. Shashi Devi',
        classApply: 'Class 11th (Science PCM/PCB)',
        dob: '2009-08-19',
        mobile: '6395052394',
        hostel: 'Yes - Hostel Required',
        address: 'Bithara-Sarai Road, Aliganj (Etah)',
        prevSchool: 'Secondary Board (89.5%)',
        date: '2026-09-25'
      },
      {
        id: 'RBS-ADM-110',
        studentName: 'Rahul Yadav',
        fatherName: 'Mr. Dinesh Yadav',
        motherName: 'Mrs. Geeta Devi',
        classApply: 'Class 12th (Science PCM/PCB)',
        dob: '2008-02-14',
        mobile: '9758612345',
        hostel: 'No - Day Scholar',
        address: 'Village Aliganj, Etah (207247)',
        prevSchool: 'RBS Inter College (82.0%)',
        date: '2026-09-26'
      }
    ];

    /* ========================================================
       DPS-STYLE AUTOMATIC CAROUSEL ENGINE
       ======================================================== */
    let currentSlideIndex = 0;
    let sliderTimer = null;
    let isSliderPlaying = true;
    const slides = [];

    function initHeroCarousel() {
      const container = document.getElementById('slidesContainer');
      const dotsContainer = document.getElementById('sliderDotsContainer');
      if (!container || !dotsContainer) return;

      const slideElements = container.querySelectorAll('.slide');
      slideElements.forEach((s, idx) => {
        slides.push(s);
        const dot = document.createElement('button');
        dot.className = `w-3 h-3 rounded-full transition-all duration-300 ${idx === 0 ? 'bg-rbs-gold w-8 shadow-glow-gold' : 'bg-white/50 hover:bg-white'}`;
        dot.setAttribute('aria-label', `Slide ${idx + 1}`);
        dot.onclick = () => goToSlide(idx);
        dotsContainer.appendChild(dot);
      });

      startSliderTimer();
    }

    function showSlide(index) {
      if (!slides.length) return;
      slides.forEach((s, i) => {
        if (i === index) {
          s.classList.remove('opacity-0', 'z-10');
          s.classList.add('opacity-100', 'z-20');
        } else {
          s.classList.remove('opacity-100', 'z-20');
          s.classList.add('opacity-0', 'z-10');
        }
      });

      const dots = document.querySelectorAll('#sliderDotsContainer button');
      dots.forEach((dot, i) => {
        if (i === index) {
          dot.className = 'w-8 h-3 rounded-full bg-rbs-gold shadow-glow-gold transition-all duration-300';
        } else {
          dot.className = 'w-3 h-3 rounded-full bg-white/50 hover:bg-white transition-all duration-300';
        }
      });

      const bar = document.getElementById('sliderProgressBar');
      if (bar) {
        bar.classList.remove('animate-progress-fill');
        void bar.offsetWidth;
        if (isSliderPlaying) {
          bar.classList.add('animate-progress-fill');
        }
      }
    }

    function nextSlide() {
      currentSlideIndex = (currentSlideIndex + 1) % slides.length;
      showSlide(currentSlideIndex);
    }

    function prevSlide() {
      currentSlideIndex = (currentSlideIndex - 1 + slides.length) % slides.length;
      showSlide(currentSlideIndex);
    }

    function goToSlide(idx) {
      currentSlideIndex = idx;
      showSlide(currentSlideIndex);
      restartSliderTimer();
    }

    function startSliderTimer() {
      if (sliderTimer) clearInterval(sliderTimer);
      sliderTimer = setInterval(nextSlide, 4500);
      const bar = document.getElementById('sliderProgressBar');
      if (bar) bar.classList.add('animate-progress-fill');
    }

    function restartSliderTimer() {
      if (isSliderPlaying) {
        startSliderTimer();
      }
    }

    function toggleSliderPlay() {
      isSliderPlaying = !isSliderPlaying;
      const btn = document.getElementById('playPauseBtn');
      const bar = document.getElementById('sliderProgressBar');

      if (isSliderPlaying) {
        startSliderTimer();
        if (btn) btn.innerHTML = '<i class="fa-solid fa-pause text-[10px]"></i> <span>Auto</span>';
        if (bar) bar.classList.add('animate-progress-fill');
      } else {
        if (sliderTimer) clearInterval(sliderTimer);
        if (btn) btn.innerHTML = '<i class="fa-solid fa-play text-[10px]"></i> <span>Paused</span>';
        if (bar) bar.classList.remove('animate-progress-fill');
      }
    }

    /* ========================================================
       ONLINE ADMISSION FORM ENGINE
       ======================================================== */
    function getStoredAdmissions() {
      const stored = localStorage.getItem('rbs_admissions_db');
      if (!stored) {
        localStorage.setItem('rbs_admissions_db', JSON.stringify(defaultAdmissionsList));
        return defaultAdmissionsList;
      }
      try {
        return JSON.parse(stored);
      } catch (e) {
        return defaultAdmissionsList;
      }
    }

    function saveAdmissionsList(list) {
      localStorage.setItem('rbs_admissions_db', JSON.stringify(list));
      renderAdmissionsTable();
    }

    function handleAdmissionSubmit(e) {
      e.preventDefault();
      const studentName = document.getElementById('admStudentName').value.trim();
      const fatherName = document.getElementById('admFatherName').value.trim();
      const motherName = document.getElementById('admMotherName').value.trim() || 'N/A';
      const classApply = document.getElementById('admClass').value;
      const dob = document.getElementById('admDOB').value;
      const mobile = document.getElementById('admMobile').value.trim();
      const hostel = document.getElementById('admHostel').value;
      const prevSchool = document.getElementById('admPrevSchool').value.trim() || 'N/A';
      const address = document.getElementById('admAddress').value.trim();

      const newId = 'RBS-ADM-' + Math.floor(100 + Math.random() * 900);
      const newEntry = {
        id: newId,
        studentName,
        fatherName,
        motherName,
        classApply,
        dob,
        mobile,
        hostel,
        prevSchool,
        address,
        date: new Date().toISOString().split('T')[0]
      };

      const list = getStoredAdmissions();
      list.unshift(newEntry);
      saveAdmissionsList(list);

      const receiptCard = document.getElementById('admSuccessReceipt');
      const regIdSpan = document.getElementById('receiptRegId');
      const summaryText = document.getElementById('receiptSummaryText');

      regIdSpan.innerText = newId;
      summaryText.innerHTML = `Registration confirmed for <strong>${studentName}</strong> (Father: ${fatherName}) in <strong>${classApply}</strong>. Boarding Status: <strong>${hostel}</strong>. Manager Vishnu Kant will connect on <strong>${mobile}</strong> shortly.`;
      
      receiptCard.classList.remove('hidden');
      receiptCard.scrollIntoView({ behavior: 'smooth' });
      document.getElementById('onlineAdmissionForm').reset();
    }

    /* ========================================================
       ADMIN WORKSPACE ENGINE
       ======================================================== */
    function openAdminModal() {
      document.getElementById('adminAuthModal').classList.remove('hidden');
    }

    function closeAdminModal() {
      document.getElementById('adminAuthModal').classList.add('hidden');
      document.getElementById('adminAuthError').classList.add('hidden');
    }

    function closeAdminWorkspace() {
      document.getElementById('adminWorkspaceModal').classList.add('hidden');
    }

    function autoFillAdminCredentials() {
      document.getElementById('adminEmailInput').value = ADMIN_CREDENTIALS.email;
      document.getElementById('adminPassInput').value = ADMIN_CREDENTIALS.pass;
    }

    function handleAdminLogin(e) {
      e.preventDefault();
      const email = document.getElementById('adminEmailInput').value.trim();
      const pass = document.getElementById('adminPassInput').value.trim();
      const errEl = document.getElementById('adminAuthError');

      if ((email.toLowerCase() === ADMIN_CREDENTIALS.email.toLowerCase() && pass === ADMIN_CREDENTIALS.pass) || (email === 'admin' && pass === 'admin123')) {
        errEl.classList.add('hidden');
        closeAdminModal();
        document.getElementById('adminWorkspaceModal').classList.remove('hidden');
        renderAdmissionsTable();
        renderMarksheetLive();
      } else {
        errEl.classList.remove('hidden');
      }
    }

    function logoutAdmin() {
      closeAdminWorkspace();
      openAdminModal();
    }

    function switchAdminTab(tabName) {
      const isAdm = tabName === 'admissions';
      document.getElementById('tabWorkspaceAdmissions').classList.toggle('hidden', !isAdm);
      document.getElementById('tabWorkspaceMarksheet').classList.toggle('hidden', isAdm);

      document.getElementById('tabBtnAdmissions').className = isAdm
        ? 'px-3.5 py-1.5 rounded-xl text-xs font-black bg-rbs-gold text-rbs-navy shadow transition'
        : 'px-3.5 py-1.5 rounded-xl text-xs font-bold bg-white/10 hover:bg-white/20 text-white transition';

      document.getElementById('tabBtnMarksheet').className = !isAdm
        ? 'px-3.5 py-1.5 rounded-xl text-xs font-black bg-rbs-gold text-rbs-navy shadow transition'
        : 'px-3.5 py-1.5 rounded-xl text-xs font-bold bg-white/10 hover:bg-white/20 text-white transition';

      if (!isAdm) {
        renderMarksheetLive();
      }
    }

    function renderAdmissionsTable() {
      const list = getStoredAdmissions();
      const countEl = document.getElementById('adminInquiryCounter');
      if (countEl) countEl.innerText = list.length;

      const tbody = document.getElementById('admissionsTableBody');
      const emptyNotice = document.getElementById('noInquiriesNotice');
      if (!tbody) return;

      tbody.innerHTML = '';
      if (!list.length) {
        emptyNotice.classList.remove('hidden');
        return;
      }
      emptyNotice.classList.add('hidden');

      list.forEach(item => {
        const isHostel = item.hostel && item.hostel.includes('Yes');
        const tr = document.createElement('tr');
        tr.className = 'hover:bg-slate-50 transition border-b border-slate-100';
        tr.innerHTML = `
          <td class="p-3 font-mono font-bold text-rbs-navy">${item.id}</td>
          <td class="p-3 font-bold text-slate-900">${item.studentName}</td>
          <td class="p-3 text-slate-700">${item.fatherName}</td>
          <td class="p-3"><span class="bg-blue-50 text-blue-800 px-2 py-0.5 rounded font-semibold text-[11px]">${item.classApply}</span></td>
          <td class="p-3"><a href="tel:${item.mobile}" class="text-amber-800 font-bold hover:underline">${item.mobile}</a></td>
          <td class="p-3">
            <span class="px-2 py-0.5 rounded text-[10px] font-bold ${isHostel ? 'bg-amber-100 text-amber-900 border border-amber-300' : 'bg-slate-100 text-slate-600'}">
              ${isHostel ? 'Hostel' : 'Day Scholar'}
            </span>
          </td>
          <td class="p-3 text-slate-500 max-w-xs truncate" title="${item.address}">${item.address}</td>
          <td class="p-3 text-slate-400 whitespace-nowrap">${item.date}</td>
          <td class="p-3 text-right whitespace-nowrap space-x-1.5">
            <button onclick="prefillMarksheetFromAdmission('${item.id}')" title="Create Marksheet" class="bg-rbs-navy hover:bg-rbs-navyLight text-rbs-goldLight px-2.5 py-1 rounded-lg text-[11px] font-bold shadow">
              <i class="fa-solid fa-award mr-1"></i> Marksheet
            </button>
            <button onclick="deleteAdmission('${item.id}')" title="Delete" class="text-rose-500 hover:text-rose-700 p-1 font-bold">
              <i class="fa-solid fa-trash-can"></i>
            </button>
          </td>
        `;
        tbody.appendChild(tr);
      });
    }

    function filterAdmissionsLive() {
      const term = document.getElementById('adminSearchInquiry').value.toLowerCase();
      const list = getStoredAdmissions();
      const filtered = list.filter(item => 
        item.studentName.toLowerCase().includes(term) ||
        item.fatherName.toLowerCase().includes(term) ||
        item.mobile.includes(term) ||
        item.address.toLowerCase().includes(term)
      );

      const tbody = document.getElementById('admissionsTableBody');
      tbody.innerHTML = '';
      filtered.forEach(item => {
        const isHostel = item.hostel && item.hostel.includes('Yes');
        const tr = document.createElement('tr');
        tr.className = 'hover:bg-slate-50 transition border-b border-slate-100';
        tr.innerHTML = `
          <td class="p-3 font-mono font-bold text-rbs-navy">${item.id}</td>
          <td class="p-3 font-bold text-slate-900">${item.studentName}</td>
          <td class="p-3 text-slate-700">${item.fatherName}</td>
          <td class="p-3"><span class="bg-blue-50 text-blue-800 px-2 py-0.5 rounded font-semibold text-[11px]">${item.classApply}</span></td>
          <td class="p-3"><a href="tel:${item.mobile}" class="text-amber-800 font-bold hover:underline">${item.mobile}</a></td>
          <td class="p-3">${isHostel ? '<span class="bg-amber-100 text-amber-900 text-[10px] font-bold px-2 py-0.5 rounded">Hostel</span>' : '<span class="text-slate-400">Day Scholar</span>'}</td>
          <td class="p-3 text-slate-500 max-w-xs truncate">${item.address}</td>
          <td class="p-3 text-slate-400">${item.date}</td>
          <td class="p-3 text-right">
            <button onclick="prefillMarksheetFromAdmission('${item.id}')" class="bg-rbs-navy text-rbs-goldLight px-2.5 py-1 rounded-lg text-[11px] font-bold">Marksheet</button>
          </td>
        `;
        tbody.appendChild(tr);
      });
    }

    function deleteAdmission(id) {
      let list = getStoredAdmissions();
      list = list.filter(a => a.id !== id);
      saveAdmissionsList(list);
    }

    function clearAllAdmissions() {
      saveAdmissionsList([]);
    }

    function exportAdmissionsCSV() {
      const list = getStoredAdmissions();
      if (!list.length) return;
      const headers = ['Ref ID', 'Student Name', 'Father Name', 'Mother Name', 'Class', 'DOB', 'Mobile', 'Hostel', 'Address', 'Date'];
      const rows = list.map(i => [
        i.id, `"${i.studentName}"`, `"${i.fatherName}"`, `"${i.motherName}"`, `"${i.classApply}"`, i.dob, i.mobile, `"${i.hostel}"`, `"${i.address}"`, i.date
      ]);
      const csvContent = 'data:text/csv;charset=utf-8,' + [headers.join(','), ...rows.map(e => e.join(','))].join('\n');
      const encodedUri = encodeURI(csvContent);
      const link = document.createElement('a');
      link.setAttribute('href', encodedUri);
      link.setAttribute('download', `RBS_Admissions_${new Date().toISOString().split('T')[0]}.csv`);
      document.body.appendChild(link);
      link.click();
      document.body.removeChild(link);
    }

    function prefillMarksheetFromAdmission(id) {
      const student = getStoredAdmissions().find(a => a.id === id);
      if (!student) return;

      document.getElementById('msInputName').value = student.studentName;
      document.getElementById('msInputFather').value = student.fatherName;
      document.getElementById('msInputRoll').value = 'RBS-' + Math.floor(1000 + Math.random() * 9000);
      document.getElementById('msInputClass').value = student.classApply;
      document.getElementById('msInputAddress').value = student.address;
      document.getElementById('msInputHostel').value = student.hostel.includes('Yes') ? 'Hostel Resident (Campus Block A)' : 'Day Scholar';

      switchAdminTab('marksheet');
      renderMarksheetLive();
    }

    /* ========================================================
       AUTOCALCULATING DYNAMIC MARKSHEET STUDIO
       ======================================================== */
    const subjectNames = [
      "Hindi (General)",
      "English Special",
      "Mathematics",
      "Science (Theory + Practical)",
      "Social Science",
      "Sanskrit / Art / IT"
    ];

    function calculateSubjectGrade(marks) {
      if (marks >= 90) return 'A1';
      if (marks >= 80) return 'A2';
      if (marks >= 70) return 'B1';
      if (marks >= 60) return 'B2';
      if (marks >= 50) return 'C1';
      if (marks >= 33) return 'D';
      return 'E (Fail)';
    }

    function renderMarksheetLive() {
      const name = document.getElementById('msInputName').value || 'Student Name';
      const father = document.getElementById('msInputFather').value || "Father's Name";
      const roll = document.getElementById('msInputRoll').value || 'RBS-2026101';
      const sClass = document.getElementById('msInputClass').value;
      const session = document.getElementById('msInputSession').value || '2025-2026';
      const address = document.getElementById('msInputAddress').value || 'Bithara, Aliganj (Etah)';
      const hostelStatus = document.getElementById('msInputHostel').value;
      const termTitle = document.getElementById('msInputTerm').value;

      document.getElementById('cardName').innerText = name;
      document.getElementById('cardFather').innerText = father;
      document.getElementById('cardRoll').innerText = roll;
      document.getElementById('cardClass').innerText = sClass;
      document.getElementById('cardAddress').innerText = address;
      document.getElementById('cardHostel').innerText = hostelStatus;
      document.getElementById('cardTermTitle').innerText = termTitle;

      const scores = [
        Math.max(0, Math.min(100, Number(document.getElementById('subScore1').value) || 0)),
        Math.max(0, Math.min(100, Number(document.getElementById('subScore2').value) || 0)),
        Math.max(0, Math.min(100, Number(document.getElementById('subScore3').value) || 0)),
        Math.max(0, Math.min(100, Number(document.getElementById('subScore4').value) || 0)),
        Math.max(0, Math.min(100, Number(document.getElementById('subScore5').value) || 0)),
        Math.max(0, Math.min(100, Number(document.getElementById('subScore6').value) || 0))
      ];

      const tbody = document.getElementById('cardMarksTableBody');
      tbody.innerHTML = '';

      let grandTotal = 0;
      let hasFailed = false;

      scores.forEach((m, idx) => {
        grandTotal += m;
        if (m < 33) hasFailed = true;
        const grade = calculateSubjectGrade(m);

        const tr = document.createElement('tr');
        tr.className = 'border-b border-slate-200 hover:bg-slate-50';
        tr.innerHTML = `
          <td class="p-2 border border-slate-300 text-slate-500 font-mono">${idx + 1}</td>
          <td class="p-2 border border-slate-300 text-left font-bold text-slate-800">${subjectNames[idx]}</td>
          <td class="p-2 border border-slate-300 font-mono">100</td>
          <td class="p-2 border border-slate-300 font-mono text-slate-500">33</td>
          <td class="p-2 border border-slate-300 font-mono font-extrabold ${m < 33 ? 'text-rose-600' : 'text-slate-900'}">${m}</td>
          <td class="p-2 border border-slate-300 font-extrabold text-amber-700">${grade}</td>
        `;
        tbody.appendChild(tr);
      });

      const percentage = (grandTotal / 6).toFixed(2);
      document.getElementById('cardGrandObtained').innerText = grandTotal;
      document.getElementById('cardPercentage').innerText = `${percentage}%`;

      const statusEl = document.getElementById('cardResultStatus');
      const divEl = document.getElementById('cardDivision');
      const overallGradeEl = document.getElementById('cardOverallGrade');

      if (hasFailed) {
        statusEl.innerText = 'COMPARTMENT / FAILED';
        statusEl.className = 'font-extrabold text-base text-rose-600';
        divEl.innerText = 'NO DIVISION';
        divEl.className = 'font-extrabold text-base text-rose-600';
        overallGradeEl.innerText = 'D';
      } else {
        statusEl.innerText = 'PASSED';
        statusEl.className = 'font-extrabold text-base text-emerald-700';

        if (percentage >= 75) {
          divEl.innerText = 'FIRST (1st) WITH DISTINCTION';
          divEl.className = 'font-extrabold text-base text-amber-900';
          overallGradeEl.innerText = 'A+';
        } else if (percentage >= 60) {
          divEl.innerText = 'FIRST (1st) DIVISION';
          divEl.className = 'font-extrabold text-base text-amber-800';
          overallGradeEl.innerText = 'A';
        } else if (percentage >= 45) {
          divEl.innerText = 'SECOND (2nd) DIVISION';
          divEl.className = 'font-extrabold text-base text-blue-800';
          overallGradeEl.innerText = 'B';
        } else {
          divEl.innerText = 'THIRD (3rd) DIVISION';
          divEl.className = 'font-extrabold text-base text-slate-700';
          overallGradeEl.innerText = 'C';
        }
      }
    }

    function loadSampleMarksheetData() {
      document.getElementById('msInputName').value = 'Km. Sarita Kumari';
      document.getElementById('msInputFather').value = 'Mr. Awadhesh Kumar';
      document.getElementById('msInputRoll').value = 'RBS-2026-884';
      document.getElementById('msInputClass').value = 'Class 11th (Science)';
      document.getElementById('msInputAddress').value = 'Bithara-Sarai Road, Aliganj (Etah)';
      document.getElementById('msInputHostel').value = 'Hostel Resident (Campus Block A)';

      document.getElementById('subScore1').value = 92;
      document.getElementById('subScore2').value = 88;
      document.getElementById('subScore3').value = 97;
      document.getElementById('subScore4').value = 95;
      document.getElementById('subScore5').value = 91;
      document.getElementById('subScore6').value = 98;

      renderMarksheetLive();
    }

    function printOfficialMarksheet() {
      window.print();
    }

    window.addEventListener('DOMContentLoaded', () => {
      initHeroCarousel();
      renderAdmissionsTable();
      renderMarksheetLive();
    });
  </script>
</body>
</html>
