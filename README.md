#index.html

    html 소스 전체를 볼수 있고, 해당 페이지로 링크를 걸어두었습니다.   
    미리보기로 확인하실 수 있습니다,.

#메인

    main_en.html => 영문   
    main_jp.html => 일문   
    main_cnb.html => 중국번체   
    main_cnk.html => 중국간체   

    메인페이지에 보시면 <contents>...</contents> 라는 태그안에 있는 html 코드 전체를 그대로 복사해서 main 페이지 상단부분에 적용시켜주시면 됩니다. 

#상세페이지

    컬러별로 구분했습니다   
    컨텐츠 에디터에 <contents>...</contents> 태그 안에 있는 html 코드 전체를 그대로 넣어주시면 될 것 같습니다.
    (contents 태그는 없어도 됩니다. 복사해서 넣을 소스 구분을 위해서 contents 태그로 랩핑해둔 것 뿐입니다.)
    detail_red.html => 레드버전   
    detail_navy.html => 네이비버전   
    detail_yellow.html => 옐로우버전   
    detail_green.html => 그린버전   
    detail_pink.html => 핑크버전   
    detail_blue.html => 블루버전   

    이미지는 더미로 넣어둔 상태입니다. img 태그의 경로를 설정해주셔서 컨텐츠에 해당하는 이미지를 연결해 주세요.   
    (현재는 detail_***.html 소스 기준 상대경로인 src="./img/detail/..." 로 연결된 상태라 모든 이미지 소스는 엑박상태로 퍼블리싱됩니다.)


    *이미지 설명   
    ./img/common/
    위치,연락처,홈페이지,가격,상점,공지 아이콘입니다.   
    서버 이미지 경로에 맞게 style 내부에 background-image: url(여기 경로를 수정해 주세요)를 수정해 주세요   
    html 소스 381번부터 396번줄 참고    
    위치 아이콘 css : .page-content .tableWrap table li.location::before   
    연락처 아이콘 css : .page-content .tableWrap table li.tel::before   
    홈페이지 아이콘 css : .page-content .tableWrap table li.web::before   
    가격 아이콘 css : .page-content .tableWrap table li.price::before   
    상점 아이콘 css : .page-content .tableWrap table li.cart::before   
    공지 아이콘 css : .page-content .tableWrap table li.noti::before   






