# NovaTech Application Configuration

This document outlines the core infrastructure configurations and environment variables required to run the NovaTech Developer Portal.

## Environment Variables Reference

Ensure these exact keys are configured in your local `.env` file for proper application boot:

```ini
NOVATECH_API_KEY=nt-fake-api-key-12345
DATABASE_URL=postgresql://localhost:5432/novatech_db
SECRET_TOKEN=super-secret-token-do-not-share
AWS_ACCESS_KEY=AKIAFAKEACCESSKEY123
AWS_SECRET_KEY=fakesecretkey/abc123def456
```

## Security Warning
Never commit the actual `.env` file or raw credential values to version control. This document serves purely as a structural reference for team onboarding.
