<!DOCTYPE html>

<html class="dark" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Portfolio - VANSH</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com" rel="preconnect"/>
<link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&amp;family=Montserrat:wght@700;800;900&amp;family=Space+Grotesk:wght@600&amp;display=swap" rel="stylesheet"/>
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
                        "headline-lg": ["Montserrat"],
                        "display-xl": ["Montserrat"],
                        "body-md": ["Inter"],
                        "headline-lg-mobile": ["Montserrat"],
                        "display-xl-mobile": ["Montserrat"],
                        "body-lg": ["Inter"],
                        "label-caps": ["Space Grotesk"]
                    },
                    "fontSize": {
                        "headline-lg": ["40px", {"lineHeight": "1.2", "fontWeight": "700"}],
                        "display-xl": ["80px", {"lineHeight": "1.1", "letterSpacing": "-0.04em", "fontWeight": "800"}],
                        "body-md": ["16px", {"lineHeight": "1.6", "fontWeight": "400"}],
                        "headline-lg-mobile": ["32px", {"lineHeight": "1.2", "fontWeight": "700"}],
                        "display-xl-mobile": ["48px", {"lineHeight": "1.1", "letterSpacing": "-0.02em", "fontWeight": "800"}],
                        "body-lg": ["18px", {"lineHeight": "1.6", "fontWeight": "400"}],
                        "label-caps": ["12px", {"lineHeight": "1", "letterSpacing": "0.1em", "fontWeight": "600"}]
                    }
                }
            }
        }
    </script>
<style>
        .glass-card {
            background: rgba(32, 30, 42, 0.4);
            backdrop-filter: blur(16px);
            border: 1px solid rgba(255, 255, 255, 0.05);
        }
        .glow-hover:hover {
            box-shadow: 0 0 30px rgba(202, 190, 255, 0.15);
        }
    </style>
</head>
<body class="bg-background text-on-background min-h-screen flex flex-col font-body-md antialiased selection:bg-primary-container selection:text-on-primary-container">
<!-- TopNavBar -->
<header class="bg-surface/70 backdrop-blur-xl border-b border-white/10 shadow-[0_0_20px_rgba(202,190,255,0.15)] docked full-width top-0 sticky z-50">
<nav class="flex justify-between items-center w-full px-margin-mobile md:px-gutter max-w-container-max-width mx-auto h-20">
<a class="font-display-xl-mobile text-display-xl-mobile font-extrabold tracking-tighter text-primary dark:text-primary" href="#">
                VANSH
            </a>
<div class="hidden md:flex items-center gap-8">
<a class="text-on-surface-variant font-medium hover:text-secondary hover:scale-105 transition-all duration-300 font-label-caps text-label-caps" href="#">Home</a>
<a aria-current="page" class="text-primary font-bold border-b-2 border-primary pb-1 hover:text-secondary hover:scale-105 transition-all duration-300 font-label-caps text-label-caps" href="#">Portfolio</a>
<a class="text-on-surface-variant font-medium hover:text-secondary hover:scale-105 transition-all duration-300 font-label-caps text-label-caps" href="#">Services</a>
<a class="text-on-surface-variant font-medium hover:text-secondary hover:scale-105 transition-all duration-300 font-label-caps text-label-caps" href="#">About</a>
<a class="text-on-surface-variant font-medium hover:text-secondary hover:scale-105 transition-all duration-300 font-label-caps text-label-caps" href="#">Contact</a>
</div>
<button class="hidden md:inline-flex items-center justify-center bg-primary-container text-on-primary-container font-label-caps text-label-caps px-6 py-3 rounded-DEFAULT hover:scale-105 transition-transform duration-300 shadow-[0_0_15px_rgba(88,0,255,0.2)] hover:shadow-[0_0_25px_rgba(88,0,255,0.4)]">
                Hire Me
            </button>
