# EasyTk Data Usage Policy

**Effective Date:** January 2026
**Last Updated:** January 2026

## Overview

This document explains in detail how EasyTk handles data throughout the video saving process. Our commitment is to process only what's necessary and retain nothing beyond the immediate task.

## Data Flow Diagram

```
User Device          EasyTk Servers              Source Platform
    |                      |                           |
    |---(1) Video URL----->|                           |
    |                      |---(2) Fetch Video-------->|
    |                      |<---(3) Video Data---------|
    |<--(4) Video File-----|                           |
    |                      |---(5) Auto-Delete-------->X
    |                      |
```

## Types of Data Processed

### 1. Video URLs
- **What:** Links to public videos you paste into the app
- **Processing:** Sent to our servers to identify and fetch the video
- **Storage:** NOT stored - used only for immediate processing
- **Retention:** None - discarded after video is fetched

### 2. Video Files
- **What:** The actual video content you're saving
- **Processing:** Temporarily held on our servers during download preparation
- **Storage:** Temporarily on servers (max ~4 minutes), then on your device
- **Retention:** Server copy auto-deleted; device copy permanent until you delete

### 3. Download History
- **What:** Record of URLs you've processed and their status
- **Processing:** Created and managed entirely on your device
- **Storage:** Local device storage only (UserDefaults)
- **Retention:** Until you clear history or uninstall app

### 4. Points and Activity
- **What:** Your earned points and activity log
- **Processing:** Calculated and stored locally
- **Storage:** Local device storage only (UserDefaults)
- **Retention:** Until you uninstall app

### 5. App Settings
- **What:** Your preferences (haptics enabled, etc.)
- **Processing:** Stored locally
- **Storage:** Local device storage only
- **Retention:** Until you uninstall app

## What We DO NOT Process

- Your personal identity
- Your location
- Your contacts
- Your browsing history
- Your device contents (photos, files, etc.)
- Any data unrelated to the specific video you're saving

## Server-Side Processing Details

### Temporary Processing
When you request a video download:

1. Our server receives the video URL
2. Server fetches video from the source
3. Video is prepared for download
4. Video is transmitted to your device
5. Server-side copy is queued for deletion
6. Automatic cleanup occurs within ~4 minutes

### No Logging Policy
Our servers do not maintain logs of:
- Which URLs were processed
- When downloads occurred
- Who requested downloads
- IP addresses of users

## Third-Party Data Sharing

### We Share Nothing
EasyTk does not share, sell, rent, or trade any user data with third parties.

### Advertising Note
Google AdMob (our ad provider) may collect limited device identifiers for ad serving. This is governed by Google's privacy policy and can be controlled in your device settings.

## Data Security Measures

### In Transit
- All communications use HTTPS/TLS encryption
- No unencrypted data transmission

### At Rest
- Server-side data is temporary (auto-deletes)
- Local device data is protected by iOS security

### Access Control
- No human access to processed videos
- Automated systems only

## Your Data Rights

### Local Data Control
You have full control over local data:
- View history in the app
- Clear history in Settings
- Uninstall app to remove all local data

### Server Data
Since we don't retain server data, there's nothing to request, modify, or delete.

## Changes to Data Practices

If we ever change how we handle data:
- We will update this document
- Material changes will be communicated via app update notes
- Continued use implies acceptance of changes

## Questions

For questions about our data practices:

**Email:** muhammadharisgift1@gmail.com

---

*This policy supplements our Privacy Policy and Terms of Service.*
