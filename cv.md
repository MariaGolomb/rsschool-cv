#Curriculum Vitae for Position of Junior Developer.

1. Maria Golomb
2. **Contact Info:** Telephone: +375 29 633 61 63; email: marialukashuk.ml@gmail.com   
3. **Summary:** Want to become good JS developer. Wish to improve my knowledge in such areas as front end development using HTML, CSS and different JS frameworks and learn JS and JS frameworks that are used to implement Back End, because want in future implement both Back and Front End.  
Have some basic development background from university(BSUIR) and some experience as a system Analyst in Belarusbank(2012-2016). All the time try to learn new.
4. **Skills:** Basic knowledge of HTML, CSS, JS, Git.
5. **Code examples:**  
```javascript
    function toBinaty(num){
        let res=[];
        while(num>0){
            rem=num%2;
            res.push(rem);
            num=Math.floor(num/2);      
        }
        return res.reverse().join('');
    }
```
```javascript
    function isValidIP(str) {
        const arrOfChar=new Array(256).fill(1).map((num, i)=>(num+i-1).toString());
        return str.split('.').length==4 
        && str.split('.').filter(current=>!arrOfChar.includes(current)).length==0
    }
```
```javascript
    function longest(s1, s2) {
        let s=s1+s2;
        let sortArr=s.split('').sort();
        let helpObj={};
        for(let i=0; i<sortArr.length; i++){
            let k=sortArr[i];
            helpObj[k]=true;
        }
        return Object.keys(helpObj).join('');   
  }
```
6. **Experience:** Projects related to HTML, CSS, JS and React on Codecademy. [Link to project.](https://github.com/MariaGolomb/Ravenous)
7. **Education:** BSUIR, Faculty of Information Technologies and Management(2007-2012); Course of Web Development on Codecademy.
8. **English:** Pre Intermediate(A2).