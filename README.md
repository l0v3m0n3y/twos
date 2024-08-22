# twos
JavaScript library for 2s.gg
# main
```js
async function main(){
    const {twos} = require('./twos');
    const url= new twos();
    let req=await url.short_url("url")
    console.log(req)
}
main()
```
