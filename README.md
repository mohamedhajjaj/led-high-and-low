const int BUTTON = 13;
const int LED = 12;
int BUTTONstate = 0;

void setup()
{
  pinMode(BUTTON, INPUT);
  pinMode(LED, OUTPUT);
}

void loop()
{
  BUTTONstate = digitalRead(BUTTON);
  if (BUTTONstate == LOW)
  {
    digitalWrite(LED, HIGH);
    delay(1000)
  }
    digitalWrite(LED, LOW);
    delay(1000)
}
 
  
  }
