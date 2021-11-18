
# All that you know about Fastlane in my Notion
https://mangrove-vase-933.notion.site/Fastlane-d4783bacfc0e46229348cb51b6e97017


# Create and edit Archive .env:

# Bundle Identifier
APP_IDENTIFIER  = "bundle"

# app store connect
APPLE_ID          = "login(AppleID)"
FASTLANE_PASSWORD = "password"

# Xcode
WORKSPACE       = "projectName.xcworkspace"
SCHEME          = "projectName"
CONFIGURATION   = ""

# Provisioning Profiles
PROFILE_APP_STORE  = "profileDist"
PROFILE_AD_HOC     = "profileADHOC"

# Developer Portal Team ID
team_id         = "bundle exec fastlane getTeamNames"

# App Store Connect Team ID
itc_team_id     = "bundle exec fastlane getTeamNames"

# Match: senha do git repo
MATCH_PASSWORD  = ""

# Transporter
# App Store Connect > Apps > App > Information App > Apple ID(ID generate automaticaly to your app).
APP_STORE_CONNECT_APPLE_ID = "xxx"

# https://appleid.apple.com > Security > APP-SPECIFIC-PASSWORD > Generate Password
# (This passwrod permite fastlane to send test flight even though account has a 2 factory security abled)
# Documentation: https://docs.fastlane.tools/best-practices/continuous-integration/
FASTLANE_APPLE_APPLICATION_SPECIFIC_PASSWORD = "xxx"

# Firebase dist
FIREBASE_DIST_SERVICE_ACCOUNT_FILE = ""
FIREBASE_APP_ID     = ""
FIREBASE_TEST_GROUP = ""
FIREBASE_TESTERS    = ""

# AppCenter
APP_CENTER_API_TOKEN    = ""
APP_CENTER_OWNER_NAME   = ""
APP_CENTER_OWNER_TYPE   = "organization"
APP_CENTER_APP_NAME     = ""
APP_CENTER_DESTINATIONS = "Collaborators"