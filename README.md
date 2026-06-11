# first-db-app

A browser-based IndexedDB customer database explorer built with HTML, CSS, and JavaScript.

## About

Demonstrates how to use IndexedDB — a built-in browser database — to load, query, and clear structured customer data. Includes a live notification panel, execution log, and scrollable query results table.

## Features

- [x] Control panel with Load DB, Query DB, and Clear DB buttons
- [x] Notification panel showing status messages for each operation
- [x] Scrollable execution log with timestamps for all actions
- [x] Scrollable query results table showing all customer records
- [x] Empty state message when no data is loaded
- [x] Load DB populates IndexedDB with customer data
- [x] Query DB retrieves and displays all customers from IndexedDB
- [x] Clear DB removes all rows from the database
- [x] Button states enabled/disabled based on app state (bonus)
- [x] Additional customer fields: Last Order date and Total Sales for the year (bonus)
- [x] Retrospection answers included in the page (bonus)

## Button State Table

| State               | Load DB  | Query DB | Clear DB |
|---------------------|----------|----------|----------|
| Initial App display | enabled  | enabled  | disabled |
| Load DB clicked     | disabled | enabled  | enabled  |
| Query DB clicked    | disabled | enabled  | enabled  |
| Clear DB clicked    | enabled  | enabled  | disabled |

## Tech Stack

- HTML
- CSS
- JavaScript (vanilla)
- IndexedDB (browser built-in)

## How to run

Open `index.html` in your browser — no build tools needed.
