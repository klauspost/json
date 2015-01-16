json
=====

A fork of the official Go library that allows streaming indented output.


# Usage

1) Replace ```import "encoding/json"``` with ```import github.com/klauspost/json```.

2) Replace 	```err = encoder.Encode(&entry)``` with ```err = encoder.EncodeIndent(&entry, "", "  ")``` where you want your JSON to be indented.

