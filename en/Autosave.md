---
title: Autosave
---

# Autosave

The autosave feature helps prevent loss of data if your computer or JabRef crashes. When autosave is enabled, JabRef will check regularly (with a configurable time interval) whether any of your databases have been modified since your last save. For each one that has, JabRef will save a copy of the database in the file named `.$[file]$`, where `[file]` is the file name of the database in question. The autosave file lies in the same directory as the bib file.

The autosave file will be deleted whenever you actively save the database, and if you quit JabRef normally. However, if JabRef is shut down due to a crash, the autosave file will remain. In this case, it will be detected the next time you attempt to open the database, and you will be given the option to recover the database from the autosave file.

Autosave is enabled by default, with a save interval of 5 minutes. If you prefer, you can disable the option to prompt before using an autosave. In this case, JabRef will quietly recover the database without providing any notifications.
