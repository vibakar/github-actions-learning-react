## Github actions learning repo

### ci-parallel.yaml
    - Runs jobs in parallel
    - Triggers workflow when pushed to main branch or pull request is raised to master branch
    - Uses env variable to install specific nodejs version
        - nodejs version configured on job level as well as on job level

### ci-sequence.yaml
    - Runs jobs in sequnece
    - Triggers on manual run