# Go-Implementation-of-Blockchain-

This code showcases,how the blockchain works in its Low-Level.

Usually Blocks are added in the blockchain, and itfollows the structure of a Merkle Tree.

The Merkle Tree is a kind of a LinkedList which holds PreviousHash|Data|TimeStamp|CurrentHash|Nonce(i.e Position).

The Hashing Algorithm used by the Blockchain is SHA-256, which will be done on the user data to hash it.

Code is written by imagining a simple features of E-commerce like an Order of a customer on any Products which has its own ID,Name,Price.

It is shown by creating an endpoints like getBlockchain, newOrder, WriteBlock.

User's request will be in the form of json. i.e, { 'id':xxx, 'name':abcd, 'price':100}

Response will be fetched based on the endpoints in the User Request.


# STEPS TO RUN A GO FILE

Download go: https://go.dev/doc/install

Download an extension for Go in your IDE.

Terminal ->Open the Project Folder -> Type (go mod init) -> go.mod will be created-> Create a  main.go file (main indicating a standalone Program)

When importing "github.com/gorilla/mux" in your main.go, Type "go mod tidy" in your Terminal. A new go.sum (config. file) will be created.

To Run: go run main.go
