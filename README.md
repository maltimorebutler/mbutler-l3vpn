# mbutler-l3vpn

The purpose of this repo is to provide a simple, readily available automated setup of a L3VPN topology.

The topology consists of 6x vSRX's forming 
- Two P nodes
- Two PE nodes
- Two CE nodes


                        P1  
                   /     |     \ 
CE5 --- PE3 ---          |        --- PE4 --- CE6
                   \     |     /  
                        P2    

Simply download the repo and initialize the topology with 'vagrant up'
