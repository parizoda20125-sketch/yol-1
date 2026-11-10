**<!DOCTYPE html>**

**<html lang="uz">**

**<head>**

&#x20;   **<meta charset="UTF-8">**

&#x20;   **<meta name="viewport" content="width=device-width, initial-scale=1.0">**

&#x20;   **<title>Ideal Yo'l Qurilishi va Infratuzilma Standartlari</title>**

&#x20;   **<!-- Tailwind CSS CDN -->**

&#x20;   **<script src="https://cdn.tailwindcss.com"></script>**

&#x20;   **<!-- Lucide Icons -->**

&#x20;   **<script src="https://unpkg.com/lucide@latest"></script>**

&#x20;   **<style>**

&#x20;       **@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800\&display=swap');**

&#x20;       **body {**

&#x20;           **font-family: 'Inter', sans-serif;**

&#x20;           **scroll-behavior: smooth;**

&#x20;       **}**

&#x20;       **.road-layer {**

&#x20;           **transition: all 0.3s ease;**

&#x20;       **}**

&#x20;       **.road-layer:hover {**

&#x20;           **transform: scale(1.02);**

&#x20;       **}**

&#x20;   **</style>**

**</head>**

**<body class="bg-slate-900 text-slate-100 min-h-screen flex flex-col justify-between selection:bg-amber-500 selection:text-slate-900">**



&#x20;   **<!-- Header Section -->**

&#x20;   **<header class="border-b border-slate-800 bg-slate-950/80 backdrop-blur-md sticky top-0 z-50">**

&#x20;       **<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">**

&#x20;           **<div class="flex items-center space-x-3">**

&#x20;               **<div class="p-2.5 bg-amber-500/10 border border-amber-500/30 rounded-xl text-amber-500">**

&#x20;                   **<i data-lucide="construction" class="w-7 h-7"></i>**

&#x20;               **</div>**

&#x20;               **<div>**

&#x20;                   **<h1 class="font-bold text-xl text-white tracking-wide">RoadMaster Pro</h1>**

&#x20;                   **<p class="text-xs text-slate-400">Yo'l qurilishi va infratuzilma standarti</p>**

&#x20;               **</div>**

&#x20;           **</div>**

&#x20;           **<nav class="hidden md:flex space-x-8 text-sm font-medium text-slate-300">**

&#x20;               **<a href="#comparison" class="hover:text-amber-400 transition-colors">Taqqoslash</a>**

&#x20;               **<a href="#ideal-steps" class="hover:text-amber-400 transition-colors">Ideal Bosqichlar</a>**

&#x20;               **<a href="#economy" class="hover:text-amber-400 transition-colors">Tejamkorlik</a>**

&#x20;               **<a href="#simulator" class="hover:text-amber-400 transition-colors">Simulyatsiya</a>**

&#x20;               **<a href="#register" class="hover:text-amber-400 transition-colors">Ariza Yuborish</a>**

&#x20;           **</nav>**

&#x20;           **<a href="#register" class="px-5 py-2.5 bg-amber-500 hover:bg-amber-400 text-slate-950 font-semibold rounded-xl transition-all shadow-lg shadow-amber-500/20 text-sm">**

&#x20;               **Taklif Yuborish**

&#x20;           **</a>**

&#x20;       **</div>**

&#x20;   **</header>**



&#x20;   **<main class="flex-grow">**

&#x20;       **<!-- Hero Section -->**

&#x20;       **<section class="relative py-24 overflow-hidden bg-gradient-to-b from-slate-950 via-slate-900 to-slate-900">**

&#x20;           **<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center relative z-10">**

&#x20;               **<span class="inline-flex items-center gap-2 px-3 py-1.5 rounded-full text-xs font-semibold bg-amber-500/10 border border-amber-500/20 text-amber-400 mb-6">**

&#x20;                   **<i data-lucide="piggy-bank" class="w-4 h-4"></i> Budjetni Tejovchi Innovatsion Yondashuv**

&#x20;               **</span>**

&#x20;               **<h1 class="text-4xl md:text-6xl font-extrabold text-white tracking-tight leading-tight max-w-4xl mx-auto">**

&#x20;                   **Arzon, Sifatli va <span class="text-transparent bg-clip-text bg-gradient-to-r from-amber-400 to-emerald-400">Ideal Yo'llar</span> Infratuzilmasi**

&#x20;               **</h1>**

&#x20;               **<p class="mt-6 text-lg text-slate-400 max-w-2xl mx-auto">**

&#x20;                   **Qayta qazish va takroriy xarajatlarga chek qo'yamiz. Har bir viloyat hamda qishloq uchun to'g'ri rejalashtirish orqali davlat va jamoatchilik mablag'larini 40% gacha tejang!**

&#x20;               **</p>**

&#x20;               **<div class="mt-10 flex flex-wrap justify-center gap-4">**

&#x20;                   **<a href="#register" class="px-7 py-3.5 bg-amber-500 hover:bg-amber-400 text-slate-950 font-bold rounded-xl transition-all shadow-lg shadow-amber-500/20 flex items-center gap-2">**

&#x20;                       **<i data-lucide="map-pin" class="w-5 h-5"></i> O'z Qishlog'ingizni Ro'yxatdan O'tkazing**

&#x20;                   **</a>**

&#x20;                   **<a href="#economy" class="px-7 py-3.5 bg-slate-800 hover:bg-slate-700 text-slate-200 font-semibold rounded-xl border border-slate-700 transition-all flex items-center gap-2">**

&#x20;                       **<i data-lucide="trending-down" class="w-5 h-5"></i> Tejamkorlik Kalkulyatori**

&#x20;                   **</a>**

&#x20;               **</div>**

&#x20;           **</div>**

&#x20;       **</section>**



&#x20;       **<!-- Visual Gallery / Image Section -->**

&#x20;       **<section class="py-12 bg-slate-950 border-b border-slate-800/80">**

&#x20;           **<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">**

&#x20;               **<div class="grid md:grid-cols-3 gap-6">**

&#x20;                   **<div class="relative group overflow-hidden rounded-2xl border border-slate-800 h-64">**

&#x20;                       **<img src="https://images.unsplash.com/photo-1541888946425-d0fbb186a5b2?auto=format\&fit=crop\&w=800\&q=80" alt="Yer osti muhandislik ishlari" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" onerror="this.src='https://placehold.co/800x500/1e293b/94a3b8?text=Muhandislik+Ishlari'">**

&#x20;                       **<div class="absolute inset-0 bg-gradient-to-t from-slate-950 via-slate-950/40 to-transparent p-6 flex flex-col justify-end">**

&#x20;                           **<span class="text-xs text-amber-400 font-semibold">1-Bosqich</span>**

&#x20;                           **<h3 class="text-lg font-bold text-white">Yer Osti Kommunikatsiyasi</h3>**

&#x20;                       **</div>**

&#x20;                   **</div>**

&#x20;                   **<div class="relative group overflow-hidden rounded-2xl border border-slate-800 h-64">**

&#x20;                       **<img src="https://images.unsplash.com/photo-1578575437130-527eed3abbec?auto=format\&fit=crop\&w=800\&q=80" alt="Yo'l zichlash va qurish" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" onerror="this.src='https://placehold.co/800x500/1e293b/94a3b8?text=Zichlash+va+Poydevor'">**

&#x20;                       **<div class="absolute inset-0 bg-gradient-to-t from-slate-950 via-slate-950/40 to-transparent p-6 flex flex-col justify-end">**

&#x20;                           **<span class="text-xs text-amber-400 font-semibold">2-Bosqich</span>**

&#x20;                           **<h3 class="text-lg font-bold text-white">Mustahkam Shag'al Poydevor</h3>**

&#x20;                       **</div>**

&#x20;                   **</div>**

&#x20;                   **<div class="relative group overflow-hidden rounded-2xl border border-slate-800 h-64">**

&#x20;                       **<img src="https://images.unsplash.com/photo-1621905251189-08b45d6a269e?auto=format\&fit=crop\&w=800\&q=80" alt="Ideal Asfalt va belgilash" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" onerror="this.src='https://placehold.co/800x500/1e293b/94a3b8?text=Ideal+Yo\\'l'">**

&#x20;                       **<div class="absolute inset-0 bg-gradient-to-t from-slate-950 via-slate-950/40 to-transparent p-6 flex flex-col justify-end">**

&#x20;                           **<span class="text-xs text-emerald-400 font-semibold">Yakuniy Natija</span>**

&#x20;                           **<h3 class="text-lg font-bold text-white">Uzoq Yillik Sifatli Yo'l</h3>**

&#x20;                       **</div>**

&#x20;                   **</div>**

&#x20;               **</div>**

&#x20;           **</div>**

&#x20;       **</section>**



&#x20;       **<!-- Cost Reduction \& Economy Section -->**

&#x20;       **<section id="economy" class="py-16 bg-slate-900 border-t border-slate-800">**

&#x20;           **<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">**

&#x20;               **<div class="text-center mb-12">**

&#x20;                   **<h2 class="text-3xl font-bold text-white">Kam Xarajat evaziga Maksimal Sifat</h2>**

&#x20;                   **<p class="text-slate-400 mt-2">Mablag'larni to'g'ri yo'naltirish va budjetni tejash mexanizmlari</p>**

&#x20;               **</div>**



&#x20;               **<div class="grid md:grid-cols-3 gap-8 mb-12">**

&#x20;                   **<div class="bg-slate-950 p-6 rounded-2xl border border-slate-800 hover:border-emerald-500/40 transition-all">**

&#x20;                       **<div class="w-12 h-12 bg-emerald-500/10 rounded-xl flex items-center justify-center text-emerald-400 mb-4">**

&#x20;                           **<i data-lucide="dollar-sign" class="w-6 h-6"></i>**

&#x20;                       **</div>**

&#x20;                       **<h3 class="text-lg font-bold text-white">40% Xarajat Tejalishi</h3>**

&#x20;                       **<p class="text-xs text-slate-400 mt-2">Asfaltni qayta-qayta buzib qazish va yamoqlash ishlariga ketadigan ortiqcha budjet batamom qisqaradi.</p>**

&#x20;                   **</div>**



&#x20;                   **<div class="bg-slate-950 p-6 rounded-2xl border border-slate-800 hover:border-emerald-500/40 transition-all">**

&#x20;                       **<div class="w-12 h-12 bg-emerald-500/10 rounded-xl flex items-center justify-center text-emerald-400 mb-4">**

&#x20;                           **<i data-lucide="clock" class="w-6 h-6"></i>**

&#x20;                       **</div>**

&#x20;                       **<h3 class="text-lg font-bold text-white">Vaqt Tejamkorligi</h3>**

&#x20;                       **<p class="text-xs text-slate-400 mt-2">Kommunikatsiya tashkilotlari bir vaqtning o'zida ishlagani sababli loyiha muddati 2 barobar tezlashadi.</p>**

&#x20;                   **</div>**



&#x20;                   **<div class="bg-slate-950 p-6 rounded-2xl border border-slate-800 hover:border-emerald-500/40 transition-all">**

&#x20;                       **<div class="w-12 h-12 bg-emerald-500/10 rounded-xl flex items-center justify-center text-emerald-400 mb-4">**

&#x20;                           **<i data-lucide="shield-check" class="w-6 h-6"></i>**

&#x20;                       **</div>**

&#x20;                       **<h3 class="text-lg font-bold text-white">15+ Yil Kafolat</h3>**

&#x20;                       **<p class="text-xs text-slate-400 mt-2">Poydevor ostida suv quvurlari oqmasligi va mustahkam bosim tufayli yo'l uzoq yillar o'tirmaydi va yorilmaydi.</p>**

&#x20;                   **</div>**

&#x20;               **</div>**



&#x20;               **<!-- Calculator Box -->**

&#x20;               **<div class="bg-slate-950 p-6 md:p-8 rounded-3xl border border-slate-800 max-w-3xl mx-auto">**

&#x20;                   **<h3 class="text-xl font-bold text-white text-center mb-6 flex items-center justify-center gap-2">**

&#x20;                       **<i data-lucide="calculator" class="w-5 h-5 text-amber-500"></i> Hududiy Tejamkorlik Hisoblagichi**

&#x20;                   **</h3>**

&#x20;                   **<div class="grid sm:grid-cols-2 gap-4 mb-6">**

&#x20;                       **<div>**

&#x20;                           **<label class="block text-xs font-semibold text-slate-400 mb-2">Yo'l uzunligi (km):</label>**

&#x20;                           **<input type="number" id="calc-km" value="5" min="1" class="w-full bg-slate-900 border border-slate-800 rounded-xl px-4 py-2.5 text-white text-sm focus:outline-none focus:border-amber-500">**

&#x20;                       **</div>**

&#x20;                       **<div>**

&#x20;                           **<label class="block text-xs font-semibold text-slate-400 mb-2">Amaldagi rejasiz qazishlar soni:</label>**

