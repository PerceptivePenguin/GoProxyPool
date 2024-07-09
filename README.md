# GoProxyPool

## This project is a free IP proxy pool implemented using Golang and Redis. It provides functionalities to fetch a collection of proxy IPs from specific websites, store them in Redis, and filter out the valid ones. The system periodically retrieves and updates the list of valid proxy IPs, ensuring the pool remains current and effective. Additionally, the project includes a local web server with an API that allows users to access the list of valid proxy IPs.

## Features:
- Proxy IP Collection: Scrapes proxy IP addresses from designated websites.
- Storage: Stores collected proxy IPs in Redis for efficient management and retrieval.
- Validation: Regularly filters and updates the list of valid proxy IPs.
- API Access: Provides an API endpoint for accessing the current list of valid proxy IPs via a local web server.
- Scheduled Updates: Periodically fetches and validates new proxy IPs to ensure the pool is always up-to-date.

This project is ideal for developers and organizations needing a reliable source of free proxy IPs for various applications, such as web scraping and anonymity.

