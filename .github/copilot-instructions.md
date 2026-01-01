# FlowShield DDoS A524BD Framework - AI Agent Instructions

## Project Overview
FlowShield is a DDoS protection framework implementing the A524BD algorithm for advanced network traffic analysis and mitigation. The framework focuses on real-time detection and response to distributed denial-of-service attacks.

## Architecture
- **Orchestrator**: Central coordination component managing detection and mitigation workflows
- **Watchdog**: Monitoring and alerting system for traffic anomalies
- **TRex Scripts**: Traffic generation and testing utilities for DDoS simulation
- **A524BD Algorithm**: Core detection logic for identifying attack patterns

## Key Components
- Traffic analyzers for packet inspection
- Rule-based mitigation engines
- Integration points for network devices and cloud services

## Development Workflow
1. Enter project directory: `cd FlowShield_DDOS_A524BD_Framework`
2. Initialize Git: `git init -b main`
3. Add files: `git add .`
4. Commit: `git commit -m "Final Production Release: FlowShield 360 A524BD Framework"`
5. Link to GitHub: `git remote add origin https://github.com/aminul-du/FlowShield_DDOS_A524BD_Framework.git`
6. Push: `git push -u origin main`

## Coding Patterns
- Use descriptive commit messages following the project naming convention
- Implement components as modular scripts/modules for easy integration
- Focus on performance-critical sections for real-time traffic processing

## Testing
- Use TRex for traffic generation and DDoS simulation testing
- Validate detection accuracy against known attack patterns
- Monitor system performance under load

## Dependencies
- Network testing tools (TRex)
- Python/shell scripting environment
- Git for version control

## File Structure
- `README.md`: Project documentation
- `.github/`: CI/CD and agent instructions
- Component directories: Orchestrator/, Watchdog/, scripts/