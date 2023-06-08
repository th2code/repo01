# Markdown language 
![markdown](https://github.com/th2code/repo01/assets/134608494/d97b4ab1-7964-44d2-8cd2-edf711c085c9)

보통 Markup language 하면 제일 먼저 생각나는것이 HTML이 아니던가?

결론부터 얘기하면 Markdown 도 Markup의 일종이다!

HTML보다는 간단하게 쓸수 있어 Down이라고 했나??! 

적절한 작명센스라 생각한다.


## Header
여섯단계로 구성되며 #의 개수로 하위 depth로 내려간다.
```
### header3
#### header4
##### header5
###### header6
```

### header3
#### header4
##### header5
###### header6


Header1,2는 본 문서의 큰제목(Markdown language)과 두번째 제목(Header)에서 볼수 있음 (Underline은 덤)


## Emphasis (강조)
```
*이탤릭체*
**볼드체**
~~취소선~~
<u>밑줄</u>
```

*이탤릭체*

**볼드체**

~~취소선~~

<u>밑줄</u>


## 코드블럭

```java
public class SampleJavaCode{
  public static void main(){
    String str = "Hello world";
    System.out.println(str);
  }
}
```

```sql
SELECT * 
  FROM TABLE_A, TABLE_B
 WHERE A.PK = B.FK
   AND A.W_DATE = TO_CHAR(SYSDATE, 'YYYYMMDD')
;
```

