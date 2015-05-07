# Ruboty::Scorekeeper

ruboty handler.
increment decrement scorekeeper

![](https://www.evernote.com/shard/s4/sh/735a955e-0b8f-4b92-b5fa-fc37e0aa1d50/373f7227962198cfdbf0f2721813d3e5/deep/0/Slack.png)

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
* scorekeeper delete {name} - Delete a point of {name}

## Contributing

1. Fork it ( https://github.com/yoshiori/ruboty-scorekeeper/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
