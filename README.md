<!DOCTYPE html>
<html lang="hi" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ram Bax Singh Inter College | Bithara, Aliganj (Etah)</title>
  
  <!-- Google Fonts: Cinzel for Crest, Montserrat & Outfit for DPS Institutional Look -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@600;700;800;900&family=Montserrat:wght@400;500;600;700;800&family=Outfit:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
  
  <!-- Font Awesome 6 -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" />
  
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            dps: {
              green: '#00482b',       /* DPS Classic Forest Green */
              greenDark: '#00331e',
              greenLight: '#08633e',
              gold: '#c59a3f',        /* Royal Institutional Gold */
              goldLight: '#e5be68',
              goldDark: '#9c7320',
              navy: '#091e3a',
              cream: '#fcfaf5',
              surface: '#f4f7f5'
            }
          },
          fontFamily: {
            crest: ['Cinzel', 'serif'],
            body: ['Outfit', 'sans-serif'],
            heading: ['Montserrat', 'sans-serif']
          }
        }
      }
    }
  </script>

  <style>
    /* Print Styling for Marksheet */
    @media print {
      body * { visibility: hidden !important; }
      #printableMarksheet, #printableMarksheet * { visibility: visible !important; }
      #printableMarksheet {
        position: absolute !important;
        left: 0 !important;
        top: 0 !important;
        width: 100% !important;
        margin: 0 !important;
        padding: 15px !important;
        background: #fff !important;
        box-shadow: none !important;
      }
      .no-print { display: none !important; }
    }

    .crest-watermark {
      background-image: url('image_a45465.jpg');
      background-position: center;
      background-repeat: no-repeat;
      background-size: 280px;
    }

    /* DPS Style Smooth Transitions */
    .slider-fade {
      transition: opacity 0.8s ease-in-out;
    }
    
    /* Custom scrollbar */
    ::-webkit-scrollbar {
      width: 8px;
      height: 8px;
    }
    ::-webkit-scrollbar-track {
      background: #f1f1f1;
    }
    ::-webkit-scrollbar-thumb {
      background: #00482b;
      border-radius: 4px;
    }
  </style>
