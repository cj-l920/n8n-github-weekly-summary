# Security Policy

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | :white_check_mark: |

## Reporting a Vulnerability

If you discover a security vulnerability in this project, please report it by opening an issue on GitHub.

## Security Considerations

When using this workflow:

1. **API Tokens**: Store GitHub and OpenAI API tokens securely in n8n credentials, never hardcode them
2. **Scope**: Use GitHub tokens with minimum required permissions (read access to repos)
3. **Data Privacy**: Be aware that repository data is sent to OpenAI for summarization
4. **Slack/Email**: Ensure notification channels are secure and appropriate for your data

## Best Practices

- Rotate API keys regularly
- Monitor workflow execution logs
- Use environment-specific configurations
- Review AI-generated summaries before sharing