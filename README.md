# Malaysia API 🇲🇾

A REST API about states in Malaysia.

All information are obtained from Wikipedia.

If you have noticed some mistakes or bugs, or maybe you have any suggestions please create an issue.

This API is meant to be a read-only web API. It is **intentional** for files to be stored this way (json format) as it avoids using any database engine.

# Introduction

The states and federal territories of Malaysia are the principal administrative divisions of Malaysia. Malaysia is a federation of 13 states (Negeri) and 3 federal territories (Wilayah Persekutuan).

11 states and 2 federal territories are located on the Malay Peninsula, collectively called Peninsular Malaysia (Semenanjung Malaysia) or West Malaysia. 2 states are on the island of Borneo, and the remaining federal territory consists of islands offshore of Borneo; they are collectively referred to as East Malaysia or Malaysian Borneo. Out of the 13 states in Malaysia, 9 are monarchies.

The aim of this API is to provide static information that will be consumed by other applications.

# List of End Points

The current base url is [https://jian.sh/malaysia-api](https://jianliew.me/malaysia-api)

| State / Federal Territories | End Point                      | Status |                                                                        |
| --------------------------- | ------------------------------ | ------ | ---------------------------------------------------------------------- |
| All                         | /state/v1/all.json             | x      | [Test](https://jian.sh/malaysia-api/state/v1/all.json)             |
| Johor                       | /state/v1/johor.json           | x      | [Test](https://jian.sh/malaysia-api/state/v1/johor.json)           |
| Kedah                       | /state/v1/kedah.json           | x      | [Test](https://jian.sh/malaysia-api/state/v1/kedah.json)           |
| Kelantan                    | /state/v1/kelantan.json        | x      | [Test](https://jian.sh/malaysia-api/state/v1/kelantan.json)        |
| Malacca                     | /state/v1/malacca.json         | x      | [Test](https://jian.sh/malaysia-api/state/v1/malacca.json)         |
| Negeri Sembilan             | /state/v1/negeri_sembilan.json | x      | [Test](https://jian.sh/malaysia-api/state/v1/negeri_sembilan.json) |
| Pahang                      | /state/v1/pahang.json          | x      | [Test](https://jian.sh/malaysia-api/state/v1/pahang.json)          |
| Penang                      | /state/v1/penang.json          | x      | [Test](https://jian.sh/malaysia-api/state/v1/penang.json)          |
| Perak                       | /state/v1/perak.json           | x      | [Test](https://jian.sh/malaysia-api/state/v1/perak.json)           |
| Perlis                      | /state/v1/perlis.json          | x      | [Test](https://jian.sh/malaysia-api/state/v1/perlis.json)          |
| Sabah                       | /state/v1/sabah.json           | x      | [Test](https://jian.sh/malaysia-api/state/v1/sabah.json)           |
| Sarawak                     | /state/v1/sarawak.json         | x      | [Test](https://jian.sh/malaysia-api/state/v1/sarawak.json)         |
| Selangor                    | /state/v1/selangor.json        | x      | [Test](https://jian.sh/malaysia-api/state/v1/selangor.json)        |
| Terengganu                  | /state/v1/terengganu.json      | x      | [Test](https://jian.sh/malaysia-api/state/v1/kelantan.json)        |
| Kuala Lumpur                | /state/v1/kuala_lumpur.json    | x      | [Test](https://jian.sh/malaysia-api/state/v1/kuala_lumpur.json)    |
| Labuan                      | /state/v1/labuan.json          | x      | [Test](https://jian.sh/malaysia-api/state/v1/labuan.json)          |
| Putrajaya                   | /state/v1/putrajaya.json       | x      | [Test](https://jian.sh/malaysia-api/state/v1/putrajaya.json)       |

_x_ indicates that the entry is completed.

# Usage Example

```bash
curl https://jian.sh/malaysia-api/state/v1/selangor.json
```

would retrieve

```json
{
  "name": "Selangor",
  "administrative_division": "State of Malaysia",
  "full_name_jawi": "سلاڠور دار الإحسان",
  "full_name": "Selangor Darul Ehsan",
  "jawi_name": "سلاڠور",
  "chinese_name_simplified": "雪兰莪",
  "chinese_name_traditional": "雪蘭莪",
  "tamil_name": "சிலாங்கூர்",
  "motto": "Dipelihara Allah",
  "anthem": "Duli Yang Maha Mulia",
  "coordinates": "3°20′N 101°30′E",
  "capital": "Shah Alam",
  "royal_capital": "Klang",
  "government_type": ["Parliamentary", "constitutional monarchy"],
  "government_sultan": "Sharafuddin",
  "chief_minister": "Amirudin Shari (PH-PKR)",
  "area": "8.104km2",
  "highest_elevation": "1,830 m (6,004 ft)",
  "population_total": "6,448,400",
  "population_demonym": "Selangorean / Selangorian",
  "human_development_index": "0.855 (very high)",
  "time_zone_summer": "UTC+8 (not observed)",
  "postal_code": ["40xxx to 48xxx", "63xxx, 640xx", "68xxx"],
  "calling_code": "03",
  "ISO_3166_code": "MY-10",
  "vehicle_registration": "B",
  "federated_into_fms": 1895,
  "japanese occupation": 1942,
  "accession_into_fom": "31 August 1957",
  "website": ["www.selangor.gov.my", "www.selangorku.com"],
  "description": "Selangor (/səˈl&aelig;ŋər/; Malay: [s(ə)laŋo(r)]), also known by its Arabic honorific Darul Ehsan, or &quot;Abode of Sincerity&quot;, is one of the 13 states of Malaysia. It is on the west coast of Peninsular Malaysia and is bordered by Perak to the north, Pahang to the east, Negeri Sembilan to the south and the Strait of Malacca to the west. Selangor surrounds the federal territories of Kuala Lumpur and Putrajaya, both of which were previously part of it. The state capital of Selangor is Shah Alam and its royal capital is Klang. Petaling Jaya and Subang Jaya received city status in 2006 and 2019, respectively. Selangor is one of four Malaysian states that contain more than one city with official city status; the others are Sarawak, Johor, and Penang. The state of Selangor has the largest economy in Malaysia in terms of gross domestic product (GDP), with RM 239.968 billion (roughly US$55.5 billion) in 2015, comprising 22.6% of the country's GDP. It is the most developed state in Malaysia; it has good infrastructure such as highways and transport, and has the largest population in Malaysia, a high standard of living and the lowest poverty rate in the country."
}
```
