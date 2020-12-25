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
