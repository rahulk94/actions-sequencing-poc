# Actions Sequencing POC

Testing one github action triggering another to defer starting a build until we've done a pre-requsite steps.

Also see https://github.com/thechetantalwar/demo-github-actions for a way to achieve a similar thing but in a single Github job. I imagine in this setup, if a job fails you'd just deal with that individually somehow and fail the whole workflow.
