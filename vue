canvas = document.getElementById("sand-canvas");
buttons = document.getElementById("ui");
background = document.getElementById("background");
buttons.style.backgroundColor = "#dbd9d9"
background.style.backgroundColor = "#dbd9d9"
canvas.style.backdropFilter = "invert(1)"
for (const child of buttons.children) {
if (child.tagName = "button"){
child.style.color = "white"
child.style.backgroundColor = "#5a914d"

  }
}
