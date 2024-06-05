The PyChain application leverages the power of Streamlit to provide an intuitive interface for interacting with a blockchain. Let’s break down its core components and functionality.

Key Features

	1.	Adjustable Block Difficulty
	•	At the top, you have a slider labeled “Block Difficulty.” This lets you modify how challenging it is to mine a new block, ranging from 1 to 5. Adjusting this affects the computational effort needed to validate new blocks.
	2.	Block Inspector
	•	This section allows you to select and inspect various blocks from the blockchain. Using a dropdown menu, you can choose a block to view its details, such as the creator_id, nonce, prev_hash, record, and timestamp. This helps in understanding the structure and data of each block.
	3.	Transaction Record Form
	•	Here, you can input details for a new transaction:
	•	Sender: Who is sending the funds.
	•	Receiver: Who is receiving the funds.
	•	Amount: The amount being transferred.
	•	Once you fill in these fields, hitting the “Add Block” button will create a new block with this transaction and add it to the blockchain.
	4.	The PyChain Ledger
	•	Below the form, you can see “The PyChain Ledger,” a table listing all blocks currently in the blockchain. Each entry shows the record (transaction details), creator_id, and prev_hash (previous block’s hash). This provides a clear view of the blockchain’s current state.
	5.	Chain Validation
	•	At the bottom, there’s a “Validate Chain” button. Clicking this will check the integrity of the blockchain, ensuring that all blocks are correctly linked and no tampering has occurred.

How It Works

	•	Depositing and Withdrawing: Users can enter their Ethereum account details to deposit or withdraw funds, which are managed by the smart contract on the blockchain. This interaction is handled using the Web3.py library.
	•	Transaction Visualization: The application updates in real-time, showing newly added blocks in the ledger table, giving users immediate feedback on their transactions.
	•	Streamlit Integration: Streamlit makes it easy to create this kind of interactive web application, with straightforward components for forms, tables, and real-time data updates.

Example Usage

	1.	Set Block Difficulty: Use the slider to set how hard it is to mine new blocks.
	2.	Enter Transaction Details: Input the sender, receiver, and amount in the provided form fields.
	3.	Add Block: Click “Add Block” to record the transaction in a new block.
	4.	Inspect Blocks: Use the block inspector to view details of any block in the chain.
	5.	Validate Chain: Ensure the blockchain’s integrity by validating the chain.

Conclusion

This PyChain Streamlit application offers a user-friendly way to interact with a blockchain, making it accessible for users to manage and inspect transactions. Its real-time updates and clear interface simplify the process of blockchain interaction, making it an excellent tool for both educational and practical purposes.

![Alt text](./Images/Images/1_pic.png)

![Alt text](./Images/Images/2_pic.png)

![Alt text](./Images/Images/3_pic.png)

![Alt text](./Images/Images/balloon_pic.png)