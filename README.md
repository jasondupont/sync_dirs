sync_dirs
=========

Sync multiple directories across a network

This project was developed to sync from one "master" directory to any other directory.  In order to maximize performance the project utilizes multiple threads.  Each thread performs 1 directory sync, then reports back to the main thread with the results.

After all threads are complete, the sync is done and the user is notified of results.
