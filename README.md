# Consul Template
Dockerized consul-template based on tiny alpine linux. This weighs in at about 16mb!

Theres a volume mounted at ```/consul-template``` so that you can use this container as a side kick for another container using ```--volumes-from```.
