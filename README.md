# 미국 자전거 공유 데이터 분석

이 프로젝트는 미국 내 주요 도시(시카고, 뉴욕, 워싱턴)의 자전거 공유 데이터를 분석하는 파이썬 프로그램입니다. 

사용자는 특정 도시를 선택하고, 월 및 요일별로 데이터를 필터링하여 다양한 통계를 확인할 수 있습니다.

## 요구 사항
이 프로그램을 실행하려면 다음의 파이썬 라이브러리가 필요합니다:

- Python 3.x
- pandas

## 데이터 파일
이 프로그램은 다음과 같은 CSV 파일을 사용합니다:
- `chicago.csv`
- `new_york_city.csv`
- `washington.csv`

CSV 파일이 같은 디렉터리에 위치해야 정상적으로 실행됩니다.

## 실행 방법
터미널(또는 명령 프롬프트)에서 다음 명령어를 실행하여 프로그램을 시작할 수 있습니다:
```sh
python bikeshare.py
```

## 기능
이 프로그램은 다음과 같은 기능을 제공합니다:

1. **사용자 입력을 통한 데이터 필터링**  
   - 도시 선택 (시카고, 뉴욕, 워싱턴)
   - 특정 월 선택 또는 모든 월 데이터 보기
   - 특정 요일 선택 또는 모든 요일 데이터 보기

2. **데이터 분석 및 통계 출력**  
   - 가장 빈번한 여행 시간
   - 가장 인기 있는 출발지 및 도착지
   - 총 여행 시간 및 평균 여행 시간
   - 사용자 유형 및 인구 통계(성별, 출생 연도 등)

3. **원시 데이터 출력 기능**  
   - 사용자 요청 시 5행씩 원본 데이터를 표시

## 예제 실행 화면
```sh
안녕하세요! 미국 자전거 공유 데이터를 탐색해봅시다!
분석할 도시 이름을 입력하세요 ['chicago', 'new york city', 'washington']: chicago
필터링할 월을 입력하세요 (예: 'all', 'january' ... 'december'): january
필터링할 요일을 입력하세요 (예: 'all', 'monday' ... 'sunday'): all

입력한 값 - 도시: 'chicago', 월: 'january', 요일: 'all'
----------------------------------------
가장 흔한 월은: january
가장 흔한 요일은: Monday
가장 흔한 시간은: 17시
...
```

## 종료 방법
프로그램 실행 중 `Ctrl + C` 를 누르거나, 프로그램 종료 메시지에 "no"를 입력하면 종료됩니다.
