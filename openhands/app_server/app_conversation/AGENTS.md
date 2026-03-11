# app_conversation

**Parent**: [app_server](../AGENTS.md) | **Repository**: Welcome to OpenHands, a community focused on AI-driven

> Provides core services, data models, and routing for managing sandboxed conversations within the OpenHands application, integrating Git functionalities for operational control. Implements the lifecycle management of conversations, from creation to tracking and interaction.

## Key Components

*No components detected*

## Folder Overview

## See Also

- [Parent overview →](../AGENTS.md) - Repository-level concepts and architecture
- [app_lifespan/ →](../app_lifespan/AGENTS.md) - Orchestrates the application's startup and shutdown phases, ensuring proper initialization and cleanup. It specifically integrates database schema migration processes into the application's lifecycle using Alembic.
- [event/ →](../event/AGENTS.md) - Provides core functionality for managing conversation events, including storage, retrieval, and streaming capabilities. Implements an extensible service layer for event handling and routing, supporting various data sources.
- [event_callback/ →](../event_callback/AGENTS.md) - Provides a comprehensive system for managing webhooks and event notifications, facilitating external system integration within conversations. Implements core services for event callback registration, data modeling, and processing, alongside a dedicated router for handling incoming requests.
