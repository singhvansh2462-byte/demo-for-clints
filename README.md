<!DOCTYPE html>

<html class="dark" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>VANSH - Portfolio</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com" rel="preconnect"/>
<link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&amp;family=Montserrat:wght@700;800;900&amp;family=Space+Grotesk:wght@600&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "on-secondary-container": "#00566b",
                        "on-secondary": "#003543",
                        "on-primary-fixed-variant": "#4800d6",
                        "tertiary-container": "#a22900",
                        "secondary-fixed-dim": "#4cd6ff",
                        "on-secondary-fixed": "#001f28",
                        "inverse-surface": "#e6e0f0",
                        "on-primary-container": "#cfc4ff",
                        "surface-container-low": "#1c1a26",
                        "surface-dim": "#14121d",
                        "on-secondary-fixed-variant": "#004e60",
                        "surface-bright": "#3a3744",
                        "surface": "#14121d",
                        "outline": "#938ea3",
                        "on-error-container": "#ffdad6",
                        "primary": "#cabeff",
                        "surface-container-highest": "#363340",
                        "on-surface-variant": "#cac3da",
                        "surface-tint": "#cabeff",
                        "on-tertiary-fixed-variant": "#872100",
                        "error": "#ffb4ab",
                        "inverse-primary": "#6128ff",
                        "tertiary-fixed-dim": "#ffb5a0",
                        "secondary": "#a6e6ff",
                        "surface-container-lowest": "#0f0d18",
                        "surface-container": "#201e2a",
                        "secondary-fixed": "#b7eaff",
                        "on-tertiary-fixed": "#3b0900",
                        "background": "#14121d",
                        "on-error": "#690005",
                        "on-primary-fixed": "#1c0062",
                        "on-background": "#e6e0f0",
                        "surface-container-high": "#2b2834",
                        "tertiary-fixed": "#ffdbd1",
                        "primary-container": "#5800ff",
                        "inverse-on-surface": "#312f3b",
                        "primary-fixed": "#e6deff",
                        "on-primary": "#32009a",
                        "error-container": "#93000a",
                        "primary-fixed-dim": "#cabeff",
                        "outline-variant": "#484457",
                        "secondary-container": "#14d1ff",
                        "on-tertiary": "#601400",
                        "surface-variant": "#363340",
                        "tertiary": "#ffb5a0",
                        "on-tertiary-container": "#ffbca9",
                        "on-surface": "#e6e0f0"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.25rem",
                        "lg": "0.5rem",
                        "xl": "0.75rem",
                        "full": "9999px"
                    },
                    "spacing": {
                        "gutter": "24px",
                        "base": "8px",
                        "section-gap-desktop": "160px",
                        "container-max-width": "1280px",
                        "section-gap-mobile": "80px",
                        "margin-mobile": "20px"
                    },
                    "fontFamily": {
                        "headline-lg": ["Montserrat", "sans-serif"],
                        "display-xl": ["Montserrat", "sans-serif"],
                        "body-md": ["Inter", "sans-serif"],
                        "headline-lg-mobile": ["Montserrat", "sans-serif"],
                        "display-xl-mobile": ["Montserrat", "sans-serif"],
                        "body-lg": ["Inter", "sans-serif"],
                        "label-caps": ["Space Grotesk", "sans-serif"]
                    },
                    "fontSize": {
                        "headline-lg": ["40px", { "lineHeight": "1.2", "fontWeight": "700" }],
                        "display-xl": ["80px", { "lineHeight": "1.1", "letterSpacing": "-0.04em", "fontWeight": "800" }],
                        "body-md": ["16px", { "lineHeight": "1.6", "fontWeight": "400" }],
                        "headline-lg-mobile": ["32px", { "lineHeight": "1.2", "fontWeight": "700" }],
                        "display-xl-mobile": ["48px", { "lineHeight": "1.1", "letterSpacing": "-0.02em", "fontWeight": "800" }],
                        "body-lg": ["18px", { "lineHeight": "1.6", "fontWeight": "400" }],
                        "label-caps": ["12px", { "lineHeight": "1", "letterSpacing": "0.1em", "fontWeight": "600" }]
                    }
                }
            }
        }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        
        /* Subtle glow for tech feel */
        .neon-glow {
            box-shadow: 0 0 40px rgba(202, 190, 255, 0.1);
        }
        
        .btn-primary-glow {
            box-shadow: 0 0 20px rgba(88, 0, 255, 0.3);
        }
        
        .btn-primary-glow:hover {
            box-shadow: 0 0 35px rgba(88, 0, 255, 0.5);
        }
    </style>
