# Traffic light

```.c
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
```


The image of the circuit is shown in fig.1

![Circuit](Circuit.png)
Fig.1 Circuit used for the traffic light
