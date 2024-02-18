## Github actions learning repo

### ci-parallel.yaml
    - Runs jobs in parallel
    - Triggers workflow when pushed to main branch or pull request is raised to master branch.
        - Added config not to trigger the workflow if the changes made on README.md file 
    - Uses env variable to install specific nodejs version
        - nodejs version configured on workflow level as well as on job level
    - Uses secerts created in repository. Also uses environment secrets in the repository

### ci-sequence.yaml
    - Runs jobs in sequnece
    - Triggers on manual run