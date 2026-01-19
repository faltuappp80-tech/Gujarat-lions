<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The King’s Realm: All About Lions</title>
    <style>
        /* CSS for Styling */
        body { font-family: 'Arial', sans-serif; margin: 0; padding: 0; line-height: 1.6; color: #333; background-color: #f4f4f4; }
        header { background: #2c3e50; color: #fff; padding: 1rem 0; text-align: center; position: sticky; top: 0; z-index: 1000; }
        nav a { color: #fff; margin: 0 15px; text-decoration: none; font-weight: bold; }
        .hero { background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://images.unsplash.com/photo-1546182990-dffeafbe841d?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80'); 
                height: 400px; background-size: cover; background-position: center; color: white; display: flex; flex-direction: column; justify-content: center; align-items: center; text-align: center; }
        .container { width: 80%; margin: auto; overflow: hidden; padding: 20px; background: white; margin-top: -50px; border-radius: 10px; box-shadow: 0 0 20px rgba(0,0,0,0.1); }
        section { padding: 40px 0; border-bottom: 1px solid #eee; }
        h2 { color: #d35400; border-left: 5px solid #d35400; padding-left: 10px; }
        .grid { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; }
        .fact-list { background: #fff3e0; padding: 20px; border-radius: 8px; }
        .gallery img { width: 100%; border-radius: 8px; margin-bottom: 10px; }
        footer { text-align: center; padding: 20px; background: #2c3e50; color: white; margin-top: 20px; }
        @media(max-width: 768px) { .grid { grid-template-columns: 1fr; } .container { width: 95%; } }
    </style>
</head>
<body>

<header>
    <h1>The King’s Realm</h1>
    <nav>
        <a href="#home">Home</a>
        <a href="#species">Species</a>
        <a href="#behavior">Behavior</a>
        <a href="#facts">Facts</a>
        <a href="#conservation">Conservation</a>
    </nav>
</header>

<div id="home" class="hero">
    <h1>Welcome to the World of Lions</h1>
    <p>Discover the majesty of the true Kings of the Jungle.</p>
</div>

<div class="container">
    
    <section id="species">
        <h2>African vs Asiatic Lions</h2>
        <div class="grid">
            <div>
                <h3>African Lions</h3>
                <p>Found in sub-Saharan Africa. They are larger, have fuller manes, and live in vast savannas. They are the iconic symbol of the African wild.</p>
            </div>
            <div>
                <h3>Asiatic Lions (Gir Lions)</h3>
                <p>Found only in <b>Gir Forest, Gujarat, India</b>. They have a distinct skin fold on their belly and a shorter mane compared to their African cousins.</p>
            </div>
        </div>
    </section>

    <section id="behavior">
        <h2>Pride Life & Behavior</h2>
        <p>Lions are unique because they are the only social big cats. They live in groups called <b>Prides</b>. While the females (lionesses) do most of the hunting through teamwork, the males protect the territory.</p>
        <p><b>Hunting:</b> They use stealth and coordination to hunt zebras, buffaloes, and deer.</p>
    </section>

    <section id="facts">
        <h2>10 Amazing Fun Facts</h2>
        <div class="fact-list">
            <ul>
                <li>Lions can roar so loud it's heard 8km away.</li>
                <li>They sleep up to 20 hours a day!</li>
                <li>A lion's heels don't touch the ground when they walk.</li>
                <li>The darker the mane, the older the lion.</li>
                <li>Lions are the second largest cats after tigers.</li>
                <li>(Add more facts here...)</li>
            </ul>
        </div>
    </section>

    <section id="gallery">
        <h2>Visual Gallery</h2>
        <div class="grid">
            <img src="https://images.unsplash.com/photo-1614027164847-1b2809eb189d?auto=format&fit=crop&w=500&q=60" alt="Lion Roaring">
            <img src="https://images.unsplash.com/photo-1517776531405-d399990b7933?auto=format&fit=crop&w=500&q=60" alt="Asiatic Lion">
        </div>
        <p align="center"><i>Tip: You can embed YouTube videos here using &lt;iframe&gt; tags.</i></p>
    </section>

    <section id="conservation">
        <h2>Conservation: Save the King</h2>
        <p>Lions are facing threats from habitat loss and poaching. Asiatic lions are critically endangered. We must support National Parks like Gir to ensure their survival.</p>
    </section>

</div>

<footer>
    <p>&copy; 2024 The King's Realm | Made for Lion Lovers</p>
</footer>

</body>
</html>
