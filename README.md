# Jobs in Egypt and the MENA Region Scraper

A Python web scraping project that extracts job listings from **Wuzzuf** using its hidden JSON APIs instead of parsing HTML pages.

The project automatically retrieves job summaries, fetches detailed information in batches, cleans the nested JSON response, and exports the results to a structured Excel (.xlsx) file.

---

## Features

- Hidden API scraping
- Automatic pagination
- Batch requests for job details
- JSON data extraction
- Data cleaning
- Export structured job data to Excel (.xlsx)

---

## Extracted Fields

| Column | Description |
|--------|-------------|
| company_name | Company name |
| title | Job title |
| country | Country |
| city | City |
| area | Area |
| careerLevel | Career level |
| workplaceArrangement | Workplace arrangement |
| workTypes | Work type |
| workExperienceYears | Required years of experience |
| vacancies | Number of vacancies |
| postedAt | Posting date |
| keywords_text | Skills / Keywords |
| MiniSalary | Minimum salary |
| MaxSalary | Maximum salary |
| currency | Salary currency |
| period | Salary period |
| educationLevel | Required education level |
| job link | Job URL |

---

## Technologies

- Python
- Requests
- Pandas

---

## Project Structure

```
wuzzuf-scraper/
│
├── scraper.py
├── README.md
├── requirements.txt
└── data/
    └── jobs.xlsx
```

---

## Learning Outcomes

This project was built as part of my Web Scraping learning journey.

Topics explored during development:

- Hidden APIs
- Browser DevTools
- Postman
- JSON APIs
- Pagination
- Batch Requests
- URL Length Limit (HTTP 414)
- Data Cleaning
- Function-based project structure

---

## Future Improvements

- Retry mechanism
- Support additional job platforms

---

## License

This project is intended for educational purposes.