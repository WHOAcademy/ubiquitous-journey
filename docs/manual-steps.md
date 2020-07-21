## Manual steps in setting up CI/CD with Jenkins

### Not automated yet when onboarding a new project / microservice 
1. Setup your repo in `who-lxp`
2. Create your webhook eg https://jenkins-my-ci-cd.apps.who.emea-2.rht-labs.com/multibranch-webhook-trigger/invoke?token=${REPO_NAME}
3. Create your Quay repo & add robot account to it
4. Create argoCD project