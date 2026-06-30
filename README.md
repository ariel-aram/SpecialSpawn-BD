# Ballsdex v3 Special Spawn

This extra allows you to configure an secondary spawn channel with rare collectibles being more common, useful for dex bots seeking to give benefits for certain users.

That's right, if you want to consider an booster-only spawn channel or anything else, this extra is absolutely for you.

## Commands

| Command | Description |
| ------- | ----------- |
| `/config special <channel>` | Configures the secondary special spawn channel. |

## Installation

Literally, all you need to do is to configure `config/extra.toml` and restart the bot, duh.

```toml
[[ballsdex.packages]]
location = "git+https://github.com/ariel-aram/SpecialSpawn-BD@1.0.0#master"
path = "specialspawn"
enabled = true
```

**Example of multiple extras:**

```toml
[[ballsdex.packages]]
location = "git+https://github.com/ariel-aram/SpecialSpawn-BD@1.0.0#master"
path = "specialspawn"
enabled = true

[[ballsdex.packages]]
location = "git+https://github.com/Mr-Lore/Ariel-is-a-GothMommy@6.9.9#master"
path = "gothmommy"
enabled = true
```

That's all, now scram. >:3
