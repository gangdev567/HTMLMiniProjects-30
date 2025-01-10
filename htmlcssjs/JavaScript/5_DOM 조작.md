네, 5장의 주제인 JavaScript의 DOM 조작에 대해 여러 가지 코딩 문제를 만들어 드리겠습니다. 각 문제는 실제 코딩 과제처럼 구성되어 있으며, JavaScript 코드를 작성하여 해결할 수 있습니다.

### 153. 기본적인 DOM 조작 활용하기

다음 HTML과 JavaScript 코드에 기본적인 DOM 조작을 활용하여 문제를 해결해보세요:

```html
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>기본 DOM 조작 예제</title>
</head>
<body>
    <h1 id="title">웹 개발 블로그</h1>
    <p id="description">이곳에 내용이 들어갑니다.</p>
    <button id="changeButton">변경</button>
    <script>
        // 여기에 JavaScript 코드를 작성하세요
    </script>
</body>
</html>
```

이 코드에 다음 조건을 만족하도록 수정하세요:
- `title` 요소의 텍스트를 "JavaScript DOM 조작"으로 변경하세요.
- `description` 요소의 텍스트를 "이곳에 JavaScript를 사용하여 DOM을 조작합니다."로 변경하세요.
- `changeButton` 요소를 클릭하면 `title` 요소의 텍스트를 "변경됨"으로, `description` 요소의 텍스트를 "버튼을 클릭했습니다."으로 변경하는 이벤트 리스너를 추가하세요.
- `document` 객체를 사용하여 요소를 선택하고 조작하세요.

### 154. 요소 선택과 조작 활용하기

다음 HTML과 JavaScript 코드에 요소 선택과 조작을 활용하여 문제를 해결해보세요:

```html
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>요소 선택과 조작 예제</title>
</head>
<body>
    <div class="container">
        <h1 id="mainTitle">웹 개발 블로그</h1>
        <ul id="list">
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
        </ul>
        <button id="addButton">항목 추가</button>
    </div>
    <script>
        // 여기에 JavaScript 코드를 작성하세요
    </script>
</body>
</html>
```

이 코드에 다음 조건을 만족하도록 수정하세요:
- `mainTitle` 요소의 텍스트를 "DOM 조작 예제"로 변경하세요.
- `list` 요소의 모든 `<li>` 요소의 텍스트 색상을 파란색으로 변경하세요.
- `addButton`을 클릭하면 "새 항목" 텍스트를 가진 새로운 `<li>` 요소를 `list` 요소의 끝에 추가하는 이벤트 리스너를 추가하세요.
- `querySelector`와 `querySelectorAll` 메서드를 사용하여 요소를 선택하고 조작하세요.

### 155. 요소 생성 및 삭제 활용하기

다음 HTML과 JavaScript 코드에 요소 생성 및 삭제를 활용하여 문제를 해결해보세요:

```html
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>요소 생성 및 삭제 예제</title>
</head>
<body>
    <div id="container">
        <h1>웹 개발 블로그</h1>
        <button id="createButton">요소 생성</button>
        <button id="deleteButton">요소 삭제</button>
    </div>
    <script>
        // 여기에 JavaScript 코드를 작성하세요
    </script>
</body>
</html>
```

이 코드에 다음 조건을 만족하도록 수정하세요:
- `createButton`을 클릭하면 `<p>` 요소를 생성하고 "새로운 요소가 생성되었습니다." 텍스트를 추가한 후 `container` 요소의 끝에 추가하는 이벤트 리스너를 추가하세요.
- `deleteButton`을 클릭하면 `container` 요소의 마지막 자식 요소를 삭제하는 이벤트 리스너를 추가하세요.
- `createElement` 메서드를 사용하여 새로운 요소를 생성하고, `appendChild` 메서드를 사용하여 요소를 추가하세요.
- `removeChild` 메서드를 사용하여 요소를 삭제하세요.

### 156. 이벤트 리스너 추가 활용하기

다음 HTML과 JavaScript 코드에 이벤트 리스너 추가를 활용하여 문제를 해결해보세요:

```html
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>이벤트 리스너 예제</title>
</head>
<body>
    <div class="container">
        <h1 id="title">웹 개발 블로그</h1>
        <button id="clickButton">클릭</button>
        <input type="text" id="inputField">
        <div id="output"></div>
    </div>
    <script>
        // 여기에 JavaScript 코드를 작성하세요
    </script>
</body>
</html>
```

