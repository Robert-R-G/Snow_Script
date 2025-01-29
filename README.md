
App Name: Flurry (macOS app built with rumps)
-------------------------------------------------------------------------------------

Functionality:
Saves and loads user settings (email, Snowflake credentials, query, role, warehouse).
Allows users to update their Snowflake credentials and query via the app interface.
Connects to Snowflake using the saved credentials.
Fetches audit count from Snowflake based on the user's query.
Displays the total audit count in the app title.
Supports auto-refreshing of audit count at 2-minute intervals (configurable).
Sends notifications when auto-refresh starts/stops.
Provides a setup guide to help users gather necessary credentials for setup.
-------------------------------------------------------------------------------------

Key Features:
User can configure and update:
Email address
Snowflake account
Role
Warehouse
Query for audit count
Uses rumps for the macOS menu and interface.
Stores configuration in a JSON file (save_file.json).
-------------------------------------------------------------------------------------

UI:
Menu options to update credentials, enable/disable auto-refresh, and view the configuration.
Guide available for gathering Snowflake credentials.
Alerts users when credentials or settings are updated.
