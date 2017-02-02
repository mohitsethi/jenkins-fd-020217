# Jenkins

## Install Jenkins

- Install key
  ` wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo apt-key add -`

- Added repository
  `vim  /etc/apt/sources.list.d/jenkins.list`
  add deb https://pkg.jenkins.io/debian-stable binary/
  
- Update cache
  `apt-get update -y`

- Install Jenkins 
  `apt-get install jenkins -y`

- Access Jenkins web console at <ipaddress:port>

- Fetch initialAdministrator password
    `cat /var/lib/jenkins/secrets/initialAdminPassword`


## Building a Sample project
- Github repo: https://github.com/mohitsethi/maven-sample-app
