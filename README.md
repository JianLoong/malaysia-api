# Malaysia API 🇲🇾

A Complete REST API about states in Malaysia

Most of the data is taken from the Wikipedia.

If you have noticed some mistakes or bugs, or maybe you have any suggestions please create an issue.

# Introduction

The states and federal territories of Malaysia are the principal administrative divisions of Malaysia. Malaysia is a federation of 13 states (Negeri) and 3 federal territories (Wilayah Persekutuan).

11 states and 2 federal territories are located on the Malay Peninsula, collectively called Peninsular Malaysia (Semenanjung Malaysia) or West Malaysia. 2 states are on the island of Borneo, and the remaining federal territory consists of islands offshore of Borneo; they are collectively referred to as East Malaysia or Malaysian Borneo. Out of the 13 states in Malaysia, 9 are monarchies.

# List of End Points

The current base url is https://jianliew.me/malaysia-api

| State / Federal Territories | End Point                      |
| --------------------------- | ------------------------------ |
| All                         | /state/v1/all.json             |
| Johor                       | /state/v1/johor.json           |
| Kedah                       | /state/v1/kedah.json           |
| Kelantan                    | /state/v1/kelantan.json        |
| Malacca                     | /state/v1/malacca.json         |
| Negeri Sembilan             | /state/v1/negeri_sembilan.json |
| Pahang                      | /state/v1/pahang.json          |
| Penang                      | /state/v1/penang.json          |
| Perak                       | /state/v1/perak.json           |
| Kedah                       | /state/v1/kedah.json           |
| Perlis                      | /state/v1/perlis.json          |
| Sabah                       | /state/v1/Sabah.json           |
| Sarawak                     | /state/v1/Sarawak.json         |
| Selangor                    | /state/v1/selangor.json        |
| Terengganu                  | /state/v1/terengganu.json      |
| Kuala Lumpur                | /state/v1/kuala_lumpur.json    |
| Labuan                      | /state/v1/labuan.json          |
| Putrajaya                   | /state/v1/putrajaya.json       |

# Usage Example

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
