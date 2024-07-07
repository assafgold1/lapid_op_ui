
# Lapid Operational Whiskey UI/UX By Assaf
![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)
______________________________
#### files info -

Assaf@assafs-MacBook-Pro Lapid Operational Whiskey % node cake.js
Total files: 50836
- .js    ██████████████████████                             44.14%
- .ts    ████████                                           15.03%
- .map   ███████                                            13.62%
- .png   ███                                                6.70%
- .json  ██                                                 4.85%
- .md    ██                                                 4.29%
- .h     ██                                                 3.02%
- .java  █                                                  2.24%
- .tsx   █                                                  1.18%
- .cpp   █                                                  1.03%
- .swift                                                    0.90%
- .svg                                                      0.78%
- .xml                                                      0.64%
- .yml                                                      0.39%
- .txt                                                      0.33%
- .class                                                    0.29%
- .html                                                     0.14%
- .pem                                                      0.08%
- .properties                                               0.07%
- .rb                                                       0.06%
- .jpg                                                      0.06%
- .css                                                      0.04%
- .plist                                                    0.03%
- .bat                                                      0.02%
- .dll                                                      0.02%
- .exe                                                      0.01%
- .conf                                                     0.01%
- .cs                                                       0.01%
- .bak                                                      0.00%
- .toml                                                     0.00%
- .py                                                       0.00%
- .log                                                      0.00%
- .rtf                                                      0.00%
- .mp3                                                      0.00%
- .zip                                                      0.00%
- .scss                                                     0.00%
- .cmd                                                      0.00%
- .env                                                      0.00%
- .webp                                                     0.00%
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

If you have any feedback, please reach out to us at fake@fake.com


![Logo](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)


## Screenshots
<table>
  <tr>
    <td align="center"><img src="https://i.ibb.co/XLHrywc/he.png" width="100px;" alt="Ben Hong"/><br /><sub><b>Hebrew</td>
    <td align="center"><img src="https://i.ibb.co/XLHrywc/en.png" width="100px;" alt="Ben Hong"/><br /><sub><b>English</td>
    <td align="center"><img src="https://i.ibb.co/XLHrywc/es.png" width="100px;" alt="Ben Hong"/><br /><sub><b>Spanish</td>
    <td align="center"><img src="https://i.ibb.co/XLHrywc/rs.png" width="100px;" alt="Ben Hong"/><br /><sub><b>russian</td>
    <td align="center"><img src="https://i.ibb.co/XLHrywc/gr.png" width="100px;" alt="Ben Hong"/><br /><sub><b>german</td>
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



