# JPMC Task 1
Starter repo for task 1 of the JPMC software engineering program

# Get total number of previous commits:
git shortlog -sn --all

# Generate patch file:
- git format-patch -n –stdout > multi_commit.patch

note: the n in -n must be replaced with a number which represents the number of commits you made for the
task. So the real command if you made 4 commits on top of the old commits should be