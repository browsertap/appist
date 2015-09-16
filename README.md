application package manage for mac, windows, and linux.

#### Examples

```bash
appm install chrome@34   # can run on windows, linux, and mac
appm install ie@6        # install natively on windows, or download IE vm
appm publish             # publish a new package
```


#### TODO

- [ ] - run apps in their own container if possible
- [ ] - `install` should take platform into consideration when installing stuff
- [ ] - `.appmrc` file with JSON config
- [ ] - maintain application settings when switching verisons
  - zip files up
- [ ] - versions are to be tagged
- [ ] - dependencies can be used
- [ ] - binaries should be hosted somewhere else (they're unlikely going to change)
- [ ] - maybe take cask approach and 
