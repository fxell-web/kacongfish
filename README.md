<!doctype html>
<html lang="id" class="scroll-smooth"><head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kacongfish - Ikan Marinasi Praktis Kedungkandang Malang</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="">
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&amp;display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            blue: '#0284c7',
                            dark: '#0369a1',
                            teal: '#0d9488',
                            orange: '#f97316',
                            gold: '#eab308'
                        }
                    },
                    fontFamily: {
                        sans: ['Plus Jakarta Sans', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        .gradient-text {
            background: linear-gradient(135deg, #0284c7 0%, #0d9488 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .hero-bg {
            background: linear-gradient(rgba(15, 23, 42, 0.75), rgba(15, 23, 42, 0.75)), url('https://images.unsplash.com/photo-1534422298391-e4f8c172dddb?auto=format&fit=crop&q=80&w=1920');
            background-size: cover;
            background-position: center;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 font-sans antialiased selection:bg-brand-blue selection:text-white">

    <header class="sticky top-0 z-40 bg-white/90 backdrop-blur-md shadow-sm transition-all duration-300">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-20">
                <!-- Logo & Brand Name -->
                <a href="#" class="flex items-center space-x-3 group">
                    <div class="w-12 h-12 rounded-2xl bg-gradient-to-tr from-brand-blue to-brand-teal flex items-center justify-center text-white shadow-lg shadow-brand-blue/30 group-hover:scale-105 transition-transform">
                        <i class="fa-solid font-bold fa-fish text-2xl"></i>
                    </div>
                    <div>
                        <span class="text-2xl font-extrabold tracking-tight text-slate-900 block leading-none">kacongfish</span>
                        <span class="text-xs font-semibold text-brand-teal tracking-wider uppercase">Ikan Marinasi Praktis</span>
                    </div>
                </a>

                <!-- Desktop Navigation -->
                <nav class="hidden md:flex items-center space-x-8">
                    <a href="#tentang" class="text-sm font-semibold text-slate-600 hover:text-brand-blue transition-colors">Tentang Kami</a>
                    <a href="#menu" class="text-sm font-semibold text-slate-600 hover:text-brand-blue transition-colors">Menu Favorit</a>
                    <a href="#keunggulan" class="text-sm font-semibold text-slate-600 hover:text-brand-blue transition-colors">Keunggulan</a>
                    <a href="#lokasi" class="text-sm font-semibold text-slate-600 hover:text-brand-blue transition-colors">Lokasi</a>
                    <a href="https://wa.me/6281235550636?text=Halo%20Kacongfish,%20saya%20ingin%20bertanya%20mengenai%20produk%20ikan%20marinasi" target="_blank" class="inline-flex items-center justify-center px-5 py-2.5 rounded-full text-sm font-bold text-white bg-brand-orange hover:bg-orange-600 shadow-md shadow-orange-500/20 hover:shadow-lg transition-all transform hover:-translate-y-0.5">
                        <i class="fa-brands fa-whatsapp text-lg mr-2"></i> Hubungi Kami
                    </a>
                </nav>

                <!-- Mobile menu button -->
                <div class="md:hidden flex items-center">
                    <button id="mobile-menu-button" type="button" class="text-slate-600 hover:text-brand-blue p-2 rounded-lg focus:outline-none" aria-label="Toggle Menu">
                        <i class="fa-solid fa-bars text-2xl" id="menu-icon"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Mobile Navigation Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white border-b border-slate-200 px-4 pt-2 pb-6 space-y-3">
            <a href="#tentang" class="block py-2 text-base font-semibold text-slate-700 hover:text-brand-blue">Tentang Kami</a>
            <a href="#menu" class="block py-2 text-base font-semibold text-slate-700 hover:text-brand-blue">Menu Favorit</a>
            <a href="#keunggulan" class="block py-2 text-base font-semibold text-slate-700 hover:text-brand-blue">Keunggulan</a>
            <a href="#lokasi" class="block py-2 text-base font-semibold text-slate-700 hover:text-brand-blue">Lokasi</a>
            <a href="https://wa.me/6281235550636?text=Halo%20Kacongfish,%20saya%20mau%20pesan%20Ikan%20Marinasi" target="_blank" class="flex items-center justify-center w-full py-3 mt-2 rounded-xl text-base font-bold text-white bg-brand-orange hover:bg-orange-600">
                <i class="fa-brands fa-whatsapp text-xl mr-2"></i> Pesan via WhatsApp
            </a>
        </div>
    </header>

    <section class="relative hero-bg py-24 lg:py-32 overflow-hidden">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                <div class="lg:col-span-7 text-center lg:text-left">
                    <div class="inline-flex items-center space-x-2 bg-brand-blue/20 border border-brand-blue/30 backdrop-blur-md px-4 py-1.5 rounded-full mb-6">
                        <span class="flex h-2 w-2 rounded-full bg-brand-orange animate-ping"></span>
                        <span class="text-xs sm:text-sm font-semibold text-cyan-200">Khas Kedungkandang, Malang</span>
                    </div>
                    <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold text-white tracking-tight leading-tight mb-6">
                        Solusi Praktis Makan Ikan Segar &amp; <span class="text-brand-orange">Bumbu Meresap!</span>
                    </h1>
                    <p class="text-lg sm:text-xl text-slate-300 mb-8 max-w-2xl mx-auto lg:mx-0 font-normal">
                        Nikmati kelezatan <strong class="text-white">Kacongfish</strong>, ikan marinasi berkualitas siap goreng/masak tanpa repot membersihkan &amp; meracik bumbu. Tinggal buka, goreng, dan sajikan!
                    </p>
                    <div class="flex flex-col sm:flex-row items-center justify-center lg:justify-start gap-4">
                        <a href="https://wa.me/6281235550636?text=Halo%20Kacongfish,%20saya%20mau%20pesan%20Ikan%20Mujair%20Marinasi%20Rp15.000" target="_blank" class="w-full sm:w-auto inline-flex items-center justify-center px-8 py-4 rounded-2xl text-lg font-bold text-white bg-gradient-to-r from-brand-orange to-amber-500 hover:from-orange-600 hover:to-amber-600 shadow-xl shadow-orange-500/25 transition-all transform hover:-translate-y-1">
                            <i class="fa-brands fa-whatsapp text-2xl mr-3"></i> Pesan Mujair Rp15.000
                        </a>
                        <a href="#menu" class="w-full sm:w-auto inline-flex items-center justify-center px-8 py-4 rounded-2xl text-lg font-bold text-white bg-white/10 hover:bg-white/20 border border-white/20 backdrop-blur-md transition-all">
                            Lihat Menu Lainnya
                        </a>
                    </div>
                    <div class="mt-10 flex items-center justify-center lg:justify-start space-x-6 text-slate-300 text-sm">
                        <div class="flex items-center"><i class="fa-solid fa-check text-brand-teal mr-2"></i> 100% Halal</div>
                        <div class="flex items-center"><i class="fa-solid fa-check text-brand-teal mr-2"></i> Tanpa Pengawet</div>
                        <div class="flex items-center"><i class="fa-solid fa-check text-brand-teal mr-2"></i> Siap Masak</div>
                    </div>
                </div>
                <!-- Highlight Hero Image / Card -->
                <div class="lg:col-span-5">
                    <div class="relative mx-auto max-w-md bg-white/10 border border-white/20 backdrop-blur-xl p-6 rounded-3xl shadow-2xl">
                        <div class="relative h-64 sm:h-72 rounded-2xl overflow-hidden mb-5">
                            <img src="https://images.unsplash.com/photo-1519708227418-c8fd9a32b7a2?auto=format&amp;fit=crop&amp;q=80&amp;w=800" alt="Ikan Mujair Marinasi Kacongfish" class="w-full h-full object-cover transform hover:scale-105 transition-transform duration-500">
                            <div class="absolute top-3 right-3 bg-brand-orange text-white text-xs font-bold px-3 py-1.5 rounded-full shadow-md uppercase tracking-wider">
                                Menu Andalan
                            </div>
                        </div>
                        <div class="text-white">
                            <div class="flex justify-between items-start mb-2">
                                <h3 class="text-2xl font-bold">Ikan Mujair Marinasi</h3>
                                <span class="text-2xl font-extrabold text-brand-gold">Rp 15.000</span>
                            </div>
                            <p class="text-slate-300 text-sm mb-4">Ikan mujair pilihan bermutu tinggi, dibersihkan higienis, dan dimarinasi dengan bumbu rempah alami yang gurih hingga ke tulang.</p>
                            <a href="https://wa.me/6281235550636?text=Halo%20Kacongfish,%20saya%20mau%20pesan%20Ikan%20Mujair%20Marinasi%20(Rp15.000)" target="_blank" class="w-full py-3 bg-brand-blue hover:bg-brand-dark text-white font-bold rounded-xl flex items-center justify-center transition-colors">
                                <i class="fa-brands fa-whatsapp mr-2 text-lg"></i> Beli Sekarang
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="tentang" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-xs font-extrabold text-brand-blue uppercase tracking-widest mb-2">Mengapa Kacongfish?</h2>
                <p class="text-3xl sm:text-4xl font-extrabold text-slate-900 tracking-tight">Solusi Praktis &amp; Lezat untuk Santapan Keluarga</p>
                <div class="w-20 h-1.5 bg-brand-orange mx-auto mt-4 rounded-full"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Feature 1 -->
                <div class="bg-slate-50 p-8 rounded-3xl border border-slate-100 hover:shadow-xl transition-all duration-300 transform hover:-translate-y-1">
                    <div class="w-14 h-14 bg-brand-blue/10 text-brand-blue rounded-2xl flex items-center justify-center text-2xl mb-6">
                        <i class="fa-solid fa-utensils"></i>
                    </div>
                    <h3 class="text-xl font-bold text-slate-900 mb-3">Praktis &amp; Bebas Repot</h3>
                    <p class="text-slate-600 leading-relaxed text-sm">Tidak perlu bersihin sisik, membuang kotoran, atau mengulek bumbu. Ikan marinasi kami siap langsung digoreng atau dibakar.</p>
                </div>

                <!-- Feature 2 -->
                <div class="bg-slate-50 p-8 rounded-3xl border border-slate-100 hover:shadow-xl transition-all duration-300 transform hover:-translate-y-1">
                    <div class="w-14 h-14 bg-brand-teal/10 text-brand-teal rounded-2xl flex items-center justify-center text-2xl mb-6">
                        <i class="fa-solid fa-mortar-pestle"></i>
                    </div>
                    <h3 class="text-xl font-bold text-slate-900 mb-3">Bumbu Rempah Meresap</h3>
                    <p class="text-slate-600 leading-relaxed text-sm">Menggunakan racikan bumbu rempah-rempah tradisional khas Malang yang meresap sempurna hingga ke dalam daging ikan.</p>
                </div>

                <!-- Feature 3 -->
                <div class="bg-slate-50 p-8 rounded-3xl border border-slate-100 hover:shadow-xl transition-all duration-300 transform hover:-translate-y-1">
                    <div class="w-14 h-14 bg-brand-orange/10 text-brand-orange rounded-2xl flex items-center justify-center text-2xl mb-6">
                        <i class="fa-solid fa-shield-halved"></i>
                    </div>
                    <h3 class="text-xl font-bold text-slate-900 mb-3">Segar &amp; Higienis</h3>
                    <p class="text-slate-600 leading-relaxed text-sm">Ikan diproses dalam kondisi segar setiap harinya, dikemas secara bersih dan higienis tanpa bahan pengawet berbahaya.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="menu" class="py-20 bg-slate-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <span class="text-xs font-extrabold text-brand-teal uppercase tracking-widest block mb-2">Pilihan Produk</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-slate-900 tracking-tight">Menu Ikan Marinasi Praktis</h2>
                <p class="text-slate-600 mt-3 text-base">Pilih varian ikan favoritmu dan pesan langsung via WhatsApp!</p>
                <div class="w-20 h-1.5 bg-brand-blue mx-auto mt-4 rounded-full"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                
                <!-- MENU 1: HIGHLIGHT MUJAIR -->
                <div class="bg-white rounded-3xl overflow-hidden shadow-md hover:shadow-2xl transition-all duration-300 border-2 border-brand-orange flex flex-col relative group">
                    <div class="absolute top-4 left-4 z-10 bg-brand-orange text-white text-xs font-bold px-3 py-1 rounded-full shadow">
                        BEST SELLER
                    </div>
                    <div class="relative h-52 overflow-hidden bg-slate-200">
                        <img src="https://images.unsplash.com/photo-1519708227418-c8fd9a32b7a2?auto=format&amp;fit=crop&amp;q=80&amp;w=600" alt="Ikan Mujair Marinasi" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500">
                    </div>
                    <div class="p-6 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xl font-extrabold text-slate-900 mb-1">Ikan Mujair Marinasi</h3>
                            <p class="text-slate-500 text-xs mb-4">Daging gurih, bumbu meresap, siap goreng krispi.</p>
                        </div>
                        <div>
                            <div class="flex items-baseline justify-between mb-4">
                                <span class="text-xs text-slate-400 font-medium">Harga / Porsi</span>
                                <span class="text-2xl font-black text-brand-orange">Rp 15.000</span>
                            </div>
                            <a href="https://wa.me/6281235550636?text=Halo%20Kacongfish,%20saya%20mau%20pesan%20Ikan%20Mujair%20Marinasi%20(Rp15.000)" target="_blank" class="w-full py-3 bg-brand-orange hover:bg-orange-600 text-white font-bold rounded-xl flex items-center justify-center transition-all shadow-md shadow-orange-500/20">
                                <i class="fa-brands fa-whatsapp text-lg mr-2"></i> Pesan Sekarang
                            </a>
                        </div>
                    </div>
                </div>

                <!-- MENU 2: NILA -->
                <div class="bg-white rounded-3xl overflow-hidden shadow-sm hover:shadow-xl transition-all duration-300 border border-slate-200 flex flex-col group">
                    <div class="relative h-52 overflow-hidden bg-slate-200">
                        <img src="https://images.unsplash.com/photo-1534422298391-e4f8c172dddb?auto=format&amp;fit=crop&amp;q=80&amp;w=600" alt="Ikan Nila Marinasi" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500">
                    </div>
                    <div class="p-6 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xl font-bold text-slate-900 mb-1">Ikan Nila Marinasi</h3>
                            <p class="text-slate-500 text-xs mb-4">Daging tebal dan lembut dengan bumbu kuning spesial.</p>
                        </div>
                        <div>
                            <div class="flex items-baseline justify-between mb-4">
                                <span class="text-xs text-slate-400 font-medium">Harga / Porsi</span>
                                <span class="text-2xl font-black text-brand-blue">Rp 18.000</span>
                            </div>
                            <a href="https://wa.me/6281235550636?text=Halo%20Kacongfish,%20saya%20mau%20pesan%20Ikan%20Nila%20Marinasi%20(Rp18.000)" target="_blank" class="w-full py-3 bg-slate-800 hover:bg-slate-900 text-white font-bold rounded-xl flex items-center justify-center transition-all">
                                <i class="fa-brands fa-whatsapp text-lg mr-2"></i> Pesan Sekarang
                            </a>
                        </div>
                    </div>
                </div>

                <!-- MENU 3: LELE -->
                <div class="bg-white rounded-3xl overflow-hidden shadow-sm hover:shadow-xl transition-all duration-300 border border-slate-200 flex flex-col group">
                    <div class="relative h-52 overflow-hidden bg-slate-200">
                        <img src="https://images.unsplash.com/photo-1544551763-46a013bb70d5?auto=format&amp;fit=crop&amp;q=80&amp;w=600" alt="Ikan Lele Marinasi" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500">
                    </div>
                    <div class="p-6 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xl font-bold text-slate-900 mb-1">Ikan Lele Marinasi</h3>
                            <p class="text-slate-500 text-xs mb-4">Ikan lele segar bersih, bebas bau lumpur, siap goreng.</p>
                        </div>
                        <div>
                            <div class="flex items-baseline justify-between mb-4">
                                <span class="text-xs text-slate-400 font-medium">Harga / Porsi</span>
                                <span class="text-2xl font-black text-brand-blue">Rp 14.000</span>
                            </div>
                            <a href="https://wa.me/6281235550636?text=Halo%20Kacongfish,%20saya%20mau%20pesan%20Ikan%20Lele%20Marinasi%20(Rp14.000)" target="_blank" class="w-full py-3 bg-slate-800 hover:bg-slate-900 text-white font-bold rounded-xl flex items-center justify-center transition-all">
                                <i class="fa-brands fa-whatsapp text-lg mr-2"></i> Pesan Sekarang
                            </a>
                        </div>
                    </div>
                </div>

                <!-- MENU 4: GURAME -->
                <div class="bg-white rounded-3xl overflow-hidden shadow-sm hover:shadow-xl transition-all duration-300 border border-slate-200 flex flex-col group">
                    <div class="relative h-52 overflow-hidden bg-slate-200">
                        <img src="https://images.unsplash.com/photo-1535591273668-578e31182c4f?auto=format&amp;fit=crop&amp;q=80&amp;w=600" alt="Ikan Gurame Marinasi" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500">
                    </div>
                    <div class="p-6 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xl font-bold text-slate-900 mb-1">Ikan Gurame Marinasi</h3>
                            <p class="text-slate-500 text-xs mb-4">Porsi mantap cocok untuk sajian makan keluarga.</p>
                        </div>
                        <div>
                            <div class="flex items-baseline justify-between mb-4">
                                <span class="text-xs text-slate-400 font-medium">Harga / Porsi</span>
                                <span class="text-2xl font-black text-brand-blue">Rp 30.000</span>
                            </div>
                            <a href="https://wa.me/6281235550636?text=Halo%20Kacongfish,%20saya%20mau%20pesan%20Ikan%20Gurame%20Marinasi%20(Rp30.000)" target="_blank" class="w-full py-3 bg-slate-800 hover:bg-slate-900 text-white font-bold rounded-xl flex items-center justify-center transition-all">
                                <i class="fa-brands fa-whatsapp text-lg mr-2"></i> Pesan Sekarang
                            </a>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <section id="lokasi" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                
                <div class="lg:col-span-5">
                    <span class="text-xs font-extrabold text-brand-blue uppercase tracking-widest block mb-2">Lokasi Kami</span>
                    <h2 class="text-3xl sm:text-4xl font-extrabold text-slate-900 mb-6">Mampir ke Dapur Kacongfish</h2>
                    <p class="text-slate-600 mb-8 leading-relaxed">
                        Kami melayani pemesanan langsung maupun pengiriman area <strong class="text-slate-900">Kedungkandang dan seluruh Kota Malang</strong>. Dapatkan ikan segar bermarinasi favorit Anda setiap hari.
                    </p>

                    <div class="space-y-6">
                        <div class="flex items-start space-x-4">
                            <div class="w-12 h-12 bg-brand-blue/10 text-brand-blue rounded-2xl flex items-center justify-center text-xl shrink-0">
                                <i class="fa-solid fa-location-dot"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-slate-900 text-lg">Alamat</h4>
                                <p class="text-slate-600 text-sm">Kedungkandang, Kota Malang, Jawa Timur</p>
                            </div>
                        </div>

                        <div class="flex items-start space-x-4">
                            <div class="w-12 h-12 bg-brand-teal/10 text-brand-teal rounded-2xl flex items-center justify-center text-xl shrink-0">
                                <i class="fa-solid fa-clock"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-slate-900 text-lg">Jam Operasional</h4>
                                <p class="text-slate-600 text-sm">Buka Setiap Hari: 07.00 - 18.00 WIB</p>
                            </div>
                        </div>

                        <div class="flex items-start space-x-4">
                            <div class="w-12 h-12 bg-brand-orange/10 text-brand-orange rounded-2xl flex items-center justify-center text-xl shrink-0">
                                <i class="fa-solid fa-phone"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-slate-900 text-lg">Kontak &amp; WhatsApp</h4>
                                <p class="text-slate-600 text-sm">0812-3555-0636 (kacongfish)</p>
                            </div>
                        </div>
                    </div>

                    <div class="mt-8">
                        <a href="https://maps.google.com/?q=Kedungkandang+Malang" target="_blank" class="inline-flex items-center px-6 py-3 rounded-xl bg-slate-900 hover:bg-slate-800 text-white font-bold text-sm transition-all shadow-md">
                            <i class="fa-solid fa-map-location-dot mr-2"></i> Petunjuk Arah di Google Maps
                        </a>
                    </div>
                </div>

                <!-- Google Maps Embed Container -->
                <div class="lg:col-span-7">
                    <div class="bg-slate-100 p-3 rounded-3xl border border-slate-200 shadow-xl">
                        <div class="w-full h-80 sm:h-96 rounded-2xl overflow-hidden relative">
                            <iframe title="Lokasi Kacongfish Kedungkandang Malang" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3951.082729350438!2d112.6375!3d-7.99!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e7882d2a4505101%3A0x4027a76e352e8d0!2sKedungkandang%2C%20Kec.%20Kedungkandang%2C%20Kota%20Malang%2C%20Jawa%20Timur!5e0!3m2!1sid!2sid!4v1700000000000!5m2!1sid!2sid" class="w-full h-full border-0" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <footer class="bg-slate-900 text-slate-400 py-12 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mb-8 pb-8 border-b border-slate-800">
                <div>
                    <div class="flex items-center space-x-3 mb-4">
                        <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-brand-blue to-brand-teal flex items-center justify-center text-white font-bold">
                            <i class="fa-solid fa-fish"></i>
                        </div>
                        <span class="text-xl font-extrabold text-white">kacongfish</span>
                    </div>
                    <p class="text-sm text-slate-400">Penyedia ikan marinasi bumbu rempah praktis, lezat, dan higienis khas Kedungkandang, Malang.</p>
                </div>

                <div>
                    <h4 class="text-white font-bold mb-4">Navigasi Cepat</h4>
                    <ul class="space-y-2 text-sm">
                        <li><a href="#tentang" class="hover:text-white transition-colors">Tentang Kacongfish</a></li>
                        <li><a href="#menu" class="hover:text-white transition-colors">Menu Ikan Mujair &amp; Lainnya</a></li>
                        <li><a href="#lokasi" class="hover:text-white transition-colors">Lokasi Kedungkandang</a></li>
                    </ul>
                </div>

                <div>
                    <h4 class="text-white font-bold mb-4">Hubungi Kami</h4>
                    <p class="text-sm mb-2"><i class="fa-solid fa-user text-brand-teal mr-2"></i> Pemilik: <strong>kacongfish</strong></p>
                    <p class="text-sm mb-2"><i class="fa-brands fa-whatsapp text-brand-teal mr-2"></i> 0812-3555-0636</p>
                    <p class="text-sm"><i class="fa-solid fa-location-dot text-brand-teal mr-2"></i> Kedungkandang, Malang</p>
                </div>
            </div>

            <div class="text-center text-xs text-slate-500">
                © 2026 Kacongfish - Ikan Marinasi Praktis Malang. All rights reserved.
            </div>
        </div>
    </footer>

    <a href="https://wa.me/6281235550636?text=Halo%20Kacongfish,%20saya%20mau%20tanya%20produk%20ikan%20marinasi" target="_blank" aria-label="Chat WhatsApp Kacongfish" class="fixed bottom-6 right-6 z-50 bg-emerald-500 text-white p-4 rounded-full shadow-2xl hover:bg-emerald-600 transition-all transform hover:scale-110 flex items-center justify-center group">
        <i class="fa-brands fa-whatsapp text-3xl"></i>
        <span class="max-w-0 overflow-hidden whitespace-nowrap group-hover:max-w-xs transition-all duration-300 ease-in-out text-sm font-bold pl-0 group-hover:pl-3">
            Chat WhatsApp
        </span>
    </a>

    <script>
        // Toggle Mobile Menu
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');
        const menuIcon = document.getElementById('menu-icon');

        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
            if (mobileMenu.classList.contains('hidden')) {
                menuIcon.classList.remove('fa-xmark');
                menuIcon.classList.add('fa-bars');
            } else {
                menuIcon.classList.remove('fa-bars');
                menuIcon.classList.add('fa-xmark');
            }
        });

        // Close mobile menu when clicking nav links
        const mobileLinks = mobileMenu.querySelectorAll('a');
        mobileLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
                menuIcon.classList.remove('fa-xmark');
                menuIcon.classList.add('fa-bars');
            });
        });
    </script>

</body></html>
