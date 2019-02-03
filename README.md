### prova
---
https://github.com/azer/prova

```
npm install -g azer/prova

node test.js
node test.js -b

npm install -g prova
prova test/foo.js test/bar.js
prova test/**/*.js -b
prova -l
prova -b -l safari
prova -b -l chrome -e
prova -b -; phantom
rm /Users/azer/.config/browser-launcher/config.json
node test -b -t coffeeify
node test -b -t coffeeify,brfs,foo,bar
node test -b --plugin foo
node test -b --plugin foo,bar
node test -b -f test.html
curl localhost:7559/assets/infoobar.png
node test -b -y "/my-api-http://localhost:8080"
```

```js
var test = require('prova')
test('timing test', function(t){
  t.plan(2)
  t.equal(typeof Date.now, 'function')
  var start = Date.now()
  
  setTimeout(function(){
    t.equal(Date.now() - start, 100)
  }, 100)
})

```

```
```