</head>
<body class="bg-background text-on-background min-h-screen flex flex-col font-body-md text-body-md antialiased overflow-x-hidden selection:bg-primary-container selection:text-on-primary-container">
<!-- TopNavBar -->
<header class="bg-surface/70 backdrop-blur-xl docked full-width top-0 sticky z-50 border-b border-white/10 shadow-[0_0_20px_rgba(202,190,255,0.15)]">
<div class="flex justify-between items-center w-full px-gutter max-w-container-max-width mx-auto h-20">
<!-- Brand Logo -->
<div class="font-display-xl-mobile text-display-xl-mobile font-extrabold tracking-tighter text-primary dark:text-primary">
                VANSH
            </div>
<!-- Navigation Links (Desktop) -->
<nav class="hidden md:flex gap-8 items-center font-body-md text-body-md">
<a class="text-primary font-bold border-b-2 border-primary pb-1 scale-102 active:scale-95 transition-transform hover:text-secondary hover:scale-105 transition-all duration-300" href="#">Home</a>
<a class="text-on-surface-variant font-medium scale-102 active:scale-95 transition-transform hover:text-secondary hover:scale-105 transition-all duration-300" href="#">Portfolio</a>
<a class="text-on-surface-variant font-medium scale-102 active:scale-95 transition-transform hover:text-secondary hover:scale-105 transition-all duration-300" href="#">Services</a>
<a class="text-on-surface-variant font-medium scale-102 active:scale-95 transition-transform hover:text-secondary hover:scale-105 transition-all duration-300" href="#">About</a>
<a class="text-on-surface-variant font-medium scale-102 active:scale-95 transition-transform hover:text-secondary hover:scale-105 transition-all duration-300" href="#">Contact</a>
</nav>
<!-- Trailing Action -->
<div class="hidden md:block">
<button class="bg-surface-container-high text-on-surface font-label-caps text-label-caps px-6 py-3 rounded-full border border-white/10 hover:border-primary hover:text-primary scale-102 active:scale-95 transition-all duration-300 flex items-center gap-2">
                    Hire Me
                    <span class="material-symbols-outlined text-sm">arrow_forward</span>
</button>
</div>
<!-- Mobile Menu Trigger -->
<button class="md:hidden text-on-surface-variant hover:text-primary transition-colors">
<span class="material-symbols-outlined text-3xl">menu</span>
</button>
</div>
</header>
<!-- Main Content -->
<main class="flex-grow flex flex-col items-center w-full">
<!-- Hero Section -->
<section class="w-full relative min-h-[921px] flex items-center pt-20 pb-section-gap-mobile md:py-section-gap-desktop px-margin-mobile md:px-gutter max-w-container-max-width mx-auto">
<!-- Background Abstract Elements (Glassmorphism/Glow) -->
<div class="absolute inset-0 pointer-events-none overflow-hidden flex items-center justify-center -z-10">
<div class="absolute w-[600px] h-[600px] bg-primary-container rounded-full blur-[150px] opacity-20 top-[-10%] right-[-10%]"></div>
<div class="absolute w-[400px] h-[400px] bg-secondary-container rounded-full blur-[120px] opacity-10 bottom-[10%] left-[-5%]"></div>
</div>
<div class="grid grid-cols-1 md:grid-cols-12 gap-12 items-center w-full relative z-10">
<!-- Text Content -->
<div class="md:col-span-7 flex flex-col items-start gap-8">
<!-- Glass Chip -->
<div class="bg-surface-container/50 backdrop-blur-md border border-white/10 px-4 py-2 rounded-full font-label-caps text-label-caps text-secondary uppercase tracking-widest inline-flex items-center gap-2">
<span class="w-2 h-2 rounded-full bg-secondary shadow-[0_0_8px_#a6e6ff] animate-pulse"></span>
                        Digital Craftsmanship
                    </div>
<h1 class="font-display-xl-mobile text-display-xl-mobile md:font-display-xl md:text-display-xl text-on-surface">
                        Designing Premium Websites That Speak <span class="text-transparent bg-clip-text bg-gradient-to-r from-primary to-secondary">Your Brand.</span>
