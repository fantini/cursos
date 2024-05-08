Download the Jenkins Docker Image
 - docker pull jenkins/jenkins

Configurando as permissões de acesso ao diretório jenkins_home
 - $ sudo chown 1000:1000 jenkins_home -R

Inicializando o jenkins
 - $ sudo docker-compose up -d

Acessando os logs do container jenkins
 - $ sudo docker logs -f jenkins

Acessando o console do container
 - $ sudo docker exec -ir jenkins bash