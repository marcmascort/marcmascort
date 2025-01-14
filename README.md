# Marc Mascort Bou

## Me
:e-mail: [marc@mmb-dev.com](mailto:marc@mmb-dev.com)<br>
📍 Cassà de la Selva, Girona, Catalunya<br>
🌐 Catalan / Spanish / English<br>
🎂 1986-09-16<br>

## Career
```php
$mmbCareer = new \Developer\Career(
  cv: 'https://www.linkedin.com/in/marcmascort',
  email: 'marc@mmb-dev.com',
  stack: ['PHP', 'JavaScript', 'Bash', 'MySQL'],
);

$mmbCareer->attach(new \Developer\Job(
  organization: 'Teladoc Health International',
  website: 'https://teladoc.com',
  location: 'remote',
  role: 'Senior Backend Engineer',
  from: new \DateTimeImmutable('2024-04-01', 'Europe/Madrid'),
));

$mmbCareer->attach(new \Developer\Job(
  organization: 'T4xi',
  website: 'https://t4xi.com',
  location: 'remote',
  team: 'eHealth (external for Teladoc)',
  role: 'Backend lead',
  from: new \DateTimeImmutable('2020-07-01', 'Europe/Madrid'),
  to: new \DateTimeImmutable('2024-03-31', 'Europe/Madrid'),
));

$mmbCareer->attach(new \Developer\Job(
  organization: 'Articstudio',
  website: 'https://articstudio.com',
  location: 'Girona',
  role: 'CTO / Developer',
  from: new \DateTimeImmutable('2013-01-01', 'Europe/Madrid'),
  to: new \DateTimeImmutable('2020-06-30', 'Europe/Madrid'),
));
```

## Open Source
🔜 Comming soon
