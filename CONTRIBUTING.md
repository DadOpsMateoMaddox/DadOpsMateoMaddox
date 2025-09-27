# Contributing to Kevin Landry's Cybersecurity Projects

Thank you for your interest in contributing to this cybersecurity-focused repository! This guide will help you understand how to contribute effectively.

## Before You Start

This repository is configured with GitHub Copilot instructions in `.github/copilot-instructions.md` that provide context about:
- Cybersecurity focus areas (honeypots, threat intelligence, vulnerability assessment)
- Coding standards for Python and Java
- Security best practices for development
- Academic and research context

## Security First

🔒 **Security is paramount** in all contributions:
- Never commit API keys, credentials, or sensitive data
- Follow secure coding practices
- Validate all inputs and handle errors gracefully
- Document security considerations in code comments

## Development Guidelines

### Python Projects
- Follow PEP 8 coding standards
- Use type hints for better code clarity
- Include comprehensive docstrings for security-sensitive functions
- Use virtual environments for dependency management

### Java Projects
- Follow Oracle Java coding conventions
- Implement proper exception handling
- Document complex algorithms clearly
- Focus on performance for security-critical operations

## Project Categories

### Honeypots & Threat Intelligence
- Implement proper isolation and sandboxing
- Log all interactions with detailed metadata
- Integrate with threat intelligence APIs responsibly
- Consider rate limiting for external API calls

### Security Tools & Scanners
- Support multiple output formats
- Implement proper caching mechanisms
- Provide clear risk scoring
- Include comprehensive error handling

## Commit Standards

Use conventional commits with security-focused scopes:
- `feat(honeypot):` - New honeypot features
- `fix(scanner):` - Bug fixes in scanning tools
- `security:` - Security-related changes
- `docs:` - Documentation updates

## Questions?

This repository reflects Kevin Landry's professional development in cybersecurity while pursuing an M.S. in Cybersecurity at George Mason University. Feel free to open an issue for questions about specific security implementations or academic context.