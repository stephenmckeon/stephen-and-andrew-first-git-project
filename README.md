# My Favorite Ruby Methods

### `loop`

- A loop allows us to tell our program to execute our code a certain number of times, or until a condition is met.

```ruby
counter = 0 
loop do 
  counter += 1  		 		
  if counter >= 10 
    break 
  end
end
```

### `each`

- Is a way to iterate over each element in an array. 

```ruby
names = ["Jo", "Liam", "Garett"] 
  names.each do |name|
  name + "!"
end 
["Jo!", "Liam!", "Garett!"]
```

### `push`

- Is a way to add an element to the end of an existing array. 

```ruby 
names = ["Jo", "Liam", "Garett"]
  names.push("Maddie")
end
["Jo", "Liam", "Garett", "Maddie"]
 ```
### `pop`

- Is a way to remove the last item from an exiting array. 

```ruby
names = ["Jo", "Liam", "Garett"]
  names.pop("Garett")
end
["Jo", "Liam"]
```

