# 使用
```
npm start
```

## 問題
根據 https://www.npmjs.com/package/json-server-auth 教學
<br>
新增 routes.json 文件,並附上規則:
<br>
```
{
  "users": 600
}
```
<br>
但是在user.js中使用的話卻可以無視規則,並且取得的資料是當前頁面的html
<br>
不知道是哪裡出的問題,可能是script節點?
