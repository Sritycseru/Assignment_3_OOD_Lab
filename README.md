This design follows object-oriented principles. Thos program is building a banking system.
I have encapsulated the account-specific data (like balance) and behavior (deposit, withdraw, transfer) within the IAccount and its implementing classes (Chequing, Saving, Investment), ensuring data integrity and modularity.

There are different types of accounts (Chequing, Saving, Investment) that share common behaviors defined in the IAccount interface.
I am using composition to manage multiple accounts within the BankService class by maintaining a Hashtable of accounts, allowing for easy access and management of accounts.
 Each account has a unique account number, ensuring that accounts can be identified and managed individually.
