# rdfind
rdfind is a command to find and remove duplicate files(with the same content)
Following cmd will find and no actions will be taken:

    rdfind -dryrun true /home/user

To delete:
    rdfind -deleteduplicates true /home/user
