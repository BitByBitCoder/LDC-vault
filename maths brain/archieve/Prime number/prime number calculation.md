There are many ways to check or calculate prime numbers.  
Each method is useful for different situations.
2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47, 53, 59, 61, 67, 71, 73, 79, 83, 89, 97 [[1](https://www.youtube.com/watch?v=WCbJ63M_-20&t=14)]

---

# What is a Prime Number?

A prime number has:

- exactly **2 factors**
    
- divisible only by:
    
    - 1
        
    - itself
        

Examples:

2, 3, 5, 7, 11, 13

Not prime:

4 → divisible by 2  
6 → divisible by 2 and 3

---

# 1. Basic Division Method

Try dividing the number by smaller numbers.

Example: 17

Check:

- 17 ÷ 2 ❌
    
- 17 ÷ 3 ❌
    
- 17 ÷ 4 ❌
    

No division works → PRIME

---

# 2. Square Root Method (Most Important)

You only test up to the square root.

Example: 97

[  
\sqrt{97} \approx 9.8  
]

So only test:

2, 3, 5, 7

Not divisible → PRIME

You stop because:

genui{"math_block_widget_always_prefetch_v2":{"content":"a^2+b^2=c^2"}}

Actually for primes, factors repeat after square root.

Example:

100 = 10 × 10

If a number had a factor bigger than 10, another factor must be smaller than 10.

So checking after √n is unnecessary.

---

# 3. Prime Number Filter Method

Use only known primes for checking.

Example: Check 137

[  
\sqrt{137} \approx 11.7  
]

Check only primes below 11.7:

- 2 ❌
    
- 3 ❌
    
- 5 ❌
    
- 7 ❌
    
- 11 ❌
    

Therefore PRIME.

This is faster.

---

# 4. Sieve of Eratosthenes

Best for finding MANY primes together.

Steps:

1. Write numbers
    
2. Remove multiples of 2
    
3. Remove multiples of 3
    
4. Remove multiples of 5
    
5. Continue
    

Remaining numbers are prime.

Example up to 20:

Start:

2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20

Remove multiples:

- 4,6,8,10...
    
- 9,12,15...
    
- etc.
    

Left:

2,3,5,7,11,13,17,19

---

# 5. Divisibility Rules Method

Quick rejection method.

## Even number

If ends in:

0,2,4,6,8 → not prime  
(except 2)

---

## Divisible by 3

Add digits.

Example:

123

1+2+3 = 6

6 divisible by 3 → 123 not prime

---

## Divisible by 5

Ends in 0 or 5 → not prime  
(except 5)

---

# 6. Fermat / Advanced Prime Tests

Used in:

- cryptography
    
- computers
    
- very large numbers
    

These use mathematical formulas instead of full division.

Not needed yet for competitive exam basics.

---

# Best Method for Competitive Exams

Usually use this order:

1. Check small rules
    
    - even?
        
    - divisible by 3?
        
    - divisible by 5?
        
2. Find square root
    
3. Test only prime numbers up to square root
    

That is the fastest manual method.

---

# Example Full Check

Is 221 prime?

Step 1:

Not even  
Digit sum = 2+2+1=5 → not divisible by 3  
Doesn't end in 5 or 0

Step 2:

[  
\sqrt{221} \approx 14.8  
]

Check primes below 15:

2,3,5,7,11,13

Try 13:

221 ÷ 13 = 17

So:

221 = 13 × 17

NOT PRIME.

---

# Summary Table

|Method|Best For|
|---|---|
|Basic Division|Beginners|
|Square Root Method|Competitive exams|
|Prime Filter|Faster checking|
|Sieve Method|Finding many primes|
|Divisibility Rules|Quick elimination|
|Fermat Test|Huge numbers/computers|