void setup(){
  size(800,300);
  textSize(72);
}
int i;
int a;
void draw(){
  background(125);
  fill(0,120,255);
  text("hello everyone",i=i+a,150);
  if(i>800) i=0;
}
void keyPressed(){
  a = key - '0';
}
