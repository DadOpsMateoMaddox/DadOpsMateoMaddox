# Copilot Instructions for Cybersecurity Projects

## Repository Context

This repository belongs to Kevin Landry, a cybersecurity professional and M.S. Cybersecurity student at George Mason University. The projects focus on:

- **Honeypots & Threat Intelligence**: Advanced honeypot systems with AI integration
- **Threat Analysis & Scanning**: Security tools for vulnerability assessment and threat detection
- **Data Structures & Algorithms**: Academic coursework and algorithmic implementations
- **Coast Guard Background**: Military service with expertise in communications and operations

## Primary Technologies

- **Python**: Primary language for cybersecurity tools, threat intelligence, and data analysis
- **Java**: Used for data structures, algorithms, and academic projects
- **Security Tools**: Integration with SHODAN, VirusTotal, AI GuardDog, and other threat intelligence APIs
- **Jupyter Notebooks**: For security research, penetration testing, and malware analysis

## Coding Standards and Best Practices

### Python Development

- Follow PEP 8 coding standards with clear, descriptive variable names
- Use type hints for function parameters and return values
- Implement comprehensive error handling with specific exception types
- Document security-sensitive functions with detailed docstrings
- Use virtual environments and requirements.txt for dependency management
- Prioritize security best practices: input validation, secure API handling, and credential management

### Java Development

- Follow Oracle's Java coding conventions
- Use meaningful class and method names that reflect cybersecurity concepts
- Implement proper exception handling for security-related operations
- Document complex algorithms with clear comments explaining the security context
- Use appropriate data structures for performance-critical security applications

### Security-Focused Development

- **Never commit secrets**: Use environment variables or secure credential stores
- **Input validation**: Always validate and sanitize user inputs, especially in security tools
- **Logging**: Implement comprehensive logging for security events and tool operations
- **Error handling**: Provide meaningful error messages without exposing sensitive information
- **Documentation**: Include clear usage examples and security considerations

## Project-Specific Guidelines

### Honeypot Development

- Implement proper isolation and sandboxing mechanisms
- Log all attacker interactions with detailed timestamps and metadata
- Integrate with threat intelligence feeds for real-time analysis
- Use secure communication channels for data transmission
- Include comprehensive monitoring and alerting capabilities

### Threat Analysis Tools

- Support multiple output formats (JSON, CSV, reports)
- Implement rate limiting for API calls to respect service limits
- Cache results appropriately to improve performance
- Provide clear risk scoring and threat categorization
- Include data validation for threat intelligence feeds

### Algorithm Implementations

- Focus on performance optimization for large datasets
- Include comprehensive unit tests with edge cases
- Document time and space complexity analysis
- Provide clear examples of practical applications in cybersecurity
- Consider thread safety for concurrent operations

## Documentation Standards

- **README files**: Include clear installation, usage, and security considerations
- **Code comments**: Explain the "why" behind security decisions, not just the "how"
- **Security notes**: Document potential vulnerabilities and mitigation strategies
- **Examples**: Provide practical examples with real-world cybersecurity scenarios
- **Changelog**: Maintain version history with security-related changes highlighted

## Testing and Quality Assurance

- Write unit tests for all security-critical functions
- Include integration tests for external API interactions
- Test error handling and edge cases thoroughly
- Validate security controls and access restrictions
- Use continuous integration for automated testing

## Commit and Development Workflow

- Use conventional commits with security-focused scopes:
  - `feat(honeypot):` for new honeypot features
  - `fix(scanner):` for threat scanning bug fixes
  - `security:` for security-related changes
  - `docs:` for documentation updates
  - `test:` for testing improvements

## Security Considerations

- **API Keys**: Use environment variables and never commit to version control
- **Data Privacy**: Handle collected threat data in compliance with privacy regulations
- **Network Security**: Implement secure communication protocols
- **Access Control**: Apply principle of least privilege
- **Audit Logging**: Maintain detailed logs for security operations

## Academic and Research Context

- Reference academic papers and security research when applicable
- Include proper citations for algorithms and security techniques
- Document experimental results with statistical analysis
- Consider ethical implications of security research
- Follow responsible disclosure practices for vulnerability research

When implementing features, always consider the cybersecurity context and potential security implications of the code being written.