# DBAssignment
Task is to add functionality for a transfer of money between accounts. Following changes is done for the same

1  Added TransferRequest DTO in domain pkg.
2  Updated Account Service with this new method for money transfer between accounts.
     
    public void transferMoney(TransferRequest transferRequest)

3 Updated the controller and Expose an endpoint to initiate a transfer.

4 Mock the NotificationService and test the transfer functionality

5 The use of ReentrantLock ensures thread-safe operations. Only one thread can execute the critical section at a time.

6 for notification interface is implemented just for mock testing.

You can directly run the project by importing Exixting gradle and then run as spring boot application.

