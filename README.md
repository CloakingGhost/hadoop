# hadoop

vi ~/.bashrc 제일아래에 추가
export JAVA_HOME=$(dirname $(dirname $(readlink -f $(which java))))  
export PATH=$PATH:$JAVA_HOME/bin  
export CLASS_PATH=.:$JAVA_HOME/lib/tools.jar  
export HADOOP_HOME=/home/user1/hadoop-3.2.4  
export PATH=$PATH:$HADOOP_HOME/bin:$HADOOP_HOME/sbin  
