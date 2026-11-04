# Task Manager Plugin

My class project for Build What Agents Want, using the task manager we built in an earlier lesson and adapting Emmanuel’s provided plugin template.

## What it does

Connects a Replit-hosted task manager to ChatGPT through four MCP tools:

- `get_tasks` — lists tasks, optionally filtered by status.
- `create_task` — adds a task.
- `change_task` — updates a task’s name or status.
- `delete_task` — deletes a task.

## Project status

Submitted to OpenAI for review. It is not yet approved or published in the directory.

This repository contains the plugin package and assets. The server runs separately on Replit.

## Important limitations

This is a learning demo with a shared, temporary task list.

- There is no login or private task ownership.
- Anyone accessing the same server process can view, change, or delete its tasks.
- Tasks disappear when the server restarts or is redeployed.
- Do not enter personal, confidential, or sensitive information.

## Files

- `plugin.json` — plugin details and submission metadata.
- `mcp.json` — MCP server connection configuration.
- `assets/` — plugin images.

Some sample branding and review materials from the class template remain in this submission.

## Server and information

MCP endpoint:
https://task-manager-mcp-server.replit.app/mcp

Privacy:
https://task-manager-mcp-server.replit.app/privacy

Terms:
https://task-manager-mcp-server.replit.app/terms

Support:
https://task-manager-mcp-server.replit.app/support

Server availability may change after the class exercise.

## Lessons learned

- Package filenames and metadata must match the required schema.
- Tool annotations must describe actual behavior, including updates that overwrite existing information.
- Server changes and plugin-package changes require different update steps.
- A privacy page can work in a browser while its text remains inaccessible to a checker that does not run JavaScript.
- Passing automated checks does not mean publication approval.

## Credits

Built by Alicia Franke during Build What Agents Want, using Emmanuel Paraskakis’ class materials and plugin template.