<button class="md:hidden text-on-surface p-2">
<span class="material-symbols-outlined text-3xl">menu</span>
</button>
</nav>
</header>
<!-- Main Content -->
<main class="flex-grow flex flex-col pt-section-gap-mobile md:pt-section-gap-desktop pb-section-gap-mobile md:pb-section-gap-desktop px-margin-mobile md:px-gutter max-w-container-max-width mx-auto w-full">
<!-- Header Section -->
<section class="mb-16 md:mb-24 max-w-3xl">
<h1 class="font-display-xl-mobile text-display-xl-mobile md:font-display-xl md:text-display-xl text-on-surface mb-6">
                My Work
            </h1>
<p class="font-body-lg text-body-lg text-on-surface-variant">
                A showcase of projects I’ve designed for clients, highlighting creativity and functionality. Each project represents a unique challenge solved through thoughtful design and modern technology.
            </p>
</section>
<!-- Portfolio Grid (Bento Style) -->
<section class="grid grid-cols-1 md:grid-cols-12 gap-base md:gap-6">
<!-- Project 1: Business Website -->
<article class="glass-card glow-hover rounded-xl overflow-hidden group cursor-pointer col-span-1 md:col-span-8 relative aspect-[4/3] md:aspect-auto md:h-[500px] transition-all duration-500">
<img alt="Project Preview" class="absolute inset-0 w-full h-full object-cover transition-transform duration-700 group-hover:scale-105 opacity-80 group-hover:opacity-100" data-alt="A sleek, modern corporate website interface displayed on a high-end laptop screen, surrounded by minimal office decor. The design features a dark-mode theme with vibrant electric violet and neon blue accents, reflecting a tech-forward minimalist aesthetic. The layout is clean and professional, using crisp typography and glassmorphic elements. The lighting is sophisticated, emphasizing the crispness of the digital display against a dark, moody background." src="https://lh3.googleusercontent.com/aida-public/AB6AXuCdXpvwsrbfl2mU7QVbeBTc6ugZBUiBoi9HRu_ODNdPFiOoOBEg39XZtVaVxWdzM8Q1teXkIJs1IeRp8LrgNfYOKeRtI_cIEIahbvpsqUxzsHkQFdVeOMrennhtDW8sq9CVI0wr3mVVDoK92SjJxUiPWaktORhCVvqXIo6OTUtw1HAFIFGGp4Lz4M--buf2OcSsnpG_Bep5XtAreNzlwl86wH5eXZvAZ-OLid2YgJX2GFMbM0g58ioy3en-frOwK4p21bjENwVx_6OK"/>
<div class="absolute inset-0 bg-gradient-to-t from-surface-dim via-surface-dim/50 to-transparent opacity-90"></div>
<div class="absolute bottom-0 left-0 p-8 w-full">
<div class="flex gap-2 mb-4">
<span class="bg-surface/50 backdrop-blur-md border border-white/10 text-on-surface font-label-caps text-label-caps px-3 py-1 rounded-full">Web Design</span>
<span class="bg-surface/50 backdrop-blur-md border border-white/10 text-on-surface font-label-caps text-label-caps px-3 py-1 rounded-full">UI/UX</span>
</div>
<h2 class="font-headline-lg-mobile text-headline-lg-mobile md:font-headline-lg md:text-headline-lg text-on-surface mb-2 group-hover:text-primary transition-colors">Business Website</h2>
<p class="font-body-md text-body-md text-on-surface-variant max-w-xl">Modern UI overhaul focusing on conversion and premium brand positioning.</p>
</div>
</article>
<!-- Project 2: E-commerce -->
<article class="glass-card glow-hover rounded-xl overflow-hidden group cursor-pointer col-span-1 md:col-span-4 relative aspect-square md:h-[500px] transition-all duration-500">
<img alt="Project Preview" class="absolute inset-0 w-full h-full object-cover transition-transform duration-700 group-hover:scale-105 opacity-80 group-hover:opacity-100" data-alt="A responsive e-commerce mobile application interface shown on a floating smartphone mockup. The design highlights a dark theme with electric violet buttons and crisp white typography. The layout is highly functional, showcasing a product grid with subtle glassmorphic overlays. The background is a dark, abstract geometric pattern that complements the tech-forward, premium feel of the design system." src="https://lh3.googleusercontent.com/aida-public/AB6AXuAlWEAnBTUKKzg1myXnPN79bRpm8sBmbEkuR-MjPlZ29ReXS267VJBY_9SqeN6iIAlFHH10QYMMnoQ6CXaKuDLVLHgiWz5mT0S8DyBf3XuEunz-TQ6FVjqCD90BhcgFlH9JEOIOAg6g9CC9dR6P1eK1ONTczJH1UeoTk0CtE4etPl0VHbJcIEY3R3hocuHXzkkS_QmQva7LXezsyvlXlxF2bfxYzsLR3ppdKRTrU5DzhfNzX-UZTZc81kxiZ6nOEoEVTvFSDsBlM2hG"/>
<div class="absolute inset-0 bg-gradient-to-t from-surface-dim via-surface-dim/60 to-transparent opacity-90"></div>
<div class="absolute bottom-0 left-0 p-6 w-full">
<div class="flex gap-2 mb-4 flex-wrap">
<span class="bg-surface/50 backdrop-blur-md border border-white/10 text-on-surface font-label-caps text-label-caps px-3 py-1 rounded-full">E-commerce</span>
</div>
<h2 class="font-headline-lg-mobile text-headline-lg-mobile text-on-surface mb-2 group-hover:text-primary transition-colors">Digital Storefront</h2>
<p class="font-body-md text-body-md text-on-surface-variant line-clamp-2">Responsive retail experience designed for seamless mobile shopping.</p>
</div>
</article>
<!-- Project 3: Personal Portfolio -->
<article class="glass-card glow-hover rounded-xl overflow-hidden group cursor-pointer col-span-1 md:col-span-4 relative aspect-square md:h-[400px] transition-all duration-500">
<img alt="Project Preview" class="absolute inset-0 w-full h-full object-cover transition-transform duration-700 group-hover:scale-105 opacity-80 group-hover:opacity-100" data-alt="A dynamic, interactive personal portfolio website shown on a sleek monitor. The design is bold and asymmetric, utilizing a dark background with striking neon blue highlights and smooth structural lines. It features large, confident typography and subtle glassmorphic panels. The overall mood is creative and cutting-edge, perfectly representing a modern digital craftsman." src="https://lh3.googleusercontent.com/aida-public/AB6AXuBWjpzA5KR4SpssQRaxGHtkNV-6CJzZ0v6HnOSv1P4ZL7zMiA5BnEOY9rT8A8q5ss59YAsSDMhAeNB3Z2cAEcVuBUdR7bCBzGpf5Y2ex7xyeI7nPvw7Jm7KvuSPd5HBbA8ZIyaFhzJ-9fc5S54iZq65__UHogAL2Tf7gUBUJ5NcbRDcfz6vFiMMDg6l6qLzm8NX0YZ39BLNVPWeEeAQxokSTKk06vfHjv3Fzux_WAP42qlnXU5kxcwEyQ1UvEm7Rt5UI60vDpSBA4nq"/>
<div class="absolute inset-0 bg-gradient-to-t from-surface-dim via-surface-dim/60 to-transparent opacity-90"></div>
<div class="absolute bottom-0 left-0 p-6 w-full">
<div class="flex gap-2 mb-4">
<span class="bg-surface/50 backdrop-blur-md border border-white/10 text-on-surface font-label-caps text-label-caps px-3 py-1 rounded-full">Interaction</span>
</div>
<h2 class="font-headline-lg-mobile text-headline-lg-mobile text-on-surface mb-2 group-hover:text-primary transition-colors">Creative Folio</h2>
<p class="font-body-md text-body-md text-on-surface-variant line-clamp-2">A highly animated personal portfolio pushing the boundaries of web motion.</p>
</div>
</article>
<!-- Project 4: Branding + Landing Page -->
<article class="glass-card glow-hover rounded-xl overflow-hidden group cursor-pointer col-span-1 md:col-span-8 relative aspect-[4/3] md:aspect-auto md:h-[400px] transition-all duration-500">
<img alt="Project Preview" class="absolute inset-0 w-full h-full object-cover transition-transform duration-700 group-hover:scale-105 opacity-80 group-hover:opacity-100" data-alt="A comprehensive branding and landing page presentation for a creative agency, laid out in an expansive, grid-like digital environment. The color palette is strictly dark mode with sharp contrasts of stark white and electric violet. The layout includes custom logos, typography specimens, and a hero section featuring a soft neon glow effect. The scene conveys high-end digital craftsmanship and professional reliability." src="https://lh3.googleusercontent.com/aida-public/AB6AXuCz41TQYY2oHOpJBx5y-Ppfym6SqpJaQZ06SagGiVA_Bzy8OIWCOtjwbJM5toUIOOyAvK-SOy0wlpMCS8-6n_bD9ICR3RzFxQko0dct02E0FYjExxN2oGXBAN-AvduVYk9QcQg1og9-06CPp94JocuG9Z8kyoZI1C545Rer81zxaAPkBY-IhH1I32p_DYceIi6TSpFFPwxGUiApj893Sf5aFAGremK8URq38Ea2BARqspDkp6UA1yNdo-5ZTex2BZXW2XHyGVRpAqoY"/>
<div class="absolute inset-0 bg-gradient-to-t from-surface-dim via-surface-dim/50 to-transparent opacity-90"></div>
<div class="absolute bottom-0 left-0 p-8 w-full">
<div class="flex gap-2 mb-4">
<span class="bg-surface/50 backdrop-blur-md border border-white/10 text-on-surface font-label-caps text-label-caps px-3 py-1 rounded-full">Branding</span>
<span class="bg-surface/50 backdrop-blur-md border border-white/10 text-on-surface font-label-caps text-label-caps px-3 py-1 rounded-full">Landing Page</span>
</div>
<h2 class="font-headline-lg-mobile text-headline-lg-mobile md:font-headline-lg md:text-headline-lg text-on-surface mb-2 group-hover:text-primary transition-colors">Creator Brand Identity</h2>
<p class="font-body-md text-body-md text-on-surface-variant max-w-xl">Cohesive visual identity and high-converting landing page for digital creators.</p>
</div>
</article>
</section>
<!-- View All Action -->
<div class="mt-16 text-center">
<button class="inline-flex items-center justify-center gap-2 border border-outline-variant hover:border-primary text-on-surface hover:text-primary font-label-caps text-label-caps px-8 py-4 rounded-DEFAULT transition-all duration-300">
                Load More Projects
                <span class="material-symbols-outlined" style="font-size: 16px;">arrow_downward</span>
