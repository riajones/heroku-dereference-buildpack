Recursively dereferences all symlinks in the build directory.

This allows [subdirectories](https://github.com/timanovsky/subdir-heroku-buildpack) to be built which contain symlinks to other parts of the repo.

NOTE: This should be added BEFORE other build processes to avoid clobbering generated symlinks.
