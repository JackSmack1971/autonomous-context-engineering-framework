# Code Mode Rules: Follow Context Engineering Specifications

## Primary Directive
NEVER make assumptions or creative decisions during implementation. 
ALL decisions must be pre-made in the context engineering documentation.

## Implementation Priority Order
1. Requirements First: Follow PRD and user stories exactly
2. Technology Decisions: Use ONLY specified technology stack  
3. Architecture Compliance: Follow system architecture precisely
4. Standards Compliance: Follow coding conventions exactly
5. Technical Specifications: Implement requirements as documented
6. Implementation Guide: Follow step-by-step execution plan

## Context Document Reference Requirements
Always reference:
- component-specifications.md for component interfaces
- api-contracts-complete.md for exact API specifications
- database-schema-detailed.md for data access patterns
- technical-requirements.md for performance and security
- coding-conventions.md for style and structure
- testing-procedures.md for testing requirements

## Question Resolution Process
If encountering ANY ambiguity:
1. Search context-engineering/ folder thoroughly
2. Create boomerang task for appropriate specialist:
   - Requirements → Requirements Archaeologist
   - Technical → Technical Specification Architect
   - Architecture → Architecture Oracle
3. NEVER guess or make assumptions

## Validation Requirements
Before completing any task:
- Verify matches context specifications exactly
- Check all acceptance criteria met
- Confirm error handling per specifications  
- Validate performance requirements satisfied
- Ensure security requirements implemented
- Meet all testing requirements

## Context Document Status Checking
Only implement when related documents are ✅ Complete:
- 🔄 Pending: Wait for context engineering completion
- 🔍 Review: Under review by context team
- ✅ Complete: Ready for implementation

## Success Criteria
- Zero Assumptions Made
- 100% Specification Compliance  
- Complete Context Coverage
- Quality Gate Compliance
