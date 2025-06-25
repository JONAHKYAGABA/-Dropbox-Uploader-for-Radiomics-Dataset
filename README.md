📦 Dropbox Uploader for Radiomics Dataset
This project provides a simple Python script to zip a dataset from Google Drive and upload it to Dropbox in chunks using the Dropbox API. It is particularly useful for handling large radiomics datasets used in medical imaging research.

🚀 Features
Mounts Google Drive in Colab to access datasets

Zips a specified directory (e.g., Segmented_Radiomic/)

Uploads the zipped file to Dropbox using chunked upload (for large files)

Handles files larger than 150MB using Dropbox sessions
🔐 Security Warning
Do NOT expose your Dropbox access token publicly. In production, use secure storage mechanisms like environment variables or encrypted vaults.

📈 Customization
You can customize:

The chunk size (chunk_size argument)

Dropbox path (dropbox_path)

Local file path (local_path)

Folder to zip
