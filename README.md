<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MealMate | Eat. Speak. Belong.</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,100..900;1,9..144,100..900&family=Outfit:wght@100..900&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Outfit', sans-serif; background-color: #FDFBF7; }
        h1, h2, h3, .serif { font-family: 'Fraunces', serif; }
        .bg-saffron { background-color: #F4A261; }
        .text-saffron { color: #F4A261; }
        .bg-sage { background-color: #8DAA91; }
        .hero-gradient { background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)), url('https://images.unsplash.com/photo-1552566626-52f8b828add9?auto=format&fit=crop&w=1600&q=80'); background-size: cover; background-position: center; }
    </style>
</head>
<body class="text-stone-800">

    <nav class="flex items-center justify-between px-8 py-6 max-w-7xl mx-auto">
        <div class="text-2xl font-bold flex items-center gap-2">
            <span class="bg-saffron text-white p-2 rounded-lg">M</span>
            <span class="serif tracking-tight text-2xl">MealMate</span>
        </div>
        <div class="hidden md:flex gap-8 font-medium text-stone-600">
            <a href="#" class="hover:text-saffron transition">Browse Locals</a>
            <a href="#" class="hover:text-saffron transition">How it Works</a>
            <a href="#" class="hover:text-saffron transition">Safety</a>
        </div>
        <button class="bg-stone-900 text-white px-6 py-2 rounded-full font-semibold hover:bg-stone-700 transition">
            Join the Table
        </button>
    </nav>

    <header class="hero-gradient h-[80vh] flex items-center justify-center text-center px-4 rounded-3xl mx-4 mb-12">
        <div class="max-w-3xl">
            <h1 class="text-5xl md:text-7xl text-white mb-6">Stop Studying.<br>Start Dining.</h1>
            <p class="text-xl text-stone-100 mb-8 font-light">Master a new language over a real meal. You bring the appetite; they bring the immersion. No classrooms, just connections.</p>
            
            <div class="bg-white p-2 rounded-full shadow-xl flex flex-col md:flex-row gap-2 max-w-2xl mx-auto">
                <input type="text" placeholder="What language?" class="flex-1 px-6 py-3 rounded-full focus:outline-none">
                <input type="text" placeholder="Which city?" class="flex-1 px-6 py-3 rounded-full focus:outline-none border-l border-gray-100">
                <button class="bg-saffron text-white px-8 py-3 rounded-full font-bold hover:opacity-90 transition">
                    Find a Table
                </button>
            </div>
        </div>
    </header>

    <section class="max-w-7xl mx-auto px-8 py-20">
        <h2 class="text-4xl text-center mb-16 italic">How we set the table</h2>
        <div class="grid md:grid-cols-3 gap-12 text-center">
            <div>
                <div class="text-4xl mb-4">📖</div>
                <h3 class="text-2xl mb-3">Browse the Menu</h3>
                <p class="text-stone-500">Find verified native speakers who share your interests—from street food lovers to fine-dining critics.</p>
            </div>
            <div>
                <div class="text-4xl mb-4">📅</div>
                <h3 class="text-2xl mb-3">Set the Date</h3>
                <p class="text-stone-500">Send an invite to your favorite local spot. Once they accept, the reservation (and your lesson) is set.</p>
            </div>
            <div>
                <div class="text-4xl mb-4">🍝</div>
                <h3 class="text-2xl mb-3">Dig In</h3>
                <p class="text-stone-500">You cover the bill, they provide the practice. It’s the most delicious "class" you’ll ever have.</p>
            </div>
        </div>
    </section>

    <section class="bg-stone-100 py-20 px-8">
        <div class="max-w-7xl mx-auto">
            <div class="flex justify-between items-end mb-12">
                <div>
                    <h2 class="text-4xl mb-2">Today’s Specials</h2>
                    <p class="text-stone-500">Native hosts available in your area</p>
                </div>
                <a href="#" class="text-saffron font-bold border-b-2 border-saffron">View all locals</a>
            </div>

            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-white rounded-2xl overflow-hidden shadow-sm hover:shadow-md transition cursor-pointer">
                    <img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?auto=format&fit=crop&w=800&q=80" class="h-64 w-full object-cover">
                    <div class="p-6">
                        <div class="flex justify-between items-start mb-2">
                            <h3 class="text-xl font-bold">Mateo, 23</h3>
                            <span class="bg-stone-100 text-xs px-2 py-1 rounded">Spanish</span>
                        </div>
                        <p class="text-stone-600 text-sm mb-4">"Let's talk about news over the best tacos in the city."</p>
                        <div class="flex gap-2">
                            <span class="text-[10px] uppercase tracking-widest bg-orange-50 text-orange-700 px-2 py-1 rounded">Beginner Friendly</span>
                        </div>
                    </div>
                </div>

                <div class="bg-white rounded-2xl overflow-hidden shadow-sm hover:shadow-md transition cursor-pointer">
                    <img src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?auto=format&fit=crop&w=800&q=80" class="h-64 w-full object-cover">
                    <div class="p-6">
                        <div class="flex justify-between items-start mb-2">
                            <h3 class="text-xl font-bold">Aiko, 21</h3>
                            <span class="bg-stone-100 text-xs px-2 py-1 rounded">Japanese</span>
                        </div>
                        <p class="text-stone-600 text-sm mb-4">"Looking for a ramen buddy. I love talking about J-Pop and design!"</p>
                        <div class="flex gap-2">
                            <span class="text-[10px] uppercase tracking-widest bg-orange-50 text-orange-700 px-2 py-1 rounded">Advanced</span>
                        </div>
                    </div>
                </div>

                <div class="bg-white rounded-2xl overflow-hidden shadow-sm hover:shadow-md transition cursor-pointer">
                    <img src="https://images.unsplash.com/photo-1539571696357-5a69c17a67c6?auto=format&fit=crop&w=800&q=80" class="h-64 w-full object-cover">
                    <div class="p-6">
                        <div class="flex justify-between items-start mb-2">
                            <h3 class="text-xl font-bold">Julian, 19</h3>
                            <span class="bg-stone-100 text-xs px-2 py-1 rounded">French</span>
                        </div>
                        <p class="text-stone-600 text-sm mb-4">"Casual French conversation. I know the best wine bars in town."</p>
                        <div class="flex gap-2">
                            <span class="text-[10px] uppercase tracking-widest bg-orange-50 text-orange-700 px-2 py-1 rounded">Intermediate</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="py-20 text-center max-w-4xl mx-auto px-8">
        <div class="bg-sage text-white p-12 rounded-3xl">
            <h2 class="text-3xl mb-6">A Safe Seat for Everyone</h2>
            <div class="grid md:grid-cols-2 gap-8 text-left text-sm">
                <div class="flex gap-4">
                    <span class="text-xl">✅</span>
                    <p><strong>Verified Palates:</strong> Every member is ID-verified before their first meal.</p>
                </div>
                <div class="flex gap-4">
                    <span class="text-xl">🤝</span>
                    <p><strong>Dual Consent:</strong> No meeting happens until both parties say "Yes."</p>
                </div>
            </div>
            <button class="mt-10 bg-white text-stone-900 px-8 py-3 rounded-full font-bold hover:bg-stone-100 transition">
                Learn about Safety
            </button>
        </div>
    </section>

    <footer class="border-t border-stone-200 py-12 text-center text-stone-400 text-sm">
        <p>&copy; 2026 MealMate. Eat. Speak. Belong.</p>
    </footer>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mateo's Profile | MealMate</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,100..900;1,9..144,100..900&family=Outfit:wght@100..900&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Outfit', sans-serif; background-color: #FDFBF7; }
        h1, h2, h3, .serif { font-family: 'Fraunces', serif; }
        .bg-saffron { background-color: #F4A261; }
        .text-saffron { color: #F4A261; }
        .border-saffron { border-color: #F4A261; }
    </style>
</head>
<body class="text-stone-800">

    <nav class="p-6 max-w-7xl mx-auto flex justify-between items-center">
        <a href="#" class="serif text-xl font-bold flex items-center gap-2">
            <span class="bg-saffron text-white px-2 rounded">M</span> MealMate
        </a>
        <a href="#" class="text-stone-500 hover:text-stone-800 transition">← Back to Search</a>
    </nav>

    <main class="max-w-5xl mx-auto px-6 py-10 grid md:grid-cols-3 gap-12">
        
        <div class="md:col-span-1">
            <div class="sticky top-10">
                <div class="relative">
                    <img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?auto=format&fit=crop&w=800&q=80" 
                         class="w-full aspect-square object-cover rounded-3xl shadow-lg mb-6">
                    <span class="absolute bottom-4 right-4 bg-green-500 text-white text-xs px-3 py-1 rounded-full border-2 border-white flex items-center gap-1">
                        ● Online
                    </span>
                </div>
                
                <h1 class="text-4xl mb-1">Mateo, 23</h1>
                <p class="text-stone-500 mb-6 flex items-center gap-2">
                    📍 Madrid, Spain • <span class="text-saffron font-bold">Native Speaker</span>
                </p>

                <div class="space-y-4 mb-8">
                    <div class="flex items-center gap-3 text-sm text-stone-600">
                        <span class="w-8 h-8 flex items-center justify-center bg-stone-100 rounded-full">🛡️</span>
                        Identity Verified
                    </div>
                    <div class="flex items-center gap-3 text-sm text-stone-600">
                        <span class="w-8 h-8 flex items-center justify-center bg-stone-100 rounded-full">⭐</span>
                        4.9 Rating (24 Meals)
                    </div>
                    <div class="flex items-center gap-3 text-sm text-stone-600">
                        <span class="w-8 h-8 flex items-center justify-center bg-stone-100 rounded-full">💬</span>
                        Responds in < 1 hour
                    </div>
                </div>

                <button class="w-full bg-saffron text-white py-4 rounded-2xl font-bold shadow-lg shadow-orange-200 hover:scale-[1.02] transition">
                    Send Dinner Invite
                </button>
            </div>
        </div>

        <div class="md:col-span-2 space-y-12">
            
            <section>
                <h2 class="text-2xl mb-4 italic">The Secret Ingredient</h2>
                <p class="text-stone-600 leading-relaxed text-lg">
                    Hola! I'm an comm students by day and a street-food explorer by night. I believe the best way to learn Spanish isn't through a textbook, but through stories told over a great plate of food. Whether you're just learning "Hola", I'm your guy.
                </p>
            </section>

            <hr class="border-stone-200">

            <section>
                <h2 class="text-2xl mb-6 italic">Topics on the Table</h2>
                <div class="flex flex-wrap gap-3">
                    <span class="px-4 py-2 bg-stone-100 rounded-full text-sm font-medium">🏙️ News Around The World</span>
                    <span class="px-4 py-2 bg-stone-100 rounded-full text-sm font-medium">⚽ Real Madrid Lore</span>
                    <span class="px-4 py-2 bg-stone-100 rounded-full text-sm font-medium">🥘 Finding Secret Tapas Spots</span>
                    <span class="px-4 py-2 bg-stone-100 rounded-full text-sm font-medium">✈️ Backpacking Latin America</span>
                    <span class="px-4 py-2 bg-stone-100 rounded-full text-sm font-medium">🎬 Pedro Almodóvar Films</span>
                </div>
            </section>

            <section>
                <h2 class="text-2xl mb-6 italic">What others are saying</h2>
                <div class="space-y-6">
                    <div class="bg-white p-6 rounded-2xl border border-stone-100">
                        <div class="flex justify-between mb-3">
                            <span class="font-bold">Sarah, 21</span>
                            <span class="text-yellow-500 text-xs">★★★★★</span>
                        </div>
                        <p class="text-stone-500 text-sm">"Mateo was so patient! We went to the DLB canteen and he helped me order in Spanish. His stories about the city buildings are fascinating."</p>
                    </div>

                    <div class="bg-white p-6 rounded-2xl border border-stone-100">
                        <div class="flex justify-between mb-3">
                            <span class="font-bold">Liam, 19</span>
                            <span class="text-yellow-500 text-xs">★★★★★</span>
                        </div>
                        <p class="text-stone-500 text-sm">"Great energy. We spent 2 hours talking about football. I learned more slang in one meal than in 3 months of Duolingo."</p>
                    </div>
                </div>
            </section>

            <section class="bg-orange-50 p-6 rounded-2xl border border-orange-100">
                <h3 class="font-bold text-orange-800 mb-2">Mateo's Favorite Spots</h3>
                <p class="text-orange-700 text-sm">Usually prefers: Malasaña, Chueca, or City Center.</p>
            </section>

        </div>
    </main>

    <footer class="py-20 text-center text-stone-400 text-xs">
        <p>Report Profile • Safety Guidelines • MealMate 2026</p>
    </footer>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>It's a Date! | MealMate Confirmation</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,100..900;1,9..144,100..900&family=Outfit:wght@100..900&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Outfit', sans-serif; background-color: #FDFBF7; }
        h1, h2, h3, .serif { font-family: 'Fraunces', serif; }
        .bg-saffron { background-color: #F4A261; }
        .success-card { animation: slideUp 0.6s ease-out; }
        @keyframes slideUp {
            from { transform: translateY(20px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
    </style>
</head>

<body class="text-stone-800 min-h-screen flex flex-col items-center justify-center p-4 md:p-8">

    <div class="mb-8 text-center w-full">
        <div class="inline-block bg-green-100 text-green-600 p-4 rounded-full mb-4 animate-bounce">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="3" d="M5 13l4 4L19 7" />
            </svg>
        </div>
        <h1 class="text-4xl md:text-5xl serif italic leading-tight">The table is set!</h1>
        <p class="text-stone-500 mt-2">Mateo has accepted your invite. Get your appetite ready.</p>
    </div>

    <div class="success-card bg-white w-full max-w-md mx-auto rounded-[2.5rem] shadow-2xl overflow-hidden border border-stone-100">
        
        <div class="bg-saffron p-6 text-white flex items-center justify-between">
            <div>
                <p class="text-[10px] uppercase tracking-[0.2em] opacity-80 font-bold">Language Immersion</p>
                <h2 class="text-2xl font-bold">Spanish & Tapas</h2>
            </div>
            <div class="text-right">
                <p class="text-[10px] uppercase tracking-[0.2em] opacity-80 font-bold"></p>
                <p class="text-xl font-bold"></p>
            </div>
        </div>

        <div class="p-8 space-y-8">
            <div class="flex items-center gap-4">
                <img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?auto=format&fit=crop&w=100&q=80" 
                     class="w-16 h-16 rounded-full object-cover ring-4 ring-stone-50 shadow-sm">
                <div>
                    <h3 class="font-bold text-lg leading-tight">Dining with Mateo</h3>
                    <p class="text-stone-400 text-sm italic">"Let's talk about Spanish!"</p>
                </div>
            </div>

            <hr class="border-dashed border-stone-200">

            <div class="grid grid-cols-2 gap-6">
                <div>
                    <p class="text-[10px] uppercase text-stone-400 font-bold tracking-widest mb-1">When</p>
                    <p class="font-bold text-stone-700">Friday, March 20</p>
                    <p class="text-sm text-stone-500">1:30 PM</p>
                </div>
                <div>
                    <p class="text-[10px] uppercase text-stone-400 font-bold tracking-widest mb-1">Where</p>
                    <p class="font-bold text-stone-700">H.F.C.@SCHOLARS COURT</p>
                    <p class="text-sm text-stone-500 truncate"></p>
                </div>
            </div>

            <hr class="border-dashed border-stone-200">

            <div class="bg-stone-50 p-5 rounded-2xl">
                <h4 class="text-sm font-bold mb-3 flex items-center gap-2">
                    🍽️ Your Prep-List
                </h4>
                <ul class="text-xs space-y-2 text-stone-500 font-medium">
                    <li class="flex items-start gap-2 italic">
                        <span>•</span> Bring 3 questions about Madrid.
                    </li>
                    <li class="flex items-start gap-2 italic">
                        <span>•</span> Check in on the app when you arrive.
                    </li>
                    <li class="flex items-start gap-2 italic">
                        <span>•</span> Remember: You cover the meal cost!
                    </li>
                </ul>
            </div>
        </div>

        <div class="p-6 bg-stone-100 flex gap-3">
            <button class="flex-1 bg-stone-900 text-white py-4 rounded-2xl font-bold hover:bg-stone-700 transition shadow-lg shadow-stone-200 text-sm">
                Add to Calendar
            </button>
            <button class="flex-1 border border-stone-200 bg-white py-4 rounded-2xl font-bold hover:bg-stone-50 transition text-sm">
                Message Mateo
            </button>
        </div>
    </div>

    <p class="mt-8 text-stone-400 text-[10px] text-center max-w-xs mx-auto">
        Need to cancel? Do so at least 24 hours before to avoid a fee. 
        <br>
        <a href="#" class="underline hover:text-stone-600 font-bold">Safety Center</a>
    </p>

</body>
</html>


</body>
</html>


<div class="max-w-md mx-auto bg-stone-900 text-white rounded-[2rem] p-8 shadow-2xl mt-12">
    <div class="flex justify-between items-start mb-8">
        <div>
            <p class="text-xs uppercase tracking-widest text-stone-400">MealMate Status</p>
            <h3 class="text-2xl serif">Main Course (Lv.10)</h3>
        </div>
        <span class="bg-saffron text-white p-2 rounded-full text-lg">🎖️</span>
    </div>

    <div class="space-y-2 mb-8">
        <div class="flex justify-between text-xs">
            <span>Next achievements: 20 Meals Taken in MealMate </span>
            <span>75%</span>
        </div>
        <div class="w-full bg-stone-700 h-2 rounded-full overflow-hidden">
            <div class="bg-saffron h-full w-[80%] transition-all duration-1000"></div>
        </div>
    </div>

    <div class="grid grid-cols-2 gap-4">
        <div class="bg-stone-800 p-4 rounded-2xl border border-stone-700">
            <p class="text-[10px] text-stone-400 uppercase">Current Meals Counted</p>
            <p class="text-xl font-bold">15</p>
        </div>
        <div class="bg-stone-800 p-4 rounded-2xl border border-stone-700">
            <p class="text-[10px] text-stone-400 uppercase">Discount</p>
            <p class="text-xl font-bold">Free Drink</p>
        </div>
    </div>

    <button class="w-full mt-8 bg-white text-stone-900 py-3 rounded-xl font-bold hover:bg-stone-200 transition">
        Check My Exclusive Benefits
    </button>
</div>

<section class="max-w-6xl mx-auto px-8 py-20 bg-white rounded-[3rem] my-12 shadow-sm">
    <div class="grid md:grid-cols-2 gap-16 items-center">
        <div class="space-y-6">
            <span class="text-saffron font-bold tracking-widest uppercase text-sm">For the Learner</span>
            <h2 class="text-4xl serif">Feed your mind, not just your tutor.</h2>
            <p class="text-stone-500 italic">"I spent $80 on a great pasta and 2 hours of Spanish. My old tutor cost $200 for an hour of Zoom. This is a no-brainer."</p>
            <ul class="space-y-2 text-stone-700">
                <li>✅ Save 50% vs Traditional Tutoring</li>
                <li>✅ Learn real-world slang and culture</li>
                <li>✅ High-density immersion</li>
            </ul>
        </div>
        <div class="space-y-6 border-l border-stone-100 pl-16">
            <span class="text-sage font-bold tracking-widest uppercase text-sm">For the Native</span>
            <h2 class="text-4xl serif">Your city is the menu.</h2>
            <p class="text-stone-500 italic">"I love my language, and I love good food. Now I get to share both while meeting amazing people from around the world."</p>
            <ul class="space-y-2 text-stone-700">
                <li>✅ Free meals at the city's best spots</li>
                <li>✅ Zero prep work—just show up and talk</li>
                <li>✅ Build a global network</li>
            </ul>
        </div>
    </div>
</section>

<section class="min-h-screen bg-[#121212] text-white flex items-center justify-center p-6">
    <div class="w-full max-w-[380px] aspect-[9/16] bg-gradient-to-b from-[#F4A261]/20 to-[#121212] rounded-[2.5rem] p-8 relative overflow-hidden flex flex-col border border-white/10 shadow-2xl">
        
        <div class="flex gap-1 mb-10">
            <div class="h-1 bg-white flex-1 rounded-full"></div>
            <div class="h-1 bg-white flex-1 rounded-full"></div>
            <div class="h-1 bg-white/30 flex-1 rounded-full"></div>
            <div class="h-1 bg-white/30 flex-1 rounded-full"></div>
        </div>

        <div class="flex-1">
            <p class="text-[#F4A261] font-bold tracking-widest uppercase text-xs mb-2">2026 WRAPPED</p>
            <h2 class="text-4xl font-serif italic leading-tight mb-8" style="font-family: 'Fraunces', serif;">
                This year, <br>you swallowed a<br><span class="text-[#F4A261]">Spanish Dictionary.</span>
            </h2>

            <div class="space-y-6">
                <div class="bg-white/5 backdrop-blur-md p-5 rounded-3xl border border-white/10">
                    <p class="text-stone-400 text-xs mb-1">Total Conversation Time</p>
                    <p class="text-3xl font-bold font-mono text-white">2,880 <span class="text-sm font-normal opacity-60">mins</span></p>
                </div>

                <div class="bg-white/5 backdrop-blur-md p-5 rounded-3xl border border-white/10">
                    <p class="text-stone-400 text-xs mb-1">Favorite Flavor</p>
                    <p class="text-2xl font-bold text-white">Spicy Mexican 🌮</p>
                </div>

                <div class="bg-white/5 backdrop-blur-md p-5 rounded-3xl border border-white/10">
                    <p class="text-stone-400 text-xs mb-1">New Vocab Unlocked</p>
                    <p class="text-3xl font-bold text-white">152 <span class="text-sm font-normal opacity-60">words</span></p>
                </div>
            </div>
        </div>

        <div class="mt-8 flex items-center justify-between">
            <div class="flex items-center gap-2">
                <div class="w-8 h-8 bg-[#F4A261] rounded-full flex items-center justify-center font-bold text-black text-xs">M</div>
                <span class="text-sm font-bold tracking-tight">MealMate</span>
            </div>
            <button class="bg-white text-black px-4 py-2 rounded-full text-xs font-bold hover:scale-105 transition shadow-lg shadow-white/10">
                Share to Stories
            </button>
        </div>

        <div class="absolute -bottom-20 -right-20 w-64 h-64 bg-[#F4A261]/20 rounded-full blur-[100px]"></div>
    </div>
</section>

</body>
</html>
