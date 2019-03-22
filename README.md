# awsome-processes

A curated list of awesome processes that would make building a company more effective and resilient.

## Reasoning
After talking to a bunch of successful people in the industry, I realized with them that good functioning companies have good processes. The first metaphor that came to mind is, a company without any processes is like code that isn't tested - no one wants that. So I tried to gather the most interesting and fundamental processes around into a list you can start using.

## How to use
My first thought is that you should fork this repo and tailor it to your specific needs and situation. As every company is a tad bit different :)

## Things I'm still not sure about
Should we split this into sections or keep it as a one-pager? any thoughts are welcomed.
  

---
**Here you go:**  
### General Code Base
- [ ] Version controlled
  - [ ] the master branch is protected unless it's a PR
  - [ ] every new feature is in a new branch
  
### Codebase security
- [ ] Credentials are not hardcoded
- [ ] Updating dependencies is an automated build process

### Issues
- [ ] Related to git
- [ ] Have templates
- [ ] When possible an image/gif is placed, elaborating as much as possible.

### Documentation
- [ ] Easily accessible
- [ ] [Centralized in one place] OR [If not centralized then, minimized to public/private docs]
 
### Pull Requests
- [ ] there are at least x eyes before a merge
- [ ] there is a passing build in ci
- [ ] the code does not change coverage (*eg feature = more tests, bug = verify tests*)

### Codebase CI
- [ ] linting via shared spec
- [ ] unit testing 
- [ ] integration testing
- [ ] e2e testing
- [ ] having 100% code coverage
- [ ] static code security checks
- [ ] [dependencies security checks](1)


### Devops
- [ ] starting a new server should be frictionless for developers
- [ ] all services should be logged to a centralized log digesting system.

### Onboarding
- [ ] has a talk with team leader & team
- [ ] gets the mission
- [ ] Introduction to product
- [ ] Exercise on building for the product and processes

### Deployment Friction
- [ ] Every dev team member should be able to spin a micro-service by himself (own DB too).
   - [ ] The new service should be automatically discoverable to other micro-services.

## Deployment to production
- [ ] Must have e2e tests before deployment
- [ ] Canary Builds
