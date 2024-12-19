# WAD

## Header 
|Position| Size | Field Name | Description |
|--|--|--|--|
| 0 | 4 | sig      | ASCII string "PWAD", or "IWAD"|
| 4 | 4 | numFiles | Number of files |
| 8 | 4 | offFAT   | Offset of directory from start of file |

## Directory

|Position| Size | Field Name | Description |
|--|--|--|--|
| 0 | 4 | offData | Offset of lump data, from start of WAD file |
| 4 | 4 | lenData | Size of lump, in bytes |
| 8 | 8 | name    | Name of lump |
