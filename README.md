" first" 
C:\Users\Chris>md git

C:\Users\Chris>cd git

C:\Users\Chris\git>dir
 Volume in drive C has no label.
 Volume Serial Number is 3CD8-024F

 Directory of C:\Users\Chris\git

04/03/2016  14:16    <DIR>          .
04/03/2016  14:16    <DIR>          ..
               0 File(s)              0 bytes
               2 Dir(s)  169,943,117,824 bytes free

C:\Users\Chris\git>echo " first" >> README.md

C:\Users\Chris\git>
C:\Users\Chris\git>git init
Initialized empty Git repository in C:/Users/Chris/git/.git/

C:\Users\Chris\git>git add README.md

C:\Users\Chris\git>git commit -m "first commit"
[master (root-commit) 455b37d] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

C:\Users\Chris\git>git remote add origin https://github.com/cchb/first.git

C:\Users\Chris\git>git push -u origin master
Username for 'https://github.com': cchb
Password for 'https://cchb@github.com':
Counting objects: 3, done.
Writing objects: 100% (3/3), 223 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/cchb/first.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.
