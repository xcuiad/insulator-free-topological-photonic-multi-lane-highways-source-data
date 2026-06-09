# Upload Checklist

Use this list right before creating the GitHub repository or pushing a final release.

## Before Upload

- Confirm that only the `.xlsx` source data are meant to be public.
- Keep all Mathematica notebooks (`*.nb`) out of the upload.
- Verify that the folder names still match the figure structure in the paper.
- Check that there are no stray temporary files such as `.DS_Store`, `~$*.xlsx`, or backup copies.
- Make sure the spreadsheet filenames are stable and descriptive enough for long-term reuse.

## Git Check

- Run `git status` and confirm that only the intended data files and text files are tracked.
- Confirm that `.nb` files are ignored.
- Review the staged files once before publishing.

## GitHub Check

- Create the GitHub repository with a clear name, such as `insulator-free-topological-photonic-multi-lane-highways-source-data`.
- Push the `main` branch.
- Add a short repository description that says these are the source data for the Nature paper.
- Add the paper DOI or manuscript link once it is available.

## Optional Good Practice

- Add a Zenodo release if you want a DOI for the dataset.
- Replace the placeholder author information in `CITATION.cff`.
- Replace the placeholder repository URL in `CITATION.cff` after the GitHub repo is created.
