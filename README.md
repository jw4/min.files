# min.files (archived)

This repository is no longer maintained. Its contents have been merged into
[johnweldon/dotfiles](https://github.com/johnweldon/dotfiles), which now serves
the minimal set through a `minimal` install profile.

## Use the minimal profile instead

```bash
DOTFILES_PROFILE=minimal sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply \
  https://github.com/johnweldon/dotfiles.git
```

For an ephemeral box (apply once, then remove chezmoi and its source), use `--one-shot` instead of `--apply`.

The `minimal` profile installs the same lean set this repo provided -- shell,
git, vim, and ssh config -- plus a few lightweight git helper scripts, while
excluding the heavy desktop pieces (Neovim, Homebrew Brewfile, VNC). See the
[dotfiles README](https://github.com/johnweldon/dotfiles#readme) for details.

This repo is kept read-only for history.
