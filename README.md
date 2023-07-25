# Game2023

![image](https://github.com/dongjin6539/Game2023/blob/main/game01.png)

게임을 배경으로 뮤직 플레이어, 테트리스 게임을 구현했습니다.
script에서 javascript, jQuery, GSAP 를 사용했습니다.
주기적으로 현재 시간과 사용되고 있는 시스템 정보에 대해 설정했습니다.

## MusicPlayer

![image](https://github.com/dongjin6539/Game2023/blob/main/game02.png)

### 사용
JavaScript를 사용하여 음악 재생 웹 애플리케이션을 구현하는데 사용됩니다. 음악 리스트를 동적으로 생성하고 음악을 재생, 일시정지하며 다음과 이전 음악으로 이동할 수 있는 기능을 가지고 있습니다.

### 메서드
- querySelector: 문서 내에서 특정 선택자에 해당하는 첫 번째 요소를 반환합니다. 선택자는 CSS 선택자를 사용하여 지정할 수 있습니다.
- setAttribute: 요소의 속성 값을 설정합니다. 첫 번째 인수로 속성 이름, 두 번째 인수로 속성 값이 전달됩니다.
- classList: 요소의 클래스를 조작하는 속성으로, add, remove, contains, toggle 등의 메서드를 제공합니다.
- addEventListener: 요소에 이벤트 리스너를 추가합니다. 첫 번째 인수로 이벤트 유형, 두 번째 인수로 이벤트가 발생했을 때 실행할 함수가 전달됩니다.
- querySelectorAll: 문서 내에서 특정 선택자에 해당하는 모든 요소를 NodeList 형태로 반환합니다.
- insertAdjacentHTML: 요소의 특정 위치에 HTML 문자열을 삽입합니다. 첫 번째 인수로 삽입 위치를 지정하는 문자열("beforebegin", "afterbegin", "beforeend", "afterend")을 전달하고, 두 번째 인수로 삽입할 HTML 문자열을 전달합니다.
- innerText: 요소의 텍스트 내용을 설정하거나 가져옵니다.
- getAttribute: 요소의 특정 속성 값을 가져옵니다.
- currentTime와 duration: HTML5 오디오/비디오 요소에서 현재 재생 시간과 전체 재생 시간을 나타내는 속성들입니다.
- play와 pause: HTML5 오디오/비디오 요소의 재생 및 일시정지를 수행하는 메서드입니다.

## Tetris

![image](https://github.com/dongjin6539/Game2023/blob/main/game03.png)


### 사용
JavaScript를 사용하여 테트리스 게임 애플리케이션을 구현하는데 사용됩니다. 게임을 하기 위해서 키보드 입력에 따라 블록을 조작하고, 매칭된 라인을 제거하며 점수를 쌓아나가는 등의 기능이 포함되어 있습니다.

### 메서드
- document.querySelector(): 주어진 CSS 선택자에 해당하는 첫 번째 요소를 반환합니다.
- new Audio(): 주어진 오디오 파일 URL로부터 새로운 Audio 객체를 생성합니다.
- document.createElement(): 주어진 태그 이름에 해당하는 HTML 요소를 생성합니다.
- Node.prepend(): 특정 요소를 해당 노드의 첫 번째 자식으로 추가합니다.
- Node.childNodes: 노드의 모든 자식 노드들을 나타내는 읽기 전용 속성으로, NodeList를 반환합니다.
- Node.classList: 요소의 클래스 목록을 나타내는 읽기 전용 속성으로, 클래스를 추가/제거/토글하는 메서드를 제공합니다.
- Node.remove(): 노드를 해당 노드의 부모에서 제거합니다.
- setInterval(): 주어진 일정한 시간 간격으로 함수를 반복해서 실행합니다.
- clearInterval(): 이전에 설정한 반복 실행을 정지합니다.
- setTimeout(): 주어진 시간 후에 함수를 실행합니다.
- Object.entries(): 객체의 속성과 값을 배열 형태로 변환합니다.
- Math.floor(): 주어진 숫자 이하의 가장 큰 정수를 반환합니다.
- addEventListener(): 특정 이벤트에 대한 이벤트 핸들러를 등록합니다.
