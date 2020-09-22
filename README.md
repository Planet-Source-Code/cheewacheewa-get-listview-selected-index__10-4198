<div align="center">

## get listview selected index


</div>

### Description

get listviews selected index
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[CheewaCheewa](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/cheewacheewa.md)
**Level**          |Beginner
**User Rating**    |4.8 (38 globes from 8 users)
**Compatibility**  |VB\.NET
**Category**       |[Controls/ Forms/ Dialogs/ Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/controls-forms-dialogs-menus__10-3.md)
**World**          |[\.Net \(C\#, VB\.net\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/net-c-vb-net.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/cheewacheewa-get-listview-selected-index__10-4198/archive/master.zip)

### API Declarations

found it cruising web,author unknown.


### Source Code

```
Private Sub ListView1_SelectedIndexChanged(ByVal sender As Object, ByVal e As System.EventArgs) Handles ListView1.SelectedIndexChanged
    'get listviews selected index
    If Me.ListView1.SelectedIndices.Count <= 0 Then
      Return
    End If
    Dim selNdx = Me.ListView1.SelectedIndices(0)
    If selNdx >= 0 Then
      MsgBox(ListView1.Items(selNdx).Text)
    End If
  End Sub
```

