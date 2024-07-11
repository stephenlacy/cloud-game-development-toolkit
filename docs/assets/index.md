# Assets

**Assets** are reusable scripts, pipeline definitions, Dockerfiles, Packer templates, and other resources that might prove useful or are dependencies of any of the modules. Each asset contains its own documentation as a `README.md` file.

!!! info
    **Don't see an asset listed?** Create a [feature request](https://github.com/aws-games/cloud-game-development-toolkit/issues/new?assignees=&labels=feature-request&projects=&template=feature_request.yml&title=Feature+request%3A+TITLE) for a new asset or learn [how to contribute new assets to the project below](#Contribute new Assets to the Cloud Game Development Toolkit)

| Asset Type | Description |
| :--------------------------------------------------------------- | :- |
| [:simple-packer: __Packer Templates__](./packer.md)              | Packer templates provide an easy way to build machine images for commonly used game dev infrastructure. Currently the project includes Packer templates for UE5 build agents for Linux and Windows, as well as a Packer template for building a Perforce Helix Core version control AMI. |
| [:simple-jenkins: __Jenkins Pipelines__](./jenkins-pipelines.md) | Jenkins Pipelines for common game dev automation workflows |
| [:simple-ansible: __Ansible Playbooks__](./playbooks.md)         | Automation scripts for reusable system level configurations. |
| [:simple-docker: __Dockerfiles__](./dockerfiles.md)              | Dockerfiles for creating Docker images of commonly used game dev infrastructure. These are primarily used in scenarios where there aren't openly available pre-built images that address a use case, or significant customization is needed that warrants building an image |