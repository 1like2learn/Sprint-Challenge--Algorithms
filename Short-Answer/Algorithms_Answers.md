#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)O(n)
The number of operations that must be performed is multiplied by n. If n was two it would look like this.
a < 8
a = 0 + 4
It would require two loops for the condition to be met. The same is true for 3 or 4.

b) n sqrt(n) The number of nested loops required increases as n increases but it increases very slowly. The larger n is the slower the number of nested loops increases.


c) O(n) For every increase in n the function will run a proportionate number of times

## Exercise II 
              bot =   0   0   0   0   0  0 4
building floors = n = 100 /49 /24 /12 /6 / 6
eggs = plenty
f = ?

top = n
bot = 0
mid = n // 2 
while top - bot > 0:
  if egg breaks @ mid:
    top = mid -1
    mid = (top - bot) // 2
  if egg not break
    bot = mid + 1
    mid = (top + bot) //2
f = mid

Complexity is log(n) because I am using a binary search function.
