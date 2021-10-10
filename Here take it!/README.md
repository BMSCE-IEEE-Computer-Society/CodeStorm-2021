# Here, take it!

> Jump over fences to get to the mound!

> ` `

> ` `

> ` `

> ` `

> You missed a clue and some punctuation! But here is another:

> `ge·ihn·eteetofvhe·ir`

> And take your flag before you go.

> `jpu{rzzepgf_tp_dmn_pxvg_rsc_ejjq}`


# Solution

When you see encrypted text you know it involves a cipher. But what are they?

You will have two different ciphers. The clue is in the first sentence. When you search for `fence cipher` you get the `Rail Fence cipher`.

Similarly `mound` must mean something - it is a synonym for hill and we find the `Hill Cipher`.

Looks like we have to use one to decrypt the other.

Strangely there are 4 empty lines in the first clue.

After looking at the configuration options of the rail fence cipher we find that we have to enter `4` at two places(`offset` and `height`), and we get this:

![missing punctuation and spaces](here2.png?raw=true "missing punctuatin and spaces")

Did we miss the `punctuation and spaces option`? Yes.

![matrix values](here3.png?raw=true "matrix values")

Now we use these values to decrypt the flag:

![flag](here4.png?raw=true "flag")

# Flag

`ctf{getting_up the_hill_was_hard}`
