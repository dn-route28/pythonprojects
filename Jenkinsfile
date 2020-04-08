pipeline {
    agent 
    stages {
          stage("Create import files") {
              steps {
                  sh """
                      touch important file1
                      touch important file2
                      touch important file3
                    """
              }
          }
          stage("Run helloworld") {
              steps {
                  sh """
                        python helloworld.py
                   """
              } //steps     
          } //stage
          stage("Run conditionals.py") {
              steps {
                  sh """
                          python conditionals.py
                     """  
                } //steps
            } //stage
    } //stages
} //pipeline
              