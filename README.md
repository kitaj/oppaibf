# oppaibf

brainfuck with oppai kaomoji.

## usage

You just 'gem install bfrb'.

And run:

  oppaibf examples/sample

## commands

* | . . | -- Increment the pointer. '>'
* | + + | -- Decrement the pointer. '<'
* (.Y.) -- Increment the byte at the pointer. '+'
* (.)(.) -- Decrement the byte at the pointer. '-'
* (o)(o) -- Output the byte at the pointer. '.'
* ( o )( o ) -- Input a byte and store it in the byte at the pointer. ','
* ( @ )( @ ) -- Jump forward past the matching (q )( p) if the byte at the pointer is zero. '['
* (q )( p) -- Jump backward to the matching ( @ )( @ ) unless the byte at the pointer is zero. ']'
