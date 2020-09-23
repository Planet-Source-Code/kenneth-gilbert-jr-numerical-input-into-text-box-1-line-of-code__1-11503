<div align="center">

## Numerical input into text box \(1 line of code\)


</div>

### Description

With this 1 line of code you can strip non-numerical input into text boxes.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Kenneth Gilbert Jr\.](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/kenneth-gilbert-jr.md)
**Level**          |Beginner
**User Rating**    |4.2 (25 globes from 6 users)
**Compatibility**  |VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[VB function enhancement](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/vb-function-enhancement__1-25.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/kenneth-gilbert-jr-numerical-input-into-text-box-1-line-of-code__1-11503/archive/master.zip)





### Source Code

```
Private Sub Text1_KeyPress(KeyAscii As Integer)
' Force numbers only in a text box
If IsNumeric(Chr(KeyAscii)) <> True Then KeyAscii = 0
End Sub
```

