# cicd

## Github Actions
**Repository** - https://github.com/wseyi/jenkins-maven

### Steps
1. Fork the repository
2. Go to settings in the repository and create your secret docker hub username and password which will be used to log into docker hub.
   ![Alt text](Screenshot_2023-11-26_12-24-11.png)
3. Go to actions and select new workflow then click the **"set up a workflow yourself"** link.
   ![Alt text](Screenshot_2023-11-26_12-12-25.png)
4. Copy script from workflow.yaml file
   ![Alt text](Screenshot_2023-11-26_12-15-50.png)

## Jenkins Pipeline
### Link to github repository
https://github.com/wseyi/jenkins-maven

#### Steps
1. Click on New item.
2. Name your item and select pipeline plug-in and click ok.
3. When configuring select github project and put the repository url. 
   ![Alt text](Screenshot_2023-11-26_11-32-28.png)
4. Copy and paste the script from jenkinsfile into the pipeline section.
   ![Alt text](Screenshot_2023-11-26_11-32-58.png)
5. Save and click build now.