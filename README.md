# hello-world

Git:
Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

Git is easy to learn and has a tiny footprint with lightning fast performance. It outclasses SCM tools like Subversion, CVS, Perforce, and ClearCase with features like cheap local branching, convenient staging areas, and multiple workflows.


Git Commits

A commit in a git repository records a snapshot of all the files in your directory. It's like a giant copy and paste, but even better!

Git wants to keep commits as lightweight as possible though, so it doesn't just blindly copy the entire directory every time you commit. It can (when possible) compress a commit as a set of changes, or a "delta", from one version of the repository to the next.

Git also maintains a history of which commits were made when. That's why most commits have ancestor commits above them -- we designate this with arrows in our visualization. Maintaining history is great for everyone working on the project!


Git Branches and Checkout

Branches in Git are incredibly lightweight as well. They are simply pointers to a specific commit -- nothing more.

 git checkout <name>     This will put us on the new branch before committing our changes
 
if you want to create a new branch AND check it out at the same time, you can simply type 
 
 git checkout -b [yourbranchname]