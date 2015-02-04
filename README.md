# p4-diff
Tool to generate a Perforce unified-diff from open or shelved changelists supporting add, edited and deleted files.

See help via p4-diff --help.

# Diff from default changelist using opened files
p4-diff -c default

# Diff from specific changelist using the shelved files
p4-diff -c 123456 -s

# Diff from specific changelist using opened files
p4-diff -c 123456
