# Cali Tourism Insights

**What do tourists actually do in Cali, Colombia, and what does that mean for local businesses?**

I'm a tour guide in Cali. Every week I see where visitors go, what they ask for and what they pay for, but none of it is measured. This project turns that experience into data.

> **Status: in progress.** I'm building this while I learn SQL, Python and data visualization. Follow the roadmap below to see where it stands.

## Questions I want to answer

1. Which activities are most popular with visitors: salsa, food, city tours, nature or birdwatching?
2. How does demand change by month, season and day of the week?
3. Where do visitors come from, and does that change what they book?
4. How big is the opportunity for nature and birdwatching tourism around Cali?

## Data

| Source | What it adds |
|---|---|
| My own tour records (anonymized) | Activities, group sizes, dates and visitor origin, straight from the field |
| Public tourism statistics for Cali and Valle del Cauca | The bigger picture to compare my records against |

No names or personal details are stored. Each tour becomes one anonymous row.

### Planned structure: `tours` table

| Column | Type | Example |
|---|---|---|
| `tour_date` | date | 2026-11-14 |
| `activity` | text | birdwatching |
| `location` | text | Km 18 |
| `group_size` | integer | 4 |
| `visitor_origin` | text | United States |
| `price_cop` | integer | 180000 |
| `duration_hours` | decimal | 5.5 |
| `booking_channel` | text | Instagram |

## Tools

- **SQL** to store and query the tour records
- **Python (pandas)** to clean and explore the data
- **Data visualization** to turn findings into charts anyone can read

## Roadmap

- [x] Define the questions
- [x] Design the dataset structure
- [ ] Collect and anonymize the first month of tour data
- [ ] First SQL queries: most popular activities, busiest days
- [ ] Clean and explore the data in Python
- [ ] Charts and first findings
- [ ] Write up what I learned

## Project structure (planned)

```
cali-tourism-insights/
├── data/          # anonymized datasets
├── sql/           # queries
├── notebooks/     # Python exploration
└── charts/        # visualizations
```

## About me

Tour guide in Cali becoming a data analyst. See more at [github.com/gallelab](https://github.com/gallelab).
