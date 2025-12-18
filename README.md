# PO Buddy

PO Buddy helps manage the **AI Buddy** project by syncing operational data from **ClickUp** into two versioned JSON files:

- `po_buddy_config.json`: configuration + mapping (no secrets)
- `po_buddy_project_content.json`: the project “source of truth” snapshot (continuously updated)

## What this repo will do

- Read ClickUp (via ClickUp MCP) to mirror tasks, comments, and time entries.
- Maintain structured project management artifacts (sprints, capacity, budget-in-hours, stakeholders, risks, comms).
- Write updates back into `po_buddy_project_content.json`.
- Commit changes to `main` with meaningful messages when deltas are detected.

## Files

- `po_buddy_config.json`
- `po_buddy_project_content.json`


