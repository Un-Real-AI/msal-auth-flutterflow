# MSAL force-refresh patch

Based on msal_auth 3.5.2. Original LICENSE retained.

Adds optional forceRefresh (default false) to silent authentication in Dart,
forwarded to Android and Apple native MSAL. No application configuration or
credentials are included.
