FROM Ubuntu

#CMD sleep 5
# when using CMD (without ENTRYPOINT)
# docker build -t ubuntu-sleeper .  -> build image
# dockr run ubuntu-sleeper          -> run image
# dockr run ubuntu-sleeper sleep 10 -> run and overide existing command

ENTRYPOINT["sleep"]
# when using ENTRYPOINT
# docker build -t ubuntu-sleeper .  -> build image
# dockr run ubuntu-sleeper 10       -> run image
CMD["5"]
# 5 -> will be appended to entry point instruction if u didn't specify any parameter in the cmd-line

# modify entrypoint during the run time
# docker run --entrypoint sleep2.0 ubuntu-sleeper 10 -> final command at startup will be "sleep2.0 10"



