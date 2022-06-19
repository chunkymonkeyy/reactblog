# reactblog
## 리액트2강 - jsx문법

1. class 아니고 className  
2. 중괄호  
변수를 html에 꽂아넣기 ==> **{ 변수명 }** 이렇게.  
데이터를 꽂아넣는다 = 데이터바인딩  
3. 스타일  
style넣을땐 **style={ {스타일명:'값', fontSize : '16px'} }** 이렇게

에러메세지는 터미널/브라우저에서 확인
만약 여기서 에러가 안뜬다? 개발자도구 f12 >console 들어가서 직접 확인해야함.

## 리액트3강 - state쓰면 좋은점

return () 안에는 <>태그로 시작해 태그로 끝나야함  
자료잠깐 저장할때 state씀 = 변수랑 똑같은 역할.
**useState** 로 만든다.
1. import { useState }  
2. useState(보관할자료)  
3. let[작명,작명]  let [a, b] = useState('남자코트추천');  

state 언제쓸까?? 
state는 변경되면 >> state쓰던 html이 자동 재렌더링됨. 자동으로 알아서 바뀜
(그냥 변수는 안됨)

즉, 변동시 자동으로 html에 반영되게만들고 싶으면 state쓴다.
자주변경될거같은 html부분은 state로 만들어놓기. (날짜같은거)
