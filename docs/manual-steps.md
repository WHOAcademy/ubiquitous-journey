## Manual steps in setting up CI/CD with Jenkins

### Not automated yet when onboarding a new project / microservice 
1. Setup your repo in `WHOAcademy`
2. Create your webhook eg https://jenkins-labs-ci-cd.apps.who.emea-2.rht-labs.com/multibranch-webhook-trigger/invoke?token=${REPO_NAME}
3. Create your Quay repo & add robot account to it
4. Create argoCD project by adding it to the `applications` array for `test` and `staging`.
