## IntelliSense for your programming language
## IntelliSense features
## Types of completions
## Customizing IntelliSense
### Settings
### Tab Completion
### Locality Bonus
### Suggestion selection

By default, VS Code pre-selects the first suggestion in the suggestion list. If you'd like different behavior, for example, to always select the most recently used item in the suggestion list, you can use the `editor.suggestSelection` setting.

The available `editor.suggestSelection` values are:

* `first` - (default) Always select the first suggestion.
* `recentlyUsed` - The previously used item is selected unless a prefix (type to select) selects a different item.
* `recentlyUsedByPrefix` - Select items based on previous prefixes that have completed those suggestions.
Selecting the most recently used item is very useful as you can quickly insert the same completion multiple times.

"Type to select" means that the current prefix (roughly the text left of the cursor) is used to filter and sort suggestions. When this happens and when its result differs from the result of `recentlyUsed`, it will be given precedence.

When using the last option, `recentlyUsedByPrefix`, VS Code remembers which item was selected for a specific prefix (partial text). For example, if you typed `co` and then selected `console`, the next time you typed `co`, the suggestion `console` would be pre-selected. This lets you quickly map various prefixes to different suggestions, for example `co` -> `console` and `con` -> `const`.
### Snippets in suggestions
### Key bindings
## Enhance completions with AI
## Troubleshooting
## Next steps
## Common questions
### Why am I not getting any suggestions?
### Why am I not seeing method and variable suggestions?
