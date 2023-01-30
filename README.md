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

### :hammer_and_wrench: Languages and Tools :
<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/php/php-original.svg" title="PHP" alt="PHP" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/laravel/laravel-plain-wordmark.svg" title="Laravel" alt="Laravel" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/mysql/mysql-original-wordmark.svg" title="MySQL" alt="MySQL" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/phpstorm/phpstorm-original.svg" title="PHPStorm" alt="PHPStorm" width="40" height="40"/>&nbsp;
    
  <img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-plain-wordmark.svg"  title="CSS3" alt="CSS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="40" height="40"/>&nbsp;
   <img src="https://github.com/devicons/devicon/blob/master/icons/vuejs/vuejs-original.svg" title="Vue" alt="Vue" width="40" height="40"/>&nbsp;
   <img src="https://github.com/devicons/devicon/blob/master/icons/docker/docker-original.svg" title="Docker" alt="Docker" width="40" height="40"/>&nbsp;
   <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original-wordmark.svg" title="Git" **alt="Git" width="40" height="40"/>&nbsp;
</div>
