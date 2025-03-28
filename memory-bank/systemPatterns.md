# System Patterns: Projects Directory

## Directory Structure
```
Projects/
├── memory-bank/       # Central documentation
│   ├── projectbrief.md
│   ├── productContext.md
│   ├── systemPatterns.md
│   ├── techContext.md
│   ├── activeContext.md
│   └── progress.md
├── .clinerules        # Project intelligence
└── [project folders]  # Individual project directories
```

## Key Technical Decisions
1. Centralized Documentation
   - All documentation lives in memory-bank/
   - Each project may have its own docs subfolder
   - Memory Bank files track overall organization

2. Project Organization
   - Each project gets its own root-level directory
   - Projects follow their own internal structure
   - Common patterns documented in .clinerules

3. Version Control
   - Each project manages its own version control
   - Memory Bank tracked with main directory
   - .clinerules evolves with project patterns

## Component Relationships
1. Memory Bank ↔ Projects
   - Memory Bank tracks project status
   - Projects reference Memory Bank for context
   - Bidirectional documentation flow

2. Projects ↔ Projects
   - Shared dependencies documented
   - Inter-project relationships tracked
   - Common patterns identified

3. .clinerules ↔ All
   - Captures learned patterns
   - Guides future development
   - Evolves with project needs
