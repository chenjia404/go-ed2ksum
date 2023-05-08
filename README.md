### Go library to calculate ed2k hashes


fork from https://github.com/Jessidhia/go-ed2k

## build 

`go build -trimpath -ldflags="-w -s" -o ed2ksum`


## how to use

`.\ed2ksum.exe ed2ksum.exe` outputs the  `3220ca970de224c869073272cd44040f  ed2ksum.exe`


`.\ed2ksum.exe -uri ed2ksum.exe` outputs the  `ed2k://|file|ed2ksum.exe|707584|3220ca970de224c869073272cd44040f|/`


## check ed2ksum

`./ed2ksum.exe  ./ed2ksum.exe > checksum.txt` 

` ./ed2ksum.exe  -c checksum.txt ` outputs the `./ed2ksum.exe: OK`