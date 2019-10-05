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
1. [Getting Started](https://www.lpi.org/blog/2018/01/09/devops-tools-introduction-01-getting-getting-started-started)
2. [Modern Software Development](https://www.lpi.org/blog/2018/01/16/devops-tools-introduction-02-modern-software-development)
  * [Twelve-Factor Applications](https://12factor.net/)
3. [Cloud Components and Platforms](https://www.lpi.org/blog/2018/01/23/devops-tools-introduction-03-cloud-components-and-platforms)
4. [Source Code Management](https://www.lpi.org/blog/2018/01/30/devops-tools-introduction-04-source-code-management)
5. [Continuous Delivery](https://www.lpi.org/blog/2018/02/06/devops-tools-introduction-05-continuous-delivery)
6. [Container Basics](https://www.lpi.org/blog/2018/02/13/devops-tools-introduction-06-container-basics)
7. [Container Orchestration](https://www.lpi.org/blog/2018/02/20/devops-tools-introduction-07-container-orchestration)
8. [Container Infrastructure](https://www.lpi.org/blog/2018/02/27/devops-tools-introduction-08-container-infrastructure)
9. [Machine Deployment](https://www.lpi.org/blog/2018/03/06/devops-tools-introduction-09-machine-deployment)
10. [Ansible](https://www.lpi.org/blog/2018/03/13/devops-tools-introduction-10-ansible)
11. [Other Configuration Management Tools](https://www.lpi.org/blog/2018/03/20/devops-tools-introduction-11-other-configuration-management-tools)
12. [IT Operations and Monitoring](https://www.lpi.org/blog/2018/03/27/devops-tools-introduction-12-it-operations-and-monitoring)
13. [Log Management and Analysis](https://www.lpi.org/blog/2018/04/03/devops-tools-introduction-13-log-management-and-analysis)
14. [Taking the Test](https://www.lpi.org/blog/2018/04/10/devops-tools-introduction-14-taking-test)
