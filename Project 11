var runner ,runner1;
function preload(){
  //pre-load images
  pathImg = loadImage("path.png");
  runner = loadImage("runner-1.png","runner-2.png"); 
}

function setup(){
  createCanvas(800,800);

  //create sprites here
  runner = createSprite (600,200,35,10);
  runner.addAnimation("running",runner-2);
  runner.scale = 1.5;
  
// moving background
path = createSprite(200,600);
path.addImage(pathImg);
path.velocityY = 4;
path.scale=1.2;

}

function draw() {
createEdgesprite();
//code to reset the background
if(path.y > 100 ){
  path.y = height/2;
}
 drawSprites();
}
