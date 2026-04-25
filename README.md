# Michael- ["❤️","💖","💘","✨","💞"][Math.floor(Math.random()*5)]@keyframes fall {
  to {
    transform: translateY(110vh) rotate(360deg);
    opacity: 0;
  }
}heart.style.animationheart.style.top20heart.style.fontSize100heart.style.leftheart.innerHTMLheart.style.positionfunction yesClicked() {
  document.body.innerHTML = `
    <h1 style="margin-top:40vh; font-size:2.5em;">
      You just made me the happiest person alive 😭❤️
    </h1>
  `;

  createHearts();
}

function createHearts() {
  for (let i = 0; i < 100; i++) {
    let heart = document.createElement("div");
    heart.innerHTML = "❤️";
    heart.style.position = "fixed";
    heart.style.left = Math.random() * 100 + "vw";
    heart.style.top = "-10px";
    heart.style.fontSize = (Math.random() * 20 + 20) + "px";
    heart.style.animation = "fall 3s linear forwards";
    document.body.appendChild(heart);
  }
}document.body.innerHTMLhttps://github.com/shaqur707-debug/Michael-.git
