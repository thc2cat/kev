# CISA KEV Web Interface

A user-friendly web interface designed to consume, display, and search the CISA Catalog of Known Exploited Vulnerabilities (KEV) JSON feed. This project aims to provide an accessible and interactive way to explore critical vulnerability data.

## 🚀 Features

Use a local retrieved CISA KEV catalog data via wget

Search Functionality: Quickly find specific vulnerabilities by CVE ID, vendor, product, or vulnerability name.

Filter Options: Refine your view by various criteria .

Detailed View: Click on any vulnerability to see comprehensive details, including vendor, product, vulnerability name, date added to KEV, required action, due date, and a link to the CISA advisory.

Clear & Intuitive UI: Designed for ease of use, making complex data easy to digest.

## 🛠️ Technologies Used

Frontend:

HTML5

CSS3 (with Tailwind CSS for rapid styling)

VueJS

Data Source:

CISA Catalog of Known Exploited Vulnerabilities (KEV) JSON feed localy downloaded.

## ⚙️ Installation

```shell
git clone https://github.com/thc2cat/kev/
cd data
make
then you cat serve data/ in any webserver as static content
```
