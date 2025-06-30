# TASK DEFINITION PROMPT FOR LEGACY PROJECTS

<prompt>

**TASK: Define development activity based on legacy project context and specific requirements**

## CONTEXT REFERENCE
I have a legacy project analysis document that maps the current codebase patterns, inconsistencies, and recommendations. Use this context as the foundation for task planning.

**Legacy Analysis Document**: [Paste or reference your PROJECT_LEGACY_ANALYSIS.md here]

## MY SPECIFIC NEED
[Describe your requirement here. Examples:
- "Add user authentication to the existing system"
- "Create a new payment processing module" 
- "Fix performance issues in the search functionality"
- "Add API endpoints for mobile app integration"
- "Refactor the database access layer"
- "Implement email notification system"]

**Current Issue/Need**: [YOUR SPECIFIC REQUIREMENT HERE]

**Business Context**: [Any additional business requirements, deadlines, or constraints]

**Technical Constraints**: [Mention any limitations - can't change certain modules, must maintain backward compatibility, etc.]

## EXPECTED OUTPUT

Generate a comprehensive task definition that includes:

### 1. TASK OVERVIEW
- Clear, actionable task title
- Brief description of what needs to be accomplished
- Success criteria and definition of "done"

### 2. TECHNICAL APPROACH
Based on the legacy analysis, define:
- Which existing patterns to follow
- Which legacy patterns to avoid
- Recommended implementation strategy
- Integration points with existing code

### 3. IMPLEMENTATION PLAN
- Step-by-step breakdown of the work
- Order of implementation (what to build first)
- Dependencies and prerequisites
- Potential risks and mitigation strategies

### 4. CODE STRUCTURE
- File/folder organization for new code
- Naming conventions to follow
- Architecture patterns to implement
- Testing approach and coverage requirements

### 5. INTEGRATION STRATEGY
- How new code will connect with existing legacy systems
- Data migration needs (if any)
- Backward compatibility considerations
- Deployment and rollback plans

### 6. QUALITY ASSURANCE
- Code review checklist specific to this task
- Testing scenarios and edge cases
- Performance benchmarks to meet
- Security considerations

### 7. CONTEXTUAL PROMPT FOR IMPLEMENTATION
Generate a ready-to-use prompt that I can give to AI for the actual implementation, including:
- All necessary context from the legacy analysis
- Specific technical requirements
- Code examples/patterns to follow
- Expected file structure and naming
- Integration guidelines

## OUTPUT FORMAT
Generate a structured task definition as a markdown file that can be saved as:
- **Single task**: `TASK-001-[task-name].md` 
- **Multiple related tasks**: `TASKS-[feature-name].md`

The file should serve as:
- Complete task specification and roadmap
- Reference document during development  
- Ready-to-use AI prompts for implementation
- Progress tracking and completion checklist

## IMPORTANT CONSIDERATIONS
- Prioritize incremental changes over major rewrites
- Ensure new code improves overall system quality
- Maintain compatibility with existing functionality
- Follow the cleanest patterns identified in legacy analysis
- Include rollback strategies for safety

---

**IMPORTANT: Generate the output as a complete markdown file that I can save as TASK-[ID]-[name].md for organization and tracking.**

</prompt>