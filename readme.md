Coding Dojo coding assignment Repo
cd DojoAssignments

 mkdir GitHubRepoAssignment

 cd GitHubRepoAssignment

  >git init
Initialized empty Git repository in C:/Users/raiff/Desktop/DojoAssignments/GitHubRepoAssignment/.git/

  >copy NUL readme.md
        1 file(s) copied.

  >git status
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        readme.md

nothing added to commit but untracked files present (use "git add" to track)

  >git add .

  >git commit -m "Updated readme.md"
[master (root-commit) 2fb0e5e] Updated readme.md
 1 file changed, 1 insertion(+)
 create mode 100644 readme.md

  >git remote add origin https://github.com/Lacan82/GitHubRepoAssignment.git

  >git push -u origin master
Counting objects: 3, done.
Writing objects: 100% (3/3), 248 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/Lacan82/GitHubRepoAssignment.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.

  >