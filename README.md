# ksu_info

##### 경성대를 소개하는 페이지입니다.
--------------
- 경성대 소개

--------------
- 경성대 홍보 영상
  - iframe 태그와 li 태그를 이용하여 동영상을 리스트로 삽입하였다.
```HTML
<div class="ui-bar ui-bar-a">경성대학교 공식 홍보 영상</div><br/>
			<li><iframe width="100%" height="240" src="https://www.youtube.com/embed/sxosP7m_fCc" 
				title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; 
				clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></li><br/>
			<div class="ui-bar ui-bar-a">올해 경성대 입학전형을 알아보자!🙋‍♂️🙋‍♀️ㅣ2023학년도 경성대학교 입학설명회</div><br/>
			<li><iframe width="100%" height="240" src="https://www.youtube.com/embed/0nEKDifWQKs"
				title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; 
				clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></li>
```
--------------
- 경성대 교가와 4K영상
  - audio 태그와 source 태그를 이용하여 오디오를 삽입하였다.
  - a 태그와 id를 이용하여 '이전'과 '다음' 버튼을 만들었다.
```HTML
<div class="ui-bar ui-bar-e">교가와 악보</div><br/>
			<audio controls width="100%" preload="metadata">
				<source src="KS_UNIV_SONG.mp3" type="audio/mp3">
			</audio>	
			<img src="images/musicSheet.jpg" alt="경성대 교가 악보" width="100%">
```
```HTML
<a href="#home"  data-direction="reverse">이전</a>
			<a href="#wizard3-2" data-rel="dialog" data-transition="slide">다음</a>
```

--------------
- 경성대 사진


https://miiin-se.github.io/ksu_info/
