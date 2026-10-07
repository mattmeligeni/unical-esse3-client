**English** | [Italiano](README.it.md)

# unical-esse3-client

A small Python client for the **Esse3 REST API** of the University of Calabria (Unical): sign-in, student
profile, courses, available exam sessions, bookings and grade averages, with an interactive terminal menu.

It is the prototype I used to explore and document the API before building the iOS app
**[MyUnical](https://github.com/mattmeligeni/MyUnical)**, and it is archived.

![Python](https://img.shields.io/badge/Python-3-3776AB?logo=python&logoColor=white)
![Status](https://img.shields.io/badge/status-archived-lightgrey)
![License](https://img.shields.io/badge/license-PolyForm%20Strict%201.0.0-lightgrey)

## What it covers

| Area | Endpoint family |
| --- | --- |
| Authentication | `/login` (HTTP Basic) |
| Profile and career | registry data, career segments, degree course |
| Exams | available sessions per course, session details, booked sessions |
| Averages | weighted and arithmetic averages from the transcript service |

## Usage

```bash
pip install -r requirements.txt
python play.py      # asks for Unical credentials (never stored) and opens the menu
```

`api_client.py` contains the `UnicalApiClient` class that the menu uses.

## License

Source-available under the [PolyForm Strict License 1.0.0](LICENSE): you may read the code and run it for
non-commercial purposes; you may not modify, redistribute or use it commercially without written permission.

---

<sub>© 2024-2026 [Mattia Meligeni](https://mattiameligeni.com) · Not affiliated with the University of Calabria or Cineca.</sub>
