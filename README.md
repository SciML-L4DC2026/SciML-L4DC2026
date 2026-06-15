# L4DC SciML Tutorial

Website and hands-on materials for the L4DC tutorial **Scientific Machine Learning for Modeling, Optimization, and Control**.

## Repository structure

```text
.
├── index.html
├── assets/
│   ├── css/
│   ├── images/
│   └── js/
├── slides/
├── notebooks/
├── code/
├── requirements.txt
└── README.md
```

## Local preview

Because this is a static website, you can preview it directly by opening `index.html`, or run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/root` folder.
5. Update the GitHub repo links in `index.html`.

## Updating materials

Add PDFs to:

```text
slides/
```

Add notebooks to:

```text
notebooks/
```

Then edit links in `index.html`.

## Colab links

For notebooks stored in this repository, use:

```text
https://colab.research.google.com/github/YOUR-ORG/L4DC-SciML-Tutorial/blob/main/notebooks/YOUR_NOTEBOOK.ipynb
```

## Tutorial agenda

- Introduction: Scientific Machine Learning for modeling, optimization, and control.
- Learning to Model via constrained system identification.
- Learning to Optimize for constrained optimization.
- Learning to Control via Differentiable Predictive Control.
