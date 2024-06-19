자바스크립트를 배우고 정리합니다.

#include <avr/io.h>

int main()
 { 
   DDRA = 0xff; //LED출력설정
   DDRB = 0x00; //SW1,SW2 입력설정
   PORTA =0xff; //LED 초기설정(OFF)
   
   while(1)
   {
      if((PINB & 0xc0) == 0x00)  //SW1, SW2 all on
	 PORTA = 0x00;		 //LED all on
      else if((PINB & 0xc0) == 0x80) //SW1 on
	 PORTA =0xf0;
      else if((PINB & 0xc0) == 0x40) //SW2 on
	 PORTA = 0x0f;		     //LED 4,5,6,7 on
      else               	    //SW1, SW2 all off
	 PORTA = 0Xff;             //LED all off                                                                                                      
   }
 }
