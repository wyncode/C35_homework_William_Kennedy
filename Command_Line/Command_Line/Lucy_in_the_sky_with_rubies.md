Here is a sample ruby app:

```ruby
puts "Welcome..."
sleep 2
puts "Let's play a game, what is your name?"
users_name = gets.chomp
puts "One second, calculating..."
sleep 3
puts "Great, #{users_name.chars.shuffle.join} is your new name - Goodbye!"
```

Copy, paste and save the above content into a file on your computer named `lucy.rb`. What is the command you would use to run this file?