&#x20;                           **<input type="number" id="calc-digs" value="3" min="0" class="w-full bg-slate-900 border border-slate-800 rounded-xl px-4 py-2.5 text-white text-sm focus:outline-none focus:border-amber-500">**

&#x20;                       **</div>**

&#x20;                   **</div>**

&#x20;                   **<div class="bg-slate-900 p-4 rounded-2xl border border-slate-800 text-center">**

&#x20;                       **<p class="text-xs text-slate-400">Rejalashtirish orqali tejab qolinadigan taxminiy mablag':</p>**

&#x20;                       **<p id="calc-result" class="text-2xl font-extrabold text-emerald-400 mt-1">150,000,000 UZS</p>**

&#x20;                   **</div>**

&#x20;               **</div>**

&#x20;           **</div>**

&#x20;       **</section>**



&#x20;       **<!-- Comparison Section -->**

&#x20;       **<section id="comparison" class="py-16 bg-slate-900 border-t border-slate-800">**

&#x20;           **<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">**

&#x20;               **<div class="text-center mb-12">**

&#x20;                   **<h2 class="text-3xl font-bold text-white">Ikki xil yondashuv: Taqqoslang</h2>**

&#x20;                   **<p class="text-slate-400 mt-2">Amaliyotdagi xatolar va biz taklif qilayotgan tizimli ideal model</p>**

&#x20;               **</div>**



&#x20;               **<div class="grid md:grid-cols-2 gap-8">**

&#x20;                   **<!-- Bad Practice -->**

&#x20;                   **<div class="bg-red-950/20 border border-red-900/40 rounded-2xl p-6 relative overflow-hidden">**

&#x20;                       **<div class="absolute -right-6 -top-6 w-24 h-24 bg-red-500/10 rounded-full blur-xl"></div>**

&#x20;                       **<div class="flex items-center justify-between mb-6">**

&#x20;                           **<span class="flex items-center gap-2 text-red-400 font-bold text-lg">**

&#x20;                               **<i data-lucide="x-circle" class="w-6 h-6"></i> Noto'g'ri Ketma-ketlik (Xato)**

&#x20;                           **</span>**

&#x20;                           **<span class="text-xs bg-red-500/20 text-red-300 px-3 py-1 rounded-full border border-red-500/30">Zararli usul</span>**

&#x20;                       **</div>**

&#x20;                       **<ul class="space-y-4">**

&#x20;                           **<li class="flex items-start gap-3 bg-slate-900/60 p-3.5 rounded-xl border border-red-900/30">**

&#x20;                               **<span class="w-6 h-6 rounded-full bg-red-500/20 text-red-400 flex items-center justify-center font-bold text-xs shrink-0 mt-0.5">1</span>**

&#x20;                               **<div>**

&#x20;                                   **<h4 class="font-semibold text-slate-200 text-sm">Shoshilinch Asfaltlash</h4>**

&#x20;                                   **<p class="text-xs text-slate-400 mt-1">Yer osti tarmoqlari holati tekshirilmasdan asfalt yotqiziladi.</p>**

&#x20;                               **</div>**

&#x20;                           **</li>**

&#x20;                           **<li class="flex items-start gap-3 bg-slate-900/60 p-3.5 rounded-xl border border-red-900/30">**

&#x20;                               **<span class="w-6 h-6 rounded-full bg-red-500/20 text-red-400 flex items-center justify-center font-bold text-xs shrink-0 mt-0.5">2</span>**

&#x20;                               **<div>**

&#x20;                                   **<h4 class="font-semibold text-slate-200 text-sm">Suv/Gaz quvurining yorilishi va qazish</h4>**

&#x20;                                   **<p class="text-xs text-slate-400 mt-1">Yangi yotqizilgan asfalt qayta kavlab tashlanadi va suv o'tkaziladi.</p>**

&#x20;                               **</div>**

&#x20;                           **</li>**

&#x20;                           **<li class="flex items-start gap-3 bg-slate-900/60 p-3.5 rounded-xl border border-red-900/30">**

&#x20;                               **<span class="w-6 h-6 rounded-full bg-red-500/20 text-red-400 flex items-center justify-center font-bold text-xs shrink-0 mt-0.5">3</span>**

&#x20;                               **<div>**

&#x20;                                   **<h4 class="font-semibold text-slate-200 text-sm">Siyqa (Yamoq) Asfalt Yamoqlash</h4>**

&#x20;                                   **<p class="text-xs text-slate-400 mt-1">Qazilgan joy o'nqir-cho'nqir qilib yopiladi va yo'l o'tirib qoladi.</p>**

&#x20;                               **</div>**

&#x20;                           **</li>**

&#x20;                       **</ul>**

&#x20;                       **<div class="mt-6 p-4 bg-red-900/20 rounded-xl text-red-300 text-xs flex items-center gap-3 border border-red-800/30">**

&#x20;                           **<i data-lucide="alert-circle" class="w-5 h-5 shrink-0"></i>**

&#x20;                           **Oqibat: Budjet isrof bo'ladi, haydovchilar noqulaylik sezadi, yo'l umri 3-5 barobarga qisqaradi.**

&#x20;                       **</div>**

&#x20;                   **</div>**



&#x20;                   **<!-- Good Practice -->**

&#x20;                   **<div class="bg-emerald-950/20 border border-emerald-900/40 rounded-2xl p-6 relative overflow-hidden">**

&#x20;                       **<div class="absolute -right-6 -top-6 w-24 h-24 bg-emerald-500/10 rounded-full blur-xl"></div>**

&#x20;                       **<div class="flex items-center justify-between mb-6">**

&#x20;                           **<span class="flex items-center gap-2 text-emerald-400 font-bold text-lg">**

&#x20;                               **<i data-lucide="check-circle" class="w-6 h-6"></i> Ideal Ketma-ketlik (To'g'ri)**

&#x20;                           **</span>**

&#x20;                           **<span class="text-xs bg-emerald-500/20 text-emerald-300 px-3 py-1 rounded-full border border-emerald-500/30">Standart usul</span>**

&#x20;                       **</div>**

&#x20;                       **<ul class="space-y-4">**

&#x20;                           **<li class="flex items-start gap-3 bg-slate-900/60 p-3.5 rounded-xl border border-emerald-900/30">**

&#x20;                               **<span class="w-6 h-6 rounded-full bg-emerald-500/20 text-emerald-400 flex items-center justify-center font-bold text-xs shrink-0 mt-0.5">1</span>**

&#x20;                               **<div>**

&#x20;                                   **<h4 class="font-semibold text-slate-200 text-sm">Integrallashgan Rejalashtirish</h4>**

&#x20;                                   **<p class="text-xs text-slate-400 mt-1">Hamma tashkilotlar (Suv, Gaz, Elektr, Aloqa) yagona xarita asosida kelishadi.</p>**

&#x20;                               **</div>**

&#x20;                           **</li>**

&#x20;                           **<li class="flex items-start gap-3 bg-slate-900/60 p-3.5 rounded-xl border border-emerald-900/30">**

&#x20;                               **<span class="w-6 h-6 rounded-full bg-emerald-500/20 text-emerald-400 flex items-center justify-center font-bold text-xs shrink-0 mt-0.5">2</span>**

&#x20;                               **<div>**

&#x20;                                   **<h4 class="font-semibold text-slate-200 text-sm">Barcha Yer Osti Tarmoqlarini Yotqizish</h4>**

&#x20;                                   **<p class="text-xs text-slate-400 mt-1">Trubalar, kabellar, drenaj tizimlari va maxsus tunnel (kolektor)lar tayyorlanadi.</p>**

&#x20;                               **</div>**

&#x20;                           **</li>**

&#x20;                           **<li class="flex items-start gap-3 bg-slate-900/60 p-3.5 rounded-xl border border-emerald-900/30">**

&#x20;                               **<span class="w-6 h-6 rounded-full bg-emerald-500/20 text-emerald-400 flex items-center justify-center font-bold text-xs shrink-0 mt-0.5">3</span>**

&#x20;                               **<div>**

&#x20;                                   **<h4 class="font-semibold text-slate-200 text-sm">Mustahkam Poydevor \& Sifatli Asfalt</h4>**

&#x20;                                   **<p class="text-xs text-slate-400 mt-1">Zichlashtirish va ko'p qatlamli asfalt yotqizish runsiz amalga oshiriladi.</p>**

&#x20;                               **</div>**

&#x20;                           **</li>**

&#x20;                       **</ul>**

&#x20;                       **<div class="mt-6 p-4 bg-emerald-900/20 rounded-xl text-emerald-300 text-xs flex items-center gap-3 border border-emerald-800/30">**

&#x20;                           **<i data-lucide="sparkles" class="w-5 h-5 shrink-0"></i>**

&#x20;                           **Natija: Yo'l 15-20 yil mobaynida qazilmasdan sifatli xizmat qiladi va budjet tejaladi.**

&#x20;                       **</div>**

&#x20;                   **</div>**

&#x20;               **</div>**

&#x20;           **</div>**

&#x20;       **</section>**



&#x20;       **<!-- Ideal Steps Section -->**

&#x20;       **<section id="ideal-steps" class="py-16 bg-slate-950">**

&#x20;           **<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">**

&#x20;               **<div class="text-center mb-16">**

&#x20;                   **<h2 class="text-3xl font-bold text-white">Ideal Yo'l Qurilishining 5 Bosqichi</h2>**

&#x20;                   **<p class="text-slate-400 mt-2">Haqiqiy sifat va mustahkamlikni ta'minlovchi xalqaro standart ketma-ketligi</p>**

&#x20;               **</div>**



&#x20;               **<div class="grid sm:grid-cols-2 lg:grid-cols-5 gap-6">**

&#x20;                   **<!-- Step 1 -->**

&#x20;                   **<div class="bg-slate-900 p-6 rounded-2xl border border-slate-800 hover:border-amber-500/50 transition-all group relative">**

&#x20;                       **<div class="w-12 h-12 bg-amber-500/10 rounded-xl flex items-center justify-center text-amber-500 mb-4 group-hover:bg-amber-500 group-hover:text-slate-950 transition-all">**

&#x20;                           **<i data-lucide="map" class="w-6 h-6"></i>**

&#x20;                       **</div>**

&#x20;                       **<span class="text-xs font-semibold text-amber-500 tracking-wider">01-BOSQICH</span>**

&#x20;                       **<h3 class="text-lg font-bold text-white mt-1">Loyiha \& GIS</h3>**

&#x20;                       **<p class="text-xs text-slate-400 mt-2">Geodeziya va yer osti xaritalarini raqamlashtirish. Barcha tashkilotlar kelishuvi.</p>**

&#x20;                   **</div>**



&#x20;                   **<!-- Step 2 -->**

&#x20;                   **<div class="bg-slate-900 p-6 rounded-2xl border border-slate-800 hover:border-amber-500/50 transition-all group relative">**

&#x20;                       **<div class="w-12 h-12 bg-amber-500/10 rounded-xl flex items-center justify-center text-amber-500 mb-4 group-hover:bg-amber-500 group-hover:text-slate-950 transition-all">**

&#x20;                           **<i data-lucide="pipette" class="w-6 h-6"></i>**

&#x20;                       **</div>**

&#x20;                       **<span class="text-xs font-semibold text-amber-500 tracking-wider">02-BOSQICH</span>**

&#x20;                       **<h3 class="text-lg font-bold text-white mt-1">Kommunikatsiya</h3>**

&#x20;                       **<p class="text-xs text-slate-400 mt-2">Suv, gaz, elektr, optik tolali aloqa quvurlari va drenaj tizimlarini o'tkazish.</p>**

&#x20;                   **</div>**



&#x20;                   **<!-- Step 3 -->**

&#x20;                   **<div class="bg-slate-900 p-6 rounded-2xl border border-slate-800 hover:border-amber-500/50 transition-all group relative">**

&#x20;                       **<div class="w-12 h-12 bg-amber-500/10 rounded-xl flex items-center justify-center text-amber-500 mb-4 group-hover:bg-amber-500 group-hover:text-slate-950 transition-all">**

&#x20;                           **<i data-lucide="layers" class="w-6 h-6"></i>**

&#x20;                       **</div>**

&#x20;                       **<span class="text-xs font-semibold text-amber-500 tracking-wider">03-BOSQICH</span>**

&#x20;                       **<h3 class="text-lg font-bold text-white mt-1">Poydevor / Zichlash</h3>**

&#x20;                       **<p class="text-xs text-slate-400 mt-2">Qum-shag'al aralashmasini yotqizish, geotukima va bir necha bosqichli zichlashtirish.</p>**

&#x20;                   **</div>**



&#x20;                   **<!-- Step 4 -->**

&#x20;                   **<div class="bg-slate-900 p-6 rounded-2xl border border-slate-800 hover:border-amber-500/50 transition-all group relative">**

