
---

# ⚙️ 6. **Jenkins/jenkins.md**

```markdown
# ⚙️ Jenkins

## ❓ What is Jenkins?
Jenkins is an automation tool for CI/CD.

## 🔄 Pipeline Stages
1. Build  
2. Test  
3. Deploy  

## 📄 Jenkinsfile Example

```groovy
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
