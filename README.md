## FileBrowser - Powerful Multi-User File Manager

FileBrowser is a free, open-source, self-hosted web application for managing files and folders.

You can manage files inside your local repository folder (on your server's hard drive) or connect to other storage adapters (see below).

FileBrowser has multi-user support, so you can have administrators and other users managing their files with different access permissions, roles and home folders.

All basic file operations are supported: copy, move, rename, edit, create, delete, preview, zip, unzip, download, upload.

If allowed, users can download multiple files or folders at once.

File upload supports drag&drop, progress bar, pause and resume. Upload is chunked so you should be able to upload large files regardless of your server configuration.

## Typical Use Cases
- Share a folder with colleagues, your team, friends or family,
- Allow workers to upload field data / docs / images,
- Use as cloud backup,
- Manage cdn with multiple people,
- Use as ftp/sftp replacement,
- Manage s3 or other 3rd party cloud storage,
- Use to quickly zip and download remote files.

## Documentation
[Check out the documentation](https://filebrowser.linuxforphp.net/documentation) here:

https://filebrowser.linuxforphp.net/documentation

## Features & Goals
- Multiple storage adapters (Local, FTP, Amazon S3, Dropbox, DO Spaces, Azure Blob and many others via [Flysystem](https://github.com/thephpleague/flysystem)),
- Multiple authentication adapters with roles and permissions (store users in a json file, database, or use WordPress),
- Multiple session adapters (native file, Pdo, Redis, MongoDB, Memcached, and others via [Symfony](https://github.com/symfony/symfony/tree/4.4/src/Symfony/Component/HttpFoundation/Session/Storage/Handler)),
- Single page front-end (built with [Vue.js](https://github.com/vuejs/vue), [Bulma](https://github.com/jgthms/bulma) and [Buefy](https://github.com/buefy/buefy)),
- Chunked uploads (built with [Resumable.js](https://github.com/23/resumable.js)),
- Zip and bulk download support,
- Highly extensible, decoupled and tested code,
- No database required.
