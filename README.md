# Documentator

A modern documentation platform built with Next.js, offering a Notion-like experience with dark mode support and comprehensive documentation features.

## Features

- 📝 Markdown-based documentation with WYSIWYG editor
- 🌙 Dark/Light mode support
- 🔐 User authentication and role-based access control
- 📂 Nested pages and folders
- 🔗 Internal linking and navigation
- 📊 Version control for documentation
- 🔍 Full-text search
- 📎 Media and file attachments
- 📤 Export/Import functionality
- 🏗️ Project-based organization

## Documentation

- [Architecture Documentation](./docs/ARCHITECTURE.md) - Detailed technical architecture and system design
- [AI Instructions](./docs/AI_INSTRUCTIONS.md) - Guidelines for AI-assisted development
- [Development Guide](./docs/DEVELOPMENT.md) - Getting started and development workflow

## Tech Stack

- **Frontend**: Next.js, TypeScript, Tailwind CSS, shadcn/ui, Redux
- **Backend**: Next.js API Routes, PostgreSQL, Prisma
- **Authentication**: NextAuth.js
- **Storage**: Local file system (with future cloud storage support)
- **Background Jobs**: Redis
- **Testing**: Jest
- **CI/CD**: GitHub Actions

## Getting Started

1. Clone the repository
2. Install dependencies: `npm install`
3. Set up environment variables (see `.env.example`)
4. Start the development server: `npm run dev`

## Contributing

Please read our [Contributing Guidelines](./CONTRIBUTING.md) before submitting a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.
