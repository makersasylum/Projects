### Abstract
I really enjoy playing cricket and since playing with a season ball can get someone injured my friends and I play with tennis balls. However, one of the major problems we face is that our tennis balls get lost very easily. We play in a 28 sq. foot area which is surrounded by tall trees with tall grass all around. One long shot and the balls get lost in the thicket of greenery. The ball being green gets camouflaged making it even tougher to find. Because of this we are forced to make rules such that no one can hit the ball too far or high resulting in the game being not as much fun.  
This is not only a problem for my friends and me but for many other children across the world who lose their tennis balls every day

### Problem Statement
Tennis Ball getting lost in the surrounding grasslands

### Who is this affecting?
Children living in the urban areas who are passionate about playing cricket, but are limited by the small space available to them.



Solution Brainstorming
1.	Magnetic ball which get attracted to a magnetic object you carry
2.	Torchlight attached to ball which automatically turns on when light sensitivity around the ball drops below a certain threshold
3.	Tool which can push the grass and bushes so that you can easily find the ball
4.	A heat scanner which can detect areas with different heat and socan quickly find the ball / IR scanner
5.	Automatic arm which can extend from a device in your hand which searches for the ball
6.	Build nets around the area you play to prevent the ball from getting lost
7.	Torchlight on your arm which can be activated by press of a button and can help you find the ball
8.	Attach a GPS to the ball which you can track and find
9.	When the light density goes below a threshold or when you command it to the ball gives out beeping noises
10.	Ball has a robotics arm which helps it crawl out of the bushand a gps which helps it find its way back to you
11.	Ball is a different glow in the dark colour which becomes easy to find
12.	Ball has an IR sensor which helps in tracking it
13.	Ball has wheels which can come out of the bottom and it can come back to you.
14.	Can create a robot which can have multiple features including heatmap sensor, a robotic arm, etc which can get in to the bushes and find the ball

### Solution Finalisation
Torchlight attached to ball which automatically turns on when light sensitivity around the ball drops below a certain threshold
 
 
### Prototype Working Video
https://www.dropbox.com/s/nph6jywxbwfclja/IMG_9906.MOV?dl=0

Code
```arduino
Void setup()
{
// put your setup code here, to run once:
pinMode(13, OUTPUT);
pinMode(9, INPUT);
Serial.begin(9600);
}

void loop() 
{// put your main code here, to run repeatedly:
if (digitalRead(9) == LOW) 
{
digitalWrite(13, HIGH);
delay(10);
}
else 
{digitalWrite(13, LOW);
delay(10);
}
}
```



### Project Contributor:
Keshav Mohta

