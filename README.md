# Walther WA2000
Your tsundere gun-girl that aims to integrate global ratelimits handling for Discord.JS v12

> (c) Girl's Frontline for [Wa2000-chan](https://iopwiki.com/wiki/WA2000)

<p align="center">
  <img src="https://iopwiki.com/images/c/ce/WA2000_costume3.png">
</p>

### Note: Before using this, please ensure you have my custom fork of [Kurasuta](https://github.com/Deivu/Kurasuta)

# Features
✅ Tsundere Gun-Girl

✅ Precious Waifu

✅ Actually fixes your 429 problems on big sharded bots

# Example
```js
const { ShardingManager } = require('kurasuta');
const { join } = require('path');
const Walther = require('wa2000');

// Require Kurasuta as normal
const manager = new ShardingManager(join(__dirname, 'main'), {
	// your options here
});

// Require WA2000 first, then pass kurasuta manager on it
const walther = new Walther(manager);

// Call .spawn() from WA2000
walther.spawn();
```

### Kashima uses this internally hence this is based on *her* structure

### You can use this soon:tm:, if you are interested on becoming a beta tester once a beta build is available, contact me at Discord `@Sāya#0113` | [Guild](https://discord.gg/FVqbtGu)