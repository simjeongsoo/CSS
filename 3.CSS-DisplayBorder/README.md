## CSS display & border
* 블록레벨요소 : 자기가 속한 영역의 너비를 모두 차지하여 블록을 형성  
ex) div, p, h1  
* 인라인 요소 : 자기에게 필요한 만큼의 공간만 차지  
ex) span, a  

1. display 속성  
= 요소를 블록과 인라인 요소중 어느쪽으로 처리할지 정의  
```
/*블록 레벨 요소인 div 요소를 인라인으로 처리하고 싶다면*/
div{ display: inline; }

/*인라인 요소인 a 요소를 블록 레벨로 처리하고 싶다면*/
a{ display: block; }
```
- 속성값 
inline : 인라인으로 처리   
block : 블록 레벨로 처리  
inline-block : 인라인으로 배치하되, 블록 레벨 요소의 속성을 추가할 수 있도록 처리  
none : 디스플레이(표시) 하지 않음  

2. border 속성  
= 요소가 차지하고 있는 영역에 테두리를 그릴 수 있음  
속성값으로 테두리의 두께,모양,크기 등을 함께 지정 할 수 있는데 이것을 ‘단축속성’ 이라고 함   
`span{ border: 2px solid green; }`

- 하위 속성  
border-color : color 정의 방식과 동일  
border-width : thin, midium, thick 등의 키워드 또는 px, em, rem 등의 단위  
border-style : none(기본값), solid(직선), dotted(점선) dashed(긴 점선) 등  
