# 0. "&lt;","&amp;"需注意
###### 輸入<,＆時需要注意
`AT&amp;T`AT&amp;T
`A&lt;B`A&lt;B
# 1. 字體大小
<code># test</code>
# test
<code>## test</code>
## test
<code>### test</code>
### test
<code>#### test</code>
#### test
<code>##### test</code>
##### test
<code>###### test</code>
###### test
```
Alt-H1
======
```
Alt-H1
======
```
Alt-H2
------
```
Alt-H2
------
# 2. 斜體粗體字
|Code|Result|
|:---|:---:|
|```*test*```<br>```_test_```|*test*<br>_test_|
|```**test**```<br>```__test__```|**test**<br>__test__|
# 3. 一條線
`***`
***
`___`
___
# 4. 連結
#### 網頁連結：
###### 跟HTML相同，使用`<a herf="url"></a>`來加入連結，`title`來加入hover標題
`<a href="https://google.com" title="David">Link to Google with "David" as title</a>`<br>
<a href="https://google.com" title="David">Link to Google with "David" as title</a>
#### 圖片連結：
`<img src="https://github.com/David855008/Readme/blob/master/AJ.jpg" width="128" height="128"/>`<br>
<img src="https://github.com/David855008/Readme/blob/master/AJ.jpg" width="128" height="128" />
# 5. 列表
###### 使用`*`,`+`,`-`來表示，可以加入連結和圖片
*  `* <a href="https://google.com" title="Google.com">https://google.com</a>`<br>
<a href="https://google.com" title="Google.com">https://google.com</a>
* `* <img src="https://github.com/David855008/Readme/blob/master/AJ.jpg" width="128" height="128"/>`<br>
<img src="https://github.com/David855008/Readme/blob/master/AJ.jpg" width="128" height="128" />
* `*test2<br>`<br>test2<br>

# 6. 引用
###### 開頭和結尾加入`` ` ``來表示
```c++
```
#include<stdio.h>
int main(){
    printf("hello world");
    return 0;
}
```
```
|MarkDown|Testing|Table|
|:-------------|:-------:|-----:|
|靠左對齊|置中對齊|靠右對齊|
|1|2|3|
|what|are|those|
|?|!|@|
