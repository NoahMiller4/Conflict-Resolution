# Conflict-Resolution

Basic merge conflicts on GitHub

    01. Create a file(on main branch) and add content to it and push it to GH
    02. Create and open a new branch (new-feature) git switch -c <branch>
    03. Change the content of the file and commit your changes
    04. On GH, change the file in the 'main' branch
    05. Go to 'main' (locally) and pull the recent updates
    06. Keep working on new-feature, commit and push your changes
    07. On GH, do a pull request for new-feature
    08. On terminal, go to new-feature and merge main
    09. Fix the conflicts, stage and commit your changes
    10. Go back to GH, and do a pull request again
    11. Back to main(locally), pull the recent updates from main (remote)
    12. Delete new-feature | git branch -D <branch>
    13. Smile, you fixed a conflict
