#1. Usage

##1. Install randomCaddress

### npm install randomCaddress

##2. Import randomCaddress

ES6 style is supported, then get global object: randomCaddress.
import randomCaddress from 'randomCaddress';

// or

var randomCaddress = require("randomCaddress.js");
or link with script in html files:

<script src="randomCaddress.js"></script>
3. Use class randomCaddress

```

 * 指定数量，类别
 * randomCaddress.result(number,type)
 * type现在就两种
   * 省-市-县区-街道-X幢-X室
   * 省-市-县区-街道-X单元-X室

```

```

var randomCaddressInstance = new randomCaddress();
//默认随机返回一个中文地址
randomCaddressInstance.result()

=>["四川省广元市昭化区张家乡4幢229室"]
// 指定type(0,1) 生成10个数据

randomCaddressInstance.result(10,1)

=>
0:"河北省邢台市隆尧县莲子镇镇7单元56室"
1:"广西壮族自治区柳州市柳南区柳石街道19单元237室"
2:"青海省西宁市城北区马坊街道13单元273室"
3:"湖南省益阳市沅江市阳罗洲镇16单元181室"
4:"山东省东营市东营区辛店街道8单元121室"
5:"河北省邢台市市辖区18单元171室"
6:"江西省抚州市金溪县浒湾镇19单元61室"
7:"江苏省南通市启东市启隆乡3单元144室"
8:"吉林省长春市农安县伏龙泉镇8单元270室"
9:"上海市上海市长宁区程家桥街道1单元116室"

```


