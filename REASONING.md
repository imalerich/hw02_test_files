## Invalid

header_invalid0:
	extra comma in headers (inside)
	3rd Header is invalid.
	Error at Line 0.

header_invalid1:
	extra comma in headers (trailing)
	6th Header is invalid.
	Error at Line 0.

header_invalid2:
	extra comma in headers (leading)
	1st Header is invalid.
	Error at Line 0.

header_invalid3:
	bogus header (BOGUS)
	4th Header is invalid.
	Error at Line 0.

header_invalid4:
	the first header is invalid for obvious reasons, but is longer than 64 characters,
	the pdf says we can assume all headers will be shorter than 64 characters,
	so we probably will not be tested on this, but makes for more robust code.
	1st Header is invalid.
	Error at Line 0.

data_invalid0:
	RHx should not be a double.
	Error at Line 1.

data_invalid1:
	Wind Dir should not be a double.
	Error at Line 6.

## Valid

header_valid0:
	I do not know if they will test for this, but I do not believe are test should be case sensitive
	correct me if I am wrong ;)
	No Error.

header_valid1:
	Uses different ordering in the headers, but is still valid
	No Error.
