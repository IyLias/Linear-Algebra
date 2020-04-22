# About

questions for coding Theory


# Q's

- I recently started studying coding Theory and little bit confused with the definition of 
(n,M,d) code.

<p>

It says that 

<p> if there are M codewords s.t. distances between every 2 codewords are at least d with length n, then there exists a (n,M,d) code

So for example, we can get 2-(2,4,1) code s.t. {(00),(01),(10),(11)}

At this moment I have a question. 

If I extract one of them in 2-(2,4,1) code element, Its minimum distance is still 1. So I can get 2-(2,3,1) code.

Similarly, I can also get 2-(2,2,1) , 2-(2,1,1) code.

<br>

Is this right based on definition of (n,M,d) code?

and if I'm right, why only use 2-(2,4,1) code ?

Is it because we are only interested in maximum M s.t. satisfies definition of (n,M,d) code? 

* ( related with theorem " d is odd , existence of (n,M,d) code iff. existence of (n+1,M,d+1) code" and "d is odd, A2(n+1,d+1) = A2(n,d)
and d is even, A2(n,d) = A2(n-1,d-1)" )

## Reference

- [Singleton Bound](https://en.wikipedia.org/wiki/Singleton_bound)

  - https://math.stackexchange.com/questions/682609/prove-a-q3-2-q2-for-all-q-ge-2