이 코드에 다음 조건을 만족하도록 수정하세요:
- `clickButton`을 클릭하면 `title` 요소의 텍스트를 "버튼이 클릭되었습니다."로 변경하는 이벤트 리스너를 추가하세요.
- `inputField`에 텍스트를 입력하고 엔터 키를 누르면 입력된 텍스트를 `output` 요소에 추가하는 이벤트 리스너를 추가하세요.
- `container` 요소를 마우스 오버하면 배경색상을 노란색으로, 마우스 아웃하면 원래 색상으로 변경하는 이벤트 리스너를 추가하세요.
- `addEventListener` 메서드를 사용하여 이벤트 리스너를 추가하세요.

### 157. 복잡한 DOM 조작 활용하기

다음 HTML과 JavaScript 코드에 복잡한 DOM 조작을 활용하여 문제를 해결해보세요:

```html
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>복잡한 DOM 조작 예제</title>
</head>
<body>
    <div class="container">
        <h1 id="mainTitle">웹 개발 블로그</h1>
        <ul id="todoList">
            <li>HTML 학습</li>
            <li>CSS 학습</li>
            <li>JavaScript 학습</li>
        </ul>
        <input type="text" id="todoInput">
        <button id="addTodoButton">추가</button>
        <button id="clearButton">모두 삭제</button>
    </div>
    <script>
        // 여기에 JavaScript 코드를 작성하세요
    </script>
</body>
</html>
```

이 코드에 다음 조건을 만족하도록 수정하세요:
- `mainTitle` 요소의 텍스트를 "TODO 리스트"로 변경하세요.
- `addTodoButton`을 클릭하면 `todoInput`에 입력된 텍스트를 `todoList`에 새로운 `<li>` 요소로 추가하는 이벤트 리스너를 추가하세요.
- `clearButton`을 클릭하면 `todoList`의 모든 `<li>` 요소를 삭제하는 이벤트 리스너를 추가하세요.
- 각 `<li>` 요소를 클릭하면 해당 요소의 텍스트 색상을 빨간색으로 변경하는 이벤트 리스너를 추가하세요.
- `todoList`의 모든 `<li>` 요소에 마우스 오버 시 배경색상을 노란색으로, 마우스 아웃 시 원래 색상으로 변경하는 이벤트 리스너를 추가하세요.
- `querySelector`와 `querySelectorAll` 메서드를 사용하여 요소를 선택하고 조작하세요.
- `createElement` 메서드를 사용하여 새로운 요소를 생성하고, `appendChild` 메서드를 사용하여 요소를 추가하세요.
- `removeChild` 메서드를 사용하여 요소를 삭제하세요.

### 158. DOM 조작의 상속과 다형성 이해하기

다음 HTML과 JavaScript 코드에 DOM 조작의 상속과 다형성을 고려하여 문제를 해결해보세요:

```html
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DOM 조작 상속과 다형성 예제</title>
</head>
<body>
    <div class="container">
        <h1 id="title">웹 개발 블로그</h1>
        <div class="element" id="element1">요소 1</div>
        <div class="element" id="element2">요소 2</div>
        <div class="element" id="element3">요소 3</div>
        <button id="changeButton">변경</button>
    </div>
    <script>
        // 여기에 JavaScript 코드를 작성하세요
    </script>
</body>
</html>
```

이 코드에 다음 조건을 만족하도록 수정하세요:
- `Element` 클래스를 정의하고, `id`, `text` 속성과 `changeText` 메서드를 포함하세요.
- `CustomElement` 클래스를 `Element`로부터 상속받고, `changeColor` 메서드를 추가하세요.
- `element1`, `element2`, `element3` 요소를 각각 `Element`와 `CustomElement` 객체로 생성하세요.
- `changeButton`을 클릭하면 각 요소의 텍스트를 "변경됨"으로 변경하고, `CustomElement` 객체의 경우 배경색상을 파란색으로 변경하는 이벤트 리스너를 추가하세요.
- `querySelector` 메서드를 사용하여 요소를 선택하고, `textContent` 속성을 사용하여 텍스트를 변경하세요.
- `style` 속성을 사용하여 배경색상을 변경하세요.

이러한 코딩 문제들은 JavaScript의 DOM 조작 개념을 다양하게 활용하는 방법을 보여줍니다. 학생들은 실제 웹 페이지에서 DOM을 효과적으로 조작하는 방법을 학습할 수 있으며, 이를 통해 동적 웹 페이지를 구현할 수 있습니다. 요소 선택, 생성, 삭제, 이벤트 처리 등의 기본적인 DOM 조작부터 복잡한 상속과 다형성 활용까지 다양한 측면에서 DOM 조작을 다룰 수 있습니다.