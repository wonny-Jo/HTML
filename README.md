# HTML(Hypertext Markup Language)이란
web page를 만드는 코드. 매우 간결하고 쉽다. 하지만 많이 쓰이기에 중요하다.

web은 public domain이기에 무료라는 엄청난 메리트가 있다.

## atom 설치 과정
- https://atom.io 에서 자신의 운영체제에 맞게 설치후 실행
- HTML Editor 검색후 다른 에디터를 사용해보는 것도 좋을듯.

## atom 첫 실행 과정
1) project를 저장할 directory 생성
2) atom을 실행하여 file 메뉴의 open folder로 생성한 directory 열기
3) project의 생성된 폴더를 우클릭하여 new file로 새로운 파일 생성(.html로 형식을 만들어줄것)
4) file 메뉴의 open file로 기존의 파일을 열어서 변경 및 사용 가능
 
## HTML 태그(tag) 정리
### 태그가 정리되어 있는 사이트(통계적으로 많이 쓰이는 순으로)
https://www.advancedwebranking.com/html/
#### 제목란 만들기
> ```<h1>text</h1>```

> h1~h6까지 가능

#### 볼드체 만들기
> ```<strong>text</strong>```

#### 밑줄 긋기
> ```<u>text</u>```

#### 줄바꿈
> ```<br>```

> 줄만 바꾸는것이기에 닫는 태그가 필요없다.

> 여러 줄 사용가능.

#### 단락 만들기
> ```<p>text</p>```

> br 태그보다 많이 사용됨

#### 이미지 넣기
##### https://unsplash.com 에서 무료로 사진을 이용가능
> ```<img src="site address" width="num or percent">```

#### 목차 만들기
##### 순서가 없는 목차 만들기
    <ul>
      <li>text1</li>
      <li>text2</li>
    </ul>

##### 순서가 있는 목차 만들기
    <ol>
     <li>text1</li>
     <li>text2</li>
    </ol>

#### 표 만들기
    <table>
      <tr>
        <td>text1</td>
        <td>text2</td>
      </tr>
      <tr>
        <td>text3</td>
        <td>text4</td>
      </tr>
      <tr>
        <td>text5</td>
        <td>text6</td>
      </tr>
    </table>