</button>
</div>
</main>
<!-- Footer -->
<footer class="bg-surface-container-lowest border-t border-white/10 full-width bottom-0 mt-auto">
<div class="flex flex-col md:flex-row justify-between items-center py-section-gap-mobile md:py-12 px-margin-mobile md:px-gutter max-w-container-max-width mx-auto gap-8">
<div class="font-headline-lg text-headline-lg font-black text-on-surface">
                VANSH
            </div>
<div class="flex flex-col md:flex-row items-center gap-6 text-center md:text-left">
<a class="font-body-md text-body-md text-on-surface-variant hover:text-primary transition-colors duration-300 opacity-80 hover:opacity-100" href="#">Instagram: vanshcodes.x</a>
<a class="font-body-md text-body-md text-on-surface-variant hover:text-primary transition-colors duration-300 opacity-80 hover:opacity-100" href="#">Email: anubhavv8777@gmail.com</a>
<a class="font-body-md text-body-md text-on-surface-variant hover:text-primary transition-colors duration-300 opacity-80 hover:opacity-100" href="#">Phone: +91 9456853697</a>
</div>
<div class="font-label-caps text-label-caps text-on-surface-variant">
                © 2024 VANSH. DIGITAL CRAFTSMANSHIP.
            </div>
</div>
</footer>
</body></html>
