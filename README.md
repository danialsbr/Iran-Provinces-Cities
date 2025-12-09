# Iran Provinces & Cities - ایران استان‌ها و شهرها 🇮🇷

<div align="center">

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![JSON Database](https://img.shields.io/badge/Data-JSON-brightgreen)](https://raw.githubusercontent.com/yourusername/Iran-Provinces-Cities/main/iran-cities.json)
[![Cities Count](https://img.shields.io/badge/Cities-2%2C942%2B-orange)](#)
[![Provinces](https://img.shields.io/badge/Provinces-31-blue)](#)

</div>

<h2 align="center">لیست تمام استان ها و شهر های ایران </h2>

A complete and up-to-date JSON database containing all **31 provinces** and **2,942+ cities** of Iran with Persian names.

Perfect for:
- Web forms (dropdown selects)
- Mobile applications
- Location-based services
- Administrative division lookups
- Data visualization & mapping

---

### آمار کلی / Summary

| Province (استان)             | Cities (شهرها) | 
|-------------------------------|-----------------|
| آذربایجان شرقی                 | 168             |
| آذربایجان غربی                 | 169             |
| اردبیل                         | 64              |
| اصفهان                         | 264             |
| البرز                          | 25              |
| ایلام                          | 56              |
| بوشهر                          | 51              |
| تهران                          | 117             |
| چهارمحال و بختیاری             | 58              |
| خراسان جنوبی                   | 38              |
| 
| خراسان رضوی                    | 210             |
| خراسان شمالی                   | 31              |
| خوزستان                        | 149             |
| زنجان                          | 48              |
| سمنان                          | 93              |
| سیستان و بلوچستان              | 122             |
| فارس                           | 195             |
| قزوین                          | 53              |
| قم                            | 12              |
| کردستان                        | 63              |
| کرمان                          | 125             |
| کرمانشاه                       | 64              |
| کهگیلویه و بویراحمد            | 32              |
| گلستان                         | 42              |
| گیلان                          | 18              |
| لرستان                         | 69              |
| مازندران                       | 156             |
| مرکزی                          | 102             |
| هرمزگان                        | 79              |
| همدان                          | 67              |
| یزد                            | 43              |

**Total: 31 provinces · 2,942+ cities**

---

### فایل‌ها / Files

- `iran-cities.json` → Full list with province → cities structure
- `iran-provinces.json` → Only provinces (optional lightweight version)
- `iran-cities-flat.json` → Flat array of all cities with province info (great for search/filter)

---

### مثال استفاده / Usage Example (JavaScript)

```js
fetch('fetch('https://raw.githubusercontent.com/danialsbr/Iran-Provinces-Cities/main/iran-cities.json')
  .then(res => res.json())
  .then(data => {
    console.log(data["تهران"]); // → ["تهران", "ری", "شمیرانات", ...]
  });')
  .then(res => res.json())
  .then(data => {
    console.log(data["تهران"]); // → ["تهران", "ری", "شمیرانات", ...]
  });
