# database
**Multi-threaded Network:** The project has a multi-threaded network that is designed to terminate cleanly upon exit, ensuring graceful shutdown and minimization of potential data loss or corruption.

**Fine Grain Locks:** The functions in the database are implemented with fine-grain locks. These locks prevent race conditions and ensure data consistency, even when accessed by multiple threads simultaneously.

**Read-Eval-Print-Loop (REPL) Stop & Go Function:** This function provides control over database operations. With the capability of stopping, waiting, and releasing functions, it enhances the handling of database operations and ensures smooth execution.

**EOF Handling:** The project handles EOF (End of File) efficiently, making sure that the list is empty, all allocated memory is freed, and the database is cleaned up. This feature ensures that there are no orphan clients or potential memory leaks in the system.
