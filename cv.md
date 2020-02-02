## Denis Agafonov

I'm 18 years old student of the third course College business and law and RS School.

## Contacts

 telegram: [`@dnagafonov`](https://t.me/dnagafonov "telegram")
 
 github: [`dnagafonov`](https://github.com/dnagafonov "github link")
 
 phone: `+375447993343`
 
 discord: `malmas#0292`
## Skills

+ HTML
+ CSS
+ SASS/SCSS
+ Node JS
+ React JS
+ Redux 
+ Express
+ Mocha, Chai

Example of simple express request:
```js
familyRouter.get(`/:name`, (req, res) => {
    const existedPerson = family.find(el => el.name === req.params.name);
    if(existedPerson){
        console.log(`Send ${req.params.name} informaion`);
        res.status(200).json(existedPerson);
    }
    else
        res.status(404).send(`404`);
});
```
