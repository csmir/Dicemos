# 🎲 Dicemos
### [Invite Dicemos to your servers!](https://discord.com/oauth2/authorize?client_id=1132013697401901076)
The primary tool in Discord for all things dice. Roll simple d6'es, or complex equations in any way you like. Extract all the details about the equation and review the results in your personal history.

⚠️ To read about data usage, refer to the [privacy statement](PRIVACY.md). 

*This product is powered by [Netcord](https://github.com/NetCordDev/NetCord) and [Commands.NET](https://github.com/csmir/Commands.NET).*

## 🧮 Usage:

`/roll` calculates your input (`formula: ...`) and provides a consise and accurate result. It is curated to a set of provided options (`options: ...`), which mutate the input or response as it sees fit.

#### Example input:

- `/roll`
- `/roll formula:1d20`
- `/roll options:rolls:5`
- `/roll formula:1d20 options:secret`

> Without arguments, this command will open a modal which allows for more extensive input specification. Some options do not support direct roll input, and instead need this modal to function.

### Roll Options

The `/roll` command accepts `options`, formatted as the following:

#### Secret
The roll will be hidden (ephemeral) from the channel and will only be visible to the user who rolled it.

> Flags: `secret`, `s`, `hidden`, `hide`, `h`

#### Master
> Flags: `master`, `gm`, `m`
The roll will be rolled in private, notifying the users in the channel that a roll has been made.

#### Masked

The roll will be masked and will not display the input values or output details.

> Flags: `masked`, `mask`

#### Invisible

The roll will be completely invisible and will not be displayed to the channel or the report channel.

> Flags: `invisible`, `inv`, `i`

#### Average

The result will return the average of the dices rolled.

> Flags: `average`, `av`

#### Max

The result will return the maximum possible result of the dices rolled.

> Flags: `max`, `maximum`, `highest`, `top`

#### Min

The result will return the minimum possible result of the dices rolled.

> Flags: `min`, `minimum`, `lowest`, `bottom`

#### Critical

The result will return a critical hit, taking the maximum possible result of the dices rolled.

> Flags: `critical`, `crit`, `c`

#### Limitless

The roll will ignore all limitations.

> Flags: `limitless`, `limit`, `l`

#### Above

The result will return how many rolls exceeded the defined value.

> Flags: `above`, `exceeds`

#### Below

The result will return how many rolls resulted below the defined value.

> Flags: `below`, `b`

#### Matches

The result will return how many rolls matched the defined value.

> Flags: `matches`, `match`, `is`

#### Explode

The dice will explode on the defined value, rolling again and adding the result to the total.

> Flags: `explode`, `exp`, `ex`, `e`

#### Advantage

The result will return the highest rolled value.

> Flags: `advantage`, `adv`, `a`

#### Disadvantage

The result will return the lowest rolled value.

> Flags: `disadvantage`, `disadv`, `dis`, `d`

#### Rolls

The result will return the number of rolls made.

> `rolls`, `r`

## Contributing

Dicemos is not open source. There is no interest in open-source collaborations. 
To report bugs or submit suggestions, make an issue here, or find me on Discord: [NET-work](https://discord.com/invite/T7hCvShAx5).
