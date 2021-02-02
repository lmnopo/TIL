# 마크다운(Markdown)

> 일반 텍스트 형식 구문을 사용하는 마크업 언어의 일종으로 사용법이 쉽고 간결하여 빠르게 문서 정리를 할 수 있습니다. 단, 모든 HTML 마크업을 대체하지는 않습니다. 



## 1. 문법

### 1.1 Header

> 헤더는 제목을 표현할 때 사용합니다. 단순히 글자의 크기를 표현하는 것이 아닌 의미론적인 중요도를 나타냅니다.

- `<h1>`부터 `<h6>`까지 표현 가능합니다.
- `#`의 갯수로 표현하거나 `<h1></h1>`의 형태로 표현 가능합니다.



# h1 태그입니다.

## h2 태그입니다.

### h3 태그입니다. 

#### h4 태그입니다. 

##### h5 태그입니다. 

###### h6 태그입니다. 



### 1.2 List

> 목록을 나열할 때 사용합니다. 순서가 필요한 항목과 그렇지 않은 항목으로 구분할 수 있습니다. 순서가 있는 항목 아래 순서가 없는 항목을 지정할 수 있으며 그 반대도 가능합니다. 

- 순서가 있는 목록

  - `1.`을 누르고 스페이스바를 누르면 생성할 수 있습니다. 
  - `tab` 키를 눌러서 하위 항목을 생성할 수 있고 `shft + tab` 키를 눌러서 상위 항목으로 이동 할 수 있습니다. 

- 순서가 없는 항목

  - `-`(하이픈)을 쓰고 스페이스 바를 누르면 생성할 수 있습니다. 
  - `tab`키를 눌러서 하위 항목을 생성할 수 있고 `shift + tab`키를 눌러서 상위항목으로 이동 할 수 있습니다.

  1. 순서가 있는 항목
  2. 순서가 있는 항목
     1. 순서가 있는 하위 항목
     2. 순서가 있는 하위 항목

- 순서가 없는 항목

- 순서가 없는 항목

  - 순서가 없는 하위 항목
  - 순서가 없는 하위 항목



### 1.3 Code Block

> 코드 블럭은 작성한 코드를 정리하거나 강조하고 싶은 부분을 나타낼 때 사용합니다. 인라인과 블럭 단위로 구분할 수 있습니다. 

- Inline
  - 인라인 블럭으로 처리하고 싶은 부분을 `(백틱)으로 감싸줍니다.
- Block
  - `'`(백틱)을 3번 입력하고  `Enter`를 눌러 생성합니다. 

`add`한 요소를 remote 저장소에 올리려면 $ git push origin master를 터미널에 입력합니다. 

```
$ git add .
$ git commit -m "first commit"
$ git push origin master
```



### 1.4 Image

> 로컬에 있는 이미지를 삽입하거나 이미지 링크를 활용하여 이미지를 나타낼 때 사용합니다.

- `![]()`을 작성하고 `()` 안에 이미지 주소를 입력합니다. `[]`안에는 이미지 파일의 이름을 작성합니다.

- 로컬에 이미지 파일을 저장한 경우 절대 경로가 아닌 상대 경로를 사용하여 이미지를 저장합니다. 

  <img src="https://techies-world.com/wp-content/uploads/2016/08/git_logo.png" style="zoom: 50%;" />![](data:image/jpeg;base64,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)

  

### 1.5 Link

> 특정 주소로 링크를 걸 때 사용합니다.

- `[]()`을 작성하고 `()` 안에 링크 주소를 작성하고 `[]`안에 어떤 링크 주소인지 작성합니다. 



[git 공식문서](https://git-scm.com/doc)

[github 공식문서](https://docs.github.com/en)



### 1.6 Table

> 표를 작성하여 요소를 구분할 수 있습니다.

* `|`(파이프) 사이에 컬럼을 작성하고 `enter`를 입력합니다.
* 마지막 컬럼을 작성하고 뒤에 `|`를 붙여줍니다. 



| working directory | staging area | remote repo |
| ----------------- | ------------ | ----------- |
| working tree      | index        | history     |
| working copy      | cache        | tree        |



### 1.7 기타

**인용문**

* `>`을 입력하고 `enter`키를 누릅니다. 

> git은 컴퓨터 파일의 변경사항을 추적하고 여러 명의 사용자들 간에 해달 파일들의 작업을 조율하기 위한 분산 버전 관리 시스템이다. 

- 인용문 안에 인용문을 작성하면 중첩해서 사용할 수 있습니다. 

> $ git add.
>
> > $ git commit -m "first commit"
> >
> > > $ git push origin master



**수평선**

- `---`, `***`, `___`을 입력하여 작성합니다. 

Working Direcgtory

__________________________________________________________________________________________________________________________________________________________________________

Staging Area

_______

Remote Repository

_____



**강조**

* 이탤릭체는 해당 부분을 `*` 혹은 `_`(언더바)로 감싸줍니다. 
* 볼드체는 해당 부분을 `**` 혹은 `__`(언더바 2개)로 감싸줍니다. 
* 취소선은 `~~`표시를 사용합니다. 

이것은 *이탤릭체*입니다.

이것은 **볼드체**입니다. 

이것은 ~~취소선~~입니다.









