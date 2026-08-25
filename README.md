# Automated Birthday Wisher

A Python project that checks birthdays.csv every day and sends a birthday email through Gmail SMTP.

## Files

- `main.py` - birthday checking and email sending logic
- `birthdays.csv` - birthday information
- `letter_3.txt` - birthday message
- `.github/workflows/birthday.yml` - daily GitHub Actions automation

## GitHub Secrets

Add these repository secrets:

- `MY_EMAIL`
- `MY_PASSWORD`

Do not put Gmail credentials directly in the code.

## Schedule

The GitHub Actions workflow runs daily at 02:30 UTC (08:00 IST).

You can also run it manually from the GitHub Actions tab.
