find -E / -type f -size +5M -iregex '.*\.(mov|mp4|m4v|mts|m2ts|avi|wmv|mpg|mpeg|mod|tod|vob)' -exec ls -lh {} + 2>/dev/null
