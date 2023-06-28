function setup() {
  createCanvas(600, 600);
  background("black");
} 9

function draw() {
  stroke("blue");
  fill("red");

  if(mouseIsPressed){
    rect(mouseX, mouseY, 20, 30);
    }

}
