# Security (& IT) Scanner Starter Kit

<div style="text-align: center;">
  <img src="https://i.imgur.com/0aAZ47l.jpeg" alt="Lego Security Engineer Produced by AI" width="20%" />
</div>

Welcome to my small and growing list of mostly-free security scanners and toolz that have personally come in handy in the course of an incident investigations, assessments, and vigorous troubleshooting a configuration. These are the tools I like to have in my back pocket and the purpose of this repo is mostly for me to have easy reference to these tools as time goes on since I don't trust browser bookmarks. There are certainly other listings for the elite hackers and OSINT wizards of the world but this "starter pack" will hopefully be of use to the average security engineer/analyst/consultant.

*Many of these tools have paid versions or APIs to use more advanced features but the freemium options are great places to start.*

## Starter Pack

### URL, Domain, and IP Scanners
- **[Cloudflare Radar](https://radar.cloudflare.com/scan)**: Understand the security, performance, technology, and network details of a URL with a publicly shareable report
- **[Shodan](https://www.shodan.io/)**: Discover devices connected to the internet and gather intelligence about them.
- **[Censys](https://search.censys.io/)**: Search engine for internet-connected devices, certificates, and open ports. Great complement to Shodan. *(Free tier: 100 results/search, 100 credits/month)*
- **[Tiny-Scan](https://www.tiny-scan.com/)**: Scanning and gathering information about IP addresses and domains.
- **[urlscan.io](https://urlscan.io/)**: Scan and analyze websites — get screenshots, resource maps, DOM snapshots, and indicators of compromise in one place.
- **[Pulsedive](https://pulsedive.com/analyze/)**: Paste text or upload files containing IPs, URLs, and domains.
- **[URLVoid](https://www.urlvoid.com/)**: Check the reputation and safety of websites. Great free API
- **[VirusTotal](https://www.virustotal.com/gui/home/url)**: Analyze URLs and domains to detect malicious content.
- **[GreyNoise](https://viz.greynoise.io/)**: Identify and filter internet background noise — quickly separate benign scanner traffic from actual threats on any IP.
- **[AbuseIPDB](https://www.abuseipdb.com/)**: Community-driven database of IP addresses reported for malicious activity. Check if an IP has been flagged.
- **[IPinfo](https://ipinfo.io/)**: Trusted source for IP info
- **[crt.sh](https://crt.sh/)**: Certificate Transparency log search — great for enumerating subdomains and understanding an org's certificate history.
- **[Browserling](https://www.browserling.com/)**: Browser sandbox. Great for testing sketchy links and seeing where they lead. *(Free tier: 3-minute sessions, older browsers only)*
- **[ICANN Lookup](https://lookup.icann.org/whois/)**: Registration details for domains/IPs
- **[DNSdumpster](https://dnsdumpster.com/)**: Free domain research tool that discovers hosts related to a domain including DNS records, MX, TXT, and a visual map.

### Configuration Scanners
- **[Mozilla Observatory](https://developer.mozilla.org/en-US/observatory)**: Scan your site for security vulnerabilities and best practices.
- **[SSL Labs](https://www.ssllabs.com/ssltest/)**: Test your SSL configuration and ensure it's secure.
- **[Security Headers](https://securityheaders.com/)**: Quickly check and grade the HTTP security headers of any site (CSP, HSTS, X-Frame-Options, etc.).
- **[Hardenize](https://www.hardenize.com/)**: Comprehensive web security assessment covering TLS, certificates, headers, DNSSEC, email security, and more in one report.
- **[HSTS Preload](https://hstspreload.org/)**: Check if a domain is on the HSTS preload list or submit one. Useful during hardening reviews.
- **[Google MX Toolbox](https://toolbox.googleapps.com/apps/checkmx/)**: Google tool to check the configuration of your mail server.
- **[ImmuniWeb](https://www.immuniweb.com/websec/)**: Free website security and privacy test covering GDPR, PCI DSS, and general hardening.

### Emails
- **[Have I Been Pwned](https://haveibeenpwned.com/)**: Check if an email address has been exposed in a data breach. The gold standard for breach lookups.
- **[Mozilla Monitor](https://monitor.mozilla.org/)**: Scan to see if your phone number, passwords or home address have been leaked
- **[MXToolbox](https://mxtoolbox.com/)**: Comprehensive suite of email and DNS diagnostic tools — check SPF, DKIM, DMARC, blacklists, and more.
- **[Google Admin Toolbox Messageheader](https://toolbox.googleapps.com/apps/messageheader/)**: Paste raw email headers to analyze routing hops, delays, and authentication results (SPF/DKIM/DMARC).
- **[TEMPMAIL](https://temp-mail.org/en/)**: Create a burner email to avoid spam

### Extensions & Addons
- **[ExtensionTotal](https://www.extensiontotal.com/)**: Tool to assess the risk of VSCode extensions, navigate the extension jungle, and detect malicious, risky or vulnerable extensions.

### Browsers and Webpages
- **[Browserling](https://www.browserling.com/)**: Live interactive cross-browser testing in your browser (so nice, mentioned it twice). *(Free tier: 3-minute sessions)*
- **[Wappalyzer](https://www.wappalyzer.com/lookup/)**: Identify technologies on websites such as content management systems, ecommerce platforms, web frameworks, server software, and analytics tools. Also in a [chrome addon](https://chromewebstore.google.com/detail/wappalyzer-technology-pro/gppongmhjkpfnbhag)
- **[CSP Evaluator](https://csp-evaluator.withgoogle.com/)**: Google tool to evaluate the effectiveness of your Content Security Policy.
- **[Redirect Detective](https://redirectdetective.com/)**: Trace the full redirect chain of any URL to see exactly where it ends up — handy for investigating suspicious short links.

### Malware & File Analysis
- **[Any.run](https://any.run/)**: Interactive online sandbox — run suspicious files or URLs and watch behavior in real time in a live VM.
- **[Hybrid Analysis](https://www.hybrid-analysis.com/)**: Free malware analysis service powered by CrowdStrike Falcon Sandbox. Submit files or URLs for deep behavioral analysis.
- **[Joe Sandbox](https://www.joesandbox.com/)**: Automated malware analysis with detailed reports covering network, file system, and registry behavior. *(Free community tier: 15 analyses/month)*
- **[MalwareBazaar](https://bazaar.abuse.ch/)**: Malware sample sharing repository from abuse.ch. Search for known samples by hash, tag, or family.
- **[URLhaus](https://urlhaus.abuse.ch/)**: Database of URLs actively distributing malware. Useful for checking if a URL has been reported as a malware distribution point.

### Threat Intelligence
- **[AlienVault OTX](https://otx.alienvault.com/)**: Open Threat Exchange — community-sourced threat intelligence with indicators of compromise (IOCs), threat pulses, and integrations.
- **[OpenCTI](https://www.opencti.io/)**: Open source threat intelligence platform for managing and correlating CTI data at scale. Self-hosted or cloud.
- **[MISP](https://www.misp-project.org/)**: Open source threat intelligence and sharing platform. Industry standard for structured IOC sharing between organizations.
- **[Feodo Tracker](https://feodotracker.abuse.ch/)**: Track botnet C2 infrastructure (Emotet, QakBot, etc.) from abuse.ch with blocklists you can actually use.

### Code & Dependency Security
- **[Semgrep](https://semgrep.dev/)**: Fast, open source static analysis for finding security issues in code. Runs in CI or interactively. Great rule library with security-specific patterns.
- **[Snyk](https://snyk.io/)**: Find and fix vulnerabilities in open source dependencies, container images, and IaC. Integrates with GitHub, GitLab, and more. *(Free for open source projects; limited test quota for private repos)*
- **[Socket](https://socket.dev/)**: Detect supply chain attacks and risky open source packages before they enter your project. Goes beyond CVEs to detect suspicious behavior.
- **[Trivy](https://trivy.dev/)**: Open source vulnerability scanner for container images, filesystems, Git repos, and Infrastructure as Code. Easy to run locally or in CI.
- **[OWASP Dependency-Check](https://owasp.org/www-project-dependency-check/)**: Identifies known vulnerable components in your project dependencies. Works across many ecosystems.
- **[deps.dev](https://deps.dev/)**: Google's open source insights tool — understand dependency trees, licenses, security advisories, and freshness for any package.

### Cloud Security
- **[Prowler](https://prowler.com/)**: Open source cloud security tool for AWS, Azure, and GCP. Runs hundreds of security checks mapped to CIS Benchmarks and compliance frameworks.
- **[ScoutSuite](https://github.com/nccgroup/ScoutSuite)**: Multi-cloud security auditing tool from NCC Group. Generates an HTML report of misconfigurations across AWS, Azure, GCP, and others.
- **[Aqua CloudSploit](https://aquasecurity.github.io/cloudsploit/)**: Open source cloud security scanner for detecting misconfigurations across major cloud providers.
- **[Steampipe](https://steampipe.io/)**: Query your cloud infrastructure using SQL. Use community mods to run CIS benchmark checks across AWS, Azure, GCP, and more.

### AI & Copilot Tools
- **[SOC Copilot](https://chatgpt.com/g/g-qvSadylbt-soc-copilot)**: SOC assistant built on ChatGPT. Helps analyze data, develop reports, and work through security scenarios. *(Requires a ChatGPT account — free tier available with usage limits)*

### Detection as Code
- **[Rex - Rule Explorer](https://rulexplorer.io/)**: collection of open source detection rules (e.g., sigma rules)
- **[Sigma Rules](https://github.com/SigmaHQ/sigma)**: collection of open source detection rules (e.g., sigma rules)
- **[Uncoder.io](https://uncoder.io/)**: Translate Sigma rules and detection queries between SIEM platforms (Splunk, Sentinel, Elastic, Chronicle, etc.) — huge time saver.
- **[YARA Rules](https://github.com/Yara-Rules/rules)**: Community collection of YARA rules for identifying malware samples and threat actors.
- **[LOKI](https://github.com/Neo23x0/Loki)**: Open source IOC and YARA scanner for endpoint triage. Point it at a directory and get a quick read on what's there.

## Contributing

Contributions are welcome! If you have a favorite security tool that you think should be included in this list, please feel free to open an issue or submit a pull request.
