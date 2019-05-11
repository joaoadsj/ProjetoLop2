# ProjetoLop2
etapa 2
//Nome: João Andre Da SIlva Júnior; Subturma:D 
var x=210
    
  function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(220);
  rect(30,200,100,100)
  rect(50,140,60,60)
  rect(60,100,40,40)
  line(50,150,10,70)
  line(110,150,150,70)
  ellipse(x,190,50,50)

 if ( keyIsDown(RIGHT_ARROW) ) 

  {

  	x = x + 3;

  }
}