&#x20;                       **<div class="w-12 h-12 bg-amber-500/10 rounded-xl flex items-center justify-center text-amber-500 mb-4 group-hover:bg-amber-500 group-hover:text-slate-950 transition-all">**

&#x20;                           **<i data-lucide="disc" class="w-6 h-6"></i>**

&#x20;                       **</div>**

&#x20;                       **<span class="text-xs font-semibold text-amber-500 tracking-wider">04-BOSQICH</span>**

&#x20;                       **<h3 class="text-lg font-bold text-white mt-1">Asfalt Yotqizish</h3>**

&#x20;                       **<p class="text-xs text-slate-400 mt-2">Yirik va mayda donador sifatli asfalt qatlamlarini issiqlik texnologiyasi bilan yotqizish.</p>**

&#x20;                   **</div>**



&#x20;                   **<!-- Step 5 -->**

&#x20;                   **<div class="bg-slate-900 p-6 rounded-2xl border border-slate-800 hover:border-amber-500/50 transition-all group relative">**

&#x20;                       **<div class="w-12 h-12 bg-amber-500/10 rounded-xl flex items-center justify-center text-amber-500 mb-4 group-hover:bg-amber-500 group-hover:text-slate-950 transition-all">**

&#x20;                           **<i data-lucide="check-check" class="w-6 h-6"></i>**

&#x20;                       **</div>**

&#x20;                       **<span class="text-xs font-semibold text-amber-500 tracking-wider">05-BOSQICH</span>**

&#x20;                       **<h3 class="text-lg font-bold text-white mt-1">Chiziqlar \& Belgilar</h3>**

&#x20;                       **<p class="text-xs text-slate-400 mt-2">Termoplastik chiziqlar, svetoforlar va piyodalar infratuzilmasini sozlash.</p>**

&#x20;                   **</div>**

&#x20;               **</div>**

&#x20;           **</div>**

&#x20;       **</section>**



&#x20;       **<!-- Interactive Simulator Section -->**

&#x20;       **<section id="simulator" class="py-16 bg-slate-900 border-t border-slate-800">**

&#x20;           **<div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8">**

&#x20;               **<div class="text-center mb-10">**

&#x20;                   **<h2 class="text-3xl font-bold text-white">Yo'l Qurilishi Simulyatori</h2>**

&#x20;                   **<p class="text-slate-400 mt-2">Bosqichlarni ketma-ket bosing va ideal yo'l qatlamlarini barpo eting</p>**

&#x20;               **</div>**



&#x20;               **<div class="bg-slate-950 p-6 md:p-8 rounded-3xl border border-slate-800 shadow-2xl">**

&#x20;                   **<!-- Buttons Control -->**

&#x20;                   **<div class="flex flex-wrap gap-3 justify-center mb-8" id="sim-controls">**

&#x20;                       **<button id="btn-step-1" class="sim-btn px-4 py-2.5 bg-slate-800 hover:bg-slate-700 text-slate-200 text-xs font-semibold rounded-xl border border-slate-700 flex items-center gap-2 transition-all">**

&#x20;                           **<span class="w-5 h-5 rounded-full bg-slate-700 flex items-center justify-center text-white">1</span> Rejalashtirish**

&#x20;                       **</button>**

&#x20;                       **<button id="btn-step-2" class="sim-btn px-4 py-2.5 bg-slate-800 hover:bg-slate-700 text-slate-200 text-xs font-semibold rounded-xl border border-slate-700 flex items-center gap-2 transition-all">**

&#x20;                           **<span class="w-5 h-5 rounded-full bg-slate-700 flex items-center justify-center text-white">2</span> Truba \& Quvurlar**

&#x20;                       **</button>**

&#x20;                       **<button id="btn-step-3" class="sim-btn px-4 py-2.5 bg-slate-800 hover:bg-slate-700 text-slate-200 text-xs font-semibold rounded-xl border border-slate-700 flex items-center gap-2 transition-all">**

&#x20;                           **<span class="w-5 h-5 rounded-full bg-slate-700 flex items-center justify-center text-white">3</span> Shag'al Poydevor**

&#x20;                       **</button>**

&#x20;                       **<button id="btn-step-4" class="sim-btn px-4 py-2.5 bg-slate-800 hover:bg-slate-700 text-slate-200 text-xs font-semibold rounded-xl border border-slate-700 flex items-center gap-2 transition-all">**

&#x20;                           **<span class="w-5 h-5 rounded-full bg-slate-700 flex items-center justify-center text-white">4</span> Asfalt Qatlam**

&#x20;                       **</button>**

&#x20;                       **<button id="btn-reset" class="px-4 py-2.5 bg-red-500/10 hover:bg-red-500/20 text-red-400 text-xs font-semibold rounded-xl border border-red-500/20 flex items-center gap-2 transition-all">**

&#x20;                           **<i data-lucide="rotate-ccw" class="w-4 h-4"></i> Qayta boshlash**

&#x20;                       **</button>**

&#x20;                   **</div>**



&#x20;                   **<!-- Visual Representation -->**

&#x20;                   **<div class="relative w-full h-64 bg-slate-900 rounded-2xl border border-slate-800 overflow-hidden flex flex-col justify-end p-4 gap-1" id="road-canvas">**

&#x20;                       **<!-- Top Surface / Markings -->**

&#x20;                       **<div id="layer-markings" class="h-6 bg-slate-800 rounded opacity-20 transition-all duration-500 flex items-center justify-around">**

&#x20;                           **<div class="w-12 h-1 bg-amber-400 rounded"></div>**

&#x20;                           **<div class="w-12 h-1 bg-amber-400 rounded"></div>**

&#x20;                           **<div class="w-12 h-1 bg-amber-400 rounded"></div>**

&#x20;                       **</div>**

&#x20;                       **<!-- Asphalt Layer -->**

&#x20;                       **<div id="layer-asphalt" class="h-14 bg-slate-700 rounded opacity-20 transition-all duration-500 flex items-center justify-center text-xs text-slate-400 font-mono">**

&#x20;                           **\[ Asfalt Qatlami ]**

&#x20;                       **</div>**

&#x20;                       **<!-- Base Layer -->**

&#x20;                       **<div id="layer-base" class="h-16 bg-amber-900/40 rounded opacity-20 transition-all duration-500 flex items-center justify-center text-xs text-amber-200/60 font-mono">**

&#x20;                           **\[ Shag'al va Zichlangan Qum Poydevor ]**

&#x20;                       **</div>**

&#x20;                       **<!-- Utilities Layer -->**

&#x20;                       **<div id="layer-pipes" class="h-20 bg-slate-800/80 rounded opacity-20 transition-all duration-500 flex items-center justify-around px-8 border-t border-slate-700">**

&#x20;                           **<div class="flex items-center gap-2 text-cyan-400 text-xs">**

&#x20;                               **<i data-lucide="droplet" class="w-4 h-4"></i> Suv Quvuri**

&#x20;                           **</div>**

&#x20;                           **<div class="flex items-center gap-2 text-amber-500 text-xs">**

&#x20;                               **<i data-lucide="flame" class="w-4 h-4"></i> Gaz Tarmog'i**

&#x20;                           **</div>**

&#x20;                           **<div class="flex items-center gap-2 text-yellow-400 text-xs">**

&#x20;                               **<i data-lucide="zap" class="w-4 h-4"></i> Elektr Kabellari**

&#x20;                           **</div>**

&#x20;                       **</div>**

&#x20;                   **</div>**



&#x20;                   **<!-- Info Box -->**

&#x20;                   **<div id="sim-status" class="mt-6 p-4 bg-slate-900 rounded-xl text-xs text-slate-300 border border-slate-800">**

&#x20;                       **<span class="text-amber-400 font-bold">Yo'riqnoma:</span> Yuqoridagi tugmalarni tartib bilan bosing (1-bosqichdan boshlab).**

&#x20;                   **</div>**

&#x20;               **</div>**

&#x20;           **</div>**

&#x20;       **</section>**



&#x20;       **<!-- Registration \& Report Form Section -->**

&#x20;       **<section id="register" class="py-16 bg-slate-950">**

&#x20;           **<div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">**

&#x20;               **<div class="text-center mb-10">**

&#x20;                   **<span class="text-xs font-bold text-amber-500 uppercase tracking-widest">Jamoatchilik Nazorati</span>**

&#x20;                   **<h2 class="text-3xl font-bold text-white mt-1">O'z Qishlog'ingiz yoki Viloyatingizni Ro'yxatdan O'tkazing</h2>**

&#x20;                   **<p class="text-slate-400 mt-2 text-sm">Yo'lingizda quvur o'tkazilishi kerakmi? Yoki yangi asfalt rejalashtirilmoqdami? Ma'lumot qoldiring!</p>**

&#x20;               **</div>**



&#x20;               **<div class="bg-slate-900 p-6 md:p-10 rounded-3xl border border-slate-800 shadow-2xl relative">**

&#x20;                   **<form id="road-request-form" class="space-y-6">**

&#x20;                       **<div class="grid md:grid-cols-2 gap-6">**

&#x20;                           **<div>**

&#x20;                               **<label class="block text-xs font-semibold text-slate-300 mb-2">Ismingiz va Familiyangiz</label>**

&#x20;                               **<input type="text" required placeholder="Masalan: Jasur Rahimov" class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-3 text-white text-sm focus:outline-none focus:border-amber-500 transition-colors">**

&#x20;                           **</div>**

&#x20;                           **<div>**

&#x20;                               **<label class="block text-xs font-semibold text-slate-300 mb-2">Telefon raqamingiz</label>**

&#x20;                               **<input type="tel" required placeholder="+998 90 123 45 67" class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-3 text-white text-sm focus:outline-none focus:border-amber-500 transition-colors">**

&#x20;                           **</div>**

&#x20;                       **</div>**



&#x20;                       **<div class="grid md:grid-cols-2 gap-6">**

&#x20;                           **<div>**

&#x20;                               **<label class="block text-xs font-semibold text-slate-300 mb-2">Viloyatni tanlang</label>**

&#x20;                               **<select required class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-3 text-white text-sm focus:outline-none focus:border-amber-500 transition-colors">**

&#x20;                                   **<option value="">-- Viloyatni tanlang --</option>**

&#x20;                                   **<option value="Toshkent">Toshkent viloyati / shahri</option>**

&#x20;                                   **<option value="Samarqand">Samarqand viloyati</option>**

&#x20;                                   **<option value="Farg'ona">Farg'ona viloyati</option>**

&#x20;                                   **<option value="Andijon">Andijon viloyati</option>**

&#x20;                                   **<option value="Namangan">Namangan viloyati</option>**

&#x20;                                   **<option value="Buxoro">Buxoro viloyati</option>**

&#x20;                                   **<option value="Xorazm">Xorazm viloyati</option>**

&#x20;                                   **<option value="Qashqadaryo">Qashqadaryo viloyati</option>**

&#x20;                                   **<option value="Surxondaryo">Surxondaryo viloyati</option>**

&#x20;                                   **<option value="Navoiy">Navoiy viloyati</option>**

&#x20;                                   **<option value="Jizzax">Jizzax viloyati</option>**

&#x20;                                   **<option value="Sirdaryo">Sirdaryo viloyati</option>**

&#x20;                                   **<option value="Qoraqalpog'iston">Qoraqalpog'iston R.</option>**

&#x20;                               **</select>**

&#x20;                           **</div>**

&#x20;                           **<div>**

&#x20;                               **<label class="block text-xs font-semibold text-slate-300 mb-2">Tuman / Qishloq / MFY nomi</label>**

&#x20;                               **<input type="text" required placeholder="Masalan: Yangiaryk tuman, Bog'ot MFY" class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-3 text-white text-sm focus:outline-none focus:border-amber-500 transition-colors">**

&#x20;                           **</div>**

&#x20;                       **</div>**



&#x20;                       **<div>**

&#x20;                           **<label class="block text-xs font-semibold text-slate-300 mb-2">Joriy Muammo yoki Yo'l Holati</label>**

&#x20;                           **<select required class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-3 text-white text-sm focus:outline-none focus:border-amber-500 transition-colors">**

&#x20;                               **<option value="rejasiz">Asfalt qilindi, lekin quvur o'tkazilmagan (xavf bor)</option>**

&#x20;                               **<option value="vodoprovod">Vodoprovod/Gaz yo'q, yangi yotqizilishi kerak</option>**

&#x20;                               **<option value="ta'mir">Yo'l o'nqir-cho'nqir, ideal ketma-ketlikda ta'mirlash kerak</option>**

&#x20;                               **<option value="boshqa">Boshqa taklif</option>**

&#x20;                           **</select>**

&#x20;                       **</div>**



&#x20;                       **<div>**

&#x20;                           **<label class="block text-xs font-semibold text-slate-300 mb-2">Batafsil Izoh yoki Taklifingiz</label>**

