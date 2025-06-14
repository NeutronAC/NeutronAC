# Neutron AC - Advanced FiveM Anticheat System

## Features
- Comprehensive anticheat protection
- Advanced ban system with adaptive cards
- Admin panel with permissions management
- Webhook integration for logging
- Bypass system for trusted players
- Real-time player monitoring

## Installation
1. Extract the `neutron_ac` folder to your resources directory
2. Add `ensure neutron_ac` to your server.cfg
3. Configure the `config.cfg` file with your webhooks and settings
4. Restart your server

## Configuration
Edit the `config.cfg` file to customize:
- Webhook URLs for different events
- Enable/disable specific anticheat features
- Blacklisted weapons, vehicles, and names
- Detection limits and thresholds

## Commands
- `/nac-ban [id] [reason] [hours]` - Ban a player
- `/nac-unban [ban id]` - Unban a player
- `/nac-bypass [id]` - Add bypass for a player
- `/nac-remove-bypass [discord id]` - Remove bypass
- `/n-ac` - Open admin panel

## Support
For support and updates, visit: https://github.com/NeutronAC/NeutronAC
