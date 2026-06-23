# Task Manager API - V2

This is a small project to retake programming from a forced hiatus. The goal with this project is to create a small api app that gets me back on track.

## Description

Objectives: Create a task manager api.
For it's first version it should allow:

- `GET /tasks` — returns all tasks
- `GET /tasks/:id` — returns one task or 404
- `POST /tasks` — creates a task (require `title`, reject with 400 if missing)
- `PATCH /tasks/:id` — updates a task
- `DELETE /tasks/:id` — deletes a task
