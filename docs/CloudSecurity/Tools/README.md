

| [WebSecurity](https://ji-podhead.github.io/Web-And-CloudSecurity/WebSecurity) | [CloudSecurity](https://ji-podhead.github.io/Web-And-CloudSecurity/CloudSecurity) |


<div align="center">
      <img src="https://github.com/ji-podhead/ji-podhead/blob/main/logo.jpg?raw=true" align="right" width="50" />
</div>

----

## Cloud Security 

| [***Attack Vectors***](https://ji-podhead.github.io/Web-And-CloudSecurity/AttackVectors/#cloud-bases-attack-vectors) | [***Tools***](https://ji-podhead.github.io/Web-And-CloudSecurity/CloudSecurity/Tools) | [***Continous Monitoring 🚧***](https://ji-podhead.github.io/Web-And-CloudSecurity/CloudSecurity/Monitoring) |


| Tool | Description | Purpose |
|------|-------------|---------|
| [suricata](https://suricata.io/ )                          | Suricata is an open-source based intrusion detection system (IDS) and intrusion prevention system (IPS). | Intrusion Detection |
|[falco](https://falco.org/  )                          |Falco is a cloud-native security tool designed for Linux systems. It employs custom rules on kernel events, which are enriched with container and Kubernetes metadata, to provide real-time alerts. Falco helps you gain visibility into abnormal behavior, potential security threats, and compliance violations, contributing to comprehensive runtime security.  | Intrusion Detection |
| [playwright](https://playwright.dev/)                         | Playwright is a framework for Web Testing and Automation. It allows testing Chromium, Firefox and WebKit with a single API.  | E2E |
|[kube-bench](https://github.com/aquasecurity/kube-bench)                | kube-bench is a tool that checks whether Kubernetes is deployed securely by running the checks documented in the CIS Kubernetes Benchmark. | k8s compliance|
|[checkov](https://www.checkov.io/4.Integrations/Kubernetes.html)                   |Checkov is a static code analysis tool for scanning infrastructure as code (IaC) files for misconfigurations that may lead to security or compliance problems. Checkov includes more than 750 predefined policies to check for common misconfiguration issues. Checkov also supports the creation and contribution of custom policies.  | iac compliance |
| [trivy](https://trivy.dev/)                         | Use Trivy to find vulnerabilities & IaC misconfigurations, SBOM discovery, Cloud scanning, Kubernetes security risks,and more. | "all in one security scanner" |
|[k6](https://k6.io/)                         | Load testing,Mix browser and API testing—interact with real browsers and collect frontend metrics,Inject faults in Kubernetes-based apps, Infrastructure testing, Regression testing | load teesting |
|[kubeaudit](https://github.com/Shopify/kubeaudit)                     |kubeaudit is a command line tool and a Go package to audit Kubernetes clusters for various different security   | k8s compliance  |
|[kubescore](https://github.com/zegl/kube-score)                     | kube-score is a tool that performs static code analysis of your Kubernetes object definitions | k8s compliance  |
| [netfetch](https://github.com/deggja/netfetch)                       |  Kubernetes tool for scanning clusters for network policies and identifying unprotected workloads. | k8s network policy scanner  |
|  [prowler](https://github.com/prowler-cloud/prowler)                           | Prowler is an Open Source security tool to perform AWS, Azure, Google Cloud and Kubernetes security best practices assessments, audits, incident response, continuous monitoring, hardening and forensics readiness, and also remediations! We have Prowler CLI (Command Line Interface) that we call Prowler Open Source and a service on top of it that we call Prowler SaaS. | compliance scans and forensics |
|             [elastic search](https://www.elastic.co/de/?utm_campaign=Google-B-EMEA-C-DE-New-Exact&utm_content=Brand-Core&utm_source=google&utm_medium=cpc&device=c&utm_term=elasticsearch&gad_source=1&gclid=Cj0KCQjw7ZO0BhDYARIsAFttkCg6WbERHZU5dmMAbxD2MKzpM2L96sNeM_QFPutInkbWR8wXoJe8rZgaAp_IEALw_wcB)         | Elasticsearch is the distributed search and analytics engine at the heart of the Elastic Stack. Logstash and Beats facilitate collecting, aggregating, and enriching your data and storing it in Elasticsearch. Kibana enables you to interactively explore, visualize, and share insights into your data and manage and monitor the stack.  | metrics, logs & forensics |
| [impulse-xdr](https://github.com/bgenev/impulse-xdr )                          |  Impulse is a fully automated host & network intrusion detection platform with real-time threat detection sensors, storage and visualisation. It detects malware from behavioural patterns rather than signatures and enables deeper visibility than legacy tools. It can be deployed on any device or VM running Linux such as cloud VMs in VPC networks, VPS servers or personal workstations and IoTs.| Intrusion Detection |
| [greenbone](https://github.com/greenbone/openvas-scanner?tab=readme-ov-file) | This is the OpenVAS Scanner of the Greenbone Community Edition. It is used for the Greenbone Enterprise appliances and is a full-featured scan engine that executes a continuously updated and extended feed of Vulnerability Tests (VTs).| Vulnerability Scanner |
| [quay/clair](https://github.com/quay/clair) | Clair is an open source project for the static analysis of vulnerabilities in application containers (currently including OCI and docker). Clients use the Clair API to index their container images and can then match it against known vulnerabilities. | static container analysis |
| [k8s e2e framework](https://github.com/kubernetes/kubernetes/tree/v1.27.0-rc.0/test/e2e/framework) | The Kubernetes E2E framework simplifies writing Ginkgo tests suites. It's main usage is for these tests suites in the Kubernetes repository itself | e2e | 
| [kubesec](https://fwdcloudsec.org/conference/archive/2020/](https://github.com/controlplaneio/kubesec)) |Kubesec is an open-source Kubernetes security scanner and analysis tool. The way it works, it accepts a single Kubernetes manifests file and provides a severity score for each found vulnerability. | k8s compliance |
| [chef inspec](https://docs.chef.io/inspec/)  | Chef InSpec is an open-source framework for testing and auditing your applications and infrastructure. It compares the actual state of your system with the desired state that you express in easy-to-read and easy-to-write Chef InSpec code. It detects violations and displays findings in the form of a report, but puts you in control of remediation. | compliance | 
| [testcontainers](https://testcontainers.com/) | Testcontainers is an open source framework for providing throwaway, lightweight instances of databases, message brokers, web browsers, or just about anything that can run in a Docker container. | env based testing |
| [locust](https://locust.io/) | Define user behaviour with Python code, and swarm your system with millions of simultaneous users.  | load testing | 
