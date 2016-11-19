Moore's law, has spoiled us, instead of inward looking we say Heil Moore's law.

I remmber, the Hadoop wave was buy less expensive hardware and today whats a comodity server
[Here are the recommended specifications for DataNode/TaskTrackers in a balanced Hadoop cluster:](http://blog.cloudera.com/blog/2013/08/how-to-select-the-right-hardware-for-your-new-hadoop-cluster/)
* 12-24 1-4TB hard disks in a JBOD (Just a Bunch Of Disks) configuration
* 2 quad-/hex-/octo-core CPUs, running at least 2-2.5GHz
* 64-512GB of RAM
* Bonded Gigabit Ethernet or 10Gigabit Ethernet (the more storage density, the higher the network throughput needed)
___Seriously ????___

If thats not enough [Our findings suggest SSD has higher performance compared to HDD-11](http://blog.cloudera.com/blog/2014/03/the-truth-about-mapreduce-performance-on-ssds/)

Does it stops there, no; there is something we could do networking as these are super chatty, hence lets bring in [InfiniBand](https://www.sandisk.in/content/dam/sandisk-main/en_us/assets/resources/enterprise/white-papers/evaluating-impact-of-ssds-and-infiniband-in-hadoop-cluster.pdf)

[World is not enough (007), you what CPU is not enough bring in GPU ](http://www.nvidia.com/object/data-science-analytics-database.html)

Now this is our simple and humble less expensive comodity server ;)

I think its time, we either look for something else or crush the big-data stack; there are new buds in form or kudu... but I feel crushing the stack is the next logical step. What if we make NN,RM,DN run as single process inside a unikernel. In an year or so the unikernel will be a viable tech and if we are ready by then the current performance number will be microscopic.

This project is a humble start towards that direction; [Where no man has gone before](https://en.wikipedia.org/wiki/Where_no_man_has_gone_before)
