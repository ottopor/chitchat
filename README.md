# chitchat

Distributed one stop social and cloud solution for everyday users. I'm still trying to write the specs before starting actual work on it.

## How is it different from existing solution

We would like to have this running from any desktop that will create a social network instance and will start communicating with the person's friends (that were added already). We already have Movim, Diaspora but they're hard to setup and requires a VPS to run.

With this approach, user and his friends will own the shared contents. 

This would be an application that would reside on a laptop or desktop of an everyday user.

The application will use peer to peer network to establish DNS between instances. User's client will update the IP address to that DNS periodically. Peer to peer network will also work as content distributor, it will keep the messages moving when one of the destination instance is turned off.

When a user adds a friend, they'll exchange tokens/keys (like gnupg keys) and that will encrypt decrypt messages between them. Also will authenticate that the user is a trusted one.

For social exchange, we can use protocol from matrix.org.

Users content will reside on his/her computer. So the data will always belong to the user.
