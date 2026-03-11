# routes

**Parent**: [server](../AGENTS.md) | **Repository**: Welcome to OpenHands, a community focused

> Provides a collection of API endpoints for managing conversations, handling file operations, interacting with Git providers, and monitoring application health. Implements the public interface for core application functionalities, including version control and conversation lifecycle management.

## Key Components

*No components detected*

## Folder Overview

## See Also

- [Parent overview →](../AGENTS.md) - Repository-level concepts and architecture
- [config/ →](../config/AGENTS.md) - Provides a centralized mechanism for managing server-wide configuration settings, including application mode, external service keys, and feature flags. It aggregates and validates these settings into a structured format for consistent application use.
- [conversation_manager/ →](../conversation_manager/AGENTS.md) - Provides an abstract base class for standardizing conversation management across various operational environments. Implements concrete conversation managers, including one that orchestrates agent loops within isolated Docker containers, handling their complete lifecycle and interactions.
- [data_models/ →](../data_models/AGENTS.md) - Contains structured definitions for core application entities, including agent loop state, conversation metadata, paginated results, and user feedback. Provides the foundational data models for managing and exchanging information within the system.
