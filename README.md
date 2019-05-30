# Command Line Project Management - `cli-pm`
This tool wraps multiple time tracking tools and project management tools and provides a flow to ensure that time tracking context is directly coupled with project management context.

# Examples
In this example we will use [Active Identifier](https://github.com/HeathNaylor/active-identifier) and [Watson](https://tailordev.github.io/Watson/) with [go-jira](https://github.com/go-jira/go-jira).

`cli-pm show ST-174839` - This will use the underlying `go-jira` API to show the data for the story `ST-174839`, while at the same time it will start a `watson` timer for `ST-174839`. These actions will be facilitated by setting the `active` identifier to `ST-174839`. This way you have context in time, project management, and the `active` CLI tool so that you can recall the active story at any time for any other CLI tools.

# Roadmap
These are the tools on the roadmap to support:

PM Tools:
- GitHub
- Jira
- Asana
- Basecamp

Time Tracking Tools:
- Harvest
- Toggl
- Watson
- Taskwarrior
