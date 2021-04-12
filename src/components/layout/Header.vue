<template>
  <div id="header">
		<div class="inner">
			<h1><a href="/vue-hour"><img src="../../assets/images/common/logo.png" alt="계룡시 어린이감성체험장"></a></h1>
			<div class="topLink">
				<ul>
					<li><a href="#">로그인</a></li>
					<!-- <li><a href="#">로그아웃</a></li> -->
					<li><a href="#">회원가입</a></li>
					<!-- <li><a href="#">마이페이지</a></li> -->
				</ul>
				<div class="topSearch">
					<form method="post" action="">
						<input type="text" name="">
						<input type="submit" name="" class="btnTopSearch" value="검색">
					</form>
				</div>
				<a href="#" class="btnBlog" title="새창열림" target="_blank">네이버 블로그 바로가기</a>
				<a href="#" class="btnInsta" title="새창열림" target="_blank">인스타그램 바로가기</a>
			</div>
		</div>
		<div id="gnb">
			<ul>
				<li><a href="/vue-hour">어린이감성체험장안내</a></li>
				<li><a href="/vue-hour/About">체험놀이</a></li>
				<li><a href="#">교육프로그램</a></li>
				<li><a href="#">장난감도서관</a></li>
				<li><a href="#">알림마당</a></li>
			</ul>
		</div>
	</div>
</template>

<script>
export default {
    name: "header"
}
</script>

<style>

</style>
