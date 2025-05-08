```php
<?php

namespace github\users\alexsvorada;

class Profile {
    public string $greeting = '👋 Welcome to my profile.';

    public array $personal = [
        "name"     => '🧑‍💻 Alex Svorada',
        "title"    => '⚡ Fullstack Software Developer',
        "location" => '🌍 Prague, CZ',
    ];

    public array $skills = [
        "frameworks" => ['🐦‍⬛ EspoCRM'],
        "languages"  => ['🐘 PHP', '⚡ JavaScript', '☕ Java'],
        "other"      => ['🤖 Cursor', '🐋 Docker', '🗄️ SQL', '📦 Git'],
    ];

    public array $contact = [
        "email"    => '📨 alex@svorada.eu',
        "linkedin" => '💼 linkedin.com/in/alexsvorada',
    ];
}
```
