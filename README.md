
# Lapid Operational Whiskey UI/UX By Assaf
![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)
______________________________
#### files info -

Assaf@assafs-MacBook-Pro Desktop % node cake.js
Total files: 77928
- .js    ██████████████████████                             43.88%
- .ts    ███████                                            14.37%
- .map   ██████                                             11.17%
- .json  ██                                                 4.86%
- .md    ██                                                 4.71%
- .h     ██                                                 4.57%
- .png   ██                                                 4.53%
- .java  ██                                                 3.26%
- .cpp   █                                                  1.72%
- .kt    █                                                  1.24%
- .xml                                                      0.86%
- .tsx                                                      0.78%
- .svg                                                      0.76%
- .m                                                        0.70%
- .swift                                                    0.58%
- .txt                                                      0.49%
- .yml                                                      0.44%
- .class                                                    0.19%
- .html                                                     0.13%
- .sh                                                       0.11%
- .rb                                                       0.08%
- .jpg                                                      0.07%
- .s                                                        0.07%
- .properties                                               0.06%
- .pem                                                      0.05%
- .lua                                                      0.04%
- .dll                                                      0.03%
- .plist                                                    0.03%
- .coffee                                                   0.03%
- .css                                                      0.03%
- .kts                                                      0.03%
- .pro                                                      0.03%
- .bat                                                      0.02%
- .exe                                                      0.01%
- .conf                                                     0.01%
- .toml                                                     0.01%
- .bak                                                      0.01%
Assaf@assafs-MacBook-Pro Lapid Operational Whiskey % 


## Run Locally


Go to the project directory

```bash
    cd App 
```

Install dependencies

```bash
npm install expo --legacy-peer-deps
```

Start the App

```bash
  npx expo start
```
Start Server
```
  cd Tools/server
  npm install
  node server
```

## Features

- open same gates via palgate api 
- send sames images to the operational rooms
- 
- Cross platform


## Feedback

If you have any feedback, please reach out to us at assaf@taninoni.com


![Logo](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)


## Screenshots
<table>
  <tr>
    <td align="center"><img src="https://i.ibb.co/XLHrywc/he.png" width="100px;" alt="Ben Hong"/><br /><sub><b>Hebrew</td>
  </tr>
</table

## Support

For support, email assaf@taninoni.com


## Tech Stack

**Client:** React, TailwindCSS

**Server:** Node, Express


## Authors

- [assaf - github](https://www.github.com/assafgold1)
- [assaf - gitlab](https://gitlab.com/assafg41)
- [dvir - github](https://github.com/pizzabossxd)

## API Reference

#### Get all items

```http
  GET /api/items
```

| NAME | URL     | / 
| :-------- | :-------                       |:------
| `NFRA` | `http://lapid.NFRA.gov.il:73294` | use headers
| `BackUp` | `http://nfra.lapid.taninoni.com:3000` ||use headers
| `Merkava` | `merkava.gov.il` |You need to connect via sap  -  www.sap.com|

#### Get Sms

```http
  GET http://lapid.NFRA.gov.il:73294/api/data/reference/users/<city>/?<id>?<phone number>?<birth data>
```

#### Get Users

```http
GET http://lapid.NFRA.gov.il:73294/api/acsses/data/rlz/v/teen/data
```



