
# HAVE A GOOD WORKING VERSION

I finally have a pretty nice working version of the representing art app! The issue with the code I had been working on for the last few weeks was ensuring that the modal appears in the correct spot. The issue is that state does not update immediately and I do not have a firm understanding of react hooks. I also found that with components like the react bootstrap modal, poppers, toggles, and overlays the state would really not update. I created my own 'modal' and was able to successfully absolutely position the modal where I wanted. When I tried to add a holding div with absolute position so that the background could be clicked to dismiss the window. However when I did that the state I passed as props did not work. I would love to investigate this further later. 


> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbNTA4Njc0MjI3LDE4NTcxNjk3ODUsMTE0MD
QzMjMwMV19
-->