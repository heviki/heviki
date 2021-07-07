```js
  var aboutme = {
      "name": "Lucas",
      "occupattions": {
          "one": "programmer",
          "two": "web developer"
      },
      "languages": ["HTML", "CSS", "JavaScript", "C++", "Python"]
  }
  
  console.log(`Hello, my name is ${aboutme.name}, i'm a ${aboutme.occupattions.one} and a ${aboutme.occupattions.two}`)
  console.log(`i'm currently working with ${aboutme.languages.slice(0, 4).join(', ')} and ${aboutme.languages[4]}`)
```

