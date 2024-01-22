## Preface
This programming language is merely a joke. It is a joke language based off a joke concept for humorous purposes only, although it should be able to be compiled to C (and possibly self-hosted).

**This is also incomplete.** The grammar of the language **has not been formally specified** in this version of the document.

## Rationale
There is no rationale. This is purely a joke meant to torture whoever who writes this cursed thingy of a thing.

## Naming Conventions
You can use whatever naming conventions that you would like. Be sure to mix up camelCase, PascalCase, snake_case and sucklesscase for the best effect!

## Reserved Emoticons
In DKS, many of the common programming symbols have been replaced with furry emoticons, as most commonly seen on discord kitten user groups.

* `-3-` replaces `#` to make a comment
* `=w=` replaces the `=` sign.
* Anything that prefixes `=` in other normal languages should replace the first `=` in DiscordKittenScript, with the exception of the less than character `<`, which should replace the last `=`. Examples include:
	* `>=` is now `>w=`
	* `<=` is now `=w<`
	* `+=` is now `+w=`
	* etc.
* The greater than and less than symbols should also be suffixed with a `w`.
	* `>w`
	* `w<`
* The double quotation mark is replaced by `>w<`
* The single quotation mark is replaced by `>.<`
* `,` is replaced by `-w-`
* `:` is replaced by `OuO`
* `;` is replaced by `OwO`
* The left and right brackets have been replaced with `~_` `_~`
* The left and right square brackets have been replaced with `u_` `_u`
* The left and right curly braces have been replaced with `^_`  `_^`
* The arithmetic operators are unchanged.

|Emoticon|Internal meaning|
|-|-|
|`-3-`|`Comment`|
|`=w=`|`Equal`|
|`w=w` |`EqualTo`|
|`!w=` |`NotEqual`|
|`>w=`|`GreaterThanEqual`|
|`=w<`|`LessThanEqual`|
|`>w`|`GreaterThan`|
|`w<`|`LessThanEqual`|
|`>w<`|`DoubleQuote`|
|`>.<`|`SingleQuote`|
|`-w-`|`Comma`|
|`OuO`|`Colon`|
|`OwO`|`Semicolon`|
|`~_`|`OpeningBracket`|
|`_~`|`ClosingBracket`|
|`u_`|`OpeningSquareBracket` |
|`_u`|`ClosingSquareBracket` |
|`^_`|`OpeningCurlyBracket` |
|`_^`|`ClosingCurlyBracket` |
|`+` `-` `/` `*` `^` `%`| `Add` `Sub` `Div` `Mul` `Pow` `Mod`|
| `+w=` `-w=` `/w=` `*w=` |`AddAssign` `SubAssign` `DivAssign` `MulAssign`|

## Reserved Words
DiscordKittenScript only reserves 23 keywords, and they are as follows:

| keyword | meaning | description |
| ---- | ---- | ---- |
| `nya` | `And` | The and keyword. |
| `nyo` | `Not` | The not keyword. |
| `or` | `Or` | The or keyword. |
| `enough` | `Break` | Break out of a loop. |
| `more` | `Continue` | Continue a loop. |
| `stick` | `If` | The if keyword. |
| `shiny` | `Else` | The else keyword. |
| `ya` | `True` | True boolean value. |
| `na` | `False` | False boolean value. |
| `is` | `TypeIs` | Denotes the type of an ident. |
| `pukes` | `Returns` | Denotes the return value of a function. |
| `four` | `BeginFor` | The for keyword, for for loops |
| `chan` | `EndFor` | Terminates the condition section of a for loop |
| `funny` | `Function` | The function declaration keyword. |
| `capitalist` | `Local` | Make a variable local. |
| `communist` | `Global` | Make a variable global |
| `broke` | `Null` | Null. |
| `flaccid` | `Mut` | Mutable Variable declaration. |
| `hard` | `Const` | Constant Variable declaration. |
| `puke` | `Return` | Returns a value out of a function. |
| `simpfor` | `Import` | Import a module. |
| `pls` | `BlockBegin` | Begin a block. |
| `kthx` | `BlockEnd` | End a block. |
| `rainbow` | `MainBegin` | Begin the main section. |
| `vomit` | `MainEnd` | End the main section. |

## Example(s)

In Python:
```python
def factorial(n: int) -> int:
	if n == 1:
		return 1
	else:
		return n * factorial(n-1)

for i in range(n):
    print(i)
factorial(5)
```

In **DiscordKittenScript**:
```dks
-3- have fun reading this atrocity
-3- this source code form is licensed under the public domain

hard communist cstdio is module OwO
cstdio =w= simpfor ~_>w<stdio.h>w<_~ OwO

hard communist factorial is function~_integer_~ returns integer OwO
factorial =w= funny ~_n_~ pukes integer OwO
pls
	stick n w=w 1 pls
		puke n OwO
	shiny
		puke n * factorial ~_n-1_~ OwO
	kthx
kthx

-3- this is the main function
rainbow 
	flaccid capitalist i is integer OwO
	four i =w= 0 OwO i w< n OwO n +w= 1 chan
	    cstdio.printf ~_>w<%d\n>w< -w- ^i_~ OwO
	kthx
	
	factorial ~_5_~ OwO
vomit OwO
```
## Grammar

### Statements

There are several statements in DiscordKittenScript, namely:
* The function (`funny`)
* The program entrypoint (`rainbow` `vomit`)
* The If-Else (`stick` `shiny`)
* The for loop (`four` `chan`)
* The while loop does not exist. Begone, while loops!

**to be completed**
