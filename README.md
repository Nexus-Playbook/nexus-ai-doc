# Nexus AI Doc Service

Document collaboration and management service for Nexus AI platform.

## Features
- Real-time collaborative editing
- Document version history
- Comments and annotations
- File attachments
- Document sharing and permissions
- Search within documents
- Export capabilities (PDF, Markdown)

## Tech Stack
- Node.js with NestJS
- MongoDB for document storage
- Redis for real-time collaboration
- WebSocket for live editing
- File storage (AWS S3 or local)

## API Endpoints
- `POST /docs` - Create document
- `GET /docs` - List documents
- `GET /docs/:id` - Get document
- `PATCH /docs/:id` - Update document
- `DELETE /docs/:id` - Delete document
- `POST /docs/:id/comments` - Add comment
- `POST /docs/:id/share` - Share document

## Real-time Collaboration
- Operational Transform (OT) for conflict resolution
- Live cursors and user presence
- Auto-save and conflict resolution

## License
Private - Nexus AI Platform