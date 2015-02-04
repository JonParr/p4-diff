# p4-diff
Tool to generate a Perforce unified-diff from open or shelved changelists supporting add, edited and deleted files.

See help via <i>p4-diff --help</i>.

### Diff from default changelist using opened files
<code>p4-diff -c default</code> > default.diff

### Diff from specific changelist using the shelved files
<code>p4-diff -c 123456 -s</code> > shelved_123456.diff

### Diff from specific changelist using opened files
<code>p4-diff -c 123456</code> > opened_123456.diff

<code>
cd ~/other_source
patch --dry-run -Np6 -i opened_123456.diff 
</code>
