# Set up selenium and Firefox for running selenium tests.
![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

#### Requirements

* `java`

#### Variables

* `selenium_install_dir`: [default: `/opt`] Install directory
* `selenium_version`: [default: `2.53.0`] Install version
* `selenium_install_firefox`: [default: `no`] Whether to install FireFox
* `selenium_install_chrome`: [default: `yes`] Whether to install Google Chrome

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
  - selenium
```

#### Start/Stop/Restart Selenium

```
$ service selenium start
$ service selenium stop
$ service selenium restart
```

#### Known issue with Firefox

For some OS combinations the package manager version of Firefox 
doesn't work appropriately with Selenium. In these circumstances 
you may see an error like:

```
WebDriver\Exception\UnknownError: Unable to connect to host 127.0.0.1 on port 7055 after 45000 ms. Firefox console output:
```

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟

