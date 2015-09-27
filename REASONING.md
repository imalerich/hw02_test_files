## Invalid Headers

header_invalid0:
	extra comma in headers (inside)
	3rd Header is invalid.
	Error at Line 1.

header_invalid1:
	extra comma in headers (trailing)
	6th Header is invalid.
	Error at Line 1.

header_invalid2:
	extra comma in headers (leading)
	1st Header is invalid.
	Error at Line 1.

header_invalid3:
	bogus header (BOGUS)
	4th Header is invalid.
	Error at Line 1.

header_invalid4:
	the first header is invalid for obvious reasons, but is longer than 64 characters,
	the pdf says we can assume all headers will be shorter than 64 characters,
	so we probably will not be tested on this, but makes for more robust code.
	1st Header is invalid.
	Error at Line 1.

header_invalid5:
	The NCDC header is listed twice.
	Error at Line 1.

header_invalid6:
	Headers are not allowed to have spaces in front of them, as per the blackboard discussion.
	Error at Line 1.

## Invalid Data

data_invalid0:
	RHx should not be a double.
	Error at Line 2.

data_invalid1:
	Wind Dir should not be a double.
	Error at Line 7.

data_invalid2:
	USAF expects an integer, a string type is provided.
	Error at Line 6.

data_invalid3:
	Wind Dir is out of the allowed range of values.
	Error at Line 2.

data_invalid4:
	Removes a necessary field from the inside of one of the rows.
	Error at Line 5.

data_invalid5:
	Removes a necessary field from the end of one of the rows.
	Error at Line 5.

## Invalid other

empty_row_invalid:
	An empty row is included within the data, I do not believe this is allowed.
	Error at Line 8.

empty_invalid:
	A completely empty file, not valid in the slightest.
	Error at Line 0.

## Valid Files

valid_format0:
	I do not know if they will test for this, but I do not believe are test should be case sensitive
	correct me if I am wrong ;)
	No Error.

valid_format1:
	Uses different ordering in the headers, but is still valid
	No Error.

valid_format2:
	Inputs a double using integer syntax, but is still within the acceptable range for that value.
	No Error.

valid_format3:
	Removes a necessary field from the end of one of the rows like data_invalid5,
	however a comma is added, so it is an empty field, because it is Wind Dir
	a default value can be assigned.
	Error at Line 5.
