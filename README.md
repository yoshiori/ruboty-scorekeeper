# Ruboty::Scorekeeper

ruboty handler.
increment decrement scorekeeper

```
> r7kamura++
incremented r7kamura (1 pt)
> @r7kamura:++
incremented r7kamura (2 pt)
> r7kamura:++
incremented r7kamura (3 pt)
> con_mame++
incremented con_mame (1 pt)
> yoshiori--
decremented yoshiori (-1 pt)
> ruboty show scoreboard
1 : r7kamura (3 pt)
2 : con_mame (1 pt)
3 : yoshiori (-1 pt)
```
## Usage

* {name}++ - Increment {name}'s point
* {name}-- - Decrement {name}'s point
* scorekeeper - Show scoreboard
* show scoreboard - Show scoreboard
* scorekeeper {name} - Show current point of {name}
* what's the score of {name} - Show current point of {name}

## Contributing

1. Fork it ( https://github.com/yoshiori/ruboty-scorekeeper/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
