# New-year-2026
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy New Year 2026 🎉</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    height: 100vh;
    background: linear-gradient(180deg, #120024, #000);
    overflow: hidden;
    font-family: 'Segoe UI', sans-serif;
}

/* Canvas */
canvas {
    position: fixed;
    inset: 0;
}

/* Festival Text */
.container {
    position: absolute;
    top: 30%;
    width: 100%;
    text-align: center;
    padding: 0 10px;
    z-index: 10;
}

h1 {
    font-size: 3rem;
    color: #ffd700;
    text-shadow: 0 0 10px red, 0 0 30px gold;
    animation: glow 2s infinite alternate;
}

h2 {
    margin-top: 15px;
    font-size: 1.2rem;
    color: #fff;
    text-shadow: 0 0 8px cyan;
}

@keyframes glow {
    from { text-shadow: 0 0 10px gold; }
    to { text-shadow: 0 0 30px red, 0 0 60px gold; }
}

/* Mobile Hint */
.tap {
    position: absolute;
    bottom: 20px;
    width: 100%;
    text-align: center;
    color: #ccc;
    font-size: 1rem;
    animation: pulse 1.5s infinite;
}

@keyframes pulse {
    0% { opacity: 0.3; }
    50% { opacity: 1; }
    100% { opacity: 0.3; }
}

/* Larger screens */
@media (min-width: 768px) {
    h1 { font-size: 4.5rem; }
    h2 { font-size: 1.6rem; }
}
</style>
</head>

<body>

<canvas id="canvas"></canvas>

<div class="container">
    <h1>🎆 Happy New Year 2026 🎆</h1>
    <h2>May Your Year Be Full of Happiness, Health & Success</h2>
</div>

<div class="tap">Tap / Click anywhere to start the celebration 🎶🎇</div>

<!-- 🎵 Background Music -->
<audio id="music" loop>
    <!-- Replace this URL with your own MP3 if you want -->
    <source src="https://cdn.pixabay.com/audio/2022/03/15/audio_4b94e7cb35.mp3" type="audio/mpeg">
</audio>

<script>
/* Canvas setup */
const canvas = document.getElementById("canvas");
const ctx = canvas.getContext("2d");
canvas.width = window.innerWidth;
canvas.height = window.innerHeight;

window.addEventListener("resize", () => {
    canvas.width = window.innerWidth;
    canvas.height = window.innerHeight;
});

let particles = [];

function createFirework(x, y) {
    for (let i = 0; i < 120; i++) {
        particles.push({
            x, y,
            angle: Math.random() * Math.PI * 2,
            speed: Math.random() * 5 + 2,
            life: 100,
            color: `hsl(${Math.random() * 360}, 100%, 60%)`
        });
    }
}

function animate() {
    ctx.fillStyle = "rgba(0, 0, 0, 0.25)";
    ctx.fillRect(0, 0, canvas.width, canvas.height);

    particles.forEach((p, i) => {
        p.x += Math.cos(p.angle) * p.speed;
        p.y += Math.sin(p.angle) * p.speed;
        p.life--;
        ctx.fillStyle = p.color;
        ctx.fillRect(p.x, p.y, 3, 3);
        if (p.life <= 0) particles.splice(i, 1);
    });

    requestAnimationFrame(animate);
}
animate();

/* Music + Interaction */
const music = document.getElementById("music");
let started = false;

function startCelebration(e) {
    if (!started) {
        music.volume = 0.5;
        music.play();
        started = true;
    }

    const x = e.touches ? e.touches[0].clientX : e.clientX;
    const y = e.touches ? e.touches[0].clientY : e.clientY;
    createFirework(x, y);
}

/* Mobile + Desktop support */
document.addEventListener("click", startCelebration);
document.addEventListener("touchstart", startCelebration);
</script>

</body>
</html>
