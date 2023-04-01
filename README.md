# ABOUT NOTEPAD

This is a markdown notepad for online articles and resources I like. I usually write down things that are profound that I've gotten a lot of value out of

# kubernetes

[forging optimal metallb config](https://patrick.easte.rs/post/2022/forging-optimal-metallb-config/)
[smarter device manager](https://gitlab.com/arm-research/smarter/smarter-device-manager) is a tool that lets you give k8s containers access to device drivers in a secure
manner. If you ever need a container to interface with something in the /dev directory, this is a great way to do it without being overpermissive with a cudgel like `--cap-add SYSADMIN`
[gcsfuse unprivileged](https://github.com/samos123/gke-gcs-fuse-unprivileged) is a good example of using gcsfuse in a secure manner
[the apk alpine linux package directory](https://pkgs.alpinelinux.org/packages) is good for browsing apk packages you can use in alpine containers
[kubelogin](https://github.com/int128/kubelogin) is a great utility for authenticating into kubernetes clusters via OIDC based auth
[kubernetes csi index](https://kubernetes-csi.github.io/docs/drivers.html)
[falco]() is a utility for container runtime scanning

## kubecon

| talk                                                                      | link                                        | summary |
| ------------------------------------------------------------------------- | ------------------------------------------- | ------- |
| My Container Image has 500 Vulnerabilities, Now What                      | https://www.youtube.com/watch?v=1fO_xSnwDPg |         |
| unsecured kubernetes in the wild                                          | https://www.youtube.com/watch?v=VGv32or8nmU |         |
| Kubernetes Exposed! Seven of Nine Hidden Secrets That Will Give You pause | https://www.youtube.com/watch?v=JBbVTmrZ45E |         |
| Exploiting a Slightly Peculiar Volume Configuration                       | https://www.youtube.com/watch?v=V8JXexaLGCU |         |
| How Kubernetes Components Communicate Securely In Your Cluster            | https://www.youtube.com/watch?v=bXnVI_hUAbk |         |

# infosec

https://overthewire.org

# gitops

[pulumi](https://www.pulumi.com/) is an obfuscation layer on top of terraform that enables you to stop writing HCL and start using an actual programming language
[gitversion](https://github.com/GitTools/GitVersion) is a useful tool for handling and incrementing versions automatically in a semver-like manner with first class parsing
[gitster's blog](https://git-blame.blogspot.com/) is a good resource for interesting git behavior

# persistent data

- [the genesis of kafka](http://notes.stephenholiday.com/Kafka.pdf) is a good whitepaper showing how kafka came to be
- [a whitepaper on spanner's availability](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/45855.pdf) is a good article to read about how google manages their own georedundant database
- [the genesis of postgres](https://dsf.berkeley.edu/postgres-v4r2/postgres.faq) from berkley is absolutely worth reading
- [data integrity during network disruptions in postgres](https://aphyr.com/posts/282-call-me-maybe-postgres)
- [mongodb's reputation in 2018](https://news.ycombinator.com/item?id=16385701)
- [the secret lives of data](http://thesecretlivesofdata.com) is a good visualization of how RAFT based quorum works
- [raft's whitepaper](https://raft.github.io/raft.pdf)

# golang

[golang sprintf string formatting](https://gobyexample.com/string-formatting) is a good page reference for `%s` usage in `fmt.SprintF`
[hugo](https://gohugo.io/) a tool for generating static sites in go
[go.work workspace syntax](https://www.sobyte.net/post/2022-01/go-multi-module/)

# cloud

[cloud terminology glossary](https://lucid.app/lucidchart/13fde51a-271f-456a-b2b3-ef6869f9ee6a/view) is a good map of terminology between various cloud providers

# people

## Leslie Lamport

[Leslie Lamport's research papers](https://lamport.azurewebsites.net/pubs/pubs.html) on distributed systems are really good resources for learning about the problem space of system distribution in tech.

- [the founding of latex](https://lamport.azurewebsites.net/pubs/pubs.html#latex)
- [Time, Clocks and the Ordering of Events in a Distributed System](http://lamport.azurewebsites.net/pubs/time-clocks.pdf)
- [the part-time parlaiment](https://lamport.azurewebsites.net/pubs/pubs.html#lamport-paxos) is a good paper to read on the genesis of paxos

## Eric Brewer

[Eric Brewer's research](https://people.eecs.berkeley.edu/~brewer/) on distributed systems in the context of data is good

- [towards robust distributed systems](https://sites.cs.ucsb.edu/~rich/class/cs293-cloud/papers/Brewer_podc_keynote_2000.pdf) is a good powerpoint to go through on the genesis of wider distributed systems and the problems you face with large datasets and consistency. They go over the origin of the CAP theorem in this talk. I wish there was a video of it...
- [a follow-up on the cap theorem](https://www.infoq.com/articles/cap-twelve-years-later-how-the-rules-have-changed/) is a good article worth reading about the follow-up on CAP theorem and distributed data design limitations
- [the definition of a partition](<https://en.wikipedia.org/wiki/Partition_(database)>) is important for understanding the above articles

## Kyle Kingsbury

Kyle Kingsbury tests databases and refutes claims about data integrity and tests distributed data systems. He has some great talks and an excellent series called jepsen.

[anna concurrenina](https://www.youtube.com/watch?v=eSaFVX4izsQ) is an excellent talk illustrating how a lot of modern databases fail to meet the standards they advertise when it comes to network disruptions/partitions and distributed systems issues

# comical items

[vim koans](https://blog.sanctum.geek.nz/vim-koans/)
[git koans](https://stevelosh.com/blog/2013/04/git-koans/)
