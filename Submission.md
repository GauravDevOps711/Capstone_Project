<h1>CAPSTONE PROJECT</h1>
<p>

1. Let’s start from scratch: Run --> cmd --> winget install wsl --> YES
![1](https://github.com/GauravDevOps711/test/assets/135973657/d8b149e7-5b00-46d2-a801-3cc6486fccba)

2. sudo apt update && sudo apt upgrade -y 
![2](https://github.com/GauravDevOps711/test/assets/135973657/67fdc8f8-9109-4ae0-9d73-1d23d78610c4)
</p>

<h3><b>APPLICATION</b></h3>

3. git clone https://github.com/sriram-R-krishnan/devops-build --> ls -l
![3](https://github.com/GauravDevOps711/test/assets/135973657/e975c70c-01b2-47e6-b5f2-b74116a4a6eb)

4. cd devops-build--> npm init -y --> sudo npm install -g serve@13.0.2 --> sudo snap install serve
![4](https://github.com/GauravDevOps711/test/assets/135973657/68450cb7-b95d-45dd-96fa-6c29b78d7408)

5. sudo npm cache clean -f--> sudo npm install -g n --> sudo n latest--> serve -s build -l 80 &
![5](https://github.com/GauravDevOps711/test/assets/135973657/64a53eeb-c03e-4c0c-af4d-294c2fc1833a)

6. Browser --> localhost:80
![6](https://github.com/GauravDevOps711/test/assets/135973657/91f41e64-e977-446d-a7a3-92b92242329a)

</p>

<h3><b>DOCKER</b></h3><p>

7. Creating a Script directory--> mkdir Script--> cd Script--> nano docker.sh && chmod +x docker.sh--> cat docker.sh 
![7](https://github.com/GauravDevOps711/test/assets/135973657/3d7aa665-655f-40b9-8c46-77da432c6e79)

8. sudo ./docker.sh 
![8](https://github.com/GauravDevOps711/test/assets/135973657/bf2aa5ce-63c2-476b-83ac-6e5b0cbff7dd)

9. sudo chmod 666 /var/run/docker.sock--> docker -v 
![9](https://github.com/GauravDevOps711/test/assets/135973657/55231e52-cc07-49f8-be75-d75d75d26133)

10. docker login --> ID & Token Password 
![10](https://github.com/GauravDevOps711/test/assets/135973657/cefa6ce0-5c41-4809-85e0-800ae5489824)

11. nano Dockerfile --> cat Dockerfile 
![11](https://github.com/GauravDevOps711/test/assets/135973657/0cfa89b3-b50d-4305-8f6b-3b4c2cf65faf)

12. nano docker-compose.yml --> cat docker-compose.yml
![12](https://github.com/GauravDevOps711/test/assets/135973657/f179dda3-b579-48fa-865b-20d04ff817a7)

</p>

<h3><b>BASH SCRIPTING</b></h3><p>

13. nano build.sh && sudo chmod +x build.sh--> cat build.sh--> ./build.sh 
![13](https://github.com/GauravDevOps711/test/assets/135973657/c1ed43f7-ad0d-4532-b326-873e6050328b)

14. nano deploy.sh && sudo chmod +x deploy.sh--> cat deploy.sh--> ./deploy.sh--> docker images ![14](https://github.com/GauravDevOps711/test/assets/135973657/fb5ee60b-4d19-47a9-b5ea-b71a03177f81)
![14 1](https://github.com/GauravDevOps711/test/assets/135973657/7570363b-b73b-44af-87fc-92e1e949f6a8)


15. Successfully pushed to Dockerhub repositories. ![25](https://github.com/GauravDevOps711/Capstone_Project/assets/135973657/e4c1e48e-695c-4f78-8bd3-cd62bf389d28)


</p>

<h3><b>VERSION CONTROL</b></h3><p>

16. nano .gitignore --> cat .gitignore --> nano .dockerignore --> cat .dockerignore --> git init ![16](https://github.com/GauravDevOps711/test/assets/135973657/0db8bce7-33c9-4898-afb9-5ebe9a1a361f)
![16 1](https://github.com/GauravDevOps711/test/assets/135973657/49954806-7f24-496f-ae09-890c9fd44315)
![16 2](https://github.com/GauravDevOps711/test/assets/135973657/ad2a135d-ef93-4b06-92d9-1e8bf90070bc)


17. git add . --> git commit -m"All files are added" ![17 1](https://github.com/GauravDevOps711/test/assets/135973657/444ad619-a75c-4d2b-b639-30e51ad9fb66)

 

18. git branch -M dev--> git branch ![19](https://github.com/GauravDevOps711/test/assets/135973657/4cdd7851-16b0-4635-8986-38f44cdb4aeb)



19. git remote add origin https://github.com/GauravDevOps711/Capstone_Project.git --> git push -u origin dev --> GitHub: UserID + Token Credential ![20](https://github.com/GauravDevOps711/test/assets/135973657/985dfc0e-8551-4c53-af49-9356a60a1630)


20. Code pushed to github remote repo. 
21. Successfully pushed the code to Gitgub repo. ![21](https://github.com/GauravDevOps711/Capstone_Project/assets/135973657/3c66da5c-4999-45f8-9e1b-c5426feda3fb)

</p>

<h3><b>DOCKER HUB</b></h3><p>

22. nano pub_repo.sh && chmod +x pub_repo.sh--> cat pub_repo.sh ![22](https://github.com/GauravDevOps711/test/assets/135973657/f228bec7-495a-49ae-af17-b1cf96a61df7)


23. docker tag devops-build gaurav4u/dev_repo:dev--> docker images --> docker push  gaurav4u/dev_repo:dev ![23](https://github.com/GauravDevOps711/test/assets/135973657/524fe955-eb7a-48b6-95b7-dd7309752ff2)


24. docker tag devops-build gaurav4u/prod_repo:prod--> docker images --> docker push gaurav4u/prod_repo:prod ![24](https://github.com/GauravDevOps711/test/assets/135973657/c5dd6bcb-e92f-4f3b-97a9-1b7513c8313f)


25. Successfully pushed “dev” and “prod” to the Docker Hub repository. ![25](https://github.com/GauravDevOps711/Capstone_Project/assets/135973657/be660e56-107f-429e-ba74-9a4f1b3e7562)

</p>


<h3><b>JENKINS</b></h3><p>

26. sudo apt install openjdk-17-jre-headless --> java --version ![26](https://github.com/GauravDevOps711/test/assets/135973657/3af65b99-0665-4506-8463-6bec2a1d2031)


27. nano jenkins.sh--> sudo chmod +x jenkins.sh--> ./jenkins.sh ![27](https://github.com/GauravDevOps711/test/assets/135973657/34622e4e-cc13-4cb9-a440-d0a77b5f822c)


28. systemctl status jenkins ![28](https://github.com/GauravDevOps711/test/assets/135973657/f0f375fa-2c87-460b-ad7b-7aecfdacb988)


29. Copy & paste the password--> Install suggested plugins --> Fill all asked details--> SAVE. ![29](https://github.com/GauravDevOps711/test/assets/135973657/7780a69d-be48-4664-9459-45ec97dc9dd4)


30. Welcome To Jenkins. ![30](https://github.com/GauravDevOps711/test/assets/135973657/8627a448-397a-4369-8267-6ee8ceb26688)


31. Goto Manage Jenkins --> Plugins --> Avavilble Plugins --> GitHub Integration + Docker Pipeline Plugins + Docker + CloudBees Docker Build and Publish![31](https://github.com/GauravDevOps711/test/assets/135973657/e62cd89f-f919-46bc-80df-020db2ed3464)


32. Now goto manage jenkins--> Tools--> Docker installations--> SAVE. ![32](https://github.com/GauravDevOps711/test/assets/135973657/87070011-31bd-4533-b64d-63c635d9c00a)


33. Click on Manage Jenkins--> Credentials--> Global: Add Credentials--> GitHub + Docker ![33](https://github.com/GauravDevOps711/test/assets/135973657/d5cabed3-caed-4b17-ac6f-1803dae59b60)


34. Dashboard--> New Item--> Item_Name--> Freestyle project--> OK. ![34](https://github.com/GauravDevOps711/test/assets/135973657/088be962-c993-491b-b5b1-5c9bdd74727f)


35. Source Code Management--> Git--> github repo URL--> Github Credential--> branch: */dev--> Save ![35](https://github.com/GauravDevOps711/test/assets/135973657/8c48fcd0-80ab-424d-a265-abfe211a8bb3)


36. Build Trigger--> GitHub hook trigger for GITScm polling ![36](https://github.com/GauravDevOps711/test/assets/135973657/9071a5c9-b2bb-4f07-b07a-92365f541548)


37. Build steps--> a) execute shell b) Docker build and publish--> Registry credentials --> SAVE ![37](https://github.com/GauravDevOps711/test/assets/135973657/2440fae4-c925-4962-ba46-70141d877945)
![37 1](https://github.com/GauravDevOps711/test/assets/135973657/21ab17e9-bbbc-4cdb-916c-bc1a9bf3b4c0)


38. Now click on “Build Now” --> 2nd build is completed. ![38](https://github.com/GauravDevOps711/test/assets/135973657/566ec2ec-4f2f-4c57-9334-1a67b6201df2)


39. Console Output  ![39](https://github.com/GauravDevOps711/test/assets/135973657/dd94194b-70bd-4f59-b123-d5776a92574a)
![39 1](https://github.com/GauravDevOps711/test/assets/135973657/beec6d51-1d0c-44d7-9dde-14ddddaafa42)


40. Successfully pushed the images to dockerhub. ![40](https://github.com/GauravDevOps711/test/assets/135973657/64b7433d-e0b5-4391-acce-cf510b7e6437)

</p>


<h3><b>AWS</b></h3><p>

41. Login to AWS using IAM--> Launch EC2--> AMI: Ubuntu 22.04 LTS ![41](https://github.com/GauravDevOps711/test/assets/135973657/a1bd08ad-441e-4f25-b2ec-77fd7bba0735)


42. Instance Type: t2.micro--> KeyPair--> Auto-assign IP: Enable ![42](https://github.com/GauravDevOps711/test/assets/135973657/fe05df6d-7178-4944-8d08-590e7ffe2b3d)


43. Guvi-SG: ssh + HTTP --> Storage: 15GB--> Launch Instance.  ![43](https://github.com/GauravDevOps711/test/assets/135973657/475de5e0-cc8b-4d80-b098-702d7439bc62)
![43 1](https://github.com/GauravDevOps711/test/assets/135973657/3471fff4-8c34-40f7-be1c-4644ebcb6743)


44. Select the instance and clink on “Connect”. ![44](https://github.com/GauravDevOps711/test/assets/135973657/63ab534e-3446-403b-8a88-02b313d694cd)


45. Connect to instance using SSH client--> copy the “ssh -I “keypair” ubuntu@ip-address. compute-1.amazonaws.com” ![45](https://github.com/GauravDevOps711/test/assets/135973657/2a881798-87a1-4955-98d2-1481b6b245ad)


46. paste it in gitbash/vs-code editor where the “keypair.pem” is saved/downloaded ![46](https://github.com/GauravDevOps711/test/assets/135973657/6223edb9-cb24-44e9-9bb3-ce5445529e03)


47. sudo apt update && sudo apt upgrade -y ![47](https://github.com/GauravDevOps711/test/assets/135973657/aa79418b-15b0-4a1e-8184-768ced00ebcc)


48. mkdir SCP_DIR--> cd SCP_DIR--> pwd--> exit  ![48](https://github.com/GauravDevOps711/test/assets/135973657/68e46871-efe2-4d3a-98c2-7536235cd846)


49. Now will upload the localhost machine files to our EC2 instance using SCP(secure copy) in SCP_DIR--> “scp -i D:/Admin.pem -r C:/Users/yoyog/Downloads/devops-build ubuntu@ec2-44-202-191-64.compute-1.amazonaws.com: /home/ubuntu/SCP_DIR”  ![49](https://github.com/GauravDevOps711/test/assets/135973657/010d661e-0c90-4cfd-ab9d-5f0b8d3cda17)
![49 1](https://github.com/GauravDevOps711/test/assets/135973657/f48c985f-75a4-4061-a66b-2907fbf0d571)


50. Another way--> git clone https://github.com/sriram-R-krishnan/devops-build.git--> ls -la ![50](https://github.com/GauravDevOps711/test/assets/135973657/bd60cb7a-d497-42c0-8343-5b1ad2f607c2)


51. Once again login to EC2--> sudo apt install tree--> tree--> output: we have SCP_DIR & devops-build ![51](https://github.com/GauravDevOps711/test/assets/135973657/a2c0ffd7-e719-4ece-a99c-8613841e7696)


52. cat Dockerfile--> cat build.sh--> cat deploy.sh ![52](https://github.com/GauravDevOps711/test/assets/135973657/30f05c03-ff07-4f96-b91c-0e1a275f2b63)


53. Installing docker--> cd SCP_DIR/devops-build/ Script--> ls -la--> sudo ./docker.sh ![53](https://github.com/GauravDevOps711/test/assets/135973657/5afa4dac-2122-4442-8fe6-7bdc4db2713c)


54. Deployment of react application --> cd .. --> ls -la--> cat react_applicatio_deployment.sh--> sudo ./react_applicatio_deployment.sh. ![54](https://github.com/GauravDevOps711/test/assets/135973657/77407672-a456-49e0-bdbe-f62f5aa43549)


55. Application running on localhost:80 (i.e ec2 instance public_ip:80)--> Browser--> ec2_public_ip:80 i.e 44.202.191.64:80 ![55](https://github.com/GauravDevOps711/test/assets/135973657/b6ffc435-bbbc-415d-b4c5-dbece8b907ef)


56. Just to cross check using Mobile browser--> 44.202.191.64:80 --> WOKING GREAT. ![56](https://github.com/GauravDevOps711/test/assets/135973657/54cfe81d-cda8-4d4b-a0fc-c4d82e438d06)


</p>

<h3><b>MONITORING</b></h3><p>

Prometheus: An open-source monitoring and alerting toolkit designed for reliability and scalability. Prometheus excels at collecting and storing real-time metrics from various systems, allowing you to gain valuable insights into your applications and infrastructure.

Node Exporter: A Prometheus exporter for hardware and OS metrics. Node Exporter provides a wide array of system-level metrics, enabling you to monitor CPU usage, memory utilization, disk I/O, and network statistics of your server.

Grafana: A popular open-source platform for monitoring and observability. Grafana allows you to visualize Prometheus data through intuitive dashboards, making it easier to analyze trends, identify anomalies, and make data-driven decisions.

57. Goto official website--> https://prometheus.io/download/ --> copy the link. ![57](https://github.com/GauravDevOps711/test/assets/135973657/77dc8eb0-5385-4cda-a09c-c009a51ee227)


58. sudo wget <paste the url> --> ls -l --> tar -xvf <file name>  ![58](https://github.com/GauravDevOps711/test/assets/135973657/57bfdcd7-4be2-4ce5-a42b-d523a0e46bbb)


59. ls -l --> cd prometheus-2.45.3.linux-amd64 --> ls -l ![59](https://github.com/GauravDevOps711/test/assets/135973657/69834537-0248-403e-a6f7-d1b970b5ace9)


60. sudo nano prometheus.yml --> cat prometheus.yml ![60](https://github.com/GauravDevOps711/test/assets/135973657/d8e36c9c-07f3-4083-a5e1-f298cf2f8b25)


61. Now repeat the same steps for “alertmanager” , “node_exporter” ![61](https://github.com/GauravDevOps711/test/assets/135973657/ffffa089-bf62-44f6-8cd8-c41cad55accc)
![61 1](https://github.com/GauravDevOps711/test/assets/135973657/aca33882-8962-48bd-888a-8a7a8aac88f9)


62. Downloading Grafana from official site --> https://grafana.com/grafana/download ![62](https://github.com/GauravDevOps711/test/assets/135973657/b3ddb0c2-2dc5-4aa2-b1ec-d59d38bda023)


63. Paste the copied commands one by one.  ![63](https://github.com/GauravDevOps711/test/assets/135973657/62c20ea7-488b-4340-bebe-1ed35a4c190a)
![63 1](https://github.com/GauravDevOps711/test/assets/135973657/7c51d9cf-80e0-47f2-acf2-cda4c93503c9)
![63 2](https://github.com/GauravDevOps711/test/assets/135973657/2a0fc781-f8d4-406b-8fe8-0316ba2d5895)


64. Grafana running in background on port:3000 --> id & password: admin ![64](https://github.com/GauravDevOps711/test/assets/135973657/8ef42ea7-9161-4bbb-a760-4a83552b44af)


65. sudo ./ prometheus  &--> running in background on port: 9090 ![65](https://github.com/GauravDevOps711/test/assets/135973657/e3d7918a-fd1d-40f6-acdc-17830e989ddf)


66. All targets are UP and running. ![66](https://github.com/GauravDevOps711/test/assets/135973657/76a14f00-42f6-4704-bfa3-30decbe87ae3)


67. Prometheus Target ![67](https://github.com/GauravDevOps711/test/assets/135973657/02e59c3b-a9b4-406b-b8d6-73cdbf73552a)


68. Node exporter ![68](https://github.com/GauravDevOps711/test/assets/135973657/5bba8655-353a-48fa-b6b5-c8d8e00c39cf)
![68 1](https://github.com/GauravDevOps711/test/assets/135973657/9e467ccb-8d8a-4894-a39b-35fadca451b2)


69. Alert_Manager ![69](https://github.com/GauravDevOps711/test/assets/135973657/c0aea7ab-f1e4-4f04-b815-bf715216c1aa)
![69 1](https://github.com/GauravDevOps711/test/assets/135973657/e27c3286-5f36-4ea5-9427-c065ae7dece1)


70. Granfana Dashboard working great. ![70](https://github.com/GauravDevOps711/test/assets/135973657/0ec34954-3b17-4dff-83f1-80bc4689ca11)
![70 1](https://github.com/GauravDevOps711/test/assets/135973657/f9bed36c-a99e-45f4-b522-bbdbcc3ba298)
![70 2](https://github.com/GauravDevOps711/test/assets/135973657/5183837a-a14b-4296-8473-3a949b79d85d)
![70 3](https://github.com/GauravDevOps711/test/assets/135973657/9d660abf-190a-4c90-954e-4ffdbba770a2)

</p>
