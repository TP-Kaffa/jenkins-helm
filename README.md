# jenkins-helm

## 개발 환경 설정

### k8s 설치

### helm 설치

- helm repo 추가
  ```
  helm repo add jenkins https://charts.jenkins.io
  helm repo update
  ```

## script 실행

1. install_jenkins.sh 실행, jenkins 설치
2. get_all_jenkins.sh 실행, k8s object 확인
3. port_forward_jenkins.sh 실행, jenkins 서비스 port-forward 추가
4. helm_status_jenkins.sh 실행, password secret 확인 명령어 확인
5. 필요에 따라 파이프라인 작성

> 출처
>
> - https://medium.com/@jyson88/kubernetes-helm-jenkins-%EC%82%AC%EC%9A%A9-a4cb11e3b612
