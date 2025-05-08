```php
<?php

namespace github\users\alexsvorada;

class Profile {
    public string $greeting = '👋 Welcome to my profile.';

    public array $personal = [
        "name"     => '🧑‍💻 Alex Svorada',
        "title"    => '⚡ Fullstack Developer',
        "location" => '🌍 Prague, CZ',
    ];

    public array $stack = [
        "frameworks" => ['🐦‍⬛ EspoCRM'],
        "languages"  => ['🐘 PHP', '⚡ JavaScript', '☕ Java'],
        "other"      => ['🤖 Cursor', '🎨 TailwindCSS', '🐋 Docker', '🗄️ SQL', '📦 Git'],
    ];

    public array $contact = [
        "email"    => '📨 alex@svorada.eu',
        "linkedin" => '💼 linkedin.com/in/alexsvorada',
    ];
}
```
