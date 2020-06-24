# What is Git 
## Some important terminology at the end of each paragraph below.

**Git** is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it - **SNAPSHOTS**

Git mostly relies on local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk, eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN. **LOCAL OPERATIONS**

Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit. **TRACKING CHANGES**

Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost. **LOSS OF DATA**

Files in Git can reside in three main states: committed, modified and staged.  **STATES**

Data is securely stored in a local database. **COMMITTED**

File has been changed but not committed to the database. **MODIFIED**