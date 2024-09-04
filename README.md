<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
  <img src="https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExZjlvc3RoeHd1aHVoc3h6aGZvNDgyb3ZxNDE2ZHJiZmJvNGtuZmc5NCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/WmunPY9JAIwfobtjgs/giphy.gif" height="210" style="flex: 1;" alt="GIF DNA">
  <img src="https://media.giphy.com/media/2zcpTzSZGQrDgX6Gc2/giphy.gif?cid=ecf05e47nhud3oluner6olkaufbg45e76z33quxdrnaeuy0w&ep=v1_gifs_related&rid=giphy.gif&ct=g" height="235" style="flex: 3;" alt="GIF T-Rex">
  <img src="https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExZjlvc3RoeHd1aHVoc3h6aGZvNDgyb3ZxNDE2ZHJiZmJvNGtuZmc5NCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/WmunPY9JAIwfobtjgs/giphy.gif" height="210" style="flex: 1;" alt="GIF DNA">
</div>

<div style="display: flex; justify-content: center; align-items: center; height: 100vh;">
  <p id="animated-text" style="font-family: 'Courier New', Courier, monospace; font-size: 24px; white-space: nowrap; overflow: hidden; border-right: 4px solid; width: 0; animation: typing 3s steps(30, end), blink-caret 0.5s step-end infinite, fadeout 1s 5s forwards;"></p>
</div>

<style>
@keyframes typing {
  from { width: 0; }
  to { width: 100%; }
}

@keyframes blink-caret {
  from, to { border-color: transparent; }
  50% { border-color: black; }
}

@keyframes fadeout {
  from { opacity: 1; }
  to { opacity: 0; }
}

#animated-text::before {
  content: "Sua frase aqui";
}
</style>






