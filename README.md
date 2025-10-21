# Trailer.dev Community

Trailer.dev is a self-hostable platform that enables seamless container-based development environments.
It provides a modern, efficient way to manage development workspaces and container resources.
Trailer.dev puts emphasis on Python and AI/ML development for ease-of-use.

## Features

- **Self-hostable**: Run your own instance of Trailer.dev
- **Container Management**: Built-in support for Docker containers, networks, volumes, and images
- **Real-time Updates**: WebSocket-based real-time communication between agents and server
- **Web UI**: A responsive and intuitive interface for managing your agents and environments
- **Multi-mode Operation**: Flexible deployment options with agent, server, and standalone modes
- **Resource Management**: Efficient handling of development resources with automatic reconciliation
- **Secure**: Built-in authentication and authorization system
- **Extensible**: A plugin system and plugin catalog allowing for future extensions and customizations

## Run Modes

Trailer.dev can be run in three different modes:

1. **Server Mode**
   - Runs the web server component
   - Handles API requests and frontend serving
   - Manages agent connections and resource coordination
   - Default port: 8090

2. **Agent Mode**
   - Runs the agent component
   - Manages local Docker resources
   - Communicates with the server
   - Handles workspace operations

3. **Standalone Mode**
   - Combines both server and agent functionality
   - Runs everything in a single process
   - Perfect for single-machine deployments
     
## About this repository

This is an **issues-only repository** for tracking bug reports from the community.

The goal of this tracker is to report bugs that our team can reproduce. Sometimes, there's a lot going on - and we're not able to reproduce the issue outside of your instance. For issues that are instance- or host-specific, please be as specific about your environment as possible.

For suggestions about features and enhancements, please add your feedback to the issue tracker as well.
