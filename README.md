<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SLAUGHTERGANG // HAUNTED HOUSE BUSINESS PLAN</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Using clean, bold fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700;900&family=Poppins:wght@600;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    
    <style>
        /* CORE STYLES - DARK AMBIENT & RED CONTRAST */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0d0d0d; /* Dark ambient background */
            color: #ffffff;
            overflow-x: hidden;
            /* Subtle texture */
            background-image: radial-gradient(circle at center, #1a1a1a 1px, transparent 1px);
            background-size: 50px 50px;
        }

        /* ACCENT COLOR: BOLD RED */
        .text-accent-red {
            color: #E50000; /* Bold Red */
            text-shadow: 0 0 10px rgba(229, 0, 0, 0.5);
        }
        .border-accent-red {
            border-color: #E50000;
        }

        /* CARD STYLING - CLEAN, HIGH-CONTRAST */
        .data-card {
            background: #1f1f1f;
            border-bottom: 4px solid #333;
            transition: all 0.3s ease;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.5);
            border-radius: 0.5rem;
        }
        .data-card:hover {
            border-bottom-color: #E50000;
            box-shadow: 0 0 25px rgba(229, 0, 0, 0.4);
            transform: translateY(-4px);
        }
        
        /* CTA BUTTON - CLEAR AND COMMANDING */
        .cta-button {
            background: #E50000;
            color: #fff; /* White text on red */
            font-family: 'Poppins', sans-serif;
            font-weight: 800;
            transition: all 0.2s ease;
            box-shadow: 0 5px 20px rgba(229, 0, 0, 0.6);
        }
        .cta-button:hover {
            background: #FF3333;
            box-shadow: 0 5px 30px rgba(229, 0, 0, 0.8);
            transform: scale(1.02);
        }
    </style>
