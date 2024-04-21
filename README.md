# Git Branching Strategy for Dmart Applications

## Jenkins

- **GIT Branching Strategy**
  1. Master/Main
  2. Release
  3. Feature
  4. Develop
  5. Hotfix

## Dmart Applications

1. **Item Stock Application** - Github repo
2. **Transportation Application** - Github repo
3. **Billing Payments Application** - Git repo

For each of the applications listed above, there are 5 branches following the Git branching strategy outlined.

## Branches

### Develop Branch
- Child branch for every developer

### Example: Transportation Application
- Trucks
- Location
- Driver details

For instance, if we consider the Transportation Application, each developer has their own branch (5 branches).

### Feature Branch
- Represents a specific feature (e.g., Trucks in Transportation Application)
- Combination of all child branches

### Release Branch
- Combines all branches together

### Master/Main Branch
- Production branch

## Workflow
1. Develop > Feature > Release > Master

## HotFix
- Used to address issues in the production environment
## CICD flow
Developer > Sourcecode > Repositary > Unit Test > Static code analysis > Build > Build artifact(jfrog) > Build and push images (Docker) > Deploy kubernates > Monitor and operate > 
 - **Master Slave setup**
 - 
