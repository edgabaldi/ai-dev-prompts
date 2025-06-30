# LEGACY PROJECT ANALYSIS PROMPT

<prompt>

**TASK: Analyze and document legacy project to create development context**

I need you to analyze the entire current project and generate structured documentation of the current state. Focus on identifying patterns, inconsistencies, and creating a map of existing code.

## REQUESTED ANALYSIS:

### 1. GENERAL STRUCTURE
- Map the main folder structure
- Identify current architecture (MVC, microservices, monolith, etc.)
- List main technologies and versions (package.json, requirements.txt, etc.)

### 2. CODE PATTERNS FOUND
Analyze and document ALL different patterns found for:
- **Controllers/Routers**: different implementation styles
- **Models/Entities**: ORMs, direct queries, data access patterns
- **Validation**: libraries used, manual validation, schemas
- **Error handling**: try/catch, middleware, different patterns
- **Authentication/Authorization**: systems in use
- **Tests**: frameworks, coverage, patterns (if they exist)

### 3. INCONSISTENCY IDENTIFICATION
- List implementation differences for similar functionalities
- Identify duplicated or redundant code
- Point out outdated or conflicting dependencies
- Mark files that seem abandoned or experimental

### 4. REFERENCE FILES/MODULES
- Identify the cleanest/most recent implementation examples
- Find files that follow best practices (even if inconsistent with the rest)
- Mark modules that could serve as templates for new development

### 5. TECHNICAL DEBT ASSESSMENT
- List major refactoring opportunities
- Identify critical files that need immediate attention
- Point out security concerns or deprecated practices
- Highlight performance bottlenecks or resource issues

### 6. DEVELOPMENT RECOMMENDATIONS
Based on your analysis, suggest:
- Which pattern should be standardized for new development
- Priority order for refactoring efforts
- Dependencies that should be updated first
- Testing strategy for legacy modules

## OUTPUT FORMAT:
**Generate everything as a single comprehensive .md file** with proper markdown formatting, including:
- Executive summary of project state
- Detailed findings for each section above
- Code examples showing different patterns found
- Actionable recommendations with priority levels
- Template structures for future development

## IMPORTANT:
- Be thorough but practical
- Include specific file paths and line numbers when relevant
- Distinguish between "different by design" vs "inconsistent patterns"
- Focus on what can be improved incrementally
- Suggest migration paths rather than complete rewrites

## ADDITIONAL CONTEXT CREATION:

After the analysis, also generate:

### 7. AI DEVELOPMENT CONTEXT TEMPLATE
Create a ready-to-use context document with:
- **Project Overview**: Brief description of what the system does
- **Current Tech Stack**: Exact versions and configurations
- **Coding Standards**: Based on the best patterns you found
- **File Organization**: Expected structure for new modules
- **Common Operations**: Templates for typical CRUD operations
- **Integration Patterns**: How modules should communicate
- **Error Handling Strategy**: Standardized approach for new code
- **Testing Approach**: Framework and patterns to follow

### 8. TASK TEMPLATES
Generate reusable prompt templates for common development tasks:
- **New Feature Template**: Structure for implementing complete features
- **Bug Fix Template**: Approach for debugging and fixing issues
- **Refactoring Template**: Safe refactoring of legacy modules
- **Integration Template**: Adding new external services or APIs

---

**IMPORTANT: Generate the complete analysis as a single markdown (.md) file that I can save directly as PROJECT_LEGACY_ANALYSIS.md**

**After running this analysis, I'll have a complete map of the legacy project and ready-to-use templates for autonomous AI-assisted development.**
</prompt>