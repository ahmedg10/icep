# Adding Additional Features Without Breaking Network
I feel that we can utlize the corners of the card to add information about who is sending and receiving the message. I feel by adding headers to the cards corners and back of card, we are able to inject additional information that will give us increased capabilties in what we can do with card. Below, I have included some header data that can be defualt card headers that network sender needs to identify to give our network most flexibilites when adding features: 

1. One corner has information about where the message is from including: name of sender, network prefix location (ECE) and network location idenity (025).
2. Another corner has information were the message is going to including name of reciever, network prefix location (ECE) and network location idenity (025), boolean if its in the same network as the sender.
3. The third corner of the card would identify the type the message is (ASCII text, Unicode text, or binary values)
4. In order to reference what nodes interacted with message, I would probably use the same solution as my anti-dupe, and use the back of card to identify what nodes has touched the card. 


## Issues that may arise
I would like to awknowledge, that I feel that the features, I descriped covers majority of information needed to have more features added seemlessly. However, if I'm missing information in the features, we should only give the sender limited capability to add additional information needed for their new feature in a "other info" corner. We want to avoid allowing too many additions to header/ card corners because it can lead to more vulnerabilties. However, if we give the sender a little corner to put additonal information not intalized by my defualt information I defined above, this should allow for any feature to be developed. 
