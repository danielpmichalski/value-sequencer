# value-sequencer
Value sequencer is a Java library that allows you to generate a list of values that are sequenced from the value from which you want the sequence to start

Let's say you want to generate string that conform to a RegExp [0-9]{3}[a-z]{4}[0-9], starting with value 000aaaa0.
The last possible value would be 999zzzz9. Examples:
- 000aaaa1
- 000aaaa2
- 000aaaa3
- 000aaaa4
- ...
- 000aaaa9
- 000aaab0
- ...
- 123abcz9
- 123abda0
- ...
