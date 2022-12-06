## HTML程式開發 [錄影教學](https://youtu.be/_R_FO71Mk2s)
```html
<!DOCTYPE html>
<html>
  
<head>
  <title>Welcome to Taiwan</title>
  <meta charset="UTF-8">
</head>  
  
<body>

<h1>My Dear Friends哈</h1>
<h1>My Dear small Friends哈</h1>

<p>This is mydeargreatteacher speaking</p>

</body>
</html>
```

## CSS
```html
<!DOCTYPE html>
<html>
<head>
<style> 
#rcorners1 {
  border-radius: 25px;
  background: #73AD21;
  padding: 20px; 
  width: 200px;
  height: 150px;  
}

#rcorners2 {
  border-radius: 25px;
  border: 2px solid #73AD21;
  padding: 20px; 
  width: 200px;
  height: 150px;  
}

#rcorners3 {
  border-radius: 25px;
  background: url(paper.gif);
  background-position: left top;
  background-repeat: repeat;
  padding: 20px; 
  width: 200px;
  height: 150px;  
}
</style>
</head>
<body>

<h1>The border-radius Property</h1>

<p>Rounded corners for an element with a specified background color:</p>
<p id="rcorners1">Rounded corners!</p>
<p>Rounded corners for an element with a border:</p>
<p id="rcorners2">Rounded corners!</p>
<p>Rounded corners for an element with a background image:</p>
<p id="rcorners3">Rounded corners!</p>

</body>
</html>
```

## Javascript [錄影教學](https://youtu.be/qKySp4I2BLA)
```html
<!DOCTYPE html>
<html>
<head>
  <title>Welcome to Taiwan</title>
  <meta charset="UTF-8">
</head>

<body>

<h2>JavaScript Objects</h2>

<p id="demo"></p>

<script>
// Create an object:
const person = {firstName:"John", lastName:"Doe", age:50, eyeColor:"blue"};
// key-value pairs
// Display some data from the object:
document.getElementById("demo").innerHTML =
person.firstName + " is " + person.age + " years old.";
</script>
<marquee>這是人生跑馬燈THIS is PORTUGAL football</marquee>

</body>
</html>
```

## [HTML marquee 跑馬燈的參數](https://medium.com/javascript%E5%88%9D%E5%BF%83%E8%80%85%E8%B8%8F%E9%9B%AA%E5%B0%8B%E6%A2%85/%E7%94%A8%E7%B0%A1%E5%96%AE%E7%9A%84-html-%E5%AF%A6%E7%8F%BE%E8%B7%91%E9%A6%AC%E7%87%88%E6%95%88%E6%9E%9C-41195af17a80)
```html
<marquee 這裡加上參數設定>這裡是跑馬燈的文字這裡是跑馬燈的文字</marquee>

<marquee bgcolor=”gray” hspace=”30" scrollamount=”8">這裡是跑馬燈的文字這裡是跑馬燈的文字</marquee>
```
- 長度設定：height=”參數值”，可以直接填入數字或是百分比，例如：10 或 20%。
- 寬度設定：width=”參數值”，可以直接填入數字或是百分比，例如：10 或 20%。
- 方向設定：direction=”參數值”，會填入 up（向上）、down（向下）、left（向左）、right（向右）。
- 行為設定：behavior=”參數值”，可設定scroll（預設值）、alternate（來回跑）、slide（跑入後停止）。
- 延遲設定：scrolldelay=”參數值”，可以設定每次跑馬燈之間要延遲多久才出現。直接填入數字。
- 速度設定：scrollamount=”參數值” ，可設定為數字，通常設定 1~10 的範圍，數字越大跑得越快。
- 次數設定：loop=”參數值”，預設值是無限，也就是說跑馬燈會無限次數的輪迴。
- 背景顏色：bgcolor=”參數值”，可設定為顏色的色碼或是直接輸入顏色名稱，預設值為白色。
- 水平距離設定：hspace=”參數值”，用來推出跑馬燈的水平距離，可以輸入數字或是百分比，例如：10 或 20%。
- 垂直距離設定：vspace=”參數值”，用來推出跑馬燈的水平距離，可以輸入數字或是百分比，例如：10 或 20%。
