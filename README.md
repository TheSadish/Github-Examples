# Github-Examples
A repo containing GitHub for programmatic examples

$GITHUB_ENV - A file that contains environment variables to be set in the current step and future steps in a job during the time of a workflow run.

env.My_Val -> This can be use to call the variable in a different step in the same job.

env:
    My_Val: Hello World

there are certain scopes where you can declare environment variables.
1. Workflow - This is the highest scope and can be used across all jobs and steps in the workflow.
2. Job - This scope is limited to the job in which it is defined and can be used across all steps within that job.
3. Step - This scope is limited to the step in which it is defined and cannot be used in other steps or jobs.