# Power BI PBIP Source Control Runbook

## Objective

This runbook explains how to export, commit, retrieve, and restore Power BI PBIP artifacts using GitHub.

## Export PBIP

1. Open report in Power BI Desktop.
2. Select File > Save As.
3. Choose Power BI Project (.pbip).
4. Save to repository folder.

## Commit Changes

```bash
git status
git add .
git commit -m "Initial PBIP export for pilot report and semantic model"
git push