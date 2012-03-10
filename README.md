awsquery -- query aws metadata for hosts 
==========================================

A collection of tools for enumerating and manipulating AWS instances based on the tags and metadata.

## INSTALLATION

Create an access key (read-only is sensible) via IAM, then export in your shell.

```bash
export ACCESS_KEY_ID='ACCESS KEY HERE'
export SECRET_ACCESS_KEY='SECRET GOES HERE'
```

## EXAMPLES

1. Look up hosts based on tags

```bash
$ awsquery Name=app1
```

2. Open iTerm with tabs for all appservers

```bash
$ awsquery Role=app | mssh iterm -u ubuntu
```

