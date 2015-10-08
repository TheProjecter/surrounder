_IntelliJ Plugin home page:_ http://plugins.intellij.net/plugin/?id=3359

Enhance default surround actions of IntelliJ IDEA by providing action which apply a template to each lines selected.


2 actions are available under the Code menu.
  * Apply template to each line _(default shortcut: shift ctrl alt J)_
  * Remove the last semicolon of lines (if any) and apply a template _(default shortcut:shift alt J)_


Example of template to use:
```
<li>$SELECTION$</li>
```

Remove semicolon is useful for templates like:
```
LOGGER.info("$SELECTION$="+$SELECTION$);
```


**Current limitations:**
  * Templates which uses variables or $END$ don't work correctly
  * Line breaks are not preserved
