How to use each of the wildcard. 
* Matches zero to any number of characters
? Matches only one character
[set] Matches only 1 character

How to use Brace Expansion to create entire directory structures. 
Start with an open brace
With no spaces, type your string separating entries by a command.
Close the brace
example mkdir -pv example_site /{assets/large,docs/share,scripts/js}