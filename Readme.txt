--------------------------------------------------------------------------------------------------------------
 DBH
--------------------------------------------------------------------------------------------------------------
 
 Conversion program for: 
	Int64<->Hex, 
	(Single/Double) Float<-> IEEE754 Dec, Hex
	Selectable Hex data order.

 UINT64 to Bytes/bits: 
	Input is a Uint64: 0 -> 18446744073709551615 )

 Bytes to UINT64/Bits to UNIT64: 
	8x 0->255  to build up a value 0 -> 18446744073709551615
	or use 8x8 bits by selecting desired bit to set it from 0 to 1 or from 1 to 0

 Logic: (Uint64) AND, OR, XOR (bitwise logic)
	+ MOD, DIV



 *Number fields work with ENTER (Type value and press ENTER)

--------------------------------------------------------------------------------------------------------------
 
 memo 1, 2 ,3:
	Useful to save some data
	All memos have automatic save / loading



--------------------------------------------------------------------------------------------------------------

 Style selection: 
	Selection list box at bottom right corner.
	Default style is "Windows"



--------------------------------------------------------------------------------------------------------------

 DBH_Settings.ini


 Form_X, Form_Y:	Program window Position on screen
 ConfirmExit=1		(0 or 1) Display a Exit confirmation message
 OnTop=0		(0 or 1) Program window is top-most window
 ActivePage=0		active/selected page,  set to -1 to disable (first Page is selected as default)
 ActiveMemo=0		active/selected memo page,  set to -1 to disable (first Page is selected as default)
 Style=Windows		Selected window Style

--------------------------------------------------------------------------------------------------------------










--------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------
07.06.2024 (v1.0.1.7)
--------------------------------------------------------------------------------------------------------------
07.06.2024 (v1.0.1.8)
+save data
--------------------------------------------------------------------------------------------------------------













--------------------------------------------------------------------------------------------------------------
Code: LARK_1
--------------------------------------------------------------------------------------------------------------
