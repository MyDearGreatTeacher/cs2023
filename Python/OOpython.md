###


### 範例1: 改編自https://www.runoob.com/python3/python3-class.html
```python
#!/usr/bin/python3
 
#類別定義
class people:
    #定義基本屬性
    name = ''
    score = 0

    #定義私有屬性,私有屬性在類外部無法直接進行訪問
    __weight = 0

    #定義constructor|建構子|構造方法
    def __init__(self,n,a,w):
        self.name = n
        self.score = a
        self.__weight = w

   #定義另一個方法(method)
    def speak(self):
        print("%s 說: 我會拿 %d 分。" %(self.name,self.score))
 
# 產生實體類
p = people('龍大大',60,90)
p.speak()
```



### 範例1:
```python

```
