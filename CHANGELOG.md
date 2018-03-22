## 0.4.0

- Support present `params` to `service_url` to oss image url.

for example:

```rb
@photo.image.service_url(params: { 'x-oss-process' => "image/resize,h_100,w_100" })
```

## 0.3.0

- Add `mode` config for setup OSS ACL, `mode: "private"` will always output URL that have signature info.
- Support `disposition: :attachment` option for `service_url` method for download original filename.

## 0.2.0

- Add url_for_direct_upload support.
- Fix delete_prefixed error when path not exists.

## 0.1.1

- Fix streaming upload.
- Fix delete by prefixed.
- Add full test.

## 0.1.0

- First release.
