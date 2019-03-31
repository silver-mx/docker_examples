FROM jenkins/jenkins:lts
# if we want to install via apt
USER root
# Needed for ruby
RUN apt-get update && apt-get install -y curl bison build-essential zlib1g-dev libssl-dev libreadline-gplv2-dev libxml2-dev git-core libsqlite3-dev nodejs
#RUN apt-add-repository -y ppa:rael-gc/rvm 
#RUN apt-get update && apt-get install -y rvm
# drop back to the regular jenkins user - good practice
USER jenkins
