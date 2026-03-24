# Contributing to LiteraryLens

Thank you for your interest in contributing to LiteraryLens.
This document explains how to contribute and the terms under
which contributions are accepted.

---

## Contributor License Agreement (CLA)

**By submitting a pull request, opening an issue with attached
code, or otherwise contributing code or documentation to this
repository, you agree to the following terms:**

1. **Copyright assignment.** You assign to Svenja Guhr
   all right, title, and interest — including all copyright —
   in and to your contribution, worldwide and in perpetuity.
   This allows the project owner to relicense, sublicense,
   or commercialise the project (including your contribution)
   without further permission from you.

2. **You retain personal use rights.** The assignment above
   does not prevent you from using your own contribution
   for your own purposes under the Apache 2.0 license.

3. **Originality.** You confirm that your contribution is
   your own original work and that you have the right to
   make this assignment. If your contribution includes or
   is based on third-party work, you identify it clearly
   in your pull request.

4. **No obligation.** The project owner is under no obligation
   to accept, merge, or use any contribution.

If you are contributing on behalf of an employer or institution,
you confirm that you have the authority to make this assignment
on their behalf, or that your employer has waived any rights
to the contribution in writing.

> If you cannot agree to these terms, please do not submit
> a pull request. You are still welcome to fork the repository
> under the terms of the Apache 2.0 license.

---

## What you can contribute

- Bug fixes and improvements to `index.html` (the reader UI)
- Improvements to `literary_classifier.py` (the Python backend)
- Documentation, README improvements, usage examples
- Translations of the UI into other languages
- Accessibility improvements

**Please do not submit:**
- Training data, labelled datasets, or annotation files
- Fine-tuned model weights or checkpoints
- Any third-party copyrighted text used as examples

---

## How to contribute

1. **Fork** the repository and create a new branch from `main`:
   ```
   git checkout -b fix/your-description
   ```

2. **Make your changes.** Keep commits focused — one logical
   change per pull request makes review much easier.

3. **Test your changes** in at least one desktop browser
   and one mobile browser before submitting.

4. **Open a pull request** against the `main` branch.
   In the PR description, briefly explain what you changed
   and why, and confirm that you agree to the CLA above
   by including this line:
   > I have read CONTRIBUTING.md and agree to the CLA.

---

## Code style

- HTML/CSS/JS: keep the existing formatting conventions
  (2-space indentation, single quotes in JS, CSS variables
  for all colours and spacing)
- Python: follow PEP 8; add a docstring to any new function
- Keep comments in English

---

## Questions

For questions about contributing or licensing, contact:
svenja.guhr@gmail.com