&#x20;                           **<textarea rows="3" placeholder="Ko'changgizdagi yo'l holati bo'yicha taklif bildiring..." class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-3 text-white text-sm focus:outline-none focus:border-amber-500 transition-colors"></textarea>**

&#x20;                       **</div>**



&#x20;                       **<button type="submit" class="w-full py-4 bg-gradient-to-r from-amber-500 to-amber-600 hover:from-amber-400 hover:to-amber-500 text-slate-950 font-bold rounded-xl transition-all shadow-lg shadow-amber-500/20 text-sm flex items-center justify-center gap-2">**

&#x20;                           **<i data-lucide="send" class="w-4 h-4"></i> Ariza va Taklifni Yuborish**

&#x20;                       **</button>**

&#x20;                   **</form>**



&#x20;                   **<!-- Alert message box -->**

&#x20;                   **<div id="form-alert" class="hidden mt-4 p-4 rounded-xl bg-emerald-500/10 border border-emerald-500/30 text-emerald-400 text-xs text-center">**

&#x20;                       **Rahmat! Sizning arizangiz va taklifingiz qabul qilindi. Tez orada mas'ul muhandislar hudud rejasi bo'yicha bog'lanishadi.**

&#x20;                   **</div>**

&#x20;               **</div>**

&#x20;           **</div>**

&#x20;       **</section>**



&#x20;       **<!-- Recommendations Section -->**

&#x20;       **<section id="recommendations" class="py-16 bg-slate-900 border-t border-slate-800">**

&#x20;           **<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">**

&#x20;               **<div class="text-center mb-12">**

&#x20;                   **<h2 class="text-3xl font-bold text-white">Yo'l Sifatini Yaxshilash Bo'yicha Tavsiyalar</h2>**

&#x20;                   **<p class="text-slate-400 mt-2">Muammoni tubdan hal etish uchun tizimli yechimlar</p>**

&#x20;               **</div>**



&#x20;               **<div class="grid md:grid-cols-3 gap-6">**

&#x20;                   **<div class="bg-slate-950 p-6 rounded-2xl border border-slate-800">**

&#x20;                       **<div class="w-10 h-10 bg-amber-500/10 text-amber-400 rounded-lg flex items-center justify-center mb-4">**

&#x20;                           **<i data-lucide="database" class="w-5 h-5"></i>**

&#x20;                       **</div>**

&#x20;                       **<h3 class="text-base font-bold text-white mb-2">Yagona GIS Geoportali</h3>**

&#x20;                       **<p class="text-xs text-slate-400 leading-relaxed">**

&#x20;                           **Barcha yer osti kommunikatsiyalarining raqamli xaritasini yaratish va uni ochiq reyestrga kiritish. Bu bilan noqonuniy yoki rejasiz qazishlarga chek qo'yiladi.**

&#x20;                       **</p>**

&#x20;                   **</div>**



&#x20;                   **<div class="bg-slate-950 p-6 rounded-2xl border border-slate-800">**

&#x20;                       **<div class="w-10 h-10 bg-amber-500/10 text-amber-400 rounded-lg flex items-center justify-center mb-4">**

&#x20;                           **<i data-lucide="shield-check" class="w-5 h-5"></i>**

&#x20;                       **</div>**

&#x20;                       **<h3 class="text-base font-bold text-white mb-2">Kolektor Tizimi (Tunnellar)</h3>**

&#x20;                       **<p class="text-xs text-slate-400 leading-relaxed">**

&#x20;                           **Yangi yo me'moriy loyihalarda barcha quvurlarni maxsus o'tish teshiklariga (tunnel) joylashtirish. Kelajakda ta'birlash uchun yo'l kavlanmaydi.**

&#x20;                       **</p>**

&#x20;                   **</div>**



&#x20;                   **<div class="bg-slate-950 p-6 rounded-2xl border border-slate-800">**

&#x20;                       **<div class="w-10 h-10 bg-amber-500/10 text-amber-400 rounded-lg flex items-center justify-center mb-4">**

&#x20;                           **<i data-lucide="file-badge" class="w-5 h-5"></i>**

&#x20;                       **</div>**

&#x20;                       **<h3 class="text-base font-bold text-white mb-2">Kafolat va Sertifikatlash</h3>**

&#x20;                       **<p class="text-xs text-slate-400 leading-relaxed">**

&#x20;                           **Pudrat tashkilotlariga kamida 5-10 yillik kafolat majburiyatini yuklash. Agar muddatdan oldin yo'l buzilsa, qayta tiklash puddatchi hisobidan bo'ladi.**

&#x20;                       **</p>**

&#x20;                   **</div>**

&#x20;               **</div>**

&#x20;           **</div>**

&#x20;       **</section>**

&#x20;   **</main>**



&#x20;   **<!-- Footer -->**

&#x20;   **<footer class="border-t border-slate-800 bg-slate-950 py-8">**

&#x20;       **<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col md:flex-row justify-between items-center gap-4">**

&#x20;           **<p class="text-xs text-slate-500">© 2026 RoadMaster Pro — Shaffof va Tejamkor Yo'l Qurilishi Tashabbusi.</p>**

&#x20;           **<div class="flex items-center space-x-4 text-xs text-slate-400">**

&#x20;               **<span class="flex items-center gap-1"><i data-lucide="check" class="w-4 h-4 text-emerald-400"></i> Xalqaro Standartlar</span>**

&#x20;               **<span class="flex items-center gap-1"><i data-lucide="check" class="w-4 h-4 text-emerald-400"></i> Kam Xarajat, Yuqori Sifat</span>**

&#x20;           **</div>**

&#x20;       **</div>**

&#x20;   **</footer>**



&#x20;   **<script>**

&#x20;       **// Lucide ikonkalarini faollashtirish**

&#x20;       **if (window.lucide) {**

&#x20;           **lucide.createIcons();**

&#x20;       **}**



&#x20;       **// Simulyator mantiqiy kodi**

&#x20;       **let currentStep = 0;**



&#x20;       **function buildStep(step) {**

&#x20;           **const infoBox = document.getElementById('sim-status');**

&#x20;           **const layerPipes = document.getElementById('layer-pipes');**

&#x20;           **const layerBase = document.getElementById('layer-base');**

&#x20;           **const layerAsphalt = document.getElementById('layer-asphalt');**

&#x20;           **const layerMarkings = document.getElementById('layer-markings');**



&#x20;           **if (!infoBox || !layerPipes || !layerBase || !layerAsphalt || !layerMarkings) return;**



&#x20;           **if (step === 1) {**

&#x20;               **currentStep = 1;**

&#x20;               **infoBox.innerHTML = '<span class="text-emerald-400 font-bold">1-Bosqich Bajarildi:</span> Geodeziya va loyihalash yakunlandi. Raqamli xarita tayyor.';**

&#x20;               **layerPipes.classList.remove('opacity-20');**

&#x20;               **layerPipes.classList.add('opacity-40');**

&#x20;           **} else if (step === 2) {**

&#x20;               **if (currentStep < 1) {**

&#x20;                   **infoBox.innerHTML = '<span class="text-red-400 font-bold">Xatolik:</span> Avval 1-bosqich (Rejalashtirish)ni bajaring!';**

&#x20;                   **return;**

&#x20;               **}**

&#x20;               **currentStep = 2;**

&#x20;               **infoBox.innerHTML = '<span class="text-emerald-400 font-bold">2-Bosqich Bajarildi:</span> Barcha yer osti quvurlari (suv, gaz, elektr) yotqizildi va sinovdan o\\'tkazildi.';**

&#x20;               **layerPipes.classList.remove('opacity-40');**

&#x20;               **layerPipes.classList.add('opacity-100', 'bg-slate-800');**

&#x20;           **} else if (step === 3) {**

&#x20;               **if (currentStep < 2) {**

&#x20;                   **infoBox.innerHTML = '<span class="text-red-400 font-bold">Xatolik:</span> Avval quvur va kommunikatsiyalarni yotqizing!';**

&#x20;                   **return;**

&#x20;               **}**

&#x20;               **currentStep = 3;**

&#x20;               **infoBox.innerHTML = '<span class="text-emerald-400 font-bold">3-Bosqich Bajarildi:</span> Shag\\'al va qum poydevori yotqizildi hamda vibratsiyali zichlashtirildi.';**

&#x20;               **layerBase.classList.remove('opacity-20');**

&#x20;               **layerBase.classList.add('opacity-100', 'bg-amber-900/80');**

&#x20;           **} else if (step === 4) {**

&#x20;               **if (currentStep < 3) {**

&#x20;                   **infoBox.innerHTML = '<span class="text-red-400 font-bold">Xatolik:</span> Poydevorsiz asfalt yotqizib bo\\'lmaydi!';**

&#x20;                   **return;**

&#x20;               **}**

&#x20;               **currentStep = 4;**

&#x20;               **infoBox.innerHTML = '<span class="text-emerald-400 font-bold">Muvaffaqiyatli!</span> Sifatli ko\\'p qatlamli asfalt va yo\\'l chiziqlari yotqizildi. Bu yo\\'l yillar davomida buzilmaydi va qayta kavlanmaydi!';**

&#x20;               **layerAsphalt.classList.remove('opacity-20');**

&#x20;               **layerAsphalt.classList.add('opacity-100', 'bg-slate-950');**

&#x20;               **layerMarkings.classList.remove('opacity-20');**

&#x20;               **layerMarkings.classList.add('opacity-100', 'bg-slate-900');**

&#x20;           **}**

&#x20;       **}**



&#x20;       **function resetSim() {**

&#x20;           **currentStep = 0;**

&#x20;           **const infoBox = document.getElementById('sim-status');**

&#x20;           **if (infoBox) {**

&#x20;               **infoBox.innerHTML = '<span class="text-amber-400 font-bold">Yo\\'riqnoma:</span> Yuqoridagi tugmalarni tartib bilan bosing (1-bosqichdan boshlab).';**

&#x20;           **}**

&#x20;           

&#x20;           **const layers = \['layer-pipes', 'layer-base', 'layer-asphalt', 'layer-markings'];**

&#x20;           **layers.forEach(id => {**

&#x20;               **const el = document.getElementById(id);**

&#x20;               **if (el) {**

&#x20;                   **el.className = el.className.replace(/opacity-100|opacity-40/g, 'opacity-20');**

&#x20;               **}**

&#x20;           **});**

&#x20;       **}**



&#x20;       **// Calculator Logic**

&#x20;       **function updateCalculator() {**

&#x20;           **const km = parseFloat(document.getElementById('calc-km').value) || 0;**

&#x20;           **const digs = parseFloat(document.getElementById('calc-digs').value) || 0;**

&#x20;           **const savedAmount = (km \* 20000000) + (digs \* 15000000);**

&#x20;           **const formatted = new Intl.NumberFormat('uz-UZ').format(savedAmount) + ' UZS';**

&#x20;           **document.getElementById('calc-result').innerText = formatted;**

&#x20;       **}**



&#x20;       **// Event listener'larni xavfsiz biriktirish**

&#x20;       **document.addEventListener('DOMContentLoaded', () => {**

&#x20;           **const btn1 = document.getElementById('btn-step-1');**

&#x20;           **const btn2 = document.getElementById('btn-step-2');**

&#x20;           **const btn3 = document.getElementById('btn-step-3');**

&#x20;           **const btn4 = document.getElementById('btn-step-4');**

&#x20;           **const btnReset = document.getElementById('btn-reset');**



&#x20;           **if (btn1) btn1.addEventListener('click', () => buildStep(1));**

&#x20;           **if (btn2) btn2.addEventListener('click', () => buildStep(2));**

&#x20;           **if (btn3) btn3.addEventListener('click', () => buildStep(3));**

&#x20;           **if (btn4) btn4.addEventListener('click', () => buildStep(4));**

&#x20;           **if (btnReset) btnReset.addEventListener('click', resetSim);**



&#x20;           **// Calculator events**

&#x20;           **const inputKm = document.getElementById('calc-km');**

&#x20;           **const inputDigs = document.getElementById('calc-digs');**

&#x20;           **if (inputKm) inputKm.addEventListener('input', updateCalculator);**

&#x20;           **if (inputDigs) inputDigs.addEventListener('input', updateCalculator);**



&#x20;           **// Form Submit Event**

&#x20;           **const form = document.getElementById('road-request-form');**

&#x20;           **const alertBox = document.getElementById('form-alert');**

&#x20;           **if (form) {**

&#x20;               **form.addEventListener('submit', (e) => {**

&#x20;                   **e.preventDefault();**

&#x20;                   **if (alertBox) {**

&#x20;                       **alertBox.classList.remove('hidden');**

&#x20;                       **form.reset();**

&#x20;                       **setTimeout(() => {**

&#x20;                           **alertBox.classList.add('hidden');**

&#x20;                       **}, 6000);**

&#x20;                   **}**

&#x20;               **});**

&#x20;           **}**

&#x20;       **});**

&#x20;   **</script>**

