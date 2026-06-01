# coupang_crawling
Coupang, Coupang Wing 카테고리별 Top10 크롤링

접근 : coupang robot.txt 특성상 playwright로는 힘들어 BeautifulSoup로 변경
js -> py 로 변경

쿠팡에서는 기본적으로 크롤링을 허용하지 않음.

재시도: 쿠팡에서는 자동적인 크롤링 방식은 허용하지 않으나 수동으로 수집하는 방식을 막진 않음. 
-> 자동화된 접근이 아닌 사람이 직접 하는것 처럼 속여야함
1. 속도가 느려야함
2. 접근이나 움직임이 자연스러워야함.

   
coupang에서 둔 제한 때문에 구현 어려움

cluade 에서 웹 캡처 하는 방식 확인해볼 필요 있음
