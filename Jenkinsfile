properties( [
   parameters([
     choice(name: 'Environment',
           choices [
            'dev',
            'qa',
            'non-prod',
            'prod'           
           ],
            description: 'select deployment Environment '
      ),
      
    choice(name: 'select Repository URL ',
           choices [
            'git',
            'bitbucket',
           
           ],
            description: 'select Repository URL '
      ), 
      string(name: 'Git and bitbucket  Repository URL',
             defaultValue: '',
            description: 'Git and bitbucket enter Repository URL' 
       ),
           choice(name: 'Branch',
           choices [
            'dev',
            'qa',
            'non-prod',
            'prod'           
           ],
            description: 'select deployment Branch name '
      ),
      booleanParam( name: 'dry_run',
           defaultValue: '',
            description: 'is this dry run or actual update' 
       ),   
            booleanParam( name: 'normal run',
           defaultValue: '',
            description: 'is this normal run or actual update' 
       )
      
    
 ])
 ])
