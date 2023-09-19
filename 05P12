void setup() {
  pinMode(3, OUTPUT);
}

void loop() {
  analogWrite(3, 0);
  delay(1000);
  for(int i = 0; i<5; i++){
    analogWrite(3,255);
    delay(100);
    analogWrite(3, 0);
    delay(100);
  }
  analogWrite(3, 255);
  while(1) {}
}
