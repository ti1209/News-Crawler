# News Crawler
-> 보안뉴스 중 가장 많이 본 기사 탭에 있는 기사 중 1페이지(약 20개) 정적 크롤링 해보기

* Settings : Pycharm, Scrapy

<원 파일 구조>  
news    
&nbsp;&nbsp;└ .idea(프로젝트 생성 시 자동생성, Github에 파일 X)    
&nbsp;&nbsp;└ venv(프로젝트 생성 시 자동생성, Github에 파일 X)  
&nbsp;&nbsp;└ .DS_Store(프로젝트 생성 시 자동생성, Github에 파일 X)  
&nbsp;&nbsp;└ news   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└ news.json    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└ news.xlsx   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└ news  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└ _pycache_(프로젝트 생성 시 자동생성, Github에 파일 X)    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└ _init_.py(프로젝트 생성 시 자동생성, Github에 파일 X)        
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└ items.py    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└ middlewares.py    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└ piplines.py    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└ settings.py    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└ spiders    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└ _pycache_(프로젝트 생성 시 자동생성, Github에 파일 X)    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└ _init_.py  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└ news_spider.py  
