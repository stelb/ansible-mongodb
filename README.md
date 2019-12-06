# mongodb cluster setup

that's just a start for learning mongodb

* testing with footloose
* only CentOS is supported right now

shardX <-> route0 <-> configX

    docker network create mongodb-cluster
    footloose create
    ansible-playbook -i inventory mongodb.yml
