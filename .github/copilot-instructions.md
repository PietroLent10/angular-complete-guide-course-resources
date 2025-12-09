# GitHub Copilot Instructions for Angular Complete Guide Course Resources

## Repository Overview
This repository contains course resources for "Angular - The Complete Guide" course, including code snapshots, attachments, and slides.

## Project Structure
- `/code-snapshots/` - Contains complete Angular project snapshots for different course sections
- `/attachments/` - Contains lecture-specific files and resources
- `/other-resources/` - Additional course materials

## Code Snapshots Organization
Each snapshot represents a specific state of an Angular project at different points in the course:
- Snapshots are organized by section (e.g., `02-essentials`, `03-essentials-modules`, etc.)
- Within each section, there are multiple snapshots showing progression
- Each snapshot is a complete, standalone Angular project

## Angular Version and Standards
- This repository contains Angular projects using modern Angular features
- Projects may use both standalone components and module-based architecture
- Follow Angular style guide and best practices
- Use TypeScript for all Angular code

## Development Guidelines

### When Working with Code Snapshots:
1. Each snapshot is independent and self-contained
2. Do not modify snapshots unnecessarily - they serve as reference points for students
3. Maintain consistency with Angular CLI structure
4. Preserve existing code style within each snapshot

### Angular Best Practices to Follow:
- Use TypeScript strict mode features
- Follow Angular naming conventions (PascalCase for components, camelCase for properties)
- Use Angular Signals for reactive state management where applicable
- Implement proper component lifecycle hooks
- Use dependency injection for services
- Follow single responsibility principle for components and services

### File Naming Conventions:
- Components: `*.component.ts`, `*.component.html`, `*.component.css`
- Services: `*.service.ts`
- Models: `*.model.ts`
- Modules: `*.module.ts`

### TypeScript Guidelines:
- Use explicit type annotations
- Avoid `any` type
- Use interfaces for object shapes
- Use enums for fixed sets of values

### Testing Considerations:
- Each snapshot may have its own testing setup
- Respect existing test configurations
- Follow Jasmine/Karma patterns if tests are present

## Documentation Standards
- Keep README.MD updated with clear instructions
- Document any changes that affect how students use the resources
- Maintain Italian and English clarity where applicable (repository owner appears to be Italian-speaking)

## Permissions and Editing
- GitHub Copilot has permission to suggest edits and improvements
- Focus on maintaining educational value of code snapshots
- Preserve the pedagogical progression between snapshots
- Avoid making breaking changes to existing snapshots unless absolutely necessary

## Important Notes
- This is a teaching resource - code clarity is more important than cleverness
- Students follow along with these snapshots, so consistency is crucial
- Respect the course structure and progression
- When in doubt, prefer simpler, more explicit code that's easier for learners to understand
