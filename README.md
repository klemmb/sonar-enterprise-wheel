# Sonar Enterprise Wheel

Interactive capability wheels for **SonarQube Server Enterprise Edition**, the **SonarQube Cloud Enterprise plan** and **Gitar Enterprise**:
core analysis at the center, Enterprise differentiators, Advanced Security and Sonar's AI and agentic products around it.

Live site: https://klemmb.github.io/sonar-enterprise-wheel/

| Page | Product | Style |
|---|---|---|
| `enterprise-wheel-server-light.html` | SonarQube Server | Light |
| `enterprise-wheel-cloud-light.html` | SonarQube Cloud | Light |
| `enterprise-wheel-server.html` | SonarQube Server | Dark |
| `enterprise-wheel-cloud.html` | SonarQube Cloud | Dark |
| `gitar-enterprise-wheel-light.html` | Gitar Enterprise | Light |
| `ai-agent-requirements.html` | Cloud, Server & Gitar | LLM models and providers per AI agent |

Each page is self-contained (icons, logos and background music are embedded). Fonts load from Google Fonts.

## Version 3

`v3/` holds the same four wheels with two extra switches under the comparison switch: **AI**, which greys out the paid AI (Sonar Vortex, Remediation Agent, Hunter Agent and Gitar), and **Advanced Security**, which greys out the Advanced Security group, for example https://klemmb.github.io/sonar-enterprise-wheel/v3/enterprise-wheel-server-light.html. The v3 pages are generated from the root pages with `make_v3.py`, so content changes are made once in the root pages.

## Controls

- Hover a segment to highlight it; click it to show its details and click it again to hide them; click the center for the overview.
- `←` / `→` step through the capabilities, `Esc` closes the details.
- `P` plays or pauses the guided tour (seconds per step are configurable), `M` toggles the background music.
- The compare switch fades what Developer Edition (Server) or the Team plan (Cloud) does not include.
- **Export PDF** opens the print dialog; choose *Save as PDF* for an A4 landscape handout.

Content reflects SonarQube Server 2026.5 LTA and SonarQube Cloud as of October 2026.
