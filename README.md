# commit-sudoku

<!-- space reserved to line up cells with line numbers -->

<table>
  <tr>            <!-- Row 1 -->
    <td>
    <td>1
    <td>
    <td>
    <td>
    <td>9
    <td>
    <td>7
    <td>4
  <tr>            <!-- Row 2 -->
    <td>7
    <td>
    <td>
    <td>
    <td>3
    <td>
    <td>
    <td>
    <td>
  <tr>            <!-- Row 3 -->
    <td>
    <td>4
    <td>
    <td>7
    <td>2
    <td>
    <td>3
    <td>
    <td>1
  <tr>            <!-- Row 4 -->
    <td>
    <td>
    <td>
    <td>
    <td>
    <td>
    <td>
    <td>
    <td>9
  <tr>            <!-- Row 5 -->
    <td>
    <td>6
    <td>7
    <td>
    <td>
    <td>
    <td>2
    <td>1
    <td>
  <tr>            <!-- Row 6 -->
    <td>5
    <td>
    <td>
    <td>
    <td>
    <td>
    <td>
    <td>
    <td>
  <tr>            <!-- Row 7 -->
    <td>4
    <td>
    <td>2
    <td>
    <td>7
    <td>1
    <td>
    <td>6
    <td>
  <tr>            <!-- Row 8 -->
    <td>
    <td>
    <td>
    <td>
    <td>4
    <td>
    <td>
    <td>
    <td>3
  <tr>            <!-- Row 9 -->
    <td>3
    <td>5
    <td>
    <td>6
    <td>
    <td>
    <td>
    <td>2
    <td>
</table>




## Rules

There are two types of pull requests, moves and others.

A move must only include filling in one number in one cell in the puzzle.

* A player can only make at most one move a day.
* A player can remove any moves made by himself or herself without the above limitation.
* Moves are accepted in order of first submission.
* Conflicting moves are skipped, they can be resubmitted ASAP once fixed.
* Multiple players can submit a single joint pull requests consistent of many moves, one from each player.

All other pull requests should improve the project in some way. Explained with what changes are made, and how it makes the project better.

* Other pull requests must not include move commits. They should also preserve git blame for moves as best as possible.
* Acceptance does not follow the rule of moves.
* They can be anything else typical of any project.
* They can even change the rules, but not apply retroactively.
