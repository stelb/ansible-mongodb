# mongodb cluster setup

that's just a start for learning mongodb

* testing with footloose
* only CentOS is supported right now

shardX <-> route0 <-> configX

## Status

config servers are created

## Usage

    docker network create mongodb-cluster
    footloose create
    ansible-playbook -i inventory mongodb.yml
