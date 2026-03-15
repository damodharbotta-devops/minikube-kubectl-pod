# minikube-kubectl-pod (class 1)

History:

    1  yum install git -y
    2  git clone https://github.com/damodharbotta-devops/minikube-kubectl-pod.git
    3  ll
    4  git checkout main
    5  ll
    6  cd minikube-kubectl-pod
    7  ll
    8  git branch -a
    9  ll
   10  vim minikube
   11  ll
   12  cd minikube
   13  ll
   14  git pull minikube-kubectl-pod
   15  git pull origin minikube-kubectl-pod
   16  ll
   17  cd ,,/
   18  cd ../
   19  ll
   20  cd minikube-kubectl-pod
   21  ll
   22  touch pod.yml
   23  ll
   24  vim pod.yml
   25  kubectl create -f pod.yml
   26  ll
   27  vim pod.yml
   28  ll
   29  vim minikube
   30  git push pod.yml
   31  git add *
   32  git commit -m "pod file added" .
   33  ll
   34  git push origin main
   35  git pull origin main
   36  git push origin main
   37  cd ../
   38  curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"
   39  ll
   40  chmod +x kubectl
   41  mv kubectl /usr/local/bin
   42  ll
   43  kubectl version
   44  curl -LO https://github.com/kubernetes/minikube/releases/latest/download/minikube-linux-amd64
   45  sudo install minikube-linux-amd64 /usr/local/bin/minikube && rm minikube-linux-amd64
   46  minikube start --driver=docker --force
   47  minikube version
   48  minikube status
   49  minikube version
   50  minikube status
   51  yum install docker -y && systemctl start docker
   52  minikube start --driver=docker --force
   53  minikube status
   54  ll
   55  cd
   56  cd minikube-kubectl-pod
   57  ll
   58  history
   59  kubectl create -f pod.yml
   60  ll
   61  touch kubectl
   62  ll
   63  vim kubectl
   64  git add*
   65  git add *
   66  git commit -m "kubectl installation commands" .
   67  git push origin main
   68  ll
   69  rm -rf minikube
   70  ll
   71  git push origin main
   72  git pull origin main
   73  git push origin main
   74  ll
   75  git checkout main
   76  ll
   77  git pull origin main
   78  history


