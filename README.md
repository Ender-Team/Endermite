# Endermite

Endermite is a project aims for high performance standalone Minecraft server.

English | [简体中文](//github.com/Ender-Team/Endermite/blob/main/README_zh-CN.md)

## Features

- Written with C++ 23, providing blade edging performance
- Come with full multi-threading mechanics, maximize CPU efficient
- Manage memory totally manually, maximize the usage of RAM resources
- Improve world storing format, enhance disk efficient
- Stick to the vanilla, features would follow the Java Edition as close as it can
- Provide many optional features not in vanilla
  > i.e. Remove building height limit
- Support Java Edition and Bedrock Edition network protocol at the same time, have built-in cross-playing feature
- Mainly consult newer versions of Minecraft for developing, keep up with Mojang's latest progress as much as possible
- Open-source and free, everyone can join and contribute
- Provide a bunch of editable arguments, for convenience in customizing the server
- Complete cross-platform support, provide executables run on multiple OSs like Windows, Linux, macOS and multiple architecture
  - Would preferentially assure performance on Linux
- Built-in adjustable force entity-processing chunk feature
- Provide save backup and management feature

## Technical Roadmap

- [ ] Java Edition protocol implement
- [ ] Bedrock Edition procotol implement
- [ ] World format conversion
- [ ] Superflat world generation
- [ ] Basic creative mod world interaction (character movement, breaking/placing blocks)
- [ ] Chat system
- [ ] Creature path fiding algorithm
- [ ] Basic mobs
- [ ] Craft system
- [ ] Other interactive blocks
- [ ] Redstone system
- [ ] Villager system
- [ ] Save backup

## Future Plans

- Implement the bridge from existing Java ecosystem, and port some plugins based on Bukkit/Spigot/Paper API
- Be compatible with official datapacks, resource packs, and behavior packs
- Provide load balancing to support mega servers
- Support calling GPU via OpenCL to boost some parallel computing
- Provide visual web control panel
- Provide supported Docker images
- Implement official built-in commands
- QQ/Discord bots
- Web satellite map
- Provide complete API and support writing third-party extensions and plugins using JavaScript/TypeScript
- Implement player operation replaying feature
- Integrated basic functions of WorldEdit
