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
- **[Tiny-Scan](https://www.tiny-scan.com/)**: Scanning and gathering information about IP addresses and domains.
- **[Pulsedive](https://pulsedive.com/analyze/)**: Paste text or upload files containing IPs, URLs, and domains.
- **[URLVoid](https://www.urlvoid.com/)**: Check the reputation and safety of websites. Great free API
- **[VirusTotal](https://www.virustotal.com/gui/home/url)**: Analyze URLs and domains to detect malicious content.
- **[IPinfo](https://ipinfo.io/)**: Trusted source for IP info
- **[Browserling](https://www.browserling.com/)**: Browser sandbox. Great for testing sketchy links and seeing where they lead
- **[ICANN Lookup](https://lookup.icann.org/whois/)**: Registration details for domains/IPs

### Configuration Scanners
- **[Mozilla Observatory](https://developer.mozilla.org/en-US/observatory)**: Scan your site for security vulnerabilities and best practices.
- **[SSL Labs](https://www.ssllabs.com/ssltest/)**: Test your SSL configuration and ensure it's secure.
- **[Google MX Toolbox](https://toolbox.googleapps.com/apps/checkmx/)**: Google tool to check the configuration of your mail server.

### Emails
- **[Mozilla Monitor](https://monitor.mozilla.org/)**: Scan to see if your phone number, passwords or home address have been leaked
- **[TEMPMAIL](https://temp-mail.org/en/)**: Create a burner email to avoid spam

### Extensions & Addons
- **[CRXcavator](https://crxcavator.io/)**: Analyze the security of browser extensions and ensure they are safe to use.
- **[ExtensionTotal](https://www.extensiontotal.com/)**: Tool to assess the risk of VSCode extensions, navigate the extension jungle, and detect malicious, risky or vulnerable extensions.

### Browsers and Webpages
- **[Browserling](https://www.browserling.com/)**: Live interactive cross-browser testing in your browser (so nice, mentioned it twice)
- **[Wappalyzer](https://www.wappalyzer.com/lookup/)**: Identify technologies on websites such as content management systems, ecommerce platforms, web frameworks, server software, and analytics tools. Also in a [chrome addon](https://chromewebstore.google.com/detail/wappalyzer-technology-pro/gppongmhjkpfnbhag
- **[CSP Evaluator](https://csp-evaluator.withgoogle.com/)**: Google tool to evaluate the effectiveness of your Content Security Policy.

### GPTs
- **[SOC Copilot](https://chatgpt.com/g/g-qvSadylbt-soc-copilot)**: SOC assistant in ChatGPT. Helps analyze data, develop reports, etc.

### Detection as Code
- **[Rex - Rule Explorer](https://rulexplorer.io/)**: collection of open source detection rules (e.g., sigma rules)
- **[Sigma Rules](https://github.com/SigmaHQ/sigma)**: collection of open source detection rules (e.g., sigma rules)

## Contributing

Contributions are welcome! If you have a favorite security tool that you think should be included in this list, please feel free to open an issue or submit a pull request.
