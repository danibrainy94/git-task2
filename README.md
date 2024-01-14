# git-task2

1. Explain version control

    **Version control** systems are a special type of software development tool designed to help software developers keep track of any changes made on the source code of any specific application. 
    Version control, also known as source control or revision control, is a system that tracks and manages changes to files over time. It is a crucial tool in software development and other collaborative projects where multiple contributors work on the same set of files. The primary objectives of version control are to facilitate collaboration, track changes, and provide a history of revisions.
------------------------------------------------------------------------------------------------------------------

2. Explain difference between git and github

    At its essence, **Git** serves as a *distributed version control system (DVCS)* designed for the management of source code history within the realm of free and open-source software. Its primary functions include facilitating code sharing, monitoring commits, and enabling the reversal of changes. Collaboration requires individual developers to have **Git** installed on their respective local devices. In simple terms, git is a command line tool.

    Conversely, GitHub functions as a web-based platform dedicated to hosting Git repositories. Beyond offering the core capabilities of **Git's** *distributed version control system (DVCS)* source code management, **GitHub** incorporates supplementary features for collaborative work, encompassing project and ticket management for support, as well as bug tracking. Developers leverage GitHub not only to share their repositories but also to access those of their peers, while also maintaining remote backups of repositories. **Github** is more of a graphical user interface that offers Git as a service.
-----------------------------------------------------------------------------------------------------------------

3. List 3 other github alternatives.
    i. Gitea
    ii. Bitbucket
    iii. Gitlab
-----------------------------------------------------------------------------------------------------------------

4. Explain the difference between git fetch and git pull.

    The **git fetch** command retrieves the most recent updates from the remote repository and stores them in your local repository. It doesn't automatically integrate these changes into your current branch. If your intention is to acquire the latest changes from the remote repository without immediately merging them into your existing branch, opting for git fetch is the appropriate choice. This proves beneficial when you wish to inspect the changes separately before deciding to merge them into your work.

    While the **git pull** command serves as a shortcut for git fetch followed by git merge. It fetches the most recent updates from the remote repository, bringing them into your local repository, and seamlessly incorporates them into your present branch. This command is frequently employed to ensure synchronization between your local repository and the remote counterpart, making it a common choice for keeping your codebase up to date.
------------------------------------------------------------------------------------------------------------------

5. Explain in simple terms git rebase and the command for it.

    **Git rebase** is a command that allows you to change the way your commit history looks. It's like rewriting the story of your project to make it more organized and clean.
    The basic idea behind **git rebase** is to take all the changes you made in one branch and apply them on top of another branch. This can help create a linear, easy-to-follow history.

    The syntax for git rebase is in the form: `git rebase main`
------------------------------------------------------------------------------------------------------------------

6. Explain in simple terms git cherry-pick and the command for it.

    In Git, **cherry-picking** refers to selecting a specific commit from one branch and applying it to another branch. This stands apart from alternative methods like merging and rebasing, which typically involve incorporating multiple commits into another branch.
    Git **cherry-pick**, akin to rebasing, represents an advanced concept and features a potent command. Its primary utility arises when there's a desire to avoid merging an entire branch, instead opting to pick and apply specific commits that are of interest.

    The syntax for git cherry-pick is in the form: `git cherry-pick<commit-hash>`
------------------------------------------------------------------------------------------------------------------









