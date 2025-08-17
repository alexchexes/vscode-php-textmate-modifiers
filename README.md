Adds extra TextMate scopes for PHP modifiers so you can style them separately:
- storage.modifier.access.php (public/private/protected)
- storage.modifier.static.php
- storage.modifier.readonly.php
- storage.modifier.final.php
- storage.modifier.abstract.php

## Notes
• `injectionSelector` ensures we only inject into PHP, and not inside strings/comments.
• The `static` regex avoids `static::` (static late binding) so we don’t style that usage