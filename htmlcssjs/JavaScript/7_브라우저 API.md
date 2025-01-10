네, 7장의 주제인 JavaScript의 브라우저 API에 대해 여러 가지 코딩 문제를 만들어 드리겠습니다. 각 문제는 실제 코딩 과제처럼 구성되어 있으며, JavaScript 코드를 작성하여 해결할 수 있습니다.

### 165. window 객체의 속성과 메서드 활용하기

다음 JavaScript 코드에 window 객체의 속성과 메서드를 활용하여 문제를 해결해보세요:

```javascript
// 여기에 코드를 작성하세요

console.log(windowWidth);  // 현재 창의 너비
console.log(windowHeight);  // 현재 창의 높이
console.log(scrollX);  // 현재 수평 스크롤 위치
console.log(scrollY);  // 현재 수직 스크롤 위치
console.log(location);  // 현재 URL 정보
console.log(history);  // 브라우저 히스토리 정보
console.log(navigator);  // 브라우저 정보
```

이 코드에 다음 조건을 만족하도록 수정하세요:
- `window.innerWidth`를 사용하여 현재 창의 너비를 `windowWidth` 변수에 할당하세요.
- `window.innerHeight`를 사용하여 현재 창의 높이를 `windowHeight` 변수에 할당하세요.
- `window.pageXOffset`를 사용하여 현재 수평 스크롤 위치를 `scrollX` 변수에 할당하세요.
- `window.pageYOffset`를 사용하여 현재 수직 스크롤 위치를 `scrollY` 변수에 할당하세요.
- `window.location` 객체를 `location` 변수에 할당하세요.
- `window.history` 객체를 `history` 변수에 할당하세요.
- `window.navigator` 객체를 `navigator` 변수에 할당하세요.
- 각 변수를 console.log()를 사용하여 출력하세요.

### 166. localStorage와 sessionStorage 활용하기

다음 JavaScript 코드에 localStorage와 sessionStorage를 활용하여 문제를 해결해보세요:

```javascript
// 여기에 코드를 작성하세요

console.log(localStorageData);  // { name: "John Doe", age: 30 }
console.log(sessionStorageData);  // { city: "New York", country: "USA" }
console.log(localStorageLength);  // 2
console.log(sessionStorageLength);  // 2
console.log(cleared);  // true
```

이 코드에 다음 조건을 만족하도록 수정하세요:
- `localStorage`에 "name" 키로 "John Doe" 값을 저장하고, "age" 키로 30 값을 저장하세요.
- `sessionStorage`에 "city" 키로 "New York" 값을 저장하고, "country" 키로 "USA" 값을 저장하세요.
- `localStorage`에 저장된 데이터를 `localStorageData` 변수에 JSON.parse()를 사용하여 파싱하세요.
- `sessionStorage`에 저장된 데이터를 `sessionStorageData` 변수에 JSON.parse()를 사용하여 파싱하세요.
- `localStorage.length`를 `localStorageLength` 변수에 할당하세요.
- `sessionStorage.length`를 `sessionStorageLength` 변수에 할당하세요.
- `localStorage.clear()`를 호출하고 결과를 `cleared` 변수에 할당하세요.
- 각 변수를 console.log()를 사용하여 출력하세요.

### 167. Geolocation API 활용하기

다음 JavaScript 코드에 Geolocation API를 활용하여 문제를 해결해보세요:

```javascript
// 여기에 코드를 작성하세요

console.log(position);  // { coords: { latitude: 37.7749, longitude: -122.4194 } }
console.log(error);  // undefined
```

이 코드에 다음 조건을 만족하도록 수정하세요:
- `navigator.geolocation.getCurrentPosition()` 메서드를 사용하여 현재 위치를 가져오세요.
- 성공 콜백 함수에서 위치 정보를 `position` 변수에 할당하세요.
- 실패 콜백 함수에서 에러 정보를 `error` 변수에 할당하세요.
- `position.coords.latitude`와 `position.coords.longitude`를 사용하여 현재 위치의 위도와 경도를 확인하세요.
- `position`과 `error`를 console.log()를 사용하여 출력하세요.

### 168. 복잡한 브라우저 API 활용하기

다음 JavaScript 코드에 복잡한 브라우저 API 개념을 활용하여 문제를 해결해보세요:

