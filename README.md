# for-pratayakshi
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>For My Pratyakshi ❤️ | From Anant</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&family=Montserrat:wght@300;400;600&family=Great+Vibes&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Montserrat', sans-serif; background-color: #fff0f3; overflow-x: hidden; scroll-behavior: smooth; }
        .dancing { font-family: 'Dancing Script', cursive; }
        .vibes { font-family: 'Great Vibes', cursive; }
        .glass { background: rgba(255, 255, 255, 0.7); backdrop-filter: blur(12px); border: 1px solid rgba(255, 255, 255, 0.3); }
        
        /* Interactive Name Spawn */
        .click-name {
            position: fixed; pointer-events: none; z-index: 9999;
            font-family: 'Dancing Script', cursive; font-weight: bold; color: #ff4d6d;
            animation: flyUp 1.2s ease-out forwards; white-space: nowrap;
        }
        @keyframes flyUp {
            0% { transform: translateY(0) scale(0.5); opacity: 1; }
            100% { transform: translateY(-150px) scale(1.8); opacity: 0; }
        }

        /* Floating Hearts Background */
        .heart { position: fixed; color: #ff4d6d; animation: floatUp 6s infinite linear; opacity: 0; z-index: 1; }
        @keyframes floatUp {
            0% { transform: translateY(100vh) rotate(0deg); opacity: 0; }
            50% { opacity: 0.6; }
            100% { transform: translateY(-10vh) rotate(360deg); opacity: 0; }
        }

        #noBtn { transition: all 0.2s ease; position: relative; }
    </style>
</head>
<body onclick="spawnName(event)">

    <div id="heart-container"></div>

    <div id="loader" class="fixed inset-0 bg-white z-[100] flex flex-col items-center justify-center p-6 text-center">
        <h2 class="dancing text-4xl text-red-500 mb-4">Syncing Anant's Heart for Pratyakshi...</h2>
        <div class="w-64 h-2 bg-gray-100 rounded-full overflow-hidden">
            <div id="progress" class="w-0 h-full bg-red-500 transition-all duration-1000"></div>
        </div>
        <p id="loading-text" class="mt-4 text-gray-400 text-xs italic">Loading memories & melodies...</p>
    </div>

    <section class="min-h-screen flex flex-col items-center justify-center text-center p-6">
        <div class="glass p-12 rounded-[60px] shadow-2xl pop-in">
            <span class="text-red-400 tracking-[0.2em] text-xs font-bold uppercase">To My Forever</span>
            <h1 class="vibes text-7xl md:text-9xl text-red-600 my-4">Pratyakshi</h1>
            <p class="dancing text-2xl md:text-4xl text-pink-500">I spent nights coding this just for you.</p>
            <div class="mt-10 animate-bounce text-red-300">Scroll Down for Our Song ↓</div>
        </div>
    </section>

    <section class="py-20 px-6 max-w-4xl mx-auto text-center">
        <h2 class="dancing text-5xl text-red-500 mb-8">Our Song 🎵</h2>
        <div class="glass p-4 rounded-[40px] shadow-xl">
            <div class="aspect-video rounded-[30px] overflow-hidden">
                <iframe width="100%" height="100%" src="https://www.youtube.com/embed/ilNt2bikxDI?autoplay=1" title="Anuv Jain - JO TUM MERE HO" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            </div>
        </div>
        <p class="mt-6 dancing text-2xl text-gray-600">"Jo tum mere ho, toh main kuch nahi maangu duniya se..."</p>
    </section>

    <section class="py-20 px-6 max-w-5xl mx-auto">
        <h2 class="dancing text-5xl text-center text-red-500 mb-16 underline decoration-pink-200">The 8 Days of Us</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
            <div class="glass p-6 rounded-3xl border-l-4 border-red-500">
                <h4 class="font-bold text-red-600">Rose Day 🌹</h4>
                <p class="text-sm text-gray-600 italic">For the girl who makes my life bloom every day.</p>
            </div>
            <div class="glass p-6 rounded-3xl border-l-4 border-red-500">
                <h4 class="font-bold text-red-600">Propose Day 💍</h4>
                <p class="text-sm text-gray-600 italic">I choose you today, tomorrow, and forever.</p>
            </div>
            <div class="glass p-6 rounded-3xl border-l-4 border-red-500">
                <h4 class="font-bold text-red-600">Teddy Day 🧸</h4>
                <p class="text-sm text-gray-600 italic">Soft heart, strong love. You're my favorite hug.</p>
            </div>
            <div class="glass p-6 rounded-3xl border-l-4 border-red-500 bg-red-50">
                <h4 class="font-bold text-red-600">Valentine's Day 💖</h4>
                <p class="text-sm text-gray-600 italic">Pratyakshi, you are my home. Happy Valentine's Day!</p>
            </div>
        </div>
    </section>

    <section class="py-20 px-6 text-center bg-white/40">
        <div class="max-w-2xl mx-auto">
            <p class="text-3xl vibes text-red-500 mb-4">"Zikr tera hi hota hai jab bhi koi mohabbat ki baat karta hai,<br> Pratyakshi, ye dil sirf tere liye hi toh dhadakta hai."</p>
            <p class="dancing text-xl text-gray-500">- Anant</p>
        </div>
    </section>

    <section class="min-h-screen flex flex-col items-center justify-center text-center p-6">
        <div class="glass p-12 rounded-[50px] shadow-2xl max-w-lg">
            <h2 class="dancing text-5xl text-red-600 mb-10">Will you be my Valentine, Pratyakshi?</h2>
            <div class="flex gap-6 justify-center">
                <button onclick="alert('I knew it! ❤️ I love you more than anything!')" class="bg-red-500 text-white px-12 py-4 rounded-full font-bold text-xl hover:scale-110 transition shadow-lg">YES! ❤️</button>
                <button id="noBtn" onmouseover="moveNo()" class="bg-gray-400 text-white px-12 py-4 rounded-full font-bold text-xl shadow-lg">No</button>
            </div>
            <p class="mt-8 text-xs text-gray-400 italic font-bold">Error 404: "No" is not an option for you! 😉</p>
        </div>
    </section>

    <script>
        // Loading Screen Animation
        window.addEventListener('load', () => {
            const prog = document.getElementById('progress');
            const loader = document.getElementById('loader');
            setTimeout(() => { prog.style.width = "100%"; }, 100);
            setTimeout(() => { loader.style.opacity = "0"; setTimeout(() => loader.remove(), 500); }, 2000);
        });

        // Floating Hearts
        function createHeart() {
            const h = document.createElement('div');
            h.innerHTML = '❤️'; h.className = 'heart';
            h.style.left = Math.random() * 100 + 'vw';
            h.style.fontSize = (Math.random() * 20 + 15) + 'px';
            h.style.animationDuration = (Math.random() * 2 + 4) + 's';
            document.getElementById('heart-container').appendChild(h);
            setTimeout(() => h.remove(), 6000);
        }
        setInterval(createHeart, 300);

        // Name Spawn on Click
        function spawnName(e) {
            const t = document.createElement('div');
            t.className = 'click-name';
            t.innerHTML = 'Anant ❤️ Pratyakshi';
            t.style.left = e.clientX + 'px';
            t.style.top = e.clientY + 'px';
            document.body.appendChild(t);
            setTimeout(() => t.remove(), 1200);
        }

        // Runaway Button
        function moveNo() {
            const btn = document.getElementById('noBtn');
            const x = Math.random() * (window.innerWidth - 120);
            const y = Math.random() * (window.innerHeight - 60);
            btn.style.position = 'fixed';
            btn.style.left = x + 'px';
            btn.style.top = y + 'px';
        }
    </script>
</body>
</html>
