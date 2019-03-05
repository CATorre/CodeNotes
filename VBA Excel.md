# Excel VBA (duplicate macro) #
Developer tab, click on 'record macro'.
Press 'alt f11' shortcut to review code in the VBA Editor.
Then you can add a button to this macro.

# Creating a loop #
create macro
Sub DuplicateSheet()
'
' DuplicateSheet Macro
'
Dim counter As Integer

For counter = 1 To 5    'This will determine how many sheets you will copy.

    Sheets("Random Data").Select
    Sheets("Random Data").Copy After:=Sheets(3)

Next counter


End Sub

Sub Text()


MsgBox ActiveWorkbook.Sheets.Count


End Sub
