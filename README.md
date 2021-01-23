# CSS_Bootstrap4FromScratchWith5Projects

VS Code 애드온 추천

Live Server

Prettier

Bracket Pair Colorizer

vscode-icons

emitte(VS코드는 기본으로 깔려 있음)

1 rem : 16px

em: 상위 요소 크기로 사이즈 결정
만약 1.5em이면 상위요소 폰트 사이즈의 1.5배로 하겠다는 뜻

rem: 문서의 최상위 요소 html의 사이즈를 기준으로 배율을 정하겠다는 뜻

# 부트스트랩4 media query 사이즈
 - xs(.col-): < 576px
 - sm(.col-sm-): >= 576px(컨테이너 너비: 540px)
 - md(.col-md-): >= 768px(컨테이너 너비: 720px)
 - lg(.col-lg-): >= 992px(컨테이너 너비: 960px)
 - xl(.col-xl-): >=1200px(컨테이너 너비: 1140px)
=================================================
# SCSS 컴파일러
 - http://koala-app.com/ 

# 부트스트랩 4.5.3 소스코드 다운로드 경로

 - https://getbootstrap.com/docs/4.5/getting-started/download/

# Lightbox for Bootstrap
 - http://ashleydw.github.io/lightbox
 - 이미지 링크를 갤러리 스타일로 만들어 주는 시스템
 - css cdn
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/ekko-lightbox/5.3.0/ekko-lightbox.css" integrity="sha512-Velp0ebMKjcd9RiCoaHhLXkR1sFoCCWXNp6w4zj1hfMifYB5441C+sKeBl/T/Ka6NjBiRfBBQRaQq65ekYz3UQ==" crossorigin="anonymous" />
 - js cdn
  <script src="https://cdnjs.cloudflare.com/ajax/libs/ekko-lightbox/5.3.0/ekko-lightbox.js" integrity="sha512-YibiFIKqwi6sZFfPm5HNHQYemJwFbyyYHjrr3UT+VobMt/YBo1kBxgui5RWc4C3B4RJMYCdCAJkbXHt+irKfSA==" crossorigin="anonymous"></script>
 - js min cdn
  <script src="https://cdnjs.cloudflare.com/ajax/libs/ekko-lightbox/5.3.0/ekko-lightbox.min.js" integrity="sha512-Y2IiVZeaBwXG1wSV7f13plqlmFOx8MdjuHyYFVoYzhyRr3nH/NMDjTBSswijzADdNzMyWNetbLMfOpIPl6Cv9g==" crossorigin="anonymous"></script>

# Slick slider
 - http://kenwheeler.github.io/slick/
 - 가로 슬라이더
 - css cdn
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.9.0/slick.css" integrity="sha512-wR4oNhLBHf7smjy0K4oqzdWumd+r5/+6QO/vDda76MW5iug4PT7v86FoEkySIJft3XA0Ae6axhIvHrqwm793Nw==" crossorigin="anonymous" />
 - css min cdn
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.9.0/slick.min.css" integrity="sha512-yHknP1/AwR+yx26cB1y0cjvQUMvEa2PFzt1c9LlS4pRQ5NOTZFWbhBig+X9G9eYW/8m0/4OXNx8pxJ6z57x0dw==" crossorigin="anonymous" />
 - css theme cdn
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.9.0/slick-theme.css" integrity="sha512-6lLUdeQ5uheMFbWm3CP271l14RsX1xtx+J5x2yeIDkkiBpeVTNhTqijME7GgRKKi6hCqovwCoBTlRBEC20M8Mg==" crossorigin="anonymous" />
 - css theme min cdn
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.9.0/slick-theme.min.css" integrity="sha512-17EgCFERpgZKcm0j0fEq1YCJuyAWdz9KUtv1EjVuaOz8pDnh/0nZxmU6BBXwaaxqoi9PQXnRWqlcDB027hgv9A==" crossorigin="anonymous" />
 - js cdn
  <script src="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.9.0/slick.js" integrity="sha512-eP8DK17a+MOcKHXC5Yrqzd8WI5WKh6F1TIk5QZ/8Lbv+8ssblcz7oGC8ZmQ/ZSAPa7ZmsCU4e/hcovqR8jfJqA==" crossorigin="anonymous"></script>
 - js min cdn
  <script src="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.9.0/slick.min.js" integrity="sha512-HGOnQO9+SP1V92SrtZfjqxxtLmVzqZpjFFekvzZVWoiASSQgSr4cw9Kqd2+l8Llp4Gm0G8GIFJ4ddwZilcdb8A==" crossorigin="anonymous"></script>

