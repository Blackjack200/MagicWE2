TODO and bug list
- [x] Redo does not apply changes
- [ ] Setbiome does not send the changes, but //biomeinfo returns that it was set
- [ ] Count returns no messages
- [x] Wand left click does not work without breaking blocks
- [x] Brush command needs rework
- [x] Undo seems to execute the action offset by 1
- [x] Shape does not refresh after pos1 and pos2 were set once
- [x] Cylinder is 1 block too tall
- [ ] Boss bar title does not always reset
- [ ] Action with 0 blocks gets stuck (ErrorException: "Division by zero" (EXCEPTION) in "plugins/MagicWE2.phar/src/xenialdan/MagicWE2/task/AsyncFillTask" at line 119)
- [ ] The flag  is unknown
- [x] "Created new session" string contains { and }
- [ ] Session destructs upon re-login instead upon logout
- [ ] Undo "steals" blocks that were changed manually later
- [ ] Rewrite CopyClipboard to be similar to RevertClipboard
- [ ] Undo is incredibly slow - probably getAABB()