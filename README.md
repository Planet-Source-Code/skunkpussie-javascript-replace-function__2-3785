<div align="center">

## Javascript Replace function


</div>

### Description

How to use the String.replace function
 
### More Info
 
Returns the string with the replaced characters


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[SkunkPussie](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/skunkpussie.md)
**Level**          |Intermediate
**User Rating**    |3.8 (19 globes from 5 users)
**Compatibility**  |
**Category**       |[String Manipulation](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/string-manipulation__2-60.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/skunkpussie-javascript-replace-function__2-3785/archive/master.zip)





### Source Code

```
// look for the word 'four' and replace with 'five' for all(g option) occurences
// String.replace(/text to find/options,replacement text)
sTMP = "see my four assed monkey, see my four assed monkey"
sTMP = sTMP.replace(/four/g,"five")
// outputted text looks like this
// sTMP = "see my five assed monkey, see my five assed monkey"
// without the (g) option it would look like this
sTMP = "see my four assed monkey, see my four assed monkey"
sTMP = sTMP.replace(/four/g,"five")
// outputted text looks like this
// sTMP = "see my five assed monkey, see my four assed monkey"
```

