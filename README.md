# AML-SYSTEM
AML SYSTEM USING BLOCKCHAIN
In this code, a blockchain object is initialized to store the transactions. The user is then prompted to enter the sender, receiver, and amount of the transaction. A new Transaction object is created with this information, and the is_valid_transaction function is used to check if the transaction is valid (i.e., not suspicious or fraudulent). If the transaction is valid, it is added to the blockchain. Otherwise, it is declined. This process continues indefinitely until the program is stopped.

The blockchain.h file contains the necessary definitions and implementations for the Blockchain and Transaction classes. It is beyond the scope of this answer to provide the complete code for these classes, but they should include the following features:

The Transaction class should have member variables for the sender, receiver, and amount of the transaction, as well as any other relevant information (e.g., timestamp, transaction ID).
The Blockchain class should have a std::vector of Transaction objects to store the transactions, as well as a std::string to store the current block hash. It should also have functions for adding transactions, generating the next block, and computing the current block hash.
The is_valid_transaction function should implement the necessary checks to detect suspicious or fraudulent transactions. This could include checking the transaction history of the sender and receiver, comparing the transaction amount to known thresholds, and using machine learning algorithms to identify patterns that indicate potential money laundering.
