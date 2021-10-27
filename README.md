# Mod
HotKeySet("{ESC}", "_Exit")  ; The count variable $iCount = 0  While 1     ; Current value     ConsoleWrite($iCount &amp; @CRLF)     ; Get the Mod of the current value + 1     $iCount = Mod($iCount + 1, 6)     ; Just to keep it slow enough to read     Sleep(500)  WEnd  Func _Exit()     Exit EndFunc
