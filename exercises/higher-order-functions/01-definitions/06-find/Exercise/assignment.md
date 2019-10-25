# Assignment

Write an extension method `FindFirst(this IEnumerable<T> xs, Func<T, bool> predicate)` that
returns the first element of `xs` that satisfies `predicate`.

```csharp
// Retrieves the primes for numbers
new List<int>() { 1, 2, 3, 4, 5 }.FindFirst( IsPrime ); // 2
```
