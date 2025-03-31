# Forks

Workflows by default will not run when Pull Request is created from a fork by unknown user (not collaborator). Such workflows require approve (warning icon in actions). This enhances a security and cost reduction (paid GitHub repository), so only people that we trust can run workflows.

# Skipping workflow run

Such commit message will not run workflows.

`git commit -m "added comments [skip ci]"`

More details [here](https://docs.github.com/en/actions/managing-workflow-runs-and-deployments/managing-workflow-runs/skipping-workflow-runs)

# Output vs Artifact

Output is just a value like filename, artifact is a zip file containing an actual files.
