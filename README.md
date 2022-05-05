# rdfind
rdfind is a command to find and remove duplicate files(with the same content)
Following cmd will find and no actions will be taken:

    rdfind -dryrun true /home/user

To delete:

    rdfind -deleteduplicates true /home/user

# MFT from image 

    vol.py -f WIN-LQS146OE2S1-20201027-142607.raw --profile=Win7SP1x64 mftparser --output=body -D ~/aaaaa --output-file=grrcon_mft.body
    mactime -b grrcon_mft.body -d -z UTC |less   

# Mozzila credentials decrypt

https://github.com/lclevy/firepwd

# Res

https://wiki.sans.blue/#!Tools/WindowsEventLogsTable.md
https://www.mandiant.com/resources/greater-visibilityt
https://nasbench.medium.com/windows-forensics-analysis-tools-and-resources-b819c8b4b6b0
