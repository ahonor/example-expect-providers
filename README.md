This is a set of plugin examples that wrap `expect`:

* NodeExecutor: Take a command string and pass it to the expectw wrapper.
* WorkflowNodeStep: 
  - blackbox: The plugin contains a standalone expect script to dispatch an action via expect.
  - inline: The plugin takes a job input containing script code to pass to the expect wrapper.


For reference information about script-type plugins see:
https://rundeck.org/docs/developer/plugin-development.html#script-plugin-development

