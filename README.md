# TTTserver
TicTacToc Server

본격 모바일 멀티플레이 틱택토 게임!

# 서버 사용방법

## 회원가입
신규 유저 등록
### 요청

### 결과

## 로그인

### 요청
> [POST] /users/signup

전달값
</pre>
{
'username' : 'hongildon',
'password':'hon1234',
'name':'홍길동'
}
</pre>
### 결과
### 성공
form-data 샘플
</pre>
{
'_id':1234567890',
'username':'hongildon',
'name':'홍길동'
}
</pre>
### 실패
<pre>
{
'message':'400 Bad Request'
}
</pre>
### 결과
