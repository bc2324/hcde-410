## What I Did

I started by cleaning and combining the worker demographic datasets and checking for duplicate IDs. Then, I analyzed the workers' demographics, including gender, age, education, and first language. I also looked at missing data and how duplicates could affect the results. Finally, I explored how these differences might introduce bias into the dataset and affect how Perspective API identifies toxic comments.

## Files

- `hcde410-a2.ipynb` – My code, analysis, and answers.
- `a2_all_annotator_demographics.csv` – Cleaned demographic dataset.
- `LICENSE.md` – License information.

## Data Source

[Wikipedia Talk Labels: Toxicity](https://doi.org/10.6084/m9.figshare.4563973)

## Tools

Python, pandas, and Jupyter Notebook.

## Takeaways

One thing I found interesting was how differently the workers were represented across demographic groups. This made me realize that even when a dataset looks objective, the people labeling it can influence the results. I think this is especially important for tools like Perspective API, since people from different backgrounds might interpret the same comment differently.