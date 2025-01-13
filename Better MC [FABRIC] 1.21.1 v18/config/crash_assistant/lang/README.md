Hi Localizer!

If you want to add new language to the mod, please create a pull request with a new or modified file:
https://github.com/KostromDan/Crash-Assistant/

lang files locate here:
common_config/src/main/resources/lang

If you want to change some text, don't edit the jar directly. Instead, you can modify the files in config/crash_assistant/lang.
You can also add an entirely new language file in this directory, and it will work.

"$DEFAULT" value means value will be taken from jar lang(if exists), else from en_us.