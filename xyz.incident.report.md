---
marp: true
paginate: true
theme: default
backgroundColor: #ffffff
backgroundImage: url('./bg.png')
---

<!-- Cover Page -->

# Post-Mortem Analysis and Continuous Improvement in DevOps

### Group Presentation A2

#### Presented by: Group 2

##### Jan, 2025

 <!-- - [Link to Econestoga](https://conestoga.desire2learn.com/d2l/home/1345607) -->

<img src="https://img.icons8.com/?size=100&id=cM5Dj9gp1RPC&format=png&color=000000" width="120" alt="Cloud Icon" />

---

# Introduction

- **Objective**: Demonstrate how structured post-mortems lead to effective incident response and enhanced reliability
- **Agenda**:
  1. Company & Incident Overview
  2. Incident Response & Post-Mortem
  3. Root Causes & Lessons Learned
  4. Improvement Areas
  5. Recommended Corrective Actions
  6. Results & Impact

---

# Incident Overview

- **XYZ Inc.**: Leading cloud-based platform for enterprise clients
- **Incident**: Routine system upgrade led to a misconfiguration error
- **Impact**:
  - Critical features became inaccessible
  - High customer dissatisfaction
  - Immediate rollback required to restore service

<img src="https://img.icons8.com/?size=100&id=GKxp4Ns6HxNk&format=png&color=000000" width="80" alt="Incident Icon" style="float:right; margin-left:10px;" />

---

# Incident Response & Post-Mortem

**Immediate Response**

- Rolled back to a stable version
- Engaged on-call DevOps team for swift resolution

**Post-Mortem Steps**

1. Cross-functional review (Dev, Ops, Support)
2. Root cause analysis (deployment script misconfiguration)
3. Blameless approach [(learn more)](https://landing.google.com/sre/sre-book/chapters/postmortem-culture/) to foster trust and transparency

<img src="https://img.icons8.com/color/96/000000/fire-alarm.png" width="80" alt="Alarm Icon" style="float:right; margin-left:10px;" />

---

# Root Causes & Lessons Learned

**Root Causes**

1. Misconfiguration in deployment script
2. Inadequate change management
3. Communication gaps during the emergency

**Lessons Learned**

- Need comprehensive testing, including config checks
- Mandatory peer reviews and sign-offs
- Clear emergency communication protocols

<img src="https://img.icons8.com/fluency/96/000000/error.png" width="80" alt="Error Icon" style="float:right; margin-left:12px;" />

---

# Improvement Areas

<style>
.slide-content {
  font-size: 24px;
  display: flex
}
</style>

<div class="slide-content">
<div>

1. **Testing & Validation**

- Automated integration/end-to-end tests
- Regular “fire drills” to practice incident handling

2. **Change Management**

   - Peer reviews for production changes
   - Documented rollback procedures and approvals
   </div>

<div>

3. **Communication & Collaboration**

   - Defined escalation paths (using a [RACI model](https://en.wikipedia.org/wiki/Responsibility_assignment_matrix) for clarity)
   - Standardized incident channels (Slack, Teams)

4. **Kanban Board as a Service**

   - Centralized backlog/task management for cross-functional teams
   - Real-time visibility of work in progress and bottlenecks
   - More ↓

   </div>
   </div>

   <img src="https://img.icons8.com/color/96/000000/improvement.png" width="80" alt="Improvement Icon" style="float:right; margin-left:10px;" />

---

# Kanban: Making Work Flow Smoothly!

**🎯 How Kanban Helps Teams:**

- **See Everything at a Glance** 📋  
  Tasks are clearly visualized in columns (To Do → In Progress → Done).

- **Stay Focused** 🎯  
  Work-in-Progress (WIP) limits prevent overload and promote higher-quality results.

- **Find Bottlenecks Faster** 🚦  
  Easily spot where work is stuck, so you can resolve issues quickly.

- **Work Together Better** 🤝  
  Transparent workflows foster collaboration and ensure everyone’s on the same page.

---

# Recommended Corrective Actions

- **Infrastructure as Code** [(IaC)](https://docs.aws.amazon.com/whitepapers/latest/introduction-devops-aws/infrastructure-as-code.html) & **Policy-as-Code [Terraform]** [(PaC)](https://www.terraform.io/use-cases/enforce-policy-as-code)
  - Automate checks for misconfigurations
- **Canary or Blue-Green Deployments** [(Martin Fowler)](https://martinfowler.com/bliki/BlueGreenDeployment.html)
  - Test updates on a small subset to reduce risk
- **Enhanced Monitoring & Observability**
  - Proactive alerts, logs, and dashboards
- **Scheduled Retrospectives & Post-Mortems**
  - Continual improvement and knowledge sharing

<img src="https://img.icons8.com/color/96/000000/approval.png" width="80" alt="Approval Icon" style="float:right; margin-left:10px;" />

---

# Results & Impact

- **Reduced Downtime**: Faster rollback and detection
- **Improved Customer Satisfaction**: Fewer critical incidents and quicker resolutions
- **Stronger Team Dynamics**: Blameless culture & cross-functional collaboration
- **Key Metrics** [[DevOps Research and Assessment (DORA)]](https://cloud.google.com/blog/products/devops-sre/using-the-four-keys-to-measure-your-devops-performance):
  - **Deployment Frequency**
  - **Lead Time for Changes**
  - **Change Failure Rate**
  - **Time to Restore Service**

<img src="https://img.icons8.com/fluency/96/000000/combo-chart.png" width="80" alt="Chart Icon" style="float:right; margin-left:10px;" />

---

# Thank You

**Thank you for your time and attention!**

<img src="https://img.icons8.com/color/96/000000/handshake.png" width="100" alt="Handshake Icon" />