</head>
<body class="bg-dps-surface text-slate-800 font-body antialiased selection:bg-dps-gold selection:text-white">

  <!-- TOP HELPLINE & UTILITY BAR (DPS Mathura Road Style) -->
  <div class="bg-dps-greenDark text-white text-xs border-b border-dps-gold/30">
    <div class="max-w-7xl mx-auto px-4 py-2 flex flex-wrap justify-between items-center gap-2">
      <div class="flex items-center gap-3 md:gap-6 flex-wrap">
        <span class="inline-flex items-center gap-1.5 text-dps-goldLight font-medium">
          <i class="fa-solid fa-graduation-cap"></i> U.P. Board Recognized &bull; Class 1st to 12th
        </span>
        <span class="hidden md:inline text-white/30">|</span>
        <span class="inline-flex items-center gap-1.5 text-emerald-300">
          <i class="fa-solid fa-bed"></i> 24x7 Residential Hostel Campus
        </span>
        <span class="hidden md:inline text-white/30">|</span>
        <span class="text-slate-300">
          <i class="fa-solid fa-location-dot text-dps-gold"></i> Bithara, Aliganj (Etah) - 207247
        </span>
      </div>

      <div class="flex items-center gap-4">
        <a href="tel:6395052394" class="hover:text-dps-goldLight transition inline-flex items-center gap-1.5 text-slate-200">
          <i class="fa-solid fa-headset text-dps-gold"></i> Helpline: <strong class="text-white">6395052394</strong>
        </a>
        <button onclick="openAdminModal()" class="bg-dps-gold hover:bg-dps-goldDark text-dps-navy font-bold px-3 py-1 rounded transition text-xs shadow inline-flex items-center gap-1">
          <i class="fa-solid fa-lock"></i> Admin Login
        </button>
      </div>
    </div>
  </div>

  <!-- MAIN INSTITUTIONAL HEADER (DPS Mathura Road Layout) -->
  <header class="bg-white border-b-2 border-dps-gold shadow-sm sticky top-0 z-40">
    <div class="max-w-7xl mx-auto px-4 py-3 flex flex-wrap justify-between items-center gap-4">
      
      <!-- Brand Crest & Title -->
      <a href="#" class="flex items-center gap-3.5 md:gap-5 group">
        <div class="relative">
          <img src="image_a45465.jpg" alt="RBS College Official Seal" class="w-16 h-16 sm:w-20 sm:h-20 rounded-full border-2 border-dps-gold shadow-md object-contain bg-white group-hover:scale-105 transition" />
          <span class="absolute -bottom-1 -right-1 bg-dps-green text-dps-goldLight text-[9px] font-bold px-1.5 py-0.5 rounded-full border border-white">ESTD</span>
        </div>
        <div>
          <h1 class="font-crest font-extrabold text-lg sm:text-2xl md:text-3xl text-dps-greenDark tracking-tight uppercase leading-tight group-hover:text-dps-green transition">
            RAM BAX SINGH INTER COLLEGE
          </h1>
          <div class="flex flex-wrap items-center gap-2 text-xs sm:text-sm font-semibold text-dps-goldDark mt-0.5">
            <span>RESIDENTIAL R.B.S. INTER COLLEGE</span>
            <span class="text-slate-300">•</span>
            <span class="text-slate-600 font-medium">Bithara-Sarai Road, Aliganj (Etah) 207247</span>
          </div>
          <p class="text-[11px] text-slate-500 font-medium hidden sm:block">A Premier Residential & Day-Boarding Institution for Holistic Learning</p>
        </div>
      </a>

      <!-- Quick Action CTAs -->
      <div class="hidden lg:flex items-center gap-3">
        <a href="#admission-desk" class="bg-dps-green hover:bg-dps-greenDark text-white font-semibold text-xs px-4 py-2.5 rounded shadow flex items-center gap-2 transition border border-dps-greenLight">
          <i class="fa-solid fa-file-signature text-dps-gold"></i> Admission 2026-27
        </a>
        <a href="https://wa.me/916395052394?text=Namaste%20Ji,%20Ram%20Bax%20Singh%20Inter%20College%20me%20admission%20aur%20hostel%20ki%20jankari%20chahiye." target="_blank" class="bg-emerald-600 hover:bg-emerald-700 text-white font-semibold text-xs px-3.5 py-2.5 rounded shadow flex items-center gap-1.5 transition">
          <i class="fa-brands fa-whatsapp text-sm"></i> WhatsApp Us
        </a>
      </div>
    </div>

    <!-- DPS STYLE HORIZONTAL NAVIGATION MENU -->
    <nav class="bg-dps-green text-white text-xs font-semibold tracking-wide">
      <div class="max-w-7xl mx-auto px-4 flex overflow-x-auto whitespace-nowrap scrollbar-none items-center py-1">
        <a href="#hero-section" class="px-3.5 py-2 hover:bg-dps-greenDark text-white transition flex items-center gap-1.5 border-b-2 border-dps-gold">
          <i class="fa-solid fa-house"></i> Home
        </a>
        <a href="#about-section" class="px-3.5 py-2 hover:bg-dps-greenDark text-slate-100 hover:text-white transition">About R.B.S.</a>
        <a href="#dignitaries" class="px-3.5 py-2 hover:bg-dps-greenDark text-slate-100 hover:text-white transition">Our Dignitaries</a>
        <a href="#wings-section" class="px-3.5 py-2 hover:bg-dps-greenDark text-slate-100 hover:text-white transition">Our Wings (1 to 12)</a>
        <a href="#hostel-section" class="px-3.5 py-2 hover:bg-dps-greenDark text-slate-100 hover:text-white transition">Residential Hostel</a>
        <a href="#gallery-section" class="px-3.5 py-2 hover:bg-dps-greenDark text-slate-100 hover:text-white transition">Campus Gallery</a>
        <a href="#toppers-section" class="px-3.5 py-2 hover:bg-dps-greenDark text-slate-100 hover:text-white transition">Top Achievers</a>
        <a href="#admission-desk" class="px-3.5 py-2 bg-dps-gold text-dps-navy font-bold hover:bg-dps-goldLight transition ml-auto rounded">
          <i class="fa-solid fa-pen-nib mr-1"></i> Online Admission Form
        </a>
      </div>
    </nav>
  </header>

  <!-- BREAKING NEWS / MARQUEE TICKER (DPS Mathura Road Component) -->
  <div class="bg-amber-100/90 border-b border-amber-300 py-1.5 px-4 text-xs">
    <div class="max-w-7xl mx-auto flex items-center gap-3">
      <span class="bg-red-700 text-white font-bold uppercase text-[10px] px-2 py-0.5 rounded tracking-wide shrink-0 animate-pulse">
        Notice
      </span>
      <marquee behavior="scroll" direction="left" class="text-slate-800 font-medium">
        🔔 Admissions Open for Academic Session 2026-2027 from Class 1st to 12th (Science & Arts Stream) &bull; Boarding & Day Scholar Seats Available &bull; Special Night Supervised Study for Hostel Students &bull; Contact Director Avadhesh Singh & Manager Vishnu Kant at 6395052394 for Registration.
      </marquee>
    </div>
  </div>

  <!-- HERO SLIDER SECTION (DPS Mathura Road Auto-Running Carousel) -->
  <section id="hero-section" class="relative bg-slate-950 overflow-hidden">
    <div class="relative w-full h-[380px] sm:h-[480px] md:h-[560px] select-none">
      
      <!-- Slides Container (object-contain with ambient framing: NO FACES CROPPED) -->
      <div id="dpsCarousel" class="relative w-full h-full flex items-center justify-center">

        <!-- Slide 1: Campus Courtyard (rbs5_2.jpeg) -->
        <div class="slide absolute inset-0 slider-fade opacity-100 z-20 flex items-center justify-center bg-slate-950">
          <img src="rbs5_2.jpeg" alt="RBS Campus Courtyard" class="w-full h-full object-contain mx-auto" onerror="this.src='rbs5.jpeg';" />
          <div class="absolute inset-x-0 bottom-0 bg-gradient-to-t from-black/90 via-black/40 to-transparent p-5 sm:p-10 text-white pointer-events-none">
            <div class="max-w-7xl mx-auto">
              <span class="bg-dps-gold text-dps-navy font-bold text-xs uppercase px-2.5 py-1 rounded shadow">Campus Overview</span>
              <h2 class="font-crest text-xl sm:text-3xl md:text-4xl font-extrabold mt-1.5 text-white">Ram Bax Singh Inter College, Bithara</h2>
              <p class="text-xs sm:text-sm text-slate-200 mt-1 max-w-2xl">A serene, green campus fostering discipline, academic brilliance, and character building.</p>
            </div>
          </div>
        </div>

        <!-- Slide 2: Assembly & Parade (rbs4_2.jpeg) -->
        <div class="slide absolute inset-0 slider-fade opacity-0 z-10 flex items-center justify-center bg-slate-950">
          <img src="rbs4_2.jpeg" alt="Morning Assembly & National Flags" class="w-full h-full object-contain mx-auto" onerror="this.src='rbs4.jpeg';" />
          <div class="absolute inset-x-0 bottom-0 bg-gradient-to-t from-black/90 via-black/40 to-transparent p-5 sm:p-10 text-white pointer-events-none">
            <div class="max-w-7xl mx-auto">
              <span class="bg-emerald-600 text-white font-bold text-xs uppercase px-2.5 py-1 rounded shadow">Morning Assembly</span>
              <h2 class="font-crest text-xl sm:text-3xl md:text-4xl font-extrabold mt-1.5 text-white">Tiranga Yatra & Cultural Discipline</h2>
              <p class="text-xs sm:text-sm text-slate-200 mt-1 max-w-2xl">Instilling patriotic values and leadership through daily morning prayers and assembly.</p>
            </div>
          </div>
        </div>

        <!-- Slide 3: Classroom Mentorship (rbs12_2.jpeg) -->
        <div class="slide absolute inset-0 slider-fade opacity-0 z-10 flex items-center justify-center bg-slate-950">
          <img src="rbs12_2.jpeg" alt="Manager Vishnu Kant In Classroom" class="w-full h-full object-contain mx-auto" onerror="this.src='rbs12.jpeg';" />
          <div class="absolute inset-x-0 bottom-0 bg-gradient-to-t from-black/90 via-black/40 to-transparent p-5 sm:p-10 text-white pointer-events-none">
            <div class="max-w-7xl mx-auto">
              <span class="bg-amber-500 text-dps-navy font-bold text-xs uppercase px-2.5 py-1 rounded shadow">Student Guidance</span>
              <h2 class="font-crest text-xl sm:text-3xl md:text-4xl font-extrabold mt-1.5 text-white">Personal Attention & Class Mentorship</h2>
              <p class="text-xs sm:text-sm text-slate-200 mt-1 max-w-2xl">Manager Shri Vishnu Kant personally interacting and encouraging student excellence.</p>
            </div>
          </div>
        </div>

        <!-- Slide 4: Cultural Fest Drama (rbs10_2.jpeg) -->
        <div class="slide absolute inset-0 slider-fade opacity-0 z-10 flex items-center justify-center bg-slate-950">
          <img src="rbs10_2.jpeg" alt="Cultural Dance & Drama Costumes" class="w-full h-full object-contain mx-auto" onerror="this.src='rbs10.jpeg';" />
          <div class="absolute inset-x-0 bottom-0 bg-gradient-to-t from-black/90 via-black/40 to-transparent p-5 sm:p-10 text-white pointer-events-none">
            <div class="max-w-7xl mx-auto">
              <span class="bg-purple-600 text-white font-bold text-xs uppercase px-2.5 py-1 rounded shadow">Cultural Spectrum</span>
              <h2 class="font-crest text-xl sm:text-3xl md:text-4xl font-extrabold mt-1.5 text-white">Sanskriti & Dramatic Arts Presentation</h2>
              <p class="text-xs sm:text-sm text-slate-200 mt-1 max-w-2xl">Nurturing creative expression and Indian heritage through stage celebrations.</p>
            </div>
          </div>
        </div>

        <!-- Slide 5: Honors & Certificates (rbs8_2.jpeg) -->
        <div class="slide absolute inset-0 slider-fade opacity-0 z-10 flex items-center justify-center bg-slate-950">
          <img src="rbs8_2.jpeg" alt="Republic Day Merit Certificates" class="w-full h-full object-contain mx-auto" onerror="this.src='rbs8.jpeg';" />
          <div class="absolute inset-x-0 bottom-0 bg-gradient-to-t from-black/90 via-black/40 to-transparent p-5 sm:p-10 text-white pointer-events-none">
            <div class="max-w-7xl mx-auto">
              <span class="bg-dps-gold text-dps-navy font-bold text-xs uppercase px-2.5 py-1 rounded shadow">Pratibha Samman</span>
              <h2 class="font-crest text-xl sm:text-3xl md:text-4xl font-extrabold mt-1.5 text-white">Republic Day Medal & Merit Awards</h2>
              <p class="text-xs sm:text-sm text-slate-200 mt-1 max-w-2xl">Recognizing academic achievers and co-curricular champions every academic year.</p>
            </div>
          </div>
        </div>

        <!-- Slide 6: Senior Teaching Session (rbs7_2.jpeg) -->
        <div class="slide absolute inset-0 slider-fade opacity-0 z-10 flex items-center justify-center bg-slate-950">
          <img src="rbs7_2.jpeg" alt="Senior Teaching Lecture" class="w-full h-full object-contain mx-auto" onerror="this.src='rbs7.jpeg';" />
          <div class="absolute inset-x-0 bottom-0 bg-gradient-to-t from-black/90 via-black/40 to-transparent p-5 sm:p-10 text-white pointer-events-none">
            <div class="max-w-7xl mx-auto">
              <span class="bg-blue-600 text-white font-bold text-xs uppercase px-2.5 py-1 rounded shadow">Academic Excellence</span>
              <h2 class="font-crest text-xl sm:text-3xl md:text-4xl font-extrabold mt-1.5 text-white">Board Exam Preparation & Lectures</h2>
              <p class="text-xs sm:text-sm text-slate-200 mt-1 max-w-2xl">Concept-driven teaching by experienced faculty for Class 10th and 12th.</p>
            </div>
          </div>
        </div>

      </div>

      <!-- Left / Right Slider Controls -->
      <button onclick="prevSlide()" class="absolute left-3 top-1/2 -translate-y-1/2 z-30 w-10 h-10 rounded-full bg-black/50 hover:bg-dps-gold text-white hover:text-dps-navy flex items-center justify-center transition shadow-lg">
        <i class="fa-solid fa-chevron-left text-sm"></i>
      </button>
      <button onclick="nextSlide()" class="absolute right-3 top-1/2 -translate-y-1/2 z-30 w-10 h-10 rounded-full bg-black/50 hover:bg-dps-gold text-white hover:text-dps-navy flex items-center justify-center transition shadow-lg">
        <i class="fa-solid fa-chevron-right text-sm"></i>
      </button>

      <!-- Carousel Progress Bar & Dots -->
      <div class="absolute bottom-3 left-0 right-0 z-30 flex flex-col items-center gap-2">
        <div class="flex items-center gap-2" id="sliderDots">
          <!-- Populated by JS -->
        </div>
      </div>
    </div>
  </section>

  <!-- DPS STYLE FLOATING METRIC CARDS -->
  <section class="bg-white border-b shadow-sm relative z-20">
    <div class="max-w-7xl mx-auto px-4 py-6 grid grid-cols-2 md:grid-cols-4 gap-4 text-center divide-x divide-slate-100">
      <div class="p-2">
        <div class="font-crest text-2xl md:text-3xl font-extrabold text-dps-green">Class 1 to 12</div>
        <div class="text-xs text-slate-500 font-semibold uppercase tracking-wider mt-1">Science & Arts Streams</div>
      </div>
      <div class="p-2">
        <div class="font-crest text-2xl md:text-3xl font-extrabold text-dps-goldDark">24x7 Hostel</div>
        <div class="text-xs text-slate-500 font-semibold uppercase tracking-wider mt-1">Residential Boarding Parisar</div>
      </div>
      <div class="p-2">
        <div class="font-crest text-2xl md:text-3xl font-extrabold text-emerald-600">100% Pass</div>
        <div class="text-xs text-slate-500 font-semibold uppercase tracking-wider mt-1">Board Examination Record</div>
      </div>
      <div class="p-2">
        <div class="font-crest text-2xl md:text-3xl font-extrabold text-dps-navy">Etah District</div>
        <div class="text-xs text-slate-500 font-semibold uppercase tracking-wider mt-1">Bithara, Aliganj (207247)</div>
      </div>
    </div>
  </section>

  <!-- OUR DIGNITARIES SECTION (DPS Mathura Road "Guiding Lights of Excellence") -->
  <section id="dignitaries" class="py-14 bg-dps-surface border-b border-slate-200">
    <div class="max-w-7xl mx-auto px-4">
      
      <div class="text-center max-w-2xl mx-auto mb-12">
        <span class="text-xs font-bold text-dps-goldDark tracking-widest uppercase bg-amber-50 px-3 py-1 rounded border border-amber-200">
          Guiding Lights of Excellence
        </span>
        <h2 class="font-crest text-2xl sm:text-3xl md:text-4xl font-extrabold text-dps-greenDark mt-2">
          Our Leadership & Dignitaries
        </h2>
        <p class="text-xs sm:text-sm text-slate-500 mt-1">
          Their visionary leadership continues to shape generations of confident, disciplined, and future-ready scholars.
        </p>
        <div class="w-20 h-1 bg-dps-gold mx-auto mt-3 rounded-full"></div>
      </div>

      <div class="grid md:grid-cols-2 gap-8 items-stretch">
        
        <!-- Dignitary 1: Director Shri Avadhesh Singh -->
        <div class="bg-white rounded-2xl border-2 border-slate-200 hover:border-dps-gold p-6 shadow-md transition flex flex-col justify-between group">
          <div>
            <div class="flex items-center gap-4 mb-4">
              <div class="w-20 h-20 rounded-full bg-dps-green/10 border-2 border-dps-gold flex items-center justify-center text-dps-green text-3xl font-crest font-bold shrink-0">
                AS
              </div>
              <div>
                <span class="text-[10px] font-bold uppercase tracking-wider bg-dps-green/10 text-dps-green px-2 py-0.5 rounded">Director Desk</span>
                <h3 class="font-crest text-xl font-bold text-dps-greenDark mt-1">Shri Avadhesh Singh</h3>
                <p class="text-xs font-semibold text-dps-goldDark">Director (Nideshak) &bull; R.B.S. Inter College</p>
              </div>
            </div>

            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed italic border-l-4 border-dps-gold pl-3 py-1 my-3 bg-amber-50/50 rounded-r">
              "Hamara lakshya gramin kshetr ke chhatron ko shahari star ki utkrishth shiksha, anushasan aur aadhunik suvidhayein pradan karna hai. Vidyalaya ka pratyek bachha rashtriya star par safal ho, yahi hamari prathmikta hai."
            </p>

            <ul class="text-xs text-slate-600 space-y-1.5 mt-3">
              <li class="flex items-center gap-2"><i class="fa-solid fa-check text-emerald-600"></i> Direction towards holistic character and academic excellence</li>
              <li class="flex items-center gap-2"><i class="fa-solid fa-check text-emerald-600"></i> Expansion of modern science laboratories and library</li>
              <li class="flex items-center gap-2"><i class="fa-solid fa-check text-emerald-600"></i> Affordable fee structure for all sections of society</li>
            </ul>
          </div>

          <div class="mt-6 pt-4 border-t border-slate-100 flex items-center justify-between text-xs text-slate-500">
            <span>Location: Bithara, Aliganj (Etah)</span>
            <span class="font-semibold text-dps-green"><i class="fa-solid fa-award text-dps-gold"></i> Institutional Patron</span>
          </div>
        </div>

        <!-- Dignitary 2: Manager Shri Vishnu Kant -->
        <div class="bg-white rounded-2xl border-2 border-slate-200 hover:border-dps-gold p-6 shadow-md transition flex flex-col justify-between group">
          <div>
            <div class="flex items-center gap-4 mb-4">
              <div class="relative w-24 h-24 shrink-0">
                <img src="vishnu kant_2.jpg" alt="Manager Vishnu Kant" class="w-full h-full object-cover rounded-full border-2 border-dps-gold shadow" onerror="this.src='https://placehold.co/200x200/00482b/ffffff?text=Vishnu+Kant';" />
                <span class="absolute bottom-0 right-1 bg-emerald-500 w-4 h-4 rounded-full border-2 border-white" title="Active"></span>
              </div>
              <div>
                <span class="text-[10px] font-bold uppercase tracking-wider bg-dps-gold/20 text-dps-goldDark px-2 py-0.5 rounded">Managing Desk</span>
                <h3 class="font-crest text-xl font-bold text-dps-greenDark mt-1">Shri Vishnu Kant</h3>
                <p class="text-xs font-semibold text-dps-goldDark">Manager (Prabandhak) &bull; R.B.S. Inter College</p>
                <div class="mt-1 flex items-center gap-2">
                  <a href="tel:6395052394" class="text-xs font-bold text-dps-green hover:underline">
                    <i class="fa-solid fa-phone text-dps-gold"></i> 6395052394
                  </a>
                </div>
              </div>
            </div>

            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed italic border-l-4 border-dps-green pl-3 py-1 my-3 bg-emerald-50/50 rounded-r">
              "Vidyalaya me Class 1st se lekar 12th tak ke chhatron ke sarvangin vikas aur unke aawasiya hostel me surakshit vatavaran ke liye hum nishtha se samarpit hain. Chhatron ka anushasan aur naitikta hi hamari dharohar hai."
            </p>

            <ul class="text-xs text-slate-600 space-y-1.5 mt-3">
              <li class="flex items-center gap-2"><i class="fa-solid fa-check text-emerald-600"></i> 24x7 personal oversight of residential hostel facilities</li>
              <li class="flex items-center gap-2"><i class="fa-solid fa-check text-emerald-600"></i> Daily interaction, parent updates, and doubt resolution</li>
              <li class="flex items-center gap-2"><i class="fa-solid fa-check text-emerald-600"></i> Direct admission inquiry helpline: +91 6395052394</li>
            </ul>
          </div>

          <div class="mt-6 pt-4 border-t border-slate-100 flex items-center justify-between text-xs">
            <a href="https://wa.me/916395052394" target="_blank" class="bg-emerald-600 hover:bg-emerald-700 text-white font-semibold px-3 py-1 rounded transition inline-flex items-center gap-1.5">
              <i class="fa-brands fa-whatsapp"></i> Chat with Manager
            </a>
            <span class="text-slate-500 font-mono">Etah (U.P.) - 207247</span>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- OUR CURRICULUM & ACADEMIC WINGS (DPS Mathura Road "Our Curriculum" Layout) -->
  <section id="wings-section" class="py-14 bg-white border-b border-slate-200">
    <div class="max-w-7xl mx-auto px-4">
      
      <div class="text-center max-w-2xl mx-auto mb-12">
        <span class="text-xs font-bold text-dps-goldDark tracking-widest uppercase">Shaping Future Leaders</span>
        <h2 class="font-crest text-2xl sm:text-3xl md:text-4xl font-extrabold text-dps-greenDark mt-2">
          Academic Wings & Curriculum (Class 1 to 12)
        </h2>
        <p class="text-xs sm:text-sm text-slate-500 mt-1">
          A rigorous, value-based curriculum affiliated with the Uttar Pradesh Secondary Board with comprehensive hostel provisions.
        </p>
        <div class="w-20 h-1 bg-dps-gold mx-auto mt-3 rounded-full"></div>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-4 gap-6">
        
        <!-- Wing 1: Primary Wing -->
        <div class="bg-dps-surface rounded-2xl border border-slate-200 p-5 hover:shadow-lg transition flex flex-col justify-between">
          <div>
            <div class="w-12 h-12 rounded-xl bg-dps-green/10 text-dps-green flex items-center justify-center text-xl mb-4">
              <i class="fa-solid fa-shapes"></i>
            </div>
            <h3 class="font-crest font-bold text-base text-dps-greenDark">Primary Wing</h3>
            <span class="text-xs font-semibold text-dps-goldDark">Class 1st to 5th</span>
            <p class="text-xs text-slate-600 mt-2 leading-relaxed">
              Foundational literacy, numeracy, moral values, and interactive learning in a joyful classroom atmosphere.
            </p>
          </div>
          <div class="mt-4 pt-3 border-t border-slate-200 text-[11px] text-slate-500 font-medium">
            Subjects: Hindi, English, Maths, EVS, Drawing
          </div>
        </div>

        <!-- Wing 2: Middle Wing -->
        <div class="bg-dps-surface rounded-2xl border border-slate-200 p-5 hover:shadow-lg transition flex flex-col justify-between">
          <div>
            <div class="w-12 h-12 rounded-xl bg-blue-100 text-blue-700 flex items-center justify-center text-xl mb-4">
              <i class="fa-solid fa-book-open-reader"></i>
            </div>
            <h3 class="font-crest font-bold text-base text-dps-greenDark">Middle Wing</h3>
            <span class="text-xs font-semibold text-blue-700">Class 6th to 8th</span>
            <p class="text-xs text-slate-600 mt-2 leading-relaxed">
              Strengthening analytical thinking, science fundamentals, computer literacy, and sports competitions.
            </p>
          </div>
          <div class="mt-4 pt-3 border-t border-slate-200 text-[11px] text-slate-500 font-medium">
            Subjects: Science, Social Studies, Maths, Sanskrit
          </div>
        </div>

        <!-- Wing 3: High School -->
        <div class="bg-dps-surface rounded-2xl border border-slate-200 p-5 hover:shadow-lg transition flex flex-col justify-between">
          <div>
            <div class="w-12 h-12 rounded-xl bg-purple-100 text-purple-700 flex items-center justify-center text-xl mb-4">
              <i class="fa-solid fa-chalkboard-user"></i>
            </div>
            <h3 class="font-crest font-bold text-base text-dps-greenDark">Secondary Wing</h3>
            <span class="text-xs font-semibold text-purple-700">Class 9th & 10th (Board)</span>
            <p class="text-xs text-slate-600 mt-2 leading-relaxed">
              Targeted board preparation, regular test series, practical lab sessions, and personalized exam mentoring.
            </p>
          </div>
          <div class="mt-4 pt-3 border-t border-slate-200 text-[11px] text-slate-500 font-medium">
            U.P. Board High School Curriculum
          </div>
        </div>

        <!-- Wing 4: Senior Secondary Intermediate -->
        <div class="bg-dps-surface rounded-2xl border-2 border-dps-gold/60 p-5 hover:shadow-lg transition flex flex-col justify-between relative bg-amber-50/30">
          <span class="absolute -top-2.5 right-4 bg-dps-gold text-dps-navy font-bold text-[10px] uppercase px-2 py-0.5 rounded shadow">Premier</span>
          <div>
            <div class="w-12 h-12 rounded-xl bg-dps-gold/20 text-dps-goldDark flex items-center justify-center text-xl mb-4">
              <i class="fa-solid fa-graduation-cap"></i>
            </div>
            <h3 class="font-crest font-bold text-base text-dps-greenDark">Senior Secondary Wing</h3>
            <span class="text-xs font-semibold text-dps-goldDark">Class 11th & 12th (Sci / Arts)</span>
            <p class="text-xs text-slate-600 mt-2 leading-relaxed">
              Advanced preparation for competitive exams (IIT-JEE, NEET, CUET) alongside Board examinations.
            </p>
          </div>
          <div class="mt-4 pt-3 border-t border-slate-200 text-[11px] text-slate-500 font-medium">
            Streams: Physics, Chemistry, Maths, Bio & Humanities
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- RESIDENTIAL HOSTEL FACILITY SECTION (DPS Style Full Feature Box) -->
  <section id="hostel-section" class="py-14 bg-dps-greenDark text-white relative overflow-hidden">
    <div class="max-w-7xl mx-auto px-4 relative z-10">
      
      <div class="grid lg:grid-cols-12 gap-8 items-center">
        
        <div class="lg:col-span-7 space-y-4">
          <div class="inline-flex items-center gap-2 bg-dps-gold/20 text-dps-goldLight border border-dps-gold/30 px-3 py-1 rounded-full text-xs font-semibold">
            <i class="fa-solid fa-house-chimney-user"></i> 24x7 Residential Facility
          </div>
          <h2 class="font-crest text-2xl sm:text-3xl md:text-4xl font-extrabold text-white">
            Residential R.B.S. Hostel Parisar
          </h2>
          <p class="text-xs sm:text-sm text-slate-200 leading-relaxed">
            Jo chhatra door-draj ke kshetron se aate hain, unke liye vidyalaya parisar me hi surakshit, anushasit aur gharpurna aawasiya hostel ki vyavastha uplabdh hai. Yahan unki padhai aur swasthya par vishesh dhyan diya jata hai.
          </p>

          <div class="grid sm:grid-cols-2 gap-4 pt-2">
            <div class="bg-white/10 border border-white/15 p-3.5 rounded-xl">
              <i class="fa-solid fa-utensils text-dps-gold text-lg mb-1"></i>
              <h4 class="text-xs font-bold text-white uppercase tracking-wider">Hygienic Mess Food</h4>
              <p class="text-[11px] text-slate-300 mt-0.5">Shuddh shakahari aur paushtik taaza bhojan samay anusar.</p>
            </div>
            <div class="bg-white/10 border border-white/15 p-3.5 rounded-xl">
              <i class="fa-solid fa-moon text-dps-gold text-lg mb-1"></i>
              <h4 class="text-xs font-bold text-white uppercase tracking-wider">Evening Supervised Study</h4>
              <p class="text-[11px] text-slate-300 mt-0.5">Adhyapakon ki nigrani me daily night revision aur self-study.</p>
            </div>
            <div class="bg-white/10 border border-white/15 p-3.5 rounded-xl">
              <i class="fa-solid fa-shield-halved text-dps-gold text-lg mb-1"></i>
              <h4 class="text-xs font-bold text-white uppercase tracking-wider">24x7 Security & CCTV</h4>
              <p class="text-[11px] text-slate-300 mt-0.5">Surakshit boundary wall, night guard evam CCTV nigrani.</p>
            </div>
            <div class="bg-white/10 border border-white/15 p-3.5 rounded-xl">
              <i class="fa-solid fa-bolt text-dps-gold text-lg mb-1"></i>
              <h4 class="text-xs font-bold text-white uppercase tracking-wider">Power Backup & RO Water</h4>
              <p class="text-[11px] text-slate-300 mt-0.5">Generator backup aur 100% shuddh peyjal suvidha.</p>
            </div>
          </div>
        </div>

        <div class="lg:col-span-5 bg-white/10 border border-dps-gold/50 rounded-2xl p-6 text-center shadow-xl backdrop-blur-sm">
          <div class="w-16 h-16 rounded-full bg-dps-gold/20 flex items-center justify-center mx-auto text-dps-gold text-2xl mb-3">
            <i class="fa-solid fa-bed"></i>
          </div>
          <h3 class="font-crest text-xl font-bold text-white">Hostel Admission Desk</h3>
          <p class="text-xs text-slate-300 mt-2 mb-4">
            Hostel seat aabantan aur fee structure ke liye Manager Vishnu Kant ji se seedhe phone par sampark karein.
          </p>
          <a href="tel:6395052394" class="block w-full bg-dps-gold hover:bg-dps-goldDark text-dps-navy font-bold py-3 rounded-xl transition text-xs shadow-md">
            <i class="fa-solid fa-phone mr-1.5"></i> Call Hostel Helpline: 6395052394
          </a>
          <a href="#admission-desk" class="block w-full mt-2.5 bg-white/20 hover:bg-white/30 text-white font-medium py-2.5 rounded-xl transition text-xs">
            Form me "Hostel Required" Select Karein
          </a>
        </div>

      </div>
    </div>
  </section>

  <!-- DPS MATHURA ROAD STYLE CAMPUS PHOTO GALLERY & EVENTS SECTION -->
  <section id="gallery-section" class="py-14 bg-dps-surface border-b border-slate-200">
    <div class="max-w-7xl mx-auto px-4">
      
      <!-- Section Title Header -->
      <div class="text-center max-w-2xl mx-auto mb-10">
        <span class="text-xs font-bold text-dps-goldDark tracking-widest uppercase bg-amber-50 px-3 py-1 rounded border border-amber-200">
          Campus Chronicle & Events
        </span>
        <h2 class="font-crest text-2xl sm:text-3xl md:text-4xl font-extrabold text-dps-greenDark mt-2">
          School Gallery & Events
        </h2>
        <p class="text-xs sm:text-sm text-slate-500 mt-1">
          Residential R.B.S. Inter College, Bithara, Aliganj (Etah)
        </p>
        <div class="w-20 h-1 bg-dps-gold mx-auto mt-2.5 rounded-full"></div>
      </div>

      <!-- Gallery Grid (100% Uncropped Faces with Ambient Framing & Lightbox) -->
      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-5">

        <!-- Image 1 -->
        <div class="bg-white rounded-xl overflow-hidden shadow-sm hover:shadow-xl transition border border-slate-200 flex flex-col cursor-pointer group" onclick="openLightbox('rbs12_2.jpeg', 'Student Activity & Award Distribution')">
          <div class="h-64 sm:h-72 bg-slate-950 flex items-center justify-center p-1.5 relative overflow-hidden">
            <img src="rbs12_2.jpeg" alt="Student Activity & Award Distribution" class="max-h-full max-w-full object-contain mx-auto group-hover:scale-105 transition duration-300" onerror="this.src='rbs12.jpeg';" />
            <span class="absolute top-2 left-2 bg-dps-gold text-dps-navy text-[10px] font-bold px-2 py-0.5 rounded shadow">Academics</span>
          </div>
          <div class="p-3 bg-white border-t border-slate-100 flex-1 flex items-center justify-between">
            <p class="text-xs font-semibold text-slate-800">Student Activity & Award Distribution</p>
            <i class="fa-solid fa-expand text-[11px] text-slate-400 group-hover:text-dps-green"></i>
          </div>
        </div>

        <!-- Image 2 -->
        <div class="bg-white rounded-xl overflow-hidden shadow-sm hover:shadow-xl transition border border-slate-200 flex flex-col cursor-pointer group" onclick="openLightbox('rbs11_2.jpeg', 'Cultural Dress Competition')">
          <div class="h-64 sm:h-72 bg-slate-950 flex items-center justify-center p-1.5 relative overflow-hidden">
            <img src="rbs11_2.jpeg" alt="Cultural Dress Competition" class="max-h-full max-w-full object-contain mx-auto group-hover:scale-105 transition duration-300" onerror="this.src='rbs11.jpeg';" />
            <span class="absolute top-2 left-2 bg-purple-600 text-white text-[10px] font-bold px-2 py-0.5 rounded shadow">Cultural</span>
          </div>
          <div class="p-3 bg-white border-t border-slate-100 flex-1 flex items-center justify-between">
            <p class="text-xs font-semibold text-slate-800">Cultural Dress Competition</p>
            <i class="fa-solid fa-expand text-[11px] text-slate-400 group-hover:text-dps-green"></i>
          </div>
        </div>

        <!-- Image 3 -->
        <div class="bg-white rounded-xl overflow-hidden shadow-sm hover:shadow-xl transition border border-slate-200 flex flex-col cursor-pointer group" onclick="openLightbox('rbs10_2.jpeg', 'Group Photo of Students in Drama Attire')">
          <div class="h-64 sm:h-72 bg-slate-950 flex items-center justify-center p-1.5 relative overflow-hidden">
            <img src="rbs10_2.jpeg" alt="Group Photo of Students" class="max-h-full max-w-full object-contain mx-auto group-hover:scale-105 transition duration-300" onerror="this.src='rbs10.jpeg';" />
            <span class="absolute top-2 left-2 bg-blue-600 text-white text-[10px] font-bold px-2 py-0.5 rounded shadow">Drama</span>
          </div>
          <div class="p-3 bg-white border-t border-slate-100 flex-1 flex items-center justify-between">
            <p class="text-xs font-semibold text-slate-800">Group Photo of Students</p>
            <i class="fa-solid fa-expand text-[11px] text-slate-400 group-hover:text-dps-green"></i>
          </div>
        </div>

        <!-- Image 4 -->
        <div class="bg-white rounded-xl overflow-hidden shadow-sm hover:shadow-xl transition border border-slate-200 flex flex-col cursor-pointer group" onclick="openLightbox('rsb9_2.jpeg', 'Staff & Management Celebration')">
          <div class="h-64 sm:h-72 bg-slate-950 flex items-center justify-center p-1.5 relative overflow-hidden">
            <img src="rsb9_2.jpeg" alt="Staff & Management Celebration" class="max-h-full max-w-full object-contain mx-auto group-hover:scale-105 transition duration-300" onerror="this.src='rsb9.jpeg';" />
            <span class="absolute top-2 left-2 bg-emerald-600 text-white text-[10px] font-bold px-2 py-0.5 rounded shadow">Staff Meet</span>
          </div>
          <div class="p-3 bg-white border-t border-slate-100 flex-1 flex items-center justify-between">
            <p class="text-xs font-semibold text-slate-800">Staff & Management Celebration</p>
            <i class="fa-solid fa-expand text-[11px] text-slate-400 group-hover:text-dps-green"></i>
          </div>
        </div>

        <!-- Image 5 -->
        <div class="bg-white rounded-xl overflow-hidden shadow-sm hover:shadow-xl transition border border-slate-200 flex flex-col cursor-pointer group" onclick="openLightbox('rbs8_2.jpeg', 'Republic Day Award Ceremony')">
          <div class="h-64 sm:h-72 bg-slate-950 flex items-center justify-center p-1.5 relative overflow-hidden">
            <img src="rbs8_2.jpeg" alt="Republic Day Award Ceremony" class="max-h-full max-w-full object-contain mx-auto group-hover:scale-105 transition duration-300" onerror="this.src='rbs8.jpeg';" />
            <span class="absolute top-2 left-2 bg-red-600 text-white text-[10px] font-bold px-2 py-0.5 rounded shadow">26th Jan</span>
          </div>
          <div class="p-3 bg-white border-t border-slate-100 flex-1 flex items-center justify-between">
            <p class="text-xs font-semibold text-slate-800">Republic Day Award Ceremony</p>
            <i class="fa-solid fa-expand text-[11px] text-slate-400 group-hover:text-dps-green"></i>
          </div>
        </div>

        <!-- Image 6 -->
        <div class="bg-white rounded-xl overflow-hidden shadow-sm hover:shadow-xl transition border border-slate-200 flex flex-col cursor-pointer group" onclick="openLightbox('rbs7_2.jpeg', 'Classroom Teaching Session')">
          <div class="h-64 sm:h-72 bg-slate-950 flex items-center justify-center p-1.5 relative overflow-hidden">
            <img src="rbs7_2.jpeg" alt="Classroom Teaching Session" class="max-h-full max-w-full object-contain mx-auto group-hover:scale-105 transition duration-300" onerror="this.src='rbs7.jpeg';" />
            <span class="absolute top-2 left-2 bg-cyan-700 text-white text-[10px] font-bold px-2 py-0.5 rounded shadow">Lecture</span>
          </div>
          <div class="p-3 bg-white border-t border-slate-100 flex-1 flex items-center justify-between">
            <p class="text-xs font-semibold text-slate-800">Classroom Teaching Session</p>
            <i class="fa-solid fa-expand text-[11px] text-slate-400 group-hover:text-dps-green"></i>
          </div>
        </div>

        <!-- Image 7 -->
        <div class="bg-white rounded-xl overflow-hidden shadow-sm hover:shadow-xl transition border border-slate-200 flex flex-col cursor-pointer group" onclick="openLightbox('rbs6_2.jpeg', 'Medal & Certificate Distribution')">
          <div class="h-64 sm:h-72 bg-slate-950 flex items-center justify-center p-1.5 relative overflow-hidden">
            <img src="rbs6_2.jpeg" alt="Medal & Certificate Distribution" class="max-h-full max-w-full object-contain mx-auto group-hover:scale-105 transition duration-300" onerror="this.src='rbs6.jpeg';" />
            <span class="absolute top-2 left-2 bg-amber-600 text-white text-[10px] font-bold px-2 py-0.5 rounded shadow">Samman</span>
          </div>
          <div class="p-3 bg-white border-t border-slate-100 flex-1 flex items-center justify-between">
            <p class="text-xs font-semibold text-slate-800">Medal & Certificate Distribution</p>
            <i class="fa-solid fa-expand text-[11px] text-slate-400 group-hover:text-dps-green"></i>
          </div>
        </div>

        <!-- Image 8 -->
        <div class="bg-white rounded-xl overflow-hidden shadow-sm hover:shadow-xl transition border border-slate-200 flex flex-col cursor-pointer group" onclick="openLightbox('rbs5_2.jpeg', 'School Campus & Building View')">
          <div class="h-64 sm:h-72 bg-slate-950 flex items-center justify-center p-1.5 relative overflow-hidden">
            <img src="rbs5_2.jpeg" alt="School Campus & Building View" class="max-h-full max-w-full object-contain mx-auto group-hover:scale-105 transition duration-300" onerror="this.src='rbs5.jpeg';" />
            <span class="absolute top-2 left-2 bg-emerald-700 text-white text-[10px] font-bold px-2 py-0.5 rounded shadow">Campus</span>
          </div>
          <div class="p-3 bg-white border-t border-slate-100 flex-1 flex items-center justify-between">
            <p class="text-xs font-semibold text-slate-800">School Campus & Building View</p>
            <i class="fa-solid fa-expand text-[11px] text-slate-400 group-hover:text-dps-green"></i>
          </div>
        </div>

        <!-- Image 9 -->
        <div class="bg-white rounded-xl overflow-hidden shadow-sm hover:shadow-xl transition border border-slate-200 flex flex-col cursor-pointer group" onclick="openLightbox('rbs4_2.jpeg', 'School Function & Parade')">
          <div class="h-64 sm:h-72 bg-slate-950 flex items-center justify-center p-1.5 relative overflow-hidden">
            <img src="rbs4_2.jpeg" alt="School Function & Parade" class="max-h-full max-w-full object-contain mx-auto group-hover:scale-105 transition duration-300" onerror="this.src='rbs4.jpeg';" />
            <span class="absolute top-2 left-2 bg-rose-600 text-white text-[10px] font-bold px-2 py-0.5 rounded shadow">Parade</span>
          </div>
          <div class="p-3 bg-white border-t border-slate-100 flex-1 flex items-center justify-between">
            <p class="text-xs font-semibold text-slate-800">School Function & Parade</p>
            <i class="fa-solid fa-expand text-[11px] text-slate-400 group-hover:text-dps-green"></i>
          </div>
        </div>

        <!-- Image 10 -->
        <div class="bg-white rounded-xl overflow-hidden shadow-sm hover:shadow-xl transition border border-slate-200 flex flex-col cursor-pointer group" onclick="openLightbox('rbs2_2.jpeg', 'Stage Program & Performances')">
          <div class="h-64 sm:h-72 bg-slate-950 flex items-center justify-center p-1.5 relative overflow-hidden">
            <img src="rbs2_2.jpeg" alt="Stage Program & Performances" class="max-h-full max-w-full object-contain mx-auto group-hover:scale-105 transition duration-300" onerror="this.src='rbs2.jpeg';" />
            <span class="absolute top-2 left-2 bg-indigo-600 text-white text-[10px] font-bold px-2 py-0.5 rounded shadow">Stage</span>
          </div>
          <div class="p-3 bg-white border-t border-slate-100 flex-1 flex items-center justify-between">
            <p class="text-xs font-semibold text-slate-800">Stage Program & Performances</p>
            <i class="fa-solid fa-expand text-[11px] text-slate-400 group-hover:text-dps-green"></i>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- LIGHTBOX MODAL (Full Screen Photo Inspector) -->
  <div id="galleryLightbox" class="fixed inset-0 bg-black/90 backdrop-blur-md z-50 flex flex-col items-center justify-center p-4 hidden" onclick="closeLightbox()">
    <button onclick="closeLightbox()" class="absolute top-4 right-5 text-white/80 hover:text-white text-3xl">
      <i class="fa-solid fa-xmark"></i>
    </button>
    <div class="max-w-4xl max-h-[85vh] p-2 flex flex-col items-center" onclick="event.stopPropagation()">
      <img id="lightboxImg" src="" alt="Full view" class="max-h-[75vh] max-w-full object-contain rounded-lg shadow-2xl border border-white/20" />
      <p id="lightboxCaption" class="text-white text-sm font-medium mt-3 text-center bg-black/60 px-4 py-1.5 rounded-full border border-white/20"></p>
    </div>
  </div>

  <!-- INFRASTRUCTURE SECTION (DPS Mathura Road "Built for Excellence") -->
  <section class="py-14 bg-white border-b border-slate-200">
    <div class="max-w-7xl mx-auto px-4">
      <div class="text-center max-w-2xl mx-auto mb-10">
        <span class="text-xs font-bold text-dps-goldDark tracking-widest uppercase">Infrastructure</span>
        <h2 class="font-crest text-2xl sm:text-3xl font-extrabold text-dps-greenDark mt-1">Built for Academic Excellence</h2>
        <p class="text-xs text-slate-500 mt-1">A vibrant campus with amenities designed to foster enriching learning experiences.</p>
      </div>

      <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-6 gap-4 text-center">
        <div class="bg-dps-surface p-4 rounded-xl border border-slate-200 hover:border-dps-gold transition">
          <i class="fa-solid fa-flask-vial text-2xl text-dps-green mb-2"></i>
          <h4 class="text-xs font-bold text-slate-800">Science Labs</h4>
          <span class="text-[10px] text-slate-500">Physics & Chem</span>
        </div>
        <div class="bg-dps-surface p-4 rounded-xl border border-slate-200 hover:border-dps-gold transition">
          <i class="fa-solid fa-laptop-code text-2xl text-blue-600 mb-2"></i>
          <h4 class="text-xs font-bold text-slate-800">Computer Lab</h4>
          <span class="text-[10px] text-slate-500">Digital Education</span>
        </div>
        <div class="bg-dps-surface p-4 rounded-xl border border-slate-200 hover:border-dps-gold transition">
          <i class="fa-solid fa-book text-2xl text-purple-600 mb-2"></i>
          <h4 class="text-xs font-bold text-slate-800">Library</h4>
          <span class="text-[10px] text-slate-500">Curated Books</span>
        </div>
        <div class="bg-dps-surface p-4 rounded-xl border border-slate-200 hover:border-dps-gold transition">
          <i class="fa-solid fa-futbol text-2xl text-emerald-600 mb-2"></i>
          <h4 class="text-xs font-bold text-slate-800">Sports Ground</h4>
          <span class="text-[10px] text-slate-500">Cricket & Athletics</span>
        </div>
        <div class="bg-dps-surface p-4 rounded-xl border border-slate-200 hover:border-dps-gold transition">
          <i class="fa-solid fa-shield-virus text-2xl text-amber-600 mb-2"></i>
          <h4 class="text-xs font-bold text-slate-800">RO Water</h4>
          <span class="text-[10px] text-slate-500">Purified Drinking</span>
        </div>
        <div class="bg-dps-surface p-4 rounded-xl border border-slate-200 hover:border-dps-gold transition">
          <i class="fa-solid fa-video text-2xl text-rose-600 mb-2"></i>
          <h4 class="text-xs font-bold text-slate-800">CCTV Safety</h4>
          <span class="text-[10px] text-slate-500">24x7 Monitored</span>
        </div>
      </div>
    </div>
  </section>

  <!-- ONLINE ADMISSION DESK (Session 2026 - 2027) -->
  <section id="admission-desk" class="py-14 bg-dps-surface">
    <div class="max-w-4xl mx-auto px-4">
      <div class="text-center mb-8">
        <span class="text-xs font-bold text-dps-goldDark tracking-widest uppercase bg-amber-50 px-3 py-1 rounded border border-amber-200">Session 2026 - 2027</span>
        <h2 class="font-crest text-2xl sm:text-3xl md:text-4xl font-extrabold text-dps-greenDark mt-2">
          Online Admission Registration Desk
        </h2>
        <p class="text-xs sm:text-sm text-slate-500 mt-1">
          Apply online for Class 1st to 12th. Details are submitted directly to the Manager's administrative portal.
        </p>
      </div>

      <div class="bg-white border-2 border-slate-200 rounded-3xl p-6 sm:p-8 shadow-xl relative">
        <form id="onlineAdmissionForm" onsubmit="handleAdmissionSubmit(event)" class="space-y-4">
          <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
            <div>
              <label class="block text-xs font-bold text-slate-700 mb-1">Student Full Name *</label>
              <input type="text" id="admStudentName" required placeholder="Chhatra / Chhatra Ka Naam" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-xs sm:text-sm focus:ring-2 focus:ring-dps-gold outline-none" />
            </div>
            <div>
              <label class="block text-xs font-bold text-slate-700 mb-1">Father's Full Name *</label>
              <input type="text" id="admFatherName" required placeholder="Pita Ka Naam" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-xs sm:text-sm focus:ring-2 focus:ring-dps-gold outline-none" />
            </div>
          </div>

          <div class="grid grid-cols-1 sm:grid-cols-3 gap-4">
            <div>
              <label class="block text-xs font-bold text-slate-700 mb-1">Admission For Class *</label>
              <select id="admClass" required class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-xs sm:text-sm focus:ring-2 focus:ring-dps-gold outline-none">
                <option value="">-- Select Class --</option>
                <option value="Class 1">Class 1</option>
                <option value="Class 2">Class 2</option>
                <option value="Class 3">Class 3</option>
                <option value="Class 4">Class 4</option>
                <option value="Class 5">Class 5</option>
                <option value="Class 6">Class 6</option>
                <option value="Class 7">Class 7</option>
                <option value="Class 8">Class 8</option>
                <option value="Class 9">Class 9 (High School Prep)</option>
                <option value="Class 10">Class 10 (UP Board)</option>
                <option value="Class 11 (Science)">Class 11 (Science Stream)</option>
                <option value="Class 11 (Arts)">Class 11 (Arts Stream)</option>
                <option value="Class 12 (Science)">Class 12 (Science Stream)</option>
                <option value="Class 12 (Arts)">Class 12 (Arts Stream)</option>
              </select>
            </div>
            <div>
              <label class="block text-xs font-bold text-slate-700 mb-1">Date of Birth *</label>
              <input type="date" id="admDOB" required class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-xs sm:text-sm focus:ring-2 focus:ring-dps-gold outline-none" />
            </div>
            <div>
              <label class="block text-xs font-bold text-slate-700 mb-1">Mobile / WhatsApp No. *</label>
              <input type="tel" id="admMobile" required pattern="[0-9]{10}" placeholder="10 Digit Number" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-xs sm:text-sm focus:ring-2 focus:ring-dps-gold outline-none" />
            </div>
          </div>

          <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
            <div>
              <label class="block text-xs font-bold text-slate-700 mb-1">Hostel Facility Needed? *</label>
              <select id="admHostel" required class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-xs sm:text-sm focus:ring-2 focus:ring-dps-gold outline-none">
                <option value="Yes">Haan, Residential Hostel Chahiye</option>
                <option value="No" selected>Nahi, Day Scholar (Aana-Jana)</option>
              </select>
            </div>
            <div>
              <label class="block text-xs font-bold text-slate-700 mb-1">Previous School / Marks %</label>
              <input type="text" id="admPrevious" placeholder="Last School & Percentage" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-xs sm:text-sm focus:ring-2 focus:ring-dps-gold outline-none" />
            </div>
          </div>

          <div>
            <label class="block text-xs font-bold text-slate-700 mb-1">Complete Address / Village / Tehsil *</label>
            <textarea id="admAddress" rows="2" required placeholder="Gram, Post, Tehsil, District & Pin Code (e.g. Bithara, Aliganj, Etah)" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-xs sm:text-sm focus:ring-2 focus:ring-dps-gold outline-none"></textarea>
          </div>

          <button type="submit" class="w-full bg-dps-green hover:bg-dps-greenDark text-dps-goldLight font-bold py-3.5 rounded-xl transition shadow-lg text-xs sm:text-sm flex items-center justify-center gap-2">
            <i class="fa-solid fa-paper-plane"></i> Submit Online Admission Application
          </button>
        </form>

        <!-- Dynamic Success Receipt -->
        <div id="admSuccessReceipt" class="hidden mt-6 bg-gradient-to-r from-amber-50 via-emerald-50 to-white border-2 border-emerald-500 rounded-2xl p-5 text-slate-800 shadow-md">
          <div class="flex items-start gap-4">
            <img src="image_a45465.jpg" alt="RBS Logo" class="w-14 h-14 rounded-full border-2 border-dps-gold shadow shrink-0 bg-white" />
            <div class="flex-1">
              <div class="flex flex-wrap items-center justify-between gap-2">
                <h4 class="font-crest text-base font-bold text-dps-greenDark">Application Registered Successfully!</h4>
                <span class="font-mono text-xs bg-white px-2.5 py-1 rounded border border-emerald-300 font-extrabold text-emerald-800" id="receiptRegId">RBS-2026-000</span>
              </div>
              <p class="text-xs text-slate-600 mt-1" id="receiptSummaryText"></p>
              
              <div class="mt-4 flex flex-wrap gap-2.5">
                <button onclick="window.print()" class="bg-dps-green hover:bg-dps-greenDark text-white text-xs px-4 py-2 rounded-lg font-bold flex items-center gap-1.5 shadow">
                  <i class="fa-solid fa-print text-dps-gold"></i> Print Slip
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

  <!-- FOOTER SECTION (DPS Mathura Road Layout) -->
  <footer class="bg-dps-greenDark text-slate-300 pt-14 pb-8 border-t-4 border-dps-gold">
    <div class="max-w-7xl mx-auto px-4 grid grid-cols-1 md:grid-cols-12 gap-8 mb-10">
      
      <!-- Column 1: School Identity -->
      <div class="md:col-span-5 space-y-3">
        <div class="flex items-center gap-3.5">
          <img src="image_a45465.jpg" alt="RBS Seal" class="w-14 h-14 rounded-full border border-dps-gold bg-white p-0.5" />
          <div>
            <h3 class="font-crest font-extrabold text-white text-base leading-tight">RAM BAX SINGH INTER COLLEGE</h3>
            <p class="text-xs text-dps-goldLight">Residential R.B.S. Inter College &bull; Bithara (Aliganj)</p>
          </div>
        </div>
        <p class="text-xs text-slate-300 leading-relaxed">
          Affiliated to the Board of High School and Intermediate Education U.P. Dedicated to nurturing disciplined, virtuous, and academically brilliant scholars from Class 1st to 12th.
        </p>
        <div class="pt-1 flex gap-2">
          <span class="bg-white/10 text-white text-[11px] px-2.5 py-1 rounded border border-white/20">Class 1 to 12</span>
          <span class="bg-white/10 text-white text-[11px] px-2.5 py-1 rounded border border-white/20">Residential Hostel</span>
          <span class="bg-white/10 text-white text-[11px] px-2.5 py-1 rounded border border-white/20">Aliganj (Etah)</span>
        </div>
      </div>

      <!-- Column 2: Navigation Links -->
      <div class="md:col-span-3 space-y-2">
        <h4 class="font-crest text-xs font-bold text-dps-goldLight uppercase tracking-wider">Quick Navigation</h4>
        <ul class="text-xs space-y-2 text-slate-300">
          <li><a href="#about-section" class="hover:text-white transition">About R.B.S. College</a></li>
          <li><a href="#dignitaries" class="hover:text-white transition">Our Dignitaries (Director & Manager)</a></li>
          <li><a href="#wings-section" class="hover:text-white transition">Academics (Class 1st to 12th)</a></li>
          <li><a href="#hostel-section" class="hover:text-white transition">Residential Hostel Facility</a></li>
          <li><a href="#gallery-section" class="hover:text-white transition">Campus Gallery & Events</a></li>
          <li><a href="#admission-desk" class="hover:text-white transition text-dps-gold font-semibold">Online Admission Form</a></li>
        </ul>
      </div>

      <!-- Column 3: Contact & Leadership Info -->
      <div class="md:col-span-4 space-y-2.5 text-xs text-slate-300">
        <h4 class="font-crest text-xs font-bold text-dps-goldLight uppercase tracking-wider">Contact & Campus Office</h4>
        <p class="flex items-start gap-2">
          <i class="fa-solid fa-location-dot text-dps-gold mt-1"></i>
          <span>Bithara - Sarai Road, Aliganj, Dist. Etah (U.P.) - 207247</span>
        </p>
        <p class="flex items-center gap-2">
          <i class="fa-solid fa-user-tie text-dps-gold"></i>
          <span><strong>Director:</strong> Shri Avadhesh Singh</span>
        </p>
        <p class="flex items-center gap-2">
          <i class="fa-solid fa-user-check text-dps-gold"></i>
          <span><strong>Manager:</strong> Shri Vishnu Kant</span>
        </p>
        <p class="flex items-center gap-2">
          <i class="fa-solid fa-phone text-dps-gold"></i>
          <a href="tel:6395052394" class="hover:text-dps-goldLight font-bold">6395052394</a>
        </p>
        <p class="flex items-center gap-2">
          <i class="fa-solid fa-envelope text-dps-gold"></i>
          <span>rambaxsinghintercollege@gmail.com</span>
        </p>
      </div>

    </div>

    <!-- Bottom Copyright & Developer Row -->
    <div class="max-w-7xl mx-auto px-4 pt-6 border-t border-white/10 text-xs text-slate-400 flex flex-wrap justify-between items-center gap-2">
      <div>© 2026 Ram Bax Singh Inter College, Bithara (Aliganj). All rights reserved.</div>
      <div class="flex items-center gap-3">
        <button onclick="openAdminModal()" class="text-dps-gold hover:underline font-semibold">
          <i class="fa-solid fa-lock text-[10px]"></i> Staff & Admin Login
        </button>
      </div>
    </div>
  </footer>

  <!-- ADMIN LOGIN MODAL -->
  <div id="adminLoginModal" class="fixed inset-0 bg-black/75 backdrop-blur-sm z-50 flex items-center justify-center p-4 hidden">
    <div class="bg-white rounded-3xl max-w-md w-full p-6 sm:p-8 shadow-2xl border-2 border-dps-gold relative">
      <button onclick="closeAdminModal()" class="absolute top-4 right-4 text-slate-400 hover:text-slate-700 text-lg">
        <i class="fa-solid fa-xmark"></i>
      </button>

      <div class="text-center mb-6">
        <img src="image_a45465.jpg" alt="RBS Crest" class="w-16 h-16 rounded-full border-2 border-dps-gold mx-auto mb-2 bg-white" />
        <h3 class="font-crest text-xl font-bold text-dps-greenDark">R.B.S. Admin Portal</h3>
        <p class="text-xs text-slate-500">Director & Manager Control Suite</p>
      </div>

      <form onsubmit="handleAdminLogin(event)" class="space-y-4">
        <div>
          <label class="block text-xs font-bold text-slate-700 mb-1">Admin Email ID</label>
          <input type="email" id="adminUserEmail" required placeholder="rambaxsinghintercollege@gmail.com" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-xs sm:text-sm focus:ring-2 focus:ring-dps-gold outline-none" />
        </div>
        <div>
          <label class="block text-xs font-bold text-slate-700 mb-1">Password</label>
          <input type="password" id="adminPassword" required placeholder="••••••••••••" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-xs sm:text-sm focus:ring-2 focus:ring-dps-gold outline-none" />
        </div>
        
        <div id="loginErrorMessage" class="hidden text-xs text-rose-700 bg-rose-50 p-2.5 rounded-lg border border-rose-200">
          Invalid Credentials! Kripya sahi Admin ID aur Password dalein.
        </div>

        <button type="submit" class="w-full bg-dps-green hover:bg-dps-greenDark text-dps-goldLight font-bold py-3 rounded-xl transition text-xs sm:text-sm shadow">
          <i class="fa-solid fa-right-to-bracket mr-2"></i> Log In To Dashboard
        </button>
      </form>

      <div class="mt-4 pt-4 border-t border-slate-100 flex justify-between items-center text-xs text-slate-500">
        <span>Manager: Vishnu Kant</span>
        <button onclick="fillAdminCredentials()" class="text-dps-goldDark font-semibold hover:underline">
          <i class="fa-solid fa-key mr-1"></i> Auto-fill Login
        </button>
      </div>
    </div>
  </div>

  <!-- ADMIN DASHBOARD FULL SCREEN WORKSPACE -->
  <div id="adminDashboard" class="fixed inset-0 bg-slate-900/90 backdrop-blur-md z-50 flex overflow-y-auto hidden">
    <div class="bg-white min-h-screen w-full flex flex-col">
      
      <!-- Admin Top Nav -->
      <header class="bg-dps-greenDark text-white px-6 py-4 flex flex-wrap justify-between items-center border-b-2 border-dps-gold">
        <div class="flex items-center gap-3">
          <img src="image_a45465.jpg" alt="RBS Crest" class="w-10 h-10 rounded-full border border-dps-gold bg-white p-0.5" />
          <div>
            <h2 class="font-crest text-base sm:text-lg font-bold">Ram Bax Singh Inter College &bull; Admin Suite</h2>
            <p class="text-[11px] text-dps-goldLight">Manager: Vishnu Kant | ID: rambaxsinghintercollege@gmail.com</p>
          </div>
        </div>

        <div class="flex items-center gap-3">
          <button onclick="switchAdminTab('admissions')" id="tabBtnAdmissions" class="px-3 py-1.5 rounded-lg text-xs font-bold bg-dps-gold text-dps-navy transition">
            <i class="fa-solid fa-list-check mr-1.5"></i> Admissions List (<span id="admissionCount">0</span>)
          </button>
          <button onclick="switchAdminTab('marksheet')" id="tabBtnMarksheet" class="px-3 py-1.5 rounded-lg text-xs font-bold bg-white/10 hover:bg-white/20 text-white transition">
            <i class="fa-solid fa-award mr-1.5"></i> Marksheet Studio
          </button>
          <button onclick="logoutAdmin()" class="bg-rose-600 hover:bg-rose-700 text-white text-xs font-semibold px-3 py-1.5 rounded-lg transition ml-2">
            <i class="fa-solid fa-arrow-right-from-bracket mr-1"></i> Logout
          </button>
        </div>
      </header>

      <!-- TAB 1: ADMISSIONS LIST -->
      <div id="tabAdmissions" class="p-6 max-w-7xl mx-auto w-full flex-1">
        <div class="flex flex-wrap justify-between items-center gap-4 mb-4">
          <div>
            <h3 class="font-crest text-xl font-bold text-dps-greenDark">Online Admission Inquiries (Class 1 to 12)</h3>
            <p class="text-xs text-slate-500">Website se aaye huye aavedan yahan live track hote hain.</p>
          </div>
          <div class="flex gap-2">
            <button onclick="exportAdmissionsCSV()" class="bg-emerald-600 hover:bg-emerald-700 text-white text-xs font-semibold px-3.5 py-2 rounded-xl transition flex items-center gap-1.5">
              <i class="fa-solid fa-file-excel"></i> Export CSV
            </button>
            <button onclick="clearAllAdmissions()" class="bg-slate-200 hover:bg-rose-100 text-rose-700 text-xs font-semibold px-3 py-2 rounded-xl transition">
              <i class="fa-solid fa-trash-can"></i> Clear All
            </button>
          </div>
        </div>

        <div class="bg-white rounded-2xl border border-slate-200 shadow overflow-hidden">
          <div class="overflow-x-auto">
            <table class="w-full text-left text-xs">
              <thead class="bg-slate-100 text-slate-700 uppercase font-bold border-b">
                <tr>
                  <th class="p-3">Ref ID</th>
                  <th class="p-3">Student Name</th>
                  <th class="p-3">Father Name</th>
                  <th class="p-3">Class</th>
                  <th class="p-3">Mobile No.</th>
                  <th class="p-3">Hostel</th>
                  <th class="p-3">Address</th>
                  <th class="p-3">Date</th>
                  <th class="p-3 text-right">Actions</th>
                </tr>
              </thead>
              <tbody id="admissionsTableBody" class="divide-y divide-slate-100 text-slate-700">
                <!-- Dynamically populated -->
              </tbody>
            </table>
          </div>
          <div id="emptyAdmissionsState" class="p-10 text-center text-slate-400 hidden">
            <i class="fa-regular fa-folder-open text-4xl mb-2 text-slate-300"></i>
            <p>Abhi tak koi naya admission aavedan praapt nahi hua hai.</p>
          </div>
        </div>
      </div>

      <!-- TAB 2: MARKSHEET GENERATOR WITH AUTOCALCULATION -->
      <div id="tabMarksheet" class="p-6 max-w-7xl mx-auto w-full flex-1 hidden">
        <div class="grid lg:grid-cols-12 gap-6">
          
          <!-- Data Entry Form Column -->
          <div class="lg:col-span-5 bg-white p-5 rounded-2xl border border-slate-200 shadow-sm space-y-4">
            <div class="border-b pb-3">
              <h3 class="font-crest text-lg font-bold text-dps-greenDark">Marksheet Data Studio</h3>
              <p class="text-xs text-slate-500">Student detail dalein, sabhi total, % aur division auto calculate honge.</p>
            </div>

            <div class="space-y-3 text-xs">
              <div class="grid grid-cols-2 gap-2">
                <div>
                  <label class="block font-bold text-slate-700 mb-1">Student Name *</label>
                  <input type="text" id="msStudentName" oninput="updateMarksheetPreview()" placeholder="Chhatra ka naam" value="Amit Kumar" class="w-full px-2.5 py-1.5 border rounded-lg focus:ring-1 focus:ring-dps-gold outline-none" />
                </div>
                <div>
                  <label class="block font-bold text-slate-700 mb-1">Father's Name *</label>
                  <input type="text" id="msFatherName" oninput="updateMarksheetPreview()" placeholder="Pita ka naam" value="Shri Ramesh Chandra" class="w-full px-2.5 py-1.5 border rounded-lg focus:ring-1 focus:ring-dps-gold outline-none" />
                </div>
              </div>

              <div class="grid grid-cols-3 gap-2">
                <div>
                  <label class="block font-bold text-slate-700 mb-1">Roll Number *</label>
                  <input type="text" id="msRollNo" oninput="updateMarksheetPreview()" value="2026101" class="w-full px-2.5 py-1.5 border rounded-lg focus:ring-1 focus:ring-dps-gold outline-none" />
                </div>
                <div>
                  <label class="block font-bold text-slate-700 mb-1">Class *</label>
                  <select id="msClass" onchange="updateMarksheetPreview()" class="w-full px-2 py-1.5 border rounded-lg focus:ring-1 focus:ring-dps-gold outline-none">
                    <option value="Class 1">Class 1</option>
                    <option value="Class 2">Class 2</option>
                    <option value="Class 3">Class 3</option>
                    <option value="Class 4">Class 4</option>
                    <option value="Class 5">Class 5</option>
                    <option value="Class 6">Class 6</option>
                    <option value="Class 7">Class 7</option>
                    <option value="Class 8">Class 8</option>
                    <option value="Class 9">Class 9</option>
                    <option value="Class 10" selected>Class 10 (High School)</option>
                    <option value="Class 11 (Science)">Class 11 (Science)</option>
                    <option value="Class 11 (Arts)">Class 11 (Arts)</option>
                    <option value="Class 12 (Science)">Class 12 (Science)</option>
                    <option value="Class 12 (Arts)">Class 12 (Arts)</option>
                  </select>
                </div>
                <div>
                  <label class="block font-bold text-slate-700 mb-1">Session</label>
                  <input type="text" id="msSession" oninput="updateMarksheetPreview()" value="2025-2026" class="w-full px-2.5 py-1.5 border rounded-lg focus:ring-1 focus:ring-dps-gold outline-none" />
                </div>
              </div>

              <div>
                <label class="block font-bold text-slate-700 mb-1">Address / Village *</label>
                <input type="text" id="msAddress" oninput="updateMarksheetPreview()" value="Bithara, Aliganj (Etah)" class="w-full px-2.5 py-1.5 border rounded-lg focus:ring-1 focus:ring-dps-gold outline-none" />
              </div>

              <!-- Subject Marks Entry -->
              <div class="border-t pt-3">
                <label class="block font-bold text-dps-greenDark mb-2">Subject Marks (Total 100 Each)</label>
                <div class="space-y-1.5 max-h-56 overflow-y-auto pr-1">
                  <div class="flex items-center justify-between gap-2 bg-slate-50 p-1.5 rounded border">
                    <span class="w-28 font-medium">1. Hindi</span>
                    <input type="number" id="sub1" min="0" max="100" value="84" oninput="updateMarksheetPreview()" class="w-20 px-2 py-1 border rounded text-right font-semibold" />
                  </div>
                  <div class="flex items-center justify-between gap-2 bg-slate-50 p-1.5 rounded border">
                    <span class="w-28 font-medium">2. English</span>
                    <input type="number" id="sub2" min="0" max="100" value="78" oninput="updateMarksheetPreview()" class="w-20 px-2 py-1 border rounded text-right font-semibold" />
                  </div>
                  <div class="flex items-center justify-between gap-2 bg-slate-50 p-1.5 rounded border">
                    <span class="w-28 font-medium">3. Mathematics</span>
                    <input type="number" id="sub3" min="0" max="100" value="91" oninput="updateMarksheetPreview()" class="w-20 px-2 py-1 border rounded text-right font-semibold" />
                  </div>
                  <div class="flex items-center justify-between gap-2 bg-slate-50 p-1.5 rounded border">
                    <span class="w-28 font-medium">4. Science</span>
                    <input type="number" id="sub4" min="0" max="100" value="86" oninput="updateMarksheetPreview()" class="w-20 px-2 py-1 border rounded text-right font-semibold" />
                  </div>
                  <div class="flex items-center justify-between gap-2 bg-slate-50 p-1.5 rounded border">
                    <span class="w-28 font-medium">5. Social Science</span>
                    <input type="number" id="sub5" min="0" max="100" value="80" oninput="updateMarksheetPreview()" class="w-20 px-2 py-1 border rounded text-right font-semibold" />
                  </div>
                  <div class="flex items-center justify-between gap-2 bg-slate-50 p-1.5 rounded border">
                    <span class="w-28 font-medium">6. Sanskrit / Drawing</span>
                    <input type="number" id="sub6" min="0" max="100" value="92" oninput="updateMarksheetPreview()" class="w-20 px-2 py-1 border rounded text-right font-semibold" />
                  </div>
                </div>
              </div>

              <div class="pt-2">
                <button onclick="window.print()" class="w-full bg-emerald-600 hover:bg-emerald-700 text-white font-bold py-2.5 rounded-xl transition text-xs shadow flex items-center justify-center gap-2">
                  <i class="fa-solid fa-print"></i> Print Official Marksheet
                </button>
              </div>
            </div>
          </div>

          <!-- Printable Marksheet Certificate Column -->
          <div class="lg:col-span-7">
            <div id="printableMarksheet" class="bg-white border-4 border-double border-dps-greenDark p-6 rounded-2xl shadow-xl crest-watermark relative text-slate-900">
              
              <!-- Certificate Top Header -->
              <div class="flex items-center justify-between border-b-2 border-dps-gold pb-4 gap-4">
                <img src="image_a45465.jpg" alt="RBS Logo" class="w-20 h-20 object-contain rounded-full border border-dps-gold bg-white p-0.5" />
                <div class="text-center flex-1">
                  <h1 class="font-crest font-black text-xl sm:text-2xl text-dps-greenDark tracking-tight">
                    RAM BAX SINGH INTER COLLEGE
                  </h1>
                  <div class="text-xs font-bold text-dps-goldDark">BITHARA (ALIGANJ, ETAH) - 207247</div>
                  <p class="text-[10px] text-slate-500 font-semibold uppercase tracking-wider">Affiliated to Board of High School and Intermediate Education, U.P.</p>
                  <div class="mt-1 inline-block bg-dps-green text-dps-goldLight text-[11px] font-bold px-3 py-0.5 rounded-full uppercase tracking-wider">
                    Official Annual Progress Report / Marksheet
                  </div>
                </div>
                <div class="w-20 text-center">
                  <span class="text-[9px] block text-slate-400">SR NO.</span>
                  <span id="pvSrNo" class="text-xs font-mono font-bold text-slate-800">RBS-2026</span>
                </div>
              </div>

              <!-- Student Details Grid -->
              <div class="my-4 bg-slate-50/90 p-3 rounded-lg border border-slate-200 text-xs grid grid-cols-2 gap-2">
                <div><span class="text-slate-500">Student Name:</span> <strong id="pvName" class="text-dps-greenDark font-bold uppercase">Amit Kumar</strong></div>
                <div><span class="text-slate-500">Roll Number:</span> <strong id="pvRoll" class="text-slate-900 font-mono font-bold">2026101</strong></div>
                <div><span class="text-slate-500">Father's Name:</span> <strong id="pvFather" class="text-slate-900">Shri Ramesh Chandra</strong></div>
                <div><span class="text-slate-500">Class & Section:</span> <strong id="pvClass" class="text-slate-900">Class 10 (High School)</strong></div>
                <div><span class="text-slate-500">Academic Session:</span> <strong id="pvSession" class="text-slate-900">2025-2026</strong></div>
                <div><span class="text-slate-500">Address / Village:</span> <strong id="pvAddress" class="text-slate-900">Bithara, Aliganj (Etah)</strong></div>
              </div>

              <!-- Marks Table -->
              <table class="w-full text-xs text-left border-collapse border border-slate-300">
                <thead class="bg-dps-green text-white text-center">
                  <tr>
                    <th class="p-1.5 border border-slate-300 text-left">Subject Description</th>
                    <th class="p-1.5 border border-slate-300 w-20">Max Marks</th>
                    <th class="p-1.5 border border-slate-300 w-20">Min Marks</th>
                    <th class="p-1.5 border border-slate-300 w-24">Marks Obtained</th>
                    <th class="p-1.5 border border-slate-300 w-20">Grade</th>
                  </tr>
                </thead>
                <tbody class="text-center font-medium divide-y">
                  <tr>
                    <td class="p-1.5 border border-slate-300 text-left font-semibold">1. Hindi</td>
                    <td class="p-1.5 border border-slate-300">100</td>
                    <td class="p-1.5 border border-slate-300">33</td>
                    <td id="pvSub1" class="p-1.5 border border-slate-300 font-bold">84</td>
                    <td id="pvG1" class="p-1.5 border border-slate-300">A</td>
                  </tr>
                  <tr>
                    <td class="p-1.5 border border-slate-300 text-left font-semibold">2. English</td>
                    <td class="p-1.5 border border-slate-300">100</td>
                    <td class="p-1.5 border border-slate-300">33</td>
                    <td id="pvSub2" class="p-1.5 border border-slate-300 font-bold">78</td>
                    <td id="pvG2" class="p-1.5 border border-slate-300">B1</td>
                  </tr>
                  <tr>
                    <td class="p-1.5 border border-slate-300 text-left font-semibold">3. Mathematics</td>
                    <td class="p-1.5 border border-slate-300">100</td>
                    <td class="p-1.5 border border-slate-300">33</td>
                    <td id="pvSub3" class="p-1.5 border border-slate-300 font-bold">91</td>
                    <td id="pvG3" class="p-1.5 border border-slate-300">A+</td>
                  </tr>
                  <tr>
                    <td class="p-1.5 border border-slate-300 text-left font-semibold">4. Science</td>
                    <td class="p-1.5 border border-slate-300">100</td>
                    <td class="p-1.5 border border-slate-300">33</td>
                    <td id="pvSub4" class="p-1.5 border border-slate-300 font-bold">86</td>
                    <td id="pvG4" class="p-1.5 border border-slate-300">A</td>
                  </tr>
                  <tr>
                    <td class="p-1.5 border border-slate-300 text-left font-semibold">5. Social Science</td>
                    <td class="p-1.5 border border-slate-300">100</td>
                    <td class="p-1.5 border border-slate-300">33</td>
                    <td id="pvSub5" class="p-1.5 border border-slate-300 font-bold">80</td>
                    <td id="pvG5" class="p-1.5 border border-slate-300">A</td>
                  </tr>
                  <tr>
                    <td class="p-1.5 border border-slate-300 text-left font-semibold">6. Sanskrit / Drawing</td>
                    <td class="p-1.5 border border-slate-300">100</td>
                    <td class="p-1.5 border border-slate-300">33</td>
                    <td id="pvSub6" class="p-1.5 border border-slate-300 font-bold">92</td>
                    <td id="pvG6" class="p-1.5 border border-slate-300">A+</td>
                  </tr>
                </tbody>
                <tfoot class="bg-amber-50/80 font-bold text-center">
                  <tr>
                    <td class="p-2 border border-slate-300 text-left">GRAND TOTAL</td>
                    <td class="p-2 border border-slate-300">600</td>
                    <td class="p-2 border border-slate-300">198</td>
                    <td id="pvGrandTotal" class="p-2 border border-slate-300 text-dps-green font-black text-sm">511</td>
                    <td id="pvOverallGrade" class="p-2 border border-slate-300 text-emerald-700">A+</td>
                  </tr>
                </tfoot>
              </table>

              <!-- Result Metrics Row -->
              <div class="mt-4 p-3 bg-slate-50 border border-slate-200 rounded-lg grid grid-cols-3 gap-2 text-center text-xs">
                <div>
                  <span class="text-slate-500 block text-[10px]">PERCENTAGE</span>
                  <span id="pvPercentage" class="font-extrabold text-sm text-dps-green">85.17%</span>
                </div>
                <div>
                  <span class="text-slate-500 block text-[10px]">FINAL RESULT</span>
                  <span id="pvResultStatus" class="font-extrabold text-sm text-emerald-700">PASSED</span>
                </div>
                <div>
                  <span class="text-slate-500 block text-[10px]">DIVISION</span>
                  <span id="pvDivision" class="font-extrabold text-sm text-dps-goldDark">FIRST (1st)</span>
                </div>
              </div>

              <!-- Signatures Row (Director Avadhesh Singh & Manager Vishnu Kant) -->
              <div class="mt-8 pt-6 grid grid-cols-3 text-center text-[11px] font-semibold text-slate-700">
                <div>
                  <div class="h-8"></div>
                  <div class="border-t border-slate-400 pt-1">Class Teacher</div>
                </div>
                <div>
                  <div class="h-8 font-crest text-dps-green flex items-end justify-center font-bold pb-0.5">
                    Vishnu Kant
                  </div>
                  <div class="border-t border-slate-400 pt-1 font-bold text-slate-800">Shri Vishnu Kant (Manager)</div>
                </div>
                <div>
                  <div class="h-8 font-crest text-dps-green flex items-end justify-center font-bold pb-0.5">
                    Avadhesh Singh
                  </div>
                  <div class="border-t border-slate-400 pt-1 font-bold text-dps-greenDark">Shri Avadhesh Singh (Director)</div>
                </div>
              </div>

            </div>
          </div>

        </div>
      </div>

    </div>
  </div>

  <!-- JAVASCRIPT CONTROLLERS -->
  <script>
    // Official Credentials
    const ADMIN_CREDENTIALS = {
      email: 'rambaxsinghintercollege@gmail.com',
      pass: 'vishnukant@207247'
    };

    // Preloaded Admissions Data
    const defaultInquiries = [
      {
        id: 'RBS-ADM-001',
        name: 'Amit Kumar',
        father: 'Shri Ramesh Chandra',
        class: 'Class 10',
        dob: '2010-04-12',
        mobile: '9876543210',
        hostel: 'Yes',
        previous: 'UP Board Class 9 - 78%',
        address: 'Bithara, Aliganj, Etah (207247)',
        date: '2026-04-10'
      },
      {
        id: 'RBS-ADM-002',
        name: 'Km. Pooja Sharma',
        father: 'Shri Dinesh Sharma',
        class: 'Class 11 (Science)',
        dob: '2009-08-19',
        mobile: '9123456780',
        hostel: 'No',
        previous: 'High School - 84%',
        address: 'Sarai Road, Aliganj (Etah)',
        date: '2026-04-12'
      },
      {
        id: 'RBS-ADM-003',
        name: 'Rahul Yadav',
        father: 'Shri Suresh Yadav',
        class: 'Class 12 (Science)',
        dob: '2008-01-25',
        mobile: '6395052394',
        hostel: 'Yes',
        previous: 'Class 11th Science - 81%',
        address: 'Gram Bithara, Aliganj (Etah)',
        date: '2026-04-14'
      }
    ];

    function getAdmissions() {
      const stored = localStorage.getItem('rbs_admissions');
      if (!stored) {
        localStorage.setItem('rbs_admissions', JSON.stringify(defaultInquiries));
        return defaultInquiries;
      }
      try {
        return JSON.parse(stored);
      } catch (e) {
        return defaultInquiries;
      }
    }

    function saveAdmissions(list) {
      localStorage.setItem('rbs_admissions', JSON.stringify(list));
      renderAdmissionsTable();
    }

    /* DPS AUTO SLIDER LOGIC */
    let currentSlide = 0;
    const slides = document.querySelectorAll('#dpsCarousel .slide');
    const totalSlides = slides.length;
    let sliderTimer = null;

    function initSliderDots() {
      const dotsCont = document.getElementById('sliderDots');
      dotsCont.innerHTML = '';
      for (let i = 0; i < totalSlides; i++) {
        const dot = document.createElement('button');
        dot.className = `w-2.5 h-2.5 rounded-full transition-all duration-300 ${i === 0 ? 'bg-dps-gold w-6' : 'bg-white/60 hover:bg-white'}`;
        dot.onclick = () => goToSlide(i);
        dotsCont.appendChild(dot);
      }
    }

    function goToSlide(n) {
      slides[currentSlide].classList.remove('opacity-100', 'z-20');
      slides[currentSlide].classList.add('opacity-0', 'z-10');

      currentSlide = (n + totalSlides) % totalSlides;

      slides[currentSlide].classList.remove('opacity-0', 'z-10');
      slides[currentSlide].classList.add('opacity-100', 'z-20');

      // Update dots
      const dots = document.querySelectorAll('#sliderDots button');
      dots.forEach((d, idx) => {
        if (idx === currentSlide) {
          d.className = 'w-6 h-2.5 rounded-full bg-dps-gold transition-all duration-300';
        } else {
          d.className = 'w-2.5 h-2.5 rounded-full bg-white/60 hover:bg-white transition-all duration-300';
        }
      });
    }

    function nextSlide() {
      goToSlide(currentSlide + 1);
    }
    function prevSlide() {
      goToSlide(currentSlide - 1);
    }

    function startAutoSlider() {
      if (sliderTimer) clearInterval(sliderTimer);
      sliderTimer = setInterval(nextSlide, 4500);
    }

    // Modal Handlers
    function openAdminModal() {
      document.getElementById('adminLoginModal').classList.remove('hidden');
    }
    function closeAdminModal() {
      document.getElementById('adminLoginModal').classList.add('hidden');
    }
    function fillAdminCredentials() {
      document.getElementById('adminUserEmail').value = ADMIN_CREDENTIALS.email;
      document.getElementById('adminPassword').value = ADMIN_CREDENTIALS.pass;
    }

    function handleAdminLogin(e) {
      e.preventDefault();
      const email = document.getElementById('adminUserEmail').value.trim();
      const pass = document.getElementById('adminPassword').value.trim();
      const errMsg = document.getElementById('loginErrorMessage');

      if (email === ADMIN_CREDENTIALS.email && pass === ADMIN_CREDENTIALS.pass) {
        errMsg.classList.add('hidden');
        closeAdminModal();
        document.getElementById('adminDashboard').classList.remove('hidden');
        renderAdmissionsTable();
        updateMarksheetPreview();
      } else {
        errMsg.classList.remove('hidden');
      }
    }

    function logoutAdmin() {
      document.getElementById('adminDashboard').classList.add('hidden');
    }

    function switchAdminTab(tab) {
      const isAdm = tab === 'admissions';
      document.getElementById('tabAdmissions').classList.toggle('hidden', !isAdm);
      document.getElementById('tabMarksheet').classList.toggle('hidden', isAdm);

      document.getElementById('tabBtnAdmissions').className = isAdm
        ? 'px-3 py-1.5 rounded-lg text-xs font-bold bg-dps-gold text-dps-navy transition'
        : 'px-3 py-1.5 rounded-lg text-xs font-bold bg-white/10 hover:bg-white/20 text-white transition';

      document.getElementById('tabBtnMarksheet').className = !isAdm
        ? 'px-3 py-1.5 rounded-lg text-xs font-bold bg-dps-gold text-dps-navy transition'
        : 'px-3 py-1.5 rounded-lg text-xs font-bold bg-white/10 hover:bg-white/20 text-white transition';
    }

    // Lightbox Controls
    function openLightbox(src, caption) {
      const modal = document.getElementById('galleryLightbox');
      const img = document.getElementById('lightboxImg');
      const cap = document.getElementById('lightboxCaption');
      img.src = src;
      cap.innerText = caption;
      modal.classList.remove('hidden');
    }
    function closeLightbox() {
      document.getElementById('galleryLightbox').classList.add('hidden');
    }

    // Admission Form Submit
    function handleAdmissionSubmit(e) {
      e.preventDefault();
      const newEntry = {
        id: 'RBS-ADM-' + Math.floor(100 + Math.random() * 900),
        name: document.getElementById('admStudentName').value.trim(),
        father: document.getElementById('admFatherName').value.trim(),
        class: document.getElementById('admClass').value,
        dob: document.getElementById('admDOB').value,
        mobile: document.getElementById('admMobile').value.trim(),
        hostel: document.getElementById('admHostel').value,
        previous: document.getElementById('admPrevious').value.trim() || 'N/A',
        address: document.getElementById('admAddress').value.trim(),
        date: new Date().toISOString().split('T')[0]
      };

      const list = getAdmissions();
      list.unshift(newEntry);
      saveAdmissions(list);

      // Show receipt
      const receiptBox = document.getElementById('admSuccessReceipt');
      document.getElementById('receiptRegId').innerText = newEntry.id;
      document.getElementById('receiptSummaryText').innerHTML = `
        <strong>${newEntry.name}</strong> S/o <strong>${newEntry.father}</strong> has been enrolled for <strong>${newEntry.class}</strong> (${newEntry.hostel === 'Yes' ? 'Hostel Resident' : 'Day Scholar'}). Phone: ${newEntry.mobile}.
      `;
      receiptBox.classList.remove('hidden');
      receiptBox.scrollIntoView({ behavior: 'smooth' });
      document.getElementById('onlineAdmissionForm').reset();
    }

    // Render Admissions
    function renderAdmissionsTable() {
      const list = getAdmissions();
      document.getElementById('admissionCount').innerText = list.length;
      const tbody = document.getElementById('admissionsTableBody');
      const empty = document.getElementById('emptyAdmissionsState');

      if (!list.length) {
        tbody.innerHTML = '';
        empty.classList.remove('hidden');
        return;
      }
      empty.classList.add('hidden');

      tbody.innerHTML = list.map(item => `
        <tr class="hover:bg-slate-50 transition">
          <td class="p-3 font-mono font-bold text-dps-green">${item.id}</td>
          <td class="p-3 font-semibold text-slate-900">${item.name}</td>
          <td class="p-3">${item.father}</td>
          <td class="p-3"><span class="bg-emerald-50 text-emerald-800 px-2 py-0.5 rounded font-semibold">${item.class}</span></td>
          <td class="p-3"><a href="tel:${item.mobile}" class="text-dps-goldDark font-semibold hover:underline">${item.mobile}</a></td>
          <td class="p-3">${item.hostel === 'Yes' ? '<span class="bg-amber-100 text-amber-800 px-2 py-0.5 rounded text-[10px] font-bold">Hostel</span>' : '<span class="text-slate-400">Day Scholar</span>'}</td>
          <td class="p-3 max-w-xs truncate" title="${item.address}">${item.address}</td>
          <td class="p-3 text-slate-400 whitespace-nowrap">${item.date}</td>
          <td class="p-3 text-right whitespace-nowrap space-x-1">
            <button onclick="loadStudentToMarksheet('${item.id}')" title="Generate Marksheet" class="bg-dps-green text-white hover:bg-dps-greenDark px-2 py-1 rounded text-[11px] font-medium">
              <i class="fa-solid fa-award"></i> Marksheet
            </button>
            <button onclick="deleteAdmission('${item.id}')" title="Delete" class="text-rose-500 hover:text-rose-700 px-1 py-1">
              <i class="fa-solid fa-trash"></i>
            </button>
          </td>
        </tr>
      `).join('');
    }

    function deleteAdmission(id) {
      if (confirm('Kya aap is admission inquiry ko delete karna chahte hain?')) {
        let list = getAdmissions().filter(a => a.id !== id);
        saveAdmissions(list);
      }
    }

    function clearAllAdmissions() {
      if (confirm('Kya aap sabhi inquiries ko delete karna chahte hain?')) {
        saveAdmissions([]);
      }
    }

    function exportAdmissionsCSV() {
      const list = getAdmissions();
      if (!list.length) return alert('Export karne ke liye koi data nahi hai!');
      const headers = ['Ref ID', 'Student Name', 'Father Name', 'Class', 'DOB', 'Mobile', 'Hostel', 'Address', 'Date'];
      const rows = list.map(i => [
        i.id, `"${i.name}"`, `"${i.father}"`, `"${i.class}"`, i.dob, i.mobile, i.hostel, `"${i.address}"`, i.date
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

    function loadStudentToMarksheet(id) {
      const student = getAdmissions().find(a => a.id === id);
      if (!student) return;
      document.getElementById('msStudentName').value = student.name;
      document.getElementById('msFatherName').value = student.father;
      document.getElementById('msAddress').value = student.address;
      document.getElementById('msRollNo').value = '2026' + Math.floor(100 + Math.random() * 900);
      switchAdminTab('marksheet');
      updateMarksheetPreview();
    }

    function getGrade(m) {
      if (m >= 90) return 'A+';
      if (m >= 75) return 'A';
      if (m >= 60) return 'B1';
      if (m >= 45) return 'B2';
      if (m >= 33) return 'C';
      return 'D (Fail)';
    }

    function updateMarksheetPreview() {
      const name = document.getElementById('msStudentName').value || 'Student Name';
      const father = document.getElementById('msFatherName').value || "Father's Name";
      const roll = document.getElementById('msRollNo').value || '2026---';
      const sClass = document.getElementById('msClass').value;
      const session = document.getElementById('msSession').value || '2025-2026';
      const address = document.getElementById('msAddress').value || 'Bithara, Aliganj (Etah)';

      const m1 = Math.max(0, Math.min(100, Number(document.getElementById('sub1').value) || 0));
      const m2 = Math.max(0, Math.min(100, Number(document.getElementById('sub2').value) || 0));
      const m3 = Math.max(0, Math.min(100, Number(document.getElementById('sub3').value) || 0));
      const m4 = Math.max(0, Math.min(100, Number(document.getElementById('sub4').value) || 0));
      const m5 = Math.max(0, Math.min(100, Number(document.getElementById('sub5').value) || 0));
      const m6 = Math.max(0, Math.min(100, Number(document.getElementById('sub6').value) || 0));

      const total = m1 + m2 + m3 + m4 + m5 + m6;
      const percentage = (total / 6).toFixed(2);

      // Fill Certificate values
      document.getElementById('pvName').innerText = name;
      document.getElementById('pvFather').innerText = father;
      document.getElementById('pvRoll').innerText = roll;
      document.getElementById('pvClass').innerText = sClass;
      document.getElementById('pvSession').innerText = session;
      document.getElementById('pvAddress').innerText = address;

      document.getElementById('pvSub1').innerText = m1;
      document.getElementById('pvSub2').innerText = m2;
      document.getElementById('pvSub3').innerText = m3;
      document.getElementById('pvSub4').innerText = m4;
      document.getElementById('pvSub5').innerText = m5;
      document.getElementById('pvSub6').innerText = m6;

      document.getElementById('pvG1').innerText = getGrade(m1);
      document.getElementById('pvG2').innerText = getGrade(m2);
      document.getElementById('pvG3').innerText = getGrade(m3);
      document.getElementById('pvG4').innerText = getGrade(m4);
      document.getElementById('pvG5').innerText = getGrade(m5);
      document.getElementById('pvG6').innerText = getGrade(m6);

      document.getElementById('pvGrandTotal').innerText = `${total} / 600`;
      document.getElementById('pvPercentage').innerText = `${percentage}%`;

      const hasFailed = [m1, m2, m3, m4, m5, m6].some(m => m < 33);
      const resElem = document.getElementById('pvResultStatus');
      const divElem = document.getElementById('pvDivision');
      const ovGradeElem = document.getElementById('pvOverallGrade');

      ovGradeElem.innerText = getGrade(Number(percentage));

      if (hasFailed) {
        resElem.innerText = 'COMPARTMENT / FAILED';
        resElem.className = 'font-extrabold text-sm text-rose-600';
        divElem.innerText = 'NO DIVISION';
      } else {
        resElem.innerText = 'PASSED';
        resElem.className = 'font-extrabold text-sm text-emerald-700';

        if (percentage >= 60) {
          divElem.innerText = 'FIRST (1st) DIVISION';
          divElem.className = 'font-extrabold text-sm text-dps-goldDark';
        } else if (percentage >= 45) {
          divElem.innerText = 'SECOND (2nd) DIVISION';
          divElem.className = 'font-extrabold text-sm text-blue-700';
        } else {
          divElem.innerText = 'THIRD (3rd) DIVISION';
          divElem.className = 'font-extrabold text-sm text-slate-700';
        }
      }
    }

    // Initialization on DOM Ready
    window.addEventListener('DOMContentLoaded', () => {
      initSliderDots();
      startAutoSlider();
      renderAdmissionsTable();
      updateMarksheetPreview();

      // Pause slider on hover
      const carousel = document.getElementById('dpsCarousel');
      if (carousel) {
        carousel.addEventListener('mouseenter', () => clearInterval(sliderTimer));
        carousel.addEventListener('mouseleave', () => startAutoSlider());
      }
    });
  </script>
</body>
</html>
