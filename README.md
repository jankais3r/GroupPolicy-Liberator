# GroupPolicy-Liberator (ノಠ益ಠ)ノ ︵ ʎɔᴉlod
*Break the chains imposed by your corporate GroupPolicy with a simple Scheduled Task*

We all know the situation. You work for a big corporation and they have opinions about what you're allowed to do with your computer. E.g. which browser extensions you can install or which system features you can use. That's annoying, and often unreasonable. So I give you this scheduled task template, which by defaults executes automatically in the background every time your computer runs `gpupdate` and it deletes whatever part of the GroupPolicy that you don't like. Completely seamless. Just edit the Actions tab and you're good to go.

Installation steps:
1) Open Task Scheduler
2) Right-click Task Sheduler Library > Import task…, select `Group Policy Liberator.xml`
3) Go to Actions tab, click Edit…, and modify the command to remove specific registry keys imposed by your GroupPolicy (the provided example enables Google Translate and removes Chrome Extension restrictions)
