# User-Notification-Preferences-API-Challenge

File Descriptions
src/main.ts

The entry point for the Nest.js application.
Bootstraps the app and listens for incoming requests.
src/app.module.ts

The root module importing UserPreferencesModule and NotificationsModule.
src/user-preferences/

user-preference.schema.ts: MongoDB schema for user preferences.
user-preferences.controller.ts: Handles CRUD operations for user preferences.
user-preferences.service.ts: Business logic for managing preferences.
create-user-preference.dto.ts: DTO for creating preferences.
update-user-preference.dto.ts: DTO for updating preferences.
src/notifications/

notifications.controller.ts: Handles sending notifications.
notifications.service.ts: Business logic for notification simulation.
send-notification.dto.ts: DTO for validating notification sending requests.
test/

user-preferences.controller.spec.ts: Tests for user preferences controller.
notifications.controller.spec.ts: Tests for notifications controller.
.env

Contains environment variables like MONGO_URI.
package.json

Lists dependencies and scripts for building and running the project.
tsconfig.json

TypeScript configuration file.
README.md

Documentation for setup, usage, and deployment.
