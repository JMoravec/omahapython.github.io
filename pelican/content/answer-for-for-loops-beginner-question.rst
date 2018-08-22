Answer for for loops - beginner question
########################################
:date: 2017-02-20 15:28
:slug: answer-for-for-loops-beginner-question
:status: published

So 'a' is essentially a temporary variable that is updated while walking
the list.

| for a in g:
|    print a

| would output
| 1
| 1
| 2
| 3
| 3
| etc

| So, keeping that in mind, if a conditional check to see what "a"
  currently is assigned
| exists in the "x" list.  And as written, appends to the list if it is
  not seen in "x"

| Hope that helps
| Chad
