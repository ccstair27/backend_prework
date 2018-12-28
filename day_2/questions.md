## Day 2 Questions

1. Create an array containing the following strings: `"zebra", "giraffe", "elephant"`.

```ruby
["Zebra", "Giraffe", "Elephant"]
```

2. Save the array you created above to a variable `animals`.

```ruby
animals = ["Zebra", "Giraffe", "Elephant"]
```

3. using the array `animals`, how would you access `"giraffe"`?

```ruby
animals[1]
```

4. How would you add `"lion"` to the `animals` array?

```ruby
animals << "lion"
```

5. Name and describe two additional array methods.

`Array#last` returns the last item of the array.
`Array#collect` and `Array#map` take a block as an argumet.  Then it iterates through the array and invokes the block on each element.  Then it returns a new array with the return value of the block as each element.

6. What are the boolean values in Ruby?

`true` and `false`.

7. In Ruby, how would you evaluate if `2` is equal to `25`? What is the result of this evaluation?

```ruby
2 == 25 # => False
```

8. In Ruby, how would you evaluate if `25` is greater than `2`? What is the result of this evaluation?

```ruby
25 > 2 # => True
```
