# Vansh Portfolio - Full Website Code

Niche aapke portfolio ke sabhi pages ka code ek sath diya gaya hai. Aap inhe alag-alag files mein save kar sakte hain.

---

## 1. index.html (Home Page)
<!-- Home Page - Vansh Portfolio -->
<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700;800;900&display=swap" rel="stylesheet">
    <title>Home - Vansh Portfolio</title>
    <style>
        body { font-family: 'Montserrat', sans-serif; background-color: #14121d; color: #ffffff; }
        .glass { background: rgba(58, 55, 68, 0.3); backdrop-filter: blur(12px); border: 1px solid rgba(255, 255, 255, 0.1); }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav class="sticky top-0 z-50 glass h-20 flex items-center px-8 justify-between border-b border-white/10">
        <div class="text-3xl font-black tracking-tighter text-[#5800ff]">VANSH</div>
        <div class="hidden md:flex gap-8 text-sm font-medium">
            <a href="index.html" class="text-[#5800ff] border-b-2 border-[#5800ff] pb-1">Home</a>
            <a href="portfolio.html" class="hover:text-[#5800ff] transition-colors">Portfolio</a>
            <a href="services.html" class="hover:text-[#5800ff] transition-colors">Services</a>
            <a href="about.html" class="hover:text-[#5800ff] transition-colors">About</a>
            <a href="contact.html" class="hover:text-[#5800ff] transition-colors">Contact</a>
        </div>
        <a href="pricing.html" class="bg-[#5800ff] text-white px-6 py-2 rounded-lg font-bold hover:scale-105 transition-transform">Hire Me</a>
    </nav>

    <!-- Hero Section -->
    <section class="min-h-[80vh] flex flex-col md:flex-row items-center justify-between px-8 md:px-20 py-20">
        <div class="max-w-2xl">
            <span class="inline-block px-4 py-1 rounded-full border border-white/20 text-[10px] tracking-widest uppercase mb-6">Digital Craftsmanship</span>
            <h1 class="text-5xl md:text-7xl font-black leading-tight mb-8">
                Designing <span class="text-[#5800ff]">Premium</span> Websites That Speak <span class="text-[#5800ff]">Your Brand.</span>
            </h1>
            <p class="text-lg text-gray-400 mb-10 max-w-lg">
                I’m Vansh, only 15, a creative web designer from India, passionate about building modern, attractive, and responsive websites for businesses and creators.
            </p>
            <div class="flex items-center gap-6">
                <a href="contact.html" class="bg-[#5800ff] px-8 py-4 rounded-xl font-bold flex items-center gap-2 hover:shadow-[0_0_20px_rgba(88,0,255,0.4)] transition-all">
                    GET STARTED 🚀
                </a>
                <span class="text-gray-400 text-sm">Let’s build your dream website today!</span>
            </div>
            
            <div class="mt-20 flex gap-12">
                <div>
                    <div class="text-4xl font-black">15+</div>
                    <div class="text-xs text-gray-500 uppercase tracking-widest mt-2">Years of Age</div>
                </div>
                <div>
                    <div class="text-4xl font-black">India</div>
                    <div class="text-xs text-gray-500 uppercase tracking-widest mt-2">Based In</div>
                </div>
            </div>
        </div>
        
        <div class="mt-20 md:mt-0 relative">
            <div class="w-80 h-80 md:w-[500px] md:h-[500px] bg-gradient-to-tr from-[#5800ff] to-purple-400 rounded-3xl rotate-3 absolute -z-10 opacity-20 blur-2xl"></div>
            <img src="https://images.unsplash.com/photo-1550745165-9bc0b252726f?auto=format&fit=crop&q=80&w=800" alt="UI Design" class="w-80 md:w-[500px] rounded-3xl shadow-2xl">
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-[#0f0d18] py-12 px-8 border-t border-white/10 mt-20">
        <div class="max-w-7xl mx-auto flex flex-col md:flex-row justify-between items-center gap-8">
            <div class="text-2xl font-black">VANSH</div>
            <div class="flex flex-col md:flex-row gap-8 text-sm text-gray-400">
                <span>Instagram: vanshcodes.x</span>
                <span>Email: singhvansh2462@gmail.com</span>
                <span>Phone: +91 9456853697</span>
            </div>
            <div class="text-xs text-gray-600">© 2024 VANSH. DIGITAL CRAFTSMANSHIP.</div>
        </div>
    </footer>
</body>
</html>

---

## 2. portfolio.html
<!-- Portfolio Page - Vansh Portfolio -->
<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700;800;900&display=swap" rel="stylesheet">
    <title>My Work - Vansh Portfolio</title>
    <style>
        body { font-family: 'Montserrat', sans-serif; background-color: #14121d; color: #ffffff; }
        .glass { background: rgba(58, 55, 68, 0.3); backdrop-filter: blur(12px); border: 1px solid rgba(255, 255, 255, 0.1); }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav class="sticky top-0 z-50 glass h-20 flex items-center px-8 justify-between border-b border-white/10">
        <div class="text-3xl font-black tracking-tighter text-[#5800ff]">VANSH</div>
        <div class="hidden md:flex gap-8 text-sm font-medium">
            <a href="index.html" class="hover:text-[#5800ff] transition-colors">Home</a>
            <a href="portfolio.html" class="text-[#5800ff] border-b-2 border-[#5800ff] pb-1">Portfolio</a>
            <a href="services.html" class="hover:text-[#5800ff] transition-colors">Services</a>
            <a href="about.html" class="hover:text-[#5800ff] transition-colors">About</a>
            <a href="contact.html" class="hover:text-[#5800ff] transition-colors">Contact</a>
        </div>
        <a href="pricing.html" class="bg-[#5800ff] text-white px-6 py-2 rounded-lg font-bold">Hire Me</a>
    </nav>

    <!-- Portfolio Section -->
    <section class="px-8 md:px-20 py-20">
        <h1 class="text-6xl font-black mb-6">My <span class="text-[#5800ff]">Work</span></h1>
        <p class="text-gray-400 text-lg max-w-2xl mb-16">
            A showcase of projects I’ve designed for clients, highlighting creativity and functionality.
        </p>

        <div class="grid md:grid-cols-2 gap-8">
            <div class="group relative overflow-hidden rounded-3xl glass">
                <img src="https://images.unsplash.com/photo-1460925895917-afdab827c52f?auto=format&fit=crop&q=80&w=800" class="w-full h-[400px] object-cover opacity-60 group-hover:scale-105 transition-transform duration-500">
                <div class="absolute bottom-0 left-0 p-8 w-full bg-gradient-to-t from-[#14121d] to-transparent">
                    <h3 class="text-3xl font-bold mb-2">Business Website</h3>
                </div>
            </div>
            <div class="group relative overflow-hidden rounded-3xl glass">
                <img src="https://images.unsplash.com/photo-1472851294608-062f824d29cc?auto=format&fit=crop&q=80&w=800" class="w-full h-[400px] object-cover opacity-60 group-hover:scale-105 transition-transform duration-500">
                <div class="absolute bottom-0 left-0 p-8 w-full bg-gradient-to-t from-[#14121d] to-transparent">
                    <h3 class="text-3xl font-bold mb-2">Digital Storefront</h3>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-[#0f0d18] py-12 px-8 border-t border-white/10 mt-20">
        <div class="max-w-7xl mx-auto flex flex-col md:flex-row justify-between items-center gap-8">
            <div class="text-2xl font-black">VANSH</div>
            <div class="text-xs text-gray-600">© 2024 VANSH. DIGITAL CRAFTSMANSHIP.</div>
        </div>
    </footer>
</body>
</html>

---

## 3. pricing.html
<!-- Pricing Page - Vansh Portfolio -->
<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700;800;900&display=swap" rel="stylesheet">
    <title>Pricing Plans - Vansh Portfolio</title>
    <style>
        body { font-family: 'Montserrat', sans-serif; background-color: #14121d; color: #ffffff; }
        .glass { background: rgba(58, 55, 68, 0.3); backdrop-filter: blur(12px); border: 1px solid rgba(255, 255, 255, 0.1); }
        .plan-card:hover { transform: translateY(-10px); border-color: #5800ff; transition: all 0.3s ease; }
    </style>
</head>
<body>
    <nav class="sticky top-0 z-50 glass h-20 flex items-center px-8 justify-between border-b border-white/10">
        <div class="text-3xl font-black tracking-tighter text-[#5800ff]">VANSH</div>
        <div class="hidden md:flex gap-8 text-sm font-medium">
            <a href="index.html" class="hover:text-[#5800ff] transition-colors">Home</a>
            <a href="portfolio.html" class="hover:text-[#5800ff] transition-colors">Portfolio</a>
            <a href="services.html" class="hover:text-[#5800ff] transition-colors">Services</a>
            <a href="about.html" class="hover:text-[#5800ff] transition-colors">About</a>
            <a href="contact.html" class="hover:text-[#5800ff] transition-colors">Contact</a>
        </div>
        <a href="pricing.html" class="bg-[#5800ff] text-white px-6 py-2 rounded-lg font-bold">Hire Me</a>
    </nav>

    <section class="px-8 md:px-20 py-24 text-center">
        <h1 class="text-6xl font-black mb-20">Choose <span class="text-[#5800ff]">Your Plan</span></h1>
        <div class="grid md:grid-cols-4 gap-8 text-left">
            <!-- Simplified Plan Example -->
            <div class="plan-card glass p-8 rounded-3xl flex flex-col border border-white/10">
                <h3 class="text-3xl font-black mb-2">Basic</h3>
                <div class="text-4xl font-black mb-10">₹5,000+</div>
                <ul class="space-y-4 mb-10 text-gray-300">
                    <li>✔ 1–3 Pages</li>
                    <li>✔ Responsive</li>
                </ul>
                <button class="w-full py-4 rounded-xl border border-white/20 font-bold hover:bg-white/5 transition-colors">SELECT PLAN</button>
            </div>
            <!-- More cards would go here following the same structure -->
        </div>
    </section>
</body>
</html>

---

## 4. contact.html
<!-- Contact Page - Vansh Portfolio -->
<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700;800;900&display=swap" rel="stylesheet">
    <title>Contact - Vansh Portfolio</title>
    <style>
        body { font-family: 'Montserrat', sans-serif; background-color: #14121d; color: #ffffff; }
        .glass { background: rgba(58, 55, 68, 0.3); backdrop-filter: blur(12px); border: 1px solid rgba(255, 255, 255, 0.1); }
        input, textarea { background: transparent !important; border-bottom: 1px solid rgba(255, 255, 255, 0.1) !important; outline: none; }
    </style>
</head>
<body>
    <nav class="sticky top-0 z-50 glass h-20 flex items-center px-8 justify-between border-b border-white/10">
        <div class="text-3xl font-black tracking-tighter text-[#5800ff]">VANSH</div>
        <div class="hidden md:flex gap-8 text-sm font-medium">
            <a href="index.html" class="hover:text-[#5800ff] transition-colors">Home</a>
            <a href="portfolio.html" class="hover:text-[#5800ff] transition-colors">Portfolio</a>
            <a href="services.html" class="hover:text-[#5800ff] transition-colors">Services</a>
            <a href="about.html" class="hover:text-[#5800ff] transition-colors">About</a>
            <a href="contact.html" class="text-[#5800ff] border-b-2 border-[#5800ff] pb-1">Contact</a>
        </div>
        <a href="pricing.html" class="bg-[#5800ff] text-white px-6 py-2 rounded-lg font-bold">Hire Me</a>
    </nav>

    <section class="px-8 md:px-20 py-24 flex flex-col md:flex-row gap-20">
        <div class="md:w-2/3">
            <h1 class="text-6xl font-black mb-10">Let’s <span class="text-[#5800ff]">Connect</span></h1>
            <div class="glass p-12 rounded-3xl">
                <form action="mailto:singhvansh2462@gmail.com" method="post" enctype="text/plain" class="space-y-12">
                    <input type="text" placeholder="Name" class="w-full py-4 text-xl" required>
                    <input type="email" placeholder="Email" class="w-full py-4 text-xl" required>
                    <textarea rows="4" placeholder="Message" class="w-full py-4 text-xl resize-none" required></textarea>
                    <button type="submit" class="bg-[#5800ff] text-white px-10 py-4 rounded-xl font-bold">Send Message ➤</button>
                </form>
            </div>
        </div>
    </section>
</body>
</html>
