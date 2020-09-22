<div align="center">

## A REAL RANDOM NUMBER GENERATOR


</div>

### Description

This code will create completely random numbers for you!
 
### More Info
 
The user MUST hace a Label named Label1 and a Button named Command1!!!

This program, after pressing the button, creates a random number in the label.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Alex M](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/alex-m.md)
**Level**          |Beginner
**User Rating**    |3.1 (34 globes from 11 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/alex-m-a-real-random-number-generator__1-24508/archive/master.zip)





### Source Code

```
Sub Command1_Click ()
Randomize 'makes it random
  'makes a random number, 1 - 100 in Label1
  Value = Int(100 * Rnd)
  Label1.Caption = Str$(Value)
End Sub
```

