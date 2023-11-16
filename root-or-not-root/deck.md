---
marp: true
title: Born to be Root
description: 
theme: uncover
paginate: true
_paginate: false
---

![bg](./assets/gradient.jpg)

# <!--fit--> Born to be Root

How we can protect our Infrastructure

<!-- Esto hace referencia a nuestra  -->

---
### Architecture of Docker

Share kernel Host

![bg right auto](assets/vm's-containers.png)

---
#### 0 - Keep Host and Docker up to date

---
#### 1 - Set a user

![bg right auto](assets/set-user-test.png)

---

![bg 100%](assets/set-user-show.png)

---
#### 2 - Limit resources

![bg right 100%](assets/set-limits.png)

---
#### 3 - Set filesystem and volumes to read-only

![bg right 100%](assets/set-filesystem.png)

---
#### 4 - Use static analysis tools

![bg right 100%](assets/tryvi.png)

---


![bg 100%](assets/trivy-adoptopenjdk.png)

---
#### 5 - Lint the Dockerfile at build time

---

## Demo Time
---
#### Review 
* Keep Host and Docker up to date
* Set a user
* Limit resources
* Set filesystem and volumes to read-only
* Use static analysis tools
* Lint the Dockerfile at build time

---

Thanks!  👋