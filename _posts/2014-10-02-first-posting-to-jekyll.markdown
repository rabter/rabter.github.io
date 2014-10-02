---
layout: post
title:  "첫 포스팅!"
date:   2014-10-02 15:23:00
categories: jekyll
---

기술 자료 포스팅을 위해 어떤 사이트를 이용할지 고민하다가 github 에서 제공하는 페이지를 이용하면 `markdown` 문서로 블로그처럼 포스팅을 할 수 있어서 바로 만들어봤다. 

[Github Page][github-page] 가이드대로 github 계정에서 `username.github.io` 형식으로 repository를 만들면 공간이 만들어진다. 

마크다운 형식으로 블로깅을 하려면 Jekyll 을 설치해야 한다. Jekyll은 Github Pages 가 지원하고 심플하고 정적 사이트를 생성해준다. 또한 매 페이지에 헤더 및 푸터를 작성하지 않도록 레이아웃 템플릿 기능도 쉽게 할 수 있다.

맥OS 에 Jekyll을 설치하기 위해서는 다음 세 가지가 필요하다. 

1. Ruby - 루비 버전 관리를 위해 rbenv를 추천한다. [rbenv설치가이드][rbenv-install]

2. Bundler - Bundler는 Jekyll처럼 Ruby 소프트웨어에 버전을 명시함으로써 일관된 버전 관리를 해주는 패키지 매니저. 
`gem install bundler` 로 설치한다.

3. Jekyll - 루비 설치 후 아래와 같이 설치한다.
`sudo gem update --system`
`sudo gem install jekyll`

Jekyll 설치가 끝나면 Scaffold 할 수 있다. 
`jekyll new USERNAME.github.io` 

자동으로 _layout, _posts, _site, _config.yml 등 생성해준다. 

code highlighter 기능도 제공해서 코드를 보여줄 때도 보기 쉽게 포스팅 할 수 있다. 

자세한 내용은 아래 참고 사이트에서 확인가능.
[jekyllrb.com][http://jekyllrb.com/docs/home/]
[github help][https://help.github.com/articles/using-jekyll-with-pages]

[rbenv-install]: http://goo.gl/lsp12U
[github-page]: https://pages.github.com/