<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AETHER | Engineering Beyond Gravity</title>
    <!-- Tailwind CSS for Layout & Styling -->
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <!-- GSAP for Smooth 3D Floating & Animations -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/gsap.min.js"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Cinzel:wght@400;600;700&family=Inter:wght@300;400;500&display=swap');
        
        body {
            font-family: 'Inter', sans-serif;
            background-color: #050505;
            color: #e5e5e5;
            overflow-x: hidden;
        }
        .font-serif-lux { font-family: 'Cinzel', serif; }
        
        /* Smooth glowing effects */
        .gold-glow {
            text-shadow: 0 0 12px rgba(212, 175, 55, 0.3);
        }
        .border-gold { border-color: rgba(212, 175, 55, 0.4); }
        .text-gold { color: #d4af37; }
        
        /* Section transition style */
        .page-section {
            display: none;
            opacity: 0;
            transition: opacity 0.5s ease-in-out;
        }
        .page-section.active {
            display: block;
            opacity: 1;
        }
    </style>
</head>
<body class="relative min-h-screen">

    <!-- Background Image Layer with Depth Filter -->
    <div class="absolute inset-0 z-0 bg-cover bg-center bg-no-repeat opacity-40 mix-blend-luminosity pointer-events-none" 
         style="background-image: url('https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=1920&q=80'); filter: blur(2px) brightness(0.3);">
    </div>

    <!-- Header / Navigation -->
    <header class="fixed top-0 left-0 w-full z-50 px-6 py-4 md:px-12 flex justify-between items-center backdrop-blur-md bg-black/20 border-b border-white/5">
        <div class="text-xl md:text-2xl font-serif-lux tracking-widest text-white gold-glow font-bold">AETHER</div>
        
        <nav class="hidden md:flex space-x-8 text-xs tracking-widest uppercase font-medium text-gray-400">
            <button onclick="switchPage('home')" class="nav-btn text-white hover:text-white transition">Home</button>
            <button onclick="switchPage('about')" class="nav-btn hover:text-white transition">About</button>
            <button onclick="switchPage('services')" class="nav-btn hover:text-white transition">Services</button>
        </nav>

        <button onclick="switchPage('about')" class="border border-gold text-gold text-xs uppercase tracking-widest px-5 py-2 hover:bg-amber-500/10 transition-all rounded-sm font-semibold">
            Contact
        </button>
    </header>

    <!-- Social Sidebar (Hidden on mobile) -->
    <div class="fixed left-6 top-1/2 -translate-y-1/2 z-40 hidden flex-col space-y-6 text-gray-500 text-sm xl:flex">
        <a href="#" class="hover:text-amber-400 transition">IG</a>
        <a href="#" class="hover:text-amber-400 transition">LN</a>
        <a href="#" class="hover:text-amber-400 transition">GH</a>
    </div>

    <main class="relative z-10 pt-24 min-h-screen flex flex-col justify-between">
        
        <!-- ================= HOME SECTION ================= -->
        <section id="home" class="page-section active px-6 md:px-24 py-8">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center min-h-[70vh]">
                
                <!-- Left Content Column -->
                <div class="lg:col-span-5 flex flex-col justify-center space-y-6 z-20 order-2 lg:order-1">
                    <p class="text-xs uppercase tracking-[0.3em] text-amber-500/80 font-semibold font-serif-lux">Engineering Beyond Gravity</p>
                    <h1 class="text-5xl md:text-7xl font-serif-lux font-bold tracking-tight text-white leading-none">
                        AETHER
                    </h1>
                    <p class="text-gray-400 text-sm md:text-base max-w-sm leading-relaxed font-light">
                        Where engineering meets art. Defying limits. Redefining luxury. Experience structural automotive handling inside curated luxury spaces.
                    </p>
                    <div class="flex items-center space-x-6 pt-4">
                        <button onclick="switchPage('services')" class="border border-white text-white text-xs uppercase tracking-widest px-8 py-3.5 hover:bg-white hover:text-black transition-all font-medium">
                            Explore
                        </button>
                        <a href="#" class="flex items-center space-x-3 text-xs uppercase tracking-widest text-gray-300 hover:text-amber-400 transition font-medium">
                            <span class="w-8 h-8 rounded-full border border-white/20 flex items-center justify-center text-[10px]">▶</span>
                            <span>Watch Showreel</span>
                        </a>
                    </div>
                </div>

                <!-- Right 3D Interactive Floating Car Container -->
                <div class="lg:col-span-7 flex justify-center items-center relative min-h-[400px] lg:min-h-[550px] order-1 lg:order-2">
                    <!-- Subtle background light flare behind the vehicle -->
                    <div class="absolute w-72 h-72 md:w-96 md:h-96 bg-amber-500/10 rounded-full blur-[100px] pointer-events-none"></div>
                    
                    <!-- Floating Wrapper controlled by GSAP -->
                    <div id="floating-car-container" class="relative w-full max-w-lg md:max-w-xl cursor-pointer perspective-1000 transform transition-transform duration-300">
                        <!-- Structural Suspension Line Visuals -->
                        <div class="absolute top-[-100px] left-1/4 w-[1px] h-[150px] bg-gradient-to-b from-transparent to-amber-500/40"></div>
                        <div class="absolute top-[-150px] right-1/3 w-[1px] h-[180px] bg-gradient-to-b from-transparent to-amber-500/40"></div>
                        
                        <!-- High-Quality Transparent Background Vehicle -->
                        <img id="car-image" src="https://images.unsplash.com/photo-1614162692292-7ac56d7f7f1e?auto=format&fit=crop&w=1000&q=80" 
                             alt="Suspended Supercar" 
                             class="w-full h-auto object-contain drop-shadow-[0_35px_35px_rgba(0,0,0,0.8)] rounded-xl border border-white/10 mix-blend-lighten">
                        
                        <!-- Mini dynamic tag on vehicle -->
                        <div class="absolute bottom-4 right-4 bg-black/80 backdrop-blur-md border border-gold/30 text-[9px] tracking-widest uppercase text-gold px-3 py-1 rounded">
                            SUSPENSION ACTIVE // 01
                        </div>
                    </div>
                </div>

            </div>

            <!-- Bottom Features Bar -->
            <div class="grid grid-cols-2 md:grid-cols-4 gap-6 border-t border-white/10 pt-8 mt-12 text-center md:text-left">
                <div>
                    <h4 class="text-xs font-serif-lux uppercase tracking-wider text-amber-500 font-bold">Precision</h4>
                    <p class="text-xs text-gray-500 mt-1">Every detail is meticulously crafted.</p>
                </div>
                <div>
                    <h4 class="text-xs font-serif-lux uppercase tracking-wider text-amber-500 font-bold">Innovation</h4>
                    <p class="text-xs text-gray-500 mt-1">Pushing technology to the next level.</p>
                </div>
                <div>
                    <h4 class="text-xs font-serif-lux uppercase tracking-wider text-amber-500 font-bold">Excellence</h4>
                    <p class="text-xs text-gray-500 mt-1">Committed to delivering high quality.</p>
                </div>
                <div>
                    <h4 class="text-xs font-serif-lux uppercase tracking-wider text-amber-500 font-bold">Passion</h4>
                    <p class="text-xs text-gray-500 mt-1">Driven by passion, inspired by dreams.</p>
                </div>
            </div>
        </section>


        <!-- ================= ABOUT SECTION ================= -->
        <section id="about" class="page-section px-6 md:px-24 py-12 max-w-4xl mx-auto text-center">
            <h2 class="text-3xl md:text-5xl font-serif-lux text-white tracking-widest mb-6">ABOUT AETHER</h2>
            <p class="text-gray-400 leading-relaxed text-sm md:text-base mb-8 max-w-2xl mx-auto font-light">
                AETHER transforms high-performance automobiles into suspended architectural art pieces inside elite residences. By engineering bespoke zero-stress rigging configurations, we float luxury vehicles within multi-story halls, glass atriums, and living spaces securely.
            </p>
            <div class="inline-block p-6 bg-white/5 border border-white/10 backdrop-blur-md rounded max-w-sm text-left">
                <div class="flex items-center space-x-4 mb-3">
                    <div class="w-12 h-12 rounded-full bg-amber-500/20 border border-gold flex items-center justify-center font-serif-lux text-white">BA</div>
                    <div>
                        <h4 class="text-sm font-bold text-white tracking-wide">BIBI AMEENA</h4>
                        <p class="text-xs text-amber-400">Lead Creator / UI Developer</p>
                    </div>
                </div>
                <p class="text-xs text-gray-400 leading-relaxed">
                    Crafting immersive, lightning-fast digital showrooms featuring advanced layout mechanics and responsive structures.
                </p>
            </div>
        </section>


        <!-- ================= SERVICES SECTION ================= -->
        <section id="services" class="page-section px-6 md:px-24 py-12">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-5xl font-serif-lux text-white tracking-widest">OUR EXPERTISE</h2>
                <p class="text-xs text-amber-500 uppercase tracking-widest mt-2">What we deliver</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6 max-w-5xl mx-auto">
                <div class="bg-gradient-to-b from-white/5 to-transparent p-8 border border-white/10 rounded hover:border-gold/50 transition duration-300">
                    <span class="text-2xl text-gold">✦</span>
                    <h3 class="text-lg font-serif-lux text-white tracking-wider mt-4 mb-2">Automotive Rigging</h3>
                    <p class="text-xs text-gray-400 leading-relaxed">Structural design engineered to hold sports cars flawlessly inside complex residential ceilings.</p>
                </div>
                <div class="bg-gradient-to-b from-white/5 to-transparent p-8 border border-white/10 rounded hover:border-gold/50 transition duration-300">
                    <span class="text-2xl text-gold">✦</span>
                    <h3 class="text-lg font-serif-lux text-white tracking-wider mt-4 mb-2">Spatial Architecture</h3>
                    <p class="text-xs text-gray-400 leading-relaxed">Designing modern luxury interiors that balance structural safety with elite museum aesthetics.</p>
                </div>
                <div class="bg-gradient-to-b from-white/5 to-transparent p-8 border border-white/10 rounded hover:border-gold/50 transition duration-300">
                    <span class="text-2xl text-gold">✦</span>
                    <h3 class="text-lg font-serif-lux text-white tracking-wider mt-4 mb-2">Dynamic Lighting</h3>
                    <p class="text-xs text-gray-400 leading-relaxed">Tailored illumination setups highlighting structural lines, accentuating your asset seamlessly.</p>
                </div>
            </div>
        </section>

        <!-- Footer Footer -->
        <footer class="w-full text-center py-6 text-[10px] text-gray-600 tracking-widest uppercase border-t border-white/5 mt-auto">
            © 2026 AETHER. All Rights Reserved.
        </footer>
    </main>

    <!-- JavaScript For Interactivity, Pages, and 3D floating -->
    <script>
        // 1. Navigation Controller (Switches between home, about, services tabs seamlessly)
        function switchPage(pageId) {
            // Hide all pages
            document.querySelectorAll('.page-section').forEach(section => {
                section.classList.remove('active');
            });
            // Show selected page
            const activeSection = document.getElementById(pageId);
            if(activeSection) {
                activeSection.classList.add('active');
            }
            
            // Subtle transition stagger on layout entry using GSAP
            gsap.fromTo(`#${pageId}`, { opacity: 0, y: 15 }, { opacity: 1, y: 0, duration: 0.6, ease: "power2.out" });
        }

        // 2. GSAP Floating Physics Engine (Simulates zero-gravity float)
        gsap.to("#floating-car-container", {
            y: -18,
            rotationZ: 1.5,
            rotationX: 3,
            duration: 4,
            ease: "sine.inOut",
            yoyo: true,
            repeat: -1
        });

        // 3. Mouse Move Parallax Interaction (Provides a interactive pseudo-3D parallax effect)
        const elementContainer = document.getElementById('floating-car-container');
        
        window.addEventListener('mousemove', (e) => {
            const xAxis = (window.innerWidth / 2 - e.pageX) / 25;
            const yAxis = (window.innerHeight / 2 - e.pageY) / 25;
            
            gsap.to(elementContainer, {
                rotationY: xAxis,
                rotationX: -yAxis,
                duration: 0.8,
                ease: "power1.out"
            });
        });

        // Reset rotation gracefully when mouse leaves window frame
        window.addEventListener('mouseleave', () => {
            gsap.to(elementContainer, {
                rotationY: 0,
                rotationX: 0,
                duration: 1.2,
                ease: "power2.out"
            });
        });
    </script>
</body>
</html>
