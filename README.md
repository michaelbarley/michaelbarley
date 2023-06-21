```php
<?php

namespace MichaelBarley;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'The Verve Group',
                'position' => 'Fullstack Software Engineer'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            TailwindCss::class,
            Aws::class,
        ];
    }

    public function getHobbiesAndInterests(): string
    {
        return [
            Coding::class,
            Cooking::class,
            Hiking::class,
            Movies::class,
        ];
    }
}
```
