# TeleDrive

### Scalable Cloud Storage Platform with Telegram-Backed Storage

TeleDrive is a cloud storage platform designed to provide reliable file upload,
download, organization, and sharing capabilities while using Telegram as the
underlying file-storage backend.

The system is built around a chunked-storage architecture: large files are
split into fixed-size chunks, uploaded independently to Telegram, and
reconstructed during download. This allows the application to handle large
files without buffering the complete file on the application server.

## 🚀 Key Features

- 📁 Upload, browse, rename, move, and delete files
- 📦 Large-file storage using fixed-size chunking
- 🔄 Resumable and range-aware downloads
- 🔐 Authentication and owner-scoped access
- 🔗 Public file sharing
- ⚡ Redis-backed rate limiting
- 📊 Storage quota management
- 🛡️ Soft deletion and background cleanup
- 🌐 Vite + Vanilla JavaScript frontend
- 🧪 Extensive automated testing
- ☁️ Separate frontend and backend deployment


