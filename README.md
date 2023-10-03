## 기술 스택

**주 언어**  
<img src="https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=Swift&logoColor=orange"/>

**프레임워크**  
<img src="https://img.shields.io/badge/UIKit-2396F3?style=flat-square&logo=UIKit&logoColor=white"/>

**협업 툴**  
<img src="https://img.shields.io/badge/Git-2396F3?style=flat-square&logo=Git&logoColor=white"/>
<img src="https://img.shields.io/badge/Linear-5E6AD2?style=flat-square&logo=Linear&logoColor=white"/>

</br>

# 프로젝트
## 1. Rescue Finder
<img width="89" alt="스크린샷 2023-10-03 오후 5 30 30" src="https://github.com/dpfdlalfm/portfolio/assets/84387335/d15e604f-4f2b-473b-97da-beaa0fae1cd8">

### iOS 개발 담당 / 2022. 08 ~ 2022. 09   
**응급상황 발생시 계곡 이용자들에게 최단거리 응급구조함과 응급실 위치를 네비게이션**  
- 지도에 현재 위치를 실시간 제공
- 실시간 날씨 정보 제공

</br>

## Point
### 응급 구조함 및 응급실 위치 계산 기능 속도 개선
- 모든 응급 구조함 데이터를 배열에 저장하여 정렬한 뒤, 마지막 5개 데이터를 추출하여 사용자에게 표시
- **배열 -> 우선순위 큐 교체**하여 결과 도출 속도 증가

</br>

---

</br>

## 2. Second-Hand
### iOS 개발 담당
- **중고 상품 거래 플랫폼**
- 6인 프로젝트  
- 2023.06 ~ 2023.08  

</br>

## Point
### 1. 이미지 캐싱 기술 도입하여 상품 이미지 로드시 지연 현상 해결

1. 이미지 다운로드 후 **Disk Cache / Memory Cache에 저장**
2. Disk Cache에 저장기록이 있는 이미지는 Memory Cache에 저장
3. 캐싱된 이미지는 다운로드 과정없이 출력

### 2. 의존성 분리
- 유지보수 및 기능 개발 편의성을 위해 도입
- 협업간 소통 편의성을 위해 도입
<img width="300" height="400" src="https://github.com/dpfdlalfm/portfolio/assets/84387335/2a12c5a7-8968-401d-bfcc-98011e0a6566">