**</body>**

**</html><!DOCTYPE html>**

**<html lang="uz">**

**<head>**

&#x20;   **<meta charset="UTF-8">**

&#x20;   **<meta name="viewport" content="width=device-width, initial-scale=1.0">**

&#x20;   **<title>Ideal Yo'l Qurilishi va Infratuzilma Standartlari</title>**

&#x20;   **<!-- Tailwind CSS CDN -->**

&#x20;   **<script src="https://cdn.tailwindcss.com"></script>**

&#x20;   **<!-- Lucide Icons -->**

&#x20;   **<script src="https://unpkg.com/lucide@latest"></script>**

&#x20;   **<style>**

&#x20;       **@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800\&display=swap');**

&#x20;       **body {**

&#x20;           **font-family: 'Inter', sans-serif;**

&#x20;           **scroll-behavior: smooth;**

&#x20;       **}**

&#x20;       **.road-layer {**

&#x20;           **transition: all 0.3s ease;**

&#x20;       **}**

&#x20;       **.road-layer:hover {**

&#x20;           **transform: scale(1.02);**

&#x20;       **}**

&#x20;   **</style>**

**</head>**

**<body class="bg-slate-900 text-slate-100 min-h-screen flex flex-col justify-between selection:bg-amber-500 selection:text-slate-900">**



&#x20;   **<!-- Header Section -->**

&#x20;   **<header class="border-b border-slate-800 bg-slate-950/80 backdrop-blur-md sticky top-0 z-50">**

&#x20;       **<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">**

&#x20;           **<div class="flex items-center space-x-3">**

&#x20;               **<div class="p-2.5 bg-amber-500/10 border border-amber-500/30 rounded-xl text-amber-500">**

&#x20;                   **<i data-lucide="construction" class="w-7 h-7"></i>**

&#x20;               **</div>**

&#x20;               **<div>**

&#x20;                   **<h1 class="font-bold text-xl text-white tracking-wide">RoadMaster Pro</h1>**

&#x20;                   **<p class="text-xs text-slate-400">Yo'l qurilishi va infratuzilma standarti</p>**

&#x20;               **</div>**

&#x20;           **</div>**

&#x20;           **<nav class="hidden md:flex space-x-8 text-sm font-medium text-slate-300">**

&#x20;               **<a href="#comparison" class="hover:text-amber-400 transition-colors">Taqqoslash</a>**

&#x20;               **<a href="#ideal-steps" class="hover:text-amber-400 transition-colors">Ideal Bosqichlar</a>**

&#x20;               **<a href="#economy" class="hover:text-amber-400 transition-colors">Tejamkorlik</a>**

&#x20;               **<a href="#simulator" class="hover:text-amber-400 transition-colors">Simulyatsiya</a>**

&#x20;               **<a href="#register" class="hover:text-amber-400 transition-colors">Ariza Yuborish</a>**

&#x20;           **</nav>**

&#x20;           **<a href="#register" class="px-5 py-2.5 bg-amber-500 hover:bg-amber-400 text-slate-950 font-semibold rounded-xl transition-all shadow-lg shadow-amber-500/20 text-sm">**

&#x20;               **Taklif Yuborish**

&#x20;           **</a>**

&#x20;       **</div>**

&#x20;   **</header>**



&#x20;   **<main class="flex-grow">**

&#x20;       **<!-- Hero Section -->**

&#x20;       **<section class="relative py-24 overflow-hidden bg-gradient-to-b from-slate-950 via-slate-900 to-slate-900">**

&#x20;           **<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center relative z-10">**

&#x20;               **<span class="inline-flex items-center gap-2 px-3 py-1.5 rounded-full text-xs font-semibold bg-amber-500/10 border border-amber-500/20 text-amber-400 mb-6">**

&#x20;                   **<i data-lucide="piggy-bank" class="w-4 h-4"></i> Budjetni Tejovchi Innovatsion Yondashuv**

&#x20;               **</span>**

&#x20;               **<h1 class="text-4xl md:text-6xl font-extrabold text-white tracking-tight leading-tight max-w-4xl mx-auto">**

&#x20;                   **Arzon, Sifatli va <span class="text-transparent bg-clip-text bg-gradient-to-r from-amber-400 to-emerald-400">Ideal Yo'llar</span> Infratuzilmasi**

&#x20;               **</h1>**

&#x20;               **<p class="mt-6 text-lg text-slate-400 max-w-2xl mx-auto">**

&#x20;                   **Qayta qazish va takroriy xarajatlarga chek qo'yamiz. Har bir viloyat hamda qishloq uchun to'g'ri rejalashtirish orqali davlat va jamoatchilik mablag'larini 40% gacha tejang!**

&#x20;               **</p>**

&#x20;               **<div class="mt-10 flex flex-wrap justify-center gap-4">**

&#x20;                   **<a href="#register" class="px-7 py-3.5 bg-amber-500 hover:bg-amber-400 text-slate-950 font-bold rounded-xl transition-all shadow-lg shadow-amber-500/20 flex items-center gap-2">**

&#x20;                       **<i data-lucide="map-pin" class="w-5 h-5"></i> O'z Qishlog'ingizni Ro'yxatdan O'tkazing**

&#x20;                   **</a>**

&#x20;                   **<a href="#economy" class="px-7 py-3.5 bg-slate-800 hover:bg-slate-700 text-slate-200 font-semibold rounded-xl border border-slate-700 transition-all flex items-center gap-2">**

&#x20;                       **<i data-lucide="trending-down" class="w-5 h-5"></i> Tejamkorlik Kalkulyatori**

&#x20;                   **</a>**

&#x20;               **</div>**

&#x20;           **</div>**

&#x20;       **</section>**



&#x20;       **<!-- Visual Gallery / Image Section -->**

&#x20;       **<section class="py-12 bg-slate-950 border-b border-slate-800/80">**

&#x20;           **<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">**

&#x20;               **<div class="grid md:grid-cols-3 gap-6">**

&#x20;                   **<div class="relative group overflow-hidden rounded-2xl border border-slate-800 h-64">**

&#x20;                       **<img src="https://images.unsplash.com/photo-1541888946425-d0fbb186a5b2?auto=format\&fit=crop\&w=800\&q=80" alt="Yer osti muhandislik ishlari" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" onerror="this.src='https://placehold.co/800x500/1e293b/94a3b8?text=Muhandislik+Ishlari'">**

&#x20;                       **<div class="absolute inset-0 bg-gradient-to-t from-slate-950 via-slate-950/40 to-transparent p-6 flex flex-col justify-end">**

&#x20;                           **<span class="text-xs text-amber-400 font-semibold">1-Bosqich</span>**

&#x20;                           **<h3 class="text-lg font-bold text-white">Yer Osti Kommunikatsiyasi</h3>**

&#x20;                       **</div>**

&#x20;                   **</div>**

&#x20;                   **<div class="relative group overflow-hidden rounded-2xl border border-slate-800 h-64">**

&#x20;                       **<img src="https://images.unsplash.com/photo-1578575437130-527eed3abbec?auto=format\&fit=crop\&w=800\&q=80" alt="Yo'l zichlash va qurish" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" onerror="this.src='https://placehold.co/800x500/1e293b/94a3b8?text=Zichlash+va+Poydevor'">**

&#x20;                       **<div class="absolute inset-0 bg-gradient-to-t from-slate-950 via-slate-950/40 to-transparent p-6 flex flex-col justify-end">**

&#x20;                           **<span class="text-xs text-amber-400 font-semibold">2-Bosqich</span>**

&#x20;                           **<h3 class="text-lg font-bold text-white">Mustahkam Shag'al Poydevor</h3>**

&#x20;                       **</div>**

&#x20;                   **</div>**

&#x20;                   **<div class="relative group overflow-hidden rounded-2xl border border-slate-800 h-64">**

&#x20;                       **<img src="https://images.unsplash.com/photo-1621905251189-08b45d6a269e?auto=format\&fit=crop\&w=800\&q=80" alt="Ideal Asfalt va belgilash" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" onerror="this.src='https://placehold.co/800x500/1e293b/94a3b8?text=Ideal+Yo\\'l'">**

&#x20;                       **<div class="absolute inset-0 bg-gradient-to-t from-slate-950 via-slate-950/40 to-transparent p-6 flex flex-col justify-end">**

&#x20;                           **<span class="text-xs text-emerald-400 font-semibold">Yakuniy Natija</span>**

&#x20;                           **<h3 class="text-lg font-bold text-white">Uzoq Yillik Sifatli Yo'l</h3>**

&#x20;                       **</div>**

&#x20;                   **</div>**

&#x20;               **</div>**

&#x20;           **</div>**

&#x20;       **</section>**



&#x20;       **<!-- Cost Reduction \& Economy Section -->**

&#x20;       **<section id="economy" class="py-16 bg-slate-900 border-t border-slate-800">**

&#x20;           **<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">**

&#x20;               **<div class="text-center mb-12">**

&#x20;                   **<h2 class="text-3xl font-bold text-white">Kam Xarajat evaziga Maksimal Sifat</h2>**

&#x20;                   **<p class="text-slate-400 mt-2">Mablag'larni to'g'ri yo'naltirish va budjetni tejash mexanizmlari</p>**

&#x20;               **</div>**



&#x20;               **<div class="grid md:grid-cols-3 gap-8 mb-12">**

&#x20;                   **<div class="bg-slate-950 p-6 rounded-2xl border border-slate-800 hover:border-emerald-500/40 transition-all">**

&#x20;                       **<div class="w-12 h-12 bg-emerald-500/10 rounded-xl flex items-center justify-center text-emerald-400 mb-4">**

&#x20;                           **<i data-lucide="dollar-sign" class="w-6 h-6"></i>**

&#x20;                       **</div>**

&#x20;                       **<h3 class="text-lg font-bold text-white">40% Xarajat Tejalishi</h3>**

&#x20;                       **<p class="text-xs text-slate-400 mt-2">Asfaltni qayta-qayta buzib qazish va yamoqlash ishlariga ketadigan ortiqcha budjet batamom qisqaradi.</p>**

&#x20;                   **</div>**



&#x20;                   **<div class="bg-slate-950 p-6 rounded-2xl border border-slate-800 hover:border-emerald-500/40 transition-all">**

&#x20;                       **<div class="w-12 h-12 bg-emerald-500/10 rounded-xl flex items-center justify-center text-emerald-400 mb-4">**

&#x20;                           **<i data-lucide="clock" class="w-6 h-6"></i>**

&#x20;                       **</div>**

&#x20;                       **<h3 class="text-lg font-bold text-white">Vaqt Tejamkorligi</h3>**

&#x20;                       **<p class="text-xs text-slate-400 mt-2">Kommunikatsiya tashkilotlari bir vaqtning o'zida ishlagani sababli loyiha muddati 2 barobar tezlashadi.</p>**

&#x20;                   **</div>**



&#x20;                   **<div class="bg-slate-950 p-6 rounded-2xl border border-slate-800 hover:border-emerald-500/40 transition-all">**

&#x20;                       **<div class="w-12 h-12 bg-emerald-500/10 rounded-xl flex items-center justify-center text-emerald-400 mb-4">**

&#x20;                           **<i data-lucide="shield-check" class="w-6 h-6"></i>**

&#x20;                       **</div>**

&#x20;                       **<h3 class="text-lg font-bold text-white">15+ Yil Kafolat</h3>**

&#x20;                       **<p class="text-xs text-slate-400 mt-2">Poydevor ostida suv quvurlari oqmasligi va mustahkam bosim tufayli yo'l uzoq yillar o'tirmaydi va yorilmaydi.</p>**

&#x20;                   **</div>**

&#x20;               **</div>**



&#x20;               **<!-- Calculator Box -->**

&#x20;               **<div class="bg-slate-950 p-6 md:p-8 rounded-3xl border border-slate-800 max-w-3xl mx-auto">**

&#x20;                   **<h3 class="text-xl font-bold text-white text-center mb-6 flex items-center justify-center gap-2">**

&#x20;                       **<i data-lucide="calculator" class="w-5 h-5 text-amber-500"></i> Hududiy Tejamkorlik Hisoblagichi**

&#x20;                   **</h3>**

&#x20;                   **<div class="grid sm:grid-cols-2 gap-4 mb-6">**

&#x20;                       **<div>**

&#x20;                           **<label class="block text-xs font-semibold text-slate-400 mb-2">Yo'l uzunligi (km):</label>**

&#x20;                           **<input type="number" id="calc-km" value="5" min="1" class="w-full bg-slate-900 border border-slate-800 rounded-xl px-4 py-2.5 text-white text-sm focus:outline-none focus:border-amber-500">**

&#x20;                       **</div>**

&#x20;                       **<div>**

&#x20;                           **<label class="block text-xs font-semibold text-slate-400 mb-2">Amaldagi rejasiz qazishlar soni:</label>**

