# responsive-web-html

### pure html and css study

####2019/10/21

- how to remove ul circle mark?

```css
.navigation-list {
  list-style: none;
}
```

- link의 밑줄 지우고 대문자로 만들자
  ![image](https://user-images.githubusercontent.com/21155325/67161695-d626f780-f397-11e9-9a47-00e5c093af39.png)

```css
.navigation-link {
  color: #fff;
  font-size: 1.6rem;
  font-weight: 400;
  letter-spacing: 0.1rem;
  text-transform: uppercase;
  text-decoration: none;
}
```

- flex 써서 이쁘게 정렬하기
  ![image](https://user-images.githubusercontent.com/21155325/67161733-4fbee580-f398-11e9-9ea6-5284b9bf4399.png)

```css
.navigation-list {
  list-style: none;
  padding: 0;
  height: 28rem;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
}
```

- position : relative
  부모에 대해서 상대적 위치 지정
- positioin : absolute
  부모가 아닌 html 기준이 된다.
  하지만 명시적으로 left나 top 값을 지정안해주면 부모 기준으로 있어야 될 offset들이 자동으로 지정된다.
  부모와의 링크가 끊긴다. 그래서 부모가 없어지면서 width값을 못정하니까 content값 만큼 커진다.
  하지만 부모가 relative라면 부모 기준으로 달라 붙는다. 즉 static이 아닌 부모를 추적해서 그걸 offset기준으로 본다.
- label 태그는 뭔가?

```html
The <label> tag defines a label for a <button>, <input>, <meter>, <output>, <progress>, <select>, or <textarea> element.

The <label> element does not render as anything special for the user. However, it provides a usability improvement for mouse users, because if the user clicks on the text within the <label> element, it toggles the control.

The for attribute of the <label> tag should be equal to the id attribute of the related element to bind them together.
```

# 키워드

### 가변그리드

### 가변패딩

### 미디어쿼리

### 뷰포트
