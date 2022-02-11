## CSS 텍스트 관련 속성  
* font-family : 글꼴 정의  
* font-size : 글자 크기 정의  
* text-align : 정렬 방식 정의  
* color : 글자 색상 정의  

1. font-family  
= 요소를 구성하는 텍스트의 글꼴을 정의  
글꼴명을 속성값으로 지정  
여러개의 글꼴을 연달아 기입하여 우선순위 지정 가능    
```
*{  
	font-family: Times, monospace, serif;  
}
```
-> Times를 우선 지정하되 , 지원되지 않을 경우 monospace를 지정한다    

2. font-size  
= 수치와 단위를 지정해 글자의 크기를 정의    
px : 모니터 상의 화소 하나 크기에 대응하는 절대적인 크기    
rem : `<html>` 태그의 front-size에 대응하는 상대적인 크기    
em : 부모태그(상위태그)의 font-size에 대응하는 상대적인 크기    

`span{ font-size: 16px; }`  
`span{ font-size: 2rm; }`  
`span{ font-size: 1.5em; }` 
h1 : default 32px  
p : default 16px  

3. text-align  
= 블록 내에서 텍스트의 정렬 방식을 정의, 미리 정의된 키워드 값을 지정   
left / right : 왼쪽 또는 오른쪽 정렬   
center : 가운데 정렬한다   
justify : 양끝 정렬한다(마지막줄 제외)  

`p{ text-align: right; }`  

4. color  
= 텍스트의 색상을 정의   
키워드 : 미리 정의된 색상별 키워드를 사용  
RGB 색상 코드 : # + 여섯자리 16진수 값 형태로 지정  
RGB 함수 : Red, Green, Blue 의 수준을 각각 정의해 지정   
`span{ color: red; }`  
`span{ color: #FF0000; }`  
`span{ color: rgb(100%, 0% 0%); }`  

