# todo-term

todo-term is a todo list utility for the commandline 

It uses git to manage synchronization but can, with a little bit of tweaking, be used without it.

## Getting started

- Download todo and put it where it suits you
- Add todo to your PATH
- Create a remote repository you want to sync with (at [bitbucket](https://bitbucket.org) they have free private repositories)

Then run:

```bash
todo -s
```

## Available commands

	h|help)   Print this help page
	a|add)    Add an item (will enter interactive mode if no argument is given)
	t|toggle) Toggle checked state of an item (will enter interactive mode if no argument is given)
	d|delete) Delete an item (will enter interactive mode if no argument is given)
	r|reset)  Reset todo list
	f|fetch)  Fetch todo list from remote repository
	p|push)   Push todo list to remote repository
	s|setup)  Setup todo list
	c|clear)  Clear todo list

## License

See [LICENSE](LICENSE.md)

