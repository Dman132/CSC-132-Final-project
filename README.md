/// Flex Sensor ///
#include <Servo.h>
Servo Leftservo;
Servo Rightservo;


void setup() {
  Rightservo.attach(11);
  Leftservo.attach(9);
  pinMode(9, OUTPUT);
  pinMode(11, OUTPUT);
}

void loop() {
  LeftservoForward();
  RightservoForward();
  delay(3000);
  LeftservoBackward();
  RightservoBackward();
  delay(3000);
}

void LeftservoForward(){
  Leftservo.write(0);
}

void LeftservoBackward(){
  Leftservo.write(90);
}

void RightservoForward(){
  Rightservo.write(90);
}

void RightservoBackward(){
  Rightservo.write(0);
}



///New Section of Code///

/// Stepper Motor ///
#include <Servo.h>
Servo Leftservo;
Servo Rightservo;


void setup() {
  Rightservo.attach(11);
  Leftservo.attach(9);
  pinMode(9, OUTPUT);
  pinMode(11, OUTPUT);
}

void loop() {
  LeftservoForward();
  RightservoForward();
  delay(3000);
  LeftservoBackward();
  RightservoBackward();
  delay(3000);
}

void LeftservoForward(){
  Leftservo.write(0);
}

void LeftservoBackward(){
  Leftservo.write(90);
}

void RightservoForward(){
  Rightservo.write(90);
}

void RightservoBackward(){
  Rightservo.write(0);
}
