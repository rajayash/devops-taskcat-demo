# devops-taskcat-demo - this github repo is private
For Demo, clone and run test run taskcat:-

    - sudo yum -y update
    - python --version
    - curl -O https://bootstrap.pypa.io/get-pip.py
    - python3 get-pip.py --user
    - sudo pip install --upgrade pip
    - pip3 install taskcat --user
    - taskcat --version
    - cd ~/environment
    - git clone https://github.com/rajayash/devops-taskcat-demo.git
    - cd devops-taskcat-demo/
    - run the command "taskcat test run"
    - aws cloudformation create-stack --stack-name pipeline-taskcat --capabilities CAPABILITY_NAMED_IAM --disable-rollback --template-body file:///home/ec2-user/environment/devops-taskcat-demo/pipeline-taskcat.yml --parameters ParameterKey=GitHubUser,ParameterValue=rajayash ParameterKey=GitHubRepo,ParameterValue=devops-taskcat-demo

=================================================
Repository -  demo CI/CD, Cloudformation, Taskcat examples. 
