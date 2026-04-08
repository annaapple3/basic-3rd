# 1. 기본 분석

- 사용된 프로토콜을 3가지 이상 작성하시오.
  -> DNS HTTP TCP

# 2. 웹 요청 분석

- HTTP 요청 중 ".pdf" 파일을 다운로드하는 요청을 찾으시오.

- 전체 URL (http:// 포함)을 작성하시오.
  -> [http://www.yongin.go.kr/ebook/src/viewer/download.php?host=main&site=20260227_091734&no=1]

- 요청 방식(GET/POST)을 작성하시오.
  -> GET

# 3. 서버 응답 분석

- 서버가 반환한 파일의 종류는 무엇인가?
  -> application/pdf

- 파일 크기는 얼마인가?
  -> 1,454,287 B

- 파일 이름은 무엇인가?
  -> 2026%EB%85%84*%EB%AA%A8%EC%9E%90%EB%B3%B4%EA%B1%B4%EC%82%AC%EC%97%85*%EC%95%88%EB%82%B4%EC%B1%85%EC%9E%90%28%EC%B2%98%EC%9D%B8%EA%B5%AC%EB%B3%B4%EA%B1%B4%EC%86%8C%29.pdf
  (2026년*모자보건사업*안내책자(처인구보건소))

# 4. 파일 복구

- NetworkMiner를 사용하여 파일을 복구하고, 복구 과정을 단계별로 작성하시오.

1. NetworkMiner을 실행합니다.
2. Wireshark에서 .pcap확장자로 저장한 파일을 불러와 열어줍니다.
3. 패킷 분석
4. 상단 메뉴에서 Files탭을 선택해 네트워크를 통해 전송된 파일 목록을 확인합니다.
5. 파일 목록에서 확장자가 .pdf파일을 찾기 위해 pdf를 검색해줍니다.
6. 해당 파일을 우클릭하여 열어줍니다.
7. 복구하려는 파일이 맞는지 확인해줍니다.

- 복구 과정 화면을 캡처하여 첨부하시오.
  <img width="1946" height="1314" alt="Image" src="https://github.com/user-attachments/assets/cb080699-6ec4-4b5e-86c6-8e2260e7ab59" />
