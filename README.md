# tools
Toolbox Sharing

## qr.zip
qr - Fast recording tool 快速记录工具

一个类似 `ls`、`top` 的 Linux 命令行工具，用于快速记录和检索信息。
A Linux command-line tool like `ls` and `top` for fast information recording and retrieval.

### Core features
1. **qr add "content"** - Add a record and return the row ID
2. **qr grep "keyword"** - Find records containing a keyword
   - Alias：`qr f "keyword"`、`qr g "keyword"`、`qr q "keyword"` (Shortcut input)
3. **qr all** - Show all records
4. **qr del <rowID>** - Delete the record with the specified row ID
