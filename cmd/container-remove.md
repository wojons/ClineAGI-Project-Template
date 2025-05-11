# Command: Container Remove

**Objective:** Remove the dedicated container for the current project.

**Project Name:** {{PROJECT_NAME}}

**Instructions:**
1. Confirm the active project context.
2. Identify the expected container name for the active project (e.g., `projects/{{PROJECT_NAME}}`).
3. Use the container runtime operations workflow (`200-03_container-runtime-operations.md`) to stop the container first using `docker stop <container_name> || true` (to avoid errors if already stopped).
4. Use the container runtime operations workflow (`200-03_container-runtime-operations.md`) to remove the container using `docker rm <container_name> || true` (to avoid errors if already removed).
5. Inform the user that the container has been removed.
