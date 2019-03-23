# tencent-geolocation-vue

> 在vue中使用的腾讯定位

# How to use

``` bash

npm i tencent-geolocation-vue -S

const key = '<申请的腾讯定位sdk>';
 
const app = '<申请的app名字>';
 
const geolocation = new Geolocation(key, app);
 
geolocation.getLocation(successCallback, errorCallback);
 
function successCallback(position) {
    console.log(position)
}
 
function errorCallback() {
    console.log('error')
}
```