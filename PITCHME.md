---
marp: true
title: "ScienceMesh: An Interoperable Federation of EFFS services for European Open Science Cloud"
description: "ScienceMesh: An Interoperable Federation of EFFS services for European Open Science Cloud"
theme: sciencemesh
paginate: true
_paginate: false
footer: CC BY 4.0
---

<!-- _class: title-slide -->

![height:180px](assets/sciencemesh.svg)
## An Interoperable Federation of EFFS services for European Open Science Cloud

### Pedro Ferreira (CERN)

---

## The Idea

![bg right horizontal 70%](assets/sciencemesh.svg)
![bg right vertical 50%](assets/cs3mesh4eosc.png)

 * **Decentralized** mesh of EFSS nodes
 * Based on **Open Standards** and **Open Source**
 * **Interoperable Platform** to easily share and deploy applications and components

---

![width:800px](assets/layer_cake.png)

---

## Objectives

![bg right 50%](assets/sciencemesh-alt.svg)

 * **Application platform** for distributed collaboration
 * **Federated** research space for Europe (and the world!)
 * Leveraging the potential of the **CS3 Community**

---

## EFSS Integration

### Objectives

 * Platform-specific plugins;
 * Implement "Invite workflow" from EFSS system;
 * A User Interface which feels seamless;

---

## EFSS Integration

![bg right 80%](assets/mockups-collab.png)

* Nextcloud
  - outsourced to PonderSource (alpha stage);
  - UX and backend;
* ownCloud
  - OCIS - using REVA, still UX work to do;
  - version 10 - backport by PonderSource (March 2022);
* Seafile
  - under discussion

---
## Federation

![bg vertical cover right:55%](assets/dashboard.png)

* Established Roadmap for Trust
* Federated Identity
* Registry (GOCDB, Mentix)
* Monitoring (Prometheus, Grafana)
* Security
* **Up and running mid-2021!**


---
<!-- _footer: 'Photo by Markus Spiske from [Pexels](https://www.pexels.com/photo/creative-dark-internet-designer-6190327/)' -->

![bg vertical cover right:60%](assets/code.jpg)
## Applications

---
<!-- _footer: 'Logos are property of the respective projects' -->

![bg width: 60%](assets/apps_grouped.png)

---
<style scoped>
  img {
    width: 200px !important;
    display: inline-block;
  }
</style>
Data Science / Data Transfers

![](assets/proto-data-science.svg) ![](assets/proto-data-transfers.svg)
![](assets/proto-md-editor.svg) ![](assets/proto-sciebords.svg)

Markdown Editor / ScieboRDS

---

![bg left:30% contain](assets/proto-data-science.svg)
# Data Science Environment

JupyterHub-based Notebook Editing

![width:400px](assets/proto-data-science.png)

https://github.com/sciencemesh/cs3api4lab

---

![bg left:30% contain](assets/proto-sciebords.svg)
# Open Data Workflow

ScieboRDS + Describo Online

![width:500px](assets/proto-sciebords.png)

https://github.com/Sciebo-RDS/port-reva
https://github.com/Arkisto-Platform/describo-online

---

![bg left:30% contain](assets/proto-md-editor.svg)
# Markdown Editor

CodiMD from you EFSS

![width:500px](assets/proto-md-editor.png)

https://github.com/cs3org/wopiserver/blob/master/src/bridge/readme.md

---

<!-- _footer: '' -->

![bg vertical cover right:50%](assets/cogs.jpg)

## Synergies

 * Conversations with several vendors about new features and integrations
   - e.g. sponsoring developments in **Rclone**
 * Open Data partnership involving UTS, PARADISEC (AU), Zenodo
   - Based on WWU's **Sciebo RDS** and UTS's **Describo**

---
<!-- _footer: '' -->

![width:700px](assets/peter.png)

Peter Heiss, Lennart Hofeditz -  [Progress of Sciebo Research Data Services](https://indico.cern.ch/event/970232/contributions/4157920/)

---
<!-- _footer: '' -->

![width:700px](assets/marco.png)

Marco La Rosa, Peter Sefton -  [Describo and RO-Crate - the FAIR data research helpers](https://indico.cern.ch/event/970232/contributions/4158369/)


---

**You app/service could be the next one!**

---
## Cubbit
<!-- _footer: '' -->

![bg right cover vertical](assets/cubbit.webp)

 * CS3Mesh on a physical device!
 * Integration with CS3APIs/IOP


*Gianluca Granero - [Cubbit Hive: the private distributed cloud](https://indico.cern.ch/event/970232/contributions/4158359)*

---
## Communications
<!-- _footer: '© Copyright 2020-2021 CS3MESH4EOSC Project Partners' -->

![bg left:45% horizontal](assets/project_site.png)
![bg left vertical](assets/mesh_site.png)

 * **Project** [website](https://cs3mesh4eosc.eu) and branding
   - Newsletters, [@cs3org](https://twitter.com/cs3org) and others
 * **ScienceMesh** [website](https://sciencemesh.io) and branding
   - [Documentation](https://developer.sciencemesh.io) on how to join
 * **Events** such as this one!

---
## Roadmap

![bg left 50%](assets/sciencemesh-proto.png)

 1. **mid-2021** - Consolidation of Proof of Concept (user sharing)
 2. **early 2022** - Second prototype - sharing with groups of users
 3. **late 2022** - Production infrastructure, applications fully integrated

---
## Conclusion

 * Lots of things for you to **discover**
 * ... but it's also about **your** ideas
 * **We hope you will like the workshop!**
