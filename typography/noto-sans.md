# Noto Sans

## 자간/행간/어간

<table>
  <thead>
    <tr>
      <th style="text-align:left">&#xC774;&#xB984;</th>
      <th style="text-align:left">CSS &#xC18D;&#xC131;&#xBA85;</th>
      <th style="text-align:left">&#xAC12;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">&#xC790;&#xAC04;</td>
      <td style="text-align:left">letter-spacing</td>
      <td style="text-align:left">-25 ~ 0</td>
    </tr>
    <tr>
      <td style="text-align:left">&#xD589;&#xAC04;</td>
      <td style="text-align:left">line-height</td>
      <td style="text-align:left">
        <p>24 - 16 (&#xD3F0;&#xD2B8;)
          <br />34 - 24 (&#xD3F0;&#xD2B8;)</p>
        <p>44 - 32 (&#xD3F0;&#xD2B8;)</p>
        <p>54 - 40 (&#xD3F0;&#xD2B8;)</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">&#xC5B4;&#xAC04;</td>
      <td style="text-align:left">word-spacing</td>
      <td style="text-align:left">&#xD3F0;&#xD2B8;&#xC5D0; &#xB9DE;&#xAC8C; &#xC870;&#xC808; (&#xC544;&#xC9C1;
        &#xACE0;&#xC815;&#xAC12;&#xC774; &#xC5C6;&#xC74C; - &#xCD94;&#xD6C4; &#xC218;&#xC815;)</td>
    </tr>
  </tbody>
</table>

## CSS 타이포그래피

위에서 나타난 속성값에 맞게 CSS 스타일에 적용하자면 아래와 같이 작성하여 사용할 수 있습니다.  
어디까지나 간단하게 나타낸 경우이므로 실제로는 디자이너의 시안에 맞게 더욱 복잡한 속성들이 많이 들어갈 것입니다.

또한, 영역별로 letter-spacing 을 적용한 후, 13px 14px 15px 폰트사이즈는 각각 요소별로 적용하기도 합니다. 그리고 2줄 이상으로 표현되는 글이 없다면, line-height 값은 중요하지 않기 때문에, 초기화 CSS 코드에서 정의했던 16px 과 같은 값을 사용하도록 합니다.

```css
body {line-height: 16px;}

p.t1 {letter-spacing: -.25px; font-size: 40px; line-height: 54px; font-weight: 600;}
p.t2 {letter-spacing: -.25px; font-size: 32px; line-height: 44px; font-weight: 600;}
p.t3 {letter-spacing: -.25px; font-size: 24px; line-height: 34px; font-weight: 600;}
p.t4 {letter-spacing: -.25px; font-size: 16px; line-height: 24px;}
```



