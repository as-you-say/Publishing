# Noto Sans KR

## 자간/행간/어간

| 이름 | CSS 속성명 | 값 |
| :--- | :--- | :--- |
| 자간 | letter-spacing | -50 ~ -75 |
| 행간 | line-height | 거의 수정할 필요가 없음 |
| 어간 | word-spacing | 폰트에 맞게 조절 \(아직 고정값이 없음 - 추후 수정\) |

## CSS 타이포그래피

위에서 나타난 속성값에 맞게 CSS 스타일에 적용하자면 아래와 같이 작성하여 사용할 수 있습니다.  
어디까지나 간단하게 나타낸 경우이므로 실제로는 디자이너의 시안에 맞게 더욱 복잡한 속성들이 많이 들어갈 것입니다.

또한, 영역별로 letter-spacing 을 적용한 후, 13px 14px 15px 폰트사이즈는 각각 요소별로 적용하기도 합니다. 그리고 2줄 이상으로 표현되는 글이 없다면, line-height 값은 중요하지 않기 때문에, 초기화 CSS 코드에서 정의했던 16px 과 같은 값을 사용하도록 합니다.

```css
h1 {letter-spacing: -.75px; font-size: 40px; font-weight: 600;}
h2 {letter-spacing: -.75px; font-size: 32px; font-weight: 600;}
h3 {letter-spacing: -.75px; font-size: 24px; font-weight: 600;}
p {letter-spacing: -.75px; font-size: 16px;}
```



