# Github Actions Training

A repo I will use to try out beginner to advanced concepts and in general play around with Github Actions.

## Links

- [Learning Github Actions by Michael Jenkins](https://www.linkedin.com/learning/learning-github-actions-2)

## Notes

- You can have many workflows but only 20 workflows 180 jobs can run concurrently for GH Enterprise.
- Jobs are limited to 6 hours of runtime
- Workflows are limited to 1000 gh api requests per hour
- Actions can't trigger other workflows
- Action logs are limited to 64kb
  - if this happens your jobs might be found queuing or failing
