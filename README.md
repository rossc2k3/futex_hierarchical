# futex_hierarchical
Hierarchcical implementation of the futex hash table in linux, hashing first by user and then by address

#How to use
This was built on linux 5.15.0. Replace the futex.c file in your kernel with this one, add a config option for CONFIG_HIERARCHICAL_HASH and enable. Then, build your kernel as you normally would.
