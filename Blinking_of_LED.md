/*
Blinking LED
*/

void setup()// Initiate pin 2 as an output
{
pinMode(2, OUTPUT);
}

void loop()
{
digitalWrite(2, HIGH);
delay(1000); // Wait for 1000 millisecond(s)
digitalWrite(2, LOW);
delay(1000); // Wait for 1000 millisecond(s)
}

<img src="https://cdn.discordapp.com/attachments/646478503549861959/976215135175725116/MicrosoftTeams-image_1.png">
