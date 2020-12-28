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