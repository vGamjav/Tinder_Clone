# Tinder_Clone
https://junghyeonsu.tistory.com/72 일단 따라하는 중
## package.json에 대하여
npm(노드 패키지 매니저)을 사용하여 패키지를 설치하거나 프로젝트를 관리할 때 사용한다.
npm init 명령어를 사용하면 프로젝트를 시작할 때 package.json 파일을 생성하고 기본 정보를 입력할 수 있다.

## App 컴포넌트를 정의한다.
1. class App extends Component { ... }: App 클래스 컴포넌트를 정의한다. 클래스 컴포넌트는 React의 기본적인 컴포넌트 유형 중 하나로서, React의 Component 클래스를 상속받아야 한다.
2. render() { ... }: render 메서드는 클래스 컴포넌트의 필수 메서드로, 화면에 표시될 JSX 코드를 반환한다.
3. <div className='App'> ... </div>: div 요소를 사용하여 컴포넌트의 렌더링 결과를 감싼다. className 속성을 사용하여 CSS 클래스를 지정할 수 있다.
4. Header 컴포넌트를 App 컴포넌트의 자식으로 추가하여 렌더링한다.
5. export default App;: App 컴포넌트를 모듈로 내보내기 위해 export default 구문을 사용한다. 이렇게 하면 다른 파일에서 import 구문을 사용하여 App 컴포넌트를 불러와 사용할 수 있다.

## CSS 정리
1. display: flex;:Flexbox는 요소들을 행 또는 열로 배열하고, 간격을 조절하고 정렬할 수 있는 기능
2. justify-content: space-between;: 요소들을 Flexbox에서 주 축(main axis)을 따라 공간을 균등하게 분배하여 배치
3. align-items: center;: 요소들을 Flexbox에서 교차 축(cross axis)을 따라 수직 정렬
4. border-bottom: 1px solid #f9f9f9;: .header 클래스의 하단에 1픽셀 두께의 #f9f9f9 색상의 실선(border)이 생성
5. height: 40px;: 이 속성은 요소의 높이를 40픽셀로 지정
6. object-fit: contain;: 이 속성은 이미지와 같은 요소가 지정된 크기로 조정되었을 때, 해당 요소를 화면에 보여주는 방식을 지정. contain 값을 사용하면, 이미지가 요소의 영역에 딱 맞게 들어가도록 크기를 조정
7. margin: 20px;: 이 속성은 요소의 외부 여백(margin)을 20픽셀로 지정(margin 속성은 margin-top, margin-right, margin-bottom, margin-left와 같이 개별적으로 설정 가능)
