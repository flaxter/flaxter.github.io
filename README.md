find / -type f \( -iname "*.mov" -o -iname "*.mp4" -o -iname "*.m4v" -o -iname "*.mts" -o -iname "*.avi" \) -size +50M -exec ls -lU {} + 2>/dev/null
