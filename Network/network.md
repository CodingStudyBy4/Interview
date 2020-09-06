
# 💡  Network
1. [HTTP와 HTTPS 차이](https://github.com/CodingStudyBy4/Interview/blob/master/Network/network.md#HTTP와-HTTPS-차이)    
	- HTTP 의 문제점들    
2. [TCP란 무엇인가?](https://github.com/CodingStudyBy4/Interview/blob/master/Network/network.md#tcp란-무엇인가)        
	- TCP flag에 대해서 설명    
	- 비연결성/연결성 프로토콜 설명    
3. [3-way handshaking이란?](https://github.com/CodingStudyBy4/Interview/blob/master/Network/network.md#3-way-handshaking이란)       
4. [TCP와 UDP의 차이](https://github.com/CodingStudyBy4/Interview/blob/master/Network/network.md#TCP와-UDP의-차이)         
	- 두 프로토콜 활용 예    
5. [주소창에 url 입력시 어떤 일이 일어나는가?](https://github.com/CodingStudyBy4/Interview/blob/master/Network/network.md#주소창에-url-입력시-어떤-일이-일어나는가)        
6. [OSI 7계층이란?](https://github.com/CodingStudyBy4/Interview/blob/master/Network/network.md#OSI-7계층이란)        
7. [TCP/IP 계층](https://github.com/CodingStudyBy4/Interview/blob/master/Network/network.md#TCP/IP-계층)        
	- 계층별 설명    
8. [HTTP 요청 메소드 Get/Post 방식 차이](https://github.com/CodingStudyBy4/Interview/blob/master/Network/network.md#HTTP-요청-메소드-Get/Post-방식-차이)        
9. [Session과 Cookie는 왜 필요한가?](https://github.com/CodingStudyBy4/Interview/blob/master/Network/network.md#Session과-Cookie는-왜-필요한가)        
	- Session과 Cookie 차이    
10. [CORS란?](https://github.com/CodingStudyBy4/Interview/blob/master/Network/network.md#CORS란)        
11. [IP-VPN망 vs 인터넷 VPN](https://github.com/CodingStudyBy4/Interview/blob/master/Network/network.md#ip-vpn망-vs-인터넷-vpn)        
    
[뒤로](https://github.com/CodingStudyBy4/Interview/blob/master/README.md#--네트워크--link)


## HTTP와 HTTPS 차이    
샬라샬라
## TCP란 무엇인가?
	- TCP flag
		- [x] TCP 헤더 구조 설명
		- [x] 목적, 용도
		- [x] 형식(ex 000001 -> 무엇인가?) 
		- [x] flag : URG(긴급)/ACK(확인)/PSH(즉시전달)/RST(연결초기화)/SYN(연결시작)/FIN(연결해제) 설명
		
	- 비연결성/연결성 프로토콜
		- [x] 연결/비연결 개념(연결 유지) + 단계
		- [x] 연결 /비연결 특징(유지비용/데이터경로)
		- [x] 연결 /비연결 예(TCP / UDP,IP,HTTP)
		- [x] (+ HTTP 지속연결에 대한 설명)
		
## 3-way handshaking이란?    
샬라샬라
## TCP와 UDP의 차이  
	- [x] 공통점(transport layer/패킷검사/제어)
	- [x] 통신(1:1 && 상호소통 / 1~N:1~N && 일방적)
	- [x] 방식(연결&& 가상회선&& 전송순서보장 / 비연결 &&데이터그램&&순서보장x)
	- [x] 그래서 결론 (신뢰성높고 느림 / 신뢰성 낮고 빠름)
	- [x] 그래서 활용 (http,email,file  / DNS,streaming)
## 주소창에 url 입력시 어떤 일이 일어나는가?    
샬라샬라
## OSI 7계층이란? 
	- Application Layer
		- [x] 목적,역할,처리단위
		- [x] http
	- Presentation Layer
		- [x] 목적,역할,처리단위
	- Session Layer
		- [x] 목적,역할,처리단위
	- Transport Layer
		- [x] 목적,역할,처리단위
		- [x] TCP UDP프로토콜
	- Network Layer
		- [x] 목적,역할,처리단위
		- [x] 서브넷,IP
		- [x] 라우팅,포워딩
	- Data Link Layer
		- [x] 목적,역할,처리단위
	- Physical Layer
		- [x] 목적,역할,처리단위
		
## TCP/IP 계층    
샬라샬라
## HTTP 요청 메소드 Get/Post 방식 차이     
	- [x] http 메소드 종류(get/post/head/put..아는대로)
	- [x] Get/Post 공통점(클->서버 요청)
	- [x] Get/Post 차이점(캐시/길이제한/메세지포함위치/url데이터노출)
	
## Session과 Cookie는 왜 필요한가?    
샬라샬라
## CORS란?    
샬라샬라
## IP-VPN망 vs 인터넷 VPN     
샬라샬라

[위로](#--Network)
