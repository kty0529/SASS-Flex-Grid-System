# SASS-Flex-Grid
**PC 기반 Flexbox Grid System**입니다.
<br>개인 용도로 만들었기 때문에 상상 그 이하의 퀄리티 일 수 있습니다.
<br>
<br>responsive-grid는 반응형을, fixed-grid는 고정형을 지원합니다.

---

## 기본값

1. Container : 1200px
2. Gutter : 30px

## 변수

1. **$container**<br>
컨테이너 기준 크기 기정
2. **$gutter**<br>
컬럼 사이 거터 크기 지정
3. **desktop**<br>
PC 기준 크기, 지정한 값 **이상**에서 작동
4. **$tablet**<br>
Tablet 기준 크기, 지정한 값 **이하**에서 작동
5. **$mobile**<br>
Mobile 기준 크기, 지정한 값 **이하**에서 작동

## 기본 사용
```html
<div class="container">
	<div class="row">
		<div class="col-6 col-tb-8 col-mo-2">PC 6, Tablet 8, Mobile 2</div>

		<div class="col-6 col-tb-4 col-mo-10">PC 6, Tablet 4, Mobile 10</div>
	</div>
</div>
```
