# Release Notes

I will do my best to document the purpose of each version number bump here, in addition to the PR messages.

## 1.0

* I've been using the theme long enough to bump from 0.999 while testing to 1.0.
* I removed pagination on `_default/single.html` from 0.999 to 1.0 -- Micro.blog does not filter out replies and other strange content types from pagination. I can probably fix this by looking for `{{ if .Paginator.Pages "type" "post" }}` or similar, but I don't think it's worth futzing with for now.
