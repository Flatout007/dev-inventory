(AJAX calls using fetch)

- Fetch is an API method that retireves data from an API

- in javascript the fetch method is normally used for ajax calls and returns a promise object


(Get data with fetch)
- use the API's URL or "endpoint" as the argument. 
Syntax: fetch('url')


(Manipulate Data)
- use "then & catch" to manipulate data. 
Syntax: fetch('url').then(callback(data){}).catch(e)


(Parse streams into JSON)
- return stream, use "then & catch" chain to manipulate JSON file. 
Syntax: function {return name.json()}.then(callback(data){}).catch(e)