&#x20;                           **<input type="number" id="calc-digs" value="3" min="0" class="w-full bg-slate-900 border border-slate-800 rounded-xl px-4 py-2.5 text-white text-sm focus:outline-none focus:border-amber-500">**

&#x20;                       **</div>**

&#x20;                   **</div>**

&#x20;                   **<div class="bg-slate-900 p-4 rounded-2xl border border-slate-800 text-center">**

&#x20;                       **<p class="text-xs text-slate-400">Rejalashtirish orqali tejab qolinadigan taxminiy mablag':</p>**

&#x20;                       **<p id="calc-result" class="text-2xl font-extrabold text-emerald-400 mt-1">150,000,000 UZS</p>**

&#x20;                   **</div>**

&#x20;               **</div>**

&#x20;           **</div>**

&#x20;       **</section>**



&#x20;       **<!-- Comparison Section -->**

&#x20;       **<section id="comparison" class="py-16 bg-slate-900 border-t border-slate-800">**

&#x20;           **<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">**

&#x20;               **<div class="text-center mb-12">**

&#x20;                   **<h2 class="text-3xl font-bold text-white">Ikki xil yondashuv: Taqqoslang</h2>**

&#x20;                   **<p class="text-slate-400 mt-2">Amaliyotdagi xatolar va biz taklif qilayotgan tizimli ideal model</p>**

&#x20;               **</div>**



&#x20;               **<div class="grid md:grid-cols-2 gap-8">**

&#x20;                   **<!-- Bad Practice -->**

&#x20;                   **<div class="bg-red-950/20 border border-red-900/40 rounded-2xl p-6 relative overflow-hidden">**

&#x20;                       **<div class="absolute -right-6 -top-6 w-24 h-24 bg-red-500/10 rounded-full blur-xl"></div>**

&#x20;                       **<div class="flex items-center justify-between mb-6">**

&#x20;                           **<span class="flex items-center gap-2 text-red-400 font-bold text-lg">**

&#x20;                               **<i data-lucide="x-circle" class="w-6 h-6"></i> Noto'g'ri Ketma-ketlik (Xato)**

&#x20;                           **</span>**

&#x20;                           **<span class="text-xs bg-red-500/20 text-red-300 px-3 py-1 rounded-full border border-red-500/30">Zararli usul</span>**

&#x20;                       **</div>**

&#x20;                       **<ul class="space-y-4">**

&#x20;                           **<li class="flex items-start gap-3 bg-slate-900/60 p-3.5 rounded-xl border border-red-900/30">**

&#x20;                               **<span class="w-6 h-6 rounded-full bg-red-500/20 text-red-400 flex items-center justify-center font-bold text-xs shrink-0 mt-0.5">1</span>**

&#x20;                               **<div>**

&#x20;                                   **<h4 class="font-semibold text-slate-200 text-sm">Shoshilinch Asfaltlash</h4>**

&#x20;                                   **<p class="text-xs text-slate-400 mt-1">Yer osti tarmoqlari holati tekshirilmasdan asfalt yotqiziladi.</p>**

&#x20;                               **</div>**

&#x20;                           **</li>**

&#x20;                           **<li class="flex items-start gap-3 bg-slate-900/60 p-3.5 rounded-xl border border-red-900/30">**

&#x20;                               **<span class="w-6 h-6 rounded-full bg-red-500/20 text-red-400 flex items-center justify-center font-bold text-xs shrink-0 mt-0.5">2</span>**

&#x20;                               **<div>**

&#x20;                                   **<h4 class="font-semibold text-slate-200 text-sm">Suv/Gaz quvurining yorilishi va qazish</h4>**

&#x20;                                   **<p class="text-xs text-slate-400 mt-1">Yangi yotqizilgan asfalt qayta kavlab tashlanadi va suv o'tkaziladi.</p>**

&#x20;                               **</div>**

&#x20;                           **</li>**

&#x20;                           **<li class="flex items-start gap-3 bg-slate-900/60 p-3.5 rounded-xl border border-red-900/30">**

&#x20;                               **<span class="w-6 h-6 rounded-full bg-red-500/20 text-red-400 flex items-center justify-center font-bold text-xs shrink-0 mt-0.5">3</span>**

&#x20;                               **<div>**

&#x20;                                   **<h4 class="font-semibold text-slate-200 text-sm">Siyqa (Yamoq) Asfalt Yamoqlash</h4>**

&#x20;                                   **<p class="text-xs text-slate-400 mt-1">Qazilgan joy o'nqir-cho'nqir qilib yopiladi va yo'l o'tirib qoladi.</p>**

&#x20;                               **</div>**

&#x20;                           **</li>**

&#x20;                       **</ul>**

&#x20;                       **<div class="mt-6 p-4 bg-red-900/20 rounded-xl text-red-300 text-xs flex items-center gap-3 border border-red-800/30">**

&#x20;                           **<i data-lucide="alert-circle" class="w-5 h-5 shrink-0"></i>**

&#x20;                           **Oqibat: Budjet isrof bo'ladi, haydovchilar noqulaylik sezadi, yo'l umri 3-5 barobarga qisqaradi.**

&#x20;                       **</div>**

&#x20;                   **</div>**



&#x20;                   **<!-- Good Practice -->**

&#x20;                   **<div class="bg-emerald-950/20 border border-emerald-900/40 rounded-2xl p-6 relative overflow-hidden">**

&#x20;                       **<div class="absolute -right-6 -top-6 w-24 h-24 bg-emerald-500/10 rounded-full blur-xl"></div>**

&#x20;                       **<div class="flex items-center justify-between mb-6">**

&#x20;                           **<span class="flex items-center gap-2 text-emerald-400 font-bold text-lg">**

&#x20;                               **<i data-lucide="check-circle" class="w-6 h-6"></i> Ideal Ketma-ketlik (To'g'ri)**

&#x20;                           **</span>**

&#x20;                           **<span class="text-xs bg-emerald-500/20 text-emerald-300 px-3 py-1 rounded-full border border-emerald-500/30">Standart usul</span>**

&#x20;                       **</div>**

&#x20;                       **<ul class="space-y-4">**

&#x20;                           **<li class="flex items-start gap-3 bg-slate-900/60 p-3.5 rounded-xl border border-emerald-900/30">**

&#x20;                               **<span class="w-6 h-6 rounded-full bg-emerald-500/20 text-emerald-400 flex items-center justify-center font-bold text-xs shrink-0 mt-0.5">1</span>**

&#x20;                               **<div>**

&#x20;                                   **<h4 class="font-semibold text-slate-200 text-sm">Integrallashgan Rejalashtirish</h4>**

&#x20;                                   **<p class="text-xs text-slate-400 mt-1">Hamma tashkilotlar (Suv, Gaz, Elektr, Aloqa) yagona xarita asosida kelishadi.</p>**

&#x20;                               **</div>**

&#x20;                           **</li>**

&#x20;                           **<li class="flex items-start gap-3 bg-slate-900/60 p-3.5 rounded-xl border border-emerald-900/30">**

&#x20;                               **<span class="w-6 h-6 rounded-full bg-emerald-500/20 text-emerald-400 flex items-center justify-center font-bold text-xs shrink-0 mt-0.5">2</span>**

&#x20;                               **<div>**

&#x20;                                   **<h4 class="font-semibold text-slate-200 text-sm">Barcha Yer Osti Tarmoqlarini Yotqizish</h4>**

&#x20;                                   **<p class="text-xs text-slate-400 mt-1">Trubalar, kabellar, drenaj tizimlari va maxsus tunnel (kolektor)lar tayyorlanadi.</p>**

&#x20;                               **</div>**

&#x20;                           **</li>**

&#x20;                           **<li class="flex items-start gap-3 bg-slate-900/60 p-3.5 rounded-xl border border-emerald-900/30">**

&#x20;                               **<span class="w-6 h-6 rounded-full bg-emerald-500/20 text-emerald-400 flex items-center justify-center font-bold text-xs shrink-0 mt-0.5">3</span>**

&#x20;                               **<div>**

&#x20;                                   **<h4 class="font-semibold text-slate-200 text-sm">Mustahkam Poydevor \& Sifatli Asfalt</h4>**

&#x20;                                   **<p class="text-xs text-slate-400 mt-1">Zichlashtirish va ko'p qatlamli asfalt yotqizish runsiz amalga oshiriladi.</p>**

&#x20;                               **</div>**

&#x20;                           **</li>**

&#x20;                       **</ul>**

&#x20;                       **<div class="mt-6 p-4 bg-emerald-900/20 rounded-xl text-emerald-300 text-xs flex items-center gap-3 border border-emerald-800/30">**

&#x20;                           **<i data-lucide="sparkles" class="w-5 h-5 shrink-0"></i>**

&#x20;                           **Natija: Yo'l 15-20 yil mobaynida qazilmasdan sifatli xizmat qiladi va budjet tejaladi.**

&#x20;                       **</div>**

&#x20;                   **</div>**

&#x20;               **</div>**

&#x20;           **</div>**

&#x20;       **</section>**



&#x20;       **<!-- Ideal Steps Section -->**

&#x20;       **<section id="ideal-steps" class="py-16 bg-slate-950">**

&#x20;           **<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">**

&#x20;               **<div class="text-center mb-16">**

&#x20;                   **<h2 class="text-3xl font-bold text-white">Ideal Yo'l Qurilishining 5 Bosqichi</h2>**

&#x20;                   **<p class="text-slate-400 mt-2">Haqiqiy sifat va mustahkamlikni ta'minlovchi xalqaro standart ketma-ketligi</p>**

&#x20;               **</div>**



&#x20;               **<div class="grid sm:grid-cols-2 lg:grid-cols-5 gap-6">**

&#x20;                   **<!-- Step 1 -->**

&#x20;                   **<div class="bg-slate-900 p-6 rounded-2xl border border-slate-800 hover:border-amber-500/50 transition-all group relative">**

&#x20;                       **<div class="w-12 h-12 bg-amber-500/10 rounded-xl flex items-center justify-center text-amber-500 mb-4 group-hover:bg-amber-500 group-hover:text-slate-950 transition-all">**

&#x20;                           **<i data-lucide="map" class="w-6 h-6"></i>**

&#x20;                       **</div>**

&#x20;                       **<span class="text-xs font-semibold text-amber-500 tracking-wider">01-BOSQICH</span>**

&#x20;                       **<h3 class="text-lg font-bold text-white mt-1">Loyiha \& GIS</h3>**

&#x20;                       **<p class="text-xs text-slate-400 mt-2">Geodeziya va yer osti xaritalarini raqamlashtirish. Barcha tashkilotlar kelishuvi.</p>**

&#x20;                   **</div>**



&#x20;                   **<!-- Step 2 -->**

&#x20;                   **<div class="bg-slate-900 p-6 rounded-2xl border border-slate-800 hover:border-amber-500/50 transition-all group relative">**

&#x20;                       **<div class="w-12 h-12 bg-amber-500/10 rounded-xl flex items-center justify-center text-amber-500 mb-4 group-hover:bg-amber-500 group-hover:text-slate-950 transition-all">**

&#x20;                           **<i data-lucide="pipette" class="w-6 h-6"></i>**

&#x20;                       **</div>**

&#x20;                       **<span class="text-xs font-semibold text-amber-500 tracking-wider">02-BOSQICH</span>**

&#x20;                       **<h3 class="text-lg font-bold text-white mt-1">Kommunikatsiya</h3>**

&#x20;                       **<p class="text-xs text-slate-400 mt-2">Suv, gaz, elektr, optik tolali aloqa quvurlari va drenaj tizimlarini o'tkazish.</p>**

&#x20;                   **</div>**



&#x20;                   **<!-- Step 3 -->**

&#x20;                   **<div class="bg-slate-900 p-6 rounded-2xl border border-slate-800 hover:border-amber-500/50 transition-all group relative">**

&#x20;                       **<div class="w-12 h-12 bg-amber-500/10 rounded-xl flex items-center justify-center text-amber-500 mb-4 group-hover:bg-amber-500 group-hover:text-slate-950 transition-all">**

&#x20;                           **<i data-lucide="layers" class="w-6 h-6"></i>**

&#x20;                       **</div>**

&#x20;                       **<span class="text-xs font-semibold text-amber-500 tracking-wider">03-BOSQICH</span>**

&#x20;                       **<h3 class="text-lg font-bold text-white mt-1">Poydevor / Zichlash</h3>**

&#x20;                       **<p class="text-xs text-slate-400 mt-2">Qum-shag'al aralashmasini yotqizish, geotukima va bir necha bosqichli zichlashtirish.</p>**

&#x20;                   **</div>**



&#x20;                   **<!-- Step 4 -->**

&#x20;                   **<div class="bg-slate-900 p-6 rounded-2xl border border-slate-800 hover:border-amber-500/50 transition-all group relative">**

