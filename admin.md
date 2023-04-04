## Idea for Admin Calls
1. One corner has information about where the message is from including: name of sender, network prefix location (ECE) and network location idenity (025), boolean if the sender is an admin.
2. Two corner has information were the message is going to including name of reciever, network prefix location (ECE) and network location idenity (025), boolean , boolean if sender is network admin.
3. the third corner of the card would identify the type the message is (Command, ASCII text, Unicode text, or binary values)
3. Now, when the Network Admin wants to send a call to a node it will first see if that node is in the its network, using the corner send information. 
4. Address the note card to that person and give it to them directly. The person would then execute the instructions on the card if the see it is from the admin within their network. 
5. The reciever will potentially send back a response on a new note card to the admin


### Issues with Solution
1. the information I am asking for to be put in corners of the card are a lot, so it can be jumbled up and not have space for it. I believe we inform everyone that each corner will have various amount of underline blank spot that are indexed. Each index is known for dedicated information/protocol what should be in each blank. 
2. Overall, the space issue is my main concern, but if we can create short hand keys and known index what each corners blank place holder are I think it will work. 

Example w/ one corner: Bob (sender), ECE (Prefix), 025 (network identity), Y (sender is admin)

Example w/ two corner:  Rob (reciever), ECE (Prefix), 026 (network identity), Y (sent from network admin)

Example w/ 3 corner: cmd (Type)

If we can keep the corners consistent and concise, we can create a mangable note card for admin actions. 
