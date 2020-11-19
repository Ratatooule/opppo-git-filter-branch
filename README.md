Старцев Алексей Андреевич

git filter-branch --tree-filter 'rm -rf objects’ HEAD
result: Rewrite 3a6f9b7bb36ed409be173fa6b9f4a6dea01953a8

git reflog expire --expire=now --all

git gc --prune=now --aggressive
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), done.
Total 3 (delta 0), reused 3 (delta 0), pack-reused 0