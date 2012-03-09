awsquery(1) -- query aws metadata for hosts 
==========================================

## SYNOPSIS

Allows the lookup and querying of EC2 hosts via the associated metadata.

## EXAMPLES

1. Look up hosts based on tags

`$ awsquery Name=app1`

2. Open iTerm with tabs for all appservers

`$ awsquery Role=app | awsssh iterm`

## CONTACT

Author is Lachlan Donald <lachlan@ljd.cc>
