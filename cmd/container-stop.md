# Command: Container Stop

**Objective:** Stop the dedicated container for the current project if it is running.

**Project Name:** {{PROJECT_NAME}}

**Instructions:**
1. Confirm the active project context.
2. Identify the expected container name for the active project (e.g., `projects/{{PROJECT_NAME}}`).
3. Use the container runtime operations workflow (`200-03_container-runtime-operations.md`) to stop the container using `docker stop <container_name>`.
4. Inform the user that the container is stopping.
