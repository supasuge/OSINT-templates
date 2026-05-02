# Obsidian.md Cybersec Templates

Case report template to use with [Obsidian.md](https://obsidian.md)

## Requirements

- Install and enable the core plugin: `Templates`

---

## OSINT Case Report Template

### Installation

```bash
OBSIDIAN_VAULT_TEMPLATES=/path/to/obsidian/vault/templatesdir                 # different depending on where you keep your vault/make the templates folder.

# Add folder templates
mkdir OBSIDIAN_VAULT/templates
wget https://raw.githubusercontent.com/supasuge/OSINT-templates/refs/heads/main/OSINT-case-report.template.md -O ${OBSIDIAN_VAULT_TEMPLATES}/OSINT-case-report
```

- For any given template you'd like to use, make sure you have the variables and any other customization's you want to make added to the "Core plugins > Templates" section of the settings.

###### TODO

- [ ] Pentesting Report Template
- [ ] Compliance Audit + Remediation Template
- [ ] Threat/Risk Analysis
- [ ] Security Assessment/Audits (ISO compliant)


---

## License

MIT
