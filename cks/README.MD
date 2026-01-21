# Certified Kubernetes Administrator (CKS)

Welcome! This folder is a curated set of resources I used to successfully prepare for the **CKS** certification. My goal is to help others navigate their own certification journey with practical, proven materials.

---

## 📖 About the Exam

The **Certified Kubernetes Security Specialist (CKS)** validates advanced skills in securing Kubernetes clusters and container-based applications across the entire lifecycle — from build and deployment to runtime.

This certification is designed for experienced Kubernetes practitioners who can confidently apply security best practices in real-world, production environments.

> **Prerequisite:** You must have *passed* the **Certified Kubernetes Administrator (CKA)** exam at any time prior to attempting the CKS exam. Your CKA certification does **not** need to be currently active at the time you sit the CKS exam.

**Exam Details:**
- **Format:** Performance-Based Exam  
- **Duration:** 120 minutes  
- **Passing Score:** 67%  

---

## 🧩 Exam Domains & Competencies

| Domain | Weight | Key Topics |
|--------|--------|-----------|
| Cluster Setup | 15% | Use network security policies to restrict cluster-level access, use CIS benchmark to review Kubernetes component security (etcd, kubelet, kube-dns, kube-api), set up Ingress with TLS, protect node metadata and endpoints, verify platform binaries before deploying |
| Cluster Hardening | 15% | Use RBAC to minimize exposure, manage service accounts carefully (disable defaults, minimize permissions), restrict access to Kubernetes API, upgrade Kubernetes to avoid vulnerabilities |
| System Hardening | 10% | Minimize host OS footprint, use least-privilege identity & access management, minimize external network access, apply kernel hardening tools (AppArmor, seccomp) |
| Minimize Microservice Vulnerabilities | 20% | Apply pod security standards, manage Kubernetes secrets, implement isolation techniques (multi-tenancy, sandboxed containers), enable Pod-to-Pod encryption (Cilium, Istio) |
| Supply Chain Security | 20% | Minimize base image footprint, understand the supply chain (SBOM, CI/CD, artifact repositories), secure the supply chain (permitted registries, artifact signing/validation), perform static analysis of workloads and images (Kubesec, KubeLinter) |
| Monitoring, Logging and Runtime Security | 20% | Perform behavioral analytics to detect malicious activities, detect threats in infrastructure/apps/networks/data/users/workloads, investigate attack phases and actors, ensure container immutability at runtime, use Kubernetes audit logs to monitor access |

---

## 📚 Study Materials

### 🎥 Video Courses

- [Certified Kubernetes Security Specialist (CKS) – KodeKloud](https://learn.kodekloud.com/courses/certified-kubernetes-security-specialist-cks)

### 🧪 Practice Tests

- [Ultimate Certified Kubernetes Security Specialist (CKS) Mock Exam Series - KodeKloud](https://learn.kodekloud.com/courses/ultimate-certified-kubernetes-security-specialist-cks-mock-exam-series)
- [CKS Simulator - killer.sh](https://killer.sh/cks) - Once enrolled you will receive access to an exam simulator


---

## 🏁 Final Words

The **CKS** is widely considered the most challenging Kubernetes certification. It tests real-world skills in securing clusters and workloads under time pressure, not just theoretical knowledge.

Passing the CKS demonstrates strong hands-on expertise in Kubernetes security and marks a major milestone in the Kubernetes certification journey.

---

## 📬 Contact

Feel free to reach out on LinkedIn if you have questions or want to connect:  
[LinkedIn Profile](https://www.linkedin.com/in/martin-hope-remote)
