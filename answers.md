*Section 1 - TestIterator*

1. The tests pass regardless as to whether or not a LinkedList was used, although it does take a bit longer to run with the LinkedList.
2. An error happens when list.remove(77) is used. It searches for the value on index 77, but there's only 6 possible indexes in this list.

*Section 2 - TestList*

1. Once again, it doesn't matter if LinkedList is used, because it passes anyways.
2. The method, list.remove(5) will remove whatever value is held at index 5.
3. The method list.remove(integer.valueOf(5)), will take the number, 5, out of the list.

*Section 3 - TestPerformance*

1. The LinkedList will usually take longer to complete as the size completes.
