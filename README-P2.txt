We'll have the project specification posted in about a day.  In the
meantime, you can start reading up on pairing heaps.

You're going to be implementing three different versions of a priority
queue:

0) Unordered (completed for you)
1) Sorted
2) Binary heap
3) Pairing heap

You ARE given templated starter files for these.  Start reading about
the Pairing heap, and if you want start thinking about implementation.
You will need to use the "left child, right sibling" approach, NOT a
vector or deque of child pointers.  Look at the UnorderedPQ.h and
UnorderedFastPQ.h for how to use this->compare().  Start working on
SortedPQ.h: if you're doing it correctly (using the STL instead of
writing loops), it can be completed in under 10 lines of code.

There are two versions of the starter files, to avoid CR/LF problems.
There's one named -Mac and one named -Windows.  If you're working just
on CAEN and/or Unix/Linux, use the -Mac version.