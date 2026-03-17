---
layout: page
title: Architecture Case Study
subtitle: How This Website Is Built
icon: fas fa-diagram-project
order: 3
---

### Building a Modern, Secure and Simple Website

*This page explains the architecture and design decisions behind the platform.*

When building this personal website, I intentionally chose a **simple but resilient architecture**.

Rather than relying on complex infrastructure, servers, or databases — which often introduce unnecessary operational overhead — I opted to use an **architecture focused on simplicity, but with a good dose of reliability, and security**.

The design prioritises:

- **Security**
- **Reliability**
- **Minimal maintenance**
- **Simplicity**
- **Zero infrastructure cost**

This approach is widely used for **documentation platforms, technical blogs, and developer portfolios**, and demonstrates how effective solutions often come from **reducing complexity rather than adding it**.

---

## Reusing This Architecture

**The full source code for this website is available on GitHub.**

Beyond hosting my own site, this project also serves as a **small practical example of architecture thinking applied to a real system**.

Anyone interested can explore the repository to:

- understand the architectural decisions behind the platform  
- see how static-site architectures remove operational complexity  
- reuse the structure for their own site  
- learn how to publish a website using GitHub Pages  

**Source code:**  
<https://github.com/xpto2000/my-mainsite>

While the platform itself is intentionally lightweight, the same principles apply to larger systems: **simplicity, resilience, and thoughtful architectural choices**.

---

## High-Level Architecture

![High-Level Architecture]({{ site.baseurl }}/assets/img/diagram1.jpg)
---

## Technology Components

The site is built using a small set of well-established technologies:

- **Jekyll** – static site generator  
- **GitHub Pages** – hosting and global CDN  
- **GitHub** – source control and publishing workflow  
- **Markdown** – content authoring  
- **HTML / CSS** – presentation layer  

Together these components form a **simple and robust platform with no servers to manage**.

---

## Development Workflow

The site can be run **locally during development**, allowing changes to be tested before publishing.

Once changes are committed and pushed to the GitHub repository, **GitHub Pages automatically rebuilds and publishes the updated site**.

This keeps the workflow simple while ensuring updates can be safely validated before going live.

---

## Why This Architecture Works Well

This model offers several advantages:

**Security**  
No application servers, databases, or exposed APIs significantly reduce the attack surface.

**Reliability**  
GitHub Pages distributes the site globally through a CDN.

**Operational Simplicity**  
Publishing is done through Git — no deployments or server management required.

**Cost Efficiency**  
The entire platform operates with **zero hosting cost**.

---

## Final Thoughts

Sometimes the best architecture is the **simplest one that fits the problem well**.

Although much of my career has involved working with large and complex enterprise environments, I still enjoy examples like this. Building a small, clean solution that is **fit for purpose** reflects what good architecture should aim for.

Regardless of scale, systems benefit from **clear thinking, pragmatic design, and thoughtful architectural decisions**.

---

## Let’s Connect

If you are interested in discussing **architecture, platform design, or technology strategy**, or just want more details on how to do the same for your personal site, feel free to connect.

- **LinkedIn:**  
  <https://www.linkedin.com/in/jesuinoazevedo/>

- **Email:**  
  <mailto:jesuino.azevedo@gmail.com>