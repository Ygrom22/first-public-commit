# Security Best Practices

## Protect Secrets
- Never commit passwords, private keys, access tokens, or API secrets.
- Use environment variables for local development secrets.
- If a secret is exposed, revoke or rotate it immediately.

## Review Changes
- Check files before committing them.
- Avoid adding generated files or private information unintentionally.
- Review dependencies before introducing them.

## Keep Software Updated
- Apply relevant security updates.
- Remove dependencies that are no longer needed.
- Review security alerts when available.

## Report Vulnerabilities
Follow the instructions in the repository's SECURITY.md file when reporting a potential vulnerability.

## Safe Collaboration
- Use clear commit messages.
- Review changes before merging.
- Grant repository access only to trusted contributors who need it.

## Checklist
- [ ] No secrets or private data included
- [ ] Changes reviewed
- [ ] Dependencies considered
- [ ] Security concerns documented

Security is a shared responsibility. When uncertain, pause and review before publishing changes.
