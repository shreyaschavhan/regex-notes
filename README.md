# ⁍ 𝐑𝐞𝐠𝐞𝐱 𝐍𝐨𝐭𝐞𝐬

Best Reources:
- [Interactive Regex Tutorial](regexone.com)
- [Best Youtube Tutorial Video](https://youtu.be/sa-TUpSx1JA)
- [Learn Regex the easy way](https://github.com/ziishaned/learn-regex)
- [Best Advice on the Internet](https://www.reddit.com/r/learnprogramming/comments/cduxuu/comment/etwj6hj/?utm_source=share&utm_medium=web2x&context=3)

Practice:
- [Regex Golf](https://alf.nu/RegexGolf)
- [regexcrossword.com](https://regexcrossword.com/)
- [regex101.com](https://regex101.com/quiz/1)
- [Hackerrank Regex Practise](https://www.hackerrank.com/domains/regex?filters%5Bstatus%5D%5B%5D=unsolved)

## 𝐄𝐬𝐜𝐚𝐩𝐞 𝐂𝐡𝐚𝐫𝐚𝐜𝐭𝐞𝐫𝐬

```
You should always escape these characters: .[{()\^|?*+
Backslash is used to escape characters

For Example: 
. - selects everything
\. - matches literal dot

You have to also escape a backslash itself i.e. \\ will result in \
```

## 𝐌𝐚𝐭𝐜𝐡𝐞𝐬 𝐂𝐡𝐚𝐫𝐚𝐜𝐭𝐞𝐫𝐬

Key | Meaning
---|---
`.` | Any character except new line
`\d` | Digit (0-9)
`\D` | Not a Digit (0-9)
`\w` | Word Characters (a-z, A-Z, 0-9)
`\W` | Not a word character 
`\s` | Whitespace (space, tab, newline)
`\S` | Not Whitespace (space, tab, newline)



## 𝐀𝐧𝐜𝐡𝐨𝐫𝐬 - 𝐌𝐚𝐭𝐜𝐡𝐞𝐬 𝐯𝐢𝐬𝐢𝐛𝐥𝐞 𝐩𝐨𝐬𝐢𝐭𝐢𝐨𝐧𝐬 𝐛𝐞𝐭𝐰𝐞𝐞𝐧 𝐜𝐡𝐚𝐫𝐚𝐜𝐭𝐞𝐫𝐬

Key | Meaning
--- | ---
`\b` | Word boundary
`\B` | Not a word boundary
`^` | Beginning of a string
`$` | End of a string

## ??

Key | Meaning
--- | ---
`[ ]` | Matches characters in brackets
`[^ ]` | Matches characters NOT in brackets
`\|` | Either Or
`()` | Group

## 𝐐𝐮𝐚𝐧𝐭𝐢𝐟𝐢𝐞𝐫𝐬

Key | Meaning
--- | ---
`*` | 0 or more
`+` | 1 or more
`?` | 0 or one
`{3}` | exact number
`{3,4}` | range of numbers (minimum, maximum)


