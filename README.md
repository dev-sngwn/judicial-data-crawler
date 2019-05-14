# judicial-data-crawler
> [국가법령정보센터](http://www.law.go.kr/precSc.do?tabMenuId=tab67#licPrec206136)의 판례 데이터를 JSON 형태로 저장하는 크롤러입니다.
  
  
## Requirements
> [ChromeDriver](http://chromedriver.chromium.org/downloads) (Chrome 버전에 맞게 다운로드 후, 소스에서 PATH 설정)
> Selenium
  
  
## Data Download
> [judicial-data.json](https://www.dropbox.com/s/q9dhqype3rtn6kl/judicial-data.json?dl=0) (80,216 sets)
  
  
## Quick Peek
* json_data[1]  

KEY | VALUE 
:--------------:|:------------------------------------------------------------------------------------------------------------
피고인 | '망 피고인 1 외 2인'
재심청구인 | '재심청구인 1 외 2인'
재항고인 | '검사'
원심결정 | '광주고법 2015. 7. 10.자 2014로157 결정'
주문 | '재항고를 기각한다.'
이유 | '재항고이유를 판단한다. 1.  사건의 경위와 쟁점 가.  재심청구인들은...'


* json_data[2]  
  
KEY | VALUE 
:--------------:|:------------------------------------------------------------------------------------------------------------
채권자, 재항고인 | '주식회사 XX자산관리대부'
채무자 | '채무자'
원심결정 | '서울회생법원 2018. 9. 13.자 2018라100208 결정'
주문 | '원심결정을 파기하고, 사건을 서울회생법원 합의부에 환송한다.'
이유 | '재항고이유를 판단한다. 1.  가. 채무자 회생 및 파산에 관한 법률...'
  
  
## Issue
> * 데이터의 형태가 일정하지 않기 때문에 원하는 데이터를 필터링해서 사용하셔야 합니다.
> * 50,000번째 데이터 부근에서 크롤러가 정지하는 경우가 있습니다. 멈춘 Cell을 직접 클릭해주시면 재개됩니다.
> * 원인 불명의 Exception이 약 50회 발생합니다.
> * 2019.05.14. 현재 사이트 접속이 원활하지 않습니다.
  
  
## License
