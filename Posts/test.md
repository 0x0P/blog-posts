---
title: "TEST글"
slug: "test"
description: "테스트입니다."
coverImage: "https://raw.githubusercontent.com/0x0P/blog-posts/main/Images/covers/1761869792250-depth-effect-is-nice-v0-v7ny4rvyd6qf1.webp"
tags: ["테스트", "test"]
createdAt: "2025-10-31T00:18:42.335Z"
updatedAt: "2025-10-31T00:18:42.335Z"
---

# H1: 제목 1

## H2: 제목 2

### H3: 제목 3

#### H4: 제목 4

##### H5: 제목 5

###### H6: 제목 6

이것은 일반 텍스트 단락입니다. **굵은 텍스트**, _기울임꼴 텍스트_, 그리고 ~~취소선~~을 포함하고 있습니다. `인라인 코드`도 테스트합니다.

---

## 목록

### 순서 없는 목록

- 항목 1
- 항목 2
  - 중첩된 항목 2.1
  - 중첩된 항목 2.2
- 항목 3

### 순서 있는 목록

1. 첫 번째 항목
2. 두 번째 항목
   1. 중첩된 첫 번째 항목
   2. 중첩된 두 번째 항목
3. 세 번째 항목

---

## 인용문

> 이것은 인용문입니다.
> 여러 줄에 걸쳐 작성될 수 있습니다.

> 바깥쪽 인용
>
> > 중첩된 인용

---

## 링크와 이미지

[이것은 Next.js 공식 문서로 가는 링크입니다.](https://nextjs.org/)

![테스트 이미지](/test2.png "테스트 이미지 캡션")

---

## 코드 블록

### JavaScript (Syntax Highlighting)

```javascript
function greet(name) {
  return `Hello, ${name}!`;
}

console.log(greet("World"));
```

### Python (Syntax Highlighting)

```python
def fibonacci(n):
    a, b = 0, 1
    while a < n:
        print(a, end=' ')
        a, b = b, a+b
    print()

fibonacci(100)
```

### 펜스 없는 코드 블록

```
이것은 언어 지정이 없는 일반 코드 블록입니다.
특별한 하이라이팅이 적용되지 않습니다.
```

---

## 테이블

| 헤더 1    |  헤더 2   |      헤더 3 |
| :-------- | :-------: | ----------: |
| 왼쪽 정렬 | 중앙 정렬 | 오른쪽 정렬 |
| 셀 1-1    |  셀 1-2   |      셀 1-3 |
| 셀 2-1    |  셀 2-2   |      셀 2-3 |

---

## 수학 공식 (KaTeX)

인라인 수학 공식: $E = mc^2$

블록 수학 공식:

$$
\int_{-\infty}^{\infty} e^{-x^2} dx = \sqrt{\pi}
$$

---

## Raw HTML

이것은 <strong>HTML strong 태그</strong>를 사용한 텍스트입니다.

<details>
  <summary>여기를 클릭하여 세부 정보 보기</summary>
  <p>숨겨져 있던 내용이 나타납니다.</p>
</details>
