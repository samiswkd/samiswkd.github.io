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

  list:
    -
    # programming
    - type: id_watch
      title: "신세계면세점"
      url: "https://www.ssgdfs.com/kr/dispctg/ctg/watch_jewelry/mens_watch"
      info: "신세계면세점 시계 코너입니다. 가끔 세일을 많이 하는 상품들이 있습니다."
    - type: id_watch
      title: "Etsy"
      url: "https://www.etsy.com/?gad_source=1&gad_campaignid=20454739093&gbraid=0AAAAADrDmr_1W1kJtaL3N7aQ4gU4v5-al&gclid=Cj0KCQjww-HABhCGARIsALLO6XxusEIfVyTOaKFZ_dqQnUEG6rmX-Or7dYI_2v1xPlh-VInxJgVrQpoaAjKrEALw_wcB"
      info: "주문제작 사이트인데, 시계줄(주로 레더)을 저렴한 가격으로 구할 수 있다고 합니다."

    # jekyiiliquid
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
---
