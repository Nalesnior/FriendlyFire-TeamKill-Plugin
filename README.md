# FriendlyFire-TeamKill-Plugin
Simple plugin for scp:sl for Exiled. It shows a warning message to the player if he's damage or kill teammate.

## Configuration
```cs
public bool IsEnabled { get; set; } = true;
public bool Debug { get; set; } = false;
public bool FriendlyFire { get; set; } = true;
public bool TeamKill { get; set; } = true;
public bool ShowMessage { get; set; } = true;
public string Message { get; set; } = "Teamkilling is not allowed!";
public string FriendlyFireMessage { get; set; } = "Friendly fire is not allowed!";
public string MessageForVictim { get; set; } = "You have been killed by your teammate! ({Attacker})";
public string FriendlyFireMessageForVictim { get; set; } = "You have been hit by your teammate! ({Attacker})";
```
