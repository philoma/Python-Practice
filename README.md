![image](https://github.com/philoma/Python-Practice/assets/87674698/e9c744e9-ad95-4e03-a227-dd016d169dd1)

A traditional for loop: for loop
![image](https://github.com/philoma/Python-Practice/assets/87674698/70574cb4-2fdc-40d0-8648-4eadeaaf1cdf)

Translated to list comprehension: list comprehension visual
![image](https://github.com/philoma/Python-Practice/assets/87674698/e6059502-fd0c-497c-b6e1-6893c5fe9134)

![image](https://github.com/user-attachments/assets/e5c15b5c-1f38-4e94-817d-8b426d65a523)

<br>
range(n - 1, -1, -1)

start = n - 1
stop = -1
step = -1

So it counts backwards.<br>
Example if n = 5:<br>
range(4, -1, -1) gives: <br>

4 3 2 1 0
<br>
Why -1 as stop?
<br>
Because range() stops before the stop value.
<br>
https://www.hackerrank.com/challenges/alphabet-rangoli/problem?isFullScreen=true <br>

title() capitalizes after any non-letter character.

Example:

s = "hello-world"

print(s.title())

Output:

Hello-World

while:

" ".join(word.capitalize() for word in s.split(' '))

gives:

Hello-world

>>> from itertools import permutations
>>> print permutations(['1','2','3'])
<itertools.permutations object at 0x02A45210>
>>> 
>>> print list(permutations(['1','2','3']))
[('1', '2', '3'), ('1', '3', '2'), ('2', '1', '3'), ('2', '3', '1'), ('3', '1', '2'), ('3', '2', '1')]
>>> 
>>> print list(permutations(['1','2','3'],2))
[('1', '2'), ('1', '3'), ('2', '1'), ('2', '3'), ('3', '1'), ('3', '2')]
>>>
>>> print list(permutations('abc',3))
[('a', 'b', 'c'), ('a', 'c', 'b'), ('b', 'a', 'c'), ('b', 'c', 'a'), ('c', 'a', 'b'), ('c', 'b', 'a')]
https://www.hackerrank.com/challenges/itertools-permutations/problem?isFullScreen=true

string:(why enumerate)
https://www.hackerrank.com/challenges/the-minion-game/problem?isFullScreen=true
