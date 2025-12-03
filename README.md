<!DOCTYPE html>
<html lang="it" style="scroll-behavior: smooth;">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FareLuce - Energie Rinnovabili Torino</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Caricamento Lucide Icons -->
    <script src="https://unpkg.com/lucide@latest"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; }
        .hero-pattern {
            background-color: #111827;
            background-image: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.7)), url('https://images.unsplash.com/photo-1509391366360-2e959784a276?ixlib=rb-4.0.3&auto=format&fit=crop&w=1920&q=80');
            background-size: cover;
            background-position: center;
        }
        .solar-gradient {
            background: linear-gradient(135deg, #059669 0%, #10b981 100%);
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- Navigation -->
    <nav class="bg-white shadow-md fixed w-full z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-20">
                <div class="flex items-center">
                    <!-- Logo Concept Placeholder -->
                    <div class="flex-shrink-0 flex items-center gap-2">
                        <i data-lucide="sun" class="h-8 w-8 text-amber-500"></i>
                        <span class="font-bold text-2xl tracking-tight text-gray-900">Fare<span class="text-emerald-600">Luce</span></span>
                    </div>
                </div>
                <div class="hidden md:flex items-center space-x-8">
                    <a href="#chi-siamo" class="text-gray-600 hover:text-emerald-600 font-medium transition cursor-pointer">Chi Siamo</a>
                    <a href="#progetti" class="text-gray-600 hover:text-emerald-600 font-medium transition cursor-pointer">I Nostri Impianti</a>
                    <a href="#servizi" class="text-gray-600 hover:text-emerald-600 font-medium transition cursor-pointer">Servizi</a>
                    <a href="#contatti" class="bg-emerald-600 text-white px-5 py-2 rounded-full font-medium hover:bg-emerald-700 transition shadow-lg hover:shadow-xl transform hover:-translate-y-0.5 cursor-pointer">Contattaci</a>
                </div>
                <!-- Mobile menu button -->
                <div class="flex items-center md:hidden">
                    <button onclick="document.getElementById('mobile-menu').classList.toggle('hidden')" class="text-gray-500 hover:text-gray-700">
                        <i data-lucide="menu" class="h-6 w-6"></i>
                    </button>
                </div>
            </div>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white border-t">
            <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
                <a href="#chi-siamo" onclick="document.getElementById('mobile-menu').classList.add('hidden')" class="block px-3 py-2 text-base font-medium text-gray-700 hover:text-emerald-600 cursor-pointer">Chi Siamo</a>
                <a href="#progetti" onclick="document.getElementById('mobile-menu').classList.add('hidden')" class="block px-3 py-2 text-base font-medium text-gray-700 hover:text-emerald-600 cursor-pointer">Impianti</a>
                <a href="#servizi" onclick="document.getElementById('mobile-menu').classList.add('hidden')" class="block px-3 py-2 text-base font-medium text-gray-700 hover:text-emerald-600 cursor-pointer">Servizi</a>
                <a href="#contatti" onclick="document.getElementById('mobile-menu').classList.add('hidden')" class="block px-3 py-2 text-base font-medium text-emerald-600 font-bold cursor-pointer">Contattaci</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section (Aggiunto id="chi-siamo" qui per far funzionare il link) -->
    <section id="chi-siamo" class="hero-pattern h-screen flex items-center relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center relative z-10">
            <h1 class="text-4xl md:text-6xl font-extrabold text-white mb-6 leading-tight">
                L'energia del futuro <br>
                <span class="text-transparent bg-clip-text bg-gradient-to-r from-emerald-400 to-amber-300">parte da Mappano</span>
            </h1>
            <p class="mt-4 max-w-2xl mx-auto text-xl text-gray-200 mb-8">
                Specialisti in grandi impianti fotovoltaici su tetti industriali e terreni agricoli. 
                Sostenibilità concreta per il Piemonte.
            </p>
            <div class="flex justify-center gap-4">
                <a href="#progetti" class="bg-amber-500 text-white px-8 py-3 rounded-full font-bold hover:bg-amber-600 transition shadow-lg cursor-pointer">
                    Vedi il nostro Impianto da 1MW
                </a>
                <a href="#contatti" class="bg-white/10 backdrop-blur-md border border-white/30 text-white px-8 py-3 rounded-full font-bold hover:bg-white/20 transition cursor-pointer">
                    Richiedi Info
                </a>
            </div>
        </div>
        
        <!-- Stats Banner -->
        <div class="absolute bottom-0 w-full bg-emerald-900/90 backdrop-blur-sm border-t border-emerald-700">
            <div class="max-w-7xl mx-auto py-6 px-4 sm:px-6 lg:px-8 grid grid-cols-2 md:grid-cols-4 gap-8 text-center text-white">
                <div>
                    <div class="text-3xl font-bold text-emerald-400">1 MW</div>
                    <div class="text-sm opacity-80">Già Installato a Mappano</div>
                </div>
                <div>
                    <div class="text-3xl font-bold text-emerald-400">100%</div>
                    <div class="text-sm opacity-80">Energia Pulita</div>
                </div>
                <div>
                    <div class="text-3xl font-bold text-emerald-400">Locali</div>
                    <div class="text-sm opacity-80">Operativi su Torino</div>
                </div>
                <div>
                    <div class="text-3xl font-bold text-emerald-400">B2B</div>
                    <div class="text-sm opacity-80">Specialisti Aziendali</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Project Showcase: Mappano -->
    <section id="progetti" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="lg:text-center mb-16">
                <h2 class="text-base text-emerald-600 font-semibold tracking-wide uppercase">Il Nostro Orgoglio</h2>
                <p class="mt-2 text-3xl leading-8 font-extrabold tracking-tight text-gray-900 sm:text-4xl">
                    Il Primo Campo Fotovoltaico di Mappano
                </p>
                <p class="mt-4 max-w-2xl text-xl text-gray-500 lg:mx-auto">
                    Un progetto pionieristico da 1 Megawatt che alimenta il territorio con energia pulita.
                </p>
            </div>

            <div class="mt-10">
                <div class="grid grid-cols-1 md:grid-cols-2 gap-10 items-center">
                    <div class="rounded-2xl overflow-hidden shadow-2xl transform hover:scale-105 transition duration-500">
                        <!-- Placeholder for actual Mappano photo -->
                        <img src="https://images.unsplash.com/photo-1545209463-5dd37bf1c518?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="Impianto Fotovoltaico Mappano" class="w-full h-80 object-cover">
                        <div class="bg-gray-900 p-4 text-white">
                            <p class="font-bold">Mappano (TO)</p>
                            <p class="text-sm text-gray-400">Potenza: 1 MWp</p>
                        </div>
                    </div>
                    <div class="space-y-6">
                        <h3 class="text-2xl font-bold text-gray-900">Energia a km zero</h3>
                        <p class="text-lg text-gray-600">
                            Situato strategicamente nella provincia di Torino, il nostro impianto di Mappano rappresenta il primo passo di una visione più ampia. Abbiamo trasformato un'area in una centrale di produzione energetica sostenibile, capace di soddisfare il fabbisogno di centinaia di utenze.
                        </p>
                        <ul class="space-y-4">
                            <li class="flex items-start">
                                <div class="flex-shrink-0">
                                    <i data-lucide="check-circle" class="h-6 w-6 text-emerald-500"></i>
                                </div>
                                <p class="ml-3 text-base text-gray-600">Produzione costante monitorata da remoto</p>
                            </li>
                            <li class="flex items-start">
                                <div class="flex-shrink-0">
                                    <i data-lucide="check-circle" class="h-6 w-6 text-emerald-500"></i>
                                </div>
                                <p class="ml-3 text-base text-gray-600">Zero emissioni di CO2 nell'atmosfera locale</p>
                            </li>
                            <li class="flex items-start">
                                <div class="flex-shrink-0">
                                    <i data-lucide="check-circle" class="h-6 w-6 text-emerald-500"></i>
                                </div>
                                <p class="ml-3 text-base text-gray-600">Modello replicabile per altre aree industriali</p>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="servizi" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-extrabold text-gray-900">Le Nostre Soluzioni</h2>
                <p class="mt-4 text-lg text-gray-500">Sviluppiamo progetti su misura per il territorio piemontese.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Service 1 -->
                <div class="bg-white rounded-xl shadow-lg p-8 hover:shadow-2xl transition border-t-4 border-emerald-500">
                    <div class="h-12 w-12 bg-emerald-100 rounded-lg flex items-center justify-center mb-6 text-emerald-600">
                        <i data-lucide="factory" class="h-6 w-6"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">Tetti Industriali</h3>
                    <p class="text-gray-600 mb-6">
                        Valorizziamo i capannoni di Mappano e provincia. Trasformiamo le coperture inattive in fonti di reddito e risparmio energetico per le aziende.
                    </p>
                    <a href="#contatti" class="text-emerald-600 font-semibold hover:text-emerald-700 flex items-center">
                        Valuta il tuo tetto <i data-lucide="arrow-right" class="ml-2 h-4 w-4"></i>
                    </a>
                </div>

                <!-- Service 2 -->
                <div class="bg-white rounded-xl shadow-lg p-8 hover:shadow-2xl transition border-t-4 border-amber-500">
                    <div class="h-12 w-12 bg-amber-100 rounded-lg flex items-center justify-center mb-6 text-amber-600">
                        <i data-lucide="sun" class="h-6 w-6"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">Campi Fotovoltaici</h3>
                    <p class="text-gray-600 mb-6">
                        Installazioni a terra ad alta efficienza. Identifichiamo le aree idonee per massimizzare la produzione nel rispetto del paesaggio.
                    </p>
                    <a href="#contatti" class="text-amber-600 font-semibold hover:text-amber-700 flex items-center">
                        Scopri di più <i data-lucide="arrow-right" class="ml-2 h-4 w-4"></i>
                    </a>
                </div>

                <!-- Service 3 -->
                <div class="bg-white rounded-xl shadow-lg p-8 hover:shadow-2xl transition border-t-4 border-emerald-500">
                    <div class="h-12 w-12 bg-emerald-100 rounded-lg flex items-center justify-center mb-6 text-emerald-600">
                        <i data-lucide="sprout" class="h-6 w-6"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">Agrivoltaico</h3>
                    <p class="text-gray-600 mb-6">
                        Il futuro dell'agricoltura. Impianti che permettono la coltivazione sottostante, unendo produzione agricola ed energetica.
                    </p>
                    <a href="#contatti" class="text-emerald-600 font-semibold hover:text-emerald-700 flex items-center">
                        Soluzioni ibride <i data-lucide="arrow-right" class="ml-2 h-4 w-4"></i>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Vision / Future -->
    <section class="py-16 solar-gradient">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center text-white">
            <h2 class="text-3xl font-bold mb-6">Il nostro impegno per il territorio</h2>
            <p class="text-xl max-w-3xl mx-auto opacity-90 mb-8">
                Stiamo pianificando nuove installazioni nell'area di Torino Nord. 
                Se possiedi un terreno agricolo o un capannone industriale, sei un potenziale partner della transizione energetica.
            </p>
            <button class="bg-white text-emerald-700 px-8 py-3 rounded-full font-bold shadow-lg hover:bg-gray-100 transition">
                Proponi la tua area
            </button>
        </div>
    </section>

    <!-- Footer / Contact -->
    <footer id="contatti" class="bg-gray-900 text-white pt-16 pb-8">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
                <div>
                    <div class="flex items-center gap-2 mb-6">
                        <i data-lucide="sun" class="h-6 w-6 text-amber-500"></i>
                        <span class="font-bold text-2xl tracking-tight">FareLuce</span>
                    </div>
                    <p class="text-gray-400 mb-6">
                        Società specializzata in energie rinnovabili.<br>
                        Sede operativa e primo impianto: Mappano (TO).
                    </p>
                    <div class="space-y-4">
                        <div class="flex items-center text-gray-300">
                            <i data-lucide="map-pin" class="h-5 w-5 mr-3 text-emerald-500"></i>
                            Mappano (TO), Italia
                        </div>
                        <div class="flex items-center text-gray-300">
                            <i data-lucide="mail" class="h-5 w-5 mr-3 text-emerald-500"></i>
                            info@fareluce.net
                        </div>
                    </div>
                </div>
                
                <div class="bg-gray-800 p-6 rounded-xl">
                    <h3 class="text-xl font-bold mb-4 text-white">Contattaci per informazioni</h3>
                    <form onsubmit="event.preventDefault(); alert('Grazie! Messaggio simulato inviato.');" class="space-y-4">
                        <input type="text" placeholder="Nome o Azienda" class="w-full px-4 py-2 rounded bg-gray-700 border border-gray-600 text-white focus:outline-none focus:border-emerald-500">
                        <input type="email" placeholder="Email" class="w-full px-4 py-2 rounded bg-gray-700 border border-gray-600 text-white focus:outline-none focus:border-emerald-500">
                        <textarea rows="3" placeholder="Messaggio (es. ho un tetto disponibile)" class="w-full px-4 py-2 rounded bg-gray-700 border border-gray-600 text-white focus:outline-none focus:border-emerald-500"></textarea>
                        <button type="submit" class="w-full bg-emerald-600 hover:bg-emerald-700 text-white font-bold py-2 rounded transition">
                            Invia Richiesta
                        </button>
                    </form>
                </div>
            </div>
            <div class="border-t border-gray-800 mt-12 pt-8 text-center text-gray-500 text-sm">
                &copy; 2025 FareLuce. Tutti i diritti riservati.
            </div>
        </div>
    </footer>

    <script>
        // Initialize Lucide icons safely
        document.addEventListener('DOMContentLoaded', () => {
            if (typeof lucide !== 'undefined') {
                lucide.createIcons();
            } else {
                console.warn('Lucide library not loaded yet, retrying...');
                // Fallback: check every 100ms
                const checkLucide = setInterval(() => {
                    if (typeof lucide !== 'undefined') {
                        lucide.createIcons();
                        clearInterval(checkLucide);
                    }
                }, 100);
                // Stop trying after 5 seconds
                setTimeout(() => clearInterval(checkLucide), 5000);
            }
        });
    </script>
</body>
</html>
