# ABOUT NOTEPAD

This is a markdown notepad for online articles and resources I like

# kubernetes

[forging optimal metallb config](https://patrick.easte.rs/post/2022/forging-optimal-metallb-config/)
[smarter device manager](https://gitlab.com/arm-research/smarter/smarter-device-manager) is a tool that lets you give k8s containers access to device drivers in a secure
manner. If you ever need a container to interface with something in the /dev directory, this is a great way to do it without being overpermissive with a cudgel like `--cap-add SYSADMIN`
[gcsfuse unprivileged](https://github.com/samos123/gke-gcs-fuse-unprivileged) is a good example of using gcsfuse in a secure manner
[the apk alpine linux package directory](https://pkgs.alpinelinux.org/packages) is good for browsing apk packages you can use in alpine containers
[kubelogin](https://github.com/int128/kubelogin) is a great utility for authenticating into kubernetes clusters via OIDC based auth
[kubernetes csi index](https://kubernetes-csi.github.io/docs/drivers.html)

# gitops

[pulumi](https://www.pulumi.com/) is an obfuscation layer on top of terraform that enables you to stop writing HCL and start using an actual programming language
[gitversion](https://github.com/GitTools/GitVersion) is a useful tool for handling and incrementing versions automatically in a semver-like manner with first class parsing
[gitster's blog](https://git-blame.blogspot.com/) is a good resource for interesting git behavior

# persistent data

[the genesis of kafka](http://notes.stephenholiday.com/Kafka.pdf) is a good whitepaper showing how kafka came to be

# golang

[golang sprintf string formatting](https://gobyexample.com/string-formatting) is a good page reference for `%s` usage in `fmt.SprintF`
[hugo](https://gohugo.io/) a tool for generating static sites in go
[go.work workspace syntax](https://www.sobyte.net/post/2022-01/go-multi-module/)

# cloud

[cloud terminology glossary](https://lucid.app/lucidchart/13fde51a-271f-456a-b2b3-ef6869f9ee6a/view) is a good map of terminology between various cloud providers

# Leslie Lamport

[Leslie Lamport's research papers](https://lamport.azurewebsites.net/pubs/pubs.html) on distributed systems are really good resources for learning about the problem space of system distribution in tech.

- [the founding of latex](https://lamport.azurewebsites.net/pubs/pubs.html#latex)
- [Time, Clocks and the Ordering of Events in a Distributed System](http://lamport.azurewebsites.net/pubs/time-clocks.pdf)

# comical items

[vim koans](https://blog.sanctum.geek.nz/vim-koans/)
[git koans](https://stevelosh.com/blog/2013/04/git-koans/)
