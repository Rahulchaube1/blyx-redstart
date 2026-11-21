## Update a binary-event probability after observations

Returns [posterior mean, posterior variance, posterior alpha, posterior beta]. This conjugate model assumes exchangeable Bernoulli observations. Invalid arguments and nonfinite results return an empty vector.

1. Open an empty file named `redstart-demo.blyx`.
2. Type `blyx-redstart-demo` and select **Redstart — runnable example**. You can also use **Snippets: Fill File with Snippet**.
3. Choose **Blyx: Run File** from the command palette. Change an argument near the end of `fn main()` to try another input.

Expected output

```text
0.5
0.05
2
2
```

[Work through the example in the browser](https://www.blyx-lang.space/play?example=package-redstart)
