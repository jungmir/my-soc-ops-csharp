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
