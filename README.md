<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0d0d,100:2b2b2b&height=120&section=header&animation=fadeIn" width="100%" alt="Header banner" />

  <p><b>Backend & Systems Engineer</b> with an <b>architecture-first mindset</b>.</p>

  <p>
    <i>
      I design and build software across the stack,
      from low-level implementation details to distributed system boundaries.
    </i>
  </p>

  <p>
    <i>
      Interested in concurrency, distributed systems, networking,
      infrastructure, and performance engineering.
    </i>
  </p>

  <p>
    <i>
      Currently exploring Vulkan and eBPF,
      with a focus on systems-level behavior and observability.
    </i>
  </p>

  <p>
    <i>
      <a href="#contact">↓ Contact</a>
    </i>
  </p>
  
</div>

---

### Profile & Analytics

<table align="center" border="0" cellpadding="0" cellspacing="0" width="100%">
  <tr>
    <td width="50%" valign="top">

### Engineering Focus

<ul>
  <li>
    <b>Backend Systems:</b>
    Java, Spring Boot, API design, concurrency, persistence, and service boundaries.
  </li>
  <li>
    <b>Distributed Systems:</b>
    service communication, routing, consistency, fault isolation, and scalability trade-offs.
  </li>
  <li>
    <b>Systems Programming:</b>
    C, C++, Rust, memory management, low-level tooling, and system behavior.
  </li>
  <li>
    <b>Infrastructure:</b>
    Linux, containers, Kubernetes, CI/CD, object storage, and edge infrastructure.
  </li>
  <li>
    <b>Performance:</b>
    concurrency models, CPU/memory behavior, I/O, profiling, and bottleneck analysis.
  </li>
</ul>

</td>

<td width="50%" valign="top" align="center">


### GitHub Activity

<br>

<img src="github-metrics.svg" alt="GitHub Metrics" width="100%">

</td>


  </tr>
</table>

<br>

---

### Selected Engineering Work

<table width="100%" border="0" cellpadding="0" cellspacing="0">
  <tr>
    <td width="45%" valign="top" align="center">
      <br>

  <a href="https://github.com/spm-ecosystem/site-package-manager">
    <img src="spm-repo.svg" alt="SPM Repository" width="100%" />
  </a>
</td>

<td width="55%" valign="top">

### SPM — Site Package Manager

A package management ecosystem built around a custom C++ parser,
edge infrastructure, and distributed package storage.

<br>

<img src="https://img.shields.io/badge/-C%2B%2B17-000000?style=flat-square&logo=cplusplus&logoColor=white" alt="C++17" />
<img src="https://img.shields.io/badge/-React%2018-000000?style=flat-square&logo=react&logoColor=61DAFB" alt="React 18" />
<img src="https://img.shields.io/badge/-Cloudflare%20Workers-000000?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare Workers" />
<img src="https://img.shields.io/badge/-R2-000000?style=flat-square&logo=cloudflare&logoColor=white" alt="R2" />
<img src="https://img.shields.io/badge/-GitOps-000000?style=flat-square&logo=git&logoColor=white" alt="GitOps" />

<h4>Architecture</h4>

<ul>
  <li>
    <b>Compiler:</b>
    C++17 lexer/parser producing structured package manifests.
  </li>
  <li>
    <b>Edge Gateway:</b>
    Cloudflare Worker handling request validation and package publishing.
  </li>
  <li>
    <b>Write Path:</b>
    <code>spm-cli → GitOps → Worker → R2</code>
  </li>
  <li>
    <b>Read Path:</b>
    <code>Extension → Local Cache → Edge Cache → R2</code>
  </li>
</ul>


</td>


  </tr>

  <tr>
    <td colspan="2">
      <br>
      <hr>
      <br>
    </td>
  </tr>

  <tr>
    <td width="45%" valign="top" align="center">
      <br>

  <a href="https://github.com/watashi-00/gatebridge">
    <img src="gatebridge-repo.svg" alt="GateBridge Repository" width="100%" />
  </a>
</td>

<td width="55%" valign="top">

### GateBridge

A lightweight Java gateway focused on service routing,
concurrency, and cluster communication.

<br>

<img src="https://img.shields.io/badge/-Java-000000?style=flat-square&logo=java&logoColor=white" alt="Java" />
<img src="https://img.shields.io/badge/-Project%20Loom-000000?style=flat-square" alt="Project Loom" />
<img src="https://img.shields.io/badge/-Virtual%20Threads-000000?style=flat-square" alt="Virtual Threads" />
<img src="https://img.shields.io/badge/-TUI-000000?style=flat-square" alt="TUI" />

<h4>Architecture</h4>

<ul>
  <li>
    <b>Concurrency:</b>
    virtual-thread based request handling on modern JDKs.
  </li>
  <li>
    <b>Routing:</b>
    dynamic traffic forwarding between connected nodes.
  </li>
  <li>
    <b>Control Plane:</b>
    interactive terminal interface for routing and event inspection.
  </li>
  <li>
    <b>Network Flow:</b>
    <code>Clients → GateBridge → Nodes</code>
  </li>
</ul>

</td>

  </tr>

</table>

---

### Architecture Interests

<div align="center">

```text
┌──────────────────────────────────────┐
│             Application              │
│                                      │
│  API Design · Concurrency · Domain   │
└──────────────────┬───────────────────┘
                   │
                   ▼
┌──────────────────────────────────────┐
│         Distributed Systems          │
│                                      │
│ Communication · Routing · Consistency│
│           Failure Boundaries         │
└──────────────────┬───────────────────┘
                   │
                   ▼
┌──────────────────────────────────────┐
│            Infrastructure            │
│                                      │
│ Linux · Containers · Networking      │
│             Storage · I/O            │
└──────────────────┬───────────────────┘
                   │
                   ▼
┌──────────────────────────────────────┐
│               System                 │
│                                      │
│ Memory · CPU · Kernel · Hardware     │
└──────────────────────────────────────┘
```

