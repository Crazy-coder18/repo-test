# Welcome to My Documentation Site

## Table of Contents
- [Getting Started](#getting-started)
- [Features](#features)
- [Code Examples](#code-examples)
- [Resources](#resources)

## Getting Started

This is a sample documentation site with various types of content. Here you'll find examples of different markdown elements and formatting options.

### Prerequisites
- Basic understanding of Markdown
- A text editor or IDE
- Git (optional)

## Features

Our documentation includes the following features:

1. **Responsive Design** - Works on all devices
2. **Code Highlighting** - Syntax highlighting for multiple languages
3. **Search Functionality** - Find content quickly
4. **Navigation** - Easy-to-use sidebar navigation

### Key Benefits

| Feature | Description | Status |
|---------|-------------|--------|
| Fast Loading | Optimized for speed | ✅ Complete |
| Mobile Friendly | Responsive design | ✅ Complete |
| Dark Mode | Toggle theme support | 🚧 In Progress |
| Offline Support | PWA capabilities | 📝 Planned |

## Code Examples

Here are some code snippets in different languages:

### JavaScript
```javascript
function greetUser(name) {
    return `Hello, ${name}! Welcome to our documentation.`;
}

const user = "Developer";
console.log(greetUser(user));
```

### Python
```python
def calculate_fibonacci(n):
    if n <= 1:
        return n
    return calculate_fibonacci(n-1) + calculate_fibonacci(n-2)

# Generate first 10 Fibonacci numbers
for i in range(10):
    print(f"F({i}) = {calculate_fibonacci(i)}")
```

### CSS
```css
.documentation-theme {
    --primary-color: #2563eb;
    --secondary-color: #64748b;
    --background-color: #f8fafc;
    --text-color: #334155;
}

.card {
    background: var(--background-color);
    border-radius: 8px;
    padding: 1.5rem;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}
```

## Resources

### Useful Links
- [Markdown Guide](https://www.markdownguide.org/)
- [GitHub Documentation](https://docs.github.com/)
- [VS Code Tips](https://code.visualstudio.com/docs)

### Quick Tips

> **Pro Tip**: Use keyboard shortcuts to speed up your workflow. `Ctrl+Shift+P` opens the command palette in VS Code.

> **Note**: Always backup your work before making major changes.

### Contact Information

For questions or support, reach out to us:

- 📧 Email: support@example.com
- 💬 Discord: [Join our server](https://discord.gg/example)
- 🐦 Twitter: [@ExampleDocs](https://twitter.com/exampledocs)

---

## Recent Updates

### Version 2.1.0 (July 2025)
- ✨ Added new search functionality
- 🐛 Fixed navigation issues on mobile
- 📝 Updated documentation structure
- 🎨 Improved visual design

### Version 2.0.0 (June 2025)
- 🚀 Complete redesign
- ⚡ Performance improvements
- 📱 Mobile-first approach
- 🌙 Dark mode support

## Technical Specifications

### System Requirements
- **Browser**: Chrome 90+, Firefox 88+, Safari 14+
- **Node.js**: 16.x or higher (for development)
- **Memory**: 512 MB RAM minimum
- **Storage**: 100 MB available space

### API Reference

#### Authentication
```http
POST /api/auth/login
Content-Type: application/json

{
  "username": "user@example.com",
  "password": "securePassword123"
}
```

#### Response
```json
{
  "success": true,
  "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...",
  "expires_in": 3600
}
```

---

*Last updated: July 3, 2025*

**© 2025 Documentation Team. All rights reserved.**