//Automatic Street Light with LDR//

#define sensorPin A5  
#define light 2

int sensorValue;

void setup()
{
  pinMode(led,OUTPUT);
  pinMode(sensorPin,INPUT);
}

void loop()
{
sensorValue = analogRead(sensorPin);
  
// check if it is dark then switch on the light else let it remain off
  
if (sensorValue <100)
digitalWrite(light,HIGH);
else
digitalWrite(light,LOW);
}