</h1>
<p class="font-body-lg text-body-lg text-on-surface-variant max-w-2xl border-l-2 border-primary/30 pl-6 py-2">
                        I’m Vansh, only 15, a creative web designer from India, passionate about building modern, attractive, and responsive websites for businesses and creators.
                    </p>
<div class="flex flex-col sm:flex-row items-start sm:items-center gap-6 mt-4">
<button class="bg-primary-container text-on-primary-container font-label-caps text-label-caps px-8 py-4 rounded-full uppercase tracking-widest btn-primary-glow scale-100 hover:scale-[1.02] active:scale-95 transition-all duration-300 flex items-center gap-3">
                            Get Started
                            <span class="material-symbols-outlined text-sm">rocket_launch</span>
</button>
<p class="font-body-md text-body-md text-secondary font-medium">
                            Let’s build your dream website today!
                        </p>
</div>
<!-- Stats/Info mini layout -->
<div class="grid grid-cols-2 gap-8 mt-12 pt-8 border-t border-white/10 w-full max-w-md">
<div>
<div class="font-headline-lg text-headline-lg text-on-surface">15+</div>
<div class="font-label-caps text-label-caps text-on-surface-variant mt-1">Years of Age</div>
</div>
<div>
<div class="font-headline-lg text-headline-lg text-on-surface">India</div>
<div class="font-label-caps text-label-caps text-on-surface-variant mt-1">Based In</div>
</div>
</div>
</div>
<!-- Visual Content (Bento/Abstract Card) -->
<div class="md:col-span-5 relative h-full min-h-[400px] w-full flex items-center justify-center hidden md:flex">
<div class="relative w-full aspect-square max-w-md">
<!-- Main Image Container with Glassmorphism border -->
<div class="absolute inset-0 bg-surface-container rounded-2xl p-2 border border-white/10 neon-glow transform rotate-3 hover:rotate-0 transition-transform duration-700 ease-out z-10">
<div class="w-full h-full rounded-xl overflow-hidden relative bg-surface">
<img alt="Abstract digital art" class="w-full h-full object-cover opacity-80 mix-blend-lighten" data-alt="A striking abstract 3D digital artwork representing web design and digital craftsmanship. The composition features sleek, floating glassmorphic panels and geometric shapes glowing with electric violet and neon blue lights against a deep, dark minimalist background. The lighting is dramatic and futuristic, creating a premium, tech-forward aesthetic. The mood is innovative, cutting-edge, and highly professional, perfectly capturing a modern digital portfolio vibe." src="https://lh3.googleusercontent.com/aida-public/AB6AXuDYPPmiAm_sgEyP6SHYcl5X1J21DoY4IIBz6zpc7_3Xa1DWzdJ3LCr3oxtkIJkGZZ_NTX6wjVhe8jTKegQ1EFZh6yFaghybi3hd6y6aPBZSuT28mQDVbZi-_fpn9SOUK0GHebiIV81cJgzerTd1zpiG0CXewIzQmdavjIqO09a7wPtFfEFC4CpUWvsaoTdtYDz3a_E2fhHuXogNyu_oqzPzVFx2Ncj13VQFpM_YecUp-Mbjm8nKH04e7tkGnGV6cZP-_ZfmlPVIzzMZ"/>
<!-- Floating UI Element 1 -->
<div class="absolute bottom-6 left-6 bg-surface/80 backdrop-blur-md border border-white/10 p-4 rounded-xl shadow-lg flex items-center gap-3 transform -translate-y-4">
<div class="w-10 h-10 rounded-full bg-primary/20 flex items-center justify-center">
<span class="material-symbols-outlined text-primary">code</span>
</div>
<div>
<div class="font-label-caps text-label-caps text-on-surface">Modern Code</div>
<div class="text-xs text-on-surface-variant">Clean &amp; Efficient</div>
</div>
</div>
</div>
</div>
<!-- Accent decorative element behind -->
<div class="absolute inset-4 bg-gradient-to-tr from-primary-container to-secondary-container rounded-2xl opacity-40 blur-xl z-0 transform -rotate-6"></div>
</div>
</div>
</div>
</section>
<!-- Portfolio Section -->
<section class="w-full relative py-section-gap-mobile md:py-section-gap-desktop px-margin-mobile md:px-gutter max-w-container-max-width mx-auto" id="portfolio">
<div class="flex flex-col gap-4 mb-16">
<h2 class="font-display-xl-mobile text-display-xl-mobile md:font-headline-lg md:text-headline-lg text-on-surface">
            Selected <span class="text-primary">Works</span>.
        </h2>