<i>
I am particularly interested in how decisions at one layer
propagate into the others.
</i>

</div>

---

### Technologies & Tools

<table width="100%" border="0" cellpadding="8" cellspacing="0">

  <thead>
    <tr>
      <th width="25%" align="left">Category</th>
      <th width="75%" align="left">Technologies</th>
    </tr>
  </thead>

  <tbody>

<tr>
  <td valign="top"><b>Languages</b></td>
  <td valign="top">

<img src="https://img.shields.io/badge/-Java-000000?style=flat-square&logo=java&logoColor=white" alt="Java" />
<img src="https://img.shields.io/badge/-C-000000?style=flat-square&logo=c&logoColor=white" alt="C" />
<img src="https://img.shields.io/badge/-C%2B%2B-000000?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" />
<img src="https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
<img src="https://img.shields.io/badge/-Zig-000000?style=flat-square&logo=zig&logoColor=white" alt="Zig" />
<img src="https://img.shields.io/badge/-Assembly-000000?style=flat-square&logo=assemblyscript&logoColor=white" alt="Assembly" />
<img src="https://img.shields.io/badge/-TypeScript-000000?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/-JavaScript-000000?style=flat-square&logo=javascript&logoColor=F7DF1E" alt="JavaScript" />

  </td>
</tr>

<tr>
  <td valign="top"><b>Backend & Frameworks</b></td>
  <td valign="top">


<img src="https://img.shields.io/badge/-Spring%20Boot-000000?style=flat-square&logo=spring&logoColor=white" alt="Spring Boot" />
<img src="https://img.shields.io/badge/-React-000000?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/-Node.js-000000?style=flat-square&logo=node.js&logoColor=white" alt="Node.js" />
<img src="https://img.shields.io/badge/-Bun-000000?style=flat-square&logo=bun&logoColor=white" alt="Bun" />

  </td>
</tr>

<tr>
  <td valign="top"><b>Data & Messaging</b></td>
  <td valign="top">

<img src="https://img.shields.io/badge/-PostgreSQL-000000?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/-MySQL-000000?style=flat-square&logo=mysql&logoColor=white" alt="MySQL" />
<img src="https://img.shields.io/badge/-Cassandra-000000?style=flat-square&logo=apachecassandra&logoColor=white" alt="Cassandra" />
<img src="https://img.shields.io/badge/-Redis-000000?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
<img src="https://img.shields.io/badge/-Kafka-000000?style=flat-square&logo=apachekafka&logoColor=white" alt="Kafka" />
<img src="https://img.shields.io/badge/-RabbitMQ-000000?style=flat-square&logo=rabbitmq&logoColor=white" alt="RabbitMQ" />

  </td>
</tr>

<tr>
  <td valign="top"><b>Infrastructure</b></td>
  <td valign="top">


<img src="https://img.shields.io/badge/-Linux-000000?style=flat-square&logo=linux&logoColor=white" alt="Linux" />
<img src="https://img.shields.io/badge/-Docker-000000?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/-Kubernetes-000000?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes" />
<img src="https://img.shields.io/badge/-GitHub%20Actions-000000?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
<img src="https://img.shields.io/badge/-Cloudflare-000000?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare" />
<img src="https://img.shields.io/badge/-Amazon%20S3-000000?style=flat-square&logo=amazonaws&logoColor=white" alt="Amazon S3" />
<img src="https://img.shields.io/badge/-Cloudflare%20R2-000000?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare R2" />

  </td>
</tr>

<tr>
  <td valign="top"><b>Currently Exploring</b></td>
  <td valign="top">


<img src="https://img.shields.io/badge/-Vulkan-000000?style=flat-square&logo=vulkan&logoColor=white" alt="Vulkan" />
<img src="https://img.shields.io/badge/-eBPF-000000?style=flat-square&logo=linux&logoColor=white" alt="eBPF" />


  </td>
</tr>


  </tbody>
</table>

---

<div align="center">

<a name="contact"></a>

### Contact & Connect

<br><br>

<table align="center">
  <tr>
    <td align="center" width="200">
      <img
        src="https://github.com/watashi-00.png"
        width="200"
        height="200"
        style="border-radius: 50%;"
        alt="Watashi00"
      />
    </td>
    <td align="left">
      <h3>Watashi00</h3>
      <p>
        <b>Backend & Systems Engineer</b>
      </p>
      <p>
        <i>
        Always exploring new technologies and paradigms,
        with a constant focus on how systems are designed,
        implemented, measured, and scaled.
        </i>
      </p>
      <a href="https://github.com/watashi-00">
        <img
          src="https://img.shields.io/badge/GitHub-000000?style=flat-square&logo=github&logoColor=white"
          alt="GitHub"
        />
      </a>
      <a href="mailto:watashi@hexacloud.net.br">
        <img
          src="https://img.shields.io/badge/Email-000000?style=flat-square&logo=gmail&logoColor=white"
          alt="Email"
        />
      </a>
      <a href="https://medium.com/@watashi00">
        <img
          src="https://img.shields.io/badge/Medium-000000?style=flat-square&logo=medium&logoColor=white"
          alt="Medium"
        />
      </a>
    </td>
  </tr>
</table>

<br><br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0d0d,100:2b2b2b&height=120&section=footer&animation=fadeIn" width="100%" alt="Footer banner" />

</div>
