<div id="intro-overlay">
  <h1 id="intro-title">
    <span class="intro-word" style="animation-delay: 0.2s;">Before</span>
    <span class="intro-word" style="animation-delay: 0.6s;">my</span>
    <span class="intro-word intro-highlight" style="animation-delay: 1s;">20th</span>
  </h1>
</div>

<style>
  #intro-overlay {
    position: fixed;
    top: 0; left: 0;
    width: 100vw; height: 100vh;
    background: black;
    display: flex;
    align-items: center;
    justify-content: center;
    z-index: 9999;
    animation: introFade 0.7s ease-in-out 3.1s forwards;
  }
  #intro-title {
    display: flex;
    flex-wrap: wrap;
    gap: 0.6rem;
    align-items: baseline;
    justify-content: center;
    text-align: center;
    padding: 0 1.5rem;
    margin: 0;
    font-size: 3rem;
    color: white;
    animation: sentenceVanish 0.8s ease-in-out 2.2s forwards;
  }
  .intro-word {
    display: inline-block;
    opacity: 0;
    animation: wordArrive 0.6s ease-out forwards;
  }
  .intro-highlight {
    color: #7b97aa;
    font-weight: 700;
    font-size: 3.4rem;
    margin-left: 0.2rem;
    margin-right: 0.2rem;
    animation: wordArriveAccent 0.7s ease-out forwards;
  }
  @keyframes wordArrive {
    0%   { opacity: 0; transform: scale(0.85); text-shadow: none; }
    60%  { opacity: 1; transform: scale(1.02); text-shadow: 0 0 12px rgba(255,255,255,0.6); }
    100% { opacity: 1; transform: scale(1); text-shadow: none; }
  }
  @keyframes wordArriveAccent {
    0%   { opacity: 0; transform: scale(0.85); text-shadow: none; }
    60%  { opacity: 1; transform: scale(1.06); text-shadow: 0 0 18px rgba(123,151,170,0.9), 0 0 34px rgba(123,151,170,0.5); }
    100% { opacity: 1; transform: scale(1); text-shadow: 0 0 10px rgba(123,151,170,0.45); }
  }
  @keyframes sentenceVanish {
    0%   { opacity: 1; }
    100% { opacity: 0; }
  }
  @keyframes introFade {
    0%   { opacity: 1; }
    100% { opacity: 0; visibility: hidden; }
  }

  @media (max-width: 600px) {
    #intro-title {
      font-size: 2rem;
      gap: 0.45rem;
      padding: 0 1rem;
    }
    .intro-highlight {
      font-size: 2.3rem;
      margin-left: 0.15rem;
      margin-right: 0.15rem;
    }
  }
</style>

<script>
  if (sessionStorage.getItem('introShown')) {
    document.getElementById('intro-overlay').style.display = 'none';
  } else {
    sessionStorage.setItem('introShown', 'true');
  }
</script>

---
As i'm gradually approaching my 20th birthday, I've come to realize that I have a lot to give. My experiences have been unique to my own self, therefore it must be worth to share to the world. With that, I present to you my digital notebook.

It will include a series of notes:
- [[Ethics]]
- [[Beliefs]]
- [[Concepts]] that stay true to me
- [[Morals]]
- Empirical [[questions]]
- Thoughts on [[love]]
- Thoughts on [[existence]]
- [[Books]] I've read
- Views on modern [[society]]

This will continue to be a work in progress, as new experiences continue to arise. 

Many terms will link with one another, keep note of this when visiting each section. 

> *“I don’t believe in the wisdom of children, nor in the wisdom of the old. There is a moment, a cusp, when the sum of gathered experience is worn down by the details of living. We are never so wise as when we live in the moment.”*

- Paul Kalanithi, When Breath Becomes Air

Alongside, I've created a simple, foundational **framework** that I follow throughout my daily life:

[[Thought]] --> [[Action]] --> [[Execution]]

Please note that each piece of my writing is solely based through my experiences and beliefs; it is entirely **subjective**. There will always be a contrary, these are just *my* personal viewpoints.

I come to realize that we humans will never share the exact same perspective on the world. An economist will view the world entirely differently than a poet, and a doctor will presumably view existence differently than a priest. In truth, the only way we can widen our vision is to seek **interpersonal [[relationships]]** and observe each individual's perspective. It is in this widening that we become closer to peace.  

> *"The end of a matter is better than its beginning, and patience is better than pride."* - Ecclesiastes 7:8 (NIV)
