
# AI Automated Invoice Agent 
A fully automated workflow built with n8n that takes an image sent to a Telegram bot, uploads it to Google Drive, extracts structured JSON using a Basic LLM model, stores the data as a new row in Google Sheets for budgeting, and finally sends a confirmation message back to the user on Telegram.

## Overview
This workflow automates the process of collecting receipts or expense images from Telegram and converting them into structured budgeting data.

## End‑to‑End Flow

User sends a picture to Telegram bot

n8n receives the image via Telegram Trigger

Image is uploaded to Google Drive

Basic LLM model extracts structured JSON (amount, category, date, notes, etc.)

JSON is appended as a new row in Google Sheets

Telegram bot replies confirming the entry

