## 5.获取用户唯一标识openid
```javascript
wx.getStorage({
    key: 'openid',
    success:function(res){
        console.log(res.data)//打印openid
    }
})
```

我的openid

![Image text](./img/login.png)