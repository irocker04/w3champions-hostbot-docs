# Flo

## How to use

- Download the client
- Run `flo.exe`
- Goto https://w3flo.com
- Create Game & Invite players
- Click `Start Game`
- Join the LAN game
- The game will start when all players joined

## Troubleshooting

- If you cannot see the LAN game:
  - Check Windows Firewall settings
  - Ensure Warcraft III's LAN is functioning
- If the WebUI is not working
  - Refresh
  - Restart flo.exe (don't do this if you are in a Warcraft III game, you will disconnect)

# Limitations

- Only maps included in Warcraft III are supported. Other maps can be supported, but need to generate map checksum in advance.
- Only supports Melee maps, custom forces and pre-defined players are
  currently not supported.

# Known Issues

- Some Melee maps are not supported:
  > Load map detail failed
  > map: read map info: bytes does not match tag `"TRIGSTR_"`)
- Not all error messages are displayed on the WebUI. Sometimes you have to check the terminal window for error messages.
- Lagging screen is not yet implemented.
- Desync detection is not yet implemented.
