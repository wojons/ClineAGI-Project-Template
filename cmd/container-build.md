# Command: Container Build

**Objective:** Build or rebuild the Docker image for the current project.

**Project Name:** {{PROJECT_NAME}}

**Instructions:**
1. Confirm the active project context.
2. Identify the expected image name for the active project (e.g., `projects/{{PROJECT_NAME}}`).
3. Ensure a Dockerfile exists in the project root (`projects/<project_name>/Dockerfile`). If not, inform the user and suggest creating one.
4. Use the container image management workflow (`200-02_container-image-management.md`) to build the image using `docker build -t <image_name> .` within the project directory.
5. Inform the user that the image build has started.
