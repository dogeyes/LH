```
doubleSmallNumber x = if x > 100
                        then x
                        else x * 2
```

```
conanO'Biren = "It's a-me, Conan O'Brien!"
```

```
let lostNumber = [4, 8, 15, 16, 23, 42]
```

```
[1, 2, 3, 5] ++ [9, 10, 11, 12]
"hello" ++ " " ++ "world"
'A': " SMALL CAT"
5:[1,2,3,4,5]
[1,2,3,4,4] !! 2
[3, 2, 1] > [2, 1, 0] --True
[3, 2, 1] > [2, 1] --True
[3, 2, 1] == [3, 2, 1] --True
head [5, 4, 3, 2, 1] --5
tail [5, 4, 3, 2, 1] --[4, 3, 2, 1]
last [5, 4, 3, 2, 1] --1
init [5, 4, 3, 2, 1] --[5, 4, 3, 2]

head [] --Exception
length [1, 2, 3, 4] --4
null [] --True
null [1,2,3] --False
reverse [5,4,3,2,1]
```

**take**
```
take 3 [5,4,3,2,1] --[5,4,3]
take 1 [3,9,3] --[3]
take 5 [1,2] --[1,2]
take 0 [6,6,6] --[]
```

**drop**
```
drop 3 [8,4,2,7,1,5,6] --[7,1,5,6]
drop 0 [1,2,3,4] --[1,2,3,4]
drop 100 [1,2,3,4] --[]
```

**maximum**
```
maximun [1,9,2,3,4] --9
```

**minimum**
```
minimum [2,1,9,3,4] --2
```

**sum**
```
sum [5,2,1,6,3,2,5,7] --31
```

**product**
```
product [6,2,1,2] --24
```

**elem**
```
4 `elem` [3,4,5,6] --True
10 `elem` [3,4,5,6] --False
```

## range

```
[1..20]
['a'..'z']
['A'..'Z']
```

```
[2,4..20]
[20,19..1]
```

Do not use floating in list rages.

```
take 24 [13,26,..]
```

```
take 10 (cycle [1,2,3]) --[1,2,3,1,2,3,1,2,3,1]
```

```
take 10 (repeat 5) --[5,5,5,5,5,5,5,5,5,5]
replicate 3 10 --[10,10,10]
```

### list comprehension
