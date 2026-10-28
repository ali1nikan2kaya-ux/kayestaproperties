# Kayesta Properties website

This folder contains the optimized public website. Put its contents at the root of the website repository. Keep index.html at the root and preserve all folder names.

Upload the extracted files with GitHub Desktop or Git. This website contains hundreds of files, so uploading through the browser may need multiple batches. A ZIP file stored in a repository does not deploy the website by itself.

## Hosting

Serve this as a static site with this folder as the publish directory; there is no build step. The domain must point to the hosting provider.

The AI mascot requires a separate backend providing /api/assistant and /api/assistant/speech on the hosted domain. A static host alone does not provide that backend. Never commit API keys or private credentials. Consultation delivery still requires its backend configuration.

## Optimization

Image paths, dimensions, decoded pixels, page URLs and application code are unchanged from the original backup. JPEG and WebP files are retained byte-for-byte. Only pixel-exact PNG compression is applied where it saves space. Unused design preview folders and unreferenced portrait originals are excluded. Original files are backed up separately on the local computer, outside this upload folder.
