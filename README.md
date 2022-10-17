# CODIGO01-PROFESSOR

#define LED0 11
#define LED1 10
#define LED2 9
#define LED3 8

void firsteffect(void); //PRIMEIRA FUNÇÃO
void secondeffect(void);// SEGUNDA FUNÇÃO


void setup()
{    
  pinMode(LED0, OUTPUT);
  pinMode(LED1, OUTPUT);
  pinMode(LED2, OUTPUT);
  pinMode(LED3, OUTPUT);
}
void loop()
{
  int option = 2; //TENHO QUE DIZER QUAL VARIAVEL ENTRAR EM SWITCH
  switch(option) 
  {
  case 1:
    firsteffect ();
  break;
  case 2:
    secondeffect ();
  break;
  } 
}
void firsteffect(void)
{
  digitalWrite(LED0, HIGH);
  delay(1000);
  digitalWrite(LED1, HIGH);
  delay(1000);
  digitalWrite(LED2, HIGH);
  delay(1000);
  digitalWrite(LED3, HIGH);
  delay(1000);
  
  digitalWrite(LED0, LOW);
  delay(1000);
  digitalWrite(LED1, LOW);
  delay(1000);
  digitalWrite(LED2, LOW);
  delay(1000);
  digitalWrite(LED3, LOW);
  delay(1000);
  
}
void secondeffect(void)
{
   digitalWrite(LED0, HIGH);
  delay(200);
  digitalWrite(LED1, HIGH);
  delay(200);
  digitalWrite(LED2, HIGH);
  delay(200);
  digitalWrite(LED3, HIGH);
  delay(200);
  
  digitalWrite(LED0, LOW);
  delay(200);
  digitalWrite(LED1, LOW);
  delay(200);
  digitalWrite(LED2, LOW);
  delay(200);
  digitalWrite(LED3, LOW);
  delay(200);
  
}
  
  
