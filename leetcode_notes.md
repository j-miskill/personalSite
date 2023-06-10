# LeetCode Notes and Lessons

## Contains Duplicate

Need to see if we can loop through the list of numbers only one time. Maybe could do it in less time with some math and cutting the list in half.

Use a hashmap to contain whether we have already seen the number and then continue through the list. If seen, return true, if not add to the hashmap.

Return false at the end if the hashmap never returns True.
