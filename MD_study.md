마크다운이란?
문서를 웹에 간단하게 보여주기 위한 문법

- 제목
# 이 깃허브 제목은 ~입니다

- 강조
*강조할 내용1*
**내가 강조할 내용**
~~취소선~~
밑줄을 MD에서 지원이 안돼요
<u>밑줄</u>

- 목록
html에서 ul, ol 이런 것들 만드는것
1. 안녕
1.1. 안녕2
1.1.1. 안녕3

 - ul처럼
    - 이렇게도 만들어지고요
        - 이렇게도 가능합니다
---
- 링크
[Google](https://google.com)
- 이미지
![대체텍스트(alt)](https://cdn.pixabay.com/photo/2024/02/26/19/39/monochrome-image-8598798_640.jpg)

- 이미지 + 링크
[![대체텍스트]](https://cdn.pixabay.com/photo/2024/02/26/19/39/monochrome-image-8598798_640.jpg)

`
import pandas as pd
`
```python
print("hello world")
print("hi")
```

```javascript
const test = "hihi"
function add(a,b) {
    console.log(a+b)
}
```

```html
<a href="test.com">태그 예제</a>
```

- 표

| 헤더1 | 헤더2 |
| --- | --- |
| 셀1 | 셀2 |

>내 바지는 나팔바지
>_(니체)_

>인용문인데
>>인용문이
>>>인용문

- 수평선 태그
---

- 줄바꿈
<br>
이런식으로


- 주석

-- 시작 --
<!-- 주석의 내용 -->
-- 종료 --