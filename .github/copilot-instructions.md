# Copilot Workspace Instructions

## Development Checklist

- [ ] `dotnet build SocOps/SocOps.csproj` passes
- [ ] `dotnet test` passes
- [ ] run any project linting or analyzer command if available

## Overview

Soc Ops is a Blazor WebAssembly social bingo game on .NET 10. Players mark squares by finding people who match the questions and win with five in a row.

## Key Commands

```bash
cd SocOps
dotnet build SocOps/SocOps.csproj
dotnet run --project SocOps
dotnet test
```

- The dev server runs at `http://localhost:5166`
- `wwwroot/css/app.css` contains the app's CSS utilities
- `workshop/` and `docs/` hold lab and guide content

## Design Guide

- Keep the app's layout simple and centered around the bingo board.
- Use `wwwroot/css/app.css` for shared utility classes and theme colors.
- Prefer reusable utility classes over custom component-specific styles.
- When adding new visuals, stay consistent with the existing rounded/blocky aesthetic.
- Preserve accessibility by keeping button labels clear and maintaining contrast.
- Focus on CSS-only theming first; avoid adding heavy external assets unless necessary.
