# NFL Big Data Bowl 2023 2024

Historical research by Eric Matthew Rupinski. Reconstruction status: **partial; original empirical findings have not been re-estimated**. Original research history is preserved.

## Research question and value

How does defender proximity relate to a ball carrier? The current work is exploratory feature construction, not a validated tackle-probability system.

## Data and methodology

Original files remain the source of historical methodology. `data/requirements.json` inventories detected input filenames and packages; it is an incomplete static manifest, not a locked environment. Raw files are absent from this repository. Reacquire them through their original authorized sources; competition and third-party licenses must be checked before reuse.

## Audit and implemented changes

Exploratory notebook; 13 hard-coded paths; tackles are joined to player-frame rows; a geometric reach flag is not a calibrated tackle probability. Tracking rows are described as elapsed frames. Main feature construction uses Week 1.

Portable input directory and required-file preflight; corrected tracking-row/time interpretation; documents Week 1 scope and heuristic status.

## Findings and validation

No new empirical finding or revised performance score is asserted. Unit checks use small constructed inputs to verify the repaired mathematics and data contracts. Parsing verifies syntax only; it does not execute an analysis. Available original illustrations are historical outputs, not independently regenerated evidence.

## Reproduce the supported checks

R 4.5.2 was used for the base-R checks.

```sh
# Original notebooks need their source data and listed packages.
# No end-to-end reproduction is claimed.
```

The original dependency set is not fully available or version locked. Successful helper tests do not establish successful execution of the original model.

## Practical applications and limits

No probability model trained or evaluated. Per-play resampling, complete carrier coverage, row-grain joins and outcome timing still need validation on licensed source data.

## Next work

Recover input data with provenance and variable timing; declare the observational unit; isolate complete games/matches chronologically; fit transformations on training folds; compare against a simple baseline; regenerate figures and revise findings from held-out evidence. Retain old conclusions as historical until then.
