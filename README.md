PFont f;

void setup(){

  size(900,800);
  
  f = createFont("굴림",64);
  
  textFont(f);
  
}

int i,a;

void draw(){

  background(255,0,255);
  
  text("안동대 컴공 사랑합니다",110,i);
  
  i=i+1*a;
  
  if(i>800) i=0;
  
}

void keyPressed(){

  a = key - '0';
  
}
