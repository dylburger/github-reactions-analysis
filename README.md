## About

This Jupyter notebook shows some example analyses of Github reactions data. You can read more about how to generate the source CSV from this Medium post, and in this [Pipedream workflow](https://pipedream.com/@dylburger/send-issue-reactions-for-a-repo-to-a-google-sheet-p_NMCar1/readme).

## Quickstart

First, [install `pipenv`](https://github.com/pypa/pipenv).

Then, in this repo, run

```bash
pipenv install
```

to install the requisite Python version and all the dependencies necessary to run this Jupyter notebook.

Once done, run

```bash
pipenv shell
jupyter notebook
```

The Jupyter UI should load in your default browser, and you can start running / editing the notebook.

## Sample data

The CSV in `data/roadmap.csv` was generated on `2019-11-26`, and provides a sample of data you can use to see how the Jupyter notebook works.

Run the [Pipedream workflow](https://pipedream.com/@dylburger/send-issue-reactions-for-a-repo-to-a-google-sheet-p_NMCar1/readme) to save issue reactions for your own repo, which writes them to a Googles spreadsheet, where you can download a CSV of the results.
