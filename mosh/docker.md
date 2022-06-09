## linux
### command
apt: advance package tool
  - apt install
  - apt list
  - apt update

readfile:
  - cat
  - more

writefile:
  - &gt; (redirect)
  - &gt;&gt; (add to last line)

search:
  - grep (global regular expression print)
  - find -type f/d -name "f*"

env:
  - printenv
  - printenv PATH
  - echo $PATH
  - export DB_USER=banana (current session)
  - source ~/.bashrc

process:
  - ps (list all ative process)
  - sleep 100 & (backgroud process)
  - kill [pid] (kill process)

users:
  - useradd
  - adduser (iteractive adduser)
  - usermod
  - userdel

filePermission:
  - chmod [ugo]u+x deploy.sh (u -> user , g -> group, o -> other)

#### chaining command
  - mkdir test; cd test;
  - mkdir test && cd test;
  - mkdir test || "echo done"
  - ls /bin | head -n 5


