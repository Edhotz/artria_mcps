## The Artria Open Source MCP'S Server

The Artria MCP Server is a Model Context Protocol to enable clients to natural
conversations with LLMS to permit request data more easy and more human instead
huge forms on platform

┌─────────────────┐
│   Aplicação     │
│   Web/Mobile    │
└────────┬────────┘
         │
         │ HTTP/WebSocket
         ▼
┌─────────────────┐
│  API Gateway    │
└────────┬────────┘
         │
         │ Conversação Natural
         ▼
┌─────────────────────────────────┐
│         Claude AI               │
│  (com MCP Tools ativadas)       │
└────┬───────────┬─────────┬──────┘
     │           │         │
     │ MCP       │ MCP     │ MCP
     ▼           ▼         ▼
┌─────────┐ ┌─────────┐ ┌─────────┐
│Property │ │Booking  │ │  User   │
│ Server  │ │ Server  │ │ Server  │
└────┬────┘ └────┬────┘ └────┬────┘
     │           │         │
     │           │         │
     ▼           ▼         ▼
┌────────────────────────────────┐
│      PostgreSQL Database       │
└────────────────────────────────┘
