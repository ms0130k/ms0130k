- ð Hi, Iâm @ms0130k
- ð Iâm interested in ...
- ð± Iâm currently learning ...
- ðï¸ Iâm looking to collaborate on ...
- ð« How to reach me ...

_Any fool can write code that a computer can understand. Good programmers write code that humans can understand. -Refactoring Improving the Design of Existing Code 15p_

```c
printf("%së¡ %síë %ìëë¤.", "ì·¨ë¯¸", "ê°ë°", "ê°ë°ì");
```
```java
System.out.println("ì¼ì ê¸¸ì´ì ë©ëª¨ë¦¬ì ì ì¥ë ì ë³´ë¥¼ í´ìíë ë°©ë²");
```
```python
print("í´ìí  ëì ë©ëª¨ë¦¬ì ë¶ì¸ ì´ë¦");
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
ms0130k/ms0130k is a â¨ special â¨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
