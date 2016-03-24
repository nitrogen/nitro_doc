# NitroDoc

A system for dealing with Nitrogen documentation.

This will be usable with any Nitrogen-type project, and will focus on
searchability and keywords (highlighted within the documentation).

Documentation will be written in a modified markdown (which currently has to be
converted from org-mode), to provide things like:

1) Keyword highlighting for searchability
2) Record attribute explanations
3) Function definitions
4) Automatic breadcrumbs
5) Differentiation of core vs plugins
6) Inline Demos? That could be cool.
7) A nice side-bar type view like erldocs.com (or just using the textbox_autocomplete, not sure yet).
8) It would be interesting to read from comments, perhaps something like:

```erlang
%% <nitrodoc record=record_name>
%% <nitrodoc function=function_name>
%% <nitrodoc handler=handler_name>
%% Some documentation
%% </nitrodoc>
```
But that could be problematic for organization and whatnot. We'll see.

# License

Copyright 2016 Jesse Gumm

MIT License
