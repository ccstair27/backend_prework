## Day 4 Questions

1. In your own words, what is the purpose of a method?

A method is a way to save some code to be executed so we can call it more easily without having to type it out again.

2. In the space below, create a method named `hello` that will print `"Sam I am"`.

``` ruby
def hello
  puts "Sam I am"
end
```

3. Create a method name `hello_someone` that takes an argument of `name` and prints `"#{name} I am"`.

``` ruby
def hello_someone(name)
  puts "#{name} I am"
end
```

4. How would you call or execute the method that you created above?

``` ruby
hello_someone("Sam")
```

5. What questions do you still have about methods in Ruby?

How do I know if a variable passed in will be mutated or not?
