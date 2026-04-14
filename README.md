pip install streamlit

import streamlit as st
import streamlit.components.v1 as components

# Set page config
st.set_page_config(page_title="MealMate | Eat. Speak. Belong.", layout="wide")

# Define your HTML & Tailwind code as a string
# I have consolidated all your sections into a single scrollable container
mealmate_html = """
<!DOCTYPE html>
<html lang="en">
<head>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,100..900;1,9..144,100..900&family=Outfit:wght@100..900&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Outfit', sans-serif; background-color: #FDFBF7; color: #1c1917; margin: 0; padding: 0;}
        h1, h2, h3, .serif { font-family: 'Fraunces', serif; }
        .bg-saffron { background-color: #F4A261; }
        .hero-gradient { 
            background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)), 
            url('https://images.unsplash.com/photo-1552566626-52f8b828add9?auto=format&fit=crop&w=1600&q=80'); 
            background-size: cover; background-position: center; 
        }
        .success-card { animation: slideUp 0.6s ease-out; }
        @keyframes slideUp { from { transform: translateY(20px); opacity: 0; } to { transform: translateY(0); opacity: 1; } }
    </style>
</head>
<body class="flex flex-col items-center">

    <nav class="w-full flex items-center justify-between px-8 py-6 max-w-7xl mx-auto">
        <div class="text-2xl font-bold flex items-center gap-2">
            <span class="bg-saffron text-white p-2 rounded-lg">M</span>
            <span class="serif tracking-tight text-2xl">MealMate</span>
        </div>
        <button class="bg-stone-900 text-white px-6 py-2 rounded-full font-semibold">Join the Table</button>
    </nav>

    <main class="w-full flex flex-col items-center space-y-24 pb-20">
        
        <header class="hero-gradient w-[95%] h-[60vh] flex items-center justify-center text-center px-4 rounded-[3rem] mx-4 shadow-xl">
            <div class="max-w-3xl text-white">
                <h1 class="text-5xl md:text-7xl mb-6 leading-tight">Stop Studying.<br>Start Dining.</h1>
                <p class="text-xl mb-8 font-light">Master a new language over a real meal.</p>
            </div>
        </header>

        <section class="w-full flex flex-col items-center px-6">
             <div class="success-card bg-white w-full max-w-md rounded-[2.5rem] shadow-2xl overflow-hidden border border-stone-100">
                <div class="bg-saffron p-6 text-white flex justify-between items-center">
                    <h2 class="text-2xl font-bold">Spanish & Tapas</h2>
                    <span class="text-sm font-mono bg-white/20 px-2 py-1 rounded">Confirmed</span>
                </div>
                <div class="p-8 space-y-6">
                    <div class="flex items-center gap-4">
                        <img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?w=100" class="w-16 h-16 rounded-full object-cover">
                        <div><h3 class="font-bold text-lg">Mateo, 26</h3><p class="text-stone-400">"Let's talk Spanish!"</p></div>
                    </div>
                    <button class="w-full bg-stone-900 text-white py-4 rounded-2xl font-bold">Add to Calendar</button>
                </div>
            </div>
        </section>

        <section class="w-full flex justify-center px-6">
            <div class="w-full max-w-[380px] aspect-[9/16] bg-gradient-to-b from-[#F4A261]/20 to-[#121212] rounded-[2.5rem] p-8 relative overflow-hidden flex flex-col border border-white/10 shadow-2xl">
                <div class="flex-1">
                    <p class="text-[#F4A261] font-bold text-xs mb-2">2026 WRAPPED</p>
                    <h2 class="text-4xl serif italic leading-tight text-white">You swallowed a <span class="text-[#F4A261]">Spanish Dictionary.</span></h2>
                    <div class="mt-12 space-y-4">
                        <div class="bg-white/5 p-4 rounded-2xl border border-white/10 text-white">
                            <p class="text-xs opacity-60">Total Conversation Time</p>
                            <p class="text-2xl font-bold">2,880 mins</p>
                        </div>
                    </div>
                </div>
                <button class="w-full bg-white text-black py-4 rounded-full font-bold">Share to Stories</button>
            </div>
        </section>

    </main>

    <footer class="py-12 text-stone-400 text-xs">© 2026 MealMate</footer>
</body>
</html>
"""

# Render the HTML in Streamlit
components.html(mealmate_html, height=2500, scrolling=True)
streamlit run app.py

