(Array)

- an array is a collection of data stored together in the same block of memory

- in PHP arrays are dynamic meaning size management isn't a thing to be concerned about


(Declare array)
- in PHP you can use [] or the array() method to declare arrays
syntax: ['A','B','C'] or syntax: array('A','B','C')


(Print array)
- You have to use the "var_dump" method to view an array in the browser
syntax: var_dump($arr)


(Modify indices)
- in PHP you can modify array indices to your liking.
Syntax [1=&gt; 'A', 10=&gt; 'B']


(Print an array index)
- access the index of an array to view its value
syntax: var_dump($arr[0])


(Associative array)
- in PHP you can turn an array into a key value pair associative array.
Syntax ["first" =&gt; 'A', "second" =&gt; 'B'] 


(Print an associative array index)
- access the key of an associative array to view its value
syntax: var_dump($Aarr["first"])


(Store variables inside arrays)
- in PHP you can store variables inside arrays
syntax: $arr = [$var, $var_n]
