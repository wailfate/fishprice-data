# fishprice-data

수산시세 앱이 매일 받아 읽는 정적 JSON. 파이프라인(fishery-biz/pipeline/publish.py)이 매일 07:30 밀어 넣는다. 사람이 손으로 고치지 않는다.

- latest.json 세 단 시세(30일) · safety.json 방사능 검사(60일) · tenders.json 입찰 · partners.json 업체 광고 · manifest.json 게시 시각
- 출처: 해양수산부 위판장별 위탁판매 현황·노량진수산시장 경락시세·aT KAMIS·국립수산물품질관리원 방사능안전성조사·조달청 나라장터(공공저작물 출처표시)
