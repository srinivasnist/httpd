    node{ 
              stage('SCM') {
                 
                        git 'https://github.com/srinivasnist/httpd.git'
            
        }
              stage('Ansible Playbook for httpd') {
                      sh 'ansible-playbook -i hosts aws_create_instance2.yml'
           
        }
    }

