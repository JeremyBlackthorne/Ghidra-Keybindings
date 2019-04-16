# Partial IDA Pro KeyBindings for Ghidra
I've been using Ghidra alongside IDA Pro and remembering different keybindings for each was tiresome so I updated 20 of my most commonly used keys in IDA Pro to be the same in Ghidra, with some suggestions from others.

Table included below for browsing.

## Install
In Ghidra's CodeBrowser, go to the menu Edit->Tool Options, then click KeyBindings on the left. On the bottom right, click the button Import and select the file ending in .kbxml in the repository. There's a button to restore defaults at any time too.

## Custom KeyBindings
<body link="#0563C1" vlink="#954F72">

<table border=0 cellpadding=0 cellspacing=0 width=921 style='border-collapse:
 collapse;table-layout:fixed;width:691pt'>
 <col class=xl66 width=31 style='mso-width-source:userset;mso-width-alt:981;
 width:23pt'>
 <col width=309 style='mso-width-source:userset;mso-width-alt:9898;width:232pt'>
 <col width=172 span=2 style='mso-width-source:userset;mso-width-alt:5504;
 width:129pt'>
 <col width=237 style='mso-width-source:userset;mso-width-alt:7594;width:178pt'>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl65 width=31 style='height:18.0pt;width:23pt'>!=</td>
  <td class=xl65 width=309 style='width:232pt'>Action Name</td>
  <td class=xl65 width=172 style='width:129pt;font-size:12.0pt;color:black;
  font-weight:700;text-decoration:none;text-underline-style:none;text-line-through:
  none;font-family:Calibri, sans-serif;background:#FFC7CE;mso-pattern:black none'>Default
  KeyBinding</td>
  <td class=xl65 width=172 style='width:129pt;font-size:12.0pt;color:black;
  font-weight:700;text-decoration:none;text-underline-style:none;text-line-through:
  none;font-family:Calibri, sans-serif;background:#FFC7CE;mso-pattern:black none'>Custom
  KeyBinding</td>
  <td class=xl65 width=237 style='width:178pt'>Plugin Name</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>View Program Differences</td>
  <td class=xl67>2</td>
  <td class=xl67>2</td>
  <td>ProgramDiffPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'>&#128213;</td>
  <td>Define string</td>
  <td style='background:#FFC7CE;mso-pattern:black none'></td>
  <td style='background:#FFC7CE;mso-pattern:black none'>A</td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Expand All</td>
  <td>Alt-DOWN</td>
  <td>Alt-DOWN</td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Add To Program</td>
  <td>Alt-I</td>
  <td>Alt-I</td>
  <td>ImporterPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'>&#128213;</td>
  <td>Add Bookmark</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>Meta-D</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>Alt-M</td>
  <td>BookmarkPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Create Default Reference</td>
  <td>Alt-R</td>
  <td>Alt-R</td>
  <td>ReferencesPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Next in History Buffer</td>
  <td>Alt-RIGHT</td>
  <td>Alt-RIGHT</td>
  <td>NextPrevAddressPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Collapse All</td>
  <td>Alt-UP</td>
  <td>Alt-UP</td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Clear Function Return Type</td>
  <td>C</td>
  <td>C</td>
  <td>FunctionPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Clear Parameter Data Type</td>
  <td>C</td>
  <td>C</td>
  <td>FunctionPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Clear Variable Data Type</td>
  <td>C</td>
  <td>C</td>
  <td>FunctionPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'>&#128213;</td>
  <td>Disassemble</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>D</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>C</td>
  <td>DisassemblerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'>&#128213;</td>
  <td>Edit Stack Frame</td>
  <td style='background:#FFC7CE;mso-pattern:black none'></td>
  <td style='background:#FFC7CE;mso-pattern:black none'>Ctrl-K</td>
  <td>StackEditorManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'>&#128213;</td>
  <td>Cycle: byte,word,dword,qword</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>B</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>D</td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Delete</td>
  <td>DELETE</td>
  <td>DELETE</td>
  <td>DataTypePreviewPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Delete</td>
  <td>DELETE</td>
  <td>DELETE</td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Delete Archive</td>
  <td>DELETE</td>
  <td>DELETE</td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Delete Bookmarks</td>
  <td>DELETE</td>
  <td>DELETE</td>
  <td>BookmarkPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Delete Comments</td>
  <td>DELETE</td>
  <td>DELETE</td>
  <td>CommentsPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Delete folder/fragment</td>
  <td>DELETE</td>
  <td>DELETE</td>
  <td>ProgramTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Delete Function</td>
  <td>DELETE</td>
  <td>DELETE</td>
  <td>FunctionPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Delete Function Variable</td>
  <td>DELETE</td>
  <td>DELETE</td>
  <td>FunctionPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Delete References From</td>
  <td>DELETE</td>
  <td>DELETE</td>
  <td>ReferencesPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Delete Register Value Range</td>
  <td>DELETE</td>
  <td>DELETE</td>
  <td>RegisterPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Delete Symbols</td>
  <td>DELETE</td>
  <td>DELETE</td>
  <td>SymbolTablePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Delete Symbols</td>
  <td>DELETE</td>
  <td>DELETE</td>
  <td>SymbolTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Remove Equate</td>
  <td>DELETE</td>
  <td>DELETE</td>
  <td>EquatePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Remove Items</td>
  <td>DELETE</td>
  <td>DELETE</td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Remove Label</td>
  <td>DELETE</td>
  <td>DELETE</td>
  <td>LabelMgrPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Remove Stack Depth Change</td>
  <td>DELETE</td>
  <td>DELETE</td>
  <td>FunctionPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Rename Equate</td>
  <td>E</td>
  <td>E</td>
  <td>EquatePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Set Equate</td>
  <td>E</td>
  <td>E</td>
  <td>EquatePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'>&#128213;</td>
  <td>Previous in History Buffer</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>Alt-LEFT</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>ESCAPE</td>
  <td>NextPrevAddressPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Create External Function</td>
  <td>F</td>
  <td>F</td>
  <td>FunctionPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Create Function</td>
  <td>F</td>
  <td>F</td>
  <td>FunctionPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Cycle: float,double</td>
  <td>F</td>
  <td>F</td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Edit Function</td>
  <td>F</td>
  <td>F</td>
  <td>FunctionPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Disassemble Arm</td>
  <td>F11</td>
  <td>F11</td>
  <td>DisassemblerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Disassemble MIPS</td>
  <td>F11</td>
  <td>F11</td>
  <td>DisassemblerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Disassemble PPC</td>
  <td>F11</td>
  <td>F11</td>
  <td>DisassemblerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Disassemble MIPS16/Micromips</td>
  <td>F12</td>
  <td>F12</td>
  <td>DisassemblerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Disassemble PPC-VLE</td>
  <td>F12</td>
  <td>F12</td>
  <td>DisassemblerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Disassemble Thumb</td>
  <td>F12</td>
  <td>F12</td>
  <td>DisassemblerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Repeat Memory Search</td>
  <td>F3</td>
  <td>F3</td>
  <td>MemSearchPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Source Code Lookup</td>
  <td>F3</td>
  <td>F3</td>
  <td>SourceCodeLookupPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'>&#128213;</td>
  <td>Display Decompiler</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>Meta-E</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>F5</td>
  <td>DecompilePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Go To Address/Label</td>
  <td>G</td>
  <td>G</td>
  <td>GoToAddressLabelPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Show All History</td>
  <td>H</td>
  <td>H</td>
  <td>LabelMgrPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Show Label History</td>
  <td>H</td>
  <td>H</td>
  <td>LabelMgrPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Import File</td>
  <td>I</td>
  <td>I</td>
  <td>ImporterPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Edit External Location</td>
  <td>L</td>
  <td>L</td>
  <td>LabelMgrPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Add Default Memory Reference</td>
  <td>M</td>
  <td>M</td>
  <td>ReferencesPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Set Default Register Reference</td>
  <td>M</td>
  <td>M</td>
  <td>ReferencesPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Set Default Stack Reference</td>
  <td>M</td>
  <td>M</td>
  <td>ReferencesPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Next Highlighted Range</td>
  <td>Meta-0</td>
  <td>Meta-0</td>
  <td>NextPrevHighlightRangePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Previous Highlighted Range</td>
  <td>Meta-9</td>
  <td>Meta-9</td>
  <td>NextPrevHighlightRangePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Select All</td>
  <td>Meta-A</td>
  <td>Meta-A</td>
  <td>CodeBrowserPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Select All Code Units</td>
  <td>Meta-A</td>
  <td>Meta-A</td>
  <td>FunctionGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Next Bookmark</td>
  <td>Meta-Alt-B</td>
  <td>Meta-Alt-B</td>
  <td>NextPrevCodeUnitPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Open/Close Program View</td>
  <td>Meta-Alt-C</td>
  <td>Meta-Alt-C</td>
  <td>ProgramDiffPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Next Data</td>
  <td>Meta-Alt-D</td>
  <td>Meta-Alt-D</td>
  <td>NextPrevCodeUnitPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Enable/Disable Byteviewer Editing</td>
  <td>Meta-Alt-E</td>
  <td>Meta-Alt-E</td>
  <td>ByteViewerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Next Function</td>
  <td>Meta-Alt-F</td>
  <td>Meta-Alt-F</td>
  <td>NextPrevCodeUnitPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Extract and Import</td>
  <td>Meta-Alt-I</td>
  <td>Meta-Alt-I</td>
  <td>ImporterPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Next Instruction</td>
  <td>Meta-Alt-I</td>
  <td>Meta-Alt-I</td>
  <td>NextPrevCodeUnitPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Next Label</td>
  <td>Meta-Alt-L</td>
  <td>Meta-Alt-L</td>
  <td>NextPrevCodeUnitPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Set Operand Label</td>
  <td>Meta-Alt-L</td>
  <td>Meta-Alt-L</td>
  <td>LabelMgrPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Next Non-Function</td>
  <td>Meta-Alt-N</td>
  <td>Meta-Alt-N</td>
  <td>NextPrevCodeUnitPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Toggle Code Unit Search Direction</td>
  <td>Meta-Alt-T</td>
  <td>Meta-Alt-T</td>
  <td>NextPrevCodeUnitPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Next Undefined</td>
  <td>Meta-Alt-U</td>
  <td>Meta-Alt-U</td>
  <td>NextPrevCodeUnitPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Next Different Byte Value</td>
  <td>Meta-Alt-V</td>
  <td>Meta-Alt-V</td>
  <td>NextPrevCodeUnitPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Previous Selected Range</td>
  <td>Meta-BRACELEFT</td>
  <td>Meta-BRACELEFT</td>
  <td>NextPrevSelectedRangePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Next Selected Range</td>
  <td>Meta-BRACERIGHT</td>
  <td>Meta-BRACERIGHT</td>
  <td>NextPrevSelectedRangePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Copy</td>
  <td>Meta-C</td>
  <td>Meta-C</td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Copy</td>
  <td>Meta-C</td>
  <td>Meta-C</td>
  <td>ClipboardPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Go to next function</td>
  <td>Meta-DOWN</td>
  <td>Meta-DOWN</td>
  <td>CodeBrowserPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Find</td>
  <td>Meta-F</td>
  <td>Meta-F</td>
  <td>DecompilePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Find Data Types</td>
  <td>Meta-F</td>
  <td>Meta-F</td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Go To Last Active Program</td>
  <td>Meta-F6</td>
  <td>Meta-F6</td>
  <td>MultiTabPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Go To Program</td>
  <td>Meta-F7</td>
  <td>Meta-F7</td>
  <td>MultiTabPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Go To Previous Program</td>
  <td>Meta-F8</td>
  <td>Meta-F8</td>
  <td>MultiTabPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Go To Next Program</td>
  <td>Meta-F9</td>
  <td>Meta-F9</td>
  <td>MultiTabPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Go To start of folder/fragment in View</td>
  <td>Meta-G</td>
  <td>Meta-G</td>
  <td>ProgramTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Set Highlight From Selection</td>
  <td>Meta-H</td>
  <td>Meta-H</td>
  <td>SetHighlightPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Open File System</td>
  <td>Meta-I</td>
  <td>Meta-I</td>
  <td>FileSystemBrowserPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Retype Variable</td>
  <td>Meta-L</td>
  <td>Meta-L</td>
  <td>DecompilePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'>&#128213;</td>
  <td>Show Bookmarks</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>Meta-B</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>Meta-M</td>
  <td>BookmarkPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Zoom Out</td>
  <td>Meta-MINUS</td>
  <td>Meta-MINUS</td>
  <td>FunctionGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Open File</td>
  <td>Meta-O</td>
  <td>Meta-O</td>
  <td>ProgramManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Print</td>
  <td>Meta-P</td>
  <td>Meta-P</td>
  <td>PrintingPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Forward Refs</td>
  <td>Meta-PERIOD</td>
  <td>Meta-PERIOD</td>
  <td>SelectRefsPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Replace View</td>
  <td>Meta-R</td>
  <td>Meta-R</td>
  <td>ProgramTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Set Register Values</td>
  <td>Meta-R</td>
  <td>Meta-R</td>
  <td>RegisterPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Save File</td>
  <td>Meta-S</td>
  <td>Meta-S</td>
  <td>ProgramManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'>&#128213;</td>
  <td>View Memory Map</td>
  <td style='background:#FFC7CE;mso-pattern:black none'></td>
  <td style='background:#FFC7CE;mso-pattern:black none'>Meta-S</td>
  <td>MemoryMapPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Back Refs</td>
  <td>Meta-SEMICOLON</td>
  <td>Meta-SEMICOLON</td>
  <td>SelectRefsPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Search Text</td>
  <td>Meta-Shift-E</td>
  <td>Meta-Shift-E</td>
  <td>SearchTextPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'>&#128213;</td>
  <td>Zoom In</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>Meta-EQUALS</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>Meta-Shift-EQUALS</td>
  <td>FunctionGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Compare Two Functions</td>
  <td>Meta-Shift-F</td>
  <td>Meta-Shift-F</td>
  <td>FunctionComparisonPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Repeat Text Search</td>
  <td>Meta-Shift-F3</td>
  <td>Meta-Shift-F3</td>
  <td>SearchTextPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Assemble</td>
  <td>Meta-Shift-G</td>
  <td>Meta-Shift-G</td>
  <td>AssemblerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Rerun Last Script</td>
  <td>Meta-Shift-R</td>
  <td>Meta-Shift-R</td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>ByteViewer Clone</td>
  <td>Meta-Shift-T</td>
  <td>Meta-Shift-T</td>
  <td>ByteViewerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Code Viewer Clone</td>
  <td>Meta-Shift-T</td>
  <td>Meta-Shift-T</td>
  <td>CodeBrowserPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Decompile Clone</td>
  <td>Meta-Shift-T</td>
  <td>Meta-Shift-T</td>
  <td>DecompilePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Function Graph Clone</td>
  <td>Meta-Shift-T</td>
  <td>Meta-Shift-T</td>
  <td>FunctionGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Redo</td>
  <td>Meta-Shift-Z</td>
  <td>Meta-Shift-Z</td>
  <td>ProgramManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>View Symbol Table</td>
  <td>Meta-T</td>
  <td>Meta-T</td>
  <td>SymbolTablePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Go to previous function</td>
  <td>Meta-UP</td>
  <td>Meta-UP</td>
  <td>CodeBrowserPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Paste</td>
  <td>Meta-V</td>
  <td>Meta-V</td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Paste</td>
  <td>Meta-V</td>
  <td>Meta-V</td>
  <td>ClipboardPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Paste Symbols</td>
  <td>Meta-V</td>
  <td>Meta-V</td>
  <td>SymbolTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Cut</td>
  <td>Meta-X</td>
  <td>Meta-X</td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Cut SymbolTree Node</td>
  <td>Meta-X</td>
  <td>Meta-X</td>
  <td>SymbolTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Remove folder/fragment from View</td>
  <td>Meta-X</td>
  <td>Meta-X</td>
  <td>ProgramTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Undo</td>
  <td>Meta-Z</td>
  <td>Meta-Z</td>
  <td>ProgramManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'>&#128213;</td>
  <td>Add Label</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>L</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>N</td>
  <td>LabelMgrPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'>&#128213;</td>
  <td>Edit Label</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>L</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>N</td>
  <td>LabelMgrPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Rename Data Field</td>
  <td>N</td>
  <td>N</td>
  <td>DataPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'>&#128213;</td>
  <td>Rename Function</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>L</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>N</td>
  <td>FunctionPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'>&#128213;</td>
  <td>Rename Function</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>L</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>N</td>
  <td>DecompilePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'>&#128213;</td>
  <td>Rename Function Variable</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>L</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>N</td>
  <td>FunctionPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'>&#128213;</td>
  <td>Rename Variable</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>L</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>N</td>
  <td>FunctionPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'>&#128213;</td>
  <td>Rename Variable</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>L</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>N</td>
  <td>DecompilePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Export Program</td>
  <td>O</td>
  <td>O</td>
  <td>ExporterPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Define Array</td>
  <td>OPEN_BRACKET</td>
  <td>OPEN_BRACKET</td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Commit Params/Return</td>
  <td>P</td>
  <td>P</td>
  <td>DecompilePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Define pointer</td>
  <td>P</td>
  <td>P</td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Add</td>
  <td>PLUS</td>
  <td>PLUS</td>
  <td>DataTypePreviewPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Cycle: char,string,unicode</td>
  <td>QUOTE</td>
  <td>QUOTE</td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>View/Edit References From</td>
  <td>R</td>
  <td>R</td>
  <td>ReferencesPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Search Memory</td>
  <td>S</td>
  <td>S</td>
  <td>MemSearchPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Edit Comments</td>
  <td>SEMICOLON</td>
  <td>SEMICOLON</td>
  <td>CommentsPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Edit Variable Comment</td>
  <td>SEMICOLON</td>
  <td>SEMICOLON</td>
  <td>FunctionPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'>&#128213;</td>
  <td>Auto Analyze</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>A</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>Shift-A</td>
  <td>AutoAnalysisPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'>&#128213;</td>
  <td>Clear Cut</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>ESCAPE</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>Shift-ESCAPE</td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Create Structure</td>
  <td>Shift-OPEN_BRACKET</td>
  <td>Shift-OPEN_BRACKET</td>
  <td>DataPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Recover Structure Variable</td>
  <td>Shift-OPEN_BRACKET</td>
  <td>Shift-OPEN_BRACKET</td>
  <td>DecompilePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Toggle Expand/Collapse Data</td>
  <td>SPACE</td>
  <td>SPACE</td>
  <td>CodeBrowserPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Choose Data Type</td>
  <td>T</td>
  <td>T</td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'>&#128213;</td>
  <td>Clear Code Bytes</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>C</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>U</td>
  <td>ClearPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Define void</td>
  <td>V</td>
  <td>V</td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Display Register Values</td>
  <td>V</td>
  <td>V</td>
  <td>RegisterPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'>&#128213;</td>
  <td>Find References To</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>Meta-Shift-F</td>
  <td style='background:#FFC7CE;mso-pattern:black none'>X</td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'>&#128213;</td>
  <td>Find References To</td>
  <td style='background:#FFC7CE;mso-pattern:black none'></td>
  <td style='background:#FFC7CE;mso-pattern:black none'>X</td>
  <td>SymbolTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Recently Used</td>
  <td>Y</td>
  <td>Y</td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>About Ghidra</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>About program</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>AboutProgramPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Add Block</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>MemoryMapPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Add External Program Name</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ReferencesPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Add Reference From</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ReferencesPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Add Selection To Highlight</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SetHighlightPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Add to Version Control</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Aggressive Instruction Finder</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>AutoAnalysisPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Align All Data Types</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Align Data Type</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Analysis Bookmarks</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>MarkerManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Analyze All Open</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>AutoAnalysisPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Analyze Function Stack References</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Apply Enum</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>EquatePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Apply Function Data Types</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>ASCII Strings</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>AutoAnalysisPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Auto Set Fallthroughs</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FallThroughPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Batch Import</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ImporterPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Block Focus Mode</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Block Hover Mode</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Byte Viewer</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ByteViewerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Byte Viewer Options</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ByteViewerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Call Convention Identification</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>AutoAnalysisPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Call-Fixup Installer</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>AutoAnalysisPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Capture Function Data Types</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Carry Checksum Values</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ComputeChecksumsPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Changes: Unsaved</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>MarkerManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>CheckIn</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>CheckIn</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>MyProgramChangesDisplayPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>CheckOut</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Clear All Colors</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ColorizingPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Clear Color</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ColorizingPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Clear Console</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ConsolePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Clear Current Selection</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Clear External Name Association</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ReferencesPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Clear Fallthroughs</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FallThroughPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Clear Flow and Repair</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ClearPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Clear History Buffer</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>NextPrevAddressPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Clear Interpreter</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Python</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Clear Pinned Symbol</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SymbolTablePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Clear Register Values</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>RegisterPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Clear Selection</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>CodeBrowserPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Clear Translation Value</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>TranslateStringsPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Clear With Options</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ClearPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Close All</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ProgramManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Close Archive</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Close File</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ProgramManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Close Others</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ProgramManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Close Tool</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Close Tree View</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ProgramTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Collapse All Data</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>CodeBrowserPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Collapse All folders/fragments</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ProgramTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Commit Locals</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DecompilePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Commit To Archive</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Compare Selected Functions</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Compute Checksum</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ComputeChecksumsPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Configure Tool</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Contents</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Convert To Char</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>EquatePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Convert To Double</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>EquatePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Convert To Float</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>EquatePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Convert To Signed Decimal</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>EquatePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Convert To Signed Hex</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>EquatePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Convert To Unsigned Binary</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>EquatePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Convert To Unsigned Decimal</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>EquatePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Convert To Unsigned Hex</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>EquatePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Convert To Unsigned Octal</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>EquatePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Copy folder/fragment</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ProgramTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Copy Special</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ClipboardPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Copy Special Again</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ClipboardPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Create Address Tables</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>AutoAnalysisPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Create Class</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SymbolTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Create Complexity Depth Tree</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ProgramTreeModularizationPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Create Default Tree View</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ProgramTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Create Dominance Tree</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ProgramTreeModularizationPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Create External Location</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SymbolTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Create Folder</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ProgramTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Create Fragment</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ProgramTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Create Function Definition</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Create Labels From Enums</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Create Library</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SymbolTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Create Multiple Functions</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Create Namespace</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SymbolTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Create Offset References</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>OffsetTablePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Create Pointer</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Create Table From Selection</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>CodeBrowserPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Create Thunk Function</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Create Typedef</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Create Typedef From Dialog</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Cursor</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>MarkerManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Cut folder/fragment</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ProgramTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Data</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>QualifiedSelectionPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Data References From</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SymbolTablePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Data Settings</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Data Type Conflict Resolution Mode</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Data Type Manager</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Debug Function Decompilation</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DecompilePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Decompiler Parameter ID</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>AutoAnalysisPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Decompiler Switch Analysis</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>AutoAnalysisPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>DecompilerProperties</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DecompilePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Default Data Settings</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Define byte</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Define char</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Define double</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Define dword</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Define float</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Define int</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Define long</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Define longdouble</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Define qword</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Define TerminatedCString</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Define TerminatedUnicode</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Define uint</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Define ulong</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Define undefined</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Define word</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Delete</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>GhidraScriptMgrPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Delete Block</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>MemoryMapPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Delete Equate</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>EquateTablePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Delete External Program Name</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ReferencesPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Delete Register Value Ranges</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Register Manager</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Delete Tree View</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ProgramTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Disassemble Restricted</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DisassemblerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Disassemble Static</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DisassemblerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Disassociate From Archive</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Display Function Call Graph</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionCallGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Display Function Graph</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Display Popup Windows</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Display Satellite View</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionCallGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Display Satellite View</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Display Script Manager</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>GhidraScriptMgrPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Display Symbol Tree</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SymbolTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Dock Satellite View</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionCallGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Dock Satellite View</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Download_PDB_File</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>PdbSymbolServerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>DWARF Line Number</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>AutoAnalysisPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Edit</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Edit</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>GhidraScriptMgrPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Edit Archive Paths</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Edit Code Block Fields</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Edit Data Type</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Edit External Location</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SymbolTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Edit External Location</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SymbolTablePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Edit Function Purge</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Edit Function Signature</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DecompilePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Edit Function Tags</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionTagPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Edit Options</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Edit Structure</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Edit Vertex Label</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>EditDataType</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DecompilePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>EditEclipse</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>GhidraScriptMgrPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Embedded Media</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>AutoAnalysisPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Enum</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Enum from Selection</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Error Bookmarks</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>MarkerManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Exclude Operands</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>MnemonicSearchPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Exit Ghidra</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Expand All Data</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>CodeBrowserPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Expand All folders/fragments</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ProgramTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Expand Block Down</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>MemoryMapPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Expand Block Up</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>MemoryMapPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Export</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ExporterPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Export Data Types</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Export to C</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DecompilePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Export Tool</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Filter Arrays</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Filter Bookmarks</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>BookmarkPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Filter Data Types</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataWindowPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Filter Pointers</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Filter Registers</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Register Manager</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Find Data Types By Size</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Find Uses of Field</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Follow location changes</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Register Manager</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>FSB Create Crypto Key Template</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FileFormatsPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>FSB Decompile JAR</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FileFormatsPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>FSB Export Eclipse Project</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FileFormatsPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>FSB Load iOS Kernel</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FileFormatsPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Function Definition</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Function Graph Options</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Function ID</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>AutoAnalysisPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Function Start Search</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>AutoAnalysisPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>GenerateChecksum</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ComputeChecksumsPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Ghidra API Help</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>GhidraScriptMgrPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Go To External Location</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SymbolTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Go To Function Entry Point</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Graph Node Function Calls</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionCallGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Group Selected Vertices</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Hide Incoming Edges</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionCallGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Hide Incoming Level Edges</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionCallGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Hide Outgoing Edges</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionCallGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Hide Outgoing Level Edges</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionCallGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Highlight</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>MarkerManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Highlight Backward Inst Slice</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DecompilePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Highlight Backward Slice</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DecompilePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Highlight Defined Use</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DecompilePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Highlight Forward Inst Slice</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DecompilePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Highlight Forward Slice</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DecompilePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Import C DataTypes</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>CParserPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Include Data Members in Filter</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Include Operands</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>MnemonicSearchPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Include Operands (except constants)</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>MnemonicSearchPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Info Bookmarks</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>MarkerManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Installed Processors</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ProgramListPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Instruction References From</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SymbolTablePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Instructions</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>QualifiedSelectionPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Jump to a XRef</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Key Binding</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>GhidraScriptMgrPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Load PDB File</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>PdbPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Lock Archive</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Make Selection</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SymbolTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Make Selection</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Make Selection From Focused Edges</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Make Selection From Hovered Edges</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Merge Blocks</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>MemoryMapPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Merge folder/fragment with Parent</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ProgramTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Modify Instruction Flow</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DisassemblerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Modularize By Subroutine [Isolated Entry]</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ModuleAlgorithmPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Modularize By Subroutine [Multiple Entry]</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ModuleAlgorithmPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Modularize By Subroutine [Overlapped Code]</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ModuleAlgorithmPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Modularize By Subroutine [Partitioned Code]</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ModuleAlgorithmPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Move Block</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>MemoryMapPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Navigate on Incoming Location Changes</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionCallGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Navigation</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ProgramTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Navigation</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SymbolTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>New</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>GhidraScriptMgrPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>New Category</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>New File Data Type Archive</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>New Project Data Type Archive</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Next Color Range</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ColorizingPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Next Data Type in History</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Non-Returning Functions - Discovered</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>AutoAnalysisPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Note Bookmarks</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>MarkerManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>On Selection</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ComputeChecksumsPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Ones Complement</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ComputeChecksumsPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Open File Data Type Archive</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Open Project Data Type Archive</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Open Tree View</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ProgramTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Override Signature</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DecompilePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Overview</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>OverviewColorPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Page Setup</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>PrintingPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Paste folder/fragment</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ProgramTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Pin Symbol</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SymbolTablePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Previous Color Range</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ColorizingPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Previous Data Type in History</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Processor Options</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DisassemblerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Program Options</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ProgramManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Re-create Function</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>References To</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SymbolTablePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Refresh</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DecompilePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Refresh</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>GhidraScriptMgrPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Refresh BuiltInTypes</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Relayout Graph</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Remove From Group</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Remove Highlight</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SetHighlightPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Remove Invalid Archive</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Remove Signature Override</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DecompilePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Rename</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Rename</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>GhidraScriptMgrPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Rename folder/fragment</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ProgramTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Rename Fragment from Code Browser</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>AutoRenamePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Rename Fragment from Program Tree View</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>AutoRenamePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Rename Symbol</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SymbolTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Rename Tree View</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ProgramTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Reset Graph</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Reset Graph</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionCallGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Restore Selection</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>RestoreSelectionPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Revert Data Type</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Revert Thunk Function</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Run</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>GhidraScriptMgrPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Save</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Save All Files</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ProgramManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Save As File</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ProgramManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Save Tool</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Save Tool As</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Script Directories</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>GhidraScriptMgrPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Scroll Lock</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ConsolePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Search for Address Tables</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>AutoTableDisassemblerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Search for Direct References</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FindPossibleReferencesPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Search for Scalars</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ScalarSearchPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Search for Strings</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>StringTablePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Search Instruction Patterns</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>InstructionSearchPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>select addresses</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ProgramTreeSelectionPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Select All Flows From</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SelectByFlowPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Select All Flows To</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SelectByFlowPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Select Bookmark Locations</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>BookmarkPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Select Complement</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>CodeBrowserPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Select Dead Subroutine</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SelectByFlowPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Select Forward Scoped Flow</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SelectByScopedFlowPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Select Function</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SelectByFlowPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Select Limited Flows From</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SelectByFlowPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Select Limited Flows To</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SelectByFlowPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Select Program Changes</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SelectByFlowPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Select Register Value Ranges</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Register Manager</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Select Reverse Scoped Flow</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SelectByScopedFlowPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Select Subroutine</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SelectByFlowPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>SelectBlock</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SelectBlockPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Selection</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>MarkerManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Set Color</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ColorizingPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Set EOL Comment</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>CommentsPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Set External Name Association</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ReferencesPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Set External Program</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SymbolTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Set Fallthrough</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FallThroughPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Set Favorite Data Type</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Set Filter</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SymbolTablePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Set Image Base</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>MemoryMapPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Set Plate Comment</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>CommentsPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Set Post Comment</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>CommentsPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Set Pre Comment</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>CommentsPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Set Repeatable Comment</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>CommentsPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Set Selection From Highlight</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SetHighlightPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Set Stack Depth Change</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Set Thunked Function</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Shared Return Calls</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>AutoAnalysisPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Show Base Data Type</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Show Comment History</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>CommentsPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Show default register values</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Register Manager</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Show Function Call Trees</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>CallTreePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Show Hex Values</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ComputeChecksumsPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Show History</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Show Incoming Edges</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionCallGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Show Incoming Level Edges</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionCallGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Show Instruction Info</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ShowInstructionInfoPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Show Outgoing Edges</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionCallGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Show Outgoing Level Edges</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionCallGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Show Preview Window</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Show Processor Manual</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ShowInstructionInfoPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Sort Fragments By Address</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ModuleSortPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Sort Fragments By Name</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ModuleSortPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Split Block</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>MemoryMapPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Stack</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>AutoAnalysisPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Structure</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Subtract Selection From Highlight</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SetHighlightPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Symbol References</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SymbolTablePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Toggle Header</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>CodeBrowserPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Toggle Mouse Hover Popups</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>CodeBrowserPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Toggle Show Translated Value</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>TranslateStringsPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Translate with Manual</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>TranslateStringsPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Twos Complement</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ComputeChecksumsPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Undefined</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>QualifiedSelectionPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>UndoCheckOut</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Ungroup All Vertices</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Ungroup Selected Vertices</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Union</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Unlock Archive</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Update</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Update</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>MyProgramChangesDisplayPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Update From Archive</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>User Agreement</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>Tool</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Vertex View Mode</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>View Check Outs</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>DataTypeManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>View Symbol References</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>SymbolTablePlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Warning Bookmarks</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>MarkerManagerPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>XOR Checksum Values</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>ComputeChecksumsPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Zoom to Vertex</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionGraphPlugin</td>
 </tr>
 <tr height=24 style='mso-height-source:userset;height:18.0pt'>
  <td height=24 class=xl66 style='height:18.0pt'><span
  style='mso-spacerun:yes'> </span></td>
  <td>Zoom to Window</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>FunctionGraphPlugin</td>
 </tr>
 <![if supportMisalignedColumns]>
 <tr height=0 style='display:none'>
  <td width=31 style='width:23pt'></td>
  <td width=309 style='width:232pt'></td>
  <td width=172 style='width:129pt'></td>
  <td width=172 style='width:129pt'></td>
  <td width=237 style='width:178pt'></td>
 </tr>
 <![endif]>
</table>

</body>

</html>
