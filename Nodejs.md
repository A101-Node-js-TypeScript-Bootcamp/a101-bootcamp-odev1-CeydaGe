# Proje ayaklandırma
* Öncelikle express paketi yükleme işlemini yapalım
* npm init
* npm install express
* Local 3000 portunda bi sunucu ayağa kaldırdığımızı düşünelim 
* const express = require('express')
* const app = express()
* app.get('/', function (req, res) {
 res.send('Hello World')
 })
* app.listen(3000)
