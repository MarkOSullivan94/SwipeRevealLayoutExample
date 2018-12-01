I have added Swipe lock enable disable feature for particular list item programmatically.

Added a new method DragLock() in SwipeRevealLayout class.

We can enable disable Swipe by calling above methods like this from adapter class.

viewHolder.mSwipeRevealLayout.dragLock(false); or  viewHolder.mSwipeRevealLayout.dragLock(true);





