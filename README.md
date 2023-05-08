### Go library to calculate ed2k hashes


fork from https://github.com/Jessidhia/go-ed2k

## build 

`go build -trimpath -ldflags="-w -s" -o ed2ksum`


## how to use

`.\go-ed2ksum.exe go-ed2ksum.exe` outputs the  `3220ca970de224c869073272cd44040f  go-ed2ksum.exe`


`.\go-ed2ksum.exe -uri go-ed2ksum.exe` outputs the  `ed2k://|file|go-ed2ksum.exe|707584|3220ca970de224c869073272cd44040f|/`


## check ed2ksum

`./go-ed2ksum.exe  ./go-ed2ksum.exe > checksum.txt` 

` ./go-ed2ksum.exe  -c checksum.txt ` outputs the `./go-ed2ksum.exe: OK`