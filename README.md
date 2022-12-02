# Implementation-of-Network-Security-using-Standard-ACL
In our project, we are going to implement network security using standard ACL.
The main of our project is to ensure network security by not allowing any 
unauthorized users to access our network. In the implementation phase, we tend to 
block the malicious host who is trying to access the network by any means. We 
have also implemented the remove facility of malicious user by not letting them 
participate in the main network.
Access Control Lists (ACL) is a group of sequential statements that define whether 
packets are accepted or rejected coming into an interface or leaving an interface. 
ACL statements operate in sequential, logical order. If a condition match is true the 
packet is permitted or denied and the rest of Access Control List statements are not 
checked. If all the Access Control List statements are unmatched an implicit “deny 
any” statement is placed at the end of the list by default. Access Control List 
evaluates packets from the top down. Once there is an access list statement match, 
the packet skips the rest of the statements. If a condition match is true, the packet is 
permitted or denied.
We are using Standard ACL for the basic implementation of our project. Standard 
Access Control Lists are the oldest type of Access Control List. Standard IP Access 
Lists are used to permit or deny traffic only based on source IP address of IP 
datagram packets and it can be created by using the “access-list” IOS command.
