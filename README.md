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
            theme: {
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
