# Contributing to 1Pipe

## Development Workflow

### 1. Issue First Approach
Before making any changes:
1. **Create an Issue** that describes:
   - Problem statement or feature request
   - Proposed solution or implementation approach
   - Testing and validation steps
   - Acceptance criteria

### 2. Branch Creation
- All development work must be done in feature branches
- Branch naming convention: `feature/issue-{number}-brief-description`
- Example: `feature/issue-42-add-kubernetes-pattern`

### 3. Development Process
1. Create your feature branch from `main`
2. Make your changes
3. Follow the testing steps outlined in the issue
4. Commit your changes with meaningful commit messages
5. Push your changes to your feature branch

### 4. Merge Request Process
1. Create a Merge Request (MR) from your feature branch to `main`
2. Link the related issue in the MR description
3. Fill out the merge request template
4. Request review from at least one reviewer
5. Address any feedback and make necessary changes

### 5. Review Requirements
- **Minimum Reviewers**: At least 1 approved review is required
- **Stale Reviews**: Will be dismissed when new commits are pushed
- **Review Resolution**: All review comments must be resolved
- **Protected Branch**: Direct pushes to `main` are not allowed
- **Status Checks**: All status checks must pass
- **Linear History**: Maintained through rebase requirement

### 6. Merge Requirements
- At least 1 approval from a maintainer
- All discussions must be resolved
- All tests must pass
- The branch must be up to date with `main`
- Linear history must be maintained

### 7. After Merge
- Feature branches are automatically deleted after 1 hour
- Close the related issue
- Update documentation if necessary

## Branch Protection Rules

The `main` branch is protected with the following rules:
- Direct pushes to `main` are prohibited
- All changes must come through merge requests
- At least 1 approval is required for merge requests
- All discussions must be resolved before merging
- Branch must be up to date before merging
- Stale approvals are automatically dismissed
- Force pushes are not allowed
- Branch deletion is not allowed

## Issue Template

When creating a new issue, include:

### Problem Statement
- Describe the problem or feature request
- Explain why this change is needed

### Implementation Details
- Outline the proposed solution
- List any technical considerations
- Identify potential impacts on existing features

### Testing Steps
- Describe how to test the changes
- List specific test cases
- Include validation criteria

### Definition of Done
- List all requirements that must be met
- Include any specific metrics or benchmarks
- Note any documentation updates needed 