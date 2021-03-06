## 1.1.0 (Unreleased)

ENHANCEMENTS:

* Add `excludes` to the `archive_file` data source to exclude files when using `source_dir` [GH-18]

BUG FIXES:

* Fix zip file path names to use forward slash on Windows [GH-25]
* Fix panic in `filepath.Walk` call [GH-26]

## 1.0.3 (March 23, 2018)

BUG FIXES:

* Fix modified time affecting zip contents and causing spurious diffs ([#16](https://github.com/terraform-providers/terraform-provider-archive/issues/16))

## 1.0.2 (March 16, 2018)

BUG FIXES:

* Fix issue with flags not being copied on a single file and regression introduced in 1.0.1 ([#13](https://github.com/terraform-providers/terraform-provider-archive/issues/13))

## 1.0.1 (March 13, 2018)

BUG FIXES:

* Fix issue with flags not being copied in to archive ([#9](https://github.com/terraform-providers/terraform-provider-archive/issues/9))

## 1.0.0 (September 15, 2017)

* No changes from 0.1.0; just adjusting to [the new version numbering scheme](https://www.hashicorp.com/blog/hashicorp-terraform-provider-versioning/).

## 0.1.0 (June 20, 2017)

NOTES:

* Same functionality as that of Terraform 0.9.8. Repacked as part of [Provider Splitout](https://www.hashicorp.com/blog/upcoming-provider-changes-in-terraform-0-10/)