&#x20;                       **<div class="w-12 h-12 bg-amber-500/10 rounded-xl flex items-center justify-center text-amber-500 mb-4 group-hover:bg-amber-500 group-hover:text-slate-950 transition-all">**

&#x20;                           **<i data-lucide="disc" class="w-6 h-6"></i>**

&#x20;                       **</div>**

&#x20;                       **<span class="text-xs font-semibold text-amber-500 tracking-wider">04-BOSQICH</span>**

&#x20;                       **<h3 class="text-lg font-bold text-white mt-1">Asfalt Yotqizish</h3>**

&#x20;                       **<p class="text-xs text-slate-400 mt-2">Yirik va mayda donador sifatli asfalt qatlamlarini issiqlik texnologiyasi bilan yotqizish.</p>**

&#x20;                   **</div>**



&#x20;                   **<!-- Step 5 -->**

&#x20;                   **<div class="bg-slate-900 p-6 rounded-2xl border border-slate-800 hover:border-amber-500/50 transition-all group relative">**

&#x20;                       **<div class="w-12 h-12 bg-amber-500/10 rounded-xl flex items-center justify-center text-amber-500 mb-4 group-hover:bg-amber-500 group-hover:text-slate-950 transition-all">**

&#x20;                           **<i data-lucide="check-check" class="w-6 h-6"></i>**

&#x20;                       **</div>**

&#x20;                       **<span class="text-xs font-semibold text-amber-500 tracking-wider">05-BOSQICH</span>**

&#x20;                       **<h3 class="text-lg font-bold text-white mt-1">Chiziqlar \& Belgilar</h3>**

&#x20;                       **<p class="text-xs text-slate-400 mt-2">Termoplastik chiziqlar, svetoforlar va piyodalar infratuzilmasini sozlash.</p>**

&#x20;                   **</div>**

&#x20;               **</div>**

&#x20;           **</div>**

&#x20;       **</section>**



&#x20;       **<!-- Interactive Simulator Section -->**

&#x20;       **<section id="simulator" class="py-16 bg-slate-900 border-t border-slate-800">**

&#x20;           **<div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8">**

&#x20;               **<div class="text-center mb-10">**

&#x20;                   **<h2 class="text-3xl font-bold text-white">Yo'l Qurilishi Simulyatori</h2>**

&#x20;                   **<p class="text-slate-400 mt-2">Bosqichlarni ketma-ket bosing va ideal yo'l qatlamlarini barpo eting</p>**

&#x20;               **</div>**



&#x20;               **<div class="bg-slate-950 p-6 md:p-8 rounded-3xl border border-slate-800 shadow-2xl">**

&#x20;                   **<!-- Buttons Control -->**

&#x20;                   **<div class="flex flex-wrap gap-3 justify-center mb-8" id="sim-controls">**

&#x20;                       **<button id="btn-step-1" class="sim-btn px-4 py-2.5 bg-slate-800 hover:bg-slate-700 text-slate-200 text-xs font-semibold rounded-xl border border-slate-700 flex items-center gap-2 transition-all">**

&#x20;                           **<span class="w-5 h-5 rounded-full bg-slate-700 flex items-center justify-center text-white">1</span> Rejalashtirish**

&#x20;                       **</button>**

&#x20;                       **<button id="btn-step-2" class="sim-btn px-4 py-2.5 bg-slate-800 hover:bg-slate-700 text-slate-200 text-xs font-semibold rounded-xl border border-slate-700 flex items-center gap-2 transition-all">**

&#x20;                           **<span class="w-5 h-5 rounded-full bg-slate-700 flex items-center justify-center text-white">2</span> Truba \& Quvurlar**

&#x20;                       **</button>**

&#x20;                       **<button id="btn-step-3" class="sim-btn px-4 py-2.5 bg-slate-800 hover:bg-slate-700 text-slate-200 text-xs font-semibold rounded-xl border border-slate-700 flex items-center gap-2 transition-all">**

&#x20;                           **<span class="w-5 h-5 rounded-full bg-slate-700 flex items-center justify-center text-white">3</span> Shag'al Poydevor**

&#x20;                       **</button>**

&#x20;                       **<button id="btn-step-4" class="sim-btn px-4 py-2.5 bg-slate-800 hover:bg-slate-700 text-slate-200 text-xs font-semibold rounded-xl border border-slate-700 flex items-center gap-2 transition-all">**

&#x20;                           **<span class="w-5 h-5 rounded-full bg-slate-700 flex items-center justify-center text-white">4</span> Asfalt Qatlam**

&#x20;                       **</button>**

&#x20;                       **<button id="btn-reset" class="px-4 py-2.5 bg-red-500/10 hover:bg-red-500/20 text-red-400 text-xs font-semibold rounded-xl border border-red-500/20 flex items-center gap-2 transition-all">**

&#x20;                           **<i data-lucide="rotate-ccw" class="w-4 h-4"></i> Qayta boshlash**

&#x20;                       **</button>**

&#x20;                   **</div>**



&#x20;                   **<!-- Visual Representation -->**

&#x20;                   **<div class="relative w-full h-64 bg-slate-900 rounded-2xl border border-slate-800 overflow-hidden flex flex-col justify-end p-4 gap-1" id="road-canvas">**

&#x20;                       **<!-- Top Surface / Markings -->**

&#x20;                       **<div id="layer-markings" class="h-6 bg-slate-800 rounded opacity-20 transition-all duration-500 flex items-center justify-around">**

&#x20;                           **<div class="w-12 h-1 bg-amber-400 rounded"></div>**

&#x20;                           **<div class="w-12 h-1 bg-amber-400 rounded"></div>**

&#x20;                           **<div class="w-12 h-1 bg-amber-400 rounded"></div>**

&#x20;                       **</div>**

&#x20;                       **<!-- Asphalt Layer -->**

&#x20;                       **<div id="layer-asphalt" class="h-14 bg-slate-700 rounded opacity-20 transition-all duration-500 flex items-center justify-center text-xs text-slate-400 font-mono">**

&#x20;                           **\[ Asfalt Qatlami ]**

&#x20;                       **</div>**

&#x20;                       **<!-- Base Layer -->**

&#x20;                       **<div id="layer-base" class="h-16 bg-amber-900/40 rounded opacity-20 transition-all duration-500 flex items-center justify-center text-xs text-amber-200/60 font-mono">**

&#x20;                           **\[ Shag'al va Zichlangan Qum Poydevor ]**

&#x20;                       **</div>**

&#x20;                       **<!-- Utilities Layer -->**

&#x20;                       **<div id="layer-pipes" class="h-20 bg-slate-800/80 rounded opacity-20 transition-all duration-500 flex items-center justify-around px-8 border-t border-slate-700">**

&#x20;                           **<div class="flex items-center gap-2 text-cyan-400 text-xs">**

&#x20;                               **<i data-lucide="droplet" class="w-4 h-4"></i> Suv Quvuri**

&#x20;                           **</div>**

&#x20;                           **<div class="flex items-center gap-2 text-amber-500 text-xs">**

&#x20;                               **<i data-lucide="flame" class="w-4 h-4"></i> Gaz Tarmog'i**

&#x20;                           **</div>**

&#x20;                           **<div class="flex items-center gap-2 text-yellow-400 text-xs">**

&#x20;                               **<i data-lucide="zap" class="w-4 h-4"></i> Elektr Kabellari**

&#x20;                           **</div>**

&#x20;                       **</div>**

&#x20;                   **</div>**



&#x20;                   **<!-- Info Box -->**

&#x20;                   **<div id="sim-status" class="mt-6 p-4 bg-slate-900 rounded-xl text-xs text-slate-300 border border-slate-800">**

&#x20;                       **<span class="text-amber-400 font-bold">Yo'riqnoma:</span> Yuqoridagi tugmalarni tartib bilan bosing (1-bosqichdan boshlab).**

&#x20;                   **</div>**

&#x20;               **</div>**

&#x20;           **</div>**

&#x20;       **</section>**



&#x20;       **<!-- Registration \& Report Form Section -->**

&#x20;       **<section id="register" class="py-16 bg-slate-950">**

&#x20;           **<div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">**

&#x20;               **<div class="text-center mb-10">**

&#x20;                   **<span class="text-xs font-bold text-amber-500 uppercase tracking-widest">Jamoatchilik Nazorati</span>**

&#x20;                   **<h2 class="text-3xl font-bold text-white mt-1">O'z Qishlog'ingiz yoki Viloyatingizni Ro'yxatdan O'tkazing</h2>**

&#x20;                   **<p class="text-slate-400 mt-2 text-sm">Yo'lingizda quvur o'tkazilishi kerakmi? Yoki yangi asfalt rejalashtirilmoqdami? Ma'lumot qoldiring!</p>**

&#x20;               **</div>**



&#x20;               **<div class="bg-slate-900 p-6 md:p-10 rounded-3xl border border-slate-800 shadow-2xl relative">**

&#x20;                   **<form id="road-request-form" class="space-y-6">**

&#x20;                       **<div class="grid md:grid-cols-2 gap-6">**

&#x20;                           **<div>**

&#x20;                               **<label class="block text-xs font-semibold text-slate-300 mb-2">Ismingiz va Familiyangiz</label>**

&#x20;                               **<input type="text" required placeholder="Masalan: Jasur Rahimov" class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-3 text-white text-sm focus:outline-none focus:border-amber-500 transition-colors">**

&#x20;                           **</div>**

&#x20;                           **<div>**

&#x20;                               **<label class="block text-xs font-semibold text-slate-300 mb-2">Telefon raqamingiz</label>**

&#x20;                               **<input type="tel" required placeholder="+998 90 123 45 67" class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-3 text-white text-sm focus:outline-none focus:border-amber-500 transition-colors">**

&#x20;                           **</div>**

&#x20;                       **</div>**



&#x20;                       **<div class="grid md:grid-cols-2 gap-6">**

&#x20;                           **<div>**

&#x20;                               **<label class="block text-xs font-semibold text-slate-300 mb-2">Viloyatni tanlang</label>**

&#x20;                               **<select required class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-3 text-white text-sm focus:outline-none focus:border-amber-500 transition-colors">**

&#x20;                                   **<option value="">-- Viloyatni tanlang --</option>**

&#x20;                                   **<option value="Toshkent">Toshkent viloyati / shahri</option>**

&#x20;                                   **<option value="Samarqand">Samarqand viloyati</option>**

&#x20;                                   **<option value="Farg'ona">Farg'ona viloyati</option>**

&#x20;                                   **<option value="Andijon">Andijon viloyati</option>**

&#x20;                                   **<option value="Namangan">Namangan viloyati</option>**

&#x20;                                   **<option value="Buxoro">Buxoro viloyati</option>**

&#x20;                                   **<option value="Xorazm">Xorazm viloyati</option>**

&#x20;                                   **<option value="Qashqadaryo">Qashqadaryo viloyati</option>**

&#x20;                                   **<option value="Surxondaryo">Surxondaryo viloyati</option>**

&#x20;                                   **<option value="Navoiy">Navoiy viloyati</option>**

&#x20;                                   **<option value="Jizzax">Jizzax viloyati</option>**

&#x20;                                   **<option value="Sirdaryo">Sirdaryo viloyati</option>**

&#x20;                                   **<option value="Qoraqalpog'iston">Qoraqalpog'iston R.</option>**

&#x20;                               **</select>**

&#x20;                           **</div>**

&#x20;                           **<div>**

&#x20;                               **<label class="block text-xs font-semibold text-slate-300 mb-2">Tuman / Qishloq / MFY nomi</label>**

&#x20;                               **<input type="text" required placeholder="Masalan: Yangiaryk tuman, Bog'ot MFY" class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-3 text-white text-sm focus:outline-none focus:border-amber-500 transition-colors">**

&#x20;                           **</div>**

&#x20;                       **</div>**



&#x20;                       **<div>**

&#x20;                           **<label class="block text-xs font-semibold text-slate-300 mb-2">Joriy Muammo yoki Yo'l Holati</label>**

&#x20;                           **<select required class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-3 text-white text-sm focus:outline-none focus:border-amber-500 transition-colors">**

&#x20;                               **<option value="rejasiz">Asfalt qilindi, lekin quvur o'tkazilmagan (xavf bor)</option>**

&#x20;                               **<option value="vodoprovod">Vodoprovod/Gaz yo'q, yangi yotqizilishi kerak</option>**

&#x20;                               **<option value="ta'mir">Yo'l o'nqir-cho'nqir, ideal ketma-ketlikda ta'mirlash kerak</option>**

&#x20;                               **<option value="boshqa">Boshqa taklif</option>**

&#x20;                           **</select>**

&#x20;                       **</div>**



&#x20;                       **<div>**

&#x20;                           **<label class="block text-xs font-semibold text-slate-300 mb-2">Batafsil Izoh yoki Taklifingiz</label>**

