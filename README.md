# Autumn

### File Uploads

- Only allow one file per upload, take whatever the first field in the payload is and save it.
- Save with unique id, filename is stored in database.
- Serve files under `autumn.revolt.chat/i/unique_id/filename.jpg`