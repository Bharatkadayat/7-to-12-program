# 7-to-12-program
7
$ git tag v1.0 
$ git tag v1.0 <commit-SHA>
8
$ git cherry-pick <start-commit>^..<end-commit> 
$ git cherry-pick ABC123^..DEF456 
9
 $  git show <commit-ID> 
 $ git show abc123 
 $ git log -n 1 <commit-ID>
 $ git log -n 1 abc123

 10
 $ git log --author="JohnDoe" --since="2024-01-01" --until="2024-12-31"
 11
 $ git log -n 5 
 $ git revert abc123 
