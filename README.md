# ABOUT NOTEPAD

This is a markdown notepad for online articles and resources I like

# kubernetes

[forging optimal metallb config](https://patrick.easte.rs/post/2022/forging-optimal-metallb-config/)
[smarter device manager](https://gitlab.com/arm-research/smarter/smarter-device-manager) is a tool that lets you give k8s containers access to device drivers in a secure
manner. If you ever need a container to interface with something in the /dev directory, this is a great way to do it without being overpermissive with a cudgel like `--cap-add SYSADMIN`
[gcsfuse unprivileged](https://github.com/samos123/gke-gcs-fuse-unprivileged) is a good example of using gcsfuse in a secure manner

# gitops

[pulumi](https://www.pulumi.com/) is an obfuscation layer on top of terraform that enables you to stop writing HCL and start using an actual programming language
[gitversion](https://github.com/GitTools/GitVersion) is a useful tool for handling and incrementing versions automatically in a semver-like manner with first class parsing

# golang

[golang sprintf string formatting](https://gobyexample.com/string-formatting) is a good page reference for `%s` usage in `fmt.SprintF`
[hugo](https://gohugo.io/) a tool for generating static sites in go

# cloud

[cloud terminology glossary](https://lucid.app/lucidchart/13fde51a-271f-456a-b2b3-ef6869f9ee6a/view) is a good map of terminology between various cloud providers

# other

[Leslie Lamport's research papers](https://lamport.azurewebsites.net/pubs/pubs.html) on distributed systems is a really good resource for learning about the problem space of system distribution.
