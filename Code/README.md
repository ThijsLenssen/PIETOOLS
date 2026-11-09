# Robust control and duality extensions

This directory contains the robust control and duality source code and examples.
The upstream PIETOOLS toolbox is preserved in `../PIETOOLS`.

Add PIETOOLS and this directory to the MATLAB path from the repository root:

```matlab
addpath(genpath('PIETOOLS'));
addpath(genpath('Code'));
```

Use the required SDP solver and review the individual example scripts and READMEs
for their settings and dependencies. Some scripts reference local installation or
manuscript paths that need to be adjusted for another machine.

Generated simulation MAT files, solver certificates and diagnostics, saved
workspaces, exported figures and videos, CSV summaries, editor backups and logs
are intentionally excluded from this branch. Run the relevant synthesis and
simulation scripts before using plotting helpers that load those results. The
Example 6 README and the STN-GPe example documentation describe the workflows.

The MATLAB source files, Markdown documentation, LaTeX sources and the small
Kao-Rantzer reference PDF are retained. `.gitignore` keeps generated outputs out
of future commits. Existing local outputs in the original checkout are preserved.
