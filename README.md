 int pinoLed = 13;

void setup() {
  pinMode(pinoLed,OUTPUT);
  }

void loop() { 
  digitalWrite(pinoLed,HIGH);

   delay(40000);// tempo de espera

     digitalWrite(pinoLed, LOW);
   
     delay(4000); // tempo de ativo



}
