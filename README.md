int led=13
int led=8
void setup() {
    pinMode(led,output);
     pinMode(led2,output);

}
void loop()
{
    digitalWrite(led,HIGH);
    delay(1000);
    digitalWrite(led,low);
    delay(1000);
    digitalWrite(led2,HIGH);
    delay(1000);
    digitalWrite(led2,low);
    delay(1000);


}



int led=13
int led=8
void setup() {
    pinMode(led,output);
     pinMode(led2,output);

}
void loop()
{
    digitalWrite(led,HIGH);
    delay(1000);
    digitalWrite(led,low);
    delay(10);
    digitalWrite(led2,HIGH);
    delay(1000);
    digitalWrite(led2,low);
    delay(10);


}



int led=13
int led=8
void setup() {
    pinMode(led,output);
     pinMode(led2,output);

}
void loop()
{
    digitalWrite(led,HIGH);
    digitalWrite(led2,HIGH);
    delay(1000);
    digitalWrite(led,low);
    digitalWrite(led2,low);
    delay(1000);
    
  
  
    


}




void setup() {
    pinMode(ledpin,OUTPUT);
  Serial.begin(9600);

}
void loop()
{
    if(Serial.available()>0){
        char incomingByte=Serial.read();
        if(incomingByte=='H'){
             digitalWrite(ledpin,HIGH);

        }
        else if(incomingByte=='l');
        {
            digitalWrite(ledpin,Low);
        }
    }
   
    
  
  
    


}



const int ledpin=13;
void setup() {
    pinMode(ledpin,OUTPUT);
  Serial.begin(9600);

}
void loop()
{
    if(Serial.available()>0){
        char incomingByte=Serial.read();
        if(incomingByte=='H'|| incomingByte=='h' ){
             digitalWrite(ledpin,HIGH);

        }
        else if(incomingByte=='l'|| incomingByte=='L');
        {
            digitalWrite(ledpin,Low);
        }
    }
   
    
  
  
    


}


vois Setup(){
    Serial.begin(9600);

}
vid loop() {
    for(float k = 0; k<360.00; k++){
        Serial.Print(sin(k* (PI / 180.00)));
        Serial.Print(" ");
        Serial.Println(cos(k* (PI / 180.00)));

    }
}


Serial.print(a);
Serial.print(num2);
Serial.print('=');
case'+':
Serial.println(num1+num2);
break;
case'-':
Serial.println(num1-num2);
break;
case'*':
Serial.println(num1*num2);
break;
case'/':
if(num2 != 0){
    Serial.println(num1/num2);
    break;
}
else{
    Serial println("err:num2 cant be zero!");
    break;
}


   
    
  
  
    


}
