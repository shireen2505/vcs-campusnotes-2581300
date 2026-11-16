# vcs-campusnotes-2581300

**CampusNotes** – a simple set of text files for keeping track of subjects, the weekly timetable, study goals and study progress.
Made for the Version Control System (CSE25303) course, Assignment 2.

## Files
| File | What it contains |
|------|------------------|
| `subjects.txt` | List of subjects this semester |
| `timetable.txt` | Weekly timetable (day – subject) |
| `goals.txt` | Study goals to complete |
| `study-tracker.txt` | Progress on each subject/task |

## Branches
- `main` – stable version of the notes
- `feature-study` – work on the study tracker

## How to use
1. Clone the repository:
   ```bash
   git clone https://github.com/shireen2505/vcs-campusnotes-2581300.git
   ```
2. Open any `.txt` file and add a new line for each subject, class or goal.
   Keep the same format as the existing lines, for example in `timetable.txt`:
   ```
   Tuesday - Version Control System
   ```
3. Save the file, then commit and push the change:
   ```bash
   git status                      # see which files changed
   git add timetable.txt           # stage the file you edited
   git commit -m "docs: add Tuesday to timetable"
   git push                        # send the commit to GitHub
   ```
4. Get the latest changes from GitHub before you start working next time:
   ```bash
   git pull
   ```

## Contributing
Fork the repository, create a branch named `feature/<your-name>-<change>`, make your change and open a pull request against `main`.

## Git history notes
Earlier exercises in this repository covered tracking multiple files, merging a feature branch, and the remote clone → push → pull workflow.
