<p align="center">
<img src="/imageassets/logo.png" alt="" width="30%" />
<h1 align="center">Limon Bot<a style="margin-left: 15px;" href="https://github.com/SagiriHimoto/LimonBot/commits/main">(<img src="https://img.shields.io/github/last-commit/SagiriHimoto/LimonBot">)</a></h1></p>

>**This is an in-dev bot for super fun testing! Like, if you wanna add this to your server, beware, I might get a sudden urge to backdoor it or something! idk!!!!!**

### Cuz, why not

Like, I literally had no reason to make it, yet here we are

## Like, a reminder for me to not f this up

Slash commands can take some time to get registered globally, so if you want to test a command you should use
the `@app_commands.guilds()` decorator so that it gets registered instantly. Example:

```py
@commands.hybrid_command(
  name="command",
  description="Command description",
)
@app_commands.guilds(discord.Object(id=GUILD_ID)) # Place your guild ID here
```

## Also like

like, thanks to the fella who made a template that I used. like, good stuff dude, props
## Issues or Questions

If you have any issues or questions, like... contact me on discord or twitter? idk

- @SagiriHimoto

I go outside and touch grass daily, so like, don't expect replies

## Built With

- [Python 3.11.5](https://www.python.org/)

## License

Idk how to licence stuff. If you want crappy code, like, go ahead and steal from me, I guess. This original template is licensed under the Apache License 2.0