## Notes7

## How to use each of the wildcard. 

## * Matches zero to any number of characters 
### Example 
* ls *.pdf
* 
## ? Matches only one character
### Example s 
 ls program?.py

## [] 1 character from a given set of characters
### Example 
ls document [A-Z].doc

## [!] The opposite of the given set

### Example
ls new-doc[!0-9].docx

## How to use 
 Expansion to create entire directory structures. 
Start with an open brace
With no spaces, type your string separating entries by a command.
Close the brace
example mkdir -pv example_site /{assets/large,docs/share,scripts/js}