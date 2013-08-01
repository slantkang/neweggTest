$ vim lib/cat.rb
$ git status
# On branch cat
# Untracked files:
#   (use "git add ..." to include in what will be committed)
#
#   lib/cat.rb
nothing added to commit but untracked files present (use "git add" to track)
$ git add lib/cat.rb
$ git commit -m "Add Cat.rb"
[cat ea7d309] Add Cat.rb
 1 files changed, 3 insertions(+), 0 deletions(-)
 create mode 100644 lib/cat.rb