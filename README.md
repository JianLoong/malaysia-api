# Malaysia API 🇲🇾

A Complete REST API about states in Malaysia

Most of the data is taken from the Wikipedia.

If you have noticed some mistakes or bugs, or maybe you have any suggestions please create an issue.

# Introduction

The states and federal territories of Malaysia are the principal administrative divisions of Malaysia. Malaysia is a federation of 13 states (Negeri) and 3 federal territories (Wilayah Persekutuan).

11 states and 2 federal territories are located on the Malay Peninsula, collectively called Peninsular Malaysia (Semenanjung Malaysia) or West Malaysia. 2 states are on the island of Borneo, and the remaining federal territory consists of islands offshore of Borneo; they are collectively referred to as East Malaysia or Malaysian Borneo. Out of the 13 states in Malaysia, 9 are monarchies. 

# List of End Points

/state/v1/all.json
/state/v1/selangor.json

# Example

```bash
curl https://jianliew.me/malaysia-api/state/v1/selangor.json
```

would retrieve 

```json
{
    "name": "Selangor",
    "full_name": "Selangor Darul Ehsan",
    "jawi_name": "سلاڠور",
    "chinese_name_simplified": "雪兰莪",
    "chinese_name_traditional": "雪蘭莪",
    "tamil_name": "சிலாங்கூர்",
    "motto": "Dipelihara Allah",
    "capital": "Shah Alam"
}
```


