```php
<?php

namespace CosminSandu;

class About extends Me
{
    public function getCurrentWorkplace()
    {
        return [
            'workplace' => [
                'company' => 'SmartValue',
                'position' => 'Software Developer'         
            ]
        ];
    }

    public function getDailyKnowledge()
    {
        return [
            Symfony::class,
            Php::class,
            PhpStorm::class,
            Git::class,
            Docker::class,
            RabbitMQ::class,
            Jira::class,
            Javascript::class,
            Html::class,
            Css::class,
        ];
    }

    public function getLinks()
    {
        return [
            'https://github.com/cosminsandu',
            'https://cosminsandu.github.io/',
            'https://www.linkedin.com/in/sanducosminmihai/',
            'http://cosminsandu.ro/',
        ]
    }

    public function getFutureGoal()
    {
        return 'To contribute to open source.';
    }
}
```