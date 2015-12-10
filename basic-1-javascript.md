---
layout: page
title: Challenge 1 Solution
permalink: /solutions/basic/1
---

```js
var sum = 0

for (var multiple = 3; multiple < 1000; multiple = multiple + 3) {
	sum = sum + multiple
}

for (var multiple = 5; multiple < 1000; multiple = multiple + 5) {
	if (multiple % 3 != 0) {
		sum = sum + multiple
	}
}

console.log(sum)

// 233168
```
