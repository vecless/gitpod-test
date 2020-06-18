# gitpod-test

I was testing gitpod.io with an FRC/WPILib robot project. Findings detailed below.

## Findings

The main "problem" this investigation was trying to solve was the platform incompatibility barrier for students. Gitpod would ideally serve as a temporary (or perhaps permanent) alternative to a Windows/Mac machine.

I don't think this can be the case.

### Stuff that worked

Grabbing the WPILib extension wasn't a serious struggle, you just need to drag-drop the `.vsix` file into Gitpod.

### Stuff which worked less

Desktop simulation tasks, deployment, etc. don't work and give a generic `"an error has occurred"` failure message. This may have been the expectation going in, but it's still a little unfortunate. Oh well...

It looks like extensions modifications would be required to make the Gitpod workspace more useful for FRC for sure. I don't think that that's something I'm willing to dive into. But it'll be cool if someone manages to make a more complete Gitpod workspace for FRC for sure. Maybe deployment is unlikely, but simulation would be a very nice thing to have.

## Conclusion

This is probably good enough to do FRC programming but you lose a non-zero set of things which are pretty useful. Not great.

This is probably an okay option for "plain old Java projects", though. I'll probably take a look at that next, but I can't imagine there being too many .
