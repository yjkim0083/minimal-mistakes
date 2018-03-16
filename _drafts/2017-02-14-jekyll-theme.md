---
title: GitHub Pages 블로그 만들기
categories:
  - Jekyll
tags:
  - Jekyll
  - GitHub Pages
  - Blogging
  - Ruby
  - 블로그
---

 GitHub에서는 [GitHub Pages](https://pages.github.com/){:target="\_blank"} 라는 호스팅 서비스를 제공하고 있는데, 이를 이용하면 개인 페이지(블로그)를 무료로 생성할 수 있다.

## Jekyll Theme
* Jekyll은 홈페이지의 소개답게 Blog-Aware Site Generator이기 때문에, 사용방법 또한 블로그의 구조를 잘 나타내고 있다.
* 보통 \_includes, \_layouts, \_posts 등의 폴더가 생기고, 이 폴더에 html과 md 파일을 작성하여 이들이 조합된 사이트를 만들어낸다.
* 자세한 내용은 [Jekyll(한국어)](https://jekyllrb-ko.github.io/){:target="\_blank"} 홈페이지를 참고하면 된다.
* 이렇게 후루룩 넘어가는 이유는 처음부터 하나하나 만들지 않아도, 이미 위의 작업을 해서 정리한 여러 **테마** 들이 있기 때문이다.
* http://jekyllthemes.org/ , https://jekyllthemes.io/ , http://themes.jekyllrc.org/

## Lanyon Theme
* Lanyon은 Jekyll에서 사용하는 Theme중에 하나이다~


ruby 설치 - [ruby download](http://rubyinstaller.org/downloads/){:target="\_blank"}



ruby dk 설치 - [ruby download](http://rubyinstaller.org/downloads/){:target="\_blank"}
bundler 설치 - gem install bundler
gem file 수정 -
bundle install -
bundle exec jekyll serve
환경변수 SSL_CERT_FILE를 [링크](http://curl.haxx.se/ca/cacert.pem){:target="\_blank"}에서 받아 설정해준다.
다시 bundle exec jekyll serve










객체를 생성하면 eden 영역으로 할당됨
eden이 꽉차면, 살아있는 객체(live 객체)를 확인함
eden에서 survivor로 이동됨. from으로 이동되고 가비지컬렉션이 되고 나면 to로 이동됨
survivor에서도 live인 애들은 from으로 이동되고 가비지컬렉션을 하고, 그 담에 to로 이동됨 이런 것을 마이너 gc라고 이야기함
live라 from으로 이동될 때 카운트를 하나씩 올려주게 된다.
카운트가 높으면,






TPMC??

TPS는 성능 지표로 많이 쓰게 됨 초당 리퀘스트라고 생각하면 됨
API의 무게에 따라 TPS에 오류가 있을 수 있기 때문에  피크때의 호출된 페이지를 보고 그때의 페이지들의 비율을 보고 TPS를 분석함
