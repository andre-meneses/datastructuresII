## Week 04

Another set of interview-like questions, now involving recursion. 

### Problem 1
> Nth Fibonacci

A classical fibonacci problem, I decided to use an iterative approach. 

### Problem 2

> If you open a keypad of your mobile phone, it will likely look like this:
>   ```
> ----- ----- -----
>  |     |     |     |
>  |  1  |  2  |  3  |
>  |     | abc | def |
>   ----- ----- -----
>  |     |     |     |
>  |  4  |  5  |  6  |
>  | ghi | jkl | mno |
>   ----- ----- -----
>  |     |     |     |
>  |  7  |  8  |  9  |
>  | pqrs| tuv | wxyz|
>   ----- ----- -----
>        |     |
>        |  0  |
>        |     |
>         -----
>   ```
>
>Almost every digit is associated with some letters in the alphabet; this allows certain phone numbers to spell out actual words.
>
>For example, the phone number 8464747328 can be written as timisgreat;
>
>similarly, the phone number 2686463 can be written as antoine or as ant6463.
>
>It's important to note that a phone number doesn't represent a single sequence of letters, but rather multiple combinations of letters. For instance, the digit 2 can represent three different letters (a, b, and c).
>
>A mnemonic is defined as a pattern of letters, ideas, or associations that assist in remembering something. Companies oftentimes use a mnemonic for their phone number to make it easier to remember.
>
>Given a stringified phone number of any non-zero length, write a function that returns all mnemonics for this phone number, in any order.
>
>For this problem, a valid mnemonic may only contain letters and the digits 0 and 1.
