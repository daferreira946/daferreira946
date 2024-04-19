### Social

* [LinkedIn](https://www.linkedin.com/in/daferreira946/)
* [Instagram](https://www.instagram.com/daferreira946)
* [Twitter](https://twitter.com/daferreira946)

```php
<?php

namespace Daferreira;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
    	// interactive links in the end
        return [
            'workplace' => [
                'company' => 'Mova.vc',
                'position' => 'TechLead and Senior Backend Engineer',      
            ],
            'degree' => [
                'computer_science' => [
                    'type' => 'bachelor',
                    'institution' => 'Petrolina College',
		    'site' => 'http://www.facape.br',
                    'concluded' => true,
                ],
		'computer_software_engineering' => [
                    'type' => 'post degree',
                    'institution' => 'Descomplica College',
		    'site' => 'https://descomplica.com.br/pos-graduacao',
                    'concluded' => true,
                ],
		'projects_in_cloud_computing' => [
                    'type' => 'post degree',
                    'institution' => 'Descomplica College',
		    'site' => 'https://descomplica.com.br/pos-graduacao',
                    'concluded' => true,
                ],
            ],
            'course' => [
                'alura' => [
                    'type' => 'professionalizing',
                    'site' => 'https://www.alura.com.br',
                    'full_certificate' => 'https://cursos.alura.com.br/user/daferreira1996/fullCertificate/0199177d83aab4b8b88edcfa32d7a5d2',
                    'completed' => [
                        'PHP training' => 'https://cursos.alura.com.br/degree/certificate/4e301603-e19e-4071-b70d-4130d24a86d7',
                        ... //others courses
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
                Jira::class,
            ],
            'languages' => [
                Php::class,
		Go::class
            ],
            'databases' => [
                MySql::class,
		Redis::class,
		Elastic::class
            ],
            'infrastructure' => [
                Git::class,
                Docker::class,
                DockerCompose::class,
		Kubernetes::class,
		GoogleCloudPlatform::class
            ],
            'utils' => [
                PHPUnit::class,
                Composer::class,
                GitLab::class,
                Make::class,
            ],
            'frameworks' => [
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
                Jira::class,
            ],
            'languages' => [
                Php::class,
                Javascript::class, //and Node.js/Typescript.js
                Python::class,
		Rust:class,
		Go::class
            ],
            'databases' => [
                MySql::class,
		Redis::class,
		Elastic::class,
                PostgreSQL::class,
                SQLite::class,
                MongoDB::class,
            ],
            'infrastructure' => [
                Git::class,
                Docker::class,
                DockerCompose::class,
		Kubernetes::class,
		GoogleCloudPlatform::class,
                Aws::class,
            ],
            'utils' => [
                PHPUnit::class,
                Composer::class,
                GitLab::class,
                Make::class,
                GitHub::class,
            ],
            'frameworks/libraries' => [
                Slim::class,
                Laravel::class,
                AdonisJS::class,
                Lumen::class,
                React::class,
		Nextjs::class,
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
### Links
* [FACAPE](http://www.facape.br)
* [Descomplica](https://descomplica.com.br/pos-graduacao)
* [Alura Full Certificate](https://cursos.alura.com.br/user/daferreira1996/fullCertificate/0199177d83aab4b8b88edcfa32d7a5d2)
* [Alura PHP Training](https://cursos.alura.com.br/degree/certificate/4e301603-e19e-4071-b70d-4130d24a86d7)
* [UpInside Bootstrap Builder](https://www.upinside.com.br/certificados/6260764202102)
* [UpInside Productive CSS with SASS](https://www.upinside.com.br/certificados/6260769202010)
* [UpInside DevTools Essentials](https://www.upinside.com.br/certificados/6260761202102)
* [HTML5 and CSS3 Essentials](https://www.upinside.com.br/certificados/6260760202010)


---------------------
Inspired by [Ash Baker](https://github.com/ashbakernz/ashbakernz)
