## To delete branches remotely and locally we do the following:-



    ## for dev branch it will be the following command
        #remotely
            --> git push origin :dev   
        #locally 
            --> git branch -d dev

    ## for test branch :-
        #remotely
            --> git push origin :test
        #locally
            --> git branch -d test


    
## Annotated tag vs  lightweight tag :-

    Annotated tag created by the following commmand:-
        git tag -a <tagname> -m "message" 
        ## we can add message here unlike lightweight which it relies on the commit message

    Lightweight tag created by the following command:-
        git tag <tagname>
        ## it takes the commit message as it's message

    
## when to use rebase ?
    we use rebase when we want to clean up commit history ,
     avoid unnecessary merge commits , 
     working on a team without overwriting history -> maintains straightforward commit log

## how to list tags ? 
    using the command -> git tag

## how to delete tag locally and remotely ?
    case remotely :
        git push origin --delete <tagname>
    
    case locally :
        git tag -d <tagname>


## adding image (Bonus)

![Git-logo](https://git-scm.com/images/logos/downloads/Git-Icon-Black.png)