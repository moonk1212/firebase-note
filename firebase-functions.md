# firebase-functions 정리

## firebase-functions의 정의

## 서버리스 아키텍쳐
- 서버가 없다는 뜻? x , 단지 서버의 존재에 대해서 신경쓰지 않아도 된다는 뜻임.
  
  - 서버가 어떤 사양으로 돌아가는지 서버의 갯수를 늘려야할지 , 네트워크는 어떤걸 사용할지 이런걸 설정할 필요가 없다.
  
 - BaaS(Backend as a Service) --> firebase  
  - Firebase 같은 BaaS 입니다. 이 시스템에서는, 앱 개발에 있어서 필요한 다양한 기능들 (데이터베이스, 소셜서비스 연동, 파일시스템 등)을 API로 제공해 줌으로서, 
  
    개발자들이 서버 개발을 하지 않고서도 필요한 기능을 쉽고 빠르게 구현 할 수 있게 해주고, 비용은 사용 한 만큼 나가게 되죠.
 
 - FaaS (Function as a Service) : FaaS 는 프로젝트를 여러개의 함수로 쪼개서 (혹은 한개의 함수로 만들어서), 매우 거대하고 분산된 컴퓨팅 자원에 여러분이 준비해둔 함수를 등록하고, 
 
 이 함수들이 실행되는 횟수 (그리고 실행된 시간) 만큼 비용을 내는 방식
## Rules for terminating a Cloud function

  1. HTTP triggers - send a response at the end
  
  https://www.youtube.com/watch?v=7IkUgCLr5oA&feature=youtu.be
  
  2. Background triggers -return a promise
  
  https://www.youtube.com/watch?v=652XeeKNHSk
  
    
  
