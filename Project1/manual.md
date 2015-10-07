ASL

### NAME
**ASL** - Calculates the average number of words in a sentence for the given file. 

### SYNOPSIS

	java main [FILEPATH] [-d DELIMITERS] [-l MINIMUMWORDLENGTH]

### DESCRIPTION

**ASL** calculates the average number of words in a sentence for the given input file. The user specifies some sentence delimiters and a minimum word length and the words less than the specified length will be ignored. Also, there are some default delimiters - .?!; and the default minimum word length is taken as 3.

### OPTIONS

	-d=DELIMITERS
		Set the sentence level delimiters. Default sentence delimiters are .?!;

	-l=MINIMUM WORD LENGTH
		Set the minimum acceptable word length in a sentence, any word less than this minimum word length would not be counted. The default minimum word length is 3.


ASL