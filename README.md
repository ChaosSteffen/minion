# Installation

First, git clone the repo:
```
git clone https://github.com/bananaltd/minion.git
cd minion
```

After that, get dependencies and compile:
```
mix deps.get
mix compile
```

Then, start with
```
elixir --name minion --cookie minion --no-halt -pa ebin --app minion
```

Or, Start interactive with
```
iex --name minion --cookie minion -S mix
```

# Documentation

Look, there is [beautifully generated documentation](http://bananaltd.github.io/minion/docs/) for you! It describes all the features on the master branch.

To generate the documetation on your own, just run:
```
mix deps.get
mix docs
```

Then, have a look into your projects `/docs` folder.

# What to do with Minion

Execute shell commands on all Nodes:
```
Cmd.all "ls"
```

# Contributors

* Steffen Schröder ([@ChaosSteffen](https://github.com/ChaosSteffen))
* Christoph Grabo ([@asaaki](https://github.com/asaaki))
* Sascha Depold ([@sdepold](https://github.com/sdepold))
