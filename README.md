- 👋 Hi, I’m @ms0130k
- 👀 I’m interested in TDD
- 🌱 I’m currently learning Spring framework

##### 좋은 개발자란
- 일정 준수, 오류 최소화

_Any fool can write code that a computer can understand. Good programmers write code that humans can understand. -Refactoring Improving the Design of Existing Code 15p_

```c
printf("%s로 %s하는 %s입니다.", "취미", "개발", "개발자");
```
```java
System.out.println("일정길이의 메모리에 저장된 정보를 해석하는 방법");
System.out.println("데이터 처리 연산을 지원하도록 소스에서 추출된 연속된 요소");
/*
Service Cloud is an easy-to-use customer service application that can help you provide and track excellent service. It keeps your customers happy and your support team sane, whether your customers reach out to you by email, phone, social media, or other channels from desktops, mobile devices, or apps.
*/
```
```python
print("해석할 대상 메모리에 붙인 이름");
```
```javascript
console.log(`When you have to add a feature to a program but the code is not structrued in a convenient way, first refactor the program to make it easy to add the feature, then add the feature.`);
document.write('Before you start refactoring, make sure you have a solid suite of tests. These tests must be self-checking.');
document.querySelector('body').innerText = 'Refactoring changes the program in small steps, so if you make a mistake, it is easy to find where the bug is.';
```
```javascript
function getTargetFromParentsToChildByClass(el, className) {
	let target = el;
	if (target.classList.contains(className)) {
		return target;
	}
	while (true) {
		if (target.parentElement === null) {
			break;
		} else if (target.parentElement.classList.contains(className)) {
			return target.parentElement;
		}
		target = target.parentElement;
	}
	return getChildByClass(el, className);
}

function getChildByClass(el, className) {
	let children = el.children;
	for (let i = 0; i < children.length; i++) {
		if (children[i] === undefined) {
			return null;
		} else if (children[i].classList.contains(className)) {
			return children[i];
		} else {
			getChildByClass(children[i], className);
		}
	}
}
```

<!---
ms0130k/ms0130k is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
