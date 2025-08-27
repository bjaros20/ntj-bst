# ntj-bst

This is a BibTeX style file (`.bst`) for the  
**National Tax Journal (NTJ)**. As far as I can tell, no official `.bst` file  
exists for NTJ, so this is my attempt to fill that gap.  It is a work-in-progress, so feel 
free to suggest changes, branch, etc.

Here is style guideline I created it from: https://ntanet.org/wp-content/uploads/2019/11/1.-NTJ-Style-Guidelines-11-01-19.pdf

---

## Background

The [National Tax Journal (NTJ)](https://ntanet.org/publications/ntj/)  
is an establishment journal focused on tax and public finance research.  
It’s published by the National Tax Association and distributed by the University of Chicago Press.  

---

## Files

- `ntj.bst` — the style file (generated with `docstrip`, based on Patrick W. Daly’s `merlin.mbs` sources).
- `example/` — minimal LaTeX + BibTeX example (to be expanded).
- `LICENSE` — licensing info (LPPL + note on this repo).

---

## Usage

Copy `ntj.bst` into your project folder, then in your `.tex` file:

```latex
\bibliographystyle{ntj}
\bibliography{references}
