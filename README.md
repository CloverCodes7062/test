Visual Next.js Builder - VS Code Extension
Core Concept
VS Code extension with webview panel that generates actual Next.js files in your project as you drag/drop components
Key Features

Drag-drop UI builder (table, form, card, button, badge)
JSON input → auto-bind to components
AI suggests layout based on JSON structure + description
Generates actual files in Next.js project (pages, actions, components)
AD group access control config
Follows project conventions automatically

Tech Stack

VS Code Extension API
React (webview UI)
File system manipulation (create routes, components, actions)
LLM integration (template suggestions)
Next.js App Router awareness

Generated Output

app/[route]/page.tsx - full page component
app/actions/[name].ts - server actions if needed
Uses existing component library
Follows project auth patterns

Workflow

Open extension panel in VS Code
Paste JSON or describe what you need
AI suggests layout
Drag components, configure
Set route, permissions, endpoints
Click generate → files created in project
Dev server auto-reloads
Refine with Cursor if needed

Demo Flow (3 min)

"Need service health dashboard"
Paste JSON → AI suggests table + badges
Drag, configure endpoint, set AD groups
Generate → dashboard live
Show files created in Explorer

MVP Scope

5 components (Table, Form, Card, Button, StatusBadge)
Basic JSON binding
File generation for Next.js App Router
Simple AI suggestions
AD group dropdown
