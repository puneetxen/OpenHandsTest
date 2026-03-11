# data_models

**Parent**: [storage](../AGENTS.md) | **Repository**: Welcome to OpenHands, a community focused on AI

> Contains fundamental data structures, enumerations, and configuration models essential for representing core application entities and settings. Provides standardized definitions for conversation metadata, status, sensitive secrets, and general application parameters.

## Key Components

*No components detected*

## Folder Overview

## See Also

- [Parent overview →](../AGENTS.md) - Repository-level concepts and architecture
- [conversation/ →](../conversation/AGENTS.md) - Implements core interfaces for managing conversation data persistence and access validation, offering extension points for custom implementations. Contains a concrete file-based storage solution and a factory for dynamic validator instantiation.
- [secrets/ →](../secrets/AGENTS.md) - Provides an extensible mechanism for managing sensitive configuration data, offering an abstract interface for secret storage. Implements a concrete file-based repository for persisting and retrieving these secrets securely.
- [settings/ →](../settings/AGENTS.md) - Provides an abstract interface for managing user settings persistence, establishing a contract for different storage mechanisms, and includes concrete implementations for storing these settings.
