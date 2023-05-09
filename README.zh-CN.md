### Go ed2k哈希计算库


fork 自 https://github.com/Jessidhia/go-ed2k

## 编译 

`go build -trimpath -ldflags="-w -s" -o ed2ksum`


## 使用方法

`.\ed2ksum.exe ed2ksum.exe` 输出  `3220ca970de224c869073272cd44040f  ed2ksum.exe`


`.\ed2ksum.exe -uri ed2ksum.exe` 输出 `ed2k://|file|ed2ksum.exe|707584|3220ca970de224c869073272cd44040f|/`


## check ed2ksum

`./ed2ksum.exe  ./ed2ksum.exe > checksum.txt` 

` ./ed2ksum.exe  -c checksum.txt ` 输出 `./ed2ksum.exe: OK`

不要使用 powershell, 它默认使用 utf-16 编码，验证会出错