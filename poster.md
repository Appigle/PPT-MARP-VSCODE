---
marp: true
title: 'DevOps & Automation: Transforming Modern Software Development'
paginate: true
theme: gaia
backgroundColor: '#FFFFFF'
backgroundImage: url('./bg.png')
style: |
  /* Decrease title and subtitle font sizes */
  h1 {
    font-size: 1.5em;
  }
  h2 {
    font-size: 1.2em;
    line-height: 1;
  }
  h3 {
    font-size: 1.1em;
  }

  img:not(.devops):not(.thx):not(.no) {
    height: 80px;
    position: absolute;
    top: 60px;
    right: 60px;
  }

  img.thx {
    margin-left: 330px;
    margin-top: 50px;
  }
  .images {
  display: flex; 
  justify-content: center; 
  align-items: center;
  gap:1em;
  }
  img.devops {
    width: 700px;
  }
  img.think {
    width: 300px;
    border-radius: 40px;
  }

  /* Flex-based text blocks for better layout */
  .flex-col {
    display: flex;
    flex-direction: column;
    gap: 0.6em;
  }

  /* Larger bullet text for clarity */
  .emphasis-list {
    font-size: 36px;
    line-height: 1.4;
  }
  .emphasis-list2 {
    font-size: 26px;
    line-height: 1.3;
  }
---

<!-- Slide 1: Title Slide -->

# **DevOps & Automation**

### Transforming Modern Software Development

![DevOps Banner](https://img.icons8.com/?size=100&id=CLa3T2WlbrOP&format=png&color=000000)

###### Present by: Lei Chen - Jan, 2025

<div class="images">
  <img class="no think" src="./empower.png" width="100" alt="DevOps Illustration" />
  <img class="devops" src="./devops.png" width="100" alt="DevOps Illustration" />
</div>

---

<!-- Slide 2: Introduction -->

## Introduction

![Introduction Icon](https://img.icons8.com/dusk/80/idea.png)

<div class="flex-col">

- **Context**: Modern software development cycles are rapid and complex.
- **DevOps**: A cultural and technical approach that unites development and operations (Kim et al., 2016).
- **Objective**: Show how DevOps principles and automation increase **efficiency**, **reliability**, and **scalability**.
</div>

---

<!-- Slide 3: DevOps Principles (Slide 1) -->

## DevOps Principles

![Principles Icon](https://img.icons8.com/dusk/80/engineering.png)

### Culture of Collaboration

- Breaks silos between Dev, Ops, QA, and business teams.
- Shared ownership of quality and uptime fosters continuous improvement (Kim et al., 2016).

### Continuous Integration & Delivery

- Automated pipelines for builds, tests, and deployments.
- Frequent, small releases that reduce risk and enable fast feedback (Humble & Farley, 2010).

---

<!-- Slide 4: DevOps Principles (Slide 2) -->

## DevOps Principles (Continued)

![IaC Icon](https://img.icons8.com/dusk/80/engineering.png)

### Infrastructure as Code (IaC)

- Version-controlled, repeatable environment setup (Terraform, Ansible).
- Consistency and elimination of “drift” across environments (HashiCorp, n.d.).

### Monitoring & Feedback

- Automated alerts and dashboards catch issues early.
- Data-driven insights guide performance and security enhancements.

---

<!-- Slide 5: Role of Automation (Slide 1) -->

## Role of Automation in DevOps

![Automation Icon](https://img.icons8.com/?size=100&id=ebqYqqDXkhky&format=png&color=000000)

<div class="emphasis-list flex-col">

- **Streamlined Processes**

  - Automated testing (JUnit, Selenium)
  - CI/CD tools (Jenkins, GitLab CI)
  - Configuration management (Chef, Puppet)

- **Reliability & Scalability**
  - Reduced human error via scripted provisioning
  - Seamless resource scaling for changing demands
  </div>

---

<!-- Slide 6: Role of Automation (Slide 2) -->

## More on Automation

![Automation Icon](https://img.icons8.com/?size=100&id=ebqYqqDXkhky&format=png&color=000000)

<div class="emphasis-list flex-col">

- **Cost & Time Efficiency**

  - Fewer manual, repetitive tasks → Faster releases
  - Quicker rollbacks reduce downtime

- **Key Metrics**
  - Teams practicing DevOps often see >50% faster lead time and improved deployment frequency (Kim et al., 2016).
  - Enhanced visibility into systems reduces mean time to recovery (MTTR).
  </div>

---

<!-- Slide 7: Manual vs. Automated Comparison -->

## Manual vs. Automated System Administration

![Comparison Icon](https://img.icons8.com/dusk/80/compare.png)

<div class="emphasis-list2">

| **Aspect**                 | **Manual Tasks**                                          | **Automated Tasks**                                                                  |
| -------------------------- | --------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| **Efficiency**             | Repetitive, slow, error-prone                             | Scripts handle tasks quickly and consistently                                        |
| **Reliability**            | Human-dependent; prone to inconsistencies                 | Automated workflows ensure uniform, predictable execution                            |
| **Scalability**            | Requires significant manual intervention when load spikes | On-demand provisioning with IaC or container orchestration                           |
| **Maintenance & Overhead** | Periodic manual checks, updates, and patches              | Centralized scripts with version control for easy updates and rollbacks              |
| **Learning Curve**         | Straightforward but time-consuming in large-scale systems | Requires time to learn tools, but yields major efficiency and reliability advantages |

</div>

---

<!-- Slide 8: Summary & Key Takeaways -->

## Summary & Key Takeaways

![Summary Icon](https://img.icons8.com/?size=100&id=46721&format=png&color=000000)

- **DevOps** bridges culture and tooling to boost collaboration and software delivery.
- **Automation** underpins reliability, speed, and scalability.
- **CI/CD, IaC, and Monitoring** are pillars of effective DevOps adoption.
- Result: **Faster releases**, **reduced risks**, and a **continuous innovation cycle**.

---

<!-- Slide 9: Thank You -->

# Thank You

**Appreciate your time and attention!**

<img class='thx' src="./thx.png" width="600" alt="Handshake Icon" />

---

<!-- Slide 10: References (APA) -->

## References

![References Icon](https://img.icons8.com/dusk/80/books.png)

1. Humble, J., & Farley, D. (2010). _Continuous Delivery: Reliable Software Releases through Build, Test, and Deployment Automation._ Addison-Wesley.
2. Kim, G., Humble, J., Debois, P., & Willis, J. (2016). _The DevOps Handbook: How to Create World-Class Agility, Reliability, and Security in Technology Organizations._ IT Revolution Press.
3. HashiCorp. (n.d.). _Terraform Documentation._ [https://developer.hashicorp.com/terraform/docs](https://developer.hashicorp.com/terraform/docs)
4. Icons8. (n.d.). Icons8. https://icons8.com/icons

<!-- End of Presentation -->
