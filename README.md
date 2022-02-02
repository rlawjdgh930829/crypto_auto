## 소개
pyupbit(https://github.com/sharebook-kr/pyupbit) 라이브러리를 이용하여 upbit 거래소에서 가상화폐를 자동매매

## 언어
Python 3.8

## 테스트
 - 업비트 Open API(https://upbit.com/service_center/open_api_guide)
 - 자산조회, 주문조회, 주문하기 체크 후 Open API Key 발급
 - test.py를 본인의 Key값으로 변경
 - test.py를 실행

## 환경 설정
 - 아나콘다 Python 3.8 버전 설치(https://docs.conda.io/en/latest/miniconda.html)
 - pip install pyupbit
 - pip install schedule
 - conda install -c conda-forge fbprophet
 - pip install pystan --upgrade

## 슬랙 설정
 - 슬랙 워크스페이스 생성
 - 슬랙 API(https://api.slack.com/apps?new_app=1)
 - Create New App를 눌러 이름과 사용할 워크스페이스 설정
 - OAuth & Permissions(https://api.slack.com/apps/A030V192GA3/oauth?) 클릭
 - Bot Token Scopes 메뉴의 Add an OAuth Scope를 클릭하여 chat:write 권한을 부여
 - OAuth Tokens & Redirect URLs 메뉴의 Install to Workspace을 클릭하여 권한 부여
 - Bot User OAuth Token을 복사하여 tradinghot.py의 myToken값을 변경
 - tradinghot.py의 myWorkspace값을 생성한 워크스페이스 이름으로 변경
