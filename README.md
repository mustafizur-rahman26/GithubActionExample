## What is GitHub Actions?
Enables you to create custom software development life cycle (SDLC) workflows directly in our GitHub repository.

- Fully integrated into Github. (Doesn’t require any external site)
- Provides multiple templates for CI and one can create own custom action and publish on the [Marketplace](https://github.com/marketplace?type=actions).
- Completely free for every open-source repository and include 2000 free build minutes per month for all private repositories.

## Common jargon

#### Workflow 
     A configurable automated process to build, test, release, or deploy any project on GitHub. 
#### Runner
     Any machine with the GitHub Actions runner application installed. 
#### Action
     Individual tasks that you combine as steps to create a job.
#### Job
     A set of steps that execute on the same runner. 
#### Step
     A step is an individual task that can run commands or actions.
     
![](./screenshots/github_workflow_example.png)

## Creating a workflow file
1. At the root of your repository, create a directory named ` .github/workflows ` to store your workflow files.
2. In ` .github/workflows `, add a `.yml ` or `.yaml ` file for your workflow.
3. Use the "Workflow syntax for GitHub Actions" reference documentation to choose events to trigger an action, add actions, and customize your workflow.

![](./screenshots/create_workflow_file.png)

![](./screenshots/workflow_project_structure.png)

## Workflow file example

![](./screenshots/workflow_example.png)

## Triggering a workflow with events
Trigger workflow or every push:

![](./screenshots/trigger_workflow_push.png)
![](./screenshots/trigger_workflow.png)

Trigger workflow on every Push that target to master or release branch

![](./screenshots/trigger_workflow_on_push_target_to_master.png)

Trigger workflow on every PR that target to master or release branch

![](./screenshots/trigger_workflow_on_pr.png)

Trigger workflow on every week Monday at 9 o'clock UTC

![](./screenshots/trigger_workflow_on_schedule.png)

Running workflow

![](./screenshots/runniung_workflow.png)

Completed workflow

![](./screenshots/completed_workflow.png)





