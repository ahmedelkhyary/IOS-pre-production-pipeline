# IOS Pre Production Pipeline
This pipeline automates the Continuous Integration (CI) process for building and deploying iOS application to TestFlight using Azure DevOps.

# Build and Deployment Requirements

#### To successfully build and upload the app, the following items are required:

1 - App ID (Bundle ID) registered in the Apple Developer portal.

2 - Provisioning Profile (for distribution to App Store or TestFlight):
  - **Must be set to manual signing.**
  - **Match the bundle ID.**

3 - iOS Distribution Certificate (P12)

4 - App-Specific Password for the Apple ID (used to upload to TestFlight).

<a href="https://www.linkedin.com/feed/update/urn:li:activity:7328780907442581504/" target="_blank" rel="noopener noreferrer">Mobile DevOps Presentation</a>
