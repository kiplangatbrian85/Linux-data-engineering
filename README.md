# Linux Fundamentals for Data Engineering

## Author
Brian Kiplangat — LuxDevHQ Data Engineering Cohort 8

---

## Server Details

| Detail | Value |
|---|---|
| Host | 159.65.222.96 |
| Linux User | briank |
| Database | briank |
| Schema | staging |
| Table | staging.farmers |

---

## Tasks Completed

- [x] SSH server access on port 22
- [x] Linux user creation (briank)
- [x] PostgreSQL setup and configuration
- [x] External connections enabled on port 5432
- [x] Database and schema creation
- [x] Sample data inserted into staging.farmers
- [x] 25 Linux commands documented
- [x] SCP file transfers (local to server and server to local)

---

## Repository Structure

| Folder | Contents |
|---|---|
| commands/ | 25 Linux commands with explanations |
| postgresql/ | Database setup steps and SQL files |
| screenshots/ | Screenshots of all commands and outputs |
| blog/ | Link to blog article |

---

## Blog Article

[Linux Fundamentals for Data Engineering](https://dev.to/kiplangat_brian/linux-fundamentals-for-data-engineering-5a9p)

---

## Technologies Used

![Linux](https://img.shields.io/badge/Linux-Ubuntu-orange)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-blue)
![Git](https://img.shields.io/badge/Git-GitHub-black)

- Ubuntu Linux
- PostgreSQL 16
- PostGIS
- SSH / SCP
- Git / GitHub

---

## How to Connect to the Database

```bash
psql -U briank -d briank -h 159.65.222.96 -p 5432
```

---

## Sample Data Preview

| id | farmer_name | county | subcounty | acreage | crop | loan_amount | loan_status | season |
|---|---|---|---|---|---|---|---|---|
| 1 | John Kipchumba | Uasin Gishu | Turbo | 2.50 | Maize | 15000.00 | Paid | 2023A |
| 2 | Mary Jelimo | Uasin Gishu | Soy | 1.80 | Maize | 12000.00 | Defaulted | 2023A |
| 3 | Peter Rotich | Uasin Gishu | Eldoret East | 3.20 | Maize | 20000.00 | Paid | 2023B |
| 4 | Grace Chebet | Uasin Gishu | Moiben | 1.00 | Maize | 8000.00 | Paid | 2023B |
| 5 | David Koech | Uasin Gishu | Kapseret | 4.50 | Maize | 30000.00 | Defaulted | 2024A |

---

*LuxDevHQ Data Engineering Cohort 8 Brian Kiplangat Kenya*
