# Command: Container Status

**Objective:** Check the status of the dedicated container for the current project.

**Project Name:** {{PROJECT_NAME}}

**Instructions:**
1. Confirm the active project context.
2. Identify the expected container name for the active project (e.g., `projects/{{PROJECT_NAME}}`).
3. Use the container runtime operations workflow (`200-03_container-runtime-operations.md`) to check the status of the container using `docker ps -a --filter name=<container_name>`.
4. Present the container status output to the user.