&#x20;                           **<textarea rows="3" placeholder="Ko'changgizdagi yo'l holati bo'yicha taklif bildiring..." class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-3 text-white text-sm focus:outline-none focus:border-amber-500 transition-colors"></textarea>**

&#x20;                       **</div>**



&#x20;                       **<button type="submit" class="w-full py-4 bg-gradient-to-r from-amber-500 to-amber-600 hover:from-amber-400 hover:to-amber-500 text-slate-950 font-bold rounded-xl transition-all shadow-lg shadow-amber-500/20 text-sm flex items-center justify-center gap-2">**

&#x20;                           **<i data-lucide="send" class="w-4 h-4"></i> Ariza va Taklifni Yuborish**

&#x20;                       **</button>**

&#x20;                   **</form>**



&#x20;                   **<!-- Alert message box -->**

&#x20;                   **<div id="form-alert" class="hidden mt-4 p-4 rounded-xl bg-emerald-500/10 border border-emerald-500/30 text-emerald-400 text-xs text-center">**

&#x20;                       **Rahmat! Sizning arizangiz va taklifingiz qabul qilindi. Tez orada mas'ul muhandislar hudud rejasi bo'yicha bog'lanishadi.**

&#x20;                   **</div>**

&#x20;               **</div>**

&#x20;           **</div>**

&#x20;       **</section>**



&#x20;       **<!-- Recommendations Section -->**

&#x20;       **<section id="recommendations" class="py-16 bg-slate-900 border-t border-slate-800">**

&#x20;           **<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">**

&#x20;               **<div class="text-center mb-12">**

&#x20;                   **<h2 class="text-3xl font-bold text-white">Yo'l Sifatini Yaxshilash Bo'yicha Tavsiyalar</h2>**

&#x20;                   **<p class="text-slate-400 mt-2">Muammoni tubdan hal etish uchun tizimli yechimlar</p>**

&#x20;               **</div>**



&#x20;               **<div class="grid md:grid-cols-3 gap-6">**

&#x20;                   **<div class="bg-slate-950 p-6 rounded-2xl border border-slate-800">**

&#x20;                       **<div class="w-10 h-10 bg-amber-500/10 text-amber-400 rounded-lg flex items-center justify-center mb-4">**

&#x20;                           **<i data-lucide="database" class="w-5 h-5"></i>**

&#x20;                       **</div>**

&#x20;                       **<h3 class="text-base font-bold text-white mb-2">Yagona GIS Geoportali</h3>**

&#x20;                       **<p class="text-xs text-slate-400 leading-relaxed">**

&#x20;                           **Barcha yer osti kommunikatsiyalarining raqamli xaritasini yaratish va uni ochiq reyestrga kiritish. Bu bilan noqonuniy yoki rejasiz qazishlarga chek qo'yiladi.**

&#x20;                       **</p>**

&#x20;                   **</div>**



&#x20;                   **<div class="bg-slate-950 p-6 rounded-2xl border border-slate-800">**

&#x20;                       **<div class="w-10 h-10 bg-amber-500/10 text-amber-400 rounded-lg flex items-center justify-center mb-4">**

&#x20;                           **<i data-lucide="shield-check" class="w-5 h-5"></i>**

&#x20;                       **</div>**

&#x20;                       **<h3 class="text-base font-bold text-white mb-2">Kolektor Tizimi (Tunnellar)</h3>**

&#x20;                       **<p class="text-xs text-slate-400 leading-relaxed">**

&#x20;                           **Yangi yo me'moriy loyihalarda barcha quvurlarni maxsus o'tish teshiklariga (tunnel) joylashtirish. Kelajakda ta'birlash uchun yo'l kavlanmaydi.**

&#x20;                       **</p>**

&#x20;                   **</div>**



&#x20;                   **<div class="bg-slate-950 p-6 rounded-2xl border border-slate-800">**

&#x20;                       **<div class="w-10 h-10 bg-amber-500/10 text-amber-400 rounded-lg flex items-center justify-center mb-4">**

&#x20;                           **<i data-lucide="file-badge" class="w-5 h-5"></i>**

&#x20;                       **</div>**

&#x20;                       **<h3 class="text-base font-bold text-white mb-2">Kafolat va Sertifikatlash</h3>**

&#x20;                       **<p class="text-xs text-slate-400 leading-relaxed">**

&#x20;                           **Pudrat tashkilotlariga kamida 5-10 yillik kafolat majburiyatini yuklash. Agar muddatdan oldin yo'l buzilsa, qayta tiklash puddatchi hisobidan bo'ladi.**

&#x20;                       **</p>**

&#x20;                   **</div>**

&#x20;               **</div>**

&#x20;           **</div>**

&#x20;       **</section>**

&#x20;   **</main>**



&#x20;   **<!-- Footer -->**

&#x20;   **<footer class="border-t border-slate-800 bg-slate-950 py-8">**

&#x20;       **<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col md:flex-row justify-between items-center gap-4">**

&#x20;           **<p class="text-xs text-slate-500">© 2026 RoadMaster Pro — Shaffof va Tejamkor Yo'l Qurilishi Tashabbusi.</p>**

&#x20;           **<div class="flex items-center space-x-4 text-xs text-slate-400">**

&#x20;               **<span class="flex items-center gap-1"><i data-lucide="check" class="w-4 h-4 text-emerald-400"></i> Xalqaro Standartlar</span>**

&#x20;               **<span class="flex items-center gap-1"><i data-lucide="check" class="w-4 h-4 text-emerald-400"></i> Kam Xarajat, Yuqori Sifat</span>**

&#x20;           **</div>**

&#x20;       **</div>**

&#x20;   **</footer>**



&#x20;   **<script>**

&#x20;       **// Lucide ikonkalarini faollashtirish**

&#x20;       **if (window.lucide) {**

&#x20;           **lucide.createIcons();**

&#x20;       **}**



&#x20;       **// Simulyator mantiqiy kodi**

&#x20;       **let currentStep = 0;**



&#x20;       **function buildStep(step) {**

&#x20;           **const infoBox = document.getElementById('sim-status');**

&#x20;           **const layerPipes = document.getElementById('layer-pipes');**

&#x20;           **const layerBase = document.getElementById('layer-base');**

&#x20;           **const layerAsphalt = document.getElementById('layer-asphalt');**

&#x20;           **const layerMarkings = document.getElementById('layer-markings');**



&#x20;           **if (!infoBox || !layerPipes || !layerBase || !layerAsphalt || !layerMarkings) return;**



&#x20;           **if (step === 1) {**

&#x20;               **currentStep = 1;**

&#x20;               **infoBox.innerHTML = '<span class="text-emerald-400 font-bold">1-Bosqich Bajarildi:</span> Geodeziya va loyihalash yakunlandi. Raqamli xarita tayyor.';**

&#x20;               **layerPipes.classList.remove('opacity-20');**

&#x20;               **layerPipes.classList.add('opacity-40');**

&#x20;           **} else if (step === 2) {**

&#x20;               **if (currentStep < 1) {**

&#x20;                   **infoBox.innerHTML = '<span class="text-red-400 font-bold">Xatolik:</span> Avval 1-bosqich (Rejalashtirish)ni bajaring!';**

&#x20;                   **return;**

&#x20;               **}**

&#x20;               **currentStep = 2;**

&#x20;               **infoBox.innerHTML = '<span class="text-emerald-400 font-bold">2-Bosqich Bajarildi:</span> Barcha yer osti quvurlari (suv, gaz, elektr) yotqizildi va sinovdan o\\'tkazildi.';**

&#x20;               **layerPipes.classList.remove('opacity-40');**

&#x20;               **layerPipes.classList.add('opacity-100', 'bg-slate-800');**

&#x20;           **} else if (step === 3) {**

&#x20;               **if (currentStep < 2) {**

&#x20;                   **infoBox.innerHTML = '<span class="text-red-400 font-bold">Xatolik:</span> Avval quvur va kommunikatsiyalarni yotqizing!';**

&#x20;                   **return;**

&#x20;               **}**

&#x20;               **currentStep = 3;**

&#x20;               **infoBox.innerHTML = '<span class="text-emerald-400 font-bold">3-Bosqich Bajarildi:</span> Shag\\'al va qum poydevori yotqizildi hamda vibratsiyali zichlashtirildi.';**

&#x20;               **layerBase.classList.remove('opacity-20');**

&#x20;               **layerBase.classList.add('opacity-100', 'bg-amber-900/80');**

&#x20;           **} else if (step === 4) {**

&#x20;               **if (currentStep < 3) {**

&#x20;                   **infoBox.innerHTML = '<span class="text-red-400 font-bold">Xatolik:</span> Poydevorsiz asfalt yotqizib bo\\'lmaydi!';**

&#x20;                   **return;**

&#x20;               **}**

&#x20;               **currentStep = 4;**

&#x20;               **infoBox.innerHTML = '<span class="text-emerald-400 font-bold">Muvaffaqiyatli!</span> Sifatli ko\\'p qatlamli asfalt va yo\\'l chiziqlari yotqizildi. Bu yo\\'l yillar davomida buzilmaydi va qayta kavlanmaydi!';**

&#x20;               **layerAsphalt.classList.remove('opacity-20');**

&#x20;               **layerAsphalt.classList.add('opacity-100', 'bg-slate-950');**

&#x20;               **layerMarkings.classList.remove('opacity-20');**

&#x20;               **layerMarkings.classList.add('opacity-100', 'bg-slate-900');**

&#x20;           **}**

&#x20;       **}**



&#x20;       **function resetSim() {**

&#x20;           **currentStep = 0;**

&#x20;           **const infoBox = document.getElementById('sim-status');**

&#x20;           **if (infoBox) {**

&#x20;               **infoBox.innerHTML = '<span class="text-amber-400 font-bold">Yo\\'riqnoma:</span> Yuqoridagi tugmalarni tartib bilan bosing (1-bosqichdan boshlab).';**

&#x20;           **}**

&#x20;           

&#x20;           **const layers = \['layer-pipes', 'layer-base', 'layer-asphalt', 'layer-markings'];**

&#x20;           **layers.forEach(id => {**

&#x20;               **const el = document.getElementById(id);**

&#x20;               **if (el) {**

&#x20;                   **el.className = el.className.replace(/opacity-100|opacity-40/g, 'opacity-20');**

&#x20;               **}**

&#x20;           **});**

&#x20;       **}**



&#x20;       **// Calculator Logic**

&#x20;       **function updateCalculator() {**

&#x20;           **const km = parseFloat(document.getElementById('calc-km').value) || 0;**

&#x20;           **const digs = parseFloat(document.getElementById('calc-digs').value) || 0;**

&#x20;           **const savedAmount = (km \* 20000000) + (digs \* 15000000);**

&#x20;           **const formatted = new Intl.NumberFormat('uz-UZ').format(savedAmount) + ' UZS';**

&#x20;           **document.getElementById('calc-result').innerText = formatted;**

&#x20;       **}**



&#x20;       **// Event listener'larni xavfsiz biriktirish**

&#x20;       **document.addEventListener('DOMContentLoaded', () => {**

&#x20;           **const btn1 = document.getElementById('btn-step-1');**

&#x20;           **const btn2 = document.getElementById('btn-step-2');**

&#x20;           **const btn3 = document.getElementById('btn-step-3');**

&#x20;           **const btn4 = document.getElementById('btn-step-4');**

&#x20;           **const btnReset = document.getElementById('btn-reset');**



&#x20;           **if (btn1) btn1.addEventListener('click', () => buildStep(1));**

&#x20;           **if (btn2) btn2.addEventListener('click', () => buildStep(2));**

&#x20;           **if (btn3) btn3.addEventListener('click', () => buildStep(3));**

&#x20;           **if (btn4) btn4.addEventListener('click', () => buildStep(4));**

&#x20;           **if (btnReset) btnReset.addEventListener('click', resetSim);**



&#x20;           **// Calculator events**

&#x20;           **const inputKm = document.getElementById('calc-km');**

&#x20;           **const inputDigs = document.getElementById('calc-digs');**

&#x20;           **if (inputKm) inputKm.addEventListener('input', updateCalculator);**

&#x20;           **if (inputDigs) inputDigs.addEventListener('input', updateCalculator);**



&#x20;           **// Form Submit Event**

&#x20;           **const form = document.getElementById('road-request-form');**

&#x20;           **const alertBox = document.getElementById('form-alert');**

&#x20;           **if (form) {**

&#x20;               **form.addEventListener('submit', (e) => {**

&#x20;                   **e.preventDefault();**

&#x20;                   **if (alertBox) {**

&#x20;                       **alertBox.classList.remove('hidden');**

&#x20;                       **form.reset();**

&#x20;                       **setTimeout(() => {**

&#x20;                           **alertBox.classList.add('hidden');**

&#x20;                       **}, 6000);**

&#x20;                   **}**

&#x20;               **});**

&#x20;           **}**

&#x20;       **});**

&#x20;   **</script>**

**</body>**

**</html>**



