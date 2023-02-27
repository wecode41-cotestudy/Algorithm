# 1. Big O
## Goal
- Can explain about Big O
- Can predict performance time of our code
- Can find out the part where performance time is too long
- Can reduce performance time (fix our code)

## Let's calculate running time of this code!

```
for
...
.....
```

### Imagine that N getting bigger
```
N = 10, 100, 1000, 1000000....
```

## Big O :
- If our algorithm goes worst, it takes time maximum Big O.
- We can use Big O to predict the performance time.
- Expression : O(1), O(N), O(logN)...

## How can we reduce performance time?
- (Judy) Avoid duplicated loop
```
for
  for
```
- In `if A and B`, let A that takes shorter performance time
  - When running `if A and B`, if A is false, B is not performed. 
