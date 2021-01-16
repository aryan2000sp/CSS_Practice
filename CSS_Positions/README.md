# Positions In CSS
---

By default every element in html page is positioned static. The static position flows the html document flow. We change the positions of the elements using the positions property of css. There are two important CSS positions types which are relative and absolute.

* __Relative:-__ This positions the elements in static maner but can be moved left, right, top and bottom to their relative static positions. The word relative means relative positions relative to their static positions.

* __Absolute:-__ This positions elements in relative maner and can be moved left, right, top and bottom. It basically removes the elements from the html document and places it in positions defined by left, right, top and bottom. Thus we can move elements without affecting other elements positions. This might result in the elements being overlapped.
---

### Examples

The example in this folder demonstrates the use of positioning of elements. If the One_Div is set position to relative and then moved to left or right by some pixels then it moves to left or right relative to its original static positions.
When set positions to absolute for One_Div and then move the element to left or right it will it basically remove the element from the document flow and add its absolute positions defined by left or right. ___[Click](https://www.youtube.com/watch?v=jx5jmI0UlXU)___ Here To learn more about positions. 

---
### When to use which positions type?

* __Relative:-__  We use positions relative when we want to fix the positions of the elements. Also this sets the positions of children elements inside of the parent elements relative to their parent elements positions. This way we don't have to worry about the positions of the children elements since they will be positioned relative to their parents positions.

* __Absolute:-__ We use positions absolute we want place a element at an exact positions without affecting the other element's positions. This may result in overlapping since absolute positions removes the element from the html document flow and places it at a position defined by left, right, top or bottom.

---

### Conclusion
In conclusion it always a best practice to use position relative for the parent elements and absolute positions for children elements.

---
### Reference
* ___[Youtube Video](https://www.youtube.com/watch?v=jx5jmI0UlXU)___
* ___[CSS-Tricks wesite](https://css-tricks.com/absolute-positioning-inside-relative-positioning/)___