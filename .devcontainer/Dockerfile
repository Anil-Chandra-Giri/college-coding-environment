# Use an official VS Code development container image
FROM mcr.microsoft.com/devcontainers/cpp:latest

# Install additional dependencies (e.g., Dev-C++ alternative)
RUN apt update && apt install -y gdb make cmake

# Set up working directory
WORKDIR /workspace

# Install VS Code extensions
RUN code --install-extension ms-vscode.cpptools
