# Q & A

This is the Duke Robotics Q&A Page. It contains problems that we have run in to, their causes, as well as how to fix them.

Entry format:

1. Problem Description: Description of the problem
2. Problem Cause: A conceptual explanation of what caused the problem
3. Fix - Conceptual: A conceptual explanation of how to fix the problem
4. Fix - Steps: Detailed steps to follow in order to fix the problem

1. Problem Description: No Docker commands work after switching from Docker ToolBox to Docker Desktop
2. Problem Cause: Docker ToolBox environment variables interfere with Docker Desktop
3. Fix - Conceptual: Delete all Docker environment variables
4. Go to environment variables and delete all environment variables that have "Docker" in their name
