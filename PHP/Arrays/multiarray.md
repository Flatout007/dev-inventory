(Multidimensional arrays)

- Multidimensional arrays are arrays that have other arrays as properties for each root indice.

- In PHP multidimensional arrays can contain different types &amp; be implemented as associative arrays.


(Create multidimensional array)
- simply create an array inside an existing one to act as properties for each root array indices.
Syntax: $arr = [['A','B','C','D'], ['E','F','G','H']] syntax: $root = [[sub][sub]]


(Create associative multidimensional array)
- simply create an associative array inside an existing array to act as properties for each root array indices.
Syntax: $Aarr = [["key" =&gt; "value"], ["key" =&gt; "value"]]


(Index values from a multidimensional array)
- to find a value in a multidimensional array simply access the root array index and the sub array index.
Syntax: var_dump($arr[0][1]) same as. syntax: var_dump($arr[root][sub])


(Index values from a associative multidimensional array)
- to find a value in an associative multidimensional array, access the root index and key.
Syntax: var_dump($arr[0]["key"])

