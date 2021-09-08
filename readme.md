Files in this repo are shared across all repos in the organization. All these files can be overwritten on a repo by repo basis. Organization-wide workflows will not work, see this note from GitHub:

> **Note:** Workflow templates can be used to create new workflows in an organization' s public repository; to use templates to create workflows in private repositories, the organization must be part of an enterprise plan.)

So the next best step is to copy the workflows and related `.yml` configurations into the `.github` folder at the root of each target repository. At the time of this writing, that would just be the `workflows` folder and its contents (`release-drafter.yml`) and the other `release-drafter.yml` file.
