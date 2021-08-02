# LED-TASK

this is the TASK for LED and make it Flash every 1SEC

https://www.tinkercad.com/things/4P90ZlnSMZM-bodacious-fyyran-waasa/editel?sharecode=toDwQbXj2z7PdXlPqlzfJS_WJRlfoEtA6AQn1wlmm7g

// C++ code
//
void setup()
{
  pinMode(13, OUTPUT);
}

void loop()
{
  digitalWrite(13, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(13, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}
