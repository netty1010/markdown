# markdown
마크다운은 .md 파일로 되어 있으며 사용법이 간단하고 가독성 있는 문서를 작성할 수 있습니다.   

# markdown syntax
1. Header 
- header 는 h1 ~ h6 까지 정의할 수 있습니다. 
# header 1
## header 2
### header 3
#### header 4
##### header 5
###### header 6


2. 단어 강조
- *이탤릭체* 혹은 _이탤릭체_
- **볼드체** 혹은 __볼드체__
- ~~취소선~~


3. 링크
```
[링크제목](링크주소, 링크설명)
링크설명은 생략가능합니다.
```
[떡볶이맛집](https://www.google.com/maps?client=safari&sxsrf=ACYBGNTIM2dt70iZJcQJgMM28rHSLDmNQg:1578912335244&q=떡볶이맛집&uact=5&um=1&ie=UTF-8&sa=X&ved=0ahUKEwi1mL6hu4DnAhVtJaYKHZZtDV8Q_AUIDSgB)

[떡볶이맛집](https://www.google.com/maps?client=safari&sxsrf=ACYBGNTIM2dt70iZJcQJgMM28rHSLDmNQg:1578912335244&q=떡볶이맛집&uact=5&um=1&ie=UTF-8&sa=X&ved=0ahUKEwi1mL6hu4DnAhVtJaYKHZZtDV8Q_AUIDSgB, "떡볶이 맛집입니다.")


4. 이미지 삽입
```
![이미지제목](이미지링크 이미지설명)
링크와 비슷합니다. 하지만 느낌표가 붙습니다
```
![떡볶이 사진](https://t1.daumcdn.net/cfile/tistory/99B6C24C5CA6ACBD02)
![떡볶이 사진](https://t1.daumcdn.net/cfile/tistory/99B6C24C5CA6ACBD02 "떡볶이 사진이어라~")


5. 코드 블럭
- 블럭 강조
```
def test():
  print("개발 좀 하는 언니는 대박날 것입니다.")
```

- 인라인 강조
저는 ```python``` 코드가 가장 좋습니다. 데헷  


6. 표
|ID|주제|설명|
|---|:---:|---:|
|1|떡볶이|세상에 없어서는 안될 존재|
|2|곱창|세상에 없어서는 안될 존재|
