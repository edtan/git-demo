# git-demo

## Cherry-picking vs. merging

This follows Raymond Chen's excellent [Stop cherry-picking, start
merging](https://devblogs.microsoft.com/oldnewthing/20180323-01/?p=98325)
blog post series.  Note that the links on those pages are outdated
(you'll need to replace the `blogs.msdn` prefix with `devblogs`), so
I've indexed them here:

[Part 1: The merge confict](https://devblogs.microsoft.com/oldnewthing/20180312-00/?p=98215)
[Part 2: The merge conflict that never happened (but should have)](https://devblogs.microsoft.com/oldnewthing/20180313-00/?p=98225)
[Part 3: Avoiding problems by creating a new merge base](https://devblogs.microsoft.com/oldnewthing/20180314-00/?p=98235)
[Part 4: Exploiting the recursive merge algorithm](https://devblogs.microsoft.com/oldnewthing/20180315-00/?p=98245)
[Part 5: Exploiting the three-way merge](https://devblogs.microsoft.com/oldnewthing/20180316-00/?p=98255)
[Part 6: Replacing the temporary fix with the permanent fix](https://devblogs.microsoft.com/oldnewthing/20180319-00/?p=98265)
[Part 7: Preventing a change from leaving a branch](https://devblogs.microsoft.com/oldnewthing/20180320-00/?p=98275)
[Part 8: How to merge a partial cherry-pick](https://devblogs.microsoft.com/oldnewthing/20180321-00/?p=98285)
[Part 9: Chasing the commit](https://devblogs.microsoft.com/oldnewthing/20180322-00/?p=98295)
[Part 10: Web-based workflow for VSTS](https://devblogs.microsoft.com/oldnewthing/20180323-00/?p=98315)
[Stop merging if you need to cherry-pick: A response from the VSTS team.](https://devblogs.microsoft.com/oldnewthing/20180709-00/?p=99195)

This repo will contain branches that follow each part, using the following naming convention:

```
cherry-[partN]-branchname

e.g. cherry-part1-master
```