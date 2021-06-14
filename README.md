```php
<?php

namespace LXCODING666;

class Me
{
    static function says() {echo 'Hi, Im Laurent';}  

    }

    public function getStudyNow(): array
    {
        return [
                'study' => [
                'faculty' => 'Informatics',
                'semester' => '2nd semester'         
                ]
            ];
    }

    public function getWorkplaceNow(): array
    {
        return [
            'workplace' => [
                'company' => 'SS.CC BATAM CENTER',
                'position' => 'IT CONSULTANT'         
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
        ];
    }

    public function getFutureGoal(): string
    {
        return 'Make My Dream Come Through.';
    }
}
```
