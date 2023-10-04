# CodingQuizOct4

Camel Case Time Complexity:
O(n) as a for loop iterates n-1 (the
length of the string excluding the first index)
times.

Camel Case Space Complexity:
O(c) because only three variables, two integers
and a char,
are used to store values throughout the entirety
of the code.

Corectness & Loop INvariant Time Copmlexity:
O(n^2) as the final (n-1) indices of the integer
array A of length n are iterated through in a
for loop and the while loop nested within the for
loop runs O(n) times as it iterates from j = (i-1) to j = 0
as long as the value at A[j] is greater than the value variable.

Correctness & Loop Invariant SPace Complexity:
O(c) as three integers are initialized and used to
either iterate through the loops or store the value
of A at a specific index.
