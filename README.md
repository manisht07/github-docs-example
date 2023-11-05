# Writing Good Documentation

## Step 1 - Using Codeblocks

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, and share** code. A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

```ruby
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Test the factorial function
number = 5
result = factorial(number)
puts "The factorial of #{number} is #{result}"
```
Make note of where it is located, it should appear above the tab key, and it may vary based on the keyboard layout.

![66a294b3-474c-450f-9602-77b94e741877](https://github.com/manisht07/github-docs-example/assets/83353539/1d584b04-ebce-4fd6-94d0-f00bfb8ad62c)

Good Cloud engineers use code blocks for code and error.

```bash
NameError: undefined local variable or method `some_value' for main:Object
```





