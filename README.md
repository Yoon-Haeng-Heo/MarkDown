# MarkDown
마크다운 문법 모음(2020/07/20 추가) by yoonhaeng heo

### 제목(Header)

- `<h1>`부터 `<h6>`까지 제목을 표현할 수 있습니다.

```
# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

```

- 제목1(h1)과 제목2(h2)는 다음과 같이 표현할 수 있습니다.


```
제목 1
=======
제목 2
------
```

### 강조(Emphasis)

- 각각 `<em>`, `<strong>`, `<del>` 태그로 변환됩니다
- 밑줄을 입력하고 싶다면 `<u></u>`태그를 사용하세요.
```markdown
이텔렉체는 *별표(asterisks)* 혹은 _언더바(underscore)_를 사용하세요.
두껍게는 **별표(asterisks)** 혹은 __언더바(underscore)__를 사용하세요.
**_이텔렉체_와 두껍게**를 같이 사용할 수 있습니다.
취소선은 ~~물결표시(tilde)~~를 사용하세요.
<u>밑줄</u>는 `<u></u>`를 사용하세요.
```

### 목록(List)

- `<ol>`, `<ul>` 목록 태그로 변환됩니다.  
- `<br>` 을 통해 줄 바꿈을 사용합니다.
<ol>1. 순서가 필요한 목록<br>2. 순서 필요  
<ul> - 순서가 필요하지 않은 목록 </ul> </ol>

 -순서가 필요하지 않은 목록에 사용 가능한 기호
- 대쉬(hyphen)
* 별표(asterisks)
+ 더하기(plus sign)


### 링크(Links)

- `<a>`로 변환됩니다.
```
<a> [GOOGLE](https://google.com)
</a>
or
[GOOGLE](https://google.com)
띄어쓰기 없이 []와 ()를 붙여서 사용해야 한다.

문서 내 일반 URL이나 꺾쇠 괄호안의 URL은 자동으로 링크로 반환됩니다.
구글 : https://google.com
네이버 : <https://naver.com>
```

[GOOGLE](https://google.com)<br>
구글 : https://google.com<br>
네이버 : <https://naver.com>

### 블록(block) 코드 강조

```html
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>
```

```css
.list > li {
position: absolute;
top: 40px;
}
```

```javascript
function foo(){
  var a = 'AAA';
  return a;
  }
```

```bash
$ vim ./~zshrc
```

```python
def func(){
  print("hello")
}
```

### 표(Table)
`<table>` 태그로 변환됩니다.<br>
헤더 셀을 구분할 때 3개 이상의 `-`기호가 필요합니다.<br>
헤더 셀을 구분하면서 `:`(colons) 기호로 셀(열/칸) 안에 내용을 정렬할 수 있습니다.<br>
가장 좌측과 가장 우측에 있는 `|`(vertical bar)기호는 생략 가능합니다.<br>

```
| 값 | 의미 | 기본값 |
|---|:---:|---:|
| `static` | 유형(기준) 없음 / 배치 불가능 | `static` |
| `relative` | 요소 자신을 기준으로 배치 |  |
| `absolute` | 위치 상 부모(조상)요소를 기준으로 배치 |  |
| `fixed` | 브라우저 창을 기준으로 배치 |  |

값 | 의미 | 기본값
---|:---:|---:
`static` | 유형(기준) 없음 / 배치 불가능 | `static`
`relative` | 요소 **자신**을 기준으로 배치 |
`absolute` | 위치 상 **_부모_(조상)요소**를 기준으로 배치 |
`fixed` | **브라우저 창**을 기준으로 배치 |
```

| 값 | 의미 | 기본값 |
|---|:---:|---:|
| `static` | 유형(기준) 없음 / 배치 불가능 | `static` |
| `relative` | 요소 자신을 기준으로 배치 |  |
| `absolute` | 위치 상 부모(조상)요소를 기준으로 배치 |  |
| `fixed` | 브라우저 창을 기준으로 배치 |  |

값 | 의미 | 기본값
---|:---:|---:
`static` | 유형(기준) 없음 / 배치 불가능 | `static`
`relative` | 요소 **자신**을 기준으로 배치 |
`absolute` | 위치 상 **_부모_(조상)요소**를 기준으로 배치 |
`fixed` | **브라우저 창**을 기준으로 배치 |

### 인용문(BlockQuote)

`<blockquote>` 태그로 변환됩니다.

```
인용문(blockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.
> _(네이버 국어 사전)_

BREAK!

> 인용문을 작성하세요!
>> 중첩된 인용문(nested blockquote)을 만들 수 있습니다.
>>> 중중첩된 인용문 1
>>> 중중첩된 인용문 2
>>> 중중첩된 인용문 3
```
인용문(blockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.
> _(네이버 국어 사전)_

BREAK!

> 인용문을 작성하세요!
>> 중첩된 인용문(nested blockquote)을 만들 수 있습니다.
>>> 중중첩된 인용문 1
>>> 중중첩된 인용문 2
>>> 중중첩된 인용문 3

출처 : https://heropy.blog/2017/09/30/markdown/

but made by yoonhaeng heo
