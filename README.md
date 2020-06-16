# superRichTextFSC
LWC for Rich Text management in Flows

1)	Block disallowed words and symbols
    a.	Control whether this is a hard block or not.
    b.	Allow setting of Toast Mode, Message and Type.
2)	Search and Replace custom text
3)	Search and Replace branded/suggested words
4)	Revert mass changes
5)	Control allowance of ‘Previous’ Navigation.


Parameter	                I	    O	    Information
allowBack	                X		        Determines whether or not Screen shows Previous navigation
autoReplaceMap	          X		        JSON formatted key:value map.  Key will be replaced by Value
disallowedSymbols	        X		        Regex for disallowed symbols
disallowedWords	          X		        Regex for disallowed words
disallowedSymbolsMessage	X		        Message to show when disallowed symbols used
disallowedWordsMessage	  X		        Message to show when disallowed words used
disallowedSymbolsType	    X		        Toast message type for disallowed symbols usage (error)
disallowedSymbolsMode	    X		        Toast message mode for disallowed symbols usage (sticky)
disallowedSymbolsType	    X		        Toast message type for disallowed words usage (error)
disallowedSymbolsMode	    X		        Toast message mode for disallowed words usage (sticky)
hardBlock	                X		        If True, then block ‘Next’ action until error resolved
richText	                X	    X	    Input and output RichText that you’ll be editing
