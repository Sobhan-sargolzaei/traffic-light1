# traffic-light1
int led pin[]= { 9, 10 , 11,12 };
int delaytime = 500;
void setup() {
for (int i =0;i<4;i++)[
pinMode (led_pin [i], OUTPUI) :
void loop() {
for (int i=0;i<4;1++){
digitalWrite (led_pin[i],HIGH) ;
delay (delaytime);
digitalWrite (led_pin[i], LOW);
}
for (int
i=0;i<4;i++){
for（int j=0;j<=i;j++）{
digitalWrite (led_pin[i],HIGH);
delay (delaytime);
for (int j=0;j<=i;j++){
digitalWrite (led_pin[i],LOW);
delay (delaytime);
Done uploading.
