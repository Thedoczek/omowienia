1. Pick random tile
2. Highlight available spots:
   - Compare four following points to their neighbors on neighboring tiles:

         ..X..
         .....
         X...X
         .....
         ..X..
         
    - If neighbors are not empty AND not the same, don't highlight (and not clickable)
3. After placing, pick spots (hardcoded for each tile) where player can place their pawn and check if the city/road/field is not taken by other player. If the're not, highlight road/city/field.
4. (optional) After selecting where to place pawn, take it's area.
   - 0, 6, c, i : city/road/field taken by 1st player
   - 
