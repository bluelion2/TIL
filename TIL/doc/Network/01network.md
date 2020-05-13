# 네트워크의 구조

### 1. 컴퓨터 네트워크란

- 두 대 이상의 컴퓨터가 연결되어 있는 것

### 2. 네트워크의 역할

- 파일전송, 웹사이트 열람, 메일 송수신

### 3. 인터넷

- 거대한 네트워크부터 작은 네트워크까지 연결하는 거대한 네트워크

## 2.  패킷

데이터를 주고 받는 데 필요한 데이터 조각 규칙

큰 데이터가 있더라도 작게 나누어서 발송하는 것이 규칙

### ⑴ 왜 작게 나눌까

- 큰 데이터를 그대로 보내면 대역폭을 많이 차지해서 패킷의 흐름을 막을 위험이 있다.
- 대역폭 : 네트워크에서 이용 가능한 최대 전송 속도로 정보를 전송할 수 있는 **시간당 전송량**

### ⑵ 패킷을 사용할 때 고려되는 점

- 순서 → 패킷에 순서를 달아서 보내게 된다
- 누락 →

# 디지털 데이터의 단위

## 1. 디지털 데이터

- 0과 1의 집합

## 2. 비트와 바이트

- 비트 : 0과 1의 정보를 나타내는 최소 단위
- 바이트 : 8bit
- 문자코드 :  특정 숫자는 특정 문자로 나타내겠다는 약속
    - ASCII CODE : 기본적인 문자 코드
    - A : 65, b : 66

# LAN WAN

## 1. LAN (LOCAL AREA NETWORK,근거리 통신망)

- 건물 안이나 특정 범위로 하는 네트워크
- 지리적으로 제한된 곳에서 컴퓨터와 프린터를 연결
- 거리가 짧고 신호가 약해지거나 오류가 발생할 확율 ↓

## 2. WAN(Wide Area Network 광역통신망)

- ISP(인터넷 서비스 제공자)가 제공하는 서비스를 사용하여 구축된 네트워크
- LAN과 LAN을 연결
- 거리가 짧고 신호가 약해지거나 오류가 발생할 확율 ↑
- ISP : Internet Service Provider like KT U+ SK브로드밴드 같은 통신회사

[LAN vs WAN](https://www.notion.so/40654240a206430381e66163f453a9f3)

# 일반적인 LAN 구성

## 필요한 것들

- ISP(인터넷 서비스 제공자), 인터넷 회선
- 인터넷 공유기(Broadband Router) : ISP와 네트워크를 연결하기 위해서

    가정이나 소규목 기업에서 인터넷에 접속할 때 사용. 가정용 라우터.

- 무선랜도 있음(와이빠이!)

# 회사에서의 랜 구성

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/30b071e1-676a-4e64-a7c5-d2aa198d2b53/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/30b071e1-676a-4e64-a7c5-d2aa198d2b53/Untitled.png)

- DMZ : 외부에 공개하기 위한 네트워크
    - 웹서버 메일서버 DNS 서버(도메인 이름을 사용하여 회사에 서버에 접속하기 위해서) 같은 것들
    - 가정의 랜에서는 서버를 외부에 공개할 필요가 없기 때문에 공개하지 않음

## 사내 서버 운영

- 데이터 센터

    대량의 데이터를 보관하기 위해 데이터 센터 서버나 네트워크 기기를 설치한 전용 시설 

- 사내 서버

    사내 또는 데이터 센터에 두고 운영하는 것을 **온프로미스(on-promise)**라고 한다

- 클라우드

    인터넷을 통해 소프트웨어나 하드웨어 등의 컴퓨팅 서비스를 제공하는 것. 

- 주로 내부망 스위치에 무선 라우터(공유기)를 설치해서 운영

# 퀴즈

1. 네트워크에서 전송되는 작은 데이터 조각을 **패킷**이라고 한다
2. 컴퓨터는 **0과 1**만 이해한다
3. 정보를 표시하는 최소 단위를 **비트**라고 한다
4. 특정 건물이나 지역을 범위로 하고 속도가 빠르며 오류 확률이 낮은 네트워크를 **LAN**이라고 한다
5. 전기 통신 사업자가 제공하는 서비스를 사용하여 구축된 속도가 느리고 오류가 발생하기 쉬운 네트워크를 **WAN**이라고 한다
6. 인터넷에 연결하려면 우선 **ISP**와 인터넷 회선을 결정하고 계약한다
7. 외부에 공개하기 위한 네트워크를 DMZ라고 한다
8. 기업의 서버는 **온 프로미스**나 클라우드 중 하나로 운영되고 있다.