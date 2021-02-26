# Etherium-Fraud-Detection


#Context

This dataset contains rows of known fraud and valid transactions made over Ethereum, a type of cryptocurrency. This dataset is imbalanced, so keep that in mind when modelling
Content

#Here is a description of the rows of the dataset:

    Index: the index number of a row

    Address: the address of the ethereum account

    FLAG: whether the transaction is fraud or not

    Avg min between sent tnx: Average time between sent transactions for account in minutes

    Avgminbetweenreceivedtnx: Average time between received transactions for account in minutes

    TimeDiffbetweenfirstand_last(Mins): Time difference between the first and last transaction

    Sent_tnx: Total number of sent normal transactions

    Received_tnx: Total number of received normal transactions

    NumberofCreated_Contracts: Total Number of created contract transactions

    UniqueReceivedFrom_Addresses: Total Unique addresses from which account received transactions

    UniqueSentTo_Addresses20: Total Unique addresses from which account sent transactions

    MinValueReceived: Minimum value in Ether ever received

    MaxValueReceived: Maximum value in Ether ever received

    AvgValueReceived5Average value in Ether ever received

    MinValSent: Minimum value of Ether ever sent

    MaxValSent: Maximum value of Ether ever sent

    AvgValSent: Average value of Ether ever sent

    MinValueSentToContract: Minimum value of Ether sent to a contract

    MaxValueSentToContract: Maximum value of Ether sent to a contract

    AvgValueSentToContract: Average value of Ether sent to contracts

    TotalTransactions(IncludingTnxtoCreate_Contract): Total number of transactions

    TotalEtherSent:Total Ether sent for account address

    TotalEtherReceived: Total Ether received for account address

    TotalEtherSent_Contracts: Total Ether sent to Contract addresses

    TotalEtherBalance: Total Ether Balance following enacted transactions

    TotalERC20Tnxs: Total number of ERC20 token transfer transactions

    ERC20TotalEther_Received: Total ERC20 token received transactions in Ether

    ERC20TotalEther_Sent: Total ERC20token sent transactions in Ether

    ERC20TotalEtherSentContract: Total ERC20 token transfer to other contracts in Ether

    ERC20UniqSent_Addr: Number of ERC20 token transactions sent to Unique account addresses

    ERC20UniqRec_Addr: Number of ERC20 token transactions received from Unique addresses

    ERC20UniqRecContractAddr: Number of ERC20token transactions received from Unique contract addresses

    ERC20AvgTimeBetweenSent_Tnx: Average time between ERC20 token sent transactions in minutes

    ERC20AvgTimeBetweenRec_Tnx: Average time between ERC20 token received transactions in minutes

    ERC20AvgTimeBetweenContract_Tnx: Average time ERC20 token between sent token transactions

    ERC20MinVal_Rec: Minimum value in Ether received from ERC20 token transactions for account

    ERC20MaxVal_Rec: Maximum value in Ether received from ERC20 token transactions for account

    ERC20AvgVal_Rec: Average value in Ether received from ERC20 token transactions for account

    ERC20MinVal_Sent: Minimum value in Ether sent from ERC20 token transactions for account

    ERC20MaxVal_Sent: Maximum value in Ether sent from ERC20 token transactions for account

    ERC20AvgVal_Sent: Average value in Ether sent from ERC20 token transactions for account

    ERC20UniqSentTokenName: Number of Unique ERC20 tokens transferred

    ERC20UniqRecTokenName: Number of Unique ERC20 tokens received

    ERC20MostSentTokenType: Most sent token for account via ERC20 transaction

    ERC20MostRecTokenType: Most received token for account via ERC20 transactions
