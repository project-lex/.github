# Configuration Examples

This directory contains example JSON configurations for Project Lex Analytics Platform to help you get started quickly.

## 📋 Available Examples

### [basic-analytics-config.json](basic-analytics-config.json)
A comprehensive example showcasing:
- **Data Sources**: Webhook and PostgreSQL connections
- **Processing Pipelines**: Data filtering, enrichment, and aggregation
- **Analytics**: Conversion funnels and real-time dashboards
- **Outputs**: Data warehouse storage and monitoring alerts
- **Monitoring**: Health checks and performance thresholds
- **Settings**: Timezone, retention policies, and privacy controls

## 🚀 Getting Started

1. **Copy an example**: Start with the `basic-analytics-config.json` example
2. **Replace placeholders**: Update environment variables like `${API_TOKEN}`, `${DB_HOST}`, etc.
3. **Customize for your needs**: Modify data sources, metrics, and outputs
4. **Test your configuration**: Start with a small dataset to validate your setup

## 🔧 Configuration Structure

All configurations follow this general structure:

```json
{
  "metadata": {
    "name": "Your Pipeline Name",
    "version": "1.0.0",
    "description": "Description of what this configuration does"
  },
  "dataSources": [...],    // Where your data comes from
  "pipelines": [...],      // How to process your data
  "analytics": [...],      // What insights to generate
  "outputs": [...],        // Where to send results
  "monitoring": {...},     // Health checks and alerts
  "settings": {...}        // Global configuration options
}
```

## 🔑 Environment Variables

For security, always use environment variables for sensitive information:

- `${API_TOKEN}` - API authentication tokens
- `${DB_HOST}`, `${DB_USER}`, `${DB_PASSWORD}` - Database credentials
- `${WAREHOUSE_HOST}`, `${WAREHOUSE_USER}`, `${WAREHOUSE_PASSWORD}` - Data warehouse credentials
- `${SLACK_WEBHOOK_URL}` - Notification webhook URLs

## 📊 Common Use Cases

### E-commerce Analytics
- Track user journeys and conversion funnels
- Monitor product performance and inventory
- Analyze customer behavior patterns

### Application Monitoring
- Monitor user engagement and feature usage
- Track performance metrics and errors
- Generate usage reports and dashboards

### Marketing Analytics
- Campaign effectiveness measurement
- Attribution modeling
- Customer segmentation

## 🛠️ Customization Tips

### Data Sources
- Use the appropriate connector type for your data
- Always use environment variables for credentials
- Define clear schemas for data validation

### Processing Pipelines
- Start simple and add complexity gradually
- Use meaningful IDs for tracking and debugging
- Consider data volume when setting time windows

### Analytics
- Focus on metrics that drive business decisions
- Set appropriate time windows for your use case
- Use grouping to segment your analysis

### Outputs
- Choose storage solutions that match your scale
- Set up monitoring alerts for critical metrics
- Consider data retention and privacy requirements

## 🔍 Validation

Before deploying your configuration:

1. **Syntax Check**: Ensure your JSON is valid
2. **Schema Validation**: Verify all required fields are present
3. **Credential Test**: Confirm all connections work
4. **Small Scale Test**: Run with limited data first
5. **Performance Test**: Verify it handles your expected data volume

## 📚 Additional Resources

- [Configuration Help Issues](/.github/ISSUE_TEMPLATE/config_help.md) - Get help with your configuration
- [Contributing Guide](/CONTRIBUTING.md) - Learn how to contribute examples
- [Security Guidelines](/SECURITY.md) - Security best practices for configurations

## 💡 Contributing Examples

Have a great configuration example? We'd love to include it! Please:

1. Remove all sensitive information
2. Add clear comments explaining the use case
3. Test the configuration thoroughly
4. Submit a pull request with a description

---

**Need help?** Use our [Configuration Help template](/.github/ISSUE_TEMPLATE/config_help.md) to get assistance from the community!