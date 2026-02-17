<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday, Sabrina!</title>
<script src="https://cdn.tailwindcss.com"></script>
<link href="https://fonts.googleapis.com/css2?family=Kalam&family=Homemade+Apple&display=swap" rel="stylesheet">
<style>
  body {
    font-family: 'Kalam', sans-serif;
    margin: 0;
    background: #fff8f0;
    color: #4a3728;
  }
  .paper {
    background: #fffef8;
    background-image: repeating-linear-gradient(0deg, transparent, transparent 29px, rgba(0,0,0,0.05) 30px);
    padding: 40px 20px;
    min-height: 100vh;
  }
  .photo-frame {
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    margin: 20px auto;
    position: relative;
    display: inline-block;
  }
  .placeholder-img {
    width: 300px; height: 300px;
    background: linear-gradient(135deg, #7BA3E8 0%, #E87B7B 100%);
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    font-family: 'Kalam', cursive;
    font-size: 14px;
    text-align: center;
    padding: 10px;
  }
  .paragraph {
    max-width: 600px;
    margin: 10px auto 40px auto;
    font-size: 16px;
    line-height: 1.6;
    text-align: justify;
  }
  .final-section {
    position: relative;
    text-align: center;
    min-height: 100vh;
  }
  #big-heart {
    position: fixed;
    top:50%; left:50%;
    transform: translate(-50%, -50%) scale(0);
    font-size: 200px;
    color: #E87B7B;
    transition: transform 1s ease-in-out;
    z-index: 2000;
    pointer-events: none;
  }
  #heart-text {
    position: fixed;
    top:50%; left:50%;
    transform: translate(-50%, -50%) scale(0);
    color: white;
    font-family: 'Homemade Apple', cursive;
    font-size: 36px;
    text-align: center;
    line-height: 1.2;
    z-index: 2001;
    pointer-events: none;
  }
  .overlay {
    position: fixed; top:0; left:0; width:100%; height:100%;
    background: rgba(0,0,0,0.3);
    opacity:0;
    transition: opacity 0.5s ease-in-out;
    z-index: 1999;
  }
  .replay-btn {
    background: #E87B7B; color: white;
    padding: 12px 30px; border-radius: 30px;
    font-size: 20px; cursor: pointer;
    margin-top: 20px;
    display: inline-block;
  }
</style>
</head>
<body>

<div class="paper" id="notebook">

  <!-- Intro -->
  <section class="intro-section text-center">
    <h1 class="handwritten-title text-4xl mb-4">Happy Birthday, Sabrina!</h1>
    <div class="photo-frame">
      <div class="placeholder-img" id="intro-photo">
        Insert your GDrive link
      </div>
    </div>
    <p class="paragraph">
      Hey baby, happy 27th birthday. You’re getting older already yeah, but your heart still remains young and pure, and that’s something I will forever cherish deeply.
    </p>
  </section>

  <!-- Content Sections -->
  <section class="content-section">
    <div class="photo-frame">
      <div class="placeholder-img">Insert your GDrive link</div>
    </div>
    <p class="paragraph">
      The smartest in whatever you do. The easiest to laugh at my jokes (but also the biggest killjoy sometimes just to stop me from exaggerating myself). The striking fancy outfits, the cute quirky face, the constant yapping and nagging whenever I make mistakes, and lastly, the prettiest smile that has been affectionating me all this while.
    </p>
  </section>

  <section class="content-section">
    <div class="photo-frame">
      <div class="placeholder-img">Insert your GDrive link</div>
    </div>
    <p class="paragraph">
      I will always remember the first time we started knowing each other. I was an introverted dick (I hope I’m not still now hehe). Little did I know, it would become the greatest gift I could have ever asked for in my life.
    </p>
  </section>

  <section class="content-section">
    <div class="photo-frame">
      <div class="placeholder-img">Insert your GDrive link</div>
    </div>
    <p class="paragraph">
      They say behind strength is consistency, and you are the most hardworking girl I’ve ever met. Your attention to detail, your respect for others, the way you show up as the best friend anyone could ask for, and the best partner I could ever receive.
    </p>
  </section>

  <section class="content-section">
    <div class="photo-frame">
      <div class="placeholder-img">Insert your GDrive link</div>
    </div>
    <p class="paragraph">
      I just hope you don’t cry too much, because it pains me to see you that way. I promise I will continue working hard to make this work, and to do things right with you. But BE STRONG BBY SBB I TAK STRONG.
    </p>
  </section>

  <!-- Final Section -->
  <section class="final-section">
    <div class="photo-frame">
      <div class="placeholder-img">Insert your GDrive link</div>
    </div>
    <button class="replay-btn" onclick="showHeart()">Let's Begin Your Celebration</button>
  </section>

</div>

<div class="overlay" id="overlay"></div>
<div id="big-heart">❤️</div>
<div id="heart-text">27th year<br>Strong Baby Girl</div>

<script>
function showHeart() {
  document.getElementById('overlay').style.opacity = '1';
  document.getElementById('big-heart').style.transform = 'translate(-50%, -50%) scale(1)';
  document.getElementById('heart-text').style.transform = 'translate(-50%, -50%) scale(1)';
}

document.getElementById('big-heart').addEventListener('click', () => {
  // Reset page
  document.getElementById('overlay').style.opacity = '0';
  document.getElementById('big-heart').style.transform = 'translate(-50%, -50%) scale(0)';
  document.getElementById('heart-text').style.transform = 'translate(-50%, -50%) scale(0)';
  window.scrollTo({ top: 0, behavior: 'smooth' });
});
</script>

</body>
</html>
