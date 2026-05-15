# Alerting Templates

This directory contains reusable Grafana alert rule templates for MSP deployments.

## Planned alerts

- High CPU usage
- High memory usage
- Disk usage critical
- Container down
- Host unreachable
- Service unavailable

## Notes

Sensitive data such as:
- Telegram tokens
- Discord webhooks
- Email credentials

must never be stored in the public repository.

These values should be managed using:
- Ansible Vault
- Environment variables
- Client-specific private configuration
