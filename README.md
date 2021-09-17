# logic-apps-test

A repo to explore the Logic Apps (Standard) experience in VS Code

## Getting started

1. Clone the repo and open in Visual Studio Code as a [dev container](https://code.visualstudio.com/docs/remote/containers)
1. Start the Azurite emulator for Azure Storage (`Azurite: Start` from the Command Palette)
1. Start debugging (`F5`)
1. In the Explorer panel, right-click on `StatefulWorkflow1\workflow.json` and choose Overview
1. When that page loads, copy the value of `Callback URL`
1. Open `test.http` and paste the URL you just copied in place of the existing value for `workflowURL`
1. Click Send Request in `test.http`

At this point you should see the HTTP response from the Logic App workflow.

To explore/modify the workflow, right-click the `workflow.json` and choose Open in Designer.

