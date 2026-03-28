# Real Estate Listings Dataset (Saudi Arabia)

Dataset from: (https://www.kaggle.com/datasets/mohdph/saudi-arabia-real-estate-dataset)

## Context
This SQLite database contains data scraped from [aqar.fm](https://www.aqar.fm), a leading platform for real estate in Saudi Arabia where users can share listings for sale or rental.

The dataset includes **all publicly available listings** up to the date of collection (**05/06/2023**).

---

## Content

### Listings Table
The main table in this dataset is `Listings`, which contains the following fields:

| Column | Type | Description |
|--------|------|-------------|
| `id` | integer | Listing ID |
| `uri` | string | Listing URL |
| `title` | string | Listing title |
| `price` | integer | Listing price in Saudi Riyal |
| `content` | text | Listing description |
| `imgs` | text | JSON array of listing images |
| `refresh` | integer | Unix timestamp of last refresh by the user |
| `category` | integer | Category ID: <br> 1=Apartment (rental), 2=Land (sell), 3=Villa (sell), 4=Floor (rental), 5=Villa (rental), 6=Apartment (sell), 7=Building (sell), 8=Store (rental), 9=House (sell), 10=Esterahah (sell), 11=House (rental), 12=Farm (sell), 13=Esterahah (rental), 14=Office (rental), 15=Land (rental), 16=Building (rental), 17=Warehouse (rental), 18=Campsite (rental), 19=Room (rental), 20=Store (sell), 21=Furnished apartment, 22=Floor (sell), 23=Chalet (rental) |
| `beds` | integer | Number of bedrooms |
| `livings` | integer | Number of living rooms |
| `wc` | integer | Number of bathrooms |
| `area` | integer | Listing area (m²) |
| `type` | integer | Listing type |
| `street_width` | integer | Width of the street |
| `age` | integer | Age of the property |
| `last_update` | integer | Unix timestamp of last update |
| `street_direction` | integer | Street direction |
| `kitchen` | integer | 1 if listing has a kitchen, 0 otherwise |
| `ac` | integer | 1 if listing has air conditioning, 0 otherwise |
| `furnished` | integer | 1 if furnished, 0 otherwise |
| `location.lat` | float | Latitude |
| `location.lng` | float | Longitude |
| `path` | string | Path to the listing page |
| `user.review` | float | Average user reviews |
| `user.img` | string | User profile image |
| `user.name` | string | User name |
| `user.phone` | string | User phone number |
| `user.is_verified` | integer | 1 if user is verified, 0 otherwise |
| `user.rega_id` | integer | User registration ID |
| `native.logo` | string | Native listing logo |
| `native.title` | string | Native listing title |
| `native.image` | string | Native listing image |
| `native.description` | string | Native listing description |
| `native.external_url` | string | Native listing external URL |
| `rent_period` | integer | Rent period ID: 0=Yearly, 1=Daily, 2=Monthly, 3=Yearly |
| `city` | string | City name (Arabic) |
| `city_id` | integer | City ID |
| `district` | string | District name (Arabic) |
| `district_id` | integer | District ID |
| `width` | integer | Property width |
| `length` | integer | Property length |
| `advertiser_type` | string | Type of listing user |
| `create_time` | integer | Unix timestamp of listing creation |
| `has_extended_details` | integer | 1 if extended details available, 0 otherwise |
| `daily_rentable` | integer | 1 if daily rentable, 0 otherwise |

---


---

