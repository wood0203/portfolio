# 프로젝트
## 1. Rescue Finder
<img width="89" alt="스크린샷 2023-10-03 오후 5 30 30" src="https://github.com/dpfdlalfm/portfolio/assets/84387335/d15e604f-4f2b-473b-97da-beaa0fae1cd8">

### iOS 개발 담당 / 2022. 08 ~ 2022. 09   
**응급상황 발생시 계곡 이용자들에게 최단거리 응급구조함과 응급실 위치를 네비게이션**
- 지도에 현재 위치를 실시간 제공
- 실시간 날씨 정보 제공

</br>

## Point
**응급 구조함 및 응급실 위치 계산 기능 속도 개선**
- 데이터 저장공간 **List > 우선순위 큐**로 대체   

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
### 1. 서버 개발 REST API 사용

</br>

## 🎯Trouble-Shooting
### 상품 이미지 로드시 지연 현상
이미지 다운로드시 동기 함수 사용으로 인해 문제 발생

### 해결시도
1. 이미지 다운로드 후 **Disk Cache / Memory Cache에 저장**
2. Disk Cache에 저장기록이 있는 이미지는 Memory Cache에 저장
3. 캐싱된 이미지는 다운로드 과정없이 출력
