### `0. Simple Web Stack`

**Tasks:**
- Design a one-server web infrastructure hosting www.foobar.com.
- Utilize:
  - 1 server
  - 1 web server (Nginx)
  - 1 application server
  - 1 application files (your code base)
  - 1 database (MySQL)
- Configure domain name foobar.com with a www record pointing to server IP 8.8.8.8.
- Explain infrastructure specifics such as server role, domain name, DNS record types, web server, application server, database, and communication protocols.
- Identify issues like SPOF, downtime during maintenance, and scaling limitations.

---

### `1. Distributed Web Infrastructure`

**Tasks:**
- Design a three-server web infrastructure hosting www.foobar.com.
- Include:
  - 2 servers
  - 1 web server (Nginx)
  - 1 application server
  - 1 load-balancer (HAproxy)
  - 1 set of application files
  - 1 database (MySQL)
- Explain the rationale behind adding each element.
- Discuss load balancer distribution algorithms, Active-Active vs. Active-Passive setups, and Primary-Replica cluster workings.
- Highlight issues like SPOF, security concerns, and lack of monitoring.

---

### `2. Secured and Monitored Web Infrastructure`

**Tasks:**
- Design a three-server web infrastructure hosting www.foobar.com with security measures and monitoring.
- Add:
  - 3 firewalls
  - 1 SSL certificate for HTTPS
  - 3 monitoring clients (SumoLogic or similar)
- Explain the purpose of each addition and justify their inclusion.
- Address issues like SSL termination, single MySQL server for writes, and component homogeneity.

---

### `3. Scale Up`

**Tasks:**
- Differentiate between application server and web server.
- Add:
  - 1 server
  - 1 load-balancer (HAproxy) configured as a cluster with another.
  - Split components (web server, application server, database) onto separate servers.
- Explain the rationale for adding each component.

