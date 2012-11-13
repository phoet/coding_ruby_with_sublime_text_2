# Snippets

- inline (con)
- from Pallet (sn con)

# Define your own

- Tools > New Snippet...

```xml
<snippet>
    <content><![CDATA['i <3 ${1:expected}!']]></content>
    <tabTrigger>subl</tabTrigger>
    <scope>source.ruby</scope>
    <description><![CDATA[<3 <3 <3]]></description>
</snippet>
```

```bash
subl ~/Dropbox/Synced\ Application\ Support/Sublime\ Text\ 2/Packages/User/
```

- http://docs.sublimetext.info/en/latest/reference/snippets.html
- http://webtempest.com/sublime-text-2-how-to-create-snippets/

# Completions


```json
// pry.sublime-completions
{
        "scope": "source.ruby",

        "completions":
        [
                { "trigger": "bp",  "contents": "binding.pry" },
                { "trigger": "bpr", "contents": "binding.pry_remote" }
        ]
}
```

- http://docs.sublimetext.info/en/latest/extensibility/completions.html
