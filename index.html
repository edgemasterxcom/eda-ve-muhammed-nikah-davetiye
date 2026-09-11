<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eda & Muhammed - Nikah Davetiyesi</title>
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,600;1,400&family=Alex+Brush&family=Montserrat:wght@300;400;500;600&display=swap" rel="stylesheet">
    
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        gold: '#C5A059',
                        dark: '#2F2E2C',
                        paper: '#ffffff',
                    },
                    fontFamily: {
                        serif: ['"Playfair Display"', 'serif'],
                        script: ['"Alex Brush"', 'cursive'],
                        sans: ['"Montserrat"', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        body, html { 
            margin: 0;
            padding: 0;
            height: 100%;
            overflow-x: hidden;
            background-color: #F8F5F2; 
        }
        
        /* Arka Plan Tasarımı */
        .floral-background {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100vh;
            z-index: 0;
            background-image: url('https://images.unsplash.com/photo-1515934751635-c81c6bc9a2d8?q=80&w=2070&auto=format&fit=crop'); 
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            opacity: 0.6; 
            filter: grayscale(20%) sepia(10%); 
        }

        /* Ana İçerik Kartı */
        .content-wrapper {
            position: relative;
            z-index: 10;
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 2rem 1rem;
        }

        .invite-card {
            background-color: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(5px);
            border: 1px solid rgba(197, 160, 89, 0.3); 
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            width: 100%;
            max-width: 450px;
            border-radius: 12px;
            padding: 2.5rem 1.5rem;
            position: relative;
        }

        /* Kapı Animasyonları */
        .door-left, .door-right {
            transition: transform 1.5s cubic-bezier(0.77, 0, 0.175, 1);
        }
        .open .door-left { transform: translateX(-100%); }
        .open .door-right { transform: translateX(100%); }
        
        .open .door-content { 
            opacity: 0; 
            pointer-events: none; 
            transition: opacity 0.5s ease; 
        }

        /* İçerik Yüklenme Animasyonları */
        .fade-in-up {
            opacity: 0;
            transform: translateY(20px);
        }
        .animate-up {
            animation: fadeInUp 1s ease forwards;
        }
        
        @keyframes fadeInUp {
            to { opacity: 1; transform: translateY(0); }
        }
        
        .delay-1 { animation-delay: 0.3s; }
        .delay-2 { animation-delay: 0.6s; }
        .delay-3 { animation-delay: 0.9s; }
        .delay-4 { animation-delay: 1.2s; }
        
    </style>
</head>
<body class="antialiased text-dark">

    <!-- Karşılama Ekranı (Kapı Açılış Efekti) -->
    <div id="welcome-doors" class="fixed inset-0 z-50 flex w-full h-full bg-white">
        <!-- Sol Kapı -->
        <div class="door-left relative w-1/2 h-full bg-white border-r border-gold/20 shadow-[10px_0_20px_rgba(0,0,0,0.05)] flex justify-end items-center overflow-hidden z-20">
             <div class="absolute w-[200%] h-full opacity-10 bg-[url('https://images.unsplash.com/photo-1515934751635-c81c6bc9a2d8?q=80&w=2070&auto=format&fit=crop')] bg-cover bg-left"></div>
        </div>
        <!-- Sağ Kapı -->
        <div class="door-right relative w-1/2 h-full bg-white border-l border-gold/20 shadow-[-10px_0_20px_rgba(0,0,0,0.05)] flex justify-start items-center overflow-hidden z-20">
             <div class="absolute w-[200%] h-full opacity-10 bg-[url('https://images.unsplash.com/photo-1515934751635-c81c6bc9a2d8?q=80&w=2070&auto=format&fit=crop')] bg-cover bg-right" style="transform: translateX(-50%);"></div>
        </div>
        
        <!-- Buton ve Karşılama Metni -->
        <div class="door-content absolute inset-0 flex flex-col items-center justify-center z-30">
            <button onclick="openInvite()" class="group relative flex flex-col items-center focus:outline-none">
                
                <!-- Zarf İkonu / Mühür Görünümü -->
                <div class="w-20 h-20 bg-white border-2 border-gold rounded-full flex items-center justify-center mb-6 shadow-[0_0_20px_rgba(197,160,89,0.3)] group-hover:scale-105 group-hover:bg-gold transition-all duration-500 cursor-pointer">
                    <i class="fa-solid fa-envelope-open-text text-2xl text-gold group-hover:text-white transition-colors duration-500"></i>
                </div>
                
                <!-- Zarif İsimler (Yeni Eklenen Kısım) -->
                <div class="flex flex-col items-center mt-2 group-hover:scale-105 transition-transform duration-500">
                    <h1 class="font-script text-5xl md:text-6xl text-dark leading-none drop-shadow-sm">Eda</h1>
                    <span class="font-script text-3xl md:text-4xl text-gold my-2 drop-shadow-sm">&amp;</span>
                    <h1 class="font-script text-5xl md:text-6xl text-dark leading-none drop-shadow-sm">Muhammed</h1>
                </div>

                <!-- UX İçin Minik Yönlendirme -->
                <div class="mt-10 flex flex-col items-center animate-pulse opacity-50">
                    <span class="font-sans text-[8px] tracking-[0.3em] uppercase text-gray-500">Açmak İçin Dokunun</span>
                    <i class="fa-solid fa-chevron-down text-[10px] text-gray-400 mt-2"></i>
                </div>

            </button>
        </div>
    </div>

    <!-- Arkadaki Sabit Çiçekli Zemin -->
    <div class="floral-background hidden" id="main-bg"></div>

    <!-- Asıl Davetiye İçeriği Alanı -->
    <div class="content-wrapper hidden" id="main-content">
        
        <div class="invite-card">
            
            <!-- Üst Altın Çizgi / Çelenk detayı -->
            <div class="flex justify-center items-center mb-6 fade-in-up animate-box">
                <div class="w-10 h-[1px] bg-gold/60"></div>
                <i class="fa-brands fa-pagelines text-gold mx-2 text-lg"></i>
                <div class="w-10 h-[1px] bg-gold/60"></div>
            </div>

            <!-- Ayet Kısmı -->
            <div class="text-center mb-8 fade-in-up animate-box delay-1">
                <p class="font-serif italic text-sm text-gray-700 leading-relaxed px-2">
                    "Ve O, sizi tek bir nefesten yarattı, ondan da eşini var etti.<br>
                    Ondan birçok erkek ve kadın meydana getirdi."
                </p>
                <p class="font-sans text-[9px] font-semibold text-gold mt-2 tracking-widest uppercase">(Nisa Suresi, 1)</p>
            </div>

            <!-- İsimler -->
            <div class="text-center mb-10 fade-in-up animate-box delay-2">
                <h1 class="font-script text-6xl md:text-7xl text-dark mb-1">Eda</h1>
                <span class="font-script text-3xl text-gold mx-2">&amp;</span>
                <h1 class="font-script text-6xl md:text-7xl text-dark mt-1">Muhammed</h1>
            </div>

            <!-- Başlık ve Giriş -->
            <div class="text-center mb-8 fade-in-up animate-box delay-3">
                <h2 class="font-sans font-light tracking-[0.25em] uppercase text-xs md:text-sm text-gold mb-4 border-b border-gold/30 pb-3 inline-block">
                    NİKAH TÖRENİ
                </h2>
                <p class="font-serif text-sm leading-relaxed text-gray-600 px-4 mt-2">
                    Bir ömür boyu sürecek mutluluğumuzun ilk adımında, 
                    siz değerli dostlarımızı aramızda görmekten onur duyarız.
                </p>
            </div>

            <!-- Bilgi Alanları -->
            <div class="space-y-6 mb-8 fade-in-up animate-box delay-4">
                
                <!-- Tarih -->
                <div class="text-center">
                    <i class="fa-regular fa-calendar text-gold text-xl mb-2 block"></i>
                    <p class="font-serif font-medium text-lg text-dark uppercase">11 Eylül Cuma 2026</p>
                    <p class="font-sans font-light text-dark tracking-wider mt-1">Saat: 15.30</p>
                </div>

                <div class="w-16 h-[1px] bg-gold/30 mx-auto"></div>

                <!-- Mekan -->
                <div class="text-center">
                    <i class="fa-solid fa-location-dot text-gold text-xl mb-2 block"></i>
                    <p class="font-serif font-medium text-lg text-dark">Altınkum Düğün Salonu</p>
                    <p class="font-sans font-light text-sm text-gray-600 mt-1 uppercase tracking-wider">Plaj, Eğirdir</p>
                </div>
                
                <div class="w-16 h-[1px] bg-gold/30 mx-auto"></div>

                <!-- Yemek -->
                <div class="text-center">
                    <i class="fa-solid fa-utensils text-gold text-xl mb-2 block"></i>
                    <p class="font-serif font-medium text-lg text-dark">Hacı Aladdin Pide & Kebap</p>
                    <p class="font-sans font-light text-xs text-gray-500 mt-1 italic">Nikah sonrası yemek ikramımızdır.</p>
                </div>

            </div>

            <!-- Alt Mesaj -->
            <div class="text-center fade-in-up animate-box delay-4 mt-6">
                <p class="font-serif italic text-gray-700 text-sm mb-6 px-4">
                    Bu özel günümüzde sizleri aramızda görmekten mutluluk duyarız.
                </p>
            </div>
            
            <!-- Yol Tarifi Butonu -->
            <div class="mt-6 text-center fade-in-up animate-box delay-4 pb-2">
                <!-- href="" içerisine Google Maps linkinizi yapıştırabilirsiniz -->
                <a href="#" class="inline-flex items-center gap-2 bg-dark text-white px-6 py-3 rounded-md font-sans text-[10px] tracking-[0.2em] uppercase hover:bg-gold hover:text-white transition-all duration-300 w-full justify-center">
                    <i class="fa-solid fa-map-location-dot"></i> Yol Tarifi Al
                </a>
            </div>

        </div>
    </div>

    <script>
        function openInvite() {
            document.getElementById('welcome-doors').classList.add('open');
            
            const bg = document.getElementById('main-bg');
            const content = document.getElementById('main-content');
            
            bg.classList.remove('hidden');
            content.classList.remove('hidden');
            
            setTimeout(() => {
                const animateBoxes = document.querySelectorAll('.animate-box');
                animateBoxes.forEach(box => {
                    box.classList.add('animate-up');
                });
            }, 300); 
            
            setTimeout(() => {
                document.getElementById('welcome-doors').style.display = 'none';
            }, 1500); 
        }
    </script>
</body>
</html>
