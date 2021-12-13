## react-tic-tac-toe

### npm module

- cra

#### `npm install`
#### `npm start`

### logic

- 9(3x3)개의 네모박스 생성 (array) 
- 각각의 네모박스는 X또는 O의 값을 가지고있다 처음에는 빈값
- 각 네모박스 (component)를 클릭 할 때마다 해당 네모박스 index에 값이 들어간다.
- player는 O, X 돌아가면서 값을 넣는다.
- 승리하는 패턴을 만든다 ex) 1, 2, 3
- 매 박스에 값이 들어갈때마다 승리 패턴을 체크한다 (useEffect)
- 승리패턴에 있는 idx값일 경우 해당 플레이어가 승리하게 된다.
- 그 이후에는 게임초기화
- 추가적으로 비겼을때의 예외값도 만들어준다 (모든 array가 빈값이 아닐때)
