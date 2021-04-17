```php
<?php

namespace Daferreira;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Incluir Tecnologia',
                'position' => 'Team Leader',      
            ],
            'degree' => [
                'computer science' => [
                    'type' => 'bachelor',
                    'institution' => 'Petrolina College',
                    'conclusion' => '2021.1',
                    'current' => true,
                ],
            ],
            'course' => [
                'alura' => [
                    'type' => 'professionalizing',
                    'site' => 'https://www.alura.com.br',
                    'full_certificate' => 'https://cursos.alura.com.br/user/daferreira1996/fullCertificate/0199177d83aab4b8b88edcfa32d7a5d2',
                    'completed' => [
                        'PHP training' => 'https://cursos.alura.com.br/degree/certificate/4e301603-e19e-4071-b70d-4130d24a86d7',
                        ... //54 others courses
                    ],
                ],
                'upinside' => [
                    'type' => 'professionalizing',
                    'site' => 'https://www.upinside.com.br',
                    'full_certificate' => null,
                    'completed' => [
                        'Bootstrap Builder' => 'https://www.upinside.com.br/certificados/6260764202102',
                        'Productive CSS with SASS' => 'https://www.upinside.com.br/certificados/6260769202010',
                        'DevTools Essentials' => 'https://www.upinside.com.br/certificados/6260761202102',
                        'HTML5 and CSS3 Essentials' => 'https://www.upinside.com.br/certificados/6260760202010',
                    ],
                ],
            ],
        ];
    }

    public function getKnowledgeUsedAtWork(): array
    {
        return [
            'management' => [
                Scrum::class,
                Trello::class,
            ],
            'languages' => [
                Php::class,
            ],
            'databases' => [
                MySql::class,
            ],
            'infrastructure' => [
                Git::class,
                Docker::class,
                Docker-compose::class,
            ],
            'utils' => [
                PHPUnit::class,
                Composer::class,
                GitLab::class,
                Make::class,
            ],
            'frameworks/libraries' => [
                Slim::class,
                CompanyPackages::class
            ],
        ];
    }
	
	public function getPersonalProjectsKnowledge(): array
    {
        return [
            'management' => [
                Scrum::class,
                Trello::class,
            ],
            'languages' => [
                Php::class,
                Javascript::class, //and Node.js/Typescript.js
                Python::class
            ],
            'databases' => [
                MySql::class,
                PostgreSQL::class,
                SQLite::class,
                MongoDB::class,
            ],
            'infrastructure' => [
                Git::class,
                Docker::class,
                Docker-compose::class,
                AWS::class,
            ],
            'utils' => [
                PHPUnit::class,
                Composer::class,
                GitLab::class,
                Make::class,
                GitHub::class,
            ],
            'frameworks' => [
                Slim::class,
                Laravel::class,
                AdonisJS::class,
                Lumen::class,
                React::class //Stack
            ],
        ];
    }

    public function getFutureGoal(): string
    {
        return [
            'To contribute to open source.',
            'Improve skills',
            'Be happy',
        ];
    }
}
```
