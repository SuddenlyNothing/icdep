# How can we add additional features to the protocol without breaking previous functionality?

We can add any features through a dictionary of rules.

The first step would be to come up with an algorithm on how to interpret a unique identifier. For example, `text` would mean that the file is a text file while `html` would mean the file is an html file. This can also include using identifiers as storing information. For example, if I wanted to note who's already received the card, the identifier could be received[Alice, Bob, Carol, Dave, ...]

The next step would be to distribute these rules to everyone so that they can understand what these unique identifiers mean.

After dstribution, these unique identifiers can be packaged with the messages and the receiver will be able to interpret the meaning through the rules.

This method allows for any feature to be implemented so long as they are able to follow these steps.
