    node{ 
              stage('SCM') {
                  steps {
                        git 'https://github.com/srinivasnist/httpd.git'
            }
        }
              stage('Ansible Playbook for httpd') {
                  steps {
                      sh 'ansible-playbook -i hosts aws_create_instance2.yml'
            }
        }
    }