</head>
<body class="antialiased">
    
    <!-- HEADER / NAVIGATION (Clean and Simple) -->
    <header class="w-full bg-[#000000] border-b-2 border-accent-red sticky top-0 z-50 shadow-lg shadow-black/50">
        <div class="container mx-auto px-4 py-4 flex justify-between items-center max-w-7xl">
            <h1 class="text-xl md:text-3xl font-extrabold text-white leading-tight uppercase">
                SLAUGHTERGANG // FORTNITE BUSINESS BRIEF
            </h1>
            <!-- Removed #cta button as the section is now gone -->
        </div>
    </header>

    <!-- 1. TITLE & INTRODUCTION -->
    <section class="text-center py-20 md:py-32 flex items-center justify-center relative bg-[#0d0d0d]">
        <div class="relative z-10 max-w-7xl mx-auto px-4 space-y-8">
            
            <h2 class="text-6xl md:text-8xl font-black leading-none text-white uppercase tracking-tighter">
                <span class="text-accent-red block text-4xl md:text-5xl mb-4 tracking-wider font-extrabold">BUSINESS PLAN:</span>
                Slaughter Gang Haunted House
            </h2>
            
            <div class="flex items-center justify-center space-x-6 text-accent-red text-4xl">
                 <!-- Requested Icons for Intro -->
                <i class="fa-solid fa-house-chimney-crack"></i>
                <i class="fa-solid fa-gamepad"></i>
                <i class="fa-solid fa-dollar-sign"></i>
            </div>

            <p class="text-xl md:text-2xl text-gray-300 max-w-5xl mx-auto font-light leading-snug pt-6">
                Join 21 Savage in the digital world of Fortnite for an exclusive Slaughter Gang haunted house experience, blending music, virtual reality, and in-game assets for an unforgettable journey.
            </p>
        </div>
    </section>

    <!-- 2. REVENUE MODEL & MONETIZATION STRATEGY -->
    <section id="revenue" class="py-16 md:py-24 bg-[#141414] border-t border-b border-[#222]">
        <div class="container mx-auto max-w-5xl px-4 space-y-12">
            <h2 class="text-4xl md:text-5xl font-extrabold text-white text-center uppercase tracking-wide border-b-2 border-accent-red pb-4">
                REVENUE MODEL & STRATEGY
            </h2>
            
            <div class="grid md:grid-cols-2 gap-8">
                
                <!-- Revenue Model Card -->
                <div class="data-card p-6 md:p-8">
                    <div class="flex items-center space-x-4 mb-4 text-accent-red">
                        <i class="fa-solid fa-dollar-sign text-3xl"></i>
                        <i class="fa-solid fa-gem text-3xl"></i>
                        <i class="fa-solid fa-gamepad text-3xl"></i>
                    </div>
                    <h3 class="text-2xl font-bold text-white mb-2">Platform Monetization</h3>
                    <p class="text-gray-400">Fortnite allows creators to monetize maps and assets, with revenue shared based on in-game purchases within our map and high player engagement rates. Players can buy digital weapons, custom gear, and experience the haunted house.</p>
                </div>

                <!-- Monetization Strategy Card -->
                <div class="data-card p-6 md:p-8">
                    <div class="flex items-center space-x-4 mb-4 text-accent-red">
                        <i class="fa-solid fa-shirt text-3xl"></i>
                        <i class="fa-solid fa-music text-3xl"></i>
                        <i class="fa-solid fa-ticket text-3xl"></i>
                    </div>
                    <h3 class="text-2xl font-bold text-white mb-2">Core Revenue Streams</h3>
                    <p class="text-gray-400 font-semibold mb-2">Revenue generated from:</p>
                    <ul class="list-disc list-inside text-gray-400 ml-4 space-y-1">
                        <li>Exclusive Digital Assets (custom weapons, gear, music) purchased directly in the map.</li>
                        <li>Custom Tracks (collaborations with 21 Savage’s music)</li>
                        <li>Special Access Tickets for Haunted House Experience</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- 3. FINANCIALS: ESTIMATED REVENUE & COST -->
    <section id="financials" class="py-16 md:py-24 container mx-auto max-w-7xl px-4 space-y-12">
        <h2 class="text-4xl md:text-5xl font-extrabold text-white text-center uppercase tracking-wide border-b-2 border-accent-red pb-4">
            PROJECTED FINANCIAL SUMMARY
        </h2>

        <div class="grid md:grid-cols-2 gap-8 pt-8">
            
            <!-- Estimated Revenue -->
            <div class="data-card p-8 border-l-4 border-accent-red">
                <div class="flex items-center space-x-4 mb-4 text-accent-red">
                    <i class="fa-solid fa-chart-line text-4xl"></i>
                    <i class="fa-solid fa-sack-dollar text-4xl"></i>
                    <i class="fa-solid fa-headset text-4xl"></i>
                </div>
                <p class="text-sm font-bold uppercase text-gray-400">ESTIMATED ANNUAL REVENUE</p>
                <p class="text-5xl md:text-7xl font-extrabold text-white mt-2">$5,000,000</p>
                <p class="text-lg text-gray-300 mt-2 font-light">Projected through the sale of custom weapons, music tracks, and unique in-game gear in our map and high player engagement rates, maximizing the Creative payout pool.</p>
            </div>

            <!-- Upfront Cost -->
            <div class="data-card p-8 border-l-4 border-accent-red">
                <div class="flex items-center space-x-4 mb-4 text-accent-red">
                    <i class="fa-solid fa-credit-card text-4xl"></i>
                    <i class="fa-solid fa-calculator text-4xl"></i>
                    <i class="fa-solid fa-helmet-safety text-4xl"></i>
                </div>
                <p class="text-sm font-bold uppercase text-gray-400">YOUR INITIAL DEVELOPMENT COST</p>
                <p class="text-5xl md:text-7xl font-extrabold text-white mt-2">$2,500</p>
                <p class="text-lg text-gray-300 mt-2 font-light">Initial development cost for map creation, asset development, and marketing. This covers all upfront expenses.</p>
            </div>

        </div>
    </section>

    <!-- 4. GAME DESIGN & METRICS -->
    <section id="design" class="py-16 md:py-24 bg-[#141414] border-t border-b border-[#222]">
        <div class="container mx-auto max-w-5xl px-4 space-y-12">
            <h2 class="text-4xl md:text-5xl font-extrabold text-white text-center uppercase tracking-wide border-b-2 border-accent-red pb-4">
                GAME DESIGN & KEY GOALS
            </h2>
            
            <div class="grid md:grid-cols-2 gap-8">
                
                <!-- Game Design Overview -->
                <div class="data-card p-6 md:p-8">
                    <div class="flex items-center space-x-4 mb-4 text-accent-red">
                        <i class="fa-solid fa-house-chimney-crack text-3xl"></i>
                        <i class="fa-solid fa-gear text-3xl"></i>
                        <i class="fa-solid fa-music text-3xl"></i>
                    </div>
                    <h3 class="text-2xl font-bold text-white mb-2">Design Overview</h3>
                    <p class="text-gray-400">We will develop a Slaughter Gang themed haunted house with interactive elements, exclusive Easter eggs, and music from 21 Savage. Players can explore, purchase unique weapons and music tracks, and enjoy custom soundtracks.</p>
                </div>

                <!-- Key Metrics & Goals -->
                <div class="data-card p-6 md:p-8">
                    <div class="flex items-center space-x-4 mb-4 text-accent-red">
                        <i class="fa-solid fa-bullseye text-3xl"></i>
                        <i class="fa-solid fa-money-bill-wave text-3xl"></i>
                        <i class="fa-solid fa-user text-3xl"></i>
                    </div>
                    <h3 class="text-2xl font-bold text-white mb-2">Key Metrics & Targets</h3>
                    <p class="text-gray-400 font-semibold mb-2">Our targets for success are:</p>
                    <ul class="list-disc list-inside text-gray-400 ml-4 space-y-1">
                        <li>Target: 100,000+ active players in the first quarter.</li>
                        <li>Critical KPI: Maintain 40%+ Player Engagement Rate for maximum payout share.</li>
                        <li>Estimated Revenue per Player: $50 from custom music and unique assets.</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- 4.5. REQUIRED IP ASSETS: EXECUTION CHECKLIST (NEW SECTION) -->
    <section id="assets" class="py-16 md:py-24 container mx-auto max-w-7xl px-4 space-y-12">
        <h2 class="text-4xl md:text-5xl font-extrabold text-accent-red text-center uppercase tracking-wide border-b-2 border-accent-red pb-4">
            REQUIRED IP ASSETS: EXECUTION CHECKLIST
        </h2>

        <p class="text-xl text-gray-300 text-center font-light">
            To ensure the highest quality and compliance, we need these assets delivered digitally upon project initiation.
        </p>

        <div class="grid md:grid-cols-3 gap-8 pt-8">
            
            <!-- Asset 1: Audio & SFX -->
            <div class="data-card p-6 border-t-4 border-accent-red">
                <h3 class="text-2xl font-bold text-white mb-4 flex items-center"><i class="fa-solid fa-headphones-alt mr-3 text-accent-red"></i> AUDIO & SFX</h3>
                <ul class="list-disc list-inside text-gray-400 ml-4 space-y-2">
                    <li>Custom Sound Loops: Ambient music tracks for in-game zones (3-5 required).</li>
                    <li>Signature Ad-libs/SFX: Clear recordings of 21 Savage's signature phrases or 'scare' sounds (WAV format preferred).</li>
                    <li>Licensed Music Files: Master audio files for tracks approved for in-game placement.</li>
                </ul>
            </div>

            <!-- Asset 2: Visuals & Imagery -->
            <div class="data-card p-6 border-t-4 border-accent-red">
                <h3 class="text-2xl font-bold text-white mb-4 flex items-center"><i class="fa-solid fa-palette mr-3 text-accent-red"></i> VISUALS & IMAGERY</h3>
                <ul class="list-disc list-inside text-gray-400 ml-4 space-y-2">
                    <li>Logos: High-resolution 'Slaughter Gang' logos (PNG/Vector) for in-game branding.</li>
                    <li>Character Renders: High-res photos or 3D renders of the specific masks, chains, or cosmetic items we plan to sell. (Note: These are for environment/gear assets, not skins)</li>
                    <li>2D Art: Any approved textures, graffiti, or exclusive artwork for environment design.</li>
                </ul>
            </div>

            <!-- Asset 3: Branding & Legal -->
            <div class="data-card p-6 border-t-4 border-accent-red">
                <h3 class="text-2xl font-bold text-white mb-4 flex items-center"><i class="fa-solid fa-gavel mr-3 text-accent-red"></i> BRANDING & LEGAL</h3>
                <ul class="list-disc list-inside text-gray-400 ml-4 space-y-2">
                    <li>Style Guide: Formal brand identity guide (color palettes, font use, tone) to maintain consistency.</li>
                    <li>IP Clearance: Formal written approval and legal sign-off for use of all intellectual property in the Epic Games ecosystem.</li>
                    <li>Approved Marketing Visuals: Core promotional imagery for launch assets.</li>
                </ul>
            </div>

        </div>
    </section>

    <!-- 5. GLOBAL MARKETING & SOCIAL STRATEGY (NEW SECTION) -->
    <section id="marketing" class="py-16 md:py-24 bg-[#141414] border-t border-b border-[#222]">
        <div class="container mx-auto max-w-7xl px-4 space-y-12">
            <h2 class="text-4xl md:text-5xl font-extrabold text-accent-red text-center uppercase tracking-wide border-b-2 border-accent-red pb-4">
                GLOBAL MARKETING & SOCIAL STRATEGY
            </h2>

            <p class="text-xl text-gray-300 text-center font-light">
                Leveraging 21 Savage's substantial reach is critical. The strategy focuses on high-impact, authentic content releases synchronized with the game's official launch and updates.
            </p>

            <div class="grid md:grid-cols-4 gap-6 pt-8">
                
                <!-- Platform 1: Instagram -->
                <div class="data-card p-6 border-l-4 border-accent-red">
                    <h3 class="text-2xl font-bold text-white mb-3 flex items-center"><i class="fa-brands fa-instagram mr-3 text-accent-red"></i> INSTAGRAM</h3>
                    <ul class="list-disc list-inside text-gray-400 ml-4 space-y-2 text-sm">
                        <li>Launch Day Reels: Short, high-energy videos showing 21 Savage's avatar performing an exclusive emote.</li>
                        <li>Digital Asset Drops: Stories featuring individual custom weapons or gear with direct purchase links.</li>
                        <li>Countdown & Teasers: Use dark, mysterious visuals for build-up content 7 days prior to launch.</li>
                    </ul>
                </div>

                <!-- Platform 2: Twitter/X -->
                <div class="data-card p-6 border-l-4 border-accent-red">
                    <h3 class="text-2xl font-bold text-white mb-3 flex items-center"><i class="fa-brands fa-x-twitter mr-3 text-accent-red"></i> TWITTER / X</h3>
                    <ul class="list-disc list-inside text-gray-400 ml-4 space-y-2 text-sm">
                        <li>Code Drop: Announce the Fortnite Island Code 30 minutes before launch to generate immediate traffic.</li>
                        <li>Retweet Incentives: Run a giveaway for a free exclusive music track or custom weapon for retweeting the launch announcement.</li>
                        <li>Direct Callouts: Tag Fortnite/Epic Games to maximize visibility and co-promotion opportunities.</li>
                    </ul>
                </div>
                
                <!-- Platform 3: TikTok -->
                <div class="data-card p-6 border-l-4 border-accent-red">
                    <h3 class="text-2xl font-bold text-white mb-3 flex items-center"><i class="fa-brands fa-tiktok mr-3 text-accent-red"></i> TIKTOK</h3>
                    <ul class="list-disc list-inside text-gray-400 ml-4 space-y-2 text-sm">
                        <li>Custom Music Clips: Use a new, custom 15-second music loop (from the map) to start a sound trend.</li>
                        <li>Duet Challenges: Challenge users to duet a reaction video to being "scared" inside the virtual haunted house.</li>
                        <li>Influencer Seeding: Distribute early access keys to top Fortnite/Gaming TikTok creators.</li>
                    </ul>
                </div>

                <!-- Platform 4: Twitch/Streaming -->
                <div class="data-card p-6 border-l-4 border-accent-red">
                    <h3 class="text-2xl font-bold text-white mb-3 flex items-center"><i class="fa-brands fa-twitch mr-3 text-accent-red"></i> TWITCH / STREAMS</h3>
                    <ul class="list-disc list-inside text-gray-400 ml-4 space-y-2 text-sm">
                        <li>Launch Stream: 21 Savage hosts a live stream playing the map with popular Fortnite streamers.</li>
                        <li>Twitch Drops: Integrate a system where watching the stream for a set time unlocks a free in-game reward.</li>
                        <li>Map Showcase: Streamers are contracted to feature the map exclusively for the first 48 hours of launch.</li>
                    </ul>
                </div>

            </div>
        </div>
    </section>

    <footer class="text-center py-6 border-t border-[#1a1a1a] bg-[#000000]">
        <p class="text-gray-600 text-sm font-light">
            SLAUGHTERGANG PARTNERSHIP BRIEF // END OF DOCUMENT
        </p>
    </footer>

</body>
</html>
