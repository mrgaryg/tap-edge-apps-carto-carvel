# Edge GitOps Repo Monitor App

This app definition is a simple way to monitor the GitOps repo where the DC Supply Chain commits `Deliverable` objects.  By default, the supply chain commits new `Deliverables` to the `dev` branch of the repo, and this app is set to monitor the `main` branch.  This allows for the use of pull requests to allow for approvals of delivery to edge sites.  If you don't need this capability, then just modify the app manifest to point to the main branch of the GitOps repo.