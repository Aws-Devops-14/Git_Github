# Git_Github
Git--> It is a Version Control System
  It helps you track changes in your code, save versions, and go back to old versions if needed.
  Allows for Collabrative development.
  A system that keep records of your changes
  Allows you to know who made changes and when
  Track file changes
  Revert to previous versions
  Work on new features without breaking main code (branching)
  Merge work from multiple developers

Github--> GitHub is a cloud platform to store Git repositories online.
      --> GitHub is a Centrally configured storage where we can maintain our source code
  Website to store & share your Git projects
  Remote storage for code
  Collaboration tools (for teams)
  Pull Requests + Reviews
  Issue tracking
  CI/CD (GitHub Actions)

Git	                                 GitHub
Version control tool	             Hosting service for Git repositories
Works offline	                     Works online
Command line tool	                 Website/platform
Created by Linus                   Torvalds	Owned by Microsoft

1.Local Version Control System:-
      Tracks file changes on a single system only.
      Only one developer works locally
      No collaboration features
      Example:
       RCS (Revision Control System)
       Simple idea: Store old versions on your own computer.

2.Centralized Version Control System:-
      There is one central server where all code is stored and developers commit code to it.
      Everyone works from a central repository
      Server failure can cause data loss
      Requires internet/network connection
      Examples:
       SVN (Subversion)
       CVS (Concurrent Versions System)
       Perforce
       Simple idea: One main storage — everyone connects to it.

3. Distributed Version Control System (DVCS)
   Each developer has a full copy of the repository (including history).
   Works even without internet
   Faster & more secure
   Best for team collaboration
  Examples:
   Git
   Mercurial
   Bazaar
   Simple idea: Every developer has the full project copy locally.

   ---->SSH is a Secure way to connect your local computer to GitHub without entering username and password every time.
     ---->ssh -keygen
     ---->create keys---->upload public key in Github---->Githb Verifies---->password never neded

---> fork is used to pull others repository to our repository between Github-------------------------Github
                                                                                    fork the repo
---> clone is a pull repository from Github to local repository like Github---------------------------Local Repository
                                                                                      clone


