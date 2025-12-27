---
layout: links
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_links

# publish date (used for seo)
# if not specified, site.time will be used.
#date: 2022-03-03 12:32:00 +0000

# for override items in _data/lang/[language].yml
#title: My title
#button_name: "My button"
# for override side_and_top_nav_buttons in _data/conf/main.yml
#icon: "fa fa-bath"

# seo
# if not specified, date will be used.
#meta_modify_date: 2022-03-03 12:32:00 +0000
# check the meta_common_description in _data/owner/[language].yml
#meta_description: ""

# optional
# please use the "image_viewer_on" below to enable image viewer for individual pages or posts (_posts/ or [language]/_posts folders).
# image viewer can be enabled or disabled for all posts using the "image_viewer_posts: true" setting in _data/conf/main.yml.
#image_viewer_on: true
# please use the "image_lazy_loader_on" below to enable image lazy loader for individual pages or posts (_posts/ or [language]/_posts folders).
# image lazy loader can be enabled or disabled for all posts using the "image_lazy_loader_posts: true" setting in _data/conf/main.yml.
#image_lazy_loader_on: true
# exclude from on site search
#on_site_search_exclude: true
# exclude from search engines
#search_engine_exclude: true
# to disable this page, simply set published: false or delete this file
#published: false


# you can always move this content to _data/content/ folder
# just create new file at _data/content/links/[language].yml and move content below.
###########################################################
#                Links Page Data
###########################################################
page_data:
  main:
    header: "링크"
    info: "각종 링크들을 정리해뒀습니다."

  # To change order of the Categories, simply change order. (you don't need to change list order.)
  category:
    - title: "경제학"
      type: id_econ
      color: "gray"
    - title: "웹 디자인"
      type: id_webdesign
      color: "#F4A273"
    - title: "시계"
      type: id_watch
      color: "#62b462"
    - title: "피아노"
      type: id_piano
      color: "#2c74f2"


  list:
    # watch
    - type: id_watch
      title: "신세계면세점"
      url: "https://www.ssgdfs.com/kr/dispctg/ctg/watch_jewelry/mens_watch"
      info: "신세계면세점 시계 코너입니다. 가끔 세일을 많이 하는 상품들이 있습니다."
    - type: id_watch
      title: "Etsy"
      url: "https://www.etsy.com/?gad_source=1&gad_campaignid=20454739093&gbraid=0AAAAADrDmr_1W1kJtaL3N7aQ4gU4v5-al&gclid=Cj0KCQjww-HABhCGARIsALLO6XxusEIfVyTOaKFZ_dqQnUEG6rmX-Or7dYI_2v1xPlh-VInxJgVrQpoaAjKrEALw_wcB"
      info: "주문제작 사이트인데, 시계줄(주로 레더)을 저렴한 가격으로 구할 수 있다고 합니다."

    # econ
    - type: id_econ
      title: "한국은행 보도자료"
      url: "https://www.bok.or.kr/portal/singl/newsData/list.do?pageIndex=&targetDepth=3&menuNo=201263&syncMenuChekKey=1&depthSubMain=&subMainAt=&searchCnd=1&searchKwd=&depth2=200038&depth3=201263&date=&sdate=&edate=&sort=1&pageUnit=10"
      info: "한국은행의 보도자료를 올리는 페이지로 BOK이슈노트, 통신/경제전망/금안보고서 등을 통해 시사 상식을 채울 수 있을 것입니다."
    - type: id_econ
      title: "한국은행 경제연구원 보도자료"
      url: "https://www.bok.or.kr/imer/singl/rsrchrData/list.do?pageIndex=1&targetDepth=2&menuNo=500535&syncMenuChekKey=2&searchCnd=1&searchKwd=&date=&sdate=&edate=&sort=1&pageUnit=10"
      info: "한국은행 산하 국책연구소 경제연구원의 보도자료로, 학술적이지만 재미있는 자료들이 많습니다."
    - type: id_econ
      title: "KDI"
      url: "https://www.kdi.re.kr/"
      info: "한국의 대표적 국책연구소 한국개발연구원의 홈페이지입니다."
    - type: id_econ
      title: "John Bates Clark Medal"
      url: "https://www.aeaweb.org/about-aea/honors-awards/bates-clark"
      info: "AEA에서 수상하는 John Bates Clark Medal 수상자 및 업적을 소개하는 페이지로, 경제학계 트렌드 파악에 도움이 됩니다."
    - type: id_econ
      title: "Fed"
      url: "https://www.federalreserve.gov/"
      info: "미국 중앙은행 Fed의 홈페이지입니다."

    # webdesign
    - type: id_webdesign
      title: "W3Schools"
      url: "https://www.w3schools.com/"
      info: "W3Schools는 웹의 모든 주요 언어로 된 무료 온라인 자습서, 참조 및 연습을 제공합니다. HTML, CSS, JavaScript, Python, SQL, Java 등과 같은 인기 있는 주제를 다룹니다."
      
    # piano
    - type: id_piano
      title: "Reminiscence"
      url: "https://www.youtube.com/watch?v=QdfcrCxQFfU&list=RDQdfcrCxQFfU&start_radio=1"
      info: "게임 테일즈위버 OST인 Reminiscence(회상)이란 곡입니다. 슬프면서도 기승전결이 확실한게 아주 취향저격입니다."
    - type: id_piano
      title: "Last Carnival"
      url: "https://www.youtube.com/watch?v=0c4-bXDBIss&list=RD0c4-bXDBIss&start_radio=1"
      info: "일본 뉴에이지 그룹 Acoustic Cafe의 Last Carnival이란 곡입니다. 피아노 인생 2번째로 연습한 곡입니다."
    - type: id_piano
      title: "Merry Christmas Mr. Lawrence"
      url: "https://www.youtube.com/watch?v=1OZDaRhHHyM&list=RD1OZDaRhHHyM&start_radio=1"
      info: "일본 유명 작곡가 류이치 사카모토가 작곡한, 영화 '전장의 크리스마스'의 제목이자 OST입니다. 류이치 사카모토는 좋은 노래가 많아 뭐라도 한 번 연습해보고 싶은데, 언제 할 지 모르겠네요."
    - type: id_piano
      title: "Romance"
      url: "https://www.youtube.com/watch?v=oYfM77jcUt8&list=RDoYfM77jcUt8&start_radio=1"
      info: "2005년작 한국 느와르 영화'달콤한 인생'의 OST입니다. 멜로디 이전의 독백이 인상적입니다."
    - type: id_piano
      title: "Epilogue"
      url: "https://www.youtube.com/watch?v=BvQxBq9Yfh8&list=RDBvQxBq9Yfh8&start_radio=1"
      info: "2003년작 한국 공포영화 '장화, 홍련'의 OST입니다. 음들의 시간을 미세하게 조절하는 표현적 타이밍과 리듬적 변이가 인상깊습니다."
    - type: id_piano
      title: "Graceful Ghost"
      url: "https://www.youtube.com/watch?v=k_kQAR0RLDQ&list=RDk_kQAR0RLDQ&start_radio=1"
      info: "미국의 작곡가 William Bolcom이 작곡한 유명한 피아노 곡입니다. 돌아가신 아버지를 추모하기 위한 곡이라는 점을 알고나면 왠지 모르게 슬프게 느껴지는 곡입니다."
    - type: id_piano
      title: "Sentimental"
      url: "https://www.youtube.com/watch?v=MJw4xjB73PE&list=RDMJw4xjB73PE&start_radio=1"
      info: "한국의 작곡가 겸 피아니스트 이진욱의 Sentimental이란 곡입니다. 공부할 때 정신차리기 좋은 곡입니다."


---
