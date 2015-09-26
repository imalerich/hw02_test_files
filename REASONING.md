## Invalid

header_invalid0:
	extra comma in headers (inside)
	In this example, the 3rd header is invalid.
	Error at Line 0.

header_invalid1:
	extra comma in headers (trailing)
	In this example, the 6th header is invalid.
	Error at Line 0.

header_invalid2:
	extra comma in headers (leading)
	In this example, the 1st header is invalid.
	Error at Line 0.

header_invalid3:
	bogus header (BOGUS)
	In this example, the 4th header is invalid.
	Error at Line 0.

header_invalid4:
	the first header is invalid for obvious reasons, but is longer than 64 characters,
	the pdf says we can assume all headers will be shorter than 64 characters,
	so we probably won't be tested on this, but makes for more robust code
	In this example, the 1st header is invalid.
	Error at Line 0.

## Valid

header_valid0:
	I do not know if they will test for this, but I do not believe are test should be case sensitive
	correct me if I'm wrong ;)
	No Error.

header_valid1:
	Uses different ordering in the headers, but is still valid
	No Error.
