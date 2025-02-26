# discord-message

<!-- Auto Generated Below -->

## Properties

| Property     | Attribute     | Description                                                                                                                   | Type                     | Default      |
| ------------ | ------------- | ----------------------------------------------------------------------------------------------------------------------------- | ------------------------ | ------------ |
| `author`     | `author`      | The message author's username.                                                                                                | `string`                 | `'User'`     |
| `avatar`     | `avatar`      | The message author's avatar. Can be an avatar shortcut, relative path, or external link.                                      | `string`                 | `undefined`  |
| `bot`        | `bot`         | Whether the message author is a bot or not. Only works if `server` is `false` or `undefined`.                                 | `boolean`                | `false`      |
| `edited`     | `edited`      | Whether the message has been edited or not.                                                                                   | `boolean`                | `false`      |
| `ephemeral`  | `ephemeral`   | Whether to make this message ephemeral.                                                                                       | `boolean`                | `false`      |
| `highlight`  | `highlight`   | Whether to highlight this message.                                                                                            | `boolean`                | `false`      |
| `profile`    | `profile`     | The id of the profile data to use.                                                                                            | `string`                 | `undefined`  |
| `roleColor`  | `role-color`  | The message author's primary role color. Can be any [CSS color value](https://www.w3schools.com/cssref/css_colors_legal.asp). | `string`                 | `undefined`  |
| `server`     | `server`      | Whether the message author is a server crosspost webhook or not. Only works if `bot` is `false` or `undefined`.               | `boolean`                | `false`      |
| `timestamp`  | `timestamp`   | The timestamp to use for the message date.                                                                                    | `Date \| null \| string` | `new Date()` |
| `twentyFour` | `twenty-four` | Whether to use 24-hour format for the timestamp.                                                                              | `boolean`                | `false`      |
| `verified`   | `verified`    | Whether the bot is verified or not. Only works if `bot` is `true`                                                             | `boolean`                | `false`      |

---

_Built with [StencilJS](https://stenciljs.com/)_
