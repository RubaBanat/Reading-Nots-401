# Node Ecosystem, TDD, CI/CD

![devops](imgs/devops.png)

---

- `Array.map()` 

runs over every element in the array and returns a new array depending on the code inside it .

---

- `Array.reduce()`

 runs over the elements in the array and returns a single value depending on the accumulator you have chosen.

---

- `Superagent()`

superagent.get(url)
.then(result=>{ console.log(‘results:‘,result.body); })

let getDataFromUrl = (url) => new Promise( (resolve,reject) => { if( superagent.get(url) ) { resolve(OK) } else { reject(BAD Request) } });


async function getData(url) { try { let result = await getDataFromUrl(url); console.log(result); } catch(e) { console.error(err); } }

---

*The promise in js is just like promise in real life it has three states you are doing it which is the pending state it can be fulfilled in the end or it will fail which is the rejection in js you can have callback functions to handle any of those two possible outcomes .*

---

**Are all callback functions considered to be Asynchronous? Why or Why Not?**

*No most of them are not but there are those synch call back functions, Examples:*

     EventEmitter (depends on when the event is fired)
     Array iteration methods like forEach
     Array sort comparator callbacks
     String replace match callbacks

---

# THE END