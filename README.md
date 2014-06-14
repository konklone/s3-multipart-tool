# s3-multipart-tools

A simple command line tool to manage S3 multipart uploads.

### Installation

```
$ npm install -g s3-multipart-tool
```

### Usage

View all __current uploads__ (either in "successful" progress or those that have failed):

```
$ s3mp uploads [bucket_name]
```

__Abort all__ current uploads in the specified bucket:

```
$ s3mp abort-all [bucket_name]
```

__Abort__ an upload by key name and upload ID:

```
$ s3mp abort [bucket_name] [key_name] [upload_id]
```