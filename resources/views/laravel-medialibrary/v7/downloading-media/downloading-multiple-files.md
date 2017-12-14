---
title: Downloading multiple files
---

You might want to let users be able to download multiple files at once. Traditionally you'd have to create a zip archive that contains the requested files.

The medialibrary is able to zip stream multiple files on the fly. So you don't need to create a zip archive on your server.

The provided `ZipStreamResponse` class that allows you to respond with a stream. Files will be zipped on the fly and you can even include files from multiple filesystems.

Here's an example on how it can be used:

```php
use Spatie\MediaLibrary\Models\Media;

class DownloadMediaController
{
   public function download(Media $mediaItem)
   {
        // Let's get some media.
        $media = $yourModel->getMedia('downloads');

        // Download the files associated with the media in a streamed way.
        // No prob if your files are very large.
        return ZipStreamResponse::create('my-files.zip')->addMedia($allMedia);
   }
}
```
