#########  this is for cmd 
# FROM ubuntu:latest
# CMD [ "echo", "this is from cmd docker file" ]
 

#  ######### 1 this is for ENTRYPOINT and to check overide cmd
# FROM ubuntu:latest
# CMD [ "this is from cmd docker file" ]
# ENTRYPOINT [ "echo", "this is from ENTRYPOINT" ]

 ######### 2 this is for ENTRYPOINT and to check overide cmd and cmd act as parameter to entrypoint
FROM ubuntu:latest
CMD [ "-l", "-rt" ]
ENTRYPOINT [ "ls" ]