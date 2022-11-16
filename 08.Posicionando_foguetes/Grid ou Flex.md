```HTML
<body>
  <header>
    <div>Logo</div>
    <div>Menu</div>
  </header>
</body>
```
```Css
body{
  margin: 0;
  height: 100vh;
  display: grid;
  grid-template-areas:
    "header header"
    "main aside"
    "footer footer";
  grid-template-rows: 30px 1fr 40px;
  grid-template-columns: 1fr 80px;
}
header{
  grid-area: header;
  background-color: green;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 8px;
}
```