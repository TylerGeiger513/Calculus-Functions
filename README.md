# Calculus-Functions
This program returns the valid delta values using the delta - epsilon definition of a limit in calculus
When demonstrating that $\lim_{x \to -1} 2x+5 = 3 \text{ with } \epsilon = 0.1$ which of the following $\delta$ values suffices?

$\delta$ = 0.0166666666667 <br>
$\delta$ = 0.05 <br>
$\delta$ = 0.1 <br>
$\delta$ = 0.0025 <br>

To solve this you would run 
```js
const f_x = (x) => {
    return (2 * x) + 5;
}

console.log(validDeltas(f_x, 3, -1, 0.1, [0.0166666666667, 0.05, 0.1, 0.0025]))
which would return the valid deltas:
[0.0166666666667, 0.05, 0.0025]
```
