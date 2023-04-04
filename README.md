
# php8 + Apache2.4 + MySQL 기반으로 구글차트기반 pie 그래프를 실시간 데이터를 받는 페이지
- pizza.php : 차트입력 화면, 5개의 data를 web(데이터베이스명)에 pizza(테이블명)에 저장
- pie.php : 구글차트기반 pie 그래프 화면, Topping1~Topping5(컬럼명)에 내용을 상위 데이터만 가져오게 하여 최근 입력 data를 그래프에 반영되게 함