```javascript
// 여기에 코드를 작성하세요

console.log(windowSize);  // { width: 1920, height: 1080 }
console.log(scrollPosition);  // { x: 0, y: 100 }
console.log(locationInfo);  // { href: "https://example.com", pathname: "/path" }
console.log(historyLength);  // 5
console.log(navigatorInfo);  // { userAgent: "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/91.0.4472.124 Safari/537.36" }
console.log(localStorageData);  // { theme: "dark", language: "en" }
console.log(sessionStorageData);  // { userId: "12345", token: "abc123" }
console.log(geolocation);  // { coords: { latitude: 37.7749, longitude: -122.4194 } }
```

이 코드에 다음 조건을 만족하도록 수정하세요:
- `window.innerWidth`와 `window.innerHeight`를 사용하여 현재 창의 크기를 `windowSize` 객체에 저장하세요.
- `window.pageXOffset`와 `window.pageYOffset`를 사용하여 현재 스크롤 위치를 `scrollPosition` 객체에 저장하세요.
- `window.location` 객체의 `href`와 `pathname` 속성을 `locationInfo` 객체에 저장하세요.
- `window.history.length`를 `historyLength` 변수에 할당하세요.
- `window.navigator.userAgent`를 `navigatorInfo` 객체에 저장하세요.
- `localStorage`에 저장된 "theme"과 "language" 값을 `localStorageData` 객체에 저장하세요.
- `sessionStorage`에 저장된 "userId"와 "token" 값을 `sessionStorageData` 객체에 저장하세요.
- `navigator.geolocation.getCurrentPosition()` 메서드를 사용하여 현재 위치 정보를 `geolocation` 객체에 저장하세요.
- 각 변수를 console.log()를 사용하여 출력하세요.

### 169. 브라우저 API의 상속과 다형성 이해하기

다음 JavaScript 코드에 브라우저 API의 상속과 다형성을 고려하여 문제를 해결해보세요:

```javascript
class BrowserAPI {
    // 여기에 코드를 작성하세요
}

class ModernBrowserAPI extends BrowserAPI {
    // 여기에 코드를 작성하세요
}

class LegacyBrowserAPI extends BrowserAPI {
    // 여기에 코드를 작성하세요
}

function useBrowserAPI(api) {
    // 여기에 코드를 작성하세요
}

// 여기에 코드를 작성하세요

console.log(modernResult);  // { width: 1920, height: 1080 }
console.log(legacyResult);  // { width: 1024, height: 768 }
```

이 코드에 다음 조건을 만족하도록 수정하세요:
- `BrowserAPI` 클래스를 정의하고, `getWindowSize` 메서드를 포함하세요.
- `ModernBrowserAPI` 클래스를 `BrowserAPI`로부터 상속받고, `getWindowSize` 메서드를 오버라이드하세요.
- `LegacyBrowserAPI` 클래스를 `BrowserAPI`로부터 상속받고, `getWindowSize` 메서드를 오버라이드하세요.
- `ModernBrowserAPI`의 `getWindowSize` 메서드는 `window.innerWidth`와 `window.innerHeight`를 사용하여 현재 창의 크기를 반환해야 합니다.
- `LegacyBrowserAPI`의 `getWindowSize` 메서드는 고정된 크기 (1024x768) 객체를 반환해야 합니다.
- `useBrowserAPI` 함수를 정의하고, 입력된 `api` 객체의 `getWindowSize` 메서드를 호출하세요.
- `modernBrowserAPI`와 `legacyBrowserAPI` 객체를 생성하고 `useBrowserAPI` 함수를 호출하세요.
- 결과를 `modernResult`와 `legacyResult` 변수에 할당하세요.
- `console.log()`를 사용하여 결과를 출력하세요.

이러한 코딩 문제들은 JavaScript의 브라우저 API 개념을 다양하게 활용하는 방법을 보여줍니다. 학생들은 실제 웹 애플리케이션에서 브라우저 API를 효과적으로 사용하는 방법을 학습할 수 있으며, 이를 통해 동적 웹 페이지를 구현할 수 있습니다. window 객체의 속성과 메서드, localStorage와 sessionStorage, Geolocation API 등의 개념을 이해하고, 이를 실제 상황에 적용하는 방법을 익힐 수 있습니다. 또한 브라우저 API의 상속과 다형성도 이해하고, 이를 실제 상황에 적용하는 방법을 익힐 수 있습니다.