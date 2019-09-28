# Miscellaneous

## Doc management
### Convert a mediawiki doc to odt
https://wiki.lpi.org/wiki/DevOps_Tools_Engineer_Objectives_V1  
View Source -> Copy&Paste in text objectives.md  
```
pandoc objectives.md -f mediawiki -t odt -s -o objectives.odt
```
### odt to github markdown
```
pandoc objectives.odt -f odt -t gfm -s -o objectives.md
```
## Documentation Links
### LPI Blog
Fabian Thorns posts:
[Getting Started](https://www.lpi.org/blog/2018/01/09/devops-tools-introduction-01-getting-getting-started-started)
[Modern Software Development](https://www.lpi.org/blog/2018/01/16/devops-tools-introduction-02-modern-software-development)
[Cloud Components and Platforms](https://www.lpi.org/blog/2018/01/23/devops-tools-introduction-03-cloud-components-and-platforms)
[Source Code Management](https://www.lpi.org/blog/2018/01/30/devops-tools-introduction-04-source-code-management)
[Continuous Delivery](https://www.lpi.org/blog/2018/02/06/devops-tools-introduction-05-continuous-delivery)
[Container Basics](https://www.lpi.org/blog/2018/02/13/devops-tools-introduction-06-container-basics)
[Container Orchestration](https://www.lpi.org/blog/2018/02/20/devops-tools-introduction-07-container-orchestration)
[Container Infrastructure](https://www.lpi.org/blog/2018/02/27/devops-tools-introduction-08-container-infrastructure)
[Machine Deployment](https://www.lpi.org/blog/2018/03/06/devops-tools-introduction-09-machine-deployment)
