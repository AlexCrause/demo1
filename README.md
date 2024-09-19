# demo1
demo1

  569  cd Spring\ Boot/
  570  ll
  571  cd demo1
  572  ll
  573  git status
  574  git log
  575  git status
  576  git add .
  577  git commit -m 'changed README.md'
  578  git log
  579  git status
  580  git add .
  581  git commit -m 'added test.txt'
  582  git log
  583  git add .
  584  git commit -m 'changed test.txt'
  585  git log
  586  git revert bd1d6d4ae95c918d5c2ac1ad23db09b68b7ef24a
  587  git log
  588  git revert 9cee4e557ae020615c97cabb708392be6a9840ad
  589  git log
  590  git revert 9da7de2d798cedce6cb3ecd2d122a8f29638b988
  591  git log
  592  git reset --soft 17601e60927f6dab7de26e15cf8e6e8778184798
  593  git status
  594  git log
  595  git reset --soft HEAD^
  596  git status
  597  git restore .
  598  git status
  599  git status
  600  git restore --staged README.md
  601  git status
  602  git restore README.md
  603  git status
  604  git log
  605  git reset --mixed HEAD^
  606  git status
  607  git restore test.txt
  608  git restore demo1/test.txt
  609  git status
  610  git log
  611  git reset --hard HEAD^
  612  git log
  613  git status
  614  git push -u origin/master
  615  git push -u origin master
  616  history
