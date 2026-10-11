## Patrick 

**Senior Software Engineer · AI-native development · Backend & platform** · Davao, Philippines

I build and run the systems behind an ICANN-accredited domain registrar: the EPP layer that talks to the registries, the customer portal, and the operator console. These days I build mostly by directing AI coding agents, and I put most of my effort into the guardrails that keep their output correct.

### What I work on

- **Registry integration** (Java 25, Spring Boot 4)
  - Took the registrar from a sample EPP client to Verisign (.com/.net) and PIR (.org) OTE certification, then to a production gateway.
  - Added RDAP, a port-43 WHOIS server and registrar data escrow.
  - Built a policy-as-config API gateway with rate limits and circuit breakers.
- **Registrar portal and operator console** (Laravel 13, React 19, PostgreSQL)
  - An aftermarket fulfilment engine with an HMAC-signed partner channel and replay protection.
  - An OpenID Connect identity provider (PKCE).
  - Fail-closed checkout and ledger safety; rate limiting and queue circuit breakers.
- **AI-native engineering** (Claude Code, MCP)
  - A multi-repo agent workspace: project detection, per-project context, custom skills.
  - Guardrails: architecture fitness tests, ArchUnit, static analysis, contract-testing stubs.
  - Product AI: multi-model LLM domain suggestions (hardened against SSRF) and a Vertex AI image classifier.
- **Google Cloud**
  - Compute Engine, Cloud SQL for PostgreSQL, external Application Load Balancer with a static IP, Cloud Armor WAF.
  - VPC firewall, Datastore, Cloud Storage, Secret Manager, Cloud Logging.

### Stack

| | |
|---|---|
| **Languages** | Java, PHP, TypeScript / JavaScript, SQL, Bash, Dart |
| **Backend** | Spring Boot, Spring Cloud Gateway, Resilience4j, Laravel, Node / Express |
| **Frontend** | React, Inertia, Tailwind, Flutter, Electron |
| **Data** | PostgreSQL, MySQL, Cloud Datastore |
| **Protocols** | EPP, RDAP, WHOIS, OpenID Connect + PKCE, HMAC request signing |
| **Testing** | JUnit, ArchUnit, Pest / PHPUnit, Vitest, Playwright |

### Why most of my work isn't here

My production work is client code in private repositories, so it stays private. My contribution graph shows that activity without exposing it. Anything public on this profile is written from scratch to show the same skills.

### Contact

patrick91tolentino@gmail.com · Resume available on request
