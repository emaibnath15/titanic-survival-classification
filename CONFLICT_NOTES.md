# Merge Conflict Notes

**File:** README.md
**Line:** Project description sentence under the title.

**main branch version:**
> "...survival on the Titanic, using a logistic regression model built with scikit-learn."

**proposal branch version:**
> "...survival on the Titanic, using a logistic regression classifier trained on Kaggle Titanic data."

**How it happened:** Both branches independently edited the same description sentence
after diverging from a common commit, so Git could not automatically pick one side.

**Resolution:** Manually combined both edits into one sentence that keeps the technique
(logistic regression) and the dataset context: "...using a logistic regression model
trained on the Kaggle Titanic dataset." Removed the `<<<<<<<`, `=======`, `>>>>>>>`
markers and committed the merged file.