<p class="font-body-lg text-body-lg text-on-surface-variant max-w-2xl">
            A showcase of recent projects, highlighting premium digital experiences tailored for forward-thinking brands.
        </p>
</div>
<div class="grid grid-cols-1 md:grid-cols-2 gap-8 md:gap-12">
<!-- Project 1: Business Website -->
<div class="group cursor-pointer">
<div class="relative w-full aspect-[4/3] rounded-2xl overflow-hidden mb-6 bg-surface-container-high border border-white/10 shadow-[0_0_20px_rgba(202,190,255,0.05)]">
<img alt="Business Website" class="w-full h-full object-cover transform group-hover:scale-105 transition-transform duration-700 ease-out opacity-90 group-hover:opacity-100" src="https://lh3.googleusercontent.com/aida-public/AB6AXuC7ba1KgXiqLOLFBrTG5bPNHr5Kol04c5G40nSaEAwY738QTRO3uJeXwtsGV7InZrRw0yRZkl-ZkMIQ1uZusZQuYVFvoFA99rO9ydoxCmhMMeSk4xl1q1zWcWk5NkC5DXMopef1nUw7Xjiedj_5JV-3IL1kq-9ojc1_Anx5y_HlYV8yBx8zgsBA_94xHKIYbKP2Q3bZ3c_iZlZRd8hCmlDpXlL6PgoRCXdQ_B0Vj1IRMqBoJj1MkaI8YXlJaddeT9QMJNP1UyEdlrZ6"/>
<div class="absolute inset-0 bg-gradient-to-t from-background/80 via-transparent to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300"></div>
</div>
<div class="flex flex-col gap-2">
<div class="font-label-caps text-label-caps text-secondary uppercase tracking-widest">Corporate Tech</div>
<h3 class="font-headline-lg-mobile text-headline-lg-mobile text-on-surface group-hover:text-primary transition-colors">Business Website</h3>
</div>
</div>
<!-- Project 2: Digital Storefront -->
<div class="group cursor-pointer md:mt-24">
<div class="relative w-full aspect-[4/3] rounded-2xl overflow-hidden mb-6 bg-surface-container-high border border-white/10 shadow-[0_0_20px_rgba(202,190,255,0.05)]">
<img alt="Digital Storefront" class="w-full h-full object-cover transform group-hover:scale-105 transition-transform duration-700 ease-out opacity-90 group-hover:opacity-100" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBSXrUQ-RgxgmIxnNqifaYIfsQf87sNTgak2Ui9F2Vxt7ardQ7XLyXBCXIXPsKs8Zdipnz50N85-uaT6GjiO9GE2JxWv3toPZ60gDjr5oHwdYyRajRolq-lSOvbNDgG0JJAJPUC6qc6dbqRXwZNfil6GNAS_-EnNE6k9BIpIN7Tz4jzCgYmQ5bq4vrTZ3n_QDRUsx_BNnqwIkO5udAo0ZMb8yOQO_IjzDtiSUM8Q_sblBtPhtAUoi01jcHYESU_A-oKt-vq1X-3MZks"/>
<div class="absolute inset-0 bg-gradient-to-t from-background/80 via-transparent to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300"></div>
</div>
<div class="flex flex-col gap-2">
<div class="font-label-caps text-label-caps text-secondary uppercase tracking-widest">E-Commerce</div>
<h3 class="font-headline-lg-mobile text-headline-lg-mobile text-on-surface group-hover:text-primary transition-colors">Digital Storefront</h3>
</div>
</div>
<!-- Project 3: Creative Folio -->
<div class="group cursor-pointer">
<div class="relative w-full aspect-[4/3] rounded-2xl overflow-hidden mb-6 bg-surface-container-high border border-white/10 shadow-[0_0_20px_rgba(202,190,255,0.05)]">
<img alt="Creative Folio" class="w-full h-full object-cover transform group-hover:scale-105 transition-transform duration-700 ease-out opacity-90 group-hover:opacity-100" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBYz9KavQMW_1KzAoPqdTD9ktSCT86fAVFILz4DoEn5a7cSIiImvzusXovGBu4LX_zQ3v1hj-x8-3oUZv1L2MRObCQ4oUNfPyRPA0oQ6OKKp5PaLG-hyC3KdyFXleUqyYkl7p2aRcYapayaum164-qgb2kuaXhaTjSW-nPEn0L7S_fUzLc6wnLRldOG2FHlpUYE9m4IZ1nC1-g2LymkmMoHotATQ3lRxGcpJ4zMg_TyT_iM5Co_A7iLlO5Fb_AsjCsmOTvvgawhZO9h"/>
<div class="absolute inset-0 bg-gradient-to-t from-background/80 via-transparent to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300"></div>
</div>
<div class="flex flex-col gap-2">
<div class="font-label-caps text-label-caps text-secondary uppercase tracking-widest">Design Agency</div>
<h3 class="font-headline-lg-mobile text-headline-lg-mobile text-on-surface group-hover:text-primary transition-colors">Creative Folio</h3>
</div>
</div>
<!-- Project 4: Creator Brand Identity -->
<div class="group cursor-pointer md:mt-24">
<div class="relative w-full aspect-[4/3] rounded-2xl overflow-hidden mb-6 bg-surface-container-high border border-white/10 shadow-[0_0_20px_rgba(202,190,255,0.05)]">
<img alt="Creator Brand Identity" class="w-full h-full object-cover transform group-hover:scale-105 transition-transform duration-700 ease-out opacity-90 group-hover:opacity-100" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDYHjsR3FqjtBlDR7XDJwh_s3CMmEX8TA6Ns0WB2RCyU4DqE9oMeA01Yo28d2Y_ScLqwtSt2156oXnWVfYmFtovL3mG0H5QrRVPld9mZhx4pwhOX6WQT6PBA2uP_4bZ13RrvYxzv1fqNOnrfEA3EvkQ9UnrCahRbDIWxq7DnphfNjbeFEZHD8w46dgXA-AUxHs7HIp6L7gQcfB-m8WfsKPsncL53NAlrKf3hbpXkXc1SNS2EmwunJ7xSs16bJBnbGD4glL7Oj46yEKd"/>
<div class="absolute inset-0 bg-gradient-to-t from-background/80 via-transparent to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300"></div>
</div>
<div class="flex flex-col gap-2">
<div class="font-label-caps text-label-caps text-secondary uppercase tracking-widest">Personal Branding</div>
<h3 class="font-headline-lg-mobile text-headline-lg-mobile text-on-surface group-hover:text-primary transition-colors">Creator Brand Identity</h3>
</div>
</div>
</div>
</section>
</main>
<!-- Footer -->
<footer class="bg-surface-container-lowest full-width bottom-0 border-t border-white/10">
<div class="flex flex-col md:flex-row justify-between items-center py-section-gap-mobile md:py-12 px-margin-mobile md:px-gutter max-w-container-max-width mx-auto gap-8">
<!-- Brand Logo -->
<div class="font-headline-lg text-headline-lg font-black text-on-surface opacity-80 hover:opacity-100 transition-opacity">
                VANSH
            </div>
<!-- Links -->
<div class="flex flex-col md:flex-row gap-6 items-center md:items-start text-center md:text-left">
<a class="font-body-md text-body-md text-on-surface-variant hover:text-primary transition-colors duration-300 opacity-80 hover:opacity-100" href="#">
                    Instagram: vanshcodes.x
                </a>
<a class="font-body-md text-body-md text-on-surface-variant hover:text-primary transition-colors duration-300 opacity-80 hover:opacity-100" href="#">
                    Email: anubhavv8777@gmail.com
                </a>
<a class="font-body-md text-body-md text-on-surface-variant hover:text-primary transition-colors duration-300 opacity-80 hover:opacity-100" href="#">
                    Phone: +91 9456853697
                </a>
</div>
<!-- Copyright -->
<div class="font-label-caps text-label-caps text-secondary text-center md:text-right opacity-80">
                © 2024 VANSH. DIGITAL CRAFTSMANSHIP.
            </div>
</div>
</footer>
</body></html>
