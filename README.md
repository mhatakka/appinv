# appinv
MIT App Inventor Projects


Branches Handling Git

There was two branches 'main' and 'master'. 'Main' was Default.
Files went to although to 'master' branch, and 'main' was empty.
Hoe to fix?

1. Create a local 'main'
   git branch -m master main
   git push -u origin main
   git push origin --delete master
