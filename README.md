<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>The Jazzy Speacial | Business Mangament</title>

<style>
body {
    margin: 0;
    font-family: "Comic Sans MS", cursive, sans-serif;
    background: linear-gradient(45deg, hotpink, orange, yellow, lime, cyan);
    background-size: 400% 400%;
    animation: chaosBG 10s infinite alternate;
    color: black;
}

@keyframes chaosBG {
    0% { background-position: left; }
    100% { background-position: right; }
}

header {
    text-align: center;
    padding: 40px 20px;
    background: black;
    color: white;
}

header h1 {
    font-size: 3rem;
    margin: 0;
    text-transform: uppercase;
    letter-spacing: 5px;
}

.tagline {
    font-style: italic;
    color: hotpink;
}

nav {
    margin-top: 20px;
}

nav a {
    color: yellow;
    text-decoration: none;
    margin: 0 15px;
    font-weight: bold;
}

nav a:hover {
    text-decoration: underline;
}

.hero {
    text-align: center;
    padding: 80px 20px;
}

.hero h2 {
    font-size: 2.5rem;
}

button {
    padding: 15px 30px;
    font-size: 1rem;
    background: black;
    color: yellow;
    border: none;
    cursor: pointer;
    margin-top: 20px;
}

button:hover {
    background: hotpink;
    color: white;
}

.section {
    padding: 60px 20px;
    text-align: center;
}

.card {
    background: white;
    padding: 20px;
    margin: 20px auto;
    width: 80%;
    max-width: 500px;
    border: 4px dashed black;
    box-shadow: 10px 10px 0 black;
}

footer {
    text-align: center;
    padding: 20px;
    background: black;
    color: white;
}
</style>
</head>

<body>

<header>
    <h1>The Jazzy Speacial</h1>
    <p class="tagline">We Misspell Success On Purpose</p>
    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#" style="color: hotpink;">Business Mangament</a>
        <a href="#">Contact</a>
    </nav>
</header>

<section class="hero">
    <h2>Business Mangament… But Make It Unhinged</h2>
    <p>We don't streamline operations. We aggressively rearrange them.</p>
    <button onclick="alert('You have subscribed to CHAOS.')">Embrace the Chaos</button>
</section>

<section class="section">
    <h2>Our Services</h2>

    <div class="card">
        <h3>Strategic Confusion</h3>
        <p>We replace your 5-year plan with vibes and a whiteboard marker that barely works.</p>
    </div>

    <div class="card">
        <h3>Operational Mayhem</h3>
        <p>Why fix bottlenecks when you can create new, more exciting ones?</p>
    </div>

    <div class="card">
        <h3>Leadership Panic Coaching</h3>
        <p>Learn how to nod confidently in meetings you don’t understand.</p>
    </div>

</section>

<section class="section">
    <h2>Client Testimonials</h2>

    <div class="card">
        <p>"Our revenue didn’t grow, but our personality did." – Anonymous CEO</p>
    </div>

    <div class="card">
        <p>"I cried twice. 10/10 experience." – Startup Founder</p>
    </div>
</section>

<section class="section">
    <h2>Why Choose Us?</h2>
    <p>Because normal is boring and spreadsheets deserve fear.</p>
</section>

<footer>
    <p>© 2026 The Jazzy Speacial | No Refunds | Probably</p>
</footer>

</body>
</html>
