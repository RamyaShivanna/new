node{
    stage('project4')
    {
        parallel(
            "job1":{
              git 'https://github.com/RamyaShivanna/new'   
             },
            "job2":{
                build job: 'pro1'
    }
            )
    }
}
