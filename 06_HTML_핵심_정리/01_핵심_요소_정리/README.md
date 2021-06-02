## HTML 핵심 정리
### 핵심 요소 정리
- **div** 블록(상자) 요소 : 특별한 의미가 없는 구분을 위한 요소. (Division)
- **h1** 블록(상자) 요소 : 제목을 의미하는 요소. (Heading)
- **p** 블록(상자) 요소 : 문장을 의미하는 요소. (Paragraph) -> div로 사용 가능
- **img** 인라인(글자) 요소 : 이미지를 삽입하는 요소. (Image)
- **h1 ~ h6** 블록(상자) 요소 : 제목을 의미하는 요소. (Heading), 숫자가 작을수록 더 중요한 제목을 정의.
- **ul** 블록(상자) 요소 : ul 순서가 필요없는 목록의 집합을 의미(Unordered LIst)
- **li** 블록(상자)요소 : 목록 내 각 항목 (List Item)
- ul 과 li 는 하나의 세트이다.
- **a** 인라인(글자) 요소 : 다른/같은 페이지로 이동하는 하이퍼링크를 지정하는 요소 (Anchor)
- **span** 인라인(글자) 요소 : 특별한 의미가 없는 구분을 위한 요소
- **br** 인라인(글자)요소 : 줄바꿈 요소. (Break)
- **input** 인라인(글자)요소 + 블록(상자)요소 = 인라인블록요소 : 사용자가 데이터를 입력하는 요소.
```
<label><input type="checkbox" /> Apple </label> 
// 인라인(글자)요소: 라벨 가능 요소(input)의 제목
```
```
<label><input type="checkbox" checked /> Apple </label> 
// 체크박스 입력 요소 체크됨
``` 
``` 
<label><input type="radio" checked /> Apple </label> 
// 1개만 선택 가능 (택1)
```
- table 테이블 요소 : 표 요소 행(Row)과 열(Column)의 집합
```
 <table>
 	<tr> // 행(Row)을 지정하는 요소.
 		<td>A</td> <td>B/td>  //  열(Column)을 지정하는 요소. (Table Data)
 	</tr> 
 	<tr> // 행(Row)을 지정하는 요소.
 			<td>A</td> <td>B/td>  //  열(Column)을 지정하는 요소. (Table Data)
 		</tr>
 </table>
 
 // AB
 // CD 로 출력
``` 