# Example: preparing photos for a fast website

You've got a folder of phone photos and you need them blog-ready: smaller, web-format, no embedded GPS. Here's the chain.

## The workflow

### 1. Convert from HEIC (iPhone) to JPG

If you're on an iPhone, your photos are likely **HEIC**. Many browsers and CMS platforms don't support it.

Use **[HEIC → JPG](https://100tools.site/tools/heic-to-jpg)** — drop the files in, download converted JPGs. Browser-side, no upload.

### 2. Strip metadata (GPS, camera serial, etc.)

Photos carry EXIF metadata you usually don't want public.

- Check what's there with **[EXIF Viewer](https://100tools.site/tools/exif-viewer)**
- Strip it with **[Image Metadata Remover](https://100tools.site/tools/image-metadata-remover)**

### 3. Resize to your target dimensions

Phone photos are often 4000+ px wide — far more than a blog needs.

Use **[Image Resizer](https://100tools.site/tools/image-resizer)** to get to 1600 × 1067 (or your CMS's recommended size).

### 4. Compress for speed

Use **[Image Compressor](https://100tools.site/tools/image-compressor)** to drop file size 60–80 % without visible quality loss.

### 5. (Optional) Convert to WebP

Modern browsers prefer WebP. Use **[Image → WebP](https://100tools.site/tools/image-to-webp)** for an extra ~25 % size drop.

### 6. (Optional) Bulk-convert

If you have lots of photos, **[Bulk Image Converter](https://100tools.site/tools/bulk-image-converter)** runs the same conversion on a folder of images in one pass.

## Result

A folder of fast-loading, privacy-respecting, web-ready images. Lighthouse will love you.

---

Got a workflow worth sharing? **[Open a PR](../CONTRIBUTING.md)** and add a file under `examples/`.
