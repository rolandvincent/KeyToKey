# Key Trigger

## Whats is Key Trigger?

Key trigger is a keyboard keys to run Action script.

## What is Action?

Action is the script to run after keys trigger was triggered.

## How to Write Action Script

#### Syntax
Script syntax is written in square brackets `[]`, for example `[ENTER]`.

#### String
To write strings you can use " and '. You can write strings using escape characters, for example 
```python
"You: I'm \"Cool\"."
```
Give output `I'm "Cool".`

If you write string outside syntax block, your input send using [SendKeys](https://learn.microsoft.com/en-us/dotnet/api/system.windows.forms.sendkeys?view=windowsdesktop-7.0) function, so it will not affected of any script before.

If you write text outside a string and script block, your input send using _KeyToKey Keyboard Input_ and will affected by script before like `HOLDTIME` or `TIME`. You can paste your copied text into Action field with _Paste Special_ (CTRL+SHIFT+V or Right Click Menu) to automatic escape your pasted text. 

#### Syntax List
Here all list of syntax you can use

1. 