=================================================


#class=”h1” : 스타일을 h1와 같이 만들어준다

#class=”display-1” : 얇은 글씨체에 글자를 h1보다 매우 크게 만들어준다(6rem)
 - 1-4까지만 존재

#class=”lead” : 1.25rem, font-weight: 300
글자를 약간 가늘고, 크게 만들어 주목 효과를 준다

# class="text-monospace"
 - 글자가 약간 모노스타일로 변경

<p class="font-weight-bold">Bold Text</p>
 - 글자 볼드
<p class="font-weight-normal">Normal Text</p>
 - 일반적인 글자
<p class="font-italic">Italic Text</p>
 - 이텔릭체
<p class="font-weight-bold">Bold Text</p>
 - 대문자로
<p class="font-weight-normal">Normal Text</p>
 - 소문자로
<p class="font-italic">Italic Text</p>
 - 첫글자만 대문자로

BLOCKQUOTES
<blockquote class="blockquote">
 - 인용구
  <p>This is a blockquote</p>
</blockquote>
<!-- BLOCKQUOTE RIGHT ALIGNED -->
<blockquote class="blockquote text-right">
 - 인용구 오른쪽 정렬
  <p>This is a blockquote aligned right</p>
</blockquote>
<!-- BLOCKQUOTE WITH FOOTER -->
<blockquote class="blockquote text-right">
 - 인용구 오른쪽 정렬
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ant</p>
  <footer class="blockquote-footer">Someone famous in
   - 인용구 마지막 라인, 대쉬있음
    <cite title="Source Title">Source Title</cite>
  </footer>
</blockquote>


<!-- TEXT TRUNCATE -->    
<div class="text-truncate">
 - 여러 라인으로 된 글을 한줄로 줄이고 ... 붙인다
  Lorem, ipsum dolor sit amet consect
  iure odit, debitis pariatur perspic
  quos. Sint magni nulla provident et
</div>

# list-unstyled
 - 리스트에서 앞에 점을 없애준다

# list-inline
 - 리스트를 인라인으로 만들어준다

# text-justify
 - 양쪽 정렬

# text-left
 - 왼쪽 정렬

# text-right
 - 오른쪽 정렬

# text-center
 - 가운데 정렬

# text-sm-right
 - sm사이즈보다 클 때 우측 정렬

# text-md-right
 - md사이즈보다 클 때 우측 정렬

# text-lg-right
 - lg사이즈보다 클 때 우측 정렬

# text-xl-right
 - xl사이즈보다 클 때 우측 정렬


# text-sm-left
 - sm사이즈보다 클 때 좌측 정렬

# text-md-left
 - md사이즈보다 클 때 좌측 정렬

# text-lg-left
 - lg사이즈보다 클 때 좌측 정렬

# text-xl-left
 - xl사이즈보다 클 때 좌측 정렬

 # text-sm-center
 - sm사이즈보다 클 때 중앙 정렬

# text-md-center
 - md사이즈보다 클 때 중앙 정렬

# text-lg-center
 - lg사이즈보다 클 때 중앙 정렬

# text-xl-center
 - xl사이즈보다 클 때 중앙 정렬

<!-- VERTICAL ALIGNMENT -->
 - inline 개체에 사용

# align-baseline
# align-top
# align-bottom
# align-middle
# align-text-top
# align-text-bottom

<!-- TURN BLOCK TO INLINE -->
# d-inline

<!-- TURN INLINE TO BLOCK -->
# d-block

<!-- INLINE BLOCK -->
# d-inline-block

<!-- FLOATS -->
 - 좌 우로 띄운다

