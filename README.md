![won't talk - don't wanna lie](https://www.aluxe.me/wp-content/uploads/2016/01/moj-php-mvc-framework-wide.jpg)

```php
<?php

namespace PavelPlotnikov;

class About extends Me
{
    /** @return Collection|Project[] */
    public function getProjects(): Collection
    {
        return collect([
            ['Soluls Like Coop', 'https://github.com/PavelPlot99/SoulsLikeCoopVue'],
        ])->mapInto(Project::class);
    }

    /** @return Knowledge[] */
    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Laravel::class,
            Docker::class,
            MySQL::class,
            RestfulApi::class,
            VueJs::class,
            Git::class,
            Vuetify::class,
            JavaScript::class,
        ];
    }

    public function getProfiles(): array
    {
        return [
            'vk'    => 'https://vk.com/6no_love6',
            'Telegram' => '@PaulPlotty',
        ];
    }

    public function getContacts(): array
    {
        return [
            'Email'    => 'pavel.plot99@gamil.com',
        ];
    }
}
```
