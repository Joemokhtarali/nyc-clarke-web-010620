# Hasketball Review Part 2

## SWBATs
- [ ] Explain what these iterators do:
    - [ ] #each
    - [ ] #select
    - [ ] #map
    - [ ] #find
- [ ] Explain the basic flow of git
- [ ] Use the basic functions of git

### Enumerable Methods in ruby
* each
* map - put whatever the block returns in a new array
* find - return the first thing that returns true 
* select - returns all the things that returned true

### Methods in ruby
* Implicit return
* Explicit return
* binding.pry

## Git terms

* Remote repository - place online where your code is stored (e.g. github, bitbucket)
* Local repository - place on your machine where the code is stored (i.e. folder on your computer)



```ruby
def game_hash
    # returns a big hash with relavant data
end

def all_players
    game_hash[:home][:players].concat(game_hash[:home][:players])
end

def find_player(player_name)
    all_players.find { |player| player[:player_name] == player_name }
end

def num_points_scored(player_name)
    find_player(player_name)[:points]
end
```
We didn't have to make so many different methods, but now the code is more readable, updatable and modular because we did.

### number_points_scored
* break large problems into small problems
* get quick feedback loop (code something, try it out)
