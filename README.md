<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vocabulary Slides - ESL</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #0f172a;
            color: #f1f5f9;
            overflow: hidden;
        }

        .slide {
            width: 100vw;
            height: 100vh;
            display: none;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 40px;
            text-align: center;
            background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
            position: relative;
        }

        .slide.active {
            display: flex;
        }

        .intro-slide {
            background: linear-gradient(135deg, #1e293b 0%, #334155 100%);
        }

        .content-slide {
            background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
        }

        .intro-slide h1 {
            font-size: 3.5rem;
            margin-bottom: 30px;
            color: #38bdf8;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }

        .intro-slide .words-list {
            font-size: 1.8rem;
            line-height: 2.2;
            color: #cbd5e1;
            margin: 30px 0;
            max-width: 900px;
        }

        .intro-slide .instruction {
            font-size: 1.3rem;
            color: #94a3b8;
            margin-top: 40px;
            font-style: italic;
        }

        .content-slide img {
            width: 100%;
            max-width: 900px;
            height: 500px;
            object-fit: cover;
            border-radius: 12px;
            margin-bottom: 30px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
        }

        .target-words {
            font-size: 2.2rem;
            margin: 20px 0;
            color: #38bdf8;
            font-weight: bold;
        }

        .speaking-prompt {
            font-size: 1.5rem;
            color: #cbd5e1;
            margin-top: 20px;
            max-width: 800px;
            line-height: 1.8;
        }

        .controls {
            position: fixed;
            bottom: 30px;
            left: 50%;
            transform: translateX(-50%);
            display: flex;
            gap: 20px;
            z-index: 100;
        }

        button {
            padding: 12px 30px;
            font-size: 1rem;
            background-color: #38bdf8;
            color: #0f172a;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            font-weight: bold;
            transition: all 0.3s ease;
        }

        button:hover {
            background-color: #0284c7;
            transform: scale(1.05);
        }

        button:disabled {
            opacity: 0.5;
            cursor: not-allowed;
            transform: scale(1);
        }

        .slide-counter {
            position: fixed;
            top: 20px;
            right: 30px;
            font-size: 1.2rem;
            color: #94a3b8;
            background-color: rgba(30, 41, 59, 0.8);
            padding: 10px 20px;
            border-radius: 6px;
        }

        .progress-bar {
            position: fixed;
            top: 0;
            left: 0;
            height: 4px;
            background-color: #38bdf8;
            transition: width 0.3s ease;
        }
    </style>
</head>
<body>

<!-- GROUP 1: FEELINGS & EMOTIONS -->
<div class="slide intro-slide active">
    <h1>Feelings & Emotions</h1>
    <div class="words-list">frightening • sad • bored • fun • patience</div>
    <div class="instruction">Use the following 4 slides to learn these words through images and speaking practice</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?scared,fear,frightened,horror,expression" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">frightening • scary</div>
    <div class="speaking-prompt">Describe a frightening moment you experienced. Use: "I was frightening when..."</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?sad,crying,unhappy,depression,sadness" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">sad • unhappy</div>
    <div class="speaking-prompt">What makes you sad? Tell your partner: "I feel sad when..."</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?bored,tired,sleepy,waiting,unmotivated" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">bored • dull</div>
    <div class="speaking-prompt">What activities make you bored? Discuss: "I get bored when..."</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?fun,happiness,laugh,playing,joy,excited" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">fun • amusing • entertainment</div>
    <div class="speaking-prompt">Describe something fun you did. Use: "It was fun because..."</div>
</div>

<!-- GROUP 2: WORK & LIFESTYLE -->
<div class="slide intro-slide">
    <h1>Work & Lifestyle</h1>
    <div class="words-list">freelancer • headquarter • charity • used to • will become</div>
    <div class="instruction">Use the following 4 slides to learn these words through images and speaking practice</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?freelancer,laptop,work,home,typing" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">freelancer • self-employed</div>
    <div class="speaking-prompt">Do you know any freelancers? Tell us: "A freelancer is..."</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?corporate,building,office,headquarters,skyscraper" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">headquarter • main office</div>
    <div class="speaking-prompt">Where is your school's headquarter? Explain: "The headquarter is..."</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?charity,helping,donation,volunteer,community" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">charity • helping others</div>
    <div class="speaking-prompt">What charity work interests you? Discuss: "I would like to support..."</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?future,growth,career,ambition,success,goal" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">will become • used to • future</div>
    <div class="speaking-prompt">What will you become in the future? Say: "I will become..." and "I used to..."</div>
</div>

<!-- GROUP 3: PLACES & ENVIRONMENT -->
<div class="slide intro-slide">
    <h1>Places & Environment</h1>
    <div class="words-list">neighborhood • farm • crowded • stage • away</div>
    <div class="instruction">Use the following 4 slides to learn these words through images and speaking practice</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?neighborhood,street,houses,community,suburban" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">neighborhood • district • area</div>
    <div class="speaking-prompt">Describe your neighborhood. Tell us: "My neighborhood is..."</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?farm,crops,animals,rural,barn" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">farm • farming • crops</div>
    <div class="speaking-prompt">Have you been to a farm? Describe: "On the farm, I saw..."</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?crowded,busy,people,market,packed" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">crowded • busy • full</div>
    <div class="speaking-prompt">Which places are crowded in your city? Say: "It's crowded when..."</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?stage,performance,theater,spotlight,concert" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">stage • away • performance</div>
    <div class="speaking-prompt">Have you performed on a stage? Share: "I was away when..." or "On stage I felt..."</div>
</div>

<!-- GROUP 4: SOUNDS & SENSATIONS -->
<div class="slide intro-slide">
    <h1>Sounds & Sensations</h1>
    <div class="words-list">noise • noisy • boring • through • quite</div>
    <div class="instruction">Use the following 4 slides to learn these words through images and speaking practice</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?loud,noise,sound,city,traffic" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">noise • sound • loud</div>
    <div class="speaking-prompt">What noises annoy you? Explain: "The noise of... is..."</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?noisy,loud,chaos,busy,construction" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">noisy • loud • chaotic</div>
    <div class="speaking-prompt">When is school noisy? Discuss: "It's noisy when..."</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?boring,dull,monotonous,uninteresting,tedious" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">boring • dull • uninteresting</div>
    <div class="speaking-prompt">What subjects are boring to you? Say: "I find... quite boring because..."</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?tunnel,passage,light,path,passage" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">through • quite • passage</div>
    <div class="speaking-prompt">Describe a path. Use: "I walk through... and it's quite..." (2-3 words)</div>
</div>

<!-- GROUP 5: RELATIONSHIPS & FAMILY -->
<div class="slide intro-slide">
    <h1>Relationships & Family</h1>
    <div class="words-list">relatives • twins • foreign • share • both</div>
    <div class="instruction">Use the following 4 slides to learn these words through images and speaking practice</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?family,relatives,together,reunion,hug" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">relatives • family • kin</div>
    <div class="speaking-prompt">Do you see your relatives often? Tell us: "My relatives are..."</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?twins,identical,siblings,brothers,sisters" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">twins • siblings • brothers</div>
    <div class="speaking-prompt">Do you know twins? Describe: "Twins are... and..."</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?foreign,international,world,culture,travel" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">foreign • different • international</div>
    <div class="speaking-prompt">Have you visited a foreign country? Say: "The foreign place was..."</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?sharing,together,cooperation,partnership,friends" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">share • both • together</div>
    <div class="speaking-prompt">What do you share with friends? Tell us: "Both of us share... because..."</div>
</div>

<!-- GROUP 6: TIME & DISCOVERY -->
<div class="slide intro-slide">
    <h1>Time & Discovery</h1>
    <div class="words-list">time • how long • half an hour • find out • sort out</div>
    <div class="instruction">Use the following 4 slides to learn these words through images and speaking practice</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?time,clock,watch,schedule,alarm" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">time • how long • duration</div>
    <div class="speaking-prompt">How long do you study? Answer: "In 6 months time... and I study for how long..."</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?hour,thirty,minutes,timer,hourglass" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">half an hour • thirty minutes</div>
    <div class="speaking-prompt">What can you do in half an hour? Say: "In half an hour, I can..."</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?discovery,search,detective,investigation,research" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">find out • discover • learn</div>
    <div class="speaking-prompt">What did you find out about your friend? Share: "I need to find out..."</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?organize,sorting,arrange,organize,tidy" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">sort out • organize • arrange</div>
    <div class="speaking-prompt">What do you need to sort out? Tell us: "I need to sort out..."</div>
</div>

<!-- GROUP 7: QUALITIES & ABILITIES -->
<div class="slide intro-slide">
    <h1>Qualities & Abilities</h1>
    <div class="words-list">able • whole • every • both • avoid</div>
    <div class="instruction">Use the following 4 slides to learn these words through images and speaking practice</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?capability,strength,strong,powerful,athletic" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">able • capable • strong</div>
    <div class="speaking-prompt">What are you able to do? Say: "I'm able to..." (use 3-4 words)</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?whole,complete,entire,total,full" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">whole • complete • entire</div>
    <div class="speaking-prompt">Describe the whole picture. Use: "The whole thing is..."</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?every,each,all,everything,universal" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">every • each • all</div>
    <div class="speaking-prompt">What happens every day? Tell us: "Every day I..."</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?avoid,prevention,escape,danger,warning" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">avoid • escape • prevent</div>
    <div class="speaking-prompt">What do you avoid? Explain: "I avoid... because..."</div>
</div>

<!-- GROUP 8: FREQUENCY & MISCELLANEOUS -->
<div class="slide intro-slide">
    <h1>Frequency & Miscellaneous</h1>
    <div class="words-list">sometimes • made • toward • patience</div>
    <div class="instruction">Use the following 4 slides to learn these words through images and speaking practice</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?sometimes,occasional,weekend,leisure,activity" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">sometimes • occasionally • often</div>
    <div class="speaking-prompt">What do you sometimes do on weekends? Share: "Sometimes I..."</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?made,creation,handmade,craft,diy" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">made • created • crafted</div>
    <div class="speaking-prompt">What have you made recently? Tell us: "I made..."</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?toward,direction,goal,path,movement" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">toward • direction • approach</div>
    <div class="speaking-prompt">Where are you heading? Say: "I'm walking toward... when..."</div>
</div>

<div class="slide content-slide">
    <img src="https://source.unsplash.com/900x600/?patience,waiting,calm,peaceful,meditation" onerror="this.src='https://images.pexels.com/photos/3807517/pexels-photo-3807517.jpeg?w=900&h=600'">
    <div class="target-words">patience • wait • calm</div>
    <div class="speaking-prompt">When do you need patience? Discuss: "I need patience when..."</div>
</div>

<div class="slide intro-slide">
    <h1>Review Complete!</h1>
    <div class="words-list">Great job!</div>
    <div class="instruction">You have learned 32+ vocabulary words across 8 themes</div>
</div>

    <div class="progress-bar" id="progressBar"></div>
    <div class="slide-counter"><span id="currentSlide">1</span> / <span id="totalSlides">37</span></div>

    <div class="controls">
        <button id="prevBtn" onclick="previousSlide()">← Previous</button>
        <button id="nextBtn" onclick="nextSlide()">Next →</button>
    </div>

    <script>
        let currentSlide = 0;
        const slides = document.querySelectorAll('.slide');
        const totalSlides = slides.length;

        function showSlide(n) {
            slides[currentSlide].classList.remove('active');
            currentSlide = (n + totalSlides) % totalSlides;
            slides[currentSlide].classList.add('active');

            document.getElementById('currentSlide').textContent = currentSlide + 1;
            document.getElementById('prevBtn').disabled = currentSlide === 0;
            document.getElementById('nextBtn').disabled = currentSlide === totalSlides - 1;

            const progress = ((currentSlide + 1) / totalSlides) * 100;
            document.getElementById('progressBar').style.width = progress + '%';
        }

        function nextSlide() {
            showSlide(currentSlide + 1);
        }

        function previousSlide() {
            showSlide(currentSlide - 1);
        }

        document.addEventListener('keydown', (e) => {
            if (e.key === 'ArrowRight') nextSlide();
            if (e.key === 'ArrowLeft') previousSlide();
        });

        document.getElementById('totalSlides').textContent = totalSlides;
        showSlide(0);
    </script>
</body>
</html>
