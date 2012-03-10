awsquery -- query aws metadata for hosts 
==========================================

A collection of tools for enumerating and manipulating AWS instances based on the tags and metadata.

## EXAMPLES

1. Look up hosts based on tags

```bash
$ awsquery Name=app1
```

2. Open iTerm with tabs for all appservers

```bash
$ awsquery Role=app | mssh iterm -u ubuntu
```

