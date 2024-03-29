# This is info about Git vs Github

GIT is a Distributed Version Control system which allows clients to create mirrored repositories. These data backups can be easily be placed on the server to replace any lost information. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it. Git mostly relies on local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk, eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN. Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit. Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to being lost. Files in Git can reside in three main states: committed, modified and staged. Data is securely stored in a local database. The file has been changed but not committed to the database.In order to start using GIT, we need to set it up. I would like to focus on the Linux set up since that's is the one I used.

In order to start using GIT we need to set it up. I would like to focus on the Linux set up since thats is the one I used.

`$ sudo yum install git`

Then we will establish nessesary settings:

`git config --global user.name "Jane Smith"
git config --global user.email "example@email.com"`

Then we Will run command to verify all the settings:

`git config --list`

And we could always use some help:

`git help command`

That's it for now.

