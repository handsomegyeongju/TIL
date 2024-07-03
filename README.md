자바스크립트를 배우고 정리합니다.


#include <avr/io.h> //avr 기본 헤더파일
#include <avr/interrupt.h> //avr 인터럽트 헤더 파일
#include <util/delay.h> // delay 함수를 사용하기 위한 헤더파일 

unsigned char digit[10] = {0xc0.0xf9,0xa4,0xb0,0x99,0x92,0x82,0xf8,0x80,0x90}; // fnd 숫자 10개(0
~ 9)
unsigned chr latch[4] = {0x01, 0x02, 0x04, 0x08}; // 자리수
int i, count = 0, fnd1, fnd10, fnd100, fnd1000; // 변수 선언
int count run; // 변수

int main(void) //메인 함수
 { 
   DDRA = 0xff; // A포트 출력 설정
   DDRD = 0xff; // A포트 출력 설정
   DDRE = 0x0f; // E포트 입출력 설정
   PORTE = 0xff; //E포트 초기 설정
   
   SREG = 0x80; //상태 레지스터 설정
   EIMSK = 0xc0; // 인터럽트 마스크 레지스터 설정
   EICRB = 0xa0; // 인터럽트 트리거 방식 설정
   
   while(1) //무한 반복
 }
