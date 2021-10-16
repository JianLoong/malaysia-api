# Malaysia API 🇲🇾

A Complete REST API about states in Malaysia

Most of the data is taken from the Wikipedia.

If you have noticed some mistakes or bugs, or maybe you have any suggestions please create an issue.

# Introduction

The states and federal territories of Malaysia are the principal administrative divisions of Malaysia. Malaysia is a federation of 13 states (Negeri) and 3 federal territories (Wilayah Persekutuan).

11 states and 2 federal territories are located on the Malay Peninsula, collectively called Peninsular Malaysia (Semenanjung Malaysia) or West Malaysia. 2 states are on the island of Borneo, and the remaining federal territory consists of islands offshore of Borneo; they are collectively referred to as East Malaysia or Malaysian Borneo. Out of the 13 states in Malaysia, 9 are monarchies.

# List of End Points

The current base url is https://jianliew.me/malaysia-api

| State / Federal Territories | End Point                      | Status |
| --------------------------- | ------------------------------ | ------ |
| All                         | /state/v1/all.json             | x      |
| Johor                       | /state/v1/johor.json           | x      |
| Kedah                       | /state/v1/kedah.json           | x      |
| Kelantan                    | /state/v1/kelantan.json        |        |
| Malacca                     | /state/v1/malacca.json         |        |
| Negeri Sembilan             | /state/v1/negeri_sembilan.json | x      |
| Pahang                      | /state/v1/pahang.json          |        |
| Penang                      | /state/v1/penang.json          |        |
| Perak                       | /state/v1/perak.json           |        |
| Perlis                      | /state/v1/perlis.json          | x      |
| Sabah                       | /state/v1/Sabah.json           |        |
| Sarawak                     | /state/v1/Sarawak.json         |        |
| Selangor                    | /state/v1/selangor.json        | x      |
| Terengganu                  | /state/v1/terengganu.json      |        |
| Kuala Lumpur                | /state/v1/kuala_lumpur.json    | x      |
| Labuan                      | /state/v1/labuan.json          | x      |
| Putrajaya                   | /state/v1/putrajaya.json       | x      |

_x_ indicates that the entry is completed.

# Usage Example

```bash
curl https://jianliew.me/malaysia-api/state/v1/selangor.json
```

would retrieve

```json
{
  "name": "Selangor",
  "administrative_division": "State of Malaysia",
  "full_name": "Selangor Darul Ehsan",
  "jawi_name": "سلاڠور",
  "chinese_name_simplified": "雪兰莪",
  "chinese_name_traditional": "雪蘭莪",
  "tamil_name": "சிலாங்கூர்",
  "motto": "Dipelihara Allah",
  "capital": "Shah Alam",
  "royal_captial": "Klang",
  "area": "8.104km2",
  "population": "6,448,400",
  "description": "Selangor (/səˈl&aelig;ŋər/; Malay: [s(ə)laŋo(r)]), also known by its Arabic honorific Darul Ehsan, or &quot;Abode of Sincerity&quot;, is one of the 13 states of Malaysia. It is on the west coast of Peninsular Malaysia and is bordered by Perak to the north, Pahang to the east, Negeri Sembilan to the south and the Strait of Malacca to the west. Selangor surrounds the federal territories of Kuala Lumpur and Putrajaya, both of which were previously part of it. The state capital of Selangor is Shah Alam and its royal capital is Klang. Petaling Jaya and Subang Jaya received city status in 2006 and 2019, respectively. Selangor is one of four Malaysian states that contain more than one city with official city status; the others are Sarawak, Johor, and Penang. The state of Selangor has the largest economy in Malaysia in terms of gross domestic product (GDP), with RM 239.968 billion (roughly US$55.5 billion) in 2015, comprising 22.6% of the country's GDP. It is the most developed state in Malaysia; it has good infrastructure such as highways and transport, and has the largest population in Malaysia, a high standard of living and the lowest poverty rate in the country."
}
```
