**SteamGroups** automatically adds members of Steam group(s) to a specific permissions group, checking for updates every 60 seconds. Users no longer in the Steam group(s) will automatically be removed from the permissions group.

## Configuration
You can configure the settings in the `SteamGroups.json` file under the `oxide/config` directory.
```json
{
  "Group Setup": [
    {
      "Steam": "CitizenSO",
      "Oxide": "default"
    },
    {
      "Steam": "OxideMod",
      "Oxide": "default"
    }
  ],
  "Update Interval (Seconds)": 300
}
```
