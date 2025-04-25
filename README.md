My local machine (superlink) is Linux mint with python 3.12.3  and docker:

(federated_learning_venv) elena@elena-desktop /AT/flower/src/docker/distributed $ docker version
Client:
 Version:           26.1.3
 API version:       1.45
 Go version:        go1.22.2
 Git commit:        26.1.3-0ubuntu1~24.04.1
 Built:             Mon Oct 14 14:29:26 2024
 OS/Arch:           linux/amd64
 Context:           default

Server:
 Engine:
  Version:          26.1.3
  API version:      1.45 (minimum version 1.24)
  Go version:       go1.22.2
  Git commit:       26.1.3-0ubuntu1~24.04.1
  Built:            Mon Oct 14 14:29:26 2024
  OS/Arch:          linux/amd64
  Experimental:     false
 containerd:
  Version:          1.7.24
  GitCommit:        
 runc:
  Version:          1.1.12-0ubuntu3.1
  GitCommit:        
 docker-init:
  Version:          0.19.0
  GitCommit:        
(federated_learning_venv) elena@elena-desktop /AT/flower/src/docker/distributed $ docker-compose version
docker-compose version 1.29.2, build unknown
docker-py version: 5.0.3
CPython version: 3.12.3
OpenSSL version: OpenSSL 3.0.13 30 Jan 2024
(federated_learning_venv) elena@elena-desktop /AT/flower/src/docker/distributed $ 



My remote machine (supernode) is actually my laptop, also linux mint, python 2.7.18, docker:

elena@elena-laptop:/distributed$ docker version
Client: Docker Engine - Community
 Version:           28.0.4
 API version:       1.48
 Go version:        go1.23.7
 Git commit:        b8034c0
 Built:             Tue Mar 25 15:07:32 2025
 OS/Arch:           linux/amd64
 Context:           default

Server: Docker Engine - Community
 Engine:
  Version:          28.0.4
  API version:      1.48 (minimum version 1.24)
  Go version:       go1.23.7
  Git commit:       6430e49
  Built:            Tue Mar 25 15:07:32 2025
  OS/Arch:          linux/amd64
  Experimental:     false
 containerd:
  Version:          1.7.27
  GitCommit:        05044ec0a9a75232cad458027ca83437aae3f4da
 runc:
  Version:          1.2.5
  GitCommit:        v1.2.5-0-g59923ef
 docker-init:
  Version:          0.19.0
  GitCommit:        de40ad0
  
elena@elena-laptop:/distributed$ docker-compose version
docker-compose version 1.25.0, build unknown
docker-py version: 4.1.0
CPython version: 3.9.2
OpenSSL version: OpenSSL 1.1.1w  11 Sep 2023
elena@elena-laptop:~/distributed$ 

