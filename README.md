<h1 align=center> Hi from Indonesia 👋 </br> Harits Rahman Mazayamusthafa</h1>
<p align=center>
  <img src="https://img.shields.io/discord/980034204236668958?style=plastic" />
  <img src="https://img.shields.io/github/followers/rietzche?style=plastic" />
  <a href="https://github.com/sponsors/rietzche"><img src="https://img.shields.io/static/v1?label=Sponsor%20rietzche&message=%E2%9D%A4&logo=GitHub" /></a>
  <img src="https://visitor-badge.laobi.icu/badge?page_id=rietzche.rietzche" />
</p>
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

<!-- ![](https://github.com/rietzche/rietzche/blob/main/header.png) -->

```php
/**
*
* My Name is Harits Rahman Mazayamusthafa
*
*/

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
<p align=center>
<a href="https://github.com/rietzche"><img align="center" src="https://github-readme-stats.vercel.app/api?username=rietzche&show_icons=true&theme=nord&hide_border=true&hide_title=true" alt="rietzche github stats" /></a>     <a href="https://github.com/rietzche"><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rietzche&layout=compact&theme=nord&hide_border=true" /></a>
</p>
