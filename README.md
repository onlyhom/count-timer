# count-timer
A countdown timer    

**use like this:**

```html
var timer1 = new CountTimer({
  endTime:'2017-04-12 20:45:50',
  container:'.test1',
  callback:function(days, hours, minutes, seconds){
    //每一秒钟的回调函数
    // console.log(days+'天'+hours+'时'+minutes+'分'+seconds+'秒');
  },
  timeEnd:function(){
    //定时器结束的回调函数
    console.log('timer1-拍卖已结束');
  }
});
```

