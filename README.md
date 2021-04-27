# Group-16-Decentralized-Stock
Decentralized network project for CS 4675/6675

## Following Stocks (PubSub)


Multiple user opinion files are already created in the folders titled 'subscribe-<user nickname>'. Each folder contains the user's opinions in JSON format that will be used in the chat room application. To create a peer that joins the chat room of a stock they are interested in:

	1. Open a terminal window and direct yourself to the Group 16 - Stock Opinions - Pubsub/ folder
	2. In the terminal, type 'go run . -nick=<user nickname>'. The <user nickname> must match one of the nicknames associated with the stocks folders.
	3. Continue to open more terminal windows and run the program with other user nicknames.
	4. Type a message in any terminal window and press enter. The message should appear in all of the other windows. 
	5. Feel free to type the other commands from any of the terminal windows ('/share', '/listopinions', '/avgrating')
