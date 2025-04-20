# Automated Issue Closing

A repository to test GitHub automation for closing labeled issues.

## How it Works

This repository contains a GitHub Actions workflow that automatically closes issues labeled as 'completed' or 'wontfix'.

## Testing the Automation

Three test issues have been created:
1. "Implement new feature" with 'completed' label (should be closed automatically)
2. "Remove legacy code" with 'wontfix' label (should be closed automatically)
3. "Fix login error" with 'bug' label (should remain open)

## Manual Testing

If the workflow did not run automatically, you can manually trigger it using GitHub's workflow dispatch feature:

1. Go to the Actions tab in the repository
2. Select the "Auto Close Issues" workflow
3. Click "Run workflow"