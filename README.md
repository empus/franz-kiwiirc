# Undernet Connect for Franz

This is the Franz recipe for Undernet Connect (https://chat.undernet.org)

The underlying webchat uses Kiwi IRC (https://kiwiirc.com)

Franz recipe credit to: Tiago Alves <tralves@gmail.com>


### Manual installation / development

1. Install the recipe

*nix systems:
```bash
cd Library/Application Support/Franz/recipes/dev # create the dev directory if needed
git clone https://github.com/empus/franz-kiwiirc kiwiirc
```

For Windows systems, clone (or download) the contents of the repo into the below directory:
```bash
%APPDATA%\Franz\recipes\dev\franz-kiwiirc
```

2. Reload Franz (View -> Reload Franz / Ctrl+Shift+R)

3. Add the new service in Franz. The service should appear under the `Development` tab.

### How to create your own Franz recipes:

- [Read the documentation](https://github.com/meetfranz/plugins)
