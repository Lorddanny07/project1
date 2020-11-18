// Upper right wheel

int enB1 = ;
int in3 = ;
int in4 = ;

// Upper left wheel

int enA1 = ;
int in1 = ; 
int in2 = ;

// Lower right wheel 

int enB2 = ;
int in7 = ;
int in8 = ;

// Lower left wheel

int enA2 = ;
int in5 = ; 
int in6 = ;

// Front Ultrasonic sensor 

const int pingPin1 = ; 
const int echoPin1 = ;

// Side Ultrasonic sensor 2

const int pingPin2 = ; 
const int echoPin2 = ;

void setup() 
{

 Serial.begin(9600);
 pinMode(enB, OUTPUT);
 pinMode(in3, OUTPUT);
 pinMode(in4, OUTPUT);
 pinMode(enA1, OUTPUT);
 pinMode(in1, OUTPUT);
 pinMode(in2, OUTPUT);
 pinMode(enB2, OUTPUT);
 pinMode(in7, OUTPUT);
 pinMode(in8, OUTPUT);
 pinMode(enA2, OUTPUT);
 pinMode(in5, OUTPUT);
 pinMode(in6, OUTPUT);
 
}

void loop() 
{
Main:
  //This part is a comparison between the data from the two sensors, and then using the boolen function to determine which direction the robot should go
  
}
void motor_stop() //Function to stop the robot
{
}
void drive_forward() //Function to drive the robot forward
{
}
void drive_backward() //Function to drive the robot backward
}
}
void turn_left() //Function to turn the robot to the left
{
}
void turn_right() //Function to turn the robot to the right
{
}
int readDurationFront() //Read the front sensor value
{
}
int readDurationWall() //Read the right sensor value
{
}
