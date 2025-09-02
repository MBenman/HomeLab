# HomeLab
A containerized homelab server and DevOps playground where my boss won’t yell at me for breaking prod.

# Goals

- Build and maintain a useful home server with enterprise-grade tools and best practices
- Learn and experiment with new software and platforms
# Current Services/Infrastructure

## Infra

- Docker    
- Vault
- Bind9 DNS
- Github Actions CI/CD

## Services
* [Obsidian Live Sync](https://github.com/vrtmrz/obsidian-livesync/tree/main)
	* Markdown Notetaking Synchronization
		* Docker
		* CouchDB
* Ollama Self-Hosted LLM 
	* Running gemma3
    

## Management/Utilities
* Bind9 DNS
	* Docker
	* To-Do:
		* Configure firewall as primary
		* Configure request route for pi.maxwellbenman.com to internal DNS
		* Automate local name resolution w/ Terraform 