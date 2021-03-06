## lab snippet

Create a personal or project snippet

### Synopsis



Source snippets from stdin, file, or in editor from scratch
Write title & description in editor, or using -m

```
lab snippet [flags]
```

### Options

```
  -b, --browse                browse snippets
  -d, --delete string         delete snippet with id
  -g, --global                create as a personal snippet
  -h, --help                  help for snippet
  -l, --list                  list snippets
  -m, --message stringSlice   Use the given <msg>; multiple -m are concatenated as seperate paragraphs
  -n, --name string           (optional) Name snippet to add code highlighting, e.g. potato.go for GoLang
  -p, --private               Make snippet private; visible only to project members (default: internal)
      --public                Make snippet public; can be accessed without any authentication (default: internal)
```

### SEE ALSO
* [lab](index.md)	 - A Git Wrapper for GitLab
* [lab snippet browse](lab_snippet_browse.md)	 - View personal or project snippet in a browser
* [lab snippet create](lab_snippet_create.md)	 - Create a personal or project snippet
* [lab snippet delete](lab_snippet_delete.md)	 - Delete a project or personal snippet
* [lab snippet list](lab_snippet_list.md)	 - List personal or project snippets

###### Auto generated by spf13/cobra on 7-Jan-2018
