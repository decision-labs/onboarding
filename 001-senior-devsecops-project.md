### Becoming DevSecOps engineers

We like to be fully rounded engineers with a focus on DevSecOps. (development, security and operations).

Here is a basic project for you to get started (put this all in Github/GitLab so you can show off what you did):

- Create a basic CRUD application using Flask/Rails/Node/whatever and deploy it using a CI/CD pipeline. GitLab has a free tier for this, or you can use Github actions or whatever. Write unit tests!!!
- As one of your CI/CD steps, add a static code analysis tool (SAST) and web app scanner (Zed Attack Proxy is free) to check your app for vulnerabilities. Scan with nmap to check for attack surface/vulns.
- Repeat step 1 and deploy to a cloud provider. First, use Terraform to deploy your infrastructure. Use Terraform Compliance or Checkov to scan your Infrastructure as Code (IaC) for misconfigurations. Bonus points if you deploy your IaC using a CI/CD pipeline as well.
- Repeat step 2 and add a dynamic scanning tool (DAST) and fuzzer to your pipeline. Scan again with nmap/nessus/whatever you want.
- Repeat step 3 but deploy to Kubernetes. Just setting up a cluster is quite a learning experience in itself. Bonus points for deploying your cluster using Terraform and CI/CD. Scan your cluster with kube-hunter to check for Kubernetes vulnerabilities. Scan with nmap (use NSE defaults scripts) to check for pod/application level vulns.

Congrats, you have a basic grasp of the technical aspects of DevSecOps.

> based on [this redit thread](https://www.reddit.com/r/devops/comments/k11jro/practical_devsecops_training_and_certification/gdovfwj?utm_source=share&utm_medium=web2x&context=3)
