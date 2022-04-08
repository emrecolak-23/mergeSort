# mergeSort
[16,21,11,8,12,22]

## mergeSort Aşamaları
[16,21,11,8,12,22]

1. Aşama
`[16,21,11] -- [8,12,22]`
2. Aşama
`[16,21] - [11] -- [8,12] - [22]`
3. Aşama
`[16] [21] - [11] - [8] [12] - [22]`
4. Aşama
`[16,21] - [11] -- [8,12] - [22]`
5. Aşama
`[11,16,21] -- [8,12,22]`
6. Aşama
`[8,11,12,16,21,22]`

## Big O Notation
```
2^x = n
logn = x
Her bir işlemde O(n) time complexity geliyor
Böylece Big O Notation O(nlogn)
```
