# Hubot Hear Say Adapter

## Description

This Hubot adapter says something when it hears something

## Sample Interaction

```
user> Hubot hear today say Today, tomorrow, what's the difference?
hubot> Added today -> Today, tomorrow, what's the difference?
user> Are you in today?
hubot> Today, tomorrow, what's the difference?
```

```
user> Hubot list hear
hubot> today -> Today, tomorrow, what's the difference?
user> Hubot delete hear today
hubot> Removed today
```

See [`src/hear-say.coffee`](src/hear-say.coffee) for full documentation.

## Data
[![NPM](https://nodei.co/npm/hubot-hear-say.png?downloads=true&stars=true)](https://nodei.co/npm/hubot-hear-say.png?downloads=true&stars=true)

## Installation

In hubot project repo, run:

`npm install hubot-hear-say --save`

Then add **hubot-hear-say** to your `external-scripts.json`:

```json
["hubot-hear-say"]
```
## Contribute

Just send pull request or file an issue !

