(AJAX call using Async Functions)

- use async functions to make ajax calls, retrieve and manipulate API data &amp; write cleaner asynchronous code.

- in javascript the "await" keyword is reseved for async functions


(get data from API)
- use "await" in front of a request call inside an async function. 
 Syntax: let f = await api('url')


(Parse Stream to JSON)
- use await in front of a readable stream and convert json ayncronously. 
Syntax: await stream.json()


(Destructring JSON objects)
- get json properties. Does not rquire "await" keyword. 
Syntax: let p = json.data[0]


(Handling Errors with async functions)
- use a "try &amp; catch" block to log errors. 
Syntax: try {async function {}} catch(e) {console.log(e)}


(Return data from async functions)
- async return values differ from basic functions, they must be used with "then &amp; catch" method chain. 
Syntax: async function {return data}.then(callback(d){}).catch(e)