# aurelia-kendoui-plugin demo site

[![Live demo](http://dabuttonfactory.com/button.png?t=Live+demo&f=Calibri-Bold&ts=24&tc=fff&tshs=1&tshc=000&hp=20&vp=8&c=5&bgt=gradient&bgc=3d85c6&ebgc=073763)](http://aurelia-ui-toolkits.github.io/demo-kendo/)
[![Plugin repository](http://dabuttonfactory.com/button.png?t=Plugin+repository&f=Calibri-Bold&ts=24&tc=fff&tshs=1&tshc=000&hp=20&vp=8&c=5&bgt=gradient&bgc=3d85c6&ebgc=073763)](https://github.com/aurelia-ui-toolkits/aurelia-kendoui-plugin)

### How to run & deploy
1. `npm install`
2. `jspm registry create kendo jspm-git`
 1. base URL: **https://bower.telerik.com**
 2. Set advanced configurations? **yes**
 3. Would you like to use the default git repository suffix (.git)? **yes**
 4. Disable shallow git clones? **no**
 5. Enable authentication? **yes**
 6. Enter your Telerik credentials
3. `jspm install`

now you can either run the app with `gulp watch` or deploy by using `gulp deploy`

### How to copy from the sample to this demo repository
1. copy the entire [aurelia-kendoui-plugin/sample/src](https://github.com/aurelia-ui-toolkits/aurelia-kendoui-plugin/tree/master/sample/src) directory to the [demo-kendo/src](https://github.com/aurelia-ui-toolkits/demo-kendo/tree/master/src) directory