# float-left
# float-right
# float-none
 - 띄우지 않는다

<!-- RESPONSIVE FLOATS -->
# float-sm-right

# float-md-right

# float-lg-right

# float-xl-right

# float-XX-left

# float-XX-none

<!-- CLEARFIX -->
 - 좌우 클리어 효과를 준다
 - 부모에 줘야 한다
 - 자식은 float-left, float-right 속성을 가진다

# clearfix

<!-- FIXED TOP -->
 - 화면에 상단에 고정

# fixed-top

<!-- FIXED STICKY -->
 - 스크롤 도중 화면의 최상단에 도달하면 고정된다

# sticky-top

<!-- FIXED BOTTOM -->
 - 바닥에 항상 고정시킨다

# fixed-bottom

<!-- TEXT COLORS -->
# text-XX
 - 글자색
 - primary, secondary, success, info, warning, danger, light, dark, whtie, mute
 - text-black-50 : rgba(0, 0, 0, .5)

<!-- BACKGROUND COLORS -->
# bg-XX
 - 배경색
 - primary, secondary, success, info, warning, danger, light, dark, whtie
 - transparent

<!-- INVISIBLE -->
# invisible
 - 안보임,
 - display-none

<!-- MARGIN -->

# mX - 숫자
 - b : bottom
 - t : top
 - l : left
 - r : right
 - x : left, right
 - y : top, bottom
 - blank : bottom, top, left, right

<!-- PADDING -->
# PX - 숫자
 - b : bottom
 - t : top
 - l : left
 - r : right
 - x : left, right
 - y : top, bottom
 - blank : bottom, top, left, right

<!-- HORIZONTAL CENTERING -->
# mx-auto
 - 가운데 정렬
 - margin-left: auto; margin-right: auto;

<!-- WIDTH CLASSES -->
# w-XX
 - 25, 50, 75, 100(이 외에는 안됨)
 - auto

<!-- WIDTH CLASSES -->
# h-XX
 - 25, 50, 75, 100(이 외에는 안됨)
 - auto

<!-- BORDERS -->
# border-XX
 - top, left, right, bottom
 - 그냥 border 쓰면 전체

<!-- BORDER COLORS -->
# border-XX
 - primary, secondary, success, info, warning, danger, light, dark, white

<!-- BORDER RADIUS -->
# rounded-XX
 - -XX없으면 전체
 - top, left, bottom, right
 - rounded-0

<!-- Custom Media Query -->

@media (min-width: 576px) {
    body {
        background: red;
    }
}

# btn
 - 버튼

# btn-XX
 - primary, secondary, success, info, warning, danger, light, dark, link
 - 버튼으로 변경 가능한 것: a, button, input type="button", input type="submit", input type="reset"

# btn-outline-XX
 - 흰색 버튼에 테두리 색깔이 다름
 - primary, secondary, success, info, warning, danger, light, dark, link

[버튼 사이즈]
# btn-XX
 - lg: 크게
 - sm: 작게
 - block: 블록처럼 라인 전체

[버튼 액티브]
# active
 - 버튼을 누른것 처럼 됨

# disabled
 - 버튼이 해제된것 처럼 보임

[토글 버튼]
 - class="btn btn-primary" data-toggle="button"

# btn-group
 - 내부에 있는 버튼들을 그룹을 만들어 준다
 - 양쪽에 라운드처리되나, 중간 버튼은 라운드 처리 되지 않아 세트 처럼 보인다

# btn-toolbar
 - 버튼 그룹을 모아서 툴바 생성

# btn-group-vertical
 - 내부에 있는 버튼들을 그룹을 만들어 세로로 정렬한다
 - 양쪽에 라운드처리되나, 중간 버튼은 라운드 처리 되지 않아 세트 처럼 보인다

[드랍다운 버튼]
# dropdown
 - 드랍다운 버튼 생성하고, 아래 div에 dropdown-menu, dropdown-item을 생성한다
 - 드랍다운 버튼에 class="btn btn-primary dropdown-toggle" data-topggle="dropdown"을 추가해야 한다
 - 구분자는 class="dropdown-divider"로



























