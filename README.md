# 아침 시장 브리핑

한국 투자자를 위한 매일 아침(06:30 KST) 종합 시장 브리핑 웹앱입니다.

- 미국 증시(다우·S&P500·나스닥), 반도체·AI 주
- 미국 10년물 국채금리와 주요 금리 구간(4.60 / 4.70 / 4.75%)
- 원/달러 환율, 국제유가(WTI·브렌트)
- 외국인 한국 주식 수급(거래일 기준), 삼성전자·SK하이닉스
- 경제·정치·사회·과학 주요 뉴스, 한국 증시 전망과 업종별 평가
- 날짜 선택으로 지난 브리핑 다시 보기, 날짜별 메모(브라우저에 저장, 내보내기·가져오기 지원)

## 구조

```
index.html            웹앱 (이 파일 하나로 동작)
data/index.json       브리핑이 있는 날짜 목록 {"dates": ["2026-10-07", ...]}
data/YYYY-MM-DD.json  날짜별 브리핑
```

새 브리핑을 추가하려면 `data/YYYY-MM-DD.json`을 올리고 `data/index.json`의 `dates`에 날짜를 추가합니다.

## GitHub Pages 켜기

Settings → Pages → Build and deployment → Source: **Deploy from a branch**, Branch: **main / (root)** → Save.
1~2분 뒤 `https://<아이디>.github.io/<저장소이름>/` 에서 열립니다.

> 확인되지 않은 수치는 추정하지 않고 '확인 불가'로 표시합니다. 투자 판단의 참고 자료이며 투자 권유가 아닙니다.
