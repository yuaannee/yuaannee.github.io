<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Archer</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            color: #333;
            line-height: 1.8;
            background-color: #f9f9f9;
        }
        header {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 200px;
            overflow: hidden;
            z-index: 1000;
        }
        .video-background {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
        }
        .video-background iframe {
            position: absolute;
            top: 50%;
            left: 50%;
            width: 177.78vh; /* Aspect ratio: 16:9 */
            height: 100vh;
            transform: translate(-50%, -50%);
        }
        .header-content {
            position: relative;
            z-index: 10;
            color: white;
            text-align: center;
            padding: 60px 20px;
            background: rgba(0, 0, 0, 0.4); /* Add a dark overlay for text visibility */
        }
        main {
            margin-top: 200px; /* Adjust for the height of the header */
            padding: 20px;
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
            text-align: justify;
        }
        p {
            margin: 10px 0;
        }
    </style>
</head>
<body>

    <header>
        <div class="video-background">
            <iframe 
                src="https://www.youtube.com/embed/fv3smSEvDpI?autoplay=1&mute=1&loop=1&playlist=fv3smSEvDpI&controls=0&showinfo=0&modestbranding=1" 
                frameborder="0" 
                allow="autoplay; loop; encrypted-media" 
                allowfullscreen>
            </iframe>
        </div>
        <div class="header-content">
            <h1>The Archer</h1>
        </div>
    </header>

    <main>
        <p>Combat, I'm ready for combat</p>
        <p>I say I don't want that, but what if I do?</p>
        <p>'Cause cruelty wins in the movies</p>
        <p>I've got a hundred thrown-out speeches I almost said to you</p>
        <p>Easy they come, easy they go</p>
        <p>I jump from the train, I ride off alone</p>
        <p>I never grew up, it's getting so old</p>
        <p>Help me hold onto you</p>
        <p>I've been the archer</p>
        <p>I've been the prey</p>
        <p>Who could ever leave me, darling?</p>
        <p>But who could stay?</p>
        <p>Dark side, I search for your dark side</p>
        <p>But what if I'm alright, right, right, right here?</p>
        <p>And I cut off my nose just to spite my face</p>
        <p>Then I hate my reflection for years and years</p>
        <p>I wake in the night, I pace like a ghost</p>
        <p>The room is on fire, invisible smoke</p>
        <p>And all of my heroes die all alone</p>
        <p>Help me hold onto you</p>
        <p>I've been the archer</p>
        <p>I've been the prey</p>
        <p>Screaming, who could ever leave me, darling?</p>
        <p>But who could stay?</p>
        <p>(I see right through me, I see right through me)</p>
        <p>'Cause they see right through me</p>
        <p>They see right through me</p>
        <p>They see right through</p>
        <p>Can you see right through me?</p>
        <p>They see right through</p>
        <p>They see right through me</p>
        <p>I see right through me</p>
        <p>I see right through me</p>
        <p>All the king's horses, all the king's men</p>
        <p>Couldn't put me together again</p>
        <p>'Cause all of my enemies started out friends</p>
        <p>Help me hold onto you</p>
        <p>I've been the archer</p>
        <p>I've been the prey</p>
        <p>Who could ever leave me, darling?</p>
        <p>But who could stay?</p>
        <p>(I see right through me, I see right through me)</p>
        <p>Who could stay?</p>
        <p>Who could stay?</p>
        <p>Who could stay?</p>
        <p>You could stay</p>
        <p>You could stay</p>
        <p>You</p>
        <p>Combat, I'm ready for combat</p>
    </main>

</body>
</html>
