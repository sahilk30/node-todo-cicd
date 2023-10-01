# node-todo-cicd

Run these commands:


`sudo apt install nodejs`


`sudo apt install npm`


`npm install`

`node app.js`

Step1: Fork the repository. Step2: Generate the SSH keys for integrating your Jenkins project with your git repository. Use ssh-keygen command to create public and private key. Step3: Now, go to your GitHub account settings. Step4: Go to SSH and GPG keys, Add public key that we created using ssh-keygen and select key-type Authentication key. Step5: Go to your GitHub repository and click on Settings. Step6: Click on Webhooks and then click on Add webhook. Step7: In the ‘Payload URL’ field, paste your Jenkins environment URL. At the end of this URL add /github-webhook/. In the ‘Content type’ select: ‘application/json’ and leave the ‘Secret’ field empty. Step8: Now for Installing GitHub Integration plugin in Jenkins Step9: Open your jenkins dashboard. Step10: Click on the Manage Jenkins button on your Jenkins dashboard Step11: Click on Manage Plugins Step12: Install GitHub Integration plugin Step13: Configuring Jenkins: Step14: Create a jenkins job Step15: Create node-todo-app freestyle project Step16: In Configure, GitHub project URL write your project GitHub URL Step17: In Git, add credentials for Jenkins Step18: Click on the ‘Build Triggers’ tab and then on the ‘GitHub hook trigger for GITScm polling’. Step19: In the Execute shell run the application using Docker compose Step20: You will have to make a Docker Compose file for this Project Step21: After build you can check console output. Step22: Using docker ps command, you can see container is created. Step23: Browse public IP address with port no.8000

