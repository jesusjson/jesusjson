<h1 align="center"> Herkese Merhaba, Ben jesusjson <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"></h1>
<p align="center"><span>Yaklaşık 3 yıldan beri programlama ile uğraşıyorum ve gün geçtikçe kendimi geliştirmeye çalışıyorum.</span></p>

```js
const jesusjson = require("./schema-jesusjson.js")

jesusjson.findOne({admin: "jesusjson"}, async (hata, data) => {
    if(hata) return console.error(hata)
    
    if(!data){
  
      const config = {
        languages: ["HTML", "CSS", "JavaScript", "PHP", "Pthon", "C#"]
      }

      const jesusjsondata = new jesusjson({
      name: "Mert",
        age: 18,
        friend = null,
        discord_main: "jesujson#4406 / 811320211826933790",
        languages: config.languages,
        servers: config.servers
      }).save().catch(hata => console.error(hata))

}})
```

  

