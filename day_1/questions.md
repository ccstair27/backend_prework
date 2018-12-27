## Day 1 Questions

1. How would you print the string `"Hello World!"` to the terminal?
```ruby
p "Hello World!"
```

2. What is the character you would use to indicate comments in a ruby file?
`#`

3. Explain the difference between an integer and a float?
An integer is a whole number like `4` while an float is a decimal like `4.0`.

4. In the space below, create a variable `animal` that holds the string `"zebra"`
```ruby
animal = "zebra"
```

5. How would you print the string `"zebra"` using the variable that you created above?
```ruby
p animal
```

6. What is interpolation? Use interpolation to print a sentence using the variable `animal`.
Interpolation is a way to insert code snippets into strings.
```ruby
p "One time I saw a #{animal} at the zoo."
```

7. How do we get input from a user? What is the method that we would use?
We can use the `gets` method.  For example:
```ruby
puts "What is your name?"
name = gets.chomp
```

8. Name and describe two common string methods.
`String#length` returns the number of characters in a string.
`String#split` returns an array of strings that were part of the original string separated by a space.  It takes an optional argument so you can split where there is a `,` or even each character if you pass in `""`.
