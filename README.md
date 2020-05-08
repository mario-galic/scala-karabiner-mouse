# scala-karabiner-mouse

Bind Scala to multi-button mouse. For example, in IntelliJ Scala

| Keymap                              | Action                          |
| ----------------------------------- | ------------------------------- |
| fn + button5 (forward)              | Show Implicit Hints             |
| fn + button1                        | Run Scala Worksheet             |
| fn + button2                        | Clean Scala Worksheet           |

### How to add rule?

1. Save `.json` karabiner rules to 
```
~/.config/karabiner/assets/complex_modifications/
```
1. Enable rule under `Preferences | Complex modifications | Add rule | Enable`

### How to costumise rule?

1. Use `Karabiner-EventViewer` to figure out exact names of events
1. Follow other examples under `complex_modifications/`
1. Remove and re-add the rule
