# Charles Mibbs — Cloud & Network Engineering Website

The source code for **[www.charlesmibbs.net](https://www.charlesmibbs.net/)**. A responsive, static personal website documenting a developing cloud and network engineering career.

## Featured project · Hybrid AWS Home Network
**Status: architecture and planning.** The project proposes an expandable 24-port Cat6 home network, a dedicated Proxmox/Linux virtualization server, and selective, cost-controlled AWS integrations. Deployment and testing have **not** yet been completed.

Five planned engineering case studies:
1. Physical LAN and Proxmox virtualization
2. Encrypted offsite backup and recovery
3. AWS VPC architecture
4. Secure hybrid connectivity
5. Terraform infrastructure as code

## Professional portfolio and documentation

- **[Live website](https://www.charlesmibbs.net/)**
- **[Website projects page](https://www.charlesmibbs.net/portfolio.html)**
- **[Public Notion engineering portfolio](https://gabby-guppy-36a.notion.site/PORTFOLIO-Professional-Work-405cf3881a8681aab0b5eea245c49398)**
- **[Earned credentials on Credly](https://www.credly.com/users/charles-mibbs)**

The public Notion portfolio contains five linked case-study pages with project goals and planned tests. Private operations materials, infrastructure inventories, task management, and maintenance records are not intended for publication.

## Website files
| Path | Purpose |
| --- | --- |
| `index.html` | Home, technical focus and earned certifications |
| `portfolio.html` | Hybrid AWS flagship project and five-phase roadmap |
| `resume.html` | Professional resume and certifications |
| `about.html` | Background and career direction |
| `styles.css` | Responsive dark design |
| `script.js` | Site interactions and shared external links |
| `config.js` | Current public contact/profile/Notion links |
| `CNAME` | GitHub Pages custom domain |

## Build and deploy
No build step is required. The site uses HTML, CSS and JavaScript. Review changes locally, then push to the publishing branch configured in GitHub Pages.

## Publication rules
- Label proposed work as **planned** until it has been deployed and tested.
- Document actual architectures, observed test results, failures and corrective actions.
- Keep IAM keys, tokens, private IP maps and identifying home infrastructure details out of this public repository.
- Never publish private Notion operations and maintenance pages.
