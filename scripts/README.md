1. Copy this script into claude scripts
   
```
mkdir -p ~/.claude/scripts
cp context-bar.sh ~/.claude/scripts/
chmod +x ~/.claude/scripts/context-bar.sh
```

2. Update your ~/.claude/settings.json:
```
{
  "statusLine": {
    "type": "command",
    "command": "~/.claude/scripts/context-bar.sh"
  }
}
```