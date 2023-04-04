# How can we send commands ("SLEEP", "RESTART", "ARE-YOU-THERE", etc) to individual nodes in the network, rather than treat them as pass-through intermediaries?

To send commands to individual nodes in the network, we can add protocol where the sender asks the receiver to follow commands on the card while also passing the card and command on.

This would lead to Alice passing a note to a node and telling the node to follow the commands on the note and pass the command and note on. The node would the follow the command and pass the note and telling the following node to follow the commands on the note and pass the command and note on (the same thing Alice did).
