



[![Docs](https://img.shields.io/badge/docs-latest-brightgreen.svg)](http://doc.servertribe.com)
[![Discord](https://img.shields.io/discord/844971127703994369)](http://discord.servertribe.com)
[![Docs](https://img.shields.io/badge/videos-watch-brightgreen.svg)](https://www.youtube.com/@servertribe)
[![Generic badge](https://img.shields.io/badge/download-latest-brightgreen.svg)](https://www.servertribe.com/community-edition/)

# Windows Storage cmdlets

Work with Windows Storage Management PowerShell cmdlets to provide an 
advanced, user-friendly interface for managing storage resources in 
Windows environments.

[Windows Storage Management-specific cmdlets](https://learn.microsoft.com/en-us/powershell/module/storage/?view=windowsserver2022-ps)

[GitHub Project](https://github.com/Attune-Automation/Windows-Storage-cmdlets)




# Attune

[Attune](https://www.servertribe.com/)
automates and orchestrates processes to streamline deployments, scaling,
migrations, and management of your systems. The Attune platform is building a
community of sharable automated and orchestrated processes.

You can leverage the publicly available orchestrated blueprints to increase
your productivity, and accelerate the delivery of your projects. You can
open-source your own work and improve existing community orchestrated projects.

## Get Started with Attune, Download NOW!

The **Attune Community Edition** can be
[downloaded](https://www.servertribe.com/comunity-edition/)
for free from our
[ServerTribe website](https://www.servertribe.com/comunity-edition/).
You can learn more about Attune through
[ServerTribe's YouTube Channel](https://www.youtube.com/@servertribe).







# Clone this Project

To clone this project into your own instance of Attune, follow the
[Clone a GIT Project How To Instructions](https://servertribe-attune.readthedocs.io/en/latest/howto/design_workspace/clone_project.html).




## Blueprints

This Project contains the following Blueprints.



### Create a bootable disk

Create a bootable USB drive on using the Windows Storage cmdlets, 
this blueprint streamlines the process, ensuring accuracy and saving time.

Upon completion, you will have a ready-to-use bootable USB drive for 
compatible systems. This automated blueprint reduces the complexity and 
potential for errors in creating bootable media, making it a valuable 
tool for IT professionals and end-users alike.




## Parameters


| Name | Type | Script Reference | Comment |
| ---- | ---- | ---------------- | ------- |
| Disk Serial Number | Text | `diskserialnumber` | Use the `Get-Disk` cmdlet to get the Disk Serial Number.<br><br>[Get-Disk documentation](https://learn.microsoft.com/en-us/powershell/module/storage/get-disk?view=windowsserver2022-ps) |
| Windows Worker | Windows Node | `windowsworker` |  |
| Windows Worker User: Administrator | Windows Credential | `windowsworkeruseradministrator` |  |
| Worker Base Directory | Text | `workerbasedirectory` |  |




## Files

| Name | Type | Comment |
| ---- | ---- | ------- |






# Contribute to this Project

**The collective power of a community of talented individuals working in
concert delivers not only more ideas, but quicker development and
troubleshooting when issues arise.**

If you’d like to contribute and help improve these projects, please fork our
repository, commit your changes in Attune, push you changes, and create a
pull request.

<img src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-pull-request-01.png" alt="pull request"/>

---

Please feel free to raise any issues or questions you have.

<img src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-get-help-02.png" alt="create an issue"/>


---

**Thank you**
