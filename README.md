# DevOps_Assignment1
Sure, here's a simplified version of your project notes:

---

### Objective
To demonstrate:
- Continuous Integration (CI)
- Continuous Deployment (CD)
- Master-Agent setup using Jenkins
- Webhook integration with GitHub
- Manual approval for production deployment

### Technologies Used
- **Jenkins**: Local setup with Controller-Agent architecture
- **GitHub**: Repository management and webhook triggering
- **Groovy**: Jenkins Declarative Pipeline
- **LocalTunnel**: Exposing localhost to GitHub for webhooks
- **Bash Scripts**: Simulated deployment steps

### Project Structure
```
.
├── Jenkinsfile             # Jenkins Pipeline definition
├── README.md               # This file
├── build.sh                # Simulated build script
├── run_tests.sh            # Simulated test script
├── deploy_staging.sh       # Mock deploy to staging
└── deploy_prod.sh          # Mock deploy to production
```

### Pipeline Flow
The Jenkins pipeline includes the following stages:
1. **Checkout**: Pulls code from GitHub
2. **Build**: Simulated build process
3. **Test**: Unit testing simulation
4. **Deploy to Staging**: Simulated deployment
5. **Manual Approval**: Human intervention before production
6. **Deploy to Production**: Final deployment stage

### GitHub Integration
- Repository: `DevOps_Assignment1`
- Webhook connected via LocalTunnel
- Jenkins triggers builds automatically on push events

### How to Run Locally
1. Clone the repo:
   ```bash
   git clone https://github.com/aishwaryakchikorde/DevOps_Assignment1.git
   ```
2. Open Jenkins
3. Create a new pipeline job and point it to this repo
4. Paste the contents of `Jenkinsfile` in the pipeline script section
5. Trigger a build manually or via GitHub webhook

### Author
**Aishwarya Chikorde**
- .NET Developer & DevOps Explorer

