# 00-test

Java programming exercises for this topic. Each exercise is worth a
different number of points — see `points.json` for the exact breakdown.

## The exercises

| Exercise | File | Points |
|---|---|---|
| 1 | `src/main/java/exercises/Exercise1.java` | 2 |
| 2 | `src/main/java/exercises/Exercise2.java` | 3 |

Each has a `TODO` method to implement, and a matching test file
(`Exercise1Test.java`, `Exercise2Test.java`) that checks it. **Don't edit
the test files or `points.json`** — grading always uses the original,
unmodified versions, so local edits there won't help.

You get partial credit within an exercise: if an exercise has 2 tests and
you pass 1 of them, you earn half that exercise's points (rounded to the
nearest whole point).

## Step by step

1. **Clone this repo**:
   ```
   git clone <this repo's URL>
   cd <the folder that creates>
   ```
2. **Open it in VS Code**: `code .` (or File → Open Folder). If prompted
   "This workspace has extension recommendations", click **Install** — this
   adds a flask-shaped **Testing** icon to the left sidebar.
3. **Run the tests before changing anything.** Click the flask icon, then
   the play button at the top of the Test Explorer panel. All tests should
   show a red X — expected, since nothing is implemented yet.
4. **Implement each exercise** in its `ExerciseN.java` file, one at a time.
5. **Re-run the tests** the same way after each change. Prefer a terminal?
   `mvn test` does the same check for all exercises at once.
6. **Submit**:
   ```
   git add -A
   git commit -m "Implement exercises"
   git push
   ```
7. Check the **Actions** tab on this repo's GitHub page — a run appears
   within a few seconds and shows a per-exercise points breakdown matching
   what you saw locally in step 5.

## Important

- Keep pushes to a minimum once tests pass locally — each push uses the
  course organization's shared (limited) GitHub Actions minutes. Iterate
  locally first.
- The score shown after a push is **practice feedback only**, not your
  recorded grade. Your teacher computes the official grade separately,
  after the deadline, using the original test files, `points.json`, and
  build configuration regardless of what ends up in this repository —
  editing `pom.xml`, the tests, `points.json`, or `.github/workflows` will
  not change your grade.
