# Trading_Bot

## 트레이딩뷰에서 전달되는 웹훅을 처리하는 봇입니다.
동아대 컴퓨터공학과 2023653 최재혁 

해당 4학년 졸업작품으로 제작되었습니다.

&nbsp;

- 특정금융거래정보의 이용 및 보고에 관한 법률(특금법)에 따르면, 해외 거래소를 포함한 모든 가상자산사업자는 금융위원회 금융정보분석원(FIU)에 신고를 한 후 영업을 해야합니다.
- 해당 법은 2021년 9월 24일부터 시행되었습니다.
- 특금법을 준수하기 위해서는 거래소가 정보보호관리체계(ISMS) 인증과 실명 입출금 계좌를 확보해야합니다.
- 이를 통해 한국에서 실명계좌를 발급 가능 거래소는 4곳입니다.
  - 업비트, 빗썹, 코인원, 코빗
  - [출처](https://coin-labs.com/guide/special-law/)

- 지원 거래소
  - 업비트 현물 USDT,BUSD 마켓
  - 한국투자증권 한국/미국 주식 마켓 제작 예정 

# Dependency

> [fastapi](https://github.com/tiangolo/fastapi) , [ccxt](https://github.com/ccxt/ccxt) , [uvicorn](https://github.com/encode/uvicorn)
