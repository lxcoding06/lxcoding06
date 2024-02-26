```php
<?php

namespace LXCODING666;

class Me
{
    static function says() {echo 'Hi, Im Laurent';}  

    }

    public function getStudied(): array
    {
        return [
                'study' => [
                'campus' => 'Amikom University Purwokerto'
                'faculty' => 'Informatics',         
                ]
            ];
    }

    public function getWorkedplace(): array
    {
        return [
            'workplaces' => [
            [
                'company' => 'Nemolab',
                'position' => 'Server Administrator',
                'since' => '2021',
                'until' => '2022'         
            ],
            [
                'company' => 'SS.CC BATAM CENTER',
                'position' => 'IT CONSULTANT',
                'since' => '2022',
                'until' => '2023'             
            ],
        ]
    ];
    }

    public function getKnowledgeNow(): array
    {
        return [
            Php::class,
            Javascript::class,
            NodeJs::class,
            Python::class,
            ReactNative::class,
            TailwindCss::class,
            Gcp::class,
            Azure::class,
            Server::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'Make My Dream Come Through.';
    }
}

?>
```
