# Bazarr-UpgradeSync
## A tool for auto-syncing upgraded mediafiles in Bazarr

UpgradeSync is a tool that can scan Bazarr for monitored media, determine whether the last sync performed was done after any changes to the mediafiles through Radarr/Sonarr, and schedule a resync if needed. It can be run as a single pass script (callable by a scheduled task or crontab).
