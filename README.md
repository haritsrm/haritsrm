### Hi there 👋

<!--
**rietzche/rietzche** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<!-- ![](https://github.com/rietzche/rietzche/blob/main/header.png) --!>

```php
// ~/.tmp/Profile/Intro.php

<?php

namespace Facades\Rietzche;

use Facades\Rietzche\Media;
use Facades\Rietzche\Profile;
use Facades\Rietzche\Development;

class Intro
{

  /**
  * __invoke()
  * 
  * @params array $learning
  * @return error
  */
  public function __invoke(array $learning)
  {
    Profile::name = 'Harits Rahman Mazayamusthafa';
    Profile::alias = 'Rietzche';
    Profile::email = 'haritzrahman98@gmail.com'; // Email address is already taken
    
    Media::instagram = Media::twitter = '@haritsrm';
    
    Development::langs = [
      'backend' => 'php:laravel|javascript:node-js|java|python',
      'frontend' => 'javascript:react-js,vue-js',
      'database' => 'postgresql|mysql|mongodb|sqlite|elasticsearch|redis'
    ];
    Development::misc = [
      'devops' => 'gcp:gke,gcloudrun,gce|aws:ecs,s3|heroku',
      'tools' => 'terminal',
      'os' => 'mac-os'
    ];
    Development::experience = carbon('2017')->diffInYears();
    
    return $this($learning);
  }
  
}

```

```
- 🥱 I am currently working on backend:java,php|devops:gcp,aws.
- 🚀 Available for Freelance projects opportunities.
```

![](https://visitor-badge.laobi.icu/badge?page_id=rietzche.rietzche